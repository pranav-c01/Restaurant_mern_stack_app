# Restaurant MERN Stack Application

## Overview

This is a single-page restaurant application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to explore various sections of the restaurant, including making reservations.

## Features

- **Hero Section**: Engaging introduction to the restaurant.
- **About Section**: Information about the restaurant's history and mission.
- **Qualities Section**: Highlights the unique qualities of the restaurant.
- **Menu Section**: Displays the restaurant's menu items.
- **Who Are We Section**: Information about the team and the restaurant's values.
- **Team Section**: Introduces the restaurant staff.
- **Reservation Section**: Users can make reservations easily.
- **Footer**: Contains contact information and links.

## Technologies Used

- **Frontend**: 
  - React.js
  - React Router (for navigation)
  - Axios (for API calls)
  - React Hot Toast (for notifications)
  
- **Backend**: 
  - Node.js
  - Express.js
  - MongoDB (for database management)


## Installation

### Prerequisites

- Node.js
- MongoDB

### Clone the Repository

```bash
git clone https://github.com/pranav-c01/Restaurant_mern_stack_app.git
cd Restaurant_mern_stack_app
```

### Backend Setup

1. **Navigate to the backend directory:**
   ```bash
   cd backend
   ```

2. **Install dependencies:**

```bash
npm install
```

3. **Create a .env file and add your MongoDB connection string:**

```bash 
MONGODB_URI=your_mongodb_connection_string
```

4. **Start the server:**

```bash
npm start
```


## Frontend Setup

1. **Navigate to the frontend directory:**
   ```bash
   cd frontend
   ```
2. **Install dependencies:**
```bash
npm install
   ```

3. **Start the React application:**
```bash
cd frontend
   ```

## Usage
Visit http://localhost:3000 to access the application.
Explore the various sections of the restaurant.
Use the reservation form to book a table by providing your details.

## Reservation Form
The reservation form allows users to input their first name, last name, email, phone number, date, and time for the reservation. Upon submission, the data is sent to the backend for processing.

## API Endpoint
POST /api/v1/reservation/send: Sends reservation details to the server.
