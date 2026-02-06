# money-manager
Money Manager – Web Application

A full-stack Money Manager Web Application designed to help users track income, expenses, and account transactions with powerful analytics and filtering features.

📌 Overview

Money Manager allows users to:

Record income and expenses

Analyze finances weekly, monthly, and yearly

Categorize transactions into Personal and Office

Manage multiple accounts and transfer funds between them

This project is built as part of a full-stack assessment / hackathon using React, Node.js, and MongoDB Atlas.

🚀 Live Application

Frontend: https://your-frontend-url

Backend API: https://your-backend-url

GitHub (Frontend): https://github.com/username/money-manager-frontend

GitHub (Backend): https://github.com/username/money-manager-backend

✨ Features
📊 Dashboard

Weekly, Monthly, and Yearly income & expense analytics

Income vs Expense charts

Category-wise expense summary

Real-time balance calculation

💸 Income & Expense Management

Add income and expenses via modal popup

Categories: Fuel, Food, Medical, Loan, Movie, etc.

Divisions: Personal and Office

Date & time tracking

Edit transactions within 12 hours only

Delete transactions

Full transaction history

🔍 Filters & Reports

Filter by:

Income / Expense

Category

Division (Personal / Office)

Date range

Search transactions by description

🏦 Account Management

Create multiple accounts (Cash, Bank, etc.)

Track real-time account balances

Transfer amount between accounts

Transaction history for each account

🎨 UI & UX

Responsive design (Mobile, Tablet, Desktop)

Tailwind CSS for clean UI

Color indicators (Green = Income, Red = Expense)

Form validations & error handling

🛠 Tech Stack
Frontend

React.js

Tailwind CSS

Recharts

Axios

date-fns

Lucide Icons

Backend

Node.js

Express.js

MongoDB Atlas

Mongoose

Deployment

Frontend: Vercel

Backend: Render

Database: MongoDB Atlas

📁 Project Structure
Frontend
money-manager-frontend/
├── src/
│   ├── components/
│   ├── services/
│   ├── App.js
│   └── index.js
├── public/
├── package.json
└── README.md

Backend
money-manager-backend/
├── models/
├── routes/
├── config/
├── server.js
├── package.json
└── README.md

🔧 Installation & Setup
Clone Repositories
git clone https://github.com/username/money-manager-frontend
git clone https://github.com/username/money-manager-backend

Backend Setup
cd money-manager-backend
npm install


Create .env

MONGODB_URI=your_mongodb_connection_string
PORT=5000


Run backend:

npm start

Frontend Setup
cd money-manager-frontend
npm install


Create .env

REACT_APP_API_URL=http://localhost:5000


Run frontend:

npm start

🔌 API Endpoints
Transactions
GET    /api/transactions
POST   /api/transactions
PUT    /api/transactions/:id
DELETE /api/transactions/:id

Accounts
GET    /api/accounts
POST   /api/accounts
POST   /api/accounts/transfer

Dashboard
GET /api/dashboard/stats

🧪 Sample Testing Data
Income

Salary – ₹30,000 (Personal)

Freelance – ₹8,000 (Office)

Expenses

Fuel – ₹1,200

Food – ₹900

Medical – ₹1,500

Accounts

Cash

Bank

Office Account

🚀 Deployment
Backend (Render)

Connect GitHub repo

Add environment variables

Start command: npm start

Frontend (Vercel)

Import GitHub repo

Add REACT_APP_API_URL

Deploy

📌 Key Highlights for Evaluation

Clean full-stack architecture

Strong CRUD logic

Real-time analytics

Edit restriction logic (12 hours)

Modular & scalable code

Professional UI using Tailwind CSS

🛣 Future Enhancements

User authentication

Budget alerts

CSV/PDF export

Recurring transactions

Multi-user support

Mobile app

👨‍💻 Author

Lokesh B
