Thank you for downloading AUTHENTECH VISVAS

# Signature Authenticity Detection using Deep Learning

## Overview
This project implements a **Siamese Convolutional Neural Network (CNN)** for **signature verification and forgery detection**. It allows users to upload an original and test signature, and the model determines whether the test signature is genuine or forged.

## Features
- Uses a **Siamese CNN model** to compare signature pairs.
- Preprocesses images with resizing, grayscale conversion, normalization, and feature enhancement.
- Provides an interactive **Kivy-based GUI** for uploading and verifying signatures.
- Utilizes **TensorFlow & Keras** for deep learning-based verification.
- Displays results with a progress bar and dialog box.

## Technologies & Libraries Used
- **Deep Learning**: TensorFlow, Keras  
- **Computer Vision**: OpenCV, scikit-image  
- **GUI Framework**: Kivy, KivyMD  
- **Other Libraries**: NumPy, Plyer (file selection)  

## Installation & Setup
### 1. Clone the Repository
```sh
git clone <repository-url>
cd <repository-folder>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Run the Application
```sh
python main.py
```

## Usage
- Upload an **original signature** and a **test signature** via the GUI.
- Click "Verify" to start the authentication process.
- The model will classify the test signature as **Genuine** or **Forged**.

## Model Details
- Uses a **Siamese CNN** to compute similarity between two signatures.
- Trained on signature datasets using binary classification (genuine vs forged).
- Optimized with **Adam optimizer** and **binary cross-entropy loss**.

## License
This project is open-source and available under the **MIT License**.

If you wish to contribute to the project, make sure to download the training data that we used from https://www.kaggle.com/datasets/robinreni/signature-verification-dataset
