# Image-Caption-generator
A deep learning-based application that generates human-like captions for images using a CNN + LSTM architecture.
# 🖼️ Image Caption Generator

A deep learning-based application that generates human-like captions for images using a CNN + LSTM architecture.

---

## 📌 Project Overview

This project demonstrates an image captioning system that combines visual feature extraction (CNN) with sequence modeling (LSTM) to produce natural language descriptions of images. Users can upload an image and receive an auto-generated caption describing the content of the image.

---

## 🛠️ Tools & Technologies

- **Python**
- **TensorFlow / Keras**
- **CNN (InceptionV3)** – for image feature extraction
- **LSTM** – for language modeling
- **Streamlit** – for the interactive web interface
- **Flickr8k Dataset** – a dataset of images and associated captions
- **NLTK** – for text processing

---

## 🧠 Model Architecture

1. **Feature Extraction (CNN)**: Pre-trained InceptionV3 extracts feature vectors from images.
2. **Caption Generator (LSTM)**: A stacked LSTM model generates the caption word-by-word.
3. **Tokenizer & Vocabulary**: Captions are tokenized, and padding is applied for sequence learning.

---

## 📁 Project Structure

