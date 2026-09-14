# 🏡 WanderLust — Airbnb Clone

A full-stack property listing web application inspired by Airbnb, where users can browse, create, edit, and delete property listings. Built to practice and demonstrate core backend and full-stack web development concepts including RESTful routing, MVC architecture, and database modeling.

🔗 **Live Demo:** [wanderlust-airbnb-clone-026b.onrender.com/listings](https://wanderlust-airbnb-clone-026b.onrender.com/listings)

---

## 📸 Screenshots

### All Listings
![All Listings](./screenshots/All%20Listings.jpeg)

### Listing Details
![Listing Details](./screenshots/Listing%20Details.jpeg)

### Create New Listing
![Create Listing](./screenshots/Create%20New%20Listing.jpeg)

---

## ✨ Features

- Browse all property listings with images, price, and location
- View detailed information for each listing
- Create a new listing with title, description, price, image, location, and country
- Edit existing listings
- Delete listings
- Responsive, clean UI built with Bootstrap
- RESTful route structure following REST conventions (Index, Show, New, Create, Edit, Update, Destroy)

---

## 🛠️ Tech Stack

**Backend:** Node.js, Express.js
**Database:** MongoDB (Mongoose ODM), hosted on MongoDB Atlas
**Templating:** EJS
**Styling:** Bootstrap 5
**Deployment:** Render (backend), MongoDB Atlas (database)

---

## 🚀 Getting Started (Run Locally)

1. Clone the repository
```bash
   git clone https://github.com/RambabuSonker/wanderlust-airbnb-clone.git
   cd wanderlust-airbnb-clone
```

2. Install dependencies
```bash
   npm install
```

3. Create a `.env` file or update the `MONGO_URL` in `app.js` with your MongoDB connection string

4. Seed sample data (optional)
```bash
   node init/index.js
```

5. Start the server
```bash
   node app.js
```

6. Visit `http://localhost:8080/listings`

---

## 📂 Project Structure