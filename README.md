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

BiyaHero is a web-based ride-booking platform designed to connect customers and riders efficiently. 
It allows users to request rides, manage bookings, and track ride history with role-based dashboards 
for Customers, Riders, and Staff.

Fixes:
- Sign-in and sign-up functionality (login for existing accounts, register for new ones)
- Customer dashboard now displays user balance and ride details
- Implemented dashboard features: Active Rides, Request a Ride, Ride History, and My Profile
- Added ride request form showing pickup and destination list with minimum fare offer

To be fixed:
- Role identification and proper dashboard redirection (Customer, Rider, Staff)
- Sidebar feature link functionality across roles
- Booking and ride confirmation process
