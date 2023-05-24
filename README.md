# Text Editor Starter Code

> cd Develop
> npm install
> npm run build
> npm run start:dev

http://localhost:3000

"scripts": {
"start:dev": "concurrently \"npm run client\" \"npm run server\"",
"start": "concurrently \"npm run client\" \"npm run server\"",
"server": "cd server && node server.js",
"build": "cd client && npm run build",
"install": "cd client && npm install && cd .. && cd server && npm install ",
"client": "cd client/dist && npm start"
},
