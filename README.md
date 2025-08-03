# How to Use My Project

Follow these steps to set up and run the project on your local machine.

---

## Prerequisites

Make sure the following are installed:

- **Python**
- **PostgreSQL**
- **Pipenv**  
  ```bash
  pip install pipenv
  ```
- **Node.js & npm**  
  Download and install from [https://nodejs.org](https://nodejs.org)

---

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <your-repo-url>
   cd <your-project-folder>
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   pipenv install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

---

## Running the Project

### Start the Backend
```bash
cd backend
pipenv shell
uvicorn main:app --reload
```

### Start the Frontend
```bash
cd frontend
npm start
```

---

## Notes

- Ensure your PostgreSQL server is running.
- Update any necessary environment variables (such as database credentials) before starting the backend.
- If you are using `.env` files, make sure they are properly configured in the backend directory.

---

## Screenshots

<img src="https://github.com/user-attachments/assets/56325a74-943a-4cf4-b761-4ee360f9c5ae" alt="image1" width="100%"><br><br>
<img src="https://github.com/user-attachments/assets/4335f735-a7bb-43e1-b731-5fc0be2abddb" alt="image2" width="100%"><br><br>
<img src="https://github.com/user-attachments/assets/13942800-2b48-427f-ae23-c6d4a7b83e8d" alt="image3" width="100%"><br><br>
<img src="https://github.com/user-attachments/assets/03697618-7b8b-4524-af06-b8b1d9187e68" alt="image5" width="100%"><br><br>
<img src="https://github.com/user-attachments/assets/6b63c2a5-52a0-4591-a821-8a05ea18e746" alt="image6" width="100%"><br><br>
<img src="https://github.com/user-attachments/assets/147d8ea6-a23d-4e14-9294-ef58a468e315" alt="image7" width="100%"><br><br>
