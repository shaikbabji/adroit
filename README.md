# adroit
1. Set Up the Project Structure
  my-app/
  ├── client/          # React frontend
  ├── server/          # Node.js backend
  ├── .gitignore       # Ignore node_modules and other files
  └── README.md        # Project documentation
2. Set Up the Backend (Node.js + Express + PostgreSQL)
   Step 1: Initialize the Node.js Backend
     1. Navigate to the server folder
       cd server
       npm init -y
     2. Install required dependencies:
        npm install express pg cors body-parser
   Step 2: Create the Server
   Step 3: Set Up PostgreSQL
    Create a database and table:
      CREATE TABLE items (
          id SERIAL PRIMARY KEY,
          name VARCHAR(100) NOT NULL,
          description TEXT
      );
    Update the pool configuration in server.js with your database credentials.
3. Set Up the Frontend (React)
  Step 1: Initialize the React App
    1. Navigate to the client folder:
      cd client
      npx create-react-app .
    2. Install Axios for API calls:
       npm install axios
  Step 2: Create React Components
  Step 3: Run the React App
  npm start in both client and server folders

   
