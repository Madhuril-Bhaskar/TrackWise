# 🚀 TrackWise – Full Stack Expense Tracker (MERN)

**TrackWise** is a powerful and intuitive full-stack Expense Tracker application built using the **MERN Stack** – **MongoDB**, **Express.js**, **React.js**, and **Node.js**.

It allows users to securely manage their income and expenses, visualize their financial activity through interactive charts, and download detailed reports in Excel format.

---

## 🔧 Tech Stack

- **Frontend**: React.js, Tailwind CSS, Recharts, Axios, Vite  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JWT (JSON Web Token)

---

## ✨ Features

1. **User Authentication**  
   Secure login and sign-up with JWT authentication.

2. **Dashboard Overview**  
   Shows total balance, income, and expenses in summary cards.

3. **Income Management**  
   - Add, view, delete income  
   - Export income to Excel  

4. **Expense Management**  
   - Add, view, delete expenses  
   - Categorize expenses  
   - Export to Excel  

5. **Interactive Charts**  
   Visualize data with Bar, Pie, and Line charts.

6. **Recent Transactions**  
   View latest income and expense records.

7. **Download Reports**  
   Export all income and expense data in Excel format.

8. **Responsive Design**  
   Fully responsive for desktop, tablet, and mobile.

9. **Sidebar Navigation**  
   Easy access to Dashboard, Income, Expenses, Logout.

10. **Quick Delete**  
    Hover over entries to delete instantly.

---

## 📸 Screenshots
Below are some visuals of the TrackWise application:

### 📝 Sign-Up Page  
A clean and simple sign-up form to create a new account.

![Sign-Up Page](frontend/expense-tracker/src/assets/images/signup_page.png)

### 🔐 Login Page
Secure login page with JWT-based authentication.

![Login Page](frontend/expense-tracker/src/assets/images/login_page.png)

### 🧾 Dashboard Overview
Get an overview of total balance, income, and expenses with interactive charts.

![Dashboard Page](frontend/expense-tracker/src/assets/images/dashboard_page1.png)
![Dashboard Page](frontend/expense-tracker/src/assets/images/dashboard_page2.png)

### 💰 Income Management
Manage, view, and analyze your income sources easily.

![Income Page](frontend/expense-tracker/src/assets/images/income_page.png)

#### ➕ Add Income Page  
Form to add a new income entry with category and amount.

![Add Income Page](frontend/expense-tracker/src/assets/images/add_income.png)

### 💸 Expense Management
Track, categorize, and manage all your expenses.

![Expense Page](frontend/expense-tracker/src/assets/images/expense_page.png)

#### ➕ Add Expense Page  
Quickly add a new expense entry with necessary details.

![Add Expense Page](frontend/expense-tracker/src/assets/images/add_expense.png)

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/TrackWise.git
cd TrackWise
```
### 2. Install Dependencies

```bash
cd backend
npm install
```
```bash
cd frontend
cd expense-tracker
npm install
```
### 3. Environment Variables
   
-> TO SET UP MONGODB
```bash
> Go to https://www.mongodb.com/
> Login or Create an Account
> Now create a project by clicking on the “New Project” button
> Now, Enter the project name and Click “Next”
> Add Member If needed. Then click on “Create Project”
> Now click on “Clusters” option in side menu and Click on “Build a Cluster” 
button
>  Now, select the type of cluster and give a cluster name
> Select a server provider, select a region that is near you, and click on “Create 
Deployment”
> Now we will be directed to the connection steps page.
>  Here we need to add a connection IP address. Create a database user and click on the “Choose a 
connection method” button
> In the Next step, Select `Drivers` option to access the atlas database using our 
Node.js project 
> Now Copy the connection string
>  Paste the connection string inside `.env` file:
```
 
-> TO SET UP JWT
>  After updating the connection string, let generate our JWT_SECRET. For that run the following command in the terminal.
```bash
node -e "console.log(require('crypto').randomBytes(64).toString('hex'))" 
```
Now Copy the connection string and JWT_SECRET and paste
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLIENT_URL=http://localhost:5173
```
### 4. Run the App
```bash
cd backend
npm run dev
```
```bash
cd frontend
cd expense-tracker
npm run dev
```
---
📁 Folder Structure
---
```BASH
TrackWise/
│
├── backend/             # Node.js + Express server
│
└── frontend/
    └── expense-tracker/ # React + Vite + Tailwind frontend
```
---

📄 License
---
This project is licensed under the MIT License.
