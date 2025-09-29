# AI Ecommerce Chatbot for Amazon (Prototype)

This project presents a prototype of an **Ecommerce chatbot** tailored for Amazon-style product interactions, implemented in a Jupyter Notebook (**`amazon_ecommerce_chatbot.ipynb`**).  

It demonstrates how a conversational agent can answer user queries, recommend or retrieve product info, and engage in simple dialogue.

---

## 🧩 Features & Workflow

- Ingest or simulate an Amazon product catalog (product names, descriptions, images)  
- Build or load embeddings / feature representations of products  
- Use a language model (e.g. HuggingFace or other LLM) to interpret user queries  
- Retrieve relevant products or information via similarity / retrieval  
- Generate responses combining context + retrieved product data  
- (Optionally) handle basic dialog state, turn-taking, fallback handling  

---

## 📦 Dependencies

You’ll typically need:

- Python 3.8+  
- Jupyter Notebook  
- `transformers`  
- `torch`  
- Similarity / embedding libraries (e.g. `sentence_transformers`)  
- Any dataset / storage for product catalog  
- Possibly additional packages like `faiss`, `sklearn`, etc.

Install via:

```bash
pip install transformers torch sentence-transformers faiss-cpu
```
---
## Clone the repo
```
git clone https://github.com/chandrasai-Durgapu/AI-Ecommerce-ChatbotAmazon.git
cd AI-Ecommerce-ChatbotAmazon
```
## Launch the repo
```
jupyter notebook amazon_ecommerce_chatbot.ipynb
```
---
