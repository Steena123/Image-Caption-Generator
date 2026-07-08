# 🖼️ Image Caption Generator using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📖 Overview

This project implements an **AI-powered Image Caption Generator** that combines **Computer Vision** and **Natural Language Processing (NLP)** to automatically generate descriptive captions for images.

The model follows an **Encoder–Decoder architecture**, where a pre-trained Convolutional Neural Network (CNN) extracts visual features from an image, and a Long Short-Term Memory (LSTM) network generates natural language captions word by word.

This project demonstrates the practical application of deep learning techniques for multimodal learning by integrating image understanding with language generation.

---

## 🎯 Objectives

- Generate descriptive captions for unseen images.
- Extract high-level visual features using a pre-trained CNN.
- Learn language patterns using an LSTM-based decoder.
- Demonstrate an end-to-end deep learning pipeline for image captioning.

---

# 🏗️ Model Architecture

The model consists of two parallel branches:

- **Image Encoder:** Extracts image features using a CNN.
- **Caption Decoder:** Processes caption sequences using an Embedding layer and LSTM.
- The extracted image features and language features are merged before predicting the next word in the caption.

<p align="center">
<img src="images/model_architecture.png" width="700">
</p>

---

# 🖼️ Sample Prediction

The figure below demonstrates the model generating a caption for an unseen image.

<p align="center">
<img src="images/sample_prediction.png" width="700">
</p>

The model predicts captions sequentially by combining the visual representation of the image with previously generated words.

---

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Pillow

---

## 🧠 AI Concepts Applied

- Deep Learning
- Computer Vision
- Natural Language Processing
- Convolutional Neural Networks (CNN)
- Long Short-Term Memory (LSTM)
- Transfer Learning
- Sequence Modeling
- Feature Extraction

---

## 📂 Dataset

The project was trained using the **Flickr8k Image Caption Dataset**, which contains images paired with multiple human-written captions.

> **Note:** The dataset is not included in this repository due to its size and licensing restrictions.

---

## 🚀 Project Workflow

1. Load and preprocess the Flickr8k dataset.
2. Extract image features using a pre-trained CNN.
3. Clean and tokenize image captions.
4. Train the LSTM-based caption generation model.
5. Generate captions for unseen images.

---

## 🎯 Applications

- Assistive technology for visually impaired users
- Automatic image annotation
- Image search and retrieval
- Social media caption generation
- Intelligent multimedia systems
- Human-computer interaction

---

## 📈 Future Improvements

- Replace the CNN–LSTM architecture with Transformer-based models such as BLIP or ViT-GPT2.
- Improve caption quality using attention mechanisms.
- Evaluate the model using BLEU, METEOR, and CIDEr metrics.
- Deploy the application as a web application using Streamlit or Flask.

---

## 📁 Repository Structure

```
Image-Caption-Generator/
│── Image_Caption_Generator.ipynb
│── README.md
│── requirements.txt
│── Image_Caption_Generator_Report.pdf
│
└── images/
    ├── model_architecture.png
    └── sample_prediction.png
```

---

## 👩‍💻 Authors

**Steena Susan Abraham**

Bachelor of Computer Applications (BCA)

Project completed as part of undergraduate coursework and included here as a demonstration of practical experience in Artificial Intelligence, Deep Learning, Computer Vision, and Natural Language Processing.

---

## 📜 License

This project is intended for educational and research purposes.
