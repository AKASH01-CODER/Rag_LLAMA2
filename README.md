# Rag_LLAMA2
This repository contains the implementation of chatbot using RAG and llama2 llm.  

-Required libraries:
  pypdf2
  transformers
  sklearn
  os
  gradio
  nltk
  torch

-First install the all requied libraries then import necessary libraries
    import os
    import PyPDF2
    import nltk
    import torch
    import gradio as gr
    from nltk.tokenize import sent_tokenize
    from sklearn.feature_extraction.text import TfidfVectorizer
    from sklearn.metrics.pairwise import cosine_similarity
    from transformers import AutoTokenizer, AutoModelForCausalLM

-After importing all this library you can run the code which is present in code.ipynb file
-After running you can see the UI where you have to upload PDF file and then you can ask question on that PDF.

