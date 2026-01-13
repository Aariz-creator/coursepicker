# Top Courses App 📚

A modern React-based course listing application that fetches and displays top courses from an external API. Users can filter courses by category and like/unlike courses with real-time feedback.

Built using React, Tailwind CSS, and React Toastify, this app demonstrates component-based architecture, API integration, and state management.

## 🚀 Features

🔍 Filter courses by category (All, Development, Business, Design, Lifestyle)

❤️ Like & unlike courses with visual feedback

🔔 Toast notifications for user actions

🌐 Fetches real-time data from an external API

⏳ Loading spinner while fetching data

🎨 Clean, responsive UI using Tailwind CSS

⚛️ Fully component-based React architecture

## 🛠 Tech Stack

React

Tailwind CSS

React Icons

React Toastify

JavaScript (ES6+)

External REST API

## 📁 Project Structure
src/
├── components/
│   ├── Card.js        # Single course card
│   ├── Cards.js       # Course list rendering
│   ├── Filter.js      # Category filter buttons
│   ├── Navbar.js      # App header
│   ├── Spinner.js     # Loading indicator
│   └── Spinner.css
├── data.js            # API URL & filter categories
├── App.js             # Main application logic
├── index.js           # React DOM entry point
├── index.css          # Tailwind + global styles
└── README.md

## 🔗 API Used
https://codehelp-apis.vercel.app/api/get-top-courses


The API returns categorized course data, which is dynamically rendered in the UI.

## ▶️ How to Run Locally

Clone the repository

git clone https://github.com/your-username/top-courses-app.git


Navigate to the project

cd top-courses-app


## Install dependencies

npm install


Start the development server

npm start


Open in browser:

http://localhost:3000

## 🧠 Key Concepts Used

React Hooks (useState, useEffect)

Conditional rendering

State lifting & prop drilling

API fetching with fetch

Toast notifications

Responsive UI with Tailwind

Component reusability

## ✨ UI Highlights

Dynamic category filter buttons

Interactive like/unlike heart icons

Smooth hover and transition effects

Loading spinner animation

Clean dark-themed layout

## 🔧 Possible Enhancements

Add search functionality

Persist liked courses using localStorage

Add pagination or infinite scroll

Add user authentication

Convert to TypeScript

Deploy on Vercel / Netlify

📄 License

This project is open-source and intended for learning and portfolio use.

🙌 Acknowledgements

Course API by CodeHelp

Icons by React Icons

Notifications by React Toastify
