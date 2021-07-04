# Login-system-description

User authentication and login is the most important feature of many websites, and most likely a key component to any project. In this project I covered absolutely everything
needed for user login and authentication in the most minimalistic and simple way. I use Express for the server backend and Passport to help manage the logged in state 
of users. I also make sure to properly encrypt and hash all user passwords so that the application is completely secure. 

The final app is a fully functional login system that can be used in any future project.

# Tech Stack
- Node.js
- Express
- bcrypt
- Passportjs
- Ejs template system
- few other dependencies. check out package.json to see full modules and versions.

# Key Features
- Server with Node.js and Express
- Passport set-up with Node.js and Express
- User passwords encryption
- Restrictition: access to routes to only logged in users
- Flash messages with Node.js and Express

EJS is used for templating and HTML forms. 
Database could potentially be added, but in order to keep project simple, I just store user info in a variable within server.js file.

## Setup guide:
clone the repository: git clone xxxx
Change directory: cd xxx

see a live demo <a href="https://login-passport-test.herokuapp.com/">here</a>!
