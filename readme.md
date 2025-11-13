# 🌐 Web Page Summarizer

A simple and effective **web page text summarizer** built using Python and the **Sumy** NLP library.  
This notebook extracts text from a webpage and generates a concise summary using natural language processing techniques.

## 🚀 Features
- Summarizes any webpage by URL  
- Adjustable summary length (sentence count)  
- Built-in interactive Jupyter widget for easy use  
- Uses `sumy`, `nltk`, and `ipywidgets`  

## 🧠 How It Works
1. Fetches webpage content using `HtmlParser`.
2. Tokenizes and processes text with `nltk`.
3. Applies **Latent Semantic Analysis (LSA)** summarization.
4. Displays a readable summary directly in the notebook.

## 🧩 Installation

```bash
pip install -r requirements.txt
