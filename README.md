# 🏕️ Camplelo (YelpCamp)

A full-stack campground listing and review platform inspired by Yelp, where users can discover, create, review, and manage campgrounds. The application features secure authentication, image uploads, interactive maps, and a responsive user interface.

🚀 **Live Demo:** https://camplelo-com.vercel.app/

📂 **GitHub Repository:** https://github.com/ParthG-dev/Camplelo.com

---

# ✨ Features

## 👤 Authentication & Authorization

* User registration and login
* Secure password hashing using Passport.js
* Session-based authentication
* Authorization to ensure only owners can edit or delete their campgrounds and reviews
* Flash messages for user feedback

## 🏕️ Campgrounds

* Create new campground listings
* Browse all campgrounds
* View detailed campground information
* Edit campground details
* Delete campground listings
* Upload multiple campground images

## ⭐ Reviews

* Add ratings and reviews
* Delete personal reviews
* Server-side review validation

## 📍 Maps & Location

* Interactive maps powered by **MapTiler**
* Geocoding support for campground locations
* Dynamic location markers

## ☁️ Image Uploads

* Cloudinary integration for image hosting
* Multiple image uploads using Multer
* Cloud-based image management

## 🔒 Security

* Server-side validation using Joi
* Passport.js authentication
* Helmet security headers
* MongoDB query sanitization
* Secure session management
* Centralized error handling

---

# 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* EJS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

### Authentication

* Passport.js
* Passport Local
* Express Session

### Cloud Services

* Cloudinary
* MapTiler

### Validation & Security

* Joi
* Helmet
* Express Mongo Sanitize
* Connect Flash

### Deployment

* Vercel

---

# 📁 Project Structure

```text
Camplelo/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── cloudinary/
├── utils/
├── middleware.js
├── schemas.js
├── app.js
├── package.json
└── .env
```

The project follows the **MVC (Model-View-Controller)** architecture, making the code modular, scalable, and easy to maintain.

---

# 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/ParthG-dev/Camplelo.com.git
```

### 2. Navigate to the project directory

```bash
cd Camplelo.com
```

### 3. Install dependencies

```bash
npm install
```

### 4. Create a `.env` file

```env
DB_URL=your_mongodb_connection_string

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_secret

MAPTILER_API_KEY=your_maptiler_api_key

SECRET=your_session_secret
```

### 5. Start the application

```bash
npm start
```

or

```bash
nodemon app.js
```

### 6. Open your browser

```
http://localhost:3000
```

---

# 🌐 Live Demo

The application is deployed on **Vercel** and can be accessed here:

**https://camplelo-com.vercel.app/**

---

# 📸 Screenshots

> Add screenshots of your application here.

Suggested screenshots:

* Home Page
* Campground Listing
* Campground Details
* Create Campground
* Login Page
* Register Page
* Review Section
* Interactive Map

---

# 📚 What I Learned

Building this project helped me gain practical experience with:

* MVC Architecture
* RESTful Routing
* Authentication & Authorization
* Session Management
* MongoDB & Mongoose
* Cloudinary Image Uploads
* Interactive Maps with MapTiler
* Express Middleware
* Server-side Validation
* Secure Web Development
* Error Handling
* Full-Stack Application Development
* Deployment using Vercel

---

# 🚀 Future Improvements

* User profile pages
* Favorites / Wishlist
* Search functionality
* Category-based filtering
* Pagination
* Dark mode
* Notifications
* Admin dashboard
* Responsive image optimization

---

# 👨‍💻 Author

**Parth Gupta**

**GitHub:** https://github.com/ParthG-dev

**Project Repository:** https://github.com/ParthG-dev/Camplelo.com

**Live Demo:** https://camplelo-com.vercel.app/

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub. Your support is greatly appreciated!
