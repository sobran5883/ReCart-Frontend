# Recart - E-commerce Website

## Overview
Recart is a full-stack e-commerce platform built using the latest web technologies. It provides a seamless shopping experience with features like product browsing, cart management, user authentication, order tracking, and secure payments via Razorpay.

## Features
- **User Authentication**: Secure login/signup using JWT authentication.
- **Product Browsing**: Users can explore products with detailed descriptions and images.
- **Cart Management**: Add/remove items, adjust quantities, and view the total price.
- **Order Tracking**: Users can view their order history and track the status.
- **Payment Integration**: Secure payments handled through Razorpay.
- **Admin Panel**: Manage products, orders, and users efficiently.

## Tech Stack
- **Frontend**: ReactJS, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **State Management**: Redux

## Installation
### Prerequisites
- Node.js installed
- MongoDB setup

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/sobran5883/ReCart-website.git
   cd server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```bash
   npm start
   ```
5. Navigate to the frontend directory and install dependencies:
   ```bash
   cd client
   npm install
   ```
6. Start the frontend:
   ```bash
   npm run dev
   ```

## Contact
For any questions or suggestions, reach out to me at sobran0054@gmail.com.

