# 🧑‍🏫 Quizo - Quiz Management System 🎯

Quizo is a **full-stack quiz management system** that allows users to **create, edit, and manage quizzes**.  
Built with **React (ShadCN UI) + Node.js (Express) + MySQL**, featuring **dark mode, authentication, and animations**.

![Quizo Banner](https://via.placeholder.com/1200x400.png?text=Quizo+-+Quiz+Management+System)

---

## 📌 **Features**
✅ **User Authentication (Login/Logout)**  
✅ **Dark Mode with Toggle**  
✅ **Quiz CRUD (Create, Read, Update, Delete)**  
✅ **ShadCN UI for Modern Styling**  


---

## 🛠 **Tech Stack**
### **Frontend**
- **React.js (Vite)**
- **TypeScript**
- **ShadCN UI (Tailwind)**
- **Axios**
- **React Router**

### **Backend**
- **Node.js (Express)**
- **TypeScript**
- **MySQL (Database)**
- **bcrypt.js** (Password Hashing)
- **dotenv** (Environment Variables)
- **cors & body-parser**

---

## Setup the Backend
cd backend

npm install

Create a .env file inside backend/:
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=quiz_db


Then, start the backend:
npm run dev
✅ Backend runs on http://localhost:5000/

## Setup the Frontend
cd ../frontend


npm install

Create a src/config.ts file:
const API_BASE_URL = "http://localhost:5000/api";
export default API_BASE_URL;
Start the frontend:
npm start
✅ Frontend runs on http://localhost:3000/

## 🎯 API Endpoints (Backend)
Authentication
POST	/api/auth/login	(Login user)

Quizzes

GET	/api/quizzes	Get all quizzes

POST	/api/quizzes	Create a new quiz

PUT	/api/quizzes/:id	Update a quiz

DELETE	/api/quizzes/:id	Delete a quiz

Add environment variables:

DB_HOST=<your-db-host>

DB_USER=<your-db-user>

DB_PASSWORD=<your-db-password>

DB_NAME=quiz_db


![alt text](https://github.com/yxshwant/QUIZO/blob/main/images/Screenshot%202025-02-20%20125345.png)
![alt text](https://github.com/yxshwant/QUIZO/blob/main/images/Screenshot%202025-02-20%20125350.png)
![alt text](https://github.com/yxshwant/QUIZO/blob/main/images/Screenshot%202025-02-20%20125359.png)
![alt text](https://github.com/yxshwant/QUIZO/blob/main/images/Screenshot%202025-02-20%20125405.png)
![alt text](https://github.com/yxshwant/QUIZO/blob/main/images/Screenshot%202025-02-20%20125419.png)
![alt text](https://github.com/yxshwant/QUIZO/blob/main/images/Screenshot%202025-02-20%20125425.png)
