![image](https://github.com/anupdhoble/6thSemProject_SignatureVerification/assets/83175840/0f5f491e-b98c-4d11-95a4-5d346918c0da)

# Signature Verification System Using CNN
Final PPT/Report:- https://drive.google.com/drive/folders/1xApvlWW8zb1vfAuTEqGFJB0UpGiqti_1?usp=sharing
## Project Overview

- **Project Title:** Signature Verification System Using CNN
- **Project Mentor:** Prof. Bhagyashree S. Madan
- **Team Leader:** Anup Dhoble (B27)
- **Team Members:** Suhani Taran, Ankit Bhardwaj

## Technology Stack

- **Front End:** Reactjs
- **Back End:** MySQL Database
- **Back End Language:** Python
- **Framework:** Django
  
## Hardware used for CNN Model Training
- **GPU used for training:** NVIDIA T4 X2 (15+15 GB)
- **Plateform:** Kaggle

## Brief Description

Every individual possesses a unique signature, crucial for personal identification and verification of legal documents. The process of verifying signatures traditionally relied on manual comparison, which is prone to human error and ineffective against modern forgery techniques.

The Signature Verification System Using CNN offers an efficient solution to authenticate handwritten signatures, reducing the risk of forgery and falsification. The system requires users to log in with basic information and submit two images: the original signature and the comparison signature. The system then processes these images and presents the verification results to the user.

To classify signatures, the project implements a Convolutional Neural Network (CNN) model. This model is trained on sample signatures, enabling accurate comparison between the original and submitted signatures.

## Problem Statement

The problem statement revolves around the need for a reliable signature verification system that minimizes human error and addresses modern forgery techniques.

# Signature Verification System using Transfer Learning

## Overview
This project aims to develop a signature verification system using transfer learning techniques in deep learning. The system utilizes a pre-trained convolutional neural network (CNN) model, ResNet50, and fine-tunes it on a dataset of signatures to achieve user-independent verification. The system is deployed using Django for backend development, React.js for frontend, and SQLite database for storing images for future training.

## Features
- Transfer learning with ResNet50 model for signature verification.
- Django backend for handling image storage and model deployment.
- React.js frontend for user interaction and visualization.
- SQLite database for storing image data.

## Project Structure
- **Backend (Django)**
  - `models.py`: Defines database models for storing image data.
  - `views.py`: Contains views for handling HTTP requests and responses.
  - `urls.py`: Defines URL patterns for different endpoints.
  - `settings.py`: Configuration settings for the Django project.
  - ![image](https://github.com/anupdhoble/6thSemProject_SignatureVerification/assets/83175840/0261573a-90a5-4732-a872-2691f18a6098)

  
- **Frontend (React.js)**
  - `components/`: Contains React components for various UI elements.
  - `pages/`: Defines different pages/routes of the web application.
  - `App.js`: Main component for the React application.
  - `index.js`: Entry point of the React application.

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Install dependencies for Django backend:
   ```
   cd backend
   pip install -r requirements.txt
   ```
3. Install dependencies for React frontend:
   ```
   cd frontend
   npm install
   ```

## Usage
1. Start the Django server:
   ```
   cd backend
   python manage.py runserver
   ```
2. Start the React development server:
   ```
   cd frontend
   npm start
   ```
3. Access the application at `http://localhost:3000` in your web browser.

## Dataset
The dataset used for training the signature verification system consists of original and forged signature images collected from various sources. Each image is labeled as either original or forged for training and evaluation purposes.

## Model Training
The signature verification model is trained using transfer learning, where the pre-trained ResNet50 model is fine-tuned on the signature dataset. The model is compiled with Adam optimizer and categorical cross-entropy loss function.

## Deployment
The trained model is deployed using Django, which serves as the backend for the web application. React.js is used for frontend development to provide an interactive user interface. Images are stored in a SQLite database for future training and reference.
![image](https://github.com/anupdhoble/6thSemProject_SignatureVerification/assets/83175840/c2df184a-13b8-4d32-9883-c432492a950a)
![image](https://github.com/anupdhoble/6thSemProject_SignatureVerification/assets/83175840/90372802-ca01-47e7-8e4c-650d1af25292)

![image](https://github.com/anupdhoble/6thSemProject_SignatureVerification/assets/83175840/834999f2-7b9e-4159-a35d-ca5dd012c7a2)
![image](https://github.com/anupdhoble/6thSemProject_SignatureVerification/assets/83175840/a4781fb7-a69f-40f9-b925-d17de3c1c535)


## Future Improvements
- Implement user authentication for secure access to the application.
- Enhance the frontend with more intuitive features and visualizations.
- Explore advanced deep learning techniques for improved signature verification accuracy.

## Contributors
- [Anup Dhoble](https://github.com/anupdhoble)

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgements
- Acknowledge any libraries, datasets, or resources used in the project.
- Mention any contributions or inspirations from other projects.
- Give credit to individuals or organizations that provided support or guidance.

