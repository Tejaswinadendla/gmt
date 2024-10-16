Backend Setup:

Navigate to the backend directory:

Install dependencies:
npm init -y
npm install
npm install express mongoose body-parser

CopyMONGODB_URL=mongodb+srv://gametheory:gametheory@cluster0.6sffr.mongodb.net/gm?retryWrites=true&w=majority

Start the backend server:
node server.js
The server should now be running on http://localhost:5000.


Frontend Setup:

Open a new terminal and create a new react app:
npx create-react-app booking-app-frontend

Install dependencies:
npm install
npm install axios

Start the React development server:
npm start
The UI should now be running on http://localhost:3000.
