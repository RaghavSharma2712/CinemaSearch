# Movie Discovery App

A responsive movie discovery application built using React, Vite, and Tailwind CSS. The application integrates with The Movie Database (TMDB) API to fetch and display movie information, allowing users to browse trending titles and search for movies in real time.

## Features

* Browse popular movies from TMDB
* Real-time movie search
* Debounced search input for optimized API requests
* Responsive design for desktop and mobile devices
* Loading states using a custom spinner component
* Error handling for failed API requests
* Modern UI built with Tailwind CSS
* Fast development environment powered by Vite

## Tech Stack

* React
* Vite
* Tailwind CSS
* TMDB API
* React Hooks (useState, useEffect)
* react-use (useDebounce)

## Project Structure

```text
src/
├── components/
│   ├── Search.jsx
│   ├── MovieCard.jsx
│   └── Spinner.jsx
├── App.jsx
└── main.jsx
```

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd movie-discovery-app
```

3. Install dependencies

```bash
npm install
```

4. Create a `.env.local` file

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
```

5. Start the development server

```bash
npm run dev
```

## How It Works

* The application fetches popular movies from TMDB when the page loads.
* User search input is debounced to reduce unnecessary API calls.
* Search results are fetched dynamically from the TMDB search endpoint.
* Movie data is rendered using reusable React components.

## Future Improvements

* Trending movies analytics
* Favorites and watchlist functionality
* Genre-based filtering
* Pagination and infinite scrolling
* User authentication
* Backend integration for user-specific data

## License

This project is created for educational and portfolio purposes.









# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
