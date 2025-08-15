# 💸 FinTrack - Personal Finance Tracker

FinTrack is a full-stack expense and income tracker that helps users manage their personal finances with ease. It provides a clean dashboard, data visualization, and secure user authentication.

---

## 🚀 Features

- 🔐 User Authentication with JWT (Register/Login)
- 📊 Dashboard with Income & Expense Tracking
- 📈 Visual Analytics using Recharts
- 📁 Profile Image Upload with Multer
- 📤 Export Financial Data as Excel (.xlsx)
- 🌐 RESTful API with Express & MongoDB
- ⚡ Fast Frontend using React + Vite + TailwindCSS

---

## 🛠 Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- Axios
- Recharts
- React Router DOM

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- JWT for authentication
- Bcrypt for password hashing
- Multer for file uploads
- XLSX for Excel export
- Dotenv for environment management

---

## 📂 Project Structure

```
FinTrack/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── config/
│   ├── uploads/
│   ├── server.js
│   └── .env
├── frontend/
│   ├── src/
│   ├── public/
│   └── vite.config.js
```

---

## 🧪 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/phegde298/FinTrack.git
cd FinTrack
```

### 2. Backend Setup
```bash
cd backend
npm install
# Create a .env file with the following:
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
npm run dev
```

### 3. Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```

---

## 📷 Screenshots
_Add screenshots or gifs of the dashboard, login, and analytics pages here._

---

## 🧑‍💻 Authors
**Prakruti Hegde**
**Bhoomi Pandey**  
Feel free to connect on [LinkedIn]([https://www.linkedin.com/in/prakruti-hegde/]) or contribute to the project.

---

## 📃 License
This project is licensed under the MIT License.
