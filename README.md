# 🎬 Akky.ai — Movie Booking App

> A React.js web application for browsing movies, selecting seats, and booking tickets — with an AI chatbot assistant.

---

## ✨ Features

- 🎥 **Movie Listings** — Browse now-showing and coming soon movies
- 🎞️ **Movie Details** — View cast, synopsis, ratings
- 💺 **Seat Selection** — Interactive seat map for choosing seats
- 💳 **Payment** — Complete booking with payment flow
- 📍 **Nearby Cinemas** — Find cinemas near your location
- 📋 **Booking History** — View all past bookings
- 🤖 **AI Chatbot** — Built-in chatbot assistant for help
- 🧭 **Multi-page Navigation** — React Router for smooth page transitions

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| Frontend | React.js, JavaScript, CSS3 |
| Routing | React Router DOM |
| Build Tool | Create React App |
| Tools | Git, GitHub, VS Code |

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- Git installed

### Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/akky.ai.git

# 2. Go into the folder
cd akky.ai

# 3. Install dependencies
npm install

# 4. Start the app
npm start
```

Open `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```
src/
├── components/
│   └── Navbar.jsx          # Navigation bar
├── pages/
│   ├── Home.jsx            # Movie listings
│   ├── MovieDetails.jsx    # Movie info page
│   ├── SeatSelection.jsx   # Seat picker
│   ├── Payment.jsx         # Payment page
│   ├── ComingSoon.jsx      # Upcoming movies
│   ├── NearbyCinemas.jsx   # Find cinemas
│   ├── BookingHistory.jsx  # Past bookings
│   └── ChatBot.jsx         # AI chatbot
├── data/
│   └── movies.js           # Movie data
└── App.js                  # Routes + layout
```

---

## 📄 License

MIT License — free to use and modify.
