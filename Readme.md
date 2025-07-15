
# 📁 Dynamic Routing 

**the concept of **dynamic routing** using Express.js. It simulates a GitHub-style user directory, allowing you to fetch user data dynamically through route parameters.

---

## 🌐 Live Server

Run your server with:

```bash
npm install
node index.js
```

Make sure to have a `.env` file with:

```env
PORT=3000
```

---

## 🚀 Features

* 📦 Dynamic Routing using Express.js
* 🔍 Fetch user info using `/user/:login`
* 📜 JSON API endpoints for mock GitHub users
* 🧠 Uses `Array.find()` and route parameters to serve dynamic data
* 🔐 Environment variable support via `dotenv`

---

## 📌 API Endpoints

### ✅ Get All Users

```
GET /user
```

Returns all mock GitHub user data.

### 🔎 Get Single User by Login

```
GET /user/:login
```

Returns a single user JSON object if found. Example:

```
GET /user/mojombo
```

### 🐱 Other Routes

```
GET /pokimon      --> returns "snorlex"
GET /anime        --> returns "GOKU"
GET /api.github   --> returns full user data as JSON
GET /gone         --> returns "hello"
```

---

## 📁 Project Structure

```
Historictors/
├── .env
├── .gitignore
├── index.js        # Main server file with routes
├── package.json
├── package-lock.json
└── README.md
```

---

## 📚 Concepts Used

* Express.js server
* Dynamic routes (`/user/:login`)
* `Array.find()` for matching users
* Static and dynamic response handling
* Basic API endpoint design

---

## ✍️ Author

Made with ❤️ by \[Aadesh Jogi ] - for learning and demonstration.

---

## 📄 License

This project is licensed under the MIT License.
