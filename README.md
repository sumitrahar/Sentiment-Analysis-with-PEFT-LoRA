# Sentiment-Analysis-with-PEFT-LoRA
Efficient fine-tuning of DistilBERT for sentiment analysis using Parameter-Efficient Fine-Tuning (PEFT) with LoRA (Low-Rank Adaptation).

📌 Overview
This project demonstrates how to perform efficient sentiment analysis fine-tuning using:

🤗 Hugging Face Transformers

Parameter-Efficient Fine-Tuning (PEFT)

LoRA (Low-Rank Adaptation) technique

Google Colab-friendly implementation

Achieves good performance while using 98% fewer trainable parameters compared to full fine-tuning.

✨ Key Features
🚀 Efficient Training: ~5MB adapter weights vs 440MB full model

💻 Hardware Friendly: Works on both CPU and GPU
🔄 Flexible Adaptation: Easy to modify for custom datasets

📊 Interpretable Results: Direct sentiment labels (POSITIVE/NEGATIVE)

🧠 Knowledge Preservation: Maintains original model capabilities

🛠️ Technical Stack
Component	Technology Used
Base Model	distilbert-base-uncased
Fine-tuning Method	LoRA (PEFT)
Framework	PyTorch + Hugging Face
Hardware Requirements	CPU/GPU (4GB+ VRAM for GPU)
Key Libraries	Transformers, Datasets, PEFT
