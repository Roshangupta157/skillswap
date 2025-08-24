# SkillSwap Platform

## Overview

SkillSwap is a full-stack platform designed to help users exchange skills with each other.  
It consists of two main parts:

- **FrontEndSkillSwap**: The frontend application built with React.js
- **BackendSkillSwap**: The backend service built with Node.js, Express, and MongoDB

Together, they provide a seamless experience for user authentication, browsing skills, and managing skill swaps.

---

## Features

### Frontend

- User login and registration
- Browse and manage skills
- Request and accept skill swaps
- Responsive UI with React.js

### Backend

- User registration and authentication
- Skill management (add, update, delete skills)
- Swap requests between users
- Middleware for validation and authentication
- Organized routes and models for maintainability

---

## Tech Stack

### Frontend

- React.js
- JavaScript (ES6+)
- CSS / Tailwind (or other styling of your choice)
- Axios or Fetch for API calls

### Backend

- Node.js
- Express.js
- MongoDB / Mongoose
- JWT for authentication
- Other dependencies as per `package.json`

---

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- MongoDB instance (local or cloud)

---

# Project Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Roshangupta157/skillswap.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FrontEndSkillSwap
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   `bash
 npm start
 `
   The app will be running at `http://localhost:3000`.

#### Environment Variables

If your project uses environment variables (e.g., API URLs), create a `.env` file and add them:
REACT_APP_API_URL=http://localhost:3000

yaml
Copy
Edit

---

2. Navigate to the project directory:
   ```bash
   cd BackendSkillSwap/server
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the root directory and add your environment variables:

   ```
   PORT=your_port_number
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

5. Run the backend server:
   `bash
 npm start
 `
   The server should now be running on `http://localhost:<PORT>`.

---

## API Endpoints

(Add details about your API endpoints here)

---

## Contributing

Contributions are welcome! Please open issues and submit pull requests.

---

## License

MIT License

---

_Created by Roshan Gupta_
