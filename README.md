# Pneumonia Infection Classification via Chest Radiography
Pneumonia is a serious respiratory illness that inflames the lung tissue, leading to symptoms like persistent cough, chest discomfort, elevated temperature, and labored breathing. This project aims to create an automated tool for identifying and categorizing pneumonia using medical imaging.

![Symptoms of Pneumonia](https://user-images.githubusercontent.com/65142149/215302250-841fde71-e182-4ffd-8036-625a3a717de7.png)

Signs of Pneumonia
Common indicators include cough, chest pain, fever, and shortness of breath, which can vary in severity and require prompt diagnosis for effective management.

Project Motivation
The primary objective is to harness artificial intelligence to enhance the precision and speed of pneumonia diagnosis through chest X-ray analysis. Automating this process supports medical practitioners by delivering rapid, reliable results, ultimately improving patient outcomes.

Methodology
The system employs transfer learning to develop a robust AI model for pneumonia detection. It leverages ResNet architectures, coded in Python with TensorFlow as the core framework. Training and model assessment were accelerated using Google Colab’s GPU capabilities, with TensorBoard employed for performance monitoring.

Core Technologies
Python: Programming language for model development.

TensorFlow: Framework for building and training neural networks.

Google Colab GPU: Cloud-based GPU for efficient computation.

TensorBoard: Tool for visualizing training metrics.

ResNet Architectures: Deep learning models for image classification.

Dataset Description
The dataset is structured into three directories—train, test, and validation—containing 5,863 JPEG X-ray images divided into two categories: Pneumonia and Healthy. These anterior-posterior chest X-rays were collected from pediatric patients aged one to five at the Guangzhou Women and Children’s Medical Center in China. Before model training, images underwent rigorous quality checks to eliminate poor-quality or unclear scans. Expert clinicians annotated the images for diagnostic accuracy, with a third specialist reviewing the validation set to ensure consistency.

The dataset used in this project is available on Kaggle: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
