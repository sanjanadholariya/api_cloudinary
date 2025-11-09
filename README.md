# Cloudinary Media Upload API (Node.js + Express)

A backend API built with Node.js & Express, supporting **image upload using Cloudinary**, authentication, and CRUD operations via MongoDB.

---

## 🚀 Features

✅ Cloudinary image upload
✅ JWT-based authentication
✅ User management
✅ Media CRUD
✅ MongoDB + Mongoose models
✅ MVC architecture
✅ Multer middleware for file handling
✅ Environment-based config
✅ Postman collection included

---

## 🛠️ Tech Stack

| Layer    | Technology         |
| -------- | ------------------ |
| Backend  | Node.js, Express   |
| Database | MongoDB, Mongoose  |
| Auth     | JWT, bcrypt        |
| Upload   | Multer, Cloudinary |
| Tools    | Postman, Nodemon   |

---

## 📁 Folder Structure

```
project-folder/
 ├─ src/
 │   ├─ config/
 │   ├─ controller/
 │   ├─ middleware/
 │   ├─ model/
 |   ├─ routes/
 │   └─ app.js
 ├─ .env
 └─ package.json
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone repository

```bash
git clone https://github.com/sanjanadholariya/api_cloudinary
```

### 2️⃣ Navigate to project folder

```bash
cd api_cloudinary
```

### 3️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Configure environment variables (.env)

```
PORT=8001
CLOUD_NAME=dw29vpjgh
CLOUDINARY_KEY=829828161963285
CLOUDINARY_SECRET=hFX0Wxx9q_wP_LjZ3bM0XAHClaY
JWT_SECRET=testing
MONGO_URL=mongodb+srv://sanjana:sanjana123@cluster0.j5x75l5.mongodb.net/api-cloudinary
```

### 5️⃣ Start project

```bash
npm run dev
```

🔐 API Endpoints

Detailed endpoints available in Postman collection.

---

## 👩‍💻 Author

**Sanjana Dholariya**
GitHub: https://github.com/sanjanadholariya
