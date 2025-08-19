# 🎬 usePopcorn

A movie search and watchlist web app built with **React + Vite**.  
Search movies from the **OMDb API**, view details, and manage your personal watched list.

---

## 🚀 Features
- 🔍 Search movies in real time from OMDb API
- 📃 View search results with posters, titles, and release years
- 🎞 View movie details (ratings, runtime, etc.)
- ⭐️ Rate movies and add them to your **Watched list**
- 🗑 Remove movies from your Watched list
- 📊 Get a quick summary (average rating, runtime, etc.)
- ⚡️ Fast dev experience powered by **Vite**

---

## 🛠️ Tech Stack
- [React 18](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [OMDb API](https://www.omdbapi.com/) for movie data
- CSS (custom styles)

---

## 📂 Project Structure
src/
├── App.jsx # Main app component
├── starRating.jsx # Star rating component
├── index.css # Global styles
└── main.jsx # Entry point


---

## ⚙️ Setup & Installation

### 1. Clone the repo
```bash
git clone https://github.com/otunba32/usepopcorn.git
cd usepopcorn

2. Install dependencies
npm install

3. Set up environment variables

Create a .env file in the root folder and add your OMDb API key:

VITE_API_KEY=your_api_key_here

🔑 You can get a free API key from OMDb API.

4. Run the app
npm run dev

This will start the app at http://localhost:5173.

📦 Build for production
npm run build


Preview production build:

npm run preview

📝 License

This project is licensed under the MIT License.


🙌 Acknowledgements

Jonas Schmedtmann’s Ultimate React Course (inspiration for app structure)

OMDb API for movie data
