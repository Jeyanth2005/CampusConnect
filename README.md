# CampusConnect: A College Communication and Engagement Platform

## Project Vision

CampusConnect is a robust and scalable full-stack web application designed to be the central hub for all academic and administrative communication within a college environment. By consolidating disparate communication channels into a single, cohesive platform, it aims to enhance collaboration, streamline information flow, and foster a more connected campus community.

---

## Core Functionalities

This platform offers a comprehensive suite of features tailored to the needs of students, faculty, and administrators:

- **Role-Based Access Control (RBAC):** A secure authentication system leveraging JSON Web Tokens (JWT) to manage different access levels for users based on their roles.
- **Announcements & Circulars:** A centralized dashboard for official college updates, event notifications, and faculty announcements.
- **Discussion Forums:** Facilitates academic and social dialogue through topic-based forums with comment and upvote features.
- **Real-Time Messaging:** Instant, secure messaging between users using WebSockets.
- **Alumni & Career Services:** Connect with alumni for mentorship and access job/internship opportunities.
- **Assignments & Grading:** Faculty can create, assign, and grade assignments; students can submit their work online.
- **Attendance Tracking:** A simple interface for faculty to manage and record attendance.

---

## Technology Stack

### Backend
- **Node.js & Express.js** – RESTful API and server-side logic
- **MongoDB & Mongoose** – NoSQL database and ODM
- **Socket.io** – Real-time communication (messaging)

### Frontend
- **React.js** – Component-based frontend development
- **React Router** – Single Page Application (SPA) navigation
- **Context API / Redux** – State management

---

## Deployment

- **Vercel** – For simplified deployment of both frontend and backend

---

## Installation & Setup

### Prerequisites

Ensure the following are installed:

- Node.js (v14.x or newer)
- npm (comes with Node.js)
- MongoDB (locally or MongoDB Atlas)
- Git

---

### Steps to Run the Project

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/CampusConnect.git
cd CampusConnect
```

#### 2. Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file inside the `Backend` directory:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=a_very_secure_secret_key_for_authentication
```

Start the backend server:

```bash
npm start
```

API will be available at: `http://localhost:5000`

#### 3. Frontend Setup

```bash
cd ../Frontend
npm install
npm start
```

Frontend will be accessible at: `http://localhost:3000`

---

## License

This project is for educational purposes. Add a license if needed.
