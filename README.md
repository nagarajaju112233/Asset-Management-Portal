# Asset-Management-Portal
📘 README - Asset Management Portal

📂 Project Overview

The Asset Management Portal is a web-based application designed to help organizations efficiently track, manage, and report their physical and digital assets. The system supports user authentication, asset assignment, and real-time asset status updates.


---

🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Node.js / Express.js (or Django if using Python)

Database: MySQL / MongoDB

Tools: VS Code, GitHub, Postman



---

🚀 Features

User authentication (Admin and User)

Add, update, delete assets

Assign assets to employees

Search and filter assets

Generate asset reports

Role-based access control

Dashboard for quick asset overview



---

📁 Project Structure

Asset-Management-Portal/
├── frontend/
├── backend/
├── database/
├── document/
├── README.md


---

⚙️ Installation Steps

1. Clone the repository:

git clone <repository-link>


2. Navigate to the project directory:

cd Asset-Management-Portal


3. Install backend dependencies:

npm install


4. Start the server:

node server.js


5. Open index.html in your browser.




---

🛠️ API Routes

POST /api/users/login – User login

GET /api/users – Get all users

POST /api/assets – Add new asset

GET /api/assets – Get all assets

PUT /api/assets/:id – Update asset

DELETE /api/assets/:id – Delete asset

POST /api/assets/assign – Assign asset to user



---
