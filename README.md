# Shopping-Website

A full-stack e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This project encompasses user authentication, product management, shopping cart functionality, and more.

## Project Structure
```
- backend – Contains the Express.js server, API routes, and MongoDB models.
- frontend – Contains the React.js application with Redux for state management.
- .env – Environment variables for backend configuration.
- example-env.env – Sample environment configuration file.
```

## Getting Started
1. Clone the Repository
    ```
        git clone https://github.com/mohiniborole28/Shopping-Website
     ```

3. Set Up Environment Variables
   Create a .env file in the root directory and configure the following variables:
   ```
       PORT=5000
       MONGO_URI=your_mongodb_connection_string
       JWT_SECRET=your_jwt_secret_key
    ```

4. Install Dependencies

   Backend
   ```
      cd backend
      npm install
   ```
   Frontend
   ```
      cd ../frontend
      npm install
   ```

6. Run the Application
   Start the Backend Server
   ```
       cd backend
       npm run server
   ```
   
   Start the Frontend Application
   ```
       cd ../frontend
       npm start
   ```

