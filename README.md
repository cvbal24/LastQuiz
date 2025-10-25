## ⚙️ Installation Guide ⚙️ ##

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/cvbal24/LastQuiz.git
cd final
```

2️⃣ Create and Activate Virtual Environment
```bash
python -m venv .venv
.venv\Scripts\activate
```

3️⃣ Install Required Packages 
```bash
pip install -r requirements.txt
pip freeze > requirements.txt
```

4️⃣ Apply Database Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

5️⃣ Create a Superuser (Admin Account) - manage users and rides.
```bash
python manage.py createsuperuser
```
You'll be prompted to enter:
- Username
- Email address
- Password

6️⃣ Run the Development Server
```bash
python manage.py runserver
```
