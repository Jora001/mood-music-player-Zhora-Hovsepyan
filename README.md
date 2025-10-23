# 🎵 Mood-Based Music Player

A web app that plays mood-based music playlists.
Select your mood — Happy, Sad, Calm, or Energetic — and instantly get a playlist that matches your vibe!

---

## 🚀 Features

* Choose your current mood
* Fetch songs dynamically via API (YouTube Data API v3)
* Beautiful and responsive UI built with React
* Backend powered by Node.js and Express
* Deployed on Vercel (frontend) and Render (backend)

---

## 🛠️ Tech Stack

**Frontend:** React + Vite + TailwindCSS
**Backend:** Node.js + Express
**API:** YouTube Data API
**Deployment:** Vercel / Render

---

## 🧱 Project Structure

```
mood-music-player-artavazd-hovsepyan/
│
├── client/       # React frontend
├── server/       # Node.js backend
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/mood-music-player-artavazd-hovsepyan.git
cd mood-music-player-artavazd-hovsepyan
```

### 2️⃣ Create frontend

```bash
cd client
npm create vite@latest .
npm install
npm install axios
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### 3️⃣ Create backend

```bash
cd ../server
npm init -y
npm install express axios cors dotenv
```

---

## 🌤️ Moods Supported

| Mood         | Description            |
| ------------ | ---------------------- |
| 😊 Happy     | Uplifting, pop & dance |
| 😔 Sad       | Acoustic, emotional    |
| 🧘 Calm      | Lo-fi, chill beats     |
| 💪 Energetic | Workout, rock          |

---

## 🧠 Future Improvements

* Add Spotify login
* Save user playlists
* Add dark/light mode

---

## 👤 Author

**Jora Hovsepyan**
