# 🪲 Precise Identification of Major Agricultural Pests Using Deep Learning

This repository presents the implementation of a deep learning-based pest recognition system developed as part of a **National Undergraduate Research Program** at Sichuan Agricultural University in 2020. This project was later published in an EI-indexed paper, where I contributed as the second author.

## 📌 Project Background

Accurate identification of crop pests is essential for modern precision agriculture. Traditional manual identification is time-consuming and error-prone. To address this, we developed an automated pest identification system based on convolutional neural networks (CNNs), using a custom dataset of 35,000 labeled images across 71 pest categories.

## 🧠 Methodology

- **Dataset**: 35,000 labeled pest images, 71 species
- **CNN Architectures**: Inception-v3 and Inception-v4 (GoogLeNet family)
- **Integration**: Enhanced Inception-v4 performance by combining it with a Support Vector Machine (SVM) classifier
- **Result**: Achieved 97.3% accuracy on the test set

## 🛠️ Technologies Used

- Python
- TensorFlow
- Scikit-learn (for SVM integration)
- NumPy / Pandas
- OpenCV (for image preprocessing)
- Matplotlib (for performance visualization)

## 📊 Results

| Model             | Accuracy |
|------------------|----------|
| Inception-v3      | 95.8%    |
| Inception-v4 + SVM| **97.3%**|

## 📄 Publication

Luo, Lijun (Second Author). *Identification of Major Agricultural Pests Based on Convolutional Neural Networks*. EI Indexed Conference, 2020.

