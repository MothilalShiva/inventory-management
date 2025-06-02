# Inventory Management Dashboard 📦📊

## Project Overview 📝

The **Inventory Management Dashboard** is a full-stack web application designed to efficiently manage and monitor inventory. The project provides a user-friendly interface to track stock levels, product details, and sales data, enabling businesses to manage their inventory in real time. Built with **Next.js**, **Redux Toolkit**, **Node.js**, and **AWS services**, it ensures a smooth user experience with fast load times and scalable performance.

---

## Features 🚀

- **Real-Time Inventory Tracking** 📈  
  Track stock levels and product details in real time, updating inventory data as changes occur.

- **Data Analytics Dashboard** 📊  
  View and analyze inventory trends, sales data, and product performance using dynamic charts and graphs.

- **User Authentication** 🔐  
  Secure user authentication and authorization with role-based access to different parts of the application.

- **Efficient Data Management** 💾  
  Store and manage product data in a database with efficient querying and performance optimization.

- **Deployment and Scalability** ☁️📡  
  Deployed on AWS with services like **RDS**, **EC2**, **API Gateway**, **Amplify**, and **S3** for improved scalability and performance.

---

## Tech Stack 🛠️

### Frontend 🎨  
- **Next.js** ⚛️  
- **React.js**  
- **Redux Toolkit** 🧠  
- **Tailwind CSS** 🎨

### Backend ⚙️  
- **Node.js**  
- **Express.js**  
- **RESTful APIs** 🌐

### Database 🗄️  
- **MongoDB**  
- **AWS RDS** (for scalability)

### Cloud Services ☁️  
- **AWS EC2**  
- **AWS API Gateway**  
- **AWS Amplify**  
- **AWS S3**

---

## Installation & Setup 🏗️

### Prerequisites 📋  
- **Node.js** (v14 or higher)  
- **npm** (v6 or higher)  
- **MongoDB** (for local development, or an AWS RDS instance for production)

### Clone the Repository 🧬  
```bash
git clone https://github.com/MothilalShiva/inventory-management.git
cd inventory-management
```

### Install Dependencies 📦  
```bash
npm install
```

### Start the Development Server 🚀  
```bash
npm run dev
```

---

## Usage 📖  
- Log in or register as a user.  
- Navigate through the dashboard to view current inventory, add or update products, and monitor sales.  
- Admin users can access advanced features and analytics.  

---

## Project Structure 📂  
```
inventory-management/
│
├── client/                  # Frontend (Next.js)
│   ├── components/          # Reusable UI components
│   ├── pages/               # Application pages
│   └── styles/              # Tailwind CSS config
│
├── server/                  # Backend (Node.js/Express)
│   ├── controllers/         # Business logic
│   ├── models/              # MongoDB schemas
│   ├── routes/              # API endpoints
│   └── config/              # DB and cloud configs
│
├── public/                  # Static assets
├── .env                     # Environment variables
├── package.json             # Project metadata
└── README.md                # Project documentation
```

---

## Future Enhancements 🌟  
- Inventory export to CSV/Excel 📄  
- Email notifications on low stock 📬  
- Role-based dashboards for warehouse staff/admin  
- Audit logs for changes made to inventory history  

---


## Contributors 🤝  
Made with ❤️ by [Mothilal Shiva](https://github.com/MothilalShiva)
