# Expense Management System

A full-stack Expense Management System built with a FastAPI backend and a Streamlit frontend.  
The application allows users to record, view, and manage expenses through a simple web interface backed by REST APIs.

The project follows a clear separation between frontend, backend, and tests, making it easy to understand, extend, and maintain.

---

## Architecture Overview

- Frontend: Streamlit-based user interface
- Backend: FastAPI server exposing REST endpoints
- Tests: Automated tests for backend and frontend components

---

## Project Structure

expense-management-system/
├── frontend/        # Streamlit UI
├── backend/         # FastAPI server and API logic
├── tests/           # Test cases
├── requirements.txt # Python dependencies
└── README.md        # Project documentation

---

## Setup and Execution

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/expense-management-system.git
cd expense-management-system
2. Install dependencies
pip install -r requirements.txt
3. Start the backend server
uvicorn backend.server:app --reload
4. Run the frontend application
streamlit run frontend/app.py
Notes
The backend service must be running before starting the frontend.

Designed with a production-style separation of concerns.

Can be extended with authentication, database persistence, or cloud deployment.
