
# Payment App MERN
This is a basic version of a Payment app, where users can send credits to their friends. This project does not yet supports real money transaction, but the credit transfer is implemented as a real money transfer.

### Backend 
Technologies used for Backend 
- Express js 
- Mongo DB
- mongoose js
- Json Web Tokens(JWT) for authentication
- Zod library for input validaton


### Frontend
Technologies used for Frontend 
- React JS, React-router-dom
- Tailwind CSS


## How to setup
1. Clone this repository by running `git clone https://github.com/Pathak1947/Wallet-APP.git`

2. Move into project directory: `cd PAYTM-APP`

3. Install dependencies with npm : 

    - for backend: `cd backend` then `npm install`

    - for frontend : `cd frontend` then `npm install`

4. Make sure you have a MongoDB instance in your device, if not then create one and change the URL at `backend/db/db.js`

5. Move to the backend  folder and start server using nodemon: `nodemon index.js` 

6.  Now move to the frontend folder and start the react app: `npm run dev`

7. Open http://localhost:5173 in your browser to see the application