# Svinnstop

A simple React (Vite) app to track purchased food items, their expiry dates, and see quick recipe suggestions.

## Run locally (if you have Node 18+ and npm)
- npm install
- npm run dev

## On Replit (Free)
- Create a new Repl by importing this folder (or a GitHub repo containing it).
- Replit will auto-install dependencies when you click Run if configured.
- The dev server listens on port 3000.

## Features
- Add items with name, quantity, purchase date, and expiry date
- View items sorted by soonest expiry, with clear status (expired/expiring)
- Filter by all, expiring (≤3 days), or expired
- Recipe suggestions based on your items
- Data persistence via localStorage

## Notes
- This is a frontend-only app; no backend or accounts. Your data stays in your browser.
- Recipes are basic, illustrative examples. You can expand the dataset in src/recipes.js.
