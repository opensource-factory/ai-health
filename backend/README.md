# AI Health App – Backend

This is the **FastAPI backend** for the AI Health application.  
It provides APIs for health tracking, user data, and AI-powered health insights.

---

## Tech Stack

- **Python**
- **FastAPI**
- **Uvicorn**
- **Pydantic**

Future additions:

- PostgreSQL
- SQLAlchemy
- JWT Authentication
- AI / ML health models

---

## Project Structure


backend
│
├── app
│ └── main.py # FastAPI entry point
│
├── venv # Python virtual environment
└── requirements.txt # Python dependencies


---

## Setup Instructions

### 1. Navigate to backend folder


cd backend


### 2. Create virtual environment


python -m venv venv


### 3. Activate virtual environment

Windows:


venv\Scripts\activate


Mac / Linux:


source venv/bin/activate


---

### 4. Install dependencies


pip install -r requirements.txt


---

### 5. Run development server


uvicorn app.main:app --reload


---

## API Access

Backend server:


http://127.0.0.1:8000


Swagger API documentation:


http://127.0.0.1:8000/docs


OpenAPI schema:


http://127.0.0.1:8000/openapi.json


---

## Development Notes

- FastAPI automatically generates API documentation.
- Use `--reload` during development to enable auto reload.
- This backend will later handle:
  - user accounts
  - health metrics
  - workout tracking
  - nutrition tracking
  - AI health recommendations