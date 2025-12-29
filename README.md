# 🎬 CineFinder

**CineFinder** — A React + Vite movie search app with live TMDB API integration.  

**Live Demo:** [Try CineFinder](https://frontend-yonatanverch-1188-yonatan-verchs-projects.vercel.app?_vercel_share=bGyuOwWVvPdF7dHriW4mAtIUt0zMi4g4)

---

## Overview

CineFinder is a modern web application for **searching and browsing movies** using the TMDB API.  
Users can explore popular movies, search by title, and save favorites. The app is fully responsive for desktop and mobile.

![CineFinder Demo](screenshots/CineFinder%20Demo%20Gif.gif)

---

## Features

- **Dynamic Movie Discovery:** Browse trending movies in real-time using TMDB API with asynchronous data fetching.  
- **Advanced Search:** Responsive search bar querying TMDB API with `async/await`, including error handling and loading states.  
- **Favorites Management:** Save and organize favorites using React Context API for scalable global state.  
- **Responsive UI:** Mobile- and desktop-optimized interface with clean, modular CSS.  
- **Robust Frontend Practices:** Conditional rendering, component reusability, and modular project architecture.

---

## Tech Stack

- **Frontend:** React, React Router, Vite  
- **State Management:** React Context API  
- **Styling:** CSS  
- **API:** TMDB (RESTful API)  
- **Deployment:** Vercel 

---

## Local Setup

1. Clone the repository:

```bash
git clone https://github.com/YonatanVerch/movie-search-app.git
cd movie-search-app

# Install dependencies
npm install

# Add your TMDB API key
echo "VITE_TMDB_API_KEY=your_api_key_here" > .env

# Start the development server
npm run dev
