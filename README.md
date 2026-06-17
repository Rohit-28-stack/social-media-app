# Social Media App

A social media web application built using Node.js, Express.js, MongoDB, and EJS. Users can register, log in securely, create posts, edit their posts, and like/unlike posts. Authentication is implemented using JWT and cookies.

## Features

* User Registration
* User Login & Logout
* Password Hashing using bcrypt
* JWT Authentication
* Create Posts
* Edit Posts
* Like / Unlike Posts
* User Profile Page
* MongoDB Database Integration
* Responsive UI with EJS Templates

## Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)
* bcrypt
* cookie-parser

### Frontend

* EJS
* HTML
* CSS

## Project Structure

```text
project/
│
├── models/
│   ├── user.js
│   └── post.js
│
├── views/
│   ├── index.ejs
│   ├── login.ejs
│   ├── profile.ejs
│   └── edit.ejs
│
├── public/
├── app.js
├── package.json
├── .env
└── README.md
```

## Screenshots

### Login Page

<img width="1920" height="1020" alt="Screenshot 2026-06-17 164634" src="https://github.com/user-attachments/assets/c8f7299b-03a5-4535-ba5a-3feda4e31fc3" />

### Profile Page

<img width="1920" height="1020" alt="Screenshot 2026-06-17 165035" src="https://github.com/user-attachments/assets/2a9d9246-b411-41c6-813f-585b9b15fc0c" />

### Create Post

<img width="1920" height="1020" alt="Screenshot 2026-06-17 165035" src="https://github.com/user-attachments/assets/f4286d13-1618-49b7-9c1a-21d551e29ac1" />


### Like / Unlike Feature

<img width="1920" height="1020" alt="Screenshot 2026-06-17 165035" src="https://github.com/user-attachments/assets/1cd44997-cbce-40c7-9520-7b6743e66716" />


## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project folder

```bash
cd social-media-app
```

3. Install dependencies

```bash
npm install
```

4. Create a .env file

```env
JWT_SECRET=your_secret_key
```

5. Start the application

```bash
node app.js
```

or

```bash
nodemon app.js
```

## Future Improvements

* Delete Posts
* Comment System
* User Profile Picture Upload
* Follow / Unfollow Users
* Real-time Notifications
* Responsive Mobile Design

## Author

Rohit Surve

B.E. Computer Engineering | MERN Stack Developer | Java & DSA Enthusiast
