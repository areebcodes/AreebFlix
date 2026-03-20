# 🎬 AreebFlix

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)

A Netflix-inspired movie discovery app built with React and the TMDB API. Browse what's popular, search for any movie, and build your personal favorites list.

🌐 **Live Demo:** [areebflixvercel.vercel.app](https://areebflixvercel.vercel.app)

---

## ✨ Features

- 🎥 Browse trending and popular movies in real time
- 🔍 Search any movie by title
- ❤️ Add and remove movies from your favorites
- 💾 Favorites saved with local storage — persists on refresh
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React | Frontend framework |
| Vite | Build tool |
| React Router | Client-side routing |
| Context API | Global state management |
| TMDB API | Movie data |
| CSS | Styling |

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- A free TMDB API key from [themoviedb.org](https://www.themoviedb.org/)

### Installation

1. Clone the repo
```bash
git clone https://github.com/areebcodes/AreebFlix.git
cd AreebFlix
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory
VITE_API_KEY=your_tmdb_api_key_here

4. Start the development server
```bash
npm run dev
```

---

## 📁 Project Structure
src/
├── components/
│   ├── MovieCard.jsx
│   └── NavBar.jsx
├── contexts/
│   └── MovieContext.jsx
├── css/
├── pages/
│   ├── Home.jsx
│   └── Favorites.jsx
└── services/
└── api.js

---

## 👤 Author

**Areeb Khan**
- GitHub: [@areebcodes](https://github.com/areebcodes)
