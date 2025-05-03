
# 🏠 Real Estate Marketplace WebApp

A Full-Stack Real Estate Marketplace application built using the **MERN** stack, allowing users to list, search, and manage property listings. The platform supports user authentication (JWT, Google OAuth), image uploads (Firebase), advanced search and filtering, and CRUD operations for property listings.

---

## 📌 Tech Stack

**Frontend:**  
- React.js (Vite, React Router, Redux Toolkit + Persist)
- Tailwind CSS
- Firebase (Image Upload and Google OAuth)

**Backend:**  
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT (User Authentication)
- Firebase (Image Upload)

**Deployment:**  
- Render (Backend + Frontend)

---

## 📂 Project Structure

```
📦 root
├── api
│   ├── controllers
│   │   ├── auth.controller.js
│   │   ├── listing.controller.js
│   │   └── user.controller.js
│   ├── models
│   │   ├── listing.model.js
│   │   └── user.model.js
│   ├── routes
│   │   ├── auth.routes.js
│   │   ├── listing.routes.js
│   │   └── user.routes.js
│   ├── utils
│   │   ├── error.js
│   │   └── verifyUser.js
│   └── index.js
├── client
│   └── src
│       ├── components
│       │   ├── Contact.jsx
│       │   ├── Header.jsx
│       │   ├── ListingItem.jsx
│       │   ├── OAuth.jsx
│       │   └── PrivateRoute.jsx
│       ├── pages
│       │   ├── About.jsx
│       │   ├── CreateListing.jsx
│       │   ├── Home.jsx
│       │   ├── Listing.jsx
│       │   ├── Profile.jsx
│       │   ├── Search.jsx
│       │   ├── SignUp.jsx
│       │   ├── Signin.jsx
│       │   └── UpdateListing.jsx
│       ├── redux
│       │   └── user
│       │       ├── userSlice.js
│       │       └── store.js
│       ├── App.jsx
│       ├── firebase.js
│       ├── index.css
│       ├── main.jsx
├── .gitignore
├── README.md
├── package.json
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js
```

---

## 🚀 Features

- **User Authentication (JWT + Google OAuth):**
  - Email/password login/signup
  - Google OAuth login/signup
  - Secure JWT-based auth using HttpOnly cookies

- **Property Listings:**
  - Create, Update, Delete listings
  - Upload up to 6 images per listing (Firebase Storage)
  - Display properties with advanced search and filters

- **Search & Filter:**
  - Filter by price, type, bedrooms, parking, and furnished status
  - Real-time "Show More" loading functionality

- **Contact Functionality:**
  - Direct contact via email to listing owners

- **Profile Management:**
  - Update profile picture, username, and email
  - View user’s own listings
  - Delete account

- **Responsive UI:**
  - Built with TailwindCSS for clean and responsive design
  - Fully mobile optimized

---

## 🛠️ Installation Instructions

### Backend (API)

```bash
cd api
npm install
npm run dev
```

### Frontend (Client)

```bash
cd client
npm install
npm run dev
```

---

## Hosted on Render

```
https://realestates-kefw.onrender.com/
```

## 📌 Future Improvements

- Notifications (Email + In-app)
- User reviews and ratings
- Real-time chat between owners and buyers
- Payment gateway integration

---
