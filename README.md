 Movie Rating System (MERN Stack)

This is a full-stack Movie Rating System built using the MERN stack (MongoDB, Express, React, Node.js). Users can rate, review, and browse movies.



 Tech Stack

- MongoDB – Database
- Express.js – Backend framework
- React.js – Frontend library
- Node.js – Server runtime

---
 Project Structure


├── backend/ # Express server + MongoDB
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── server.js
│ └── .env # Not included in repo
├── public/ # React public assets
├── src/ # React app
│ ├── AdminComponents/
│ ├── UserComponents/
│ ├── Components/
│ ├── styles/
│ ├── utils/
│ └── App.js, index.js, ...
├── .gitignore
├── README.md

To start
cd backend
npm install
npm start
For the frontend
npm install
npm start

Features
🔐 User authentication and authorization

🎥 Movie listings with admin control

⭐ Users can rate and review movies

👥 Separate components for admin and user interfaces

🧼 Clean folder structure for scalability
