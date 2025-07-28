# 🔐 Auth-Tutorial

This is a full-stack authentication system built. It demonstrates a secure and modular approach to building authentication features including user registration, login, JWT-based session handling, and email verification (via Mailtrap).

---

## 🚀 Features

- 🔑 User Authentication (Login/Signup)
- 🔐 Password Hashing using `bcryptjs`
- 🛡️ JWT-based Token Authentication
- ✉️ Email verification with `Mailtrap`
- 🌍 CORS enabled backend
- 📦 MongoDB for data persistence
- ⚙️ Environment variable management using `dotenv`
- 🧪 Nodemon for development
- 🧩 Modular folder structure

---

## 🧰 Tech Stack

### Backend
- **Node.js**
- **Express.js**
- **MongoDB** + `mongoose`
- **bcryptjs**
- **jsonwebtoken**
- **cookie-parser**
- **dotenv**
- **cors**
- **mailtrap**
- **crypto**
- **nodemon** (development)

### Frontend
- React (not shown here but assumed from the build script)

---

## 📁 Project Structure

```

auth-tutorial/
├── backend/
│   └── index.js (entry point)
├── frontend/
│   └── \[React app files]
├── package.json

````

---

## 🛠️ Installation & Setup

### 🔧 Backend

1. Clone the repo:

   ```bash
   git clone https://github.com/ayan-x1/Auth-Tutorial.git
   cd Auth-Tutorial
   ```

2. Install backend dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file inside the root directory:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   MAILTRAP_USER=your_mailtrap_username
   MAILTRAP_PASS=your_mailtrap_password
   ```

4. Run the backend server in development:

   ```bash
   npm run dev
   ```

5. Or to run in production mode:

   ```bash
   npm start
   ```

### 🖥️ Frontend

Inside the `frontend/` folder:

```bash
cd frontend
npm install
npm start
```

---

## 📦 Scripts

```bash
# Install all dependencies (backend & frontend)
npm run build

# Start backend in production mode
npm start

# Start backend with hot reload (nodemon)
npm run dev
```

---

## 📬 API Endpoints (Examples)

| Method | Endpoint      | Description        |
| ------ | ------------- | ------------------ |
| POST   | /api/register | Register new user  |
| POST   | /api/login    | Authenticate user  |
| POST   | /api/verify   | Email verification |

*(Update with actual routes when available)*

---

## 📧 Email Integration (Mailtrap)

This project uses **Mailtrap** to simulate email sending in development mode. Make sure you set your Mailtrap credentials in `.env`.

---

## 📜 License

This project is licensed under the [ISC License](https://opensource.org/licenses/ISC).

---

## 👤 Author

Developed by [Ayan Ali](https://github.com/ayan-x1)
