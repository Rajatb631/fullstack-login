# Fullstack Login App

This is a fullstack login application built with React (frontend) and Node.js (backend) using Prisma and PostgreSQL.

## 📁 Project Structure

```
login-app-updated/
├── backend/
└── frontend/
```

---

## 🚀 Getting Started

### 🖥️ Frontend Setup

Navigate to the `frontend` directory and run:

```bash
cd frontend
npm install
```

#### Required Packages (auto-installed):
- `react`
- `react-dom`
- `react-hook-form`
- `@hookform/resolvers`
- `zod`
- `axios`
- `react-scripts`

Start the app:

```bash
npm start
```

---

### ⚙️ Backend Setup

Navigate to the `backend` directory and run:

```bash
cd backend
npm install
npx prisma generate
```

#### Required Packages (install if not already added):
```bash
npm install express cors dotenv prisma @prisma/client bcrypt jsonwebtoken
```

Start the server:

```bash
node index.js
```

Make sure your `.env` is configured correctly with your PostgreSQL URL, like this:

```env
DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
JWT_SECRET="your-secret"
```

---

## 🌐 Default API Endpoint

- `POST /api/login` – Accepts `{ uid, password }`

---

## 🧪 Test Credentials

Use existing users from the database or create a signup route as needed.

---

## 📌 Notes

- Ensure PostgreSQL is running.
- Backend runs on `http://localhost:3000`
- Frontend runs on `http://localhost:3001` (or next available port)

---

Happy coding! 🎉
