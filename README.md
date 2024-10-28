# Simple Blog Application (SBA)

A Node.js and Express-based RESTful application that allows users to manage and interact with users, posts, and comments. This project demonstrates basic CRUD operations, filtering, and form handling in a web application.

## ✨Features

- **User Management:** Create, view, update, and delete users.
- **Post Management:** Create, view, update, and delete posts.
- **Comment Management:** Create, view, update, and delete comments on posts.
- **Basic Filtering:** Filter posts by user ID, title, and date range.
- **Static File Serving:** Serve static CSS files to style the application.
- **Form Handling:** HTML form to create a new post.

## Table of Contents

- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Project Structure](#project-structure)
- [License](#license)

## Getting Started

### Prerequisites

- **Node.js** (v14 or higher recommended)
- **npm** (Node Package Manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/simple-blog-app.git
   cd simple-blog-app

2. **Install dependencies:**

   ```bash
    npm install

3. **Start the server:**

   ```bash
   node index.js

## 🔗 API Endpoints

### Users
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/users` | Get all users |
| GET | `/api/users/:id` | Get a specific user |
| POST | `/api/users` | Create a new user |
| PUT | `/api/users/:id` | Update a user |
| DELETE | `/api/users/:id` | Delete a user |

### Posts
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/posts` | Get all posts |
| GET | `/api/posts/:id` | Get a specific post |
| POST | `/api/posts` | Create a new post |
| PUT | `/api/posts/:id` | Update a post |
| DELETE | `/api/posts/:id` | Delete a post |

### Comments
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/comments` | Get all comments |
| GET | `/api/comments/:id` | Get a specific comment |
| POST | `/api/comments` | Create a new comment |
| PUT | `/api/comments/:id` | Update a comment |


## 📁 Project Structure
.

    Copysimple-blog-app/
    │
    ├── assets/
    │   ├── styles.css       # Application styles
    │   └── index.js         # Client-side JavaScript
    │
    ├── routes/
    │   ├── users.js         # User routes
    │   ├── posts.js         # Post routes
    │   └── comments.js      # Comment routes
    │
    ├── views/
    │   └── index.ejs        # Main template
    │
    ├── index.js             # Application entry point
    ├── package.json
    └── README.md

## ⚙️ Development

Run in development mode:
```bash
# If you have nodemon
npm run dev
# Standard mode
node index.js
```

## 🤝 Contributing

1. **Fork** the repository
2. **Create your feature branch**  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**  
   ```bash  
   git commit -m 'Add some AmazingFeature'
4. **Push to the branch**  
   ```bash
    git push origin feature/AmazingFeature
5. Open a Pull Request


## 🌟 Acknowledgments

This project was built with the support of the following open-source technologies:

- [Express.js](https://expressjs.com/)
- [EJS](https://ejs.co/)
- [Node.js](https://nodejs.org/)



