# MERN Flight Booking Application

The MERN Flight Booking Application is a comprehensive flight booking system built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

The application includes the following features:

### Front-End

- Sign-In & Sign-Up Pages: Users can create an account and log in to access the website.
- Token-Based System: Only registered users can access the website, and authentication is handled using passport.js.
- Password Hashing: User passwords are securely hashed using passport.js.
- Profile Page: Users have a profile page that displays their information.
- City Selection: Users can choose their starting city and destination city from a list of available cities.
- Flight Listings: The application provides a list of flights from different airlines, including various details.
- Seat Selection: Users can select their seats from a user-friendly interface, and the application generates dynamic forms for storing passenger data.
- Confirmation Page: After seat selection, users are taken to a confirmation page where they can provide debit card data (without payment processing).
- Boarding Pass: The final page displays a boarding pass with passenger data and generates a random transaction ID.

### Back-End

- Express.js Application: The backend is built using Express.js.
- MongoDB Atlas: The application uses MongoDB Atlas to store collections.
- User Authentication: Authentication and token-based system are implemented using passport.js.
- Password Hashing: User passwords are securely hashed using passport.js.
- Seat Data: This version of the application does not support storing dynamic seat data from the cloud.

## Getting Started

Follow these instructions to set up and run the project on your local machine for development and testing purposes.

### Prerequisites

Make sure the following software is installed on your system:

- Node 8.x
- npm 3.x

To check your Node.js and npm versions, run the following commands in the terminal:

```bash
node -v
npm -v
```

### Installation

To install the necessary dependencies, run the following commands:

```bash
cd SWADESHI AIRLINES/frontend
npm install
cd ../backend
npm install
```

### Starting the Application

To start the frontend and backend servers, run the following commands:

```bash
cd SWADESHI AIRLINES/frontend
npm start
```

Open a new terminal window and run:

```bash
cd SWADESHI AIRLINES/backend
npm run devStart
```

These commands will start the MongoDB and frontend servers.

By following these instructions, you will have the MERN Flight Booking Application running on your local machine.
