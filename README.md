# Weed Detection in Agriculture 🌿

## Overview 
Weed detection in agriculture is a crucial task for removing unwanted plants that compete with crops. This project focuses on leveraging deep learning models for accurate weed identification, leading to increased yields, lower costs, and reduced herbicide use. We performed a comparative analysis between YOLOv8, RetinaNet, SSD, and Faster R-CNN to determine the most effective approach for weed detection in agricultural settings.

## Installation 💻
1. Clone the repository:
`git clone https://github.com/maysoonalmalawi/weed-detection.git](https://github.com/maysoonalmalawi/CPCS433_Project`

## Usage 🚀
1. Download the dataset and pre-trained models.
2. Run the respective scripts for training and evaluation of each model:
- `train_yolov8.py`
- `train_retinanet.py`
- `train_ssd.py`
- `train_faster_rcnn.py`
3. Evaluate the performance metrics such as accuracy, precision, recall, and F1-score for each model.
4. Choose the model with the best performance for weed detection in your agricultural application.

## Dataset 📂
The dataset used for training and evaluation consists of labeled images containing crops and weeds. The specifications of the dataset are as follows:
- 1 class: grass-weed
- Number of training images: 1661
- Number of test images: 245
- variety of weed species
- variety of locations, climates, and conditions

## Pre-trained Models 🧠
We provide pre-trained models for YOLOv8, RetinaNet, SSD, and Faster R-CNN, which can be downloaded from [insert link here].

## Comparative Analysis 📈
The comparative analysis between YOLOv8, RetinaNet, SSD, and Faster R-CNN includes the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

The analysis aims to determine the model that achieves the highest performance in weed detection while considering factors such as inference speed and computational resources.

Based on these results, we recommend using **YOLOv8** for weed detection in agriculture due to its superior performance.

## Conclusion 💡
Integrating deep learning models like YOLOv8, RetinaNet, SSD, and Faster R-CNN into weed detection processes enhances accuracy, efficiency, and sustainability in agriculture. This project provides insights into selecting the most suitable model for weed detection based on performance metrics and application requirements.

