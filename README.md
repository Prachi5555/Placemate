# PlaceMate 🚀

A modern **Job Portal** web application that connects companies with job seekers. Companies can register, post jobs, and manage applicants, while users can browse jobs and apply with their resumes. Built with a **React + Vite frontend** and a **Node.js + Express + MongoDB backend**, with authentication handled through **Clerk** and media uploads via **Cloudinary**.

---

## ✨ Features

### For Job Seekers
- Browse and search job listings  
- View job details  
- Apply for jobs  
- Manage applications  
- Upload and update resume  

### For Companies
- Register and login  
- Post new jobs  
- Manage posted jobs  
- View applicants  
- Update job visibility and application status  

### Platform Features
- Authentication with Clerk  
- Cloudinary for file uploads (logos, resumes)  
- Sentry integration for error monitoring  
- RESTful API architecture  

---

## 🛠 Tech Stack

**Frontend**
- React (Vite)
- Tailwind CSS
- React Router
- Axios
- Clerk Authentication

**Backend**
- Node.js
- Express
- MongoDB + Mongoose
- Cloudinary
- Multer
- JWT / Clerk Webhooks
- Sentry

---

## 📂 Project Structure

```
PlaceMate/
│
├── client/        # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/        # Node/Express backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
```

---

## ⚙️ Installation & Setup

### 1) Clone the repository
```bash
git clone https://github.com/Ayush-Goel20/PlaceMate.git
cd PlaceMate
```

### 2) Install dependencies

**Frontend**
```bash
cd client
npm install
```

**Backend**
```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the **server** folder:

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret
CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret
```

> You may also need Clerk frontend keys in the client depending on deployment.

---

## ▶️ Run the Project

### Backend
```bash
cd server
npm run server
```

### Frontend
```bash
cd client
npm run dev
```

---

## 📡 API Endpoints (Sample)

### Company
- `POST /api/company/register`
- `POST /api/company/login`
- `GET /api/company/company`
- `POST /api/company/post-job`
- `GET /api/company/applicants`

### Jobs
- `GET /api/jobs`
- `GET /api/jobs/:id`

### User
- `GET /api/users/user`
- `POST /api/users/apply`
- `GET /api/users/applications`
- `POST /api/users/update-resume`

---

## 🌍 Deployment

- Frontend ready for **Vercel**  
- Backend can be deployed on **Render / Vercel / Railway**  

---

## 📸 Screenshots

_Add screenshots here once available._

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use and modify it.

---

## 👤 Author

**Ayush Goel**  
GitHub: [@Ayush-Goel20](https://github.com/Ayush-Goel20)

---

⭐ If you like this project, don’t forget to give it a star!
