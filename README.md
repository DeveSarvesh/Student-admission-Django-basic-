**📘 Student Admission System – Django Project**
This is a basic Student Admission System built using the Django web framework as part of an internship task.
The project demonstrates the use of Django templates, static files, views, and routing using urls.py. No models or databases are used in this version.

**🗂️ Technologies Used**
Backend: Python, Django (no models used)
Frontend: HTML, CSS (via Django templates and static files)
Version Control: Git & GitHub

📁 Folder Structure Overview
css
Copy
Edit
student_admission/
├── main/
│   ├── templates/main/
│   ├── static/main/
│   ├── views.py
│   ├── urls.py
├── student_admission/
│   ├── settings.py
│   ├── urls.py
├── manage.py
├── .gitignore

**🚀 How to Run**
Clone the repository
git clone https://github.com/YourUsername/student-admission-system.git

Navigate to the project folder
cd student-admission-system

Create virtual environment (optional but recommended)
python -m venv venv && source venv/bin/activate (Linux/Mac)
venv\Scripts\activate (Windows)

Install Django
pip install django

Run the server
python manage.py runserver

Open http://127.0.0.1:8000/ in your browser
