# 🧠 BLIP + LLaMA 3 Image Captioning Pipeline

This project demonstrates a powerful **multimodal AI system** that combines **BLIP** (Bootstrapped Language Image Pretraining) for image captioning and **LLaMA 3** (Meta's state-of-the-art large language model) for instruction-following. Built using Hugging Face Transformers and executed on Google Colab with free GPU support.

---

## 📌 What This Project Does

- 📸 Takes any input image  
- ✍️ Uses **BLIP** to generate a detailed caption  
- 💬 Feeds the caption into **LLaMA 3**, which can:  
  - Answer questions about the image  
  - Expand on image context  
  - Follow user instructions  

---

## 🛠️ Technologies Used

- `transformers` by Hugging Face 🤗  
- **BLIP** for visual understanding and captioning  
- **Meta LLaMA 3 8B-Instruct** for text generation  
- `torch`, `accelerate`, `bitsandbytes`  
- Google Colab for execution  
- Hugging Face Hub for model access


