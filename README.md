# Face_Mask_Detection

This project aims to detect the presence of face masks on individuals in images or video streams. It leverages deep learning and computer vision techniques to build a model that can distinguish between masked and unmasked faces. This application has significant implications for public safety, especially in environments where mask-wearing is mandatory.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
The Face Mask Detection Project uses a convolutional neural network (CNN) to identify whether individuals are wearing masks. The model is trained on a dataset containing images of people with and without masks, providing a binary classification output.

## Dataset
The dataset used in this project is available on Kaggle and includes images labeled as "with mask" and "without mask." You can download the dataset from the following link:

- [Kaggle Dataset: Face Mask Detection](https://www.kaggle.com/datasets/maithreyisuresh/face-mask-detection)

To download the dataset, you may use the Kaggle API or download it manually and place it in the appropriate directory.

### Downloading via Kaggle API
1. **Install Kaggle API**:
   ```bash
   pip install kaggle
   ```
2. **Setup Kaggle API**:
   - Get your Kaggle API credentials from your Kaggle account settings and place the `kaggle.json` file in the `~/.kaggle/` directory.

3. **Download Dataset**:
   ```bash
   kaggle datasets download -d maithreyisuresh/face-mask-detection
   ```

## Project Structure
The project consists of the following key files and directories:

- **`Minor_Project_Face_Mask_Detection.ipynb`**: Jupyter notebook containing the implementation of the face mask detection model, including data preprocessing, model training, and evaluation.
- **`/data`**: Directory where the dataset should be placed.
- **`/models`**: Directory to save trained models.

## Installation
To run this project, you need to set up a Python environment with the required packages. Follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/face-mask-detection.git
   cd face-mask-detection
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Running the Notebook**:
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `Minor_Project_Face_Mask_Detection.ipynb` and run the cells to preprocess the data, train the model, and evaluate its performance.

2. **Inference**:
   - Use the trained model to detect masks on new images or video streams.

## Contributing
We welcome contributions to improve the project. If you'd like to contribute, please fork the repository and submit a pull request with your changes.
