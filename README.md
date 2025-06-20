# 🎬 Movie UI App

A sleek and responsive movie search app built with **React**, **Tailwind CSS**, and **TMDb API**. Instantly search for popular movies, see trending titles, and get quick info — all in a smooth, user-friendly interface.

![Hero Banner](./hero.png)

## 🚀 Features

- 🔍 Search for movies using TMDb API
- 🕒 Debounced search for performance
- 🎨 Stylish UI with Tailwind CSS
- 🌐 Responsive design for all screen sizes
- 🎞️ Dynamic results with movie cards
- 🌀 Loading spinners for async feedback

## 📦 Tech Stack

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TMDb API](https://www.themoviedb.org/documentation/api)
- [Vite](https://vitejs.dev/)
- [React Hooks](https://reactjs.org/docs/hooks-intro.html)

## 🛠 Setup & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-ui.git
cd movie-ui
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variable

Create a `.env` file in the root directory and add your TMDb API token:

```
VITE_TMDB_API_KEY=your_tmdb_bearer_token_here
```

> 💡 Make sure it's a **Bearer Token** from TMDb (not the plain API key).

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Build for Production

```bash
npm run build
```

### 6. Preview the Production Build

```bash
npm run preview
```

## 📁 Folder Structure

```
movie-ui/
├── public/
│   └── hero.png
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   └── Spinner.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env
├── index.html
├── tailwind.config.js
└── vite.config.js
```

## 🔑 API Reference

This app uses [The Movie Database (TMDb)](https://www.themoviedb.org/) for all movie data.

- Base URL: `https://api.themoviedb.org/3`
- Endpoints used:
  - `/search/movie`
  - `/discover/movie?sort_by=popularity.desc`


## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 💡 Acknowledgements

- [TMDb](https://www.themoviedb.org/) for movie data
- [Tailwind CSS](https://tailwindcss.com/)
- [React](https://reactjs.org/)

---

Feel free to contribute or raise an issue! Happy coding 💻
