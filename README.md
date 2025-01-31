#Chat App - MERN Stack
This is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The app allows users to send and receive messages in real-time, with support for media uploads, secure authentication, and theme customization options.

Features
Real-Time Messaging: Users can send and receive messages instantly with WebSocket (Socket.io) integration.
User Authentication: Users can sign up, log in, and manage sessions with JWT-based authentication.
Media Uploads: Support for image uploads with Cloudinary integration.
Responsive UI: Built with React.js and responsive design to support different screen sizes.
Theme Customization: Users can customize the app's theme with multiple options to personalize their chat experience.
Environment Configuration: Configurable environment settings for development and production environments.
Theme Customization
One of the best parts of this app is the ability for users to fully customize their chat experience. Users have several options for changing the app's theme, such as:

Dark and Light Modes: Switch between dark and light themes based on preference.
Color Themes: Choose from a variety of color schemes to make the chat experience more personalized.

Installation
Prerequisites
Node.js (v12 or higher)
MongoDB (running locally or using a cloud instance)
Cloudinary account for media uploads
Steps to Run the Application
Clone the repository:

bash
Copy
Edit
git clone <your-repository-url>
cd chat-app
Install the backend dependencies:

bash
Copy
Edit
cd backend
npm install
Install the frontend dependencies:

bash
Copy
Edit
cd frontend
npm install

Run the frontend:

bash
Copy
Edit
cd frontend
npm start
Visit http://localhost:3000 to access the chat app.

Technologies Used
MongoDB: NoSQL database for storing user data and messages.
Express.js: Web server framework for handling API requests.
React.js: Frontend framework for building the UI.
Node.js: JavaScript runtime for building the backend.
Socket.io: Real-time communication for sending and receiving messages.
JWT: Secure user authentication using JSON Web Tokens.
Cloudinary: Cloud service for managing media uploads.
