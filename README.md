# 🚗 Car Rental Booking Platform

A full-stack MERN Car Rental Booking Platform that allows users to browse, search, and book rental vehicles while providing vehicle owners with a dashboard to manage their cars and bookings.

## 🌐 Live Demo

### Frontend
https://car-rental-mern-one.vercel.app/

### Backend API
https://car-rental-server-zeta-ten.vercel.app/

---

## ✨ Features

### User Features

- Browse available rental vehicles
- Search cars
- View detailed car information
- Book rental cars
- View booking history
- Responsive UI for desktop and mobile
- Secure authentication

### Owner Features

- Owner Dashboard
- Add new cars
- Upload car images
- Manage listed vehicles
- View customer bookings
- Update vehicle availability

---

## 🛠 Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- React Router DOM
- Axios

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- ImageKit

### Deployment

- Frontend: Vercel
- Backend: Vercel

---

## 📂 Project Structure

```
CarRental/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── package.json
│   └── server.js
│
├── README.md
└── .gitignore
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/CarRental.git
```

### Install Frontend

```bash
cd client
npm install
npm run dev
```

### Install Backend

```bash
cd server
npm install
npm run server
```

---

## 🔐 Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=5000

MONGODB_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY

IMAGEKIT_PUBLIC_KEY=YOUR_PUBLIC_KEY
IMAGEKIT_PRIVATE_KEY=YOUR_PRIVATE_KEY
IMAGEKIT_URL_ENDPOINT=YOUR_URL_ENDPOINT

CLERK_SECRET_KEY=YOUR_CLERK_SECRET_KEY
```

---

## 📱 Pages

- Home
- Cars Listing
- Car Details
- My Bookings
- Owner Dashboard
- Add Car
- Manage Cars
- Manage Bookings

---

## 💡 Future Improvements

- Online Payments (Stripe/Razorpay)
- Reviews & Ratings
- Wishlist
- Email Notifications
- Advanced Filters
- Google Maps Integration

---

## 🎯 Skills Demonstrated

- Full Stack MERN Development
- REST API Development
- Authentication & Authorization
- CRUD Operations
- Responsive UI Design
- MongoDB Database Design
- Image Upload & Cloud Storage
- API Integration
- Deployment using Vercel

---

## 👩‍💻 Author

**Pinki**

GitHub: https://github.com/YOUR_GITHUB_USERNAME

LinkedIn: https://linkedin.com/in/YOUR_LINKEDIN

---

## 📄 License

This project is created for educational and portfolio purposes.