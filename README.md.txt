🌍 World Capital Quiz

A simple interactive web-based quiz application that tests knowledge of world capitals.

This project was built for learning and practising backend development using PostgreSQL and understanding how data is fetched dynamically from a database.

🎯 Purpose of This Project

This project was created for:

Learning Node.js and Express

Practicing PostgreSQL database integration

Understanding how the backend fetches data from the database

Connecting frontend (EJS) with backend logic

Handling form submission and validation

This project was developed as part of learning from the Udemy course:

Angela Yu – Developer and Lead Instructor

Course:
“The Complete Full-Stack Web Development Bootcamp”

The course covers:

HTML

CSS

JavaScript

Node.js

React

PostgreSQL

Web3 and DApps

This quiz project was customized and implemented independently for better understanding and practice.

🛠️ Tech Stack

Node.js

Express.js

PostgreSQL

EJS

CSS

📂 Project Structure

World-Capital-Quiz/

│
├── node_modules/  

│
├── public/

│   ├── images/

│   │   └── background.jpg

│   │
│   └── styles/

│       └── main.css

│
├── views/

│   └── index.ejs

│
├── capitals.csv    

(optional if using)

├── index.js

├── package.json

├── package-lock.json

├── README.md

└── .gitignore🗄️ Database Setup (PostgreSQL)

Open PostgreSQL.

Create database:

CREATE DATABASE country;

Create table:

CREATE TABLE capitals (
  id SERIAL PRIMARY KEY,
  country VARCHAR(100),
  capital VARCHAR(100)
);

Insert sample data:

INSERT INTO capitals (country, capital) VALUES
('India', 'New Delhi'),
('France', 'Paris'),
('Germany', 'Berlin'),
('Japan', 'Tokyo'),
('Brazil', 'Brasilia');
📦 Install Dependencies

Open terminal inside project folder and run:

npm install

If starting fresh:

npm init -y
npm install express body-parser pg ejs
▶️ How To Run

Run:

node index.js

Or:

nodemon index.js

Then open:

http://localhost:3000
🎮 How It Works

Random country is displayed

User enters the capital

Correct answer increases score

Wrong answer ends the game

User can restart

💡 Future Improvements

Add multiple-choice options

Add leaderboard

Add timer

Add difficulty levels

Deploy online

👩‍💻 Author

Prarthana Bhandari
MCA Student
