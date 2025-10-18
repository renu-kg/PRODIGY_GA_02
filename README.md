# 🎨 Image Generation with Stable Diffusion XL  

This project was created as part of my **Generative AI Internship at Prodigy InfoTech**.  
The goal was to explore **Diffusion Models** and understand how modern AI systems generate high-quality, realistic images from textual descriptions.  

---

## 📋 Overview  

**Diffusion Models** are a class of generative models that learn to create data (like images) by progressively *denoising* random noise until a clear image emerges.  

This project uses **Stable Diffusion XL (SDXL)** — an advanced text-to-image model developed by **Stability AI**.  
It works by taking a **prompt** (a short text description) and generating a detailed, artistic image that visually represents the text.  

---

## ⚙️ What This Project Does  

1. Installs and imports required libraries (`diffusers`, `torch`, `transformers`, `accelerate`)  
2. Loads the **SDXL Base Model** for initial image generation  
3. Loads the **SDXL Refiner Model** for high-quality detailing  
4. Applies **attention slicing** and **sequential CPU offloading** for better memory optimization  
5. Generates and displays the final refined image from a descriptive text prompt  

---

## 🚀 Technologies Used  

```
🖥️ Python 3  
🧩 Hugging Face Diffusers  
⚙️ PyTorch  
🎨 Stable Diffusion XL (Base + Refiner)  
📦 Accelerate & Safetensors for performance optimization  
```

---

## 📂 How to Run  

```
1️⃣ Clone this repository  
   git clone https://github.com/renu-kg/PRODIGY_GA_02.git  

2️⃣ Navigate to the folder  
   cd PRODIGY_GA_02  

3️⃣ Install dependencies  
   pip install diffusers transformers accelerate torch invisible_watermark safetensors ftfy==6.1.1  

4️⃣ Run the notebook or script  
   python image_generation.py  
   # or open in Google Colab for better GPU performance  

5️⃣ Edit the 'prompt' variable in the code to create your own AI-generated artwork!
```

---

## 💡 Key Learnings  

✨ Understanding how **Diffusion Models** work (noise → image)  
🎨 Using **Stable Diffusion XL** for text-to-image generation  
⚙️ Implementing **model offloading** to optimize memory  
🧠 Exploring **AI-driven creativity** through visuals  

---

## 💫 Internship Credit  

This project was built as part of my **Generative AI Internship at [Prodigy InfoTech](https://prodigyinfotech.dev)**.  
It deepened my understanding of how modern AI brings imagination to life — one pixel at a time. 💫  

---

## 📎 Connect With Me  

👩‍💻 **Renu K G**  
🔗 [LinkedIn](https://www.linkedin.com/in/renu-k-g-9aaa152a6)  
🌐 [GitHub](https://github.com/renu-kg)  

---

