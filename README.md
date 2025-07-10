# Job Tracker API

A simple FastAPI backend service to manage job application tracking.
This project is designed as a starting point for building a Job Tracker SaaS with Python and FastAPI.

## Features
- FastAPI setup with a basic health check endpoint (/ping)
- Ready for extension to add job-related endpoints (CRUD)
- Lightweight and easy to run locally with Python virtual environment

### Prerequisites
- Python 3.8+
- Git

#### Setup Instructions
- Clone the repository
git clone https://github.com/saisri-damacharla/job-tracker.git
cd job-tracker

- Create and activate a virtual environment
On Windows (Git Bash):
python -m venv venv
source venv/Scripts/activate

- Install dependencies
pip install fastapi uvicorn

- Run the FastAPI server
uvicorn main:app --reload

- Open your browser and test the endpoint:
http://127.0.0.1:8000/ping → Should return {"message": "pong"}

