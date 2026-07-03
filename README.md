# EduTwin - Student Result Management System

A beginner-friendly, fully functional web application for managing student results.

## Tech Stack
- Frontend: HTML, CSS, Vanilla JavaScript
- Backend: Python (Flask)
- Database: SQLite

## Features
- **Admin Panel**: Add students, enter subject-wise marks, delete records, view summary tables.
- **Student Panel**: Login securely via Roll Number and Password, view subject-wise marks, total, percentage, and grade.
- **Dynamic Calculation**: Automatically calculates percentage and grades.

## Setup Instructions

1. **Install Flask**
   ```bash
   pip install flask
   ```

2. **Run the Application**
   Navigate to the project directly and run:
   ```bash
   python app.py
   ```

3. **Access the Application**
   Open your browser and navigate to `http://127.0.0.1:5000/`

4. **Default Admin Login**
   - Username: `admin`
   - Password: `admin`

5. **Existing Students (Migration)**
   - The system now features secure password-based authentication for students.
   - For databases created before this update, existing student accounts have been safely migrated but do not have a password configured. These legacy accounts cannot authenticate until an administrator assigns them a password.

   ## 📁 Project Structure
   Edu/
├── static/          # CSS, JS, images
├── templates/       # HTML templates
├── app.py           # Main Flask application
├── database.db      # SQLite database
├── requirements.txt # Dependencies
└── README.md
## 🤝 Contributing
1. Fork the repository
2. Create new branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m 'feat: add feature'`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License.

---
⭐ Star this repo if you found it helpful!
