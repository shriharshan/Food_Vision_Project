# 🍔 Food Classification Model 🍰

This repository contains a TensorFlow implementation of a food classification model using the EfficientNetV2B0 architecture. The model is trained to classify images into 10 different food classes.

## Table of Contents

- [Directory Structure](#directory-structure)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Training](#training)
- [Inference](#inference)

## Directory Structure
* 📁 Data/
    * 📁 10_food_classes_all_data/
        * 📁 train/
        * 📁 test/
* 📄 model.py
* 📄 README.md


## Prerequisites

Ensure you have the following prerequisites installed on your system:

- 🧠 TensorFlow
- 🧮 NumPy
- 📊 Matplotlib

You can install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```
## Setup
### Clone the Repository:

```bash
git clone https://github.com/shriharshan/Food_Vision_Project.git
cd your-repo 
```

### Download the Dataset:

I've used Food101 dataset from [kaggle](https://www.kaggle.com/datasets/dansbecker/food-101) and used only 10 classes for this model. Download the dataset and organize it in the Data/10_food_classes_all_data directory. The dataset should have separate train and test folders containing images for training and testing.

## Training
The model will be trained for 5 epochs using data augmentation and the EfficientNetV2B0 base model.