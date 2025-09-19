# GPT-2-QUICKSTART

A hands-on Jupyter notebook that demonstrates **text generation with Hugging Face Transformers** (GPT-2) using both the high-level `pipeline` API and the lower-level `generate()` interface with custom decoding settings.

> Notebook: `Hugging_face_text_generation.ipynb`

---

## What you’ll learn

- Load and run GPT-2 via `transformers` `pipeline("text-generation")`
- Use `AutoTokenizer` + `AutoModelForCausalLM` directly
- Configure decoding (`max_new_tokens`, `temperature`, `top_p`, `do_sample`, `num_return_sequences`)
- Compare different sampling settings and outputs
- Save/clear GPU/CPU cache, basic reproducibility tips

---

## Requirements

- Python 3.9+  
- Recommended: GPU with CUDA (optional but faster)

```bash
pip install "transformers>=4.44" "torch>=2.2" "accelerate>=0.28" "huggingface_hub>=0.24"
