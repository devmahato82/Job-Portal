# 🚀 Job Portal Web Application (MERN Stack)

A full-featured **Job Portal Web Application** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This platform connects job seekers with recruiters, enabling seamless job posting, searching, and application management.

---

## 📌 Features

### 👨‍💼 For Job Seekers

* User registration & login 
* Create and update profile
* Browse and search jobs
* Apply to jobs
* Track application status

### 🏢 For Recruiters

* Recruiter registration & login
* Post, update, and delete jobs
* View applicants
* Manage job listings

### ⚙️ General Features

* Responsive UI (mobile-friendly)
* Secure authentication & authorization
* RESTful API integration
* Error handling and validation

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Axios
* Tailwind CSS 
### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose)

### Other Tools

* Git & GitHub

---



## ⚡ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/job-portal.git
cd job-portal
```

### 2️⃣ Setup Backend

```
cd backend
npm install
```

Create a `.env` file inside `server/`:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend:

```
npm run dev
```

---

### 3️⃣ Setup Frontend

```
cd frontend\job-portal
npm install
npm run dev
```

---

## 🔗 API Endpoints (Sample)

### Auth Routes

* POST `/api/auth/register`
* POST `/api/auth/login`

### Job Routes

* GET `/api/jobs`
* POST `/api/jobs`
* PUT `/api/jobs/:id`
* DELETE `/api/jobs/:id`

### Application Routes

* POST `/api/apply/:jobId`
* GET `/api/applications`

---



## 🚀 Future Improvements

* Email notifications
* Real-time chat system

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/feature-name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature/feature-name`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Dev Kumar Mahato**

---

⭐ If you like this project, don’t forget to star the repo!
