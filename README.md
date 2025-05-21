# rxledger-portal
// README.md

# RxLedger Portal

RxLedger is a B2B web application platform connecting *retailers, **wholesalers, and **delivery representatives* for seamless medicine order management, smart billing, Excel-based ledgers, and real-time delivery tracking.

## Features

### Retailer
- Browse products from wholesalers
- Place orders with one click
- View and track order ledger

### Wholesaler
- Manage products and offers
- Upload inventory via Excel
- Assign delivery reps by area

### Delivery Representative
- View assigned deliveries
- Update delivery status

## Tech Stack
- *React.js* with Tailwind CSS (Frontend)
- *ShadCN UI* Components
- Mock login and local state (future: Firebase/Auth API)
- Excel upload support (CSV/XLSX - basic reader)

## Screenshots
> Add screenshots here (UI dashboard views per role)

## Getting Started

1. *Clone the repo:*
bash
git clone https://github.com//rxledger-portal.git
cd rxledger-portal


2. *Install dependencies:*
bash
npm install


3. *Run the app:*
bash
npm run dev


4. *Deploy to Vercel:*
- Go to [https://vercel.com](https://vercel.com)
- Click *Add New > Project*
- Import the rxledger-portal repository
- Set framework to *React*
- Leave build settings default
- Click *Deploy*

Your site will be live at: https://rxledger-portal.vercel.app

## Todo / Upcoming
- Firebase login + role-based auth
- Real Excel parsing with SheetJS
- Backend API for order/inventory
- Admin analytics dashboard

---

*Made with love for B2B pharmacy automation.*
