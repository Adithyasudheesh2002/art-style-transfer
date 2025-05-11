# 🎨 AI Art Style Transfer App

Transform your photos into artwork using the styles of famous painters like **Van Gogh**, **Picasso**, and **Monet** using deep learning and neural style transfer.

## 📌 Project Overview

This app applies **Neural Style Transfer** to blend the **content of one image** with the **style of another**, using a pretrained **VGG19** model in PyTorch.  
Users can upload a content image (e.g., a flower) and choose an artistic style to apply — all within an easy-to-use **Streamlit** web interface.

---

## 🚀 Live Demo

Try it now on Hugging Face Spaces:  
👉 [https://yourname.hf.space](https://yourname.hf.space) *(replace with your link)*

---

## 🛠️ Technologies Used

- **PyTorch** – for building and optimizing the style transfer model
- **VGG19** – pretrained convolutional neural network for feature extraction
- **Streamlit** – for building an interactive web app UI
- **OpenCV / PIL** – for image preprocessing and conversion
- **Hugging Face Spaces / Streamlit Cloud** – for deployment

---

## 🧠 How It Works

1. **Content Image**: Defines the structure (e.g., a flower photo)
2. **Style Image**: Defines the painting style (e.g., Starry Night)
3. The model optimizes a target image to match:
   - **Content** from the content image
   - **Style** from the style image (via Gram matrices)

---

## 📸 Example

| Content | Style | Output |
|--------|--------|--------|
| ![](samples/content.jpg) | ![](samples/style.jpg) | ![](samples/output.jpg) |

---

## 📂 Usage Instructions

### 🔧 Local Setup

```bash
git clone https://github.com/yourusername/art-style-transfer.git
cd art-style-transfer
pip install -r requirements.txt
streamlit run app.py
