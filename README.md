<h1 align="center" style="color:#2c3e50;">🎓 College Memes</h1>

<p align="center">
  <img src="./preview.png" alt="College Meme App Preview" width="700"/>
</p>

<p align="center">
  <b>A meme-sharing platform where students and admins from different colleges can connect and create content.</b><br>
  Post memes, manage users, form groups — all in one student-centric social media app.
</p>

---

## 📄 About the Project

This full-stack application is designed to help students express, interact, and engage through memes and short posts.

- 🧑 Admins can manage their college-specific users
- 🎭 Users can request to join and participate in group activities
- 📸 Post memes, videos, and comment/like your way into fun!

---

## 🌟 Features

- 🧑‍🎓 Admin & User Registration
- 🏫 College-based segregation & user approval
- 👥 Group creation (one per admin)
- 📝 Post creation with text + image/video
- ❤️ Like & 💬 Comment functionality
- ✅ Protected access: only approved users can see college posts

---

## 🛠️ Tech Stack

> This is a full-stack MERN application.

- ⚛️ Frontend: React + Vite
- 🎨 Styling: Tailwind CSS
- 🌐 Backend: Node.js + Express.js
- 🗃️ Database: MongoDB (Mongoose)
- 🔐 Auth: Cookie-based session (withCredentials)

---

## 🚀 Getting Started

🧾 Prerequisites:

- Node.js & npm installed
- MongoDB running locally or on Atlas

📦 Installation:

1️⃣ Clone the Repository

```bash
git clone https://github.com/rockyhans/college-meme-app
cd college-meme-app
2️⃣ Setup Environment Variables

Create a .env file in the /backend directory:

ini
Copy
Edit
PORT=5000
MONGO_DB_URI=mongodb://localhost:27017/college-meme
JWT_SECRET=yourSecretKey
3️⃣ Install Dependencies

Backend:

bash
Copy
Edit
cd backend
npm install
Frontend:

bash
Copy
Edit
cd frontend
npm install
▶️ Run the app:

Backend:

bash
Copy
Edit
npm run dev
Frontend (Vite):

bash
Copy
Edit
npm run dev
🌐 The app will be live at:

Frontend → http://localhost:5173

Backend → http://localhost:5000

📁 Project Structure
bash
Copy
Edit
college-meme-app/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── vite.config.js
📸 Features in Action
Admins can create groups for their colleges

Users can join only after approval by their respective college admin

Posts can contain memes (images/videos) and text

Only users from the same college can see their group’s posts

📅 Project Status
This project is in active development. Upcoming features include:

🔐 OAuth login

🗃️ User profile pages

🔔 Notifications & activity feed

👤 Contributor
<table> <tr> <td align="center"> <img src="https://avatars.githubusercontent.com/u/164065390?v=4" width="80px;" alt="Danish Rizwan"/> <br /><sub><b>Danish Rizwan</b></sub><br /> <sub>Full-Stack Developer</sub> </td> </tr> </table>
📬 Contact
📧 Email: rdanishrizwan@example.com

🌐 GitHub: https://github.com/rockyhans

💬 Team: College Meme Core

