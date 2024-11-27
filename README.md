
# Role-Based Access Control (RBAC)

This is a **Role-Based Access Control** application built using **Node.js**, **Express**, **Passport.js**, and more.

## Features

- **Authentication**: Supports email and password authentication.
- **Authorization**: Implements Role-Based Access Control for managing user permissions.
- **MVC Architecture**: Built using the **Model-View-Controller** design pattern for clean and maintainable code.
- **Database Integration**: Uses **Mongoose** as an ORM for MongoDB to manage user data.
---

## Prerequisites

Before running the application, ensure the following are installed on your system:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- Basic knowledge of JavaScript, Node.js, and MongoDB is recommended.

---

## Getting Started

Follow these steps to set up and run the application locally:

### 1. Clone the Repository
```bash
git clone https://github.com/raaahul1102/RBAC.git
```

### 2. Install Dependencies
Navigate to the project folder and install the required packages:
```bash
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the root directory and add the following variables:
```env
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI # Example: mongodb://localhost:27017
DB_NAME=YOUR_DB_NAME
```

### 4. Connect MongoDB
Ensure MongoDB is running and accessible at the URI specified in your `.env` file.

### 5. Run the Application
Start the server using:
```bash
node app.js
```
The application will run on the port specified in the `.env` file (default: `3000`).

---


## Admin details
- Email: admin@gmail.com
- Password: 123456

---

## Deployment

The application is deployed and accessible at:
[https://rbac-5ee4.onrender.com](https://rbac-5ee4.onrender.com)

