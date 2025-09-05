# 🎬 MovieFlix

MovieFlix is a modern movie discovery web app built with **React.js**, powered by **TMDB API** for fetching movie data, and **Appwrite** for backend services.  
It allows users to explore movies, search through thousands of titles, and view trending movies that update dynamically with your searches.

---

## 🚀 Features

- 🔍 **Search Movies** – Find your favorite movies instantly.
- 🎥 **Trending Movies** – Displays trending movies that change based on searches.
- 📑 **Movie Listings** – Browse through thousands of movies with details.
- ⚡ **Fast & Modern UI** – Built with React.js and styled for a smooth experience.
- 🗄️ **Backend with Appwrite** – Secure backend integration.

---

## 📸 Screenshot

![MovieFlix Screenshot](./assets/screenshot.png)

---

## 🛠️ Tech Stack

- **Frontend:** [React.js](https://react.dev/)
- **Backend:** [Appwrite](https://appwrite.io/)
- **Movie Data API:** [TMDB API](https://developer.themoviedb.org/)

---

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/MovieFlix.git
   cd MovieFlix
   ```

2. Install Dependencies

   ```bash
   npm install
   ```

3. Setup Environment Variables
   Create .env file in the root directory and add the following:

   ```env
   # TMDB API
   VITE_TMDB_API_KEY=your_tmdb_api_key_here

   # Appwrite Credentials
   VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   VITE_APPWRITE_BUCKET_ID=your_appwrite_bucket_id

   ```

4. Run the development server
   ```bash
   npm run dev
   ```
5. Open http://localhost:5173 in your browser.
