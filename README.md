# Skin Disease Prediction System

## Overview
The Skin Disease Prediction System is an AI-powered web application that predicts different types of skin diseases from uploaded skin images. The application uses a deep learning model built with PyTorch and provides an interactive interface using Gradio.

The system also includes user authentication, prediction history, and an administrator dashboard for managing records.

## Features
- AI-based skin disease prediction
- Deep learning model using ConvNeXt Tiny
- Gradio web interface
- User login and registration
- Admin dashboard
- Prediction history stored in SQLite database
- Malignancy risk estimation
- Clinical image validation before prediction
- Responsive UI with custom CSS and animations

## Technologies Used
- Python
- PyTorch
- Torchvision
- Gradio
- NumPy
- Pillow (PIL)
- SQLite
- Kaggle Models

## Diseases Detected
- Nevus
- Melanoma
- Basal Cell Carcinoma
- Seborrheic Keratosis
- Squamous Cell Carcinoma
- Actinic Keratosis
- Pigmented Benign Keratosis

## Project Structure

```
Skin-disease-prediction-system/
│── skin_disease_prediction.ipynb
│── README.md
│── requirements.txt
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Skin-disease-prediction-system.git
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

3. Run the notebook or launch the Gradio application.

## How It Works

1. Upload a skin lesion image.
2. The system validates whether it is a clinical skin image.
3. The AI model predicts the most likely skin disease.
4. The application displays:
   - Predicted disease
   - Confidence score
   - Malignancy risk
5. Prediction history is stored securely for authorized users.

## Future Improvements
- Support more skin diseases
- Mobile-friendly deployment
- Cloud deployment
- Explainable AI visualizations
- Multi-language support

## Disclaimer
This project is intended for educational and research purposes only. It is not a substitute for professional medical advice or diagnosis.

## Author
Gladwin Paul Biju
