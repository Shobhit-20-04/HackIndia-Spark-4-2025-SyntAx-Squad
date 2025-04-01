# HackIndia-Spark-4-2025-SyntAx-Squad
# Project Repository

## Overview
This repository contains the code and assets for a **React Native** mobile application integrated with a **Django** backend. The application includes **Web3 authentication** for secure login and leverages **AI** for various intelligent features. The frontend is built with React Native, while the backend is powered by Django to provide AI-based functionalities.

## Features
- **React Native Frontend**: A mobile application with modern UI components and interaction flows.
- **Django Backend**: Handles all the business logic, AI functionalities, and Web3 authentication.
- **Web3 Authentication**: Secure login system using Web3 technologies (e.g., MetaMask).
- **AI Integration**: Python-based AI functionalities integrated via Django for personalized experiences.
- **Dial Pad**: A custom dial pad with text-to-speech (TTS) and speech-to-text (STT) features.
- **Call Logs & History**: Stores and displays call logs, integrated with Web3 login and AI features.

## Project Structure

Project/ 
  │── backend/ # Django backend with AI and Web3 authentication 
  │ ├── manage.py # Django project manager 
  │ ├── requirements.txt # Python dependencies for the backend 
  │ ├── backend/ # Main Django backend app folder 
  │ │ ├── init.py # Initialize the app 
  │ │ ├── settings.py # Django settings (database, middleware, etc.) 
  │ │ ├── urls.py # URL routing for backend endpoints 
  │ │ ├── views.py # Views for AI functionality and Web3 logic 
  │ │ ├── models.py # Database models for call logs and user data 
  │── frontend/ # React Native frontend 
  │ ├── src/ # Source code for the frontend application 
  │ │ ├── components/ # Reusable UI components (Button, Input, etc.) 
  │ │ ├── screens/ # Different screens of the mobile app (Login, Call Screen, etc.) 
  │ │ ├── App.tsx # Main entry point of the React Native application 
  │ ├── package.json # Node.js dependencies and scripts for the frontend 
  │── README.md # Project documentation (this file) 
  │── .gitignore # Gitignore file to exclude unnecessary files from version control

## Setup Instructions

### Backend Setup

1. **Install Backend Dependencies**: 
   After cloning the repository, navigate to the `backend` folder and install the required Python packages.

   ```bash
   cd backend
   pip install -r requirements.txt
2. **Database Migration: Apply migrations to set up the database for the backend**:

   ```bash
   python manage.py migrate
3. **Run the Django Development Server: Start the server locally to test the backend API.**

   ```bash
   python manage.py runserver

    
### Frontend Setup

1. **Install Frontend Dependencies: Navigate to the frontend folder and install the required dependencies.**

   ```bash
   cd frontend
   npm install
2. **Start the Frontend Application: Run the React Native development server.**
   
   ```bash
   npm start
