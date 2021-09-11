-Create app (start at root folder)
npx create-react-app marketplace

cd frontend
npm install react-router-dom

-marketplace folder
npm init (accept defaults)
npm install express
node backend/server.js

npm install --save-dev nodemon (automatically re run after changes in backend) with this code in package.json:
    "start": "nodemon --watch backend --exec node --experimental-modules backend/server.js"

cd frontend 
npm install axios