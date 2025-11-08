# 🛍️ MERN E-Commerce Project

A full-stack **E-Commerce web application** built using the **MERN stack** (MongoDB, Express.js, React, Node.js).  
This project demonstrates modern web development best practices, including API-driven architecture, responsive UI, authentication, image management, and state handling.

---

## 🚀 Tech Stack

### 🖥️ Frontend

- **React 18** + **Vite**
- **Redux Toolkit** for state management
- **React Query** for data fetching & caching
- **Material Tailwind** + **Bootstrap** for styling
- **Formik** + **Yup** for form handling and validation
- **React Router v6** for routing
- **React Toastify** & **React Spinners** for user feedback
- **Axios** for API requests
- **React Quill**, **React Modal**, **React Tooltip** for UI components
- **Persian Date** for date handling (supports Farsi calendar)

### ⚙️ Backend

- **Node.js** + **Express.js**
- **MongoDB** + **Mongoose ORM**
- **JWT Authentication** with **bcrypt** password hashing
- **Cloudinary** for image upload & hosting
- **Multer** + **Sharp** for local file upload and image optimization
- **Dotenv** for environment configuration
- **Cors**, **Cookie-Parser**, **Body-Parser** for middleware
- **Nodemailer** for email handling (e.g. password reset, order confirmation)
- **Morgan** for API logging

---

## 📁 Project Structure

```text
root/
├── backend/
│   ├── index.js
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middlewares/
│   ├── utils/
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── hooks/
│   │   ├── api/
│   │   └── main.jsx
│   └── package.json
│
└── README.md
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2️⃣ Backend setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```

Then start the server:

```bash
# for development
npm run server

# or for production
npm start
```

### 3️⃣ Frontend setup

```bash
cd ../frontend
npm install
npm run dev
```

Frontend will run on **<http://localhost:5173>** by default.  
Backend runs on **<http://localhost:5000>** (configurable in `.env`).

---

## 🔐 Authentication Flow

- JWT-based authentication
- Cookies for session persistence
- Secure password hashing with **bcrypt**
- Protected routes middleware
- Optional email verification & password recovery (via **Nodemailer**)

---

## 🧠 Key Features

✅ User registration & login  
✅ Product CRUD operations  
✅ Image upload via Cloudinary  
✅ Category & slug management  
✅ Cart & order system (in progress)  
✅ Persian date support  
✅ Responsive design  
✅ Client-side caching via React Query  
✅ Role-based access control (optional)

---

## 🧰 Development Scripts

### Frontend

| Script            | Description                 |
| ----------------- | --------------------------- |
| `npm run dev`     | Run Vite development server |
| `npm run build`   | Build production-ready app  |
| `npm run preview` | Preview the built app       |
| `npm run lint`    | Run ESLint checks           |

### Backend

| Script           | Description                                      |
| ---------------- | ------------------------------------------------ |
| `npm start`      | Start Express server                             |
| `npm run server` | Start with Nodemon (auto-restart on file change) |

---

## 🧪 Future Improvements

- Add payment gateway integration (Stripe / Zarinpal)
- Improve order management system
- Admin dashboard with analytics
- Full test coverage (Jest + React Testing Library)
- Docker support for deployment

---

## 🌍 Deployment

You can deploy this stack easily:

- **Frontend** → [Vercel](https://vercel.com) / [Netlify](https://www.netlify.com)
- **Backend** → [Render](https://render.com) / [Railway](https://railway.app) / [Heroku](https://www.heroku.com)
- **Database** → [MongoDB Atlas](https://www.mongodb.com/atlas)

---

## 👨‍💻 Author

**Reza Bakhshi Nia**  
📧 Email: [Your Email Here]  
🌐 Portfolio: [Your Website Here]  
💼 LinkedIn: [Your LinkedIn URL]

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 💬 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you’d like to change.

---

> _Built with ❤️ using the MERN stack and modern web development best practices._
