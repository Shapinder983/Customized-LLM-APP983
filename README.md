---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
This code sets up an interactive chat application using Gradio and HuggingFace's Inference API to discuss blockchain technology. It processes a PDF on blockchain, builds a searchable vector database, and retrieves relevant document excerpts to enhance responses. Users can ask questions about blockchain, and the app provides contextually relevant answers based on the PDF content and user input.
