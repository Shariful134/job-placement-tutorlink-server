# 📚 TutorLink 🎓 Backend

A robust REST API built with **Node.js**, **Express**, **Mongoose**, and **MongoDB** to support the TutorLink platform — a system where students find tutors, book sessions, and manage their learning journey. This backend handles authentication, tutor profiles, bookings, reviews, and payments.

---

## 🚀 Features

- **User Authentication & Authorization** (JWT + bcrypt)
- **Role-based Access Control** (Student & Tutor)
- **Tutor Profile Management**
- **Dynamic Subject Management**
- **Booking System** with status updates
- **Payment Integration** (SSLCommerz / Stripe)
- **RESTful API Architecture**
- **Modular Route & Controller Structure**

---

## 🛠️ Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JWT + bcrypt
- **Deployment:** Render (API), MongoDB Atlas (DB)

---

## 📁 Project Structure

1. All Dependencies Install:
```bash
npm install
```
2. Set up environment variables in your .env file:
```bash
NODE_ENV=development
PORT=5000
DATABASE_URL=[Your mongodb database link]
BCRYPT_SALT_ROUNDS=12
JWT_ACCESS_SECRET = 091b2c529dec033b5ff4531e622ea3f93170e045222963319662b7e4a34f0cdd
JWT_REFRESH_SECRET = 41b991b21dc0a439cb45fed544992ba3fafa3f912d3c4dedebec3592d7d552fb74a86a4d69ea560bcf7bf988d173ddecaffa9815dd5a6661bcacd58c0cdb2dc5
CLIENT_SIDE_URL=[client side url]
CLOUDINARY_CLOUD_NAME=[Your cooud name]
CLOUDINARY_API_KEY=[Your cooud api]
CLOUDINARY_API_SECRET=[Your cooud api secret]
SP_ENDPOINT=https://sandbox.shurjopayment.com
SP_USERNAME=sp_sandbox
SP_PASSWORD=pyyk97hu&6u6
SP_PREFIX=SP
SP_RETURN_URL=[Your frontend deploy link]
```
3. Build in Server
```bash
npm run build
```
4.Start the Server
```bash
npm run start:dev
```

"# portfolio-tutorlink-server" 
"# job-placement-tutorlink-server" 
