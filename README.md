# 🎨 Neural Style Transfer Web Application

A deep learning-based **Neural Style Transfer (NST)** web application that combines the content of one image with the artistic style of another image.

The application uses a pre-trained **VGG-19 encoder** and a trained decoder to generate a new image that preserves the content of the input image while applying the visual style of the selected style image.

---

## 📌 Project Overview

Neural Style Transfer is a computer vision technique that uses deep neural networks to transfer the artistic style of one image onto another image.

For example:

- **Content Image:** A photograph of a person, building, or landscape.
- **Style Image:** A painting or artistic image.
- **Output Image:** The original content with the artistic style applied.

This project provides a simple web interface where users can upload a content image, select/upload a style image, adjust the style strength, and generate the stylized output.

---

## ✨ Features

- 🖼️ Upload a content image
- 🎨 Upload or select a style image
- 🔄 Perform Neural Style Transfer
- 🎚️ Adjust style strength using an alpha value
- ⚡ Generate stylized images through a Flask web application
- 📱 Simple and user-friendly web interface
- 🧠 Uses a pre-trained VGG-based encoder
- 🤖 Uses a trained decoder for fast image generation
- 💻 Runs locally using Python and Flask

---

## 🏗️ Project Structure

```text
ai-nst-project/
│
├── Demo_IO_Images/
│   ├── i-p/
│   └── o-p/
│
├── NST_Code/
│   ├── content_data/
│   ├── examples/
│   ├── experiment/
│   │   └── final_exp/
│   │       └── decoder_final.pth
│   │
│   ├── static/
│   │   └── uploads/
│   │
│   ├── style_data/
│   ├── templates/
│   │   └── index.html
│   │
│   ├── utils/
│   │   ├── models.py
│   │   └── utils.py
│   │
│   ├── app.py
│   ├── train.py
│   ├── vgg_normalised.pth
│   └── adain_algo.png
│
├── code.ipynb
├── requirements.txt
├── Procfile.txt
└── README.md
