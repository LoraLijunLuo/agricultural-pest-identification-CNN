# 🪲 Precise Identification of Major Agricultural Pests Using Deep Learning

This repository presents the implementation of a deep learning-based pest recognition system developed as part of a **National Undergraduate Research Program** during my third year at Sichuan Agricultural University. This project was later published in an EI-indexed paper, where I contributed as the second author.

## 📌 Project Background

Accurate identification of crop pests is essential for modern precision agriculture. Traditional manual identification is time-consuming and prone to error, especially given the diversity and large quantity of pest species. To address this, we developed an automated pest identification system based on convolutional neural networks (CNNs), using a custom dataset of 35,000 labeled images across 71 pest categories.

## 📊 Key Highlights

- **Dataset:** 35,000 labeled pest images, covering 71 distinct pest species
- **Model Architectures:** Implemented and compared Inception-v3 and Inception-v4 models in the GoogLeNet family for multi-class pest classification
- **Model Optimization:** Integrated a Support Vector Machine (SVM) classifier with Inception-v4 feature outputs, significantly improving classification performance
- **Results:**
  - Inception-v4 + SVM: Achieved 97.3% classification accuracy on the test set
  - Inception-v3: Delivered second-best performance in comparative analysis
- **Research Outcome:** Published an **EI-indexed conference paper** based on this project: [Identification of the agricultural pests based on deep learning models (Second Author)](https://github.com/LoraLijunLuo/agricultural-pest-identification-CNN/blob/main/Published%20EI%20paper%20(Second%20Author).pdf)

## 🛠️ Tools & Technologies

- Python
- TensorFlow
- CNN: Inception-v3, Inception-v4 (GoogLeNet)
- SVM (Support Vector Machine)
- Image preprocessing
- Scientific Writing & Model Evaluation

## 🔍 Disclaimer
Due to research ethics and data agreements, the source code and image dataset cannot be publicly shared. This repository is intended to showcase research project goals, methods, and outcomes.


