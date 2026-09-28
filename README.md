# 🤖 AI BlogNest – API Backend

AI BlogNest is an **AI-augmented blog backend project** developed using **Node.js, Express.js, MongoDB, Mongoose, JavaScript, and AI API**. It provides REST APIs for **user registration, login, authentication, and blog management**. The APIs are tested using **Thunder Client**, including Register, Login, Get Blogs, and Create Blog requests. The project demonstrates backend development, database integration, API handling, and AI-powered functionality.

## 🛠️ Technologies

**Node.js • Express.js • MongoDB • Mongoose • JavaScript • AI API • Thunder Client**

## ✨ Features

* User Registration & Login
* Authentication
* Blog Management
* AI Integration
* REST APIs
* MongoDB Database
* Thunder Client API Testing

## 🧪 Thunder Client Requests

**Register:** `POST /api/auth/register`
**Login:** `POST /api/auth/login`
**Get Blogs:** `GET /api/blogs`
**Create Blog:** `POST /api/blogs`

## ⚙️ Setup

```bash
npm install
npm start
```

Configure the required MongoDB connection and AI API key in the `.env` file.
## 🧪 Thunder Client Request Examples

### 1. Register User

**POST** `/api/auth/register`

```json
{
  "name": "Test User",
  "email": "test@example.com",
  "password": "123456"
}
```

### 2. Login User

**POST** `/api/auth/login`

```json
{
  "email": "test@example.com",
  "password": "123456"
}
```

### 3. Get Blogs

**GET** `/api/blogs`

### 4. Create Blog

**POST** `/api/blogs`

```json
{
  "title": "My First Blog",
  "content": "This is my first blog post."
}
```

> These APIs were tested using **Thunder Client**.
