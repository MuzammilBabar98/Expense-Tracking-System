**Expense Management System**

A full-stack Expense Management System built with a FastAPI backend and a Streamlit frontend.
The system allows users to record, view, and manage expenses through a lightweight web interface backed by a RESTful API.

The project is structured with clear separation between frontend, backend, and tests, making it easy to extend, maintain, and deploy.

Architecture Overview

Frontend: Streamlit application providing the user interface for expense input and visualization

Backend: FastAPI server exposing REST endpoints for expense operations

Tests: Automated tests covering backend and frontend logic

Project Structure
expense-management-system/
│
├── frontend/        # Streamlit UI
├── backend/         # FastAPI server and API logic
├── tests/           # Test cases
├── requirements.txt # Python dependencies
└── README.md        # Project documentation

Setup & Execution
1. Clone the repository
git clone https://github.com/yourusername/expense-management-system.git
cd expense-management-system

2. Install dependencies
pip install -r requirements.txt

3. Start the backend server
uvicorn backend.server:app --reload

4. Run the frontend application
streamlit run frontend/app.py

Notes

The backend must be running before starting the frontend.

The project is intended for learning and experimentation but follows production-style separation of concerns.

Can be easily extended with authentication, database persistence, or cloud deployment.

