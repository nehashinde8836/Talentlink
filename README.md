# TalentLink – Freelance Marketplace Platform

TalentLink is a full-stack freelance marketplace platform that connects clients and freelancers in a seamless digital workspace. The platform enables users to post projects, submit proposals, manage contracts, and communicate securely.

---

## Features

- User Authentication with JWT
- Role-based Access (Client & Freelancer)
- Project Posting and Management
- Proposal Submission System
- Contract Management
- Secure REST APIs using Django REST Framework
- Responsive UI with React.js
- Dashboard for Projects and Applications
- Real-time Collaboration Workflow

---

## Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Django
- Django REST Framework

### Authentication
- JWT (JSON Web Token)

### Database
- SQLite / PostgreSQL

---

## Project Structure

```bash
TalentLink/
│
├── frontend/        # React Frontend
├── backend/         # Django Backend
├── screenshots/     # Project screenshots
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/talentlink.git
cd talentlink
```

---

### 2️⃣ Backend Setup

```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Backend runs on:

```bash
http://127.0.0.1:8000/
```

---

### 3️⃣ Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

Frontend runs on:

```bash
http://localhost:3000/
```

---

## Authentication Flow

- Users can register as:
  - Client
  - Freelancer
- JWT authentication is used for secure login and API access.

---


---

## Future Enhancements

- Real-time Chat System
- Payment Gateway Integration
- AI-based Freelancer Recommendation
- Notifications and Email Alerts
- Deployment on AWS

---

## Author

Neha Shinde

- GitHub: https://github.com/nehashinde8836
- LinkedIn: https://www.linkedin.com/in/neha-shinde-software-engineer/

---

## 📄 License

This project is developed for educational and learning purposes.
