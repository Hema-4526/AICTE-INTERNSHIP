GARBAGE CLASSIFICATION

# Trash Classification using EfficientNetV2B0 (Transfer Learning)

This project classifies trash images into the following categories:
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

We use TensorFlow and EfficientNetV2B0 (transfer learning) to train and evaluate the model.

---

## 📁 Dataset Structure

The dataset is organized in folders where each folder name is a class label:

TrashType_Image_Dataset/
├── cardboard/
├── glass/
├── metal/
├── paper/
├── plastic/
└── trash/

Each folder contains respective class images.

## 🔧 Environment Setup

Make sure you have the following installed:

- Python 3.8+
- TensorFlow 2.x
- matplotlib
- seaborn
- numpy
- PIL (Pillow)
- gradio (optional for UI)

Install using:

```bash
pip install tensorflow matplotlib seaborn pillow gradio
