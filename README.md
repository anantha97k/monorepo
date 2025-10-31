# Resume Management Application (Full-Stack MVC)

This project is a **full-stack MVC web application** that enables users to **create, view, update, and manage resumes** through a complete CRUD interface.
The system is designed with scalability and maintainability in mind, featuring a React-based frontend and an Express backend with dual database support.

---

## Features

* **Full CRUD functionality** for managing user resumes.
* **Single Page Application (SPA)** built with ReactJS for a responsive and interactive user experience.
* **Authentication and Authorization** handled through React Context and PostgreSQL.
* **Separation of concerns** with MVC architecture for clear and maintainable code structure.
* **Dual-database design**: PostgreSQL for user authentication and MongoDB for resume data.
* **Deployed on Render** for production-ready hosting.

---

## Tech Stack

| Layer        | Technology                                               |
| ------------ | -------------------------------------------------------- |
| Frontend     | ReactJS, React Router, React Context                     |
| Backend      | Express.js                                               |
| Architecture | MVC (Model–View–Controller)                              |
| Databases    | PostgreSQL (Authentication), MongoDB Atlas (Resume Data) |
| Deployment   | Render                                                   |

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/resume-manager-mvc.git
cd resume-manager-mvc
```

### 2. Install Dependencies

```bash
npm install
cd client && npm install
```

### 3. Environment Variables

Create a `.env` file in the root directory with the following:

```env
PORT=5000
POSTGRES_URL="your_postgres_connection_url"
MONGODB_URI="your_mongodb_connection_url"
JWT_SECRET="your_secret_key"
```
---

## Deployment

The application is deployed on **Render**, with the following configuration:

* **Backend**: Node.js (Express) service
* **Frontend**: Static site deployment (React build)
* **Databases**: Render PostgreSQL and MongoDB Atlas

---

## Project Structure

```
├── client/                  # React frontend (SPA)
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── views/
│   └── app.js
├── package.json
└── README.md
```

---
