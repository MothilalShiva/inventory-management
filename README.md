# Inventory Management Dashboard

## Project Overview

The **Inventory Management Dashboard** is a full-stack web application designed to efficiently manage and monitor inventory. The project provides a user-friendly interface to track stock levels, product details, and sales data, enabling businesses to manage their inventory in real-time. Built with **Next.js**, **Redux Toolkit**, **Node.js**, and **AWS services**, it ensures a smooth user experience with fast load times and scalable performance.

## Features

- **Real-Time Inventory Tracking**  
  Track stock levels and product details in real time, updating inventory data as changes occur.

- **Data Analytics Dashboard**  
  View and analyze inventory trends, sales data, and product performance using dynamic charts and graphs.

- **User Authentication**  
  Secure user authentication and authorization with role-based access to different parts of the application.

- **Efficient Data Management**  
  Store and manage product data in a database with efficient querying and performance optimization.

- **Deployment and Scalability**  
  Deployed on AWS with services like **RDS**, **EC2**, **API Gateway**, **Amplify**, and **S3** for improved scalability and performance.

## Tech Stack

- **Frontend**:  
  - **Next.js**  
  - **React.js**  
  - **Redux Toolkit**  
  - **Tailwind CSS**

- **Backend**:  
  - **Node.js**  
  - **Express.js**  
  - **RESTful APIs**

- **Database**:  
  - **MongoDB**  
  - **AWS RDS** (for scalability)

- **Cloud Services**:  
  - **AWS EC2**  
  - **AWS API Gateway**  
  - **AWS Amplify**  
  - **AWS S3**

## Installation

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB (for local development, or an AWS RDS instance for production)

### Clone the repository

```bash
git clone https://github.com/MothilalShiva/inventory-management.git
cd inventory-management
Install dependencies
bash
Copy
Edit
npm install
Set up environment variables
Create a .env file and add the following variables:

makefile
Copy
Edit
MONGODB_URI=your_mongo_db_connection_string
AWS_ACCESS_KEY_ID=your_aws_access_key_id
AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
Start the development server
bash
Copy
Edit
npm run dev
This will start the application on http://localhost:3000.

Usage
Once the application is running, you can access the following key features:

Dashboard: View an overview of the inventory data with real-time updates.
Product Management: Add, update, or delete product details.
Sales Analytics: Analyze sales data and trends.
User Management: Admins can manage user roles and permissions.
Deployment
The application is deployed on AWS with scalable infrastructure. You can view the live application (if deployed) or deploy it using services like AWS EC2 and AWS Amplify.
License
This project is licensed under the MIT License - see the LICENSE file for details.
