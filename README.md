# Plant Disease Prediction using CNN
---

![image](https://github.com/user-attachments/assets/8bc1906f-5e32-4b19-9343-708c6f836769)


This repository is about building an image classifier using Convolutional Neural Networks (CNN) in Python for Plant Disease Prediction.

## Project Overview

This project involves training a deep learning model to classify plant diseases using images. The dataset contains a variety of plant images, categorized by disease types. The trained model can predict the disease class of a given plant image.

## Dataset

The dataset used for training the model is available on Kaggle. You can download it from the following link:

[Kaggle Dataset: PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)

## Trained Model

The trained model is available for download. You can use this model to make predictions on new images without retraining:

[Download Trained Model](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link)

## Setup Instructions

To set up this project on your local machine, follow the steps below:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/plant-disease-prediction-cnn-deep-learning-project.git
cd plant-disease-prediction-cnn-deep-learning-project
```

### 2. Install Dependencies

Ensure you have Python and pip installed. Then, install the required Python packages:

```bash
pip install -r requirements.txt
```

### 3. Download the Dataset

Download the dataset from Kaggle and place it in the appropriate directory within your project folder.

### 4. Train the Model

If you want to train the model from scratch, run the following command:

```bash
python train.py
```

### 5. Use the Trained Model

To use the pre-trained model, load it and make predictions on new images:

```bash
python predict.py --image_path /path/to/image.jpg
```

## Project Structure

- `train.py` - Script to train the CNN model.
- `predict.py` - Script to make predictions using the trained model.
- `model/` - Directory containing the trained model.
- `data/` - Directory where the dataset should be stored.
- `requirements.txt` - List of Python packages required to run the project.

## How to Contribute

If you'd like to contribute to this project, feel free to submit a pull request or open an issue. Contributions are welcome!

---

