# SAWILI EATs

## Overview

SAWILI eats is full-stack digital platform that enables restaurant owners and food vendors with tool to manage their business for smooth running

The system bridges the gap between traditional business management and modern technologh by offering features such as job tracking, customer management, inventory control, digital payments, food delivery, customers reviews and easy license renewal

## Features

### User Management
- User registration and authentication
- Role-based access (Admin, Vendor, Customer)
- Profile management

### Inventory Management
- Track raw produce and already made food
- Low stock alerts
- Category-based organization

### Order & Job Tracking
- Create and manage customer orders
- Track job progress (Pending → In Progress → Completed)
- Assign food deliveries and catering giggs to vendors

### Payments Integration
- M-Pesa integration for seamless payments
- Payment status tracking
- Transaction history
- Card and paypall cashless payment intergration

### Communication
- Real-time chat between customers and vendors
- Notifications for updates and messages

### Dashboard & Analytics
- Admin dashboard with system overview
- Business insights (sales, orders, revenue)
- Activity logs
10:35 AM
 
## Tech Stack

**Fronted**
- React.js
- Tailwindcss
- Axios
- Redux

**Backend**
- Django
- django Rest Framework (DRF)
- PostgreSQL

**DevOps $ Deployment**
- Docker
- Github Actions (CI/CD)
- CluodHosting (AWS/ Render / Azure )


## Project Structure##
text
SAWILI-EATS/
│
├── frontend/                # React application
│   ├── src/
│   ├── components/
│   └── pages/
│
├── backend/                # Django application
│   ├── apps/
│   ├── models/
│   ├── views/
│   └── api/
│
├── docker/                 # Docker configurations
├── docs/                   # Documentation
├── .env.example            # Environment variables template
├── requirements.txt
├── package.json
└── README.md
``


## Installarion & Setup

```bash
git clone https://github.com/Sawandda-Seth/SAWILI-EATS.git

cd SAWILI-EATS

Open index.html in any modern browser and view your site

Prerequisites

* Node.js (v16+)
* Python (v3.10+)
* PostgreSQL
* Docker (optional)

Backend Setup (Django)

**Bash**

# Clone repository
git clone [https://github.com/Sawanda-Seth/SAWILI-EATS.git](https://github.com/Sawandda-Seth/SAWILI-EATS.git)

cd SAWILI-EATS/backend

# Create virtual environment
python -m venv env
source env/bin/activate   # Windows: env\\Scripts\\activate

# Install dependencies
pip install -r requirements.txt

# Configure environment variables
cp .env.example .env

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver


Frontend Setup (React)

**Bash**

cd ../frontend

# Install dependencies
npm install

# Start development server
npm start
```

## API Endpoints

| **Methods** | **Endpoints** | **Description** |
| -------------- | ------------ | ------------- |
| POST            | `api/auth/register/` | Register user|
| POST            | `api/auth/login/` | Login user|
| GET            | `api/orders/` | List Orders|      
| POST            | `api/orders/` | Create Order|      
| GET            | `api/orders/` | View Inventory |  

## Environment Variables

Create a .env file in both frontend and backend directories:

Backend

**Plaintext**

SECRET_KEY=your_secret_key
DEBUG=True
DB_NAME=jua_kali_db
DB_USER=postgres
DB_PASSWORD=your_password
MPESA_CONSUMER_KEY=your_key
MPESA_CONSUMER_SECRET=your_secret


## Frontend

**Plaintext**

REACT_APP_API_URL=http://localhost:8000/api


## Testing

**Bash**

# Backend tests
python manage.py test

# Frontend tests
npm test


## Deployment

1. **Build frontend:** npm run build
2. **Use Docker for full-stack deployment:** docker-compose up --build
3. **Deploy on:**
   * AWS (EC2 / S3)
   * Azure
   * Render / Vercel (frontend)

Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push to your branch
5. Open a Pull Request


# Author

**Seth Sawanda**

* GitHub: https://github.com/Sawandda-Seth
* Email: Sawandawork@gmail.com 

# Vision

To digitize and empower the Jua Kali sector by providing accessible, scalable, and efficient software solutions that enhance productivity and market reach.