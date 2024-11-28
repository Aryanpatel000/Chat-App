# Chat-App

### Features
Real-time communication*: Instant message delivery using WebSocket or Socket.IO.
User authentication*: Secure login and registration system.
Chat rooms*: Multiple rooms for topic-based discussions.
Private messaging*: Direct messages between users.
Typing indicators*: Real-time feedback when someone is typing.
Message history*: Persistent storage of chat history.
Responsive design*: Works on desktop and mobile devices.


 ### Tech Stack
Backend: Node.js with Socket.IO (or other WebSocket libraries)
Frontend: React/HTML/CSS for user interface
Database: MongoDB for storing messages and user data
Authentication: JWT (JSON Web Token) or OAuth for secure user authentication

### Prerequisites
Node.js (v14+)
MongoDB or your preferred database
npm or yarn package manager

## Installation

1. Clone the Repository:
   bash
   git https://github.com/Aryanpatel000/Chat-App.git
   cd real-time-chat-app
   

2. Install Dependencies:
   bash
   npm install
   
3. Configure Environment Variables:
   Create a .env file in the root directory with the following variables:
   env
   PORT=3000
   DB_URL=mongodb://localhost:27017/chatapp

   
4. *tart the Application*:
   Development Mode: npm run dev
   Production Mode: npm start
     
5. Access the Application:
   Open your browser and navigate to http://localhost:3000.

## API Endpoints

### User Authentication
POST /api/register: Register a new user.
POST /api/login: Authenticate an existing user.

### Chat Operations
GET /api/rooms: Fetch available chat rooms.
POST /api/messages: Send a message to a chat room or user.
GET /api/messages: Fetch chat history for a room or user.

### WebSocket Events
connect: Triggered when a user connects.
disconnect: Triggered when a user disconnects.
message: Broadcasts a new message to a room.
typing: Notifies other users that someone is typing.
## Contact
For questions or support, feel free to reach out:
Email: patel.aryanbhai246@gmail.com
GitHub: https://github.com/Aryanpatel00

## user signin or signup interface
![WhatsApp Image 2024-11-28 at 12 07 38_066fd759](https://github.com/user-attachments/assets/49daa5d0-e870-4ba9-b933-1c52b2d91d3d)
![WhatsApp Image 2024-11-28 at 12 07 42_f671c351](https://github.com/user-attachments/assets/53719642-b52a-4d76-8869-a24e0805231a)


## user dashboard interface
![WhatsApp Image 2024-11-28 at 09 33 51_7ab5ac16](https://github.com/user-attachments/assets/f2335d13-638a-40e5-af8a-137c6e20baf4)

 
