# GREEN_CAMPUS_DECISION_ANALYST
A web-based analytics dashboard that tracks date- and building-wise resource use, including electricity, water, waste, and environmental data. Interactive visuals give administrators clear insights to manage resources efficiently and support smarter campus sustainability decisions.

Project Overview

Green Campus Decision Analytics enables users to:

Record daily electricity, water, waste, and environmental data

Filter data using date and building selection

Visualize sustainability metrics through graphs and charts

Generate daily decisions and monthly improvement insights

The system supports smart campus decision-making for improved environmental performance.

🛠 Tech Stack
Frontend

React.js

JavaScript

Chart.js

Bootstrap

Backend

Node.js

Express.js

Database

MongoDB

Security

JWT Authentication

bcrypt Password Hashing

📂 Project Structure
green-campus-decision-analytics/
│
├── client/          # React frontend
├── server/          # Node + Express backend
├── .gitignore
├── README.md
└── package.json
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/green-campus-decision-analytics.git
cd green-campus-decision-analytics
2️⃣ Setup Backend
cd server
npm install
npm start
3️⃣ Setup Frontend
cd client
npm install
npm start
🔐 Environment Variables

Create a .env file inside the server folder:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
🚫 .gitignore Setup

Ensure the following are ignored:

node_modules/
.env
dist/
build/
coverage/
🌱 System Workflow

User opens welcome page and logs in

Enters daily sustainability data (electricity, water, waste, environment)

Dashboard displays filtered analytics by date and building

Suggestion page shows daily decision and monthly improvement insights

🌿 Branching Strategy

main → Stable production-ready code

develop → Active development integration

feature/* → New features (e.g., feature/dashboard-ui)

bugfix/* → Issue fixes

Workflow:

Create branch from develop

Complete feature or fix

Open pull request to develop

Merge to main after testing

🎯 Project Goal

To provide a data-driven sustainability decision system that helps institutions
monitor resources, visualize trends, and achieve environmental improvement goals.
