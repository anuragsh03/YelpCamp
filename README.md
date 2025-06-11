# YelpCamp

**A Full-Stack Web Application for Campground Discovery and Reviews**

---

## Overview

YelpCamp is a full-stack web application inspired by Yelp, but designed specifically for camping enthusiasts. Users can browse, create, and review campgrounds. The project features user authentication, campground management, and interactive reviews, making it an excellent showcase for modern web development skills.

---

## Features

- **User Authentication:**  
  - Register and log in using username/email and password.
  - Authentication handled with Passport.js.
- **Campground Management:**  
  - Create, view, edit, and delete campground listings.
  - Only authenticated users can add or edit campgrounds.
- **Reviews:**  
  - Add, edit, and delete reviews for campgrounds.
  - Users can only modify their own reviews.
- **Authorization:**  
  - Users can only edit or delete campgrounds and reviews they have created.
- **Responsive Design:**  
  - Mobile-friendly interface using Bootstrap.
- **Flash Messages:**  
  - Success and error notifications for user actions.
- **Image Upload:**  
  - Upload and display campground images (Cloudinary integration).
- **Map Integration:**  
  - Display campground locations on a map (Mapbox or Google Maps).
- **Search and Sorting:**  
  - Search campgrounds by name or location.
  - Sort by rating, price, or number of reviews.
- **Client and Server-Side Validation:**  
  - Form validation using Bootstrap and Joi.

---

## Technologies Used

- **Frontend:**  
  - HTML5, CSS3, Bootstrap, EJS
- **Backend:**  
  - Node.js, Express.js, RESTful Routing
- **Database:**  
  - MongoDB (Mongoose ODM)
- **Authentication:**  
  - Passport.js, express-session, connect-flash
- **Image Hosting:**  
  - Cloudinary
- **Map Integration:**  
  - Mapbox or Google Maps API

---

## Getting Started

### Prerequisites

- **Node.js** and **npm** installed
- **MongoDB** installed and running
- **Cloudinary** account for image uploads
- **Mapbox or Google Maps API key** for map features

### Installation

1. **Clone the repository:**

git clone https://github.com/YOUR-USERNAME/YelpCamp.git
cd YelpCamp

2. **Install dependencies:**

npm install

3. **Set up environment variables:**
- Create a `.env` file in the root directory.
- Add the following variables:
  ```
  DATABASE_URL=mongodb://localhost:27017/yelpcamp
  CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
  CLOUDINARY_KEY=your_cloudinary_key
  CLOUDINARY_SECRET=your_cloudinary_secret
  MAPBOX_TOKEN=your_mapbox_token
  ```
4. **Start the application:**

node app.js

- Visit `http://localhost:3000` in your browser.

---

## Usage

- **Browse campgrounds** without logging in.
- **Register** or **log in** to create, edit, or delete campgrounds and reviews.
- **Upload images** and **view campground details**.
- **Leave reviews** and **see campgrounds on a map**.

---

## Screenshots

*Add screenshots of the main pages here if available.*

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License.

---

*Enjoy your camping adventures with YelpCamp!*
