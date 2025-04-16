# Full-Stack To-Do List Application

This project is a full-stack To-Do List application that integrates a **React frontend** with a **FastAPI backend**. The backend provides a RESTful API and uses **SQLite** for database storage, while the frontend allows users to add, edit, delete, and filter tasks.

## Setup Instructions

### Prerequisites
- **Node.js** and **npm** (for React frontend)
- **Python** (for FastAPI backend)
- **SQLite** (if not using the default setup)

---

### Frontend (FastAPI)

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
2. Install the frontend dependencies: 
   npm install
3. Run the development server:
   npm run dev
The frontend will be available at http://localhost:3000.
   
### Backend (React)
1. Navigate to the backend folder:

   cd fastapi-backend


2.Create and activate a virtual environment (for Python):

  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install the backend dependencies:

   pip install -r requirements.txt


4. Run the FastAPI development server:

   uvicorn app.main:app --reload
The backend will be available at http://localhost:8000.



Backend API Endpoints:
1. GET https://backendfastapi-rdsf.onrender.com/todos/  
   Description: Fetch all to-do items.  


2. POST https://backendfastapi-rdsf.onrender.com/todos/
Description: Create a new to-do item.


3. GET https://backendfastapi-rdsf.onrender.com/todos/{todo_id}
Description: Fetch a single to-do item by ID.


4. PUT https://backendfastapi-rdsf.onrender.com/todos/{todo_id}
Description: Update a to-do item by ID.


5. DELETE https://backendfastapi-rdsf.onrender.com/todos/{todo_id}
Description: Delete a to-do item by ID.


6. GET https://backendfastapi-rdsf.onrender.com/todos/filter/{status}
Description: Fetch to-do items filtered by status (completed or pending).
