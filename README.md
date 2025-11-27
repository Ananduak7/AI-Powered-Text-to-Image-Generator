# 🎨 AI-Powered Text-to-Image Generator

This project is developed as part of the **Machine Learning Internship Task Assessment**
It demonstrates the ability to build and deploy a **Text-to-Image Generation System** using **Stable Diffusion**, an advanced open-source Latent Diffusion Model.

---

## 🚀 Project Overview

This application converts **textual descriptions into images** using the **Stable Diffusion v1.5** model.  
The entire system is deployed on **Google Colab**, featuring a **web UI created using Streamlit** and made publicly accessible using **Ngrok tunnels**.

---

## ✨ Key Features

✔ Text → Image generation using Stable Diffusion  
✔ Adjustable inference parameters:
- Prompt & Negative Prompt
- Number of images (1–4)
- Sampling steps (20–100)
- Guidance scale for creativity

✔ GPU acceleration (if available)  
✔ Modern Web UI using Streamlit  
✔ Public deployment using Ngrok  
✔ Images saved with metadata (timestamp)  
✔ Ability to load saved images from `/content` directory  

---

## 🧠 Model Used

### 🔹 Stable Diffusion v1.5
A **Latent Diffusion Model (LDM)** preferred because:
- High-quality image generation
- Fully **open-source**
- Efficient GPU memory usage
- Ideal for real-time generation in Colab Free GPU environments  
- Strong community support + HuggingFace availability

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Model | Stable Diffusion v1.5 (Diffusers) |
| Framework | PyTorch |
| Frontend | Streamlit |
| Tunneling | Ngrok |
| Deployment | Google Colab |
| Language | Python |

---

## 📂 Project Structure
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/cd8346a0-a6cf-4357-94c8-d21457cc5e6a" />


