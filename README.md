# Amazon Clone

This project is a clone of Amazon built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It includes features such as password hashing, JWT authentication, user login/logout functionality, Redux for state management, Material UI for styling, and Postman for testing APIs.

## Features:
- User authentication: Users can sign up, login, and logout.
- Password hashing: User passwords are securely hashed before being stored.
- JWT authentication: JSON Web Tokens are used for user authentication.
- Redux for state management: Provides a predictable state container for managing application state.
- Material UI for styling: Offers a set of pre-designed React components for building user interfaces.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/amitesh197/Amazon-Clone.git
```

2. Navigate to the project directory:
```bash
cd Amazon-Clone
cd server
npm install
cd ../client
npm install
```

3. Configuration
Create a .env file in the server directory and add the following variables:
```bash
MONGODB_URI=<Your MongoDB connection URI>
KEY=<Your JWT secret key>
```
Replace <Your MongoDB connection URI> with your actual MongoDB connection URI and <Your JWT secret key> with your desired JWT secret key.

4. Running the Application

Start the server:
```bash
cd server
node app.js
```

Start the client:
```bash
cd ../client
npm start
```

The application should now be running on `http://localhost:3000`

## Contributing
Contributions are welcome! Feel free to submit pull requests or open issues if you encounter any problems or have suggestions for improvements.
