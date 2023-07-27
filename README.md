<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dhruvsethi708/Netflix-Clone">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Netflix_2015_N_logo.svg/800px-Netflix_2015_N_logo.svg.png" alt="Logo" width="80" height="auto">
  </a>

<h3 align="center">Netflix Clone</h3>

  <p align="center">
    A full-stack Netflix clone that comes with an admin dashboard.
    <br />
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

<p align="center"><img src="https://firebasestorage.googleapis.com/v0/b/netflix-clone-49e41.appspot.com/o/prevN.png?alt=media&token=517f7148-b492-4eb9-a98e-6917e398ddab" alt="Netflix Screenshot" width="800" height="auto">  
  <br />  
  <br />  
<img src="https://firebasestorage.googleapis.com/v0/b/netflix-clone-49e41.appspot.com/o/prevAD.png?alt=media&token=0fe915b7-6614-4bf5-ac21-68fa1c4b13f5" alt="Admin Dashboard Screenshot" width="800" height="auto"></p>

This is a Netflix clone written using the MERN stack. It features a client side which allows users to register, login, browse and watch content categorized by type (movie or series) and genre. It also features an admin dashboard which is a fully functional CMS that allows admins to view, create, modify and delete users, content and content lists. 


### Built With

* [Material UI](https://mui.com/)
* [React.js](https://reactjs.org/)
* [Node.js](https://nodejs.org/en/)
* [Express](https://expressjs.com/)
* [JSON Web Token](https://jwt.io/)
* [MongoDB](https://www.mongodb.com/)
* [Mongoose](https://mongoosejs.com/)
* [Firebase](https://firebase.google.com/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* npm  
  <br /> 
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo  
   <br /> 
   ```sh
   git clone https://github.com/dhruvsethi708/Netflix-Clone.git
   ```
2. Install NPM packages  
   <br /> 
   ```sh
   npm install  // API dependencies
   cd client
   npm install  // Client side dependencies
   cd ..
   cd admin
   npm install  // Admin dashboard dependencies
   ```
3. Run server and front end  
   <br /> 
   ```sh
   cd ..
   nodemon start  // Start server
   cd client
   npm start      // Start Netflix front end
   cd ..
   cd admin
   npm start      // Start admin dashboard front end
   ```

