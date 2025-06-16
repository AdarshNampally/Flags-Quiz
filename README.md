# 🌍 Flag Quiz Game

A fun and educational web app where users guess the **name** of a country based on its **flag**, built using **Node.js**, **Express.js**, **PostgreSQL**, and **EJS** templating. 
This project was created as part of a Full Stack Web Development learning journey to demonstrate the integration of backend databases with dynamic frontend rendering.

---

## 🚀 Features

- Displays a country's flag and prompts users to enter the capital city.
- Validates user input and gives instant feedback (✔ or ✖).
- Keeps track of the total correct answers (score).
- Ends the game on a wrong answer and shows the final score.
- Dynamically loads a new question after each correct response.
- Fetches all questions from a PostgreSQL database.

---

## 🛠️ Technologies Used

- **Node.js** + **Express.js** – Backend server
- **EJS** – Templating engine for rendering dynamic HTML
- **PostgreSQL** – Relational database to store flag-country-capital data
- **body-parser** – Middleware to parse form data
- **CSS** – Basic styling

---

## 🗂️ Project Structure

flag-quiz-game/
├── public/
│ └── styles/
│ └── main.css # Custom styling
├── views/
│ └── index.ejs # Main game page
├── index.js # Main server logic
├── README.md # This file
└── world.sql # (Optional) SQL file to create and populate the database


🔧 Setup Instructions
1. Clone the repository:

git clone https://github.com/your-username/flag-quiz-game.git
cd flag-quiz-game

2. Install dependencies:

Configure PostgreSQL connection:

3. Edit the index.js file if needed:

const db = new pg.Client({
  user: "postgres",
  host: "localhost",
  database: "world",
  password: "your_password_here",
  port: 5432, // or 5433 based on your config
});


4. Start the server:
node index.js

5. Open the app in your browser:
Edit
http://localhost:3000
