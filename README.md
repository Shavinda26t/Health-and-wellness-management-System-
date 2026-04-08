# Health and Wellness Management System (MediHeaven)

![Project Banner](https://img.shields.io/badge/Stack-MERN-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-ISC-green?style=for-the-badge)

A comprehensive, full-stack healthcare management solution designed to streamline clinic operations, patient care, and administrative tasks. Built with the **MERN** (MongoDB, Express, React, Node.js) stack, featuring a responsive UI and robust backend services.

---

## 🚀 Key Modules & Features

### 🏥 Patient & Doctor Management
- **Patient Records**: Secure management of patient profiles, history, and records.
- **Doctor Portal**: Doctor profile management, specialization tracking, and availability.
- **Appointment Scheduling**: Real-time booking system for patients with appointment tracking.

### 💊 Medical Services
- **Digital Prescriptions**: Generation and management of patient prescriptions.
- **Diagnosis Tracking**: Integrated system for recording patient diagnoses.
- **Feedback System**: Interactive feedback and rating system for patient experience.

### 📦 Inventory & E-Commerce
- **Product Store**: Integrated marketplace for healthcare and wellness products.
- **Cart & Checkout**: Seamless shopping experience for medical supplies.
- **Inventory Management**: Real-time tracking of stock levels and product details.

### 💰 Financial & Admin
- **Payroll Management**: Automated staff salary and payroll processing.
- **Petty Cash & Transactions**: Tracking of daily expenses and financial transactions.
- **Admin Dashboard**: Comprehensive analytics with interactive charts (Recharts & Chart.js).
- **PDF Reports**: Automated generation of prescriptions and financial reports using JSPDF.

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: React 19
- **Styling**: Tailwind CSS, Bootstrap 5, Styled Components
- **Animations**: Framer Motion
- **Charts**: Recharts, Chart.js
- **State/Routing**: React Router 7, Axios
- **UI Components**: React Bootstrap, Lucide Icons, FontAwesome

### Backend
- **Engine**: Node.js & Express
- **Database**: MongoDB (Atlas) with Mongoose ORM
- **Security**: JWT Authentication, Bcryptjs encryption
- **Validation**: Joi
- **Storage**: Multer for file/image uploads
- **Email**: Nodemailer for automated notifications

---

## ⚙️ Setup & Installation

Follow these steps to get the project running locally.

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB Atlas Account](https://www.mongodb.com/cloud/atlas) or Local MongoDB
- `npm` or `yarn` package manager

### 1. Clone the Repository
```bash
git clone https://github.com/Shavinda26t/Health-and-wellness-management-System-.git
cd Health-and-wellness-management-System-
```

### 2. Backend Configuration
1. Navigate to the backend directory:
   ```bash
   cd ITP/backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `backend` root and add your credentials:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   EMAIL_USER=your_email@gmail.com
   EMAIL_PASS=your_app_password
   ```
4. Start the backend:
   ```bash
   npm run dev
   ```

### 3. Frontend Configuration
1. Open a new terminal and navigate to the frontend directory:
   ```bash
   cd ITP/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend:
   ```bash
   npm start
   ```

---

## 📂 Project Structure

```text
├── ITP/
│   ├── backend/        # Node.js API
│   │   ├── Controllers/# Business logic for routes
│   │   ├── Middleware/ # Auth and validation middleware
│   │   ├── Model/      # Mongoose database schemas
│   │   ├── Routes/     # API endpoints
│   │   ├── Utils/      # Helper functions
│   │   ├── server.js   # Entry point
│   │   └── .env        # Environment variables
│   ├── frontend/       # React App
│   │   ├── public/     # Static assets
│   │   ├── src/
│   │   │   ├── Components/ # Reusable UI components
│   │   │   ├── Pages/      # Main application views
│   │   │   ├── App.js      # Root component
│   │   │   └── Main.js     # Entry point
└── README.md
```

---

## 📄 License
Distributed under the ISC License. See `LICENSE` for more information.

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
