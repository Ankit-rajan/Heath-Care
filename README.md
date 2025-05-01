# 🏥 Health Care - Hospital Management System (Django)

This is a Django-based Hospital Management System that allows patients to book appointments, contact hospital staff, and get assigned doctors. Admins can manage appointments, assign doctors, and maintain patient records with an easy-to-use interface.

## 🚀 Features

- ✅ Patient Signup/Login
- ✅ Book Appointments
- ✅ Contact Form with Email Notifications
- ✅ Admin Panel
  - Assign doctors to patients with time/date
  - Edit/Delete appointments
  - Approve/Reject records
  - Admit/Discharge patients
- ✅ Email Notifications:
  - Appointment confirmation
  - Doctor assignment
  - Contact form responses
- ✅ Password Reset via Email
- ✅ Responsive and Modern UI

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django (Python)
- **Database**: SQLite (default Django DB)
- **Email**: Django's Email backend with SMTP (e.g., Gmail)
- **Deployment**: Localhost (can be extended to Heroku, Render, etc.)

## 📸 Screenshots

> _Include screenshots or a screen recording of key features for better understanding (optional)_

## 🔧 Installation & Setup

### Prerequisites

- Python 3.8 or above
- pip (Python package manager)
- Git

### Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/Ankit-rajan/Heath-Care.git
cd Heath-Care

# 2. Create a virtual environment
python -m venv venv
source venv/Scripts/activate  # For Windows
# source venv/bin/activate    # For macOS/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Make migrations & migrate the database
python manage.py makemigrations
python manage.py migrate

# 5. Create a superuser for the admin panel
python manage.py createsuperuser

# 6. Run the server
python manage.py runserver



✉️ Email Configuration
In settings.py, configure:

EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'your-email@gmail.com'
EMAIL_HOST_PASSWORD = 'your-app-password'

Make sure to enable less secure apps or use App Passwords if using Gmail.



## Project Structure

The project is organized as follows:
HospitalManagement_Django/
│
├── hospital/            # Core Django app
├── templates/           # HTML templates
├── static/              # CSS/JS/Images
├── db.sqlite3           # Default database
├── manage.py
└── .gitignore


- **`hospital/`**: Contains the main Django app for the hospital management system.
- **`templates/`**: Stores the HTML templates for rendering views.
- **`static/`**: Holds the static files (CSS, JavaScript, images) used by the application.
- **`db.sqlite3`**: The default SQLite database that comes with Django.
- **`manage.py`**: A command-line utility that helps with administrative tasks like migrations, starting the server, etc.
- **`.gitignore`**: Ensures certain files and directories (like `venv/`) are not tracked by Git.




🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙋‍♂️ Author

Ankit 

Roll No: 2203002024, 6th Semester, BCA

[GitHub Profile](https://github.com/Ankit-rajan)