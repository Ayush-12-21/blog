 Blog Platform

This is a basic blog platform built using Node.js, Express.js, and MongoDB. It allows users to register, log in, and create/view blog posts. It's a great project for learning the fundamentals of full-stack development with a focus on backend and MongoDB integration.

---

# Features

- User registration and login with cookies
- Create and view blog posts
- MongoDB integration for data storage
- EJS templating engine for frontend rendering
- Basic authentication middleware
- Clean project structure using Express routes


# Technologies Used

- Node.js
- Express.js
- MongoDB & Mongoose
- EJS (Embedded JavaScript Templates)
- dotenv for environment variables
- cookie-parser for authentication cookies

# Folder Structure

```
├── models/
│   └── blog.js
├── routes/
│   ├── user.js
│   └── blog.js
├── middlewares/
│   └── authentication.js
├── views/
│   └── (EJS templates)
├── public/
│   └── (static files)
├── .env
├── index.js
├── package.json
```

---

# Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/blog-platform.git
cd blog-platform
```

### 2. Install dependencies
```bash
npm install
```

### 3. Create a `.env` file
Create a `.env` file in the root of your project and add your MongoDB connection string:

```env
MONGO_URL=mongodb://localhost:27017/blogPlatform
PORT=8000
```

> Replace the MongoDB URL with your own connection string if using MongoDB Atlas.

#4. Run the project
bash
npm start


The server will start at:  
`http://localhost:8000`

---

## 👤 Author

- Ayush Kumar  
- B.Tech 2nd Year Student at IIIT Allahabad

---

## 📌 Note

- Make sure MongoDB is running locally or remotely before starting the server.
- The `.env` and `node_modules` files are ignored in version control via `.gitignore`.
