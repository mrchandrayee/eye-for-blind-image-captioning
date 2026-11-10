# 👁️ Eye for Blind — Image Captioning for Visually Impaired

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

**Eye for Blind** — A deep learning image captioning system that helps visually impaired people by automatically generating descriptive captions for images and converting them to speech.

## 🎯 Problem Statement

Build an image captioning model using CNN + LSTM (Encoder-Decoder with Attention) that generates meaningful text descriptions of images, then converts them to audio for visually impaired users.

## 🏗️ Architecture

- **CNN Encoder** — InceptionV3 / ResNet for image feature extraction
- **LSTM Decoder** — Sequence generation with Bahdanau Attention
- **Text-to-Speech** — gTTS for audio output
- **Streamlit** — Web interface for image upload

## ✨ Features

- 👁️ Automatic image caption generation
- 🔊 Text-to-speech audio output
- 🏥 Accessibility focused application
- 🐳 Dockerized deployment
- 🌐 Streamlit web interface
- 📊 BLEU score evaluation

---

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee) · [Profile](https://github.com/mrchandrayee/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
