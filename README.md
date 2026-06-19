# TravelBuddy – Full Stack Travel Booking Web Application

TravelBuddy is a full-stack travel booking platform inspired by popular travel service providers. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), the application enables users to search, book, and manage travel services including flights, hotels, trains, and cabs through a modern and responsive web interface.

---

## Project Overview

TravelBuddy provides a centralized travel booking experience by integrating multiple transportation and accommodation services into a single platform.

The application includes secure authentication, dynamic search functionality, booking management, payment simulation, role-based dashboards, and administrative controls.

---

## Features

### Authentication and Authorization

* User Registration and Login
* JWT-Based Authentication
* Password Encryption with bcrypt
* User and Admin Roles
* Google Authentication Integration

### Dynamic Travel Search

* Flight Search
* Hotel Search
* Train Search
* Cab Search
* Advanced Search Filters
* Tab-Based Search Interface

### Booking Management

* Unified Booking Flow
* Add to Cart Functionality
* Booking Confirmation
* Booking History Tracking
* Price Calculation Engine

### Payment Gateway Simulation

* Mock Payment Integration
* Transaction Processing
* Booking Status Updates
* Payment Tracking

### User Dashboard

* Personal Booking History
* Booking Statistics
* User Profile Management

### Admin Dashboard

* Platform Statistics
* Booking Management
* Service Monitoring
* Booking Status Control

### Responsive User Interface

* Modern Design
* Mobile-Friendly Layout
* Intuitive Navigation
* Fast User Experience

---

## Technology Stack

### Frontend

* React.js
* JavaScript (ES6+)
* Vite
* Tailwind CSS
* React Context API

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose ODM

### Authentication

* JSON Web Token (JWT)
* bcrypt.js
* Google OAuth

### APIs

* RESTful APIs

### Development Tools

* Git
* GitHub
* Visual Studio Code

---

## Project Structure

```text
travelbuddy-backend
│
├── config
├── controllers
├── middleware
├── models
├── routes
├── utils
├── package.json
└── server.js

travelbuddy-frontend
│
├── public
├── src
│   ├── components
│   ├── context
│   ├── pages
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── vite.config.js
└── tailwind.config.js
```

---

## System Architecture

```text
Frontend (React.js)
         |
         v
REST API Layer
         |
         v
Backend (Node.js + Express.js)
         |
         v
Authentication Services
         |
         v
MongoDB Database
```

---

## Installation and Setup

### Prerequisites

* Node.js
* MongoDB
* Git

---

### Clone the Repository

```bash
git clone https://github.com/yourusername/TravelBuddy.git

cd TravelBuddy
```

---

## Database Setup

Ensure MongoDB is installed and running locally:

```bash
mongodb://localhost:27017
```

Create collections automatically through the application or insert sample data manually.

---

## Backend Setup

Navigate to the backend directory:

```bash
cd travelbuddy-backend
```

Install dependencies:

```bash
npm install
```

Start the backend server:

```bash
npm run dev

# OR

node server.js
```

Backend URL:

```text
http://localhost:5000
```

---

## Frontend Setup

Navigate to the frontend directory:

```bash
cd travelbuddy-frontend
```

Install dependencies:

```bash
npm install
```

Start the React application:

```bash
npm run dev
```

Frontend URL:

```text
http://localhost:5173
```

---

## Google Authentication Setup

### Frontend Dependencies

```bash
npm install @react-oauth/google jwt-decode
```

### Backend Dependencies

```bash
npm install google-auth-library
```

### Environment Variables

Frontend:

```env
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

Backend:

```env
GOOGLE_CLIENT_ID=your_google_client_id
JWT_SECRET=your_secret_key
MONGODB_URI=your_mongodb_connection_string
```

---

## Core Modules

### Authentication Module

Handles user registration, login, Google OAuth, and authorization.

### Search Module

Provides search functionality for flights, hotels, trains, and cabs.

### Booking Module

Manages booking creation, updates, and cancellation.

### Payment Module

Processes payment simulation and transaction handling.

### User Dashboard

Displays user bookings, statistics, and account information.

### Admin Dashboard

Provides administrative controls and booking management.

---

## Security Features

* JWT Authentication
* Password Hashing with bcrypt
* Protected API Routes
* Role-Based Access Control
* Google OAuth Authentication
* Secure Session Management

---

## Application Workflow

1. User registers or logs in.
2. User searches for travel services.
3. User selects a service and proceeds to booking.
4. Payment process is initiated.
5. Booking confirmation is generated.
6. Booking history is stored and displayed in the dashboard.

---

## Future Enhancements

* Real Payment Gateway Integration
* Flight and Hotel APIs
* Real-Time Ticket Availability
* AI-Based Travel Recommendations
* Travel Expense Tracker
* Multi-Currency Support
* Push Notifications
* Mobile Application Development
* Travel Review System

---

## Learning Outcomes

This project demonstrates practical implementation of:

* Full Stack Web Development
* MERN Stack Architecture
* REST API Development
* JWT Authentication
* Google OAuth Integration
* MongoDB Database Design
* Role-Based Access Control
* Payment Processing Workflows
* Responsive UI Development

---

## Author

Atharva Dhanraj Kakde

B.Tech Computer Science and Engineering
Minor in Artificial Intelligence and Machine Learning (AI/ML)
Jawaharlal Nehru Engineering College (JNEC), MGM University

GitHub: https://github.com/atharvakakde

Portfolio: https://atharva-kakde-portfolio.vercel.app
