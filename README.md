# Full-Stack Chat Application

This repository contains a fully functional full-stack chat application built with modern technologies. It enables real-time messaging, user authentication, and a responsive user interface.

## Features

- **Real-Time Messaging**: Chat with other users instantly using WebSocket technology.
- **User Authentication**: Secure user login and registration system.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.
- **Scalable Backend**: Built with Node.js and MongoDB for efficient and scalable performance.
- **Modern Frontend**: Built using React for a dynamic and interactive user experience.

## Live Demo

Visit the deployed application here: 
👉 [Full-Stack Chat Application](https://fullstack-chat-app-nmqe.onrender.com/)

## Technologies Used

### Frontend
- React
- Tailwind CSS (or CSS framework of your choice)
- Axios (for API requests)

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- Socket.IO (for real-time communication)

### Other Tools
- JSON Web Tokens (JWT) for authentication
- bcrypt.js for password hashing

## Prerequisites

Before running this application, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/try/download/community)
- A package manager like `npm` or `yarn`

## Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/RajYash0/fullstack-chat-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd fullstack-chat-app
   ```

3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

## Configuration

1. **Backend Configuration**:
   - Navigate to the `backend` folder and create a `.env` file.
   - Add the following environment variables:
     ```env
     PORT=5000
     MONGO_URI=mongodb://localhost:27017/chatapp
     JWT_SECRET=your_jwt_secret
     ```

2. **Frontend Configuration**:
   - Update the API base URL in the frontend (usually in an `axios` configuration file).

## Running the Application

1. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

2. Start the frontend development server:
   ```bash
   cd frontend
   npm start
   ```

3. Open your browser and go to `http://localhost:3000` to view the application.

## Folder Structure

```plaintext
fullstack-chat-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   └── package.json
└── README.md
```

## Deployment

To deploy the application:

1. Build the frontend for production:
   ```bash
   cd frontend
   npm run build
   ```

2. Serve the production build using a server (e.g., Nginx or Serve).

3. Host the backend on a platform like [Heroku](https://www.heroku.com/) or [AWS](https://aws.amazon.com/).

4. Update the API base URL in the frontend to point to the deployed backend.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy coding! 🎉
