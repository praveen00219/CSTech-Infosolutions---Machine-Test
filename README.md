# 🏥 Doctor Booking App

A real-time doctor consultation and booking platform with secure video calling capabilities. This full-stack application allows patients to book appointments, consult with doctors via video call, and manage appointments efficiently from both admin and user perspectives.

---

## ✨ Features

- 👨‍⚕️ Doctor appointment booking and scheduling
- 📹 Real-time video consultation using [ZegoCloud API](https://www.zegocloud.com/)
- 🔐 Secure authentication using JWT and bcrypt
- 🌐 Admin dashboard for managing doctors, patients, and bookings
- ⚙️ RESTful API built with Express and MongoDB
- ⚡ Fast and responsive UI built with React and Tailwind CSS

---

## 🧱 Tech Stack

### Frontend

- **React**
- **Tailwind CSS**
- **Vite**
- **React Router**
- **Context API**
- **ZegoCloud SDK** (`@zegocloud/zego-uikit-prebuilt`)
- **Axios**
- **React Toastify**

### Backend

- **Node.js**
- **Express**
- **MongoDB + Mongoose**
- **JWT Authentication**
- **Cloudinary (Image Upload)**
- **Multer**
- **Validator**
- **dotenv**

### Admin Panel & Credentials

- Separate React app for managing data and monitoring operations
- **Login credentials** -
  Email: paru2192000@gmail.com
  Password: Praveen@219

---

## Live Demo

- For User: [https://medico-book.onrender.com](https://medico-book.onrender.com)
- For Admin: [https://medico-book-admin.onrender.com](https://medico-book-admin.onrender.com)

## 📁 Project Structure

```plaintext
.
├── backend         # Node.js/Express server
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   └── models/
├── frontend        # User-facing app
│   └── Vite + React
├── admin           # Admin dashboard
│   └── Vite + React
└── README.md
```

## Getting Started

- Clone the repository:

```bash
   git clone https://github.com/praveen00219/CSTech-Infosolutions---Machine-Test.git
   cd doctor-booking-app

```

- Setup Backend:

```bash
    cd backend
    npm install
    touch .env
    npm run server

```

- Setup Frontend:

```bash
    cd ../frontend
    npm install
    npm run dev

```

- Setup Admin:

```bash
    cd ../admin
    npm install
    npm run dev

```

## Environment Variables

- Backend (.env):

```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret
```

- Frontend/Admin:

```env
    VITE_API_URL=http://localhost:5000

```

## Acknowledgements

- ZegoCloud – for real-time video API
- MongoDB
- React
- Tailwind CSS

## Auther

- Praveen - [LinkedIn](https://www.linkedin.com/in/praveen219/)
