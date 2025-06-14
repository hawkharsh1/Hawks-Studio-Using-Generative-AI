# 🦅 Hawk Studio - AI-Powered Image Generating Platform

## 🌟 Overview
Hawk Studio is a professional-grade image editing suite powered by generative AI, designed for e-commerce businesses, content creators, and photographers. The platform automates complex editing workflows while maintaining studio-quality results.

![Hawk Studio Interface](https://github.com/hawkharsh1/Hawks-Studio-Using-Generative-AI/blob/main/image.png)


## 🌟 Features

- 🖼️ **Generate HD Images**  
  Create high-definition product visuals from simple text prompts.

- 🎯 **Background Removal**  
  Remove image backgrounds with optional replacement colors.

- 🌅 **Add Realistic Shadows**  
  Enhance product visuals with lifelike shadow overlays.

- 🏠 **Lifestyle Shots**  
  Generate lifestyle contexts for your product using text or reference images.

- ✨ **AI-Powered Prompt Enhancement**  
  Automatically improve user input prompts for better image outcomes.

- 📝 **Call-to-Action Overlay**  
  Add marketing-ready CTA text to your generated visuals.

- 🎮 **Intuitive UI Controls**  
  Use sliders, buttons, color pickers, and file uploaders for a seamless user experience.

- 💾 **Image Download Option**  
  Download your final ad creatives with a single click.

## 🚀 How It Works

1. Choose whether to start from text, image, or both.
2. Apply enhancements like shadow or background removal.
3. Preview the generated result.
4. Download the image for immediate use in campaigns.

## 🛠️ Tech Stack
![screen shot](https://github.com/hawkharsh1/Hawks-Studio-Using-Generative-AI/blob/main/Techstack.png)

- **Python 3.10+**
- **Streamlit**
- **Bria AI API**
- `rembg` for background removal
- `Pillow` and `NumPy` for image processing

## 🧪 How to Use

1. **Enter your API Key**
   - Launch the app.
   - On the sidebar, find the **"Enter your API Key"** field.
   - Paste this sample Bria API key to get started:
     ```
     b1162e664ff143abbea3336cc7ee49a5
     ```
   - You can also generate your own Bria API key by visiting [Bria AI](https://bria.ai).

2. **Choose a Generation Mode**
   - ✏️ **Text Prompt** — Type a short product description (e.g., "modern lamp on a wooden table").
   - 🖼️ **Image Upload** — Upload a product photo to enhance or modify.

3. **Apply Enhancements**
   - 🎯 Remove background (with optional background color).
   - 🌅 Add realistic shadows.
   - 🏠 Generate lifestyle shots using text or reference image.
   - ✨ Enhance prompts automatically.
   - 📝 Add marketing-ready CTA text (e.g., "Buy Now").

4. **Preview and Download**
   - 🔍 See the result in real time.
   - 💾 Click **Download** to save the final creative for your campaign.

## 🧠 What is Bria AI?

[Bria AI](https://bria.ai) provides powerful APIs for **creative image generation**, **manipulation**, and **visual content enhancement** using generative AI models. It's designed to help businesses and developers create high-quality marketing visuals quickly and programmatically.

### 🔗 Bria AI Capabilities Used in This Project:

In **Hawk Studio AI**, Bria AI is used to:

- 🖼️ **Generate HD product images from text**: You describe your product (e.g., “a sleek smartwatch on a white table”), and Bria returns a photorealistic image.
- 🏠 **Create lifestyle shots**: It blends your product with realistic backgrounds or environments using either reference images or generated scenes.
- ✨ **Enhance prompt descriptions**: Automatically refines vague or basic text inputs to make image generation more accurate and impactful.

### 🔐 How Bria AI Is Integrated:

- You enter your **Bria API key** in the sidebar (`streamlit.text_input()` field).
- The app sends your prompt or image request to Bria’s endpoint via `requests.post()`.
- The AI processes your input and returns a high-resolution image, which is then displayed in the app and made available for download.

> Bria AI powers the core creativity behind the app — helping you skip stock photo searches or hiring designers for ad creatives.

### Some generated images from the Hawk's Studio App
![screen shot](https://github.com/hawkharsh1/Hawks-Studio-Using-Generative-AI/blob/main/Techstack.png)
![screen shot](https://github.com/hawkharsh1/Hawks-Studio-Using-Generative-AI/blob/main/Techstack.png)

 
## 📦 Installation

```bash
git clone https://github.com/hawkharsh1/Hawks-Studio-Using-Gen-AI.git
cd Hawks-Studio-Using-Gen-AI
pip install -r requirements.txt
streamlit run app.py
