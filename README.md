# 🚀 Image Generation using Stable Diffusion & ComfyUI

## 📌 Project Overview
This project explores AI-driven **image generation** using **Stable Diffusion** within the **ComfyUI** framework. By leveraging prompt engineering, negative prompts, and fine-tuned parameters, we create **highly detailed and imaginative visuals** that adhere to specific themes. 

## 🛠 Features
- 🎨 **Text-to-Image Generation**: Generate unique AI-generated images from descriptive text prompts.
- 🧠 **Negative Prompting**: Exclude unwanted elements from generated images.
- ⚡ **ComfyUI Workflow**: Utilize a **node-based** workflow for greater flexibility and customization.
- 🔧 **Fine-Tuned Parameters**: Control image style, detail level, and consistency.
- 🖼️ **Multi-Prompt Composition**: Combine multiple prompts to create intricate scenes.

## 📂 Project Structure
```
📁 Stable_Diffusion_ComfyUI_Project
 ├── 📜 README.md  # Project Documentation
 ├── 📁 Workflows  # ComfyUI workflow files (.json)
 ├── 📁 Outputs    # Generated images
 ├── 📁 Models     # Stable Diffusion models used
 ├── 📁 Scripts    # Python scripts for automation
```

## 🔧 Installation & Setup
### 1️⃣ Install Dependencies
Ensure you have **Python 3.8+** installed, then install the required libraries:
```bash
pip install torch torchvision torchaudio
pip install comfyui
```

### 2️⃣ Download Stable Diffusion Model
Place the **Stable Diffusion v1.5/v2.1 model checkpoint** in the `Models` folder.

### 3️⃣ Run ComfyUI
Start the UI with:
```bash
python main.py
```
Access ComfyUI in your browser at `http://127.0.0.1:8188`.

## 📜 How to Use
1️⃣ **Load Checkpoint**: Choose a Stable Diffusion model.
2️⃣ **Set Prompts**: Enter **positive** and **negative prompts** to guide generation.
3️⃣ **Adjust Parameters**: Tune **CFG scale, denoise, steps, and seed** for better results.
4️⃣ **Generate Image**: Click **Queue** to create an image.
5️⃣ **Save & Refine**: Adjust prompts and settings for enhancements.

## ✨ Example Prompts
**1️⃣ The Enchanted Library of Whispering Books** 📚
> *"A magical library where books float in midair, whispering ancient secrets, with golden runes glowing on the spines and mystical creatures guarding the forbidden knowledge."*
❌ Negative Prompt: *No modern bookshelves, no human librarians, no electronic screens, no candles, no dust or decay.*
> ![image](https://github.com/user-attachments/assets/b4cd58f1-5c67-4b2f-812d-c44baca79401)


**2️⃣ The Ocean Beneath the Stars** 🌌
> *"A surreal ocean that reflects galaxies instead of water, where celestial whales glide through space, leaving trails of shimmering stardust in their wake."*
❌ Negative Prompt: *No regular sea waves, no visible planet surface, no earthly marine life, no human boats, no coral reefs.*
> ![image](https://github.com/user-attachments/assets/ae0aaea1-94ea-4440-8b5e-7cdbba4b4802)


**3️⃣ The Clockwork Forest of Endless Time** ⏳
> *"A forest where trees are made of intricate gears and golden cogs, with branches ticking like clock hands, and glowing vines pulsing with the rhythm of time itself."*
❌ Negative Prompt: *No organic wood, no leaves, no natural flowers, no animals, no waterfalls or rivers.*
> ![image](https://github.com/user-attachments/assets/4d9f36fc-1816-44c9-b5fa-603d4160878e)


## 🔍 Troubleshooting
- 🛑 **Image not aligned with prompt?** → Refine prompts with more explicit details.
- ⚠️ **Blurry or low-detail images?** → Increase **steps** and tweak **CFG scale**.
- 🔄 **Model not loading?** → Ensure the correct model file is placed in `Models/`.

## 🤝 Acknowledgments
A special thanks to **Edunet AICTE** and **Edunet Foundation (IBM SkillsBuild)** for providing an invaluable learning platform. Gratitude to the **ComfyUI & Stable Diffusion** communities for their open-source contributions. 🙌
