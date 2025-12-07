# Car Rental System

A complete car rental management system built with Flask.

## Features

- **User Features:**
  - Browse available cars
  - Book cars with date selection
  - Upload ID and driver's license
  - View booking history
  - Make payments (GCash, Cash, Card)
  - Write reviews for rented cars

- **Admin Features:**
  - Manage cars (Add, Edit, Delete)
  - Manage users and admins
  - View and manage bookings
  - Update booking status (Pending → Approved → Returned → Completed)
  - View dashboard with statistics
  - Date overlap validation

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd "ACP FINAL PROJECT - Car Rental"
```

2. Create virtual environment:
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create database:
```bash
cd rent_a_car
python create_db.py
```

5. Run the application:
```bash
python app.py
```

6. Access the application:
- Open browser: `http://127.0.0.1:5000`
- Admin login: `admin@example.com` / `admin123`

## Project Structure

```
rent_a_car/
├── app.py              # Main application file
├── models.py           # Database models
├── forms.py            # Form definitions
├── create_db.py        # Database creation script
├── templates/          # HTML templates
├── static/             # CSS, JS, Images
└── instance/           # Database files (not in git)
```

## Technologies

- **Backend:** Flask, SQLAlchemy
- **Database:** SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** Flask-Login
- **Forms:** Flask-WTF

## Default Admin Account

- Email: `admin@example.com`
- Password: `admin123`

## License

This project is for educational purposes.
