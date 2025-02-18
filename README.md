# Rooms Booking App

## Overview
The **Rooms Booking App** is a full-stack web application that allows users to search, book, and manage room reservations. It provides an intuitive UI for customers to browse available rooms and an admin dashboard for managing bookings.

## Features
- User authentication (sign-up, login, logout)
- Browse and filter available rooms
- Book rooms and manage reservations
- Payment integration for seamless transactions
- Admin dashboard to manage room availability and bookings
- Responsive UI for a smooth user experience

## Tech Stack
- **Frontend:** React.js, TypeScript, Redux, Tailwind CSS
- **Backend-as-a-Service:** Appwrite
- **Authentication:** JWT-based authentication
- **State Management:** Redux
- **Styling:** Tailwind CSS
- **Database:** MongoDB with Mongoose ORM

## Appwrite Backend
For this project, I have used the **Appwrite** platform to handle our backend requirements. Appwrite is an open-source Backend-as-a-Service (BaaS) that provides a robust set of APIs for common backend functionalities.
- **Authentication:** Implemented secure user authentication using Appwrite's Auth API.
- **Database:** Utilized Appwrite's database service for storing and managing application data.
- **Storage:** Employed Appwrite's storage solution for handling image file uploads.
## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/souravpl8092/rooms-booking-app.git
   ```

2. Navigate to the project directory:
   ```sh
   cd rooms-booking-app
   ```

3. Install dependencies:
   ```sh
   npm install
   ```

4. Set up the environment variables:
   - Create a `.env` file in the root directory
   - Add the required variables such as database connection string, JWT secret, and API keys

5. Start the development server:
   ```sh
   npm start
   ```

6. For backend setup:
   ```sh
   cd backend
   npm install
   npm run dev
   ```

## License
This project is licensed under the MIT License.

## Contact
For any issues or queries, feel free to reach out:
- **GitHub:** [souravpl8092](https://github.com/souravpl8092)

---
### Happy Coding! 🚀


