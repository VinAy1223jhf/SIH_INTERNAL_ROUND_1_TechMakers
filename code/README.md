# Techmakers: Healthcare Assistant Platform

*Problem Statement ID: 1682*  
*Smart India Hackathon 2024*

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Our Solution](#our-solution)
- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Machine Learning Models](#machine-learning-models)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

Techmakers is an innovative healthcare assistant platform designed to leverage advanced machine learning models and a conversational chatbot to provide accurate disease predictions and personalized health insights. Developed for the Smart India Hackathon 2024, our platform aims to bridge the gap between patients and healthcare providers by offering accessible, reliable, and proactive health monitoring.

## Problem Statement

The healthcare industry faces significant challenges in terms of early diagnosis and patient engagement, especially in remote and underserved areas. Traditional healthcare systems often lack the infrastructure and resources to provide timely and personalized care, leading to delayed diagnoses and poor health outcomes.

*Problem Statement ID 1682* challenges us to develop a solution that enhances early disease detection, improves patient engagement, and ensures timely intervention using modern technology.

## Our Solution

Techmakers addresses these challenges by integrating state-of-the-art machine learning models for disease prediction with a user-friendly web application. The platform is designed to:
- *Predict Diseases*: Using advanced ML models to provide early detection of conditions such as diabetes and Parkinson's disease.
- *Engage Patients*: A dynamic chatbot offers insights based on the user's health data, encouraging proactive health management.
- *Provide Accessible Care*: The platform's intuitive design ensures ease of use, making healthcare accessible to users of all technological backgrounds.

## Features

- *Disease Prediction Models*: Real-time analysis and prediction for diseases like diabetes and Parkinson's based on user inputs.
- *Conversational Chatbot*: A smart chatbot that provides personalized health tips and insights, comparing current data with historical trends.
- *User Authentication and Secure Data Handling*: Ensures user privacy and data security through secure authentication and data storage practices.
- *Responsive and Intuitive UI*: Built using React.js and Tailwind CSS for a seamless user experience across devices.
- *Dynamic Forms and Input Handling*: Easily input health data and receive immediate feedback on potential health risks.
- *Real-Time Data Analysis*: Access to the most recent health data for accurate and timely predictions.

## Architecture

![Architecture](https://via.placeholder.com/800x400) (Placeholder for architecture diagram)

The architecture of Techmakers is designed to ensure scalability, security, and ease of use:

1. *Frontend*: Built with React.js and Tailwind CSS, providing a responsive and user-friendly interface.
2. *Backend*: Powered by Node.js and Express.js for robust API development, with MongoDB handling data storage.
3. *Machine Learning Models*: Integrated using Python and frameworks like TensorFlow and Keras, hosted on the backend for real-time inference.
4. *Chatbot Integration*: Developed using JavaScript and integrated into the frontend to interact with users and provide insights based on machine learning outputs.

## Technologies Used

- *Frontend*: React.js, Tailwind CSS, Redux, Vite
- *Backend*: Node.js, Express.js, MongoDB
- *Machine Learning*: Python, TensorFlow, Keras
- *Authentication*: JWT, Redux for state management
- *DevOps*: Docker, GitHub Actions for CI/CD
- *APIs*: RESTful APIs for seamless integration between frontend and backend

## Machine Learning Models

1. *Diabetes Prediction Model*: Uses features like pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age to predict the likelihood of diabetes.
   
2. *Parkinson’s Disease Prediction Model*: Utilizes vocal parameters such as MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), jitter metrics, shimmer metrics, NHR, HNR, RPDE, DFA, and others to determine the probability of Parkinson's disease.

Both models are trained on extensive datasets and fine-tuned to achieve high accuracy and reliability in predictions.

## Getting Started

To set up the project locally, follow these steps:

1. *Clone the Repository*:
   bash
   git clone https://github.com/Priyanshu14G/Techmakers.git
   
2. *Install Dependencies*:
   Navigate to both the client and server directories and run:
   bash
   npm install
   
3. *Set Up Environment Variables*:
   Create a .env file in the root directory and add your MongoDB URI and other environment variables as per the .env.example file.

4. *Run the Application*:
   Start the backend server:
   bash
   npm run dev
   
   Then start the frontend development server:
   bash
   npm start
   

## Usage

- *Login/Signup*: Users can create an account or log in to access personalized features.
- *Disease Prediction*: Navigate to the prediction form, enter the required health data, and receive immediate predictions.
- *Chatbot Interaction*: Engage with the chatbot for insights based on your health data and historical trends.

## Contributors

- *Priyanshu Gupta* - [GitHub](https://github.com/Priyanshu14G)
- *[Your Team Members]* - [GitHub Links]

We believe in collaboration and innovation. If you're interested in contributing, please reach out!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
