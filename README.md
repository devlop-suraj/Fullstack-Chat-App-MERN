This Full Stack Chat Application is a real-time messaging platform built using the MERN stack (MongoDB, Express.js, React, Node.js). The application allows users to register, log in, and engage in real-time chat with other users. It features user authentication, message storage, and a responsive user interface styled with Tailwind CSS.

Key Features
User Authentication: Secure registration and login functionality with JWT (JSON Web Tokens) for session management.
Real-Time Messaging: Instant messaging capabilities using WebSocket for seamless communication.
User Profiles: Each user has a unique profile with a username and avatar.
Responsive Design: A modern and user-friendly interface built with Tailwind CSS, ensuring compatibility across devices.
Message History: Users can view their chat history, with messages stored in a MongoDB database.
File Uploads: Users can share files within the chat.
Technologies Used
Frontend:

React
Tailwind CSS
Axios for API calls
Backend:

Node.js
Express.js
MongoDB with Mongoose
WebSocket for real-time communication
Bcrypt for password hashing
JSON Web Tokens (JWT) for authentication
Installation
Clone the repository:

bash
Run
Copy code
git clone https://github.com/yourusername/Fullstack-Chat-App-MERN
cd chat-application
Navigate to the client directory and install dependencies:

bash
Run
Copy code
cd client
npm install
Navigate to the server directory and install dependencies:

bash
Run
Copy code
cd server
npm install
Set up environment variables:

Create a .env file in the server directory and add your MongoDB connection string and other necessary configurations.
Start the server:

bash
Run
Copy code
cd server
npm start
Start the client:

bash
Run
Copy code
cd client
npm start
Usage
Register a new account or log in with existing credentials.
Start chatting with other users in real-time.
Share files and view your chat history.
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
