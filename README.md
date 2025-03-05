# Talk-A-Tive

Talk-a-tive is a Full Stack Chatting App.
Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.

## Tech Stack

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB

## Demo

[https://talk-a-tive.herokuapp.com/](https://talk-a-tive-7fgq.onrender.com)

![](https://github.com/piyush-eon/mern-chat-app/blob/master/screenshots/group%20%2B%20notif.PNG)

## Run Locally

Clone the project

```bash
  git clone https://github.com/piyush-eon/mern-chat-app
```

Go to the project directory

```bash
  cd mern-chat-app
```

Install dependencies

```bash
  npm install
```

```bash
  cd frontend/
  npm install
```

Start the server

```bash
  npm run start
```

Start the Client

```bash
  //open now terminal
  cd frontend
  npm start
```

# Features


1️⃣ Project Overview
Brief introduction to the chat application.
Supports one-on-one chat & group chat.
Real-time messaging using Socket.IO.
User authentication with JWT (JSON Web Token).
Notifications for new messages and group activities.
Chatbot integration for automated responses.


2️⃣ Features


✅ User Authentication:

Login & Signup using JWT.
Secure password hashing with Bcrypt.
Role-based access control (Admin, User).


✅ One-on-One Chat:

Real-time private messaging.
Typing indicators and message read status.


✅ Group Chat:

Create and join chat groups.
Add or remove members.
Group message notifications.


✅ Notifications:

Live notifications when a new message arrives.
Browser notifications for new messages.


✅ Chatbot Integration (Basic Features):

Automated responses to user queries.
Supports simple AI-based replies.
Example: Weather bot, FAQ bot, etc.

✅ Database & Backend:

Uses MongoDB for storing messages and users.
Express.js API for chat functionality.

✅ WebSockets (Socket.IO) for Real-Time Chat:

#API END-POINTS


4️⃣ API Endpoints
📌 User Authentication

Method	Endpoint	Description

POST	/api/users/register	Register a new user
POST	/api/users/login	Login user & get JWT
📌 Chat Messages

Method	Endpoint	Description

GET	/api/messages/:userId	Get messages from a user
POST	/api/messages/send	Send a message
📌 Group Chats

Method	Endpoint	Description

POST	/api/groups/create	Create a new group
POST	/api/groups/add-user	Add user to a group

## Made By

VENKATESH R K
