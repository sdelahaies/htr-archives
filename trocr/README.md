# htr-archives

## trocr


### Set up environment

```bash
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
uv pip install jiwer
```

### Content

This repository contains the following notebooks:


| `finetune_trocr_catmus.ipynb`               | Notebook based on the Niels Rodge's original Tutorial for finetuning trocr. |  
| `finetune_trocr_lora_generic.ipynb`         | Lora finetuning for trocr. |
| `dpo_trocr_custom.ipynb`             | A pytorch reference free Direct preference optimization implementation for trocr. |
