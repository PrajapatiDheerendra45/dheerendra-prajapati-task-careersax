# Creers AXS TAsk

This is a **User Management System** built with **React.js (Frontend)** and **Express.js with MOngoDB (Backend)**. The system includes authentication, user management, and external API integration.

## Features

### Backend (Express.js + MongoDB)
- **Authentication:** Login using email & password with JWT token generation and expiry.
- **User Management:** Create, Login


### Frontend (React.js+ Tailwind css)
- **Login Screen**
- **Registration**
- **Dashboard** 


---

## Project Setup


### Clone the Repository
```sh
git https://github.com/PrajapatiDheerendra45/dheerendra-prajapati-task-careersax.git

```

---

## Backend Setup (Express + MOngoDB)

### 1. Install Dependencies
```sh
npm install
```

### 2. Configure Database
```env
PORT=5000
MONGO_URI=mongodb+srv://dheeru:Praja%40123@libraraymanagement.8sm6a.mongodb.net/CareearsAXSTask
JWT_SECRET=yourjwtsecret

```


### 4. Start the Backend Server
```sh
 nodemon   #  use nodemon for auto-restart
node server.js #OR
```

Backend will run on `http://localhost:5000`

---

## Frontend Setup (React + Tailwind CSS)

### 1. Navigate to Frontend Directory
```sh
cd client
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Configure Environment Variables
Create a `.env` file inside `client/` with the following:
```env
REACT_APP_API_BASE_URL=http://localhost:5000
```

### 4. Start the Frontend Server
```
cd client 
npm install
npm start
```
Frontend will run on `http://localhost:3000`

---
### 4. Start the Backend Server
```

npm install
### start command
nodemon
or
node server.js
```
Backend will run on `http://localhost:5000`

---

## API Endpoints

### **Authentication**
- `POST http://localhost:5000/api/auth/login` - Login user

### **User Management**

- `POST http://localhost:5000/api/auth/register` - Create a new user
- `POST http://localhost:5000/api/auth/login` -loin

---



### Frontend Deployment (Vercel/Netlify)
- Build the frontend:
```sh
cd client
npm run build
```
- Deploy `client/build/` 

---

## Tech Stack
- **Frontend:** React.js,  Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, JWT
- **Database:** MongoDB
- **Deployment:** onrender (Frontend),onrender  (Backend)

---

## Author
Developed by **Your Name** - [GitHub](https://github.com/PrajapatiDheerendra45/dheerendra-prajapati-task-careersax.git)

---

## Deploy link
  Deploy by **Dheerendra prajapati** - [onrender]( https://dheerendra-prajapti-task-carearaxs.onrender.com/)
 
 test email - dkp@gmail.com
 test password- 123456


