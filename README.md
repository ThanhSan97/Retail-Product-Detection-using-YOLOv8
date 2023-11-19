# Retail-Product-Detection-using-YOLOv8
Building a system for product recognition and counting at the checkout counter in supermarkets using YOLOv8" was carried out by my team of 5 members at Duy Tan University. The result of the project is the development of a system that can recognize products at the checkout counter and count the quantity of each product. 


# Retail Product Checkout with YOLOv8

## I. Introduction

Welcome to the Retail Product Checkout project, where we leverage YOLOv8 to develop a robust object detection and counting model for products on the checkout counter in supermarkets. This project aims to streamline the retail experience by automating the process of item identification and counting during checkout.

## II. Project Implementation

### 1. Data Collection

To train our YOLOv8 model, we collected a diverse dataset of retail checkout scenarios. You can find the dataset [here](https://drive.google.com/file/d/1g4NhcnpTTecGooMpzObEfXzeVmvRJHFr/view?usp=sharing), and we used [Roboflow](https://universe.roboflow.com/cdio-zmfmj/retail-product-checkout) for data preprocessing and augmentation.

### 2. Data Processing
 - Dataset: https://drive.google.com/file/d/1g4NhcnpTTecGooMpzObEfXzeVmvRJHFr/view?usp=sharing
or Roboflow project: https://universe.roboflow.com/cdio-zmfmj/retail-product-checkout
- The collected data underwent preprocessing and augmentation to enhance the model's ability to generalize. This step is crucial for improving the model's performance on real-world scenarios.

### 3. YOLOv8 Introduction

[YOLOv8](https://docs.ultralytics.com) by Ultralytics is a state-of-the-art object detection framework. Refer to the official documentation for a comprehensive guide on YOLOv8's architecture and functionalities.

### 4. Model Training

We trained our object detection model using the YOLOv8 framework. The training process involves optimizing the model to recognize and count products accurately. The trained model is then ready for deployment.
Open the Retail-Product-Detection.ipynb to better understand the training process

### 5. Results

In the "results" folder, you can find visualizations showcasing the model's performance on sample images from the dataset. These results demonstrate the model's ability to detect and count products effectively.

## III. Getting Started

### Clone Repository

- git clone https://github.com/ThanhSan97/Retail-Product-Detection-using-YOLOv8.git
- cd your-repository

