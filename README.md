## ⚙️ Installation Guide ⚙️ ##

### 1️⃣ Clone the Repository
git clone https://github.com/https:/https://github.com/KerstinPaguio/FINAL.git
cd final

2️⃣ Create and Activate Virtual Environment
python -m venv .venv
.venv\Scripts\activate

3️⃣ Install Required Packages 
pip install -r requirements.txt
pip freeze > requirements.txt

4️⃣ Apply Database Migrations
python manage.py makemigrations
python manage.py migrate

5️⃣ Create a Superuser (Admin Account) - manage users and rides.
python manage.py createsuperuser
You'll be prompted to enter:
- Username
- Email address
- Password

6️⃣ Run the Development Server
python manage.py runserver
