Book Library Web App

A modern, responsive Book Library web application built with React + Vite + TailwindCSS.
Users can search for books (via Google Books API), sign up/login, add books to their favorites list, rate them ⭐, and manage their library — all with a clean dashboard experience.

✨ Features

🔍 Search books by title or author (Google Books API)

🖼️ View cover images + descriptions

🔑 Signup/Login with mock authentication (saved in localStorage)

❤️ Favorites dashboard for each user

⭐ Rate books from 1–5 stars

🗑️ Remove books individually or clear all favorites (with confirmation)

🔔 Toast notifications for all actions (login/logout, add/remove, errors)

📱 Fully responsive (desktop, tablet, mobile)

🔢 Favorites count badge in Navbar

🛠️ Data persistence with localStorage (favorites + user accounts survive refresh)

🖼️ Screens

Home Page → search books, view covers & descriptions, open details modal

Book Modal → see full details + add to favorites with rating

Dashboard → see your favorites, edit ratings, remove books, or clear all

Auth Pages → sign up, login, and logout with feedback

🚀 Tech Stack

⚛️ React (Vite) – frontend framework

🎨 TailwindCSS – styling

🔔 react-hot-toast – notifications

🔑 localStorage – simple persistence

📚 Google Books API – book search & data
Usage

Search for any book by title/author.

Click on a book → open details modal → rate it and add to favorites.

Dashboard:

Adjust star rating

Remove single book (with confirmation)

Clear all favorites (with confirmation)

Login/logout/signup with email + password (saved in localStorage).

📌 Notes

This project uses mock authentication → no backend, only localStorage.

All favorites & ratings are user-specific (based on logged-in account).

If you want real accounts, you could extend this with Firebase/Auth0/etc.

💡 Future Improvements

🔐 Real authentication (JWT or Firebase)

📦 Backend (Node/Express + MongoDB) to sync user data

📝 Add “Want to Read” vs “Finished Reading” sections

🌙 Dark mode toggle

🏆 Credits

Built as a Capstone Project for ALX

📚 Data from Google Books API

🎨 Styled with TailwindCSS
