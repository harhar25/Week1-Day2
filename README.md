#The files is on the "MASTER" Branch

# 🐍 Login & Profile Management System
---



- User registration with unique username and email
- Secure password hashing (using Werkzeug)
- Login/logout functionality with Flask-Login session management
- Editable user profile with:
  - Profile image upload
  - Personal information (name, birthday, sex, degree, phone, address)
  - Auto age calculation from birthday
- SQLite database integration via SQLAlchemy ORM
- Upload validation (only png, jpg, jpeg, gif images)
- Flash messaging for user feedback
- Responsive and clean front-end using HTML + CSS

---

Technologies Used

- Python 3
- Flask
- Flask-Login
- Flask-SQLAlchemy
- Werkzeug
- SQLite (local database)

---

📝 Setup Instructions

Clone the repository:

```bash
git clone https://github.com/harhar25/Week1-Day2.git
cd Week1-Day2

**Create and activate a virtual environment:**
python -m venv venv
.\venv\Scripts\activate     # On Windows
source venv/bin/activate    # On Mac/Linux

**Install dependencies:**
pip install -r requirements.txt

**Run the application:**
python app.py
Access it at: http://127.0.0.1:8000

📁 Project Structure
/static/uploads/           # Profile images upload folder
/templates/                # HTML templates (login.html, register.html, profile.html)
app.py                     # Main Flask application file
requirements.txt           # Python dependencies
README.md                  # Project overview


🛡️ Security Notes

*Passwords are hashed before storage.
*Uploaded files are sanitized using secure_filename.
*Upload types restricted to images only (png, jpg, jpeg, gif).
*User sessions managed securely via Flask-Login.

📌 To-Do / Improvements

**Add email verification**
**Integrate user role management (admin, user)**
**Add pagination for users list (if listing)**
**Use PostgreSQL/MySQL for production-ready deployment**
**Dockerize the app for containerized deployment**

📸 Demo Screenshot

![image](https://github.com/user-attachments/assets/15b6f1d9-8e61-43a2-92e6-2b6c5bd174e4)
![image](https://github.com/user-attachments/assets/c14f031d-25b8-4a02-8be8-91f5f4c2c809)
![Screenshot 2025-06-04 004915](https://github.com/user-attachments/assets/5adf9671-26c6-4144-b4d9-a0302eaf902f)

📃 License
MIT License.
Free to use, modify, and share.

🙌 Acknowledgments

**Flask Documentation**
**Flask-Login Documentation**
**Flask-SQLAlchemy Documentation**



