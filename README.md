# Mistral-7B QLoRA Assistant

This repository contains the code to fine-tune the **Mistral-7B-Instruct-v0.3** model using **QLoRA** (Quantized Low-Rank Adaptation) on the Capybara dataset. The model is then deployed using FastAPI and Gradio.

## 🚀 Hugging Face Model
The fine-tuned LoRA adapter is hosted on Hugging Face:
👉 [mohidali9679/mistral-7b-assistant](https://huggingface.co/mohidali9679/mistral-7b-assistant)

## 🛠️ Tech Stack
- **Framework:** PyTorch, Hugging Face Transformers
- **Fine-tuning:** PEFT, TRL, BitsAndBytes (4-bit quantization)
- **Deployment:** FastAPI, Uvicorn, Gradio
- **Environment:** Google Colab (Tesla T4 GPU)

## 📓 How to Run
You can run the full pipeline by opening the notebook:
1. Open `chatbot_1.ipynb` in Google Colab.
2. Run the cells sequentially to load the dataset, fine-tune the model, and test the inference.
3. The notebook also contains cells to launch a Gradio web interface and a FastAPI backend.
