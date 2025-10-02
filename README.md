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

## Demo Screenshots

## 💬 Chatbot Demo

![Chatbot Interface 1](https://raw.githubusercontent.com/chandrasai-Durgapu/AI-Ecommerce-ChatbotAmazon/main/amazon-ecommerce-cahtbot1.png)

![Chatbot Interface 2](https://raw.githubusercontent.com/chandrasai-Durgapu/AI-Ecommerce-ChatbotAmazon/main/amazon-ecommerce-cahtbot2.png)

![Chatbot Interface 3](https://raw.githubusercontent.com/chandrasai-Durgapu/AI-Ecommerce-ChatbotAmazon/main/amazon-ecommerce-cahtbot3.png)

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
## Set Up a Python Environment:

It's recommended to use a virtual environment:
```bash
python -m venv chatbot-env
source chatbot-env/bin/activate  # On Windows, use `chatbot-env\Scripts\activate`
```
## Launch the repo
```
jupyter notebook amazon_ecommerce_chatbot.ipynb
```
---
## Use Cases

This AI-powered chatbot prototype is ideal for:

E-commerce Platforms: Enhancing user experience through conversational interfaces.

Product Discovery: Assisting users in finding products based on natural language queries.

Customer Support: Providing automated responses to common customer inquiries.
