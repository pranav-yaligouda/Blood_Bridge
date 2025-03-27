# BloodBridge

This is a **Django-based Blood Bank Management System** that allows users to manage blood donations, requests, and stock.

## Features

- User authentication (Donor, Patient, Admin).
- Donors can register and update their profiles.
- Patients can request blood donations.
- Admin dashboard to manage blood stock and users.
- Automated tracking of blood availability.
- Secure database management.

## Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite3
- **Dependencies:** Django, Pillow

## Installation & Setup

### 1. Clone the Repository
```bash
git clone <repo-url>
cd bloodbankmanagement-master
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Admin Access)
```bash
python manage.py createsuperuser
```

### 6. Run the Server
```bash
python manage.py runserver
```

## License

This project is open-source and available under the MIT License.
