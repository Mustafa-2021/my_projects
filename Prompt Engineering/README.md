# Prompting an LLM using Hugging Face

Delve into crafting effective prompts for large language models with Hugging Face’s Transformers library.

---

## 🔍 Notebook Overview

- **Environment Setup**: Install and import the `transformers` library.  
- **Model & Tokenizer Loading**: Load pre‑trained LLMs (e.g., GPT‑2, GPT‑Neo) and their tokenizers.  
- **Prompt Engineering Techniques**:  
  - Zero‑shot prompts  
  - Few‑shot examples  
  - Instruction tuning formats  
- **Response Generation**: Generate text continuations, control length, and tweak decoding strategies (top‑k, top‑p, temperature).  
- **Evaluation & Comparison**: Compare outputs across different prompt styles and model sizes.  
- **Best Practices**: Tips for reducing bias, improving relevance, and handling model limitations.

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.x  
- **Libraries**:  
  - transformers  
  - torch (PyTorch)  
  - tensorflow (optional)  
  - tokenizers
 

You can install them via:

```bash
pip install transformers torch tensorflow tokenizers

How to run:
jupyter notebook Prompting_an_LLM_using_hugging_face.ipynb
