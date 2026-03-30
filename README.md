# DAABQ-Model-Compression
# Dynamic Attention-Aware Bit Quantization (DAABQ)

This repository contains the implementation of the DAABQ method for efficient deep learning model compression.

## 📌 Overview
DAABQ is a post-training mixed-precision quantization technique that assigns adaptive bit-widths (6-bit, 7-bit, 8-bit) based on channel importance derived from activation values.

## 🧠 Models Implemented
- ResNet50
- MobileNetV2
- InceptionV3

## 📊 Key Results
- ~3.5×–4× model compression
- Minimal accuracy degradation

## 📁 Notebooks
- ResNet50 DAABQ
- MobileNetV2 DAABQ
- InceptionV3 DAABQ

## ⚙️ Tech Stack
Python, PyTorch, NumPy

## 📌 Dataset
CIFAR-10

---

This project was developed as part of my M.Tech research work.
