# Helmet_Safety_Detection.
# Helmet Detection with YOLOv10

## Overview
This project is focused on detecting helmet usage using a YOLOv10 model. The model is fine-tuned using a helmet safety dataset to ensure high accuracy in detecting whether individuals are wearing helmets in various environments.

## Pipeline
The following pipeline illustrates the steps involved in the project:

![Pipeline](path/to/your/image.png)

1. **Helmet Safety Dataset**: A dataset containing images of individuals with and without helmets.
2. **Pre-trained Model**: A YOLOv10 model pre-trained on a general object detection dataset.
3. **Training (Fine-tuning)**: The pre-trained model is fine-tuned using the helmet safety dataset.
4. **Trained YOLOv10**: The fine-tuned YOLOv10 model is used to detect helmets in new images.

## Input and Output
- **Input**: An image where helmet detection needs to be performed.
- **Output**: The same image with bounding boxes around detected helmets.

## Installation
To run this project, you need to install the required dependencies. You can do this by running:

```bash
pip install -r requirements.txt
