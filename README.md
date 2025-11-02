# 🎓 Happenly – University Event Management System

**Happenly** is a web-based platform designed to simplify and digitalize **university event management**.  
It allows students, faculty, and organizers to **create, manage, and participate** in university events efficiently — all in one place!
Also, the AI feature enables us to search for the programs and know more about them!

🌐 **Live Demo:** (https://happenly-frontend.onrender.com/)

---

## 🚀 Features

- 🗓️ **Event Listing:** View all upcoming and ongoing events at your university.
- 📝 **Event Creation:** Organizers can add new events with details like date, time, and venue.
- 🎟️ **Registration System:** Students can easily register or unregister from events.
- 🧾 **Event Details Page:** Each event has its own detailed page with complete information.
- 👨‍🎓 **User Authentication:** Secure login and registration using Firebase Auth.
- 📅 **Personalized Dashboard:** Users can view and manage events they’ve created or joined.
- 📱 **Responsive UI:** Optimized for mobile, tablet, and desktop.
- 🌐 **Cloud Deployment:** Fully deployed and accessible from anywhere via Render.

---

## 🧰 Tech Stack

| Category             | Technologies Used                                   |
|----------------------|-----------------------------------------------------|
| **Frontend**         | React.js, Vite, Tailwind CSS                        |
| **Backend**    | Node.js, Express.js                                 |
| **Database**         | Firebase Firestore / MongoDB *(depending on setup)* |
| **Authentication**   | Firebase Authentication                             |
| **Deployment**       | Render (Frontend)                                   |
| **Version Control**  | Git & GitHub                                        |

---

## ⚙️ Installation & Setup

Follow these steps to run Happenly locally 👇

# 1️⃣ Clone this repository
git clone https://github.com/<your-username>/happenly.git

# 2️⃣ Move into the project folder
cd happenly

# 3️⃣ Install dependencies
npm install

# 4️⃣ Create a .env file in the root directory
# Add your Firebase credentials inside it

VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id

# 5️⃣ Run the app locally
npm run dev


## ⚙️ Folder setup
```bash
happenly/
├── client/                         # Frontend (React + Vite)
│   ├── public/                     # Static assets
│   ├── src/
│   │   ├── assets/                 # Images, icons
│   │   ├── components/             # Reusable UI components
│   │   ├── context/                # Auth and global state management
│   │   ├── pages/                  # Event listing, creation, dashboard, login pages
│   │   ├── App.jsx                 # Root component
│   │   └── main.jsx                # Entry point
│   ├── package.json
│   ├── vite.config.js
│   ├── tailwind.config.js
│   └── README.md
│
├── server/                         # Backend (Node.js + Express)
│   ├── src/
│   │   ├── routes/                 # API routes
│   │   ├── controllers/            # Business logic
│   │   ├── models/                 # Database schemas
│   │   └── server.js               # Entry point
│   ├── package.json
│   └── .env                        # Environment variables (ignored)
│
├── .gitignore                      # Git ignored files and folders
└──  README.md                       # Project documentation


```


## 🧑‍💻 Author

- 👩‍💻 Laghuvi Rawat
- 🎓 University Event Management Project – Frontend Deployed on Render
- ⭐ Don’t forget to star this repo if you like it!


## ☁️ Deployment

The project is deployed on Render for seamless accessibility.


