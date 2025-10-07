# 💰 Wallet App

## 🧩 Overview
Wallet App is a full-stack application that helps users manage their income, expenses, and track overall balance efficiently.  
It includes a React frontend and a Spring Boot backend, communicating through REST APIs.

---

## 🚀 Features
- User registration and authentication (JWT)
- Add, update, and delete income/expense entries
- View expense reports and transaction history
- Real-time expense tracking dashboard
- Responsive, modern UI built with React
- Secure backend API built with Spring Boot and MySQL

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|-------------|
| Frontend | React.js, Axios |
| Backend | Spring Boot, Spring Security |
| Database | MySQL |
| Build Tools | Maven (backend), npm (frontend) |
| Version Control | Git, GitHub |

---

## ⚙️ Project Structure

```
Wallet-app/
│
├── expense-app-frontend-react/ # React frontend
│ ├── src/
│ ├── public/
│ └── package.json
│
├── expense-app-backend/ # Spring Boot backend
│ ├── src/
│ ├── pom.xml
│ └── application.properties
│
├── README.md
```

## 🧑‍💻 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Wallet-app.git
cd Wallet-app

Backend Setup (Spring Boot)
cd expense-app-backend

Configure database in src/main/resources/application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/wallet_db
spring.datasource.username=your_db_user
spring.datasource.password=your_db_password
spring.jpa.hibernate.ddl-auto=update

Run the backend:
mvn spring-boot:run
```

## Backend runs at 👉 http://localhost:8080

### 3️⃣ Frontend Setup (React)

```
cd ../expense-app-frontend-react
npm install

Create .env file:
REACT_APP_API_URL=http://localhost:8080

Run the frontend:
npm start

```
## Frontend runs at 👉 http://localhost:3000

### 🔗 API Integration
```
The React frontend consumes REST APIs from the Spring Boot backend.
For example:

Method	Endpoint	Description
POST	/api/auth/register	Register user
POST	/api/auth/login	Login user
GET	/api/transactions	Fetch all transactions
POST	/api/transactions	Add a new transaction
DELETE	/api/transactions/{id}	Delete transaction
📸 Screenshots (optional)


<img width="1725" height="842" alt="Screenshot (1144)" src="https://github.com/user-attachments/assets/3326489f-fba0-4bc9-bdc5-c01fd2f86648" />
<img width="1777" height="865" alt="Screenshot (1143)" src="https://github.com/user-attachments/assets/4b1e8a55-0f3f-4e1d-8d1c-1b19a82baf7b" />


```
### 👩‍💻 Author

## Vanshika Srivastava


---
