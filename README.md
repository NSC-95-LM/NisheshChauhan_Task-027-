# NisheshChauhan_Task(27)

## Summary
This project is a basic Vite + React application that fetches photo data from the JSONPlaceholder API and displays it in a responsive gallery layout. The app is styled with Tailwind CSS and includes loading and error state handling.

## What it Does?
- Fetches photo records from `https://jsonplaceholder.typicode.com/photos`
- Displays a dark-themed gallery of images with their titles
- Shows a loading message while the data is being fetched
- Shows an error message if the request fails
- Uses a reusable custom hook for API fetching

## Project Structure
```bash
nsc-27-basic-vite/
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── input.css
│   └── components/
│       └── useFetch.jsx
├── public/
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── vite.config.js
└── node_modules/
```

## How to Run?
1. Open the project folder in your terminal.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the local URL shown in the terminal (usually `http://localhost:5173`).

Optional production commands:
```bash
npm run build
npm run preview
```

## Technologies Used
- React
- Vite
- Tailwind CSS
- JavaScript
- JSONPlaceholder API

## Author
Nishesh Chauhan