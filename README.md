# How to run the project

1. Create a .env file in the root directory of the project and add the following:
    MONGO_URI=<your_mongo_uri>  // replace <your_mongo_uri> with your MongoDB connection string
    JWT_SECRET=<your_jwt_secret> // replace <your_jwt_secret> with any secret key
    PORT=5000
 
 2. Run the following commands in the terminal:
    npm install
    npm run dev
 
 3. Use Postman or any other API client to test the API endpoints.
 
 4. You can use the following endpoints:
    POST /api/user/register
    POST /api/user/login
    POST /api/todo
    PUT /api/todo/:id
    DELETE /api/todo/:id
    GET /api/todo