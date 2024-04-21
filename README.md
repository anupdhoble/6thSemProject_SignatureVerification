
# Signature Verification System Using CNN

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

## Future Improvements
- Implement user authentication for secure access to the application.
- Enhance the frontend with more intuitive features and visualizations.
- Explore advanced deep learning techniques for improved signature verification accuracy.

## Contributors
- [Your Name](https://github.com/your-username)

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgements
- Acknowledge any libraries, datasets, or resources used in the project.
- Mention any contributions or inspirations from other projects.
- Give credit to individuals or organizations that provided support or guidance.

