# Zerodha Clone

A full-stack trading platform inspired by Zerodha, built using React, Node.js, Express.js, and MongoDB. This project recreates key trading dashboard features, including authentication, portfolio tracking, and interactive UI components.

## Features

- **User Authentication:** Signup and login with JWT-based authentication and secure cookie handling.
- **Dashboard & Portfolio:** View holdings, positions, and portfolio information.
- **Interactive UI:** Clean, responsive dashboard with reusable components.
- **RESTful API:** Backend endpoints for user management and trading-related operations.
- **Charts & Visualizations:** Interactive chart components for displaying market-related data.

## Tech Stack

- **Frontend:** React, JavaScript, HTML5, CSS3, Material UI,Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT and HTTP cookies
- **Charts:** Chart.js

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yugank45/Zerodha-Clone.git
cd Zerodha-Clone
```

### 2. Install Dependencies

Install the dependencies separately in the frontend and backend directories, depending on your project structure.

```bash
cd backend
npm install

cd ../frontend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the backend directory and add the environment variables required by your application.

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Use the actual variable names expected by your code. Never commit real credentials or secrets to GitHub.

### 4. Run the Application

Start the backend:

```bash
cd backend
npm start
```

Start the frontend in a separate terminal:

```bash
cd frontend
npm start
```

Check the `package.json` files for the correct scripts if your project uses `npm run dev` or another command.

## Project Structure

```text
Zerodha-Clone/
├── frontend/
│   ├── src/
│   └── package.json
├── backend/
│   ├── models/
│   ├── routes/
│   ├── package.json
│   └── server.js
└── README.md
```

*The structure above is illustrative; adjust it to match your actual repository.*

## Disclaimer

This project is built for educational and demonstration purposes. It is not affiliated with or endorsed by Zerodha and does not provide real brokerage or trading services.

## Author

**Yugank Singh**

- GitHub: [@yugank45](https://github.com/yugank45)
- Project Repository: [Zerodha Clone](https://github.com/yugank45/Zerodha-Clone)
