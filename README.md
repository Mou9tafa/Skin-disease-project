# Skin Disease Classification Project

A deep learning project for automated skin disease classification using artificial intelligence and medical image analysis.


## Project Contents

* **`code/`**: Contains the Google Colab notebooks used for data preprocessing, model training, fine-tuning, and evaluation.
* **`dataset/`**: Contains information about the datasets used in this project.
* **`models/`**: Contains the trained deep learning model files.
* **`results/`**: Contains evaluation results, performance metrics, and visualizations.

## Dataset Sources

The dataset used in this project was collected from multiple Kaggle datasets:

- **Acne Dataset:**  
  https://www.kaggle.com/datasets/nayanchaure/acne-dataset  
  Classes: Acne

- **Skin Diseases Image Dataset:**  
  https://www.kaggle.com/datasets/ismailpromus/skin-diseases-image-dataset  
  Classes: Eczema, Warts, Psoriasis

- **Vitiligo Dataset:**  
  https://www.kaggle.com/datasets/shinynose/vitiligo  
  Class: Vitiligo

The datasets were combined, preprocessed, and augmented to create a multi-class skin disease classification dataset.

## Model Used

* **EfficientNetB3 (Transfer Learning & Fine-Tuning)** - Final Classification Model

## Additional AI Components

* **RAG (Retrieval-Augmented Generation):** Used to retrieve relevant medical information and enhance the generated responses.
* **LLM (Large Language Model):** Integrated to provide intelligent explanations and information based on the model predictions.
* **Grad-CAM (Gradient-weighted Class Activation Mapping):** Used for model interpretability by visualizing the regions of the image that influenced the prediction.

## Technologies Used

* Python
* TensorFlow / Keras
* EfficientNetB3
* Transfer Learning
* Fine-Tuning
* RAG
* Large Language Models (LLM)
* Grad-CAM
* Google Colab

## Project Goal

Develop a deep learning system capable of classifying multiple skin diseases from medical images with high accuracy while providing explainable AI insights and intelligent medical information retrieval.

The final **EfficientNetB3** model achieved an accuracy of **88%** on the test dataset. The system combines deep learning classification, explainability using Grad-CAM, and AI-powered assistance using RAG and LLM technologies.
