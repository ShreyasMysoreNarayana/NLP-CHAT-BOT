# NLP-CHAT-BOT
An End-To-End NLP Chat Bot for Websites

📌 Overview
This project is an AI-powered chatbot that integrates Google Dialogflow with a FastAPI backend and a frontend web interface. It supports natural language understanding, database interactions, and web-based deployment.

🚀 Features
Dialogflow Integration: Handles intent recognition and entity extraction

FastAPI Backend: Serves as the API layer for chatbot responses

MySQL Database: Stores chat history and other relevant data

Frontend Web Interface: Enables users to interact with the chatbot

ngrok Support: Facilitates HTTPS tunneling for local development

🛠️ Tech Stack
NLP Platform: Google Dialogflow

Backend: Python (FastAPI)

Database: MySQL

Frontend: Web-based interface

Deployment: ngrok for tunneling, Uvicorn for running FastAPI

📂 Project Structure
📦 chatbot-project
 ┣ 📂 backend             # FastAPI backend code
 ┣ 📂 db                 # MySQL database dump
 ┣ 📂 dialogflow_assets  # Intent training data
 ┣ 📂 frontend           # Website code
 ┣ 📜 README.md          # Documentation
 ┣ 📜 requirements.txt   # Backend dependencies


🔧 Setup & Installation
1️⃣ Install Dependencies
pip install -r backend/requirements.txt

2️⃣ Import the Database
Open MySQL Workbench

Import the database dump from the db folder

3️⃣ Start FastAPI Backend
cd backend
uvicorn main:app --reload

4️⃣ Set Up ngrok for HTTPS Tunneling
Download and install ngrok

Open a command prompt and navigate to the ngrok folder

Run:
ngrok http 8000
Copy the generated HTTPS URL and update it in Dialogflow for webhook integration

🚀 Deployment
Deploy the FastAPI backend on a cloud platform (e.g., AWS, GCP)

Use Firebase Hosting for the frontend

Configure Dialogflow webhooks with your API URL

📌 Future Enhancements
Implement OAuth for secure authentication

Add support for multiple languages

Integrate with external APIs for enhanced responses
