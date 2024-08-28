# Soil Texture Classification with PyTorch

## Overview
This project aims to classify soil textures from images using a convolutional neural network (CNN) implemented in PyTorch. The model, `SandNet`, classifies soil into five categories: Clay, Loam, Sand, Sandy Loam, and Silt. The project uses PyTorch's dataset utilities for loading and transforming the data, and a custom CNN architecture for the classification task.

## Prerequisites
- Python 3.8 or higher
- PyTorch 1.7 or higher
- torchvision
- PIL (Pillow)

## Installation
Clone the repository and install the required packages:
```bash
git clone https://github.com/yourusername/soil-texture-classification.git
cd soil-texture-classification
pip install torch torchvision pillow
```
## Dataset
Soil Data/

├── Clay/

├── Loam/

├── Sand/

├── Sandy Loam/

└── Silt/


# Model Architecture
The SandNet model consists of three convolutional layers followed by max-pooling layers and two fully connected layers. The model's architecture is designed to work effectively with the soil image dataset, recognizing features relevant to different soil textures

# Evaluation
Testing accuracy: **84.14634146341463%**

![Training Loss and Accuracy](Screenshot%202024-08-27%20201635.png)
