# 📁 Digital Asset Management System (DAMS)

A scalable, secure, and user-friendly **Digital Asset Management System** (DAMS) built with **React + TypeScript** for the frontend and **Node.js + Express + MongoDB** for the backend. The system allows users to upload, categorize, store, and manage digital files (documents, images, videos) with a clean UI and role-based access control.

> 🎓 Developed as part of the **CDAC Final Project 2025**

> 🌐 **Live Demo Coming Soon**  
> 📦 **Local Setup Supported** (see instructions below)

---

## 📌 Core Features

- 🗃️ Upload and store various digital file types securely
- 🧑‍💼 Admin dashboard for asset tracking and management
- 🔍 Filter/search assets by category, type, or metadata
- 🔐 JWT-based user authentication and session handling
- 🧩 Modular architecture (frontend, backend, and separate landing page)
- 📁 Auto-folder organization of uploaded assets

---

## 🛠️ Tech Stack

| Frontend              | Backend                 | Styling        | Database     | Tooling & Config    |
|-----------------------|--------------------------|----------------|--------------|---------------------|
| React.js (Vite + TS)  | Node.js + Express.js     | Tailwind CSS   | MongoDB      | ESLint, PostCSS     |
| React Router          | RESTful API              | DaisyUI (opt)  | Mongoose     | Vite, .env configs  |

---

## 🗂️ Project Structure

Root/
│
├── CDAC_project/
│ ├── src/ # React admin dashboard
│ │ ├── components/
│ │ ├── context/
│ │ ├── pages/
│ │ └── ...
│ └── server/ # Node.js backend
│ ├── config/ # DB, JWT setup
│ ├── models/ # Mongoose schemas
│ ├── controllers/ # Business logic
│ ├── routes/ # API routes
│ ├── middleware/ # Auth, file validation
│ └── uploads/ # Uploaded asset storage
│
├── landing_page/ # Public-facing landing website
│ ├── src/
│ │ ├── App.tsx
│ │ └── components/
│ └── ...

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MohammedAzam-08/Digital-Asset-Management.git
cd Digital-Asset-Management/CDAC_project
2️⃣ Install Dependencies
bash
Copy
Edit
npm install
3️⃣ Start Development Servers
bash
Copy
Edit
npm run dev:full
💡 This command launches both the frontend (at http://localhost:5173) and backend server (at http://localhost:5000).

🔐 Environment Configuration
Create a .env file in CDAC_project/server/:

env
Copy
Edit
PORT=5000
MONGO_URI=mongodb+srv://<your_mongo_uri>
JWT_SECRET=your_jwt_secret
UPLOAD_FOLDER=uploads/
🧪 Testing Guidelines
Test user authentication flows (signup, login, logout)

Upload various file types (PDF, DOCX, PNG, MP4)

Simulate unauthorized access and error handling

Validate asset retrieval, download, and deletion logic

Use Postman for backend API testing (if needed)

📸 Screenshots (Coming Soon)
Login Page	Asset Upload	Admin Dashboard

📈 Possible Enhancements
 Add support for previewing videos/images in-browser

 Add download links for each asset

 File version control and rollback

 Integration with cloud storage (AWS S3 / GDrive)

 Audit logs for tracking asset changes

🧑‍💻 Contributors
Mohammed Azam — Full Stack Developer
🔗 Portfolio | LinkedIn

Ahmed Pasha — Co-Developer
🔗 GitHub

⭐ Feedback & Acknowledgments
If you find this project helpful or inspiring, please consider:

🌟 Starring the repo

🐞 Reporting issues

🚀 Forking and contributing

“Securely managing digital content with performance and scalability in mind.”
