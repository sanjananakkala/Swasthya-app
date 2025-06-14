# Saanjh Sahayak – AI-Powered Assistance for Elderly Care Homes

**Saanjh Sahayak** is a project focused on improving elderly healthcare using AI. This system supports clinical decision-making for caregivers and doctors in elderly homes by offering features like disease risk prediction, emergency alerts, patient record management, and AI-assisted diagnostics. The project aims to enhance personalized elderly care through intelligent technology and real-time insights.

## Features

- **Disease Risk Prediction**: Predict the likelihood of chronic diseases using AI and health metrics.
- **AI-Assisted Diagnosis**: Uses Gemma-2 LLM to provide diagnostic suggestions based on patient symptoms.
- **Emergency Alerts**: Sends real-time notifications to caregivers and doctors in critical situations.
- **Medical Record Management**: Securely store and access patient history, medications, and reports.
- **User Authentication**: Role-based login system for caregivers, doctors, and admin users.

## Tech Stack

- **Frontend**: React.js (for the interactive medical staff dashboard)
- **Backend**: Flask (for building REST APIs and LLM integration)
- **Database**: MongoDB (for storing patient records securely)
- **AI/LLM**: Gemma-2 via Ollama (for generating diagnostic predictions)
- **Styling**: Tailwind CSS (for responsive UI design)

## Installation

To get started with the project, follow these steps:

1. **Clone the repository** 
git clone https://github.com/yourusername/saanjh-sahayak.git
2. **Navigate to the project directory**
cd saanjh-sahayak
3. **Install backend dependencies**
cd backend
pip install -r requirements.txt
python app.py
4. **Install frontend dependencies**
cd frontend
npm install
npm start
5. **Start the application:**
**For the backend:**
cd server
nodemon server.js
**For the frontend:**
cd frontend
npm start
**For the Machine Learning:**
cd ML
python main.py
# USAGE
**Login/Register**: Users can register and log in as caregivers (elderly home) or medical staff to access their dashboards.
**Health Monitoring**: Users can track health metrics and monitor progress over time.
**Medication Reminders**: Set up notifications for medication schedules.
**Communication**: Engage with doctors and caregivers through the built-in video system.






