## How Do You Like Your Salmon? 

The purpose of this project is to provide the backend for my web page, "How Do You Like Your Salmon?" The goal of the final project is to prompt the user with a series of questions that will provide them with a salmon recipe respective to their choices. 

This project is built with **JavaScript using Node Express and tested with Thunder Client** in VS. 

# Getting Started

After **_installing NPM, install the following packages using_**:
  ```   
    npm i bcrypt
    npm i cookie-parser
    npm i cors
    npm i date-fns
    npm i bcrypt
    npm i bcrypt
    npm i dotenv
    npm i express
    npm i jsonwebtoken
    npm i mongoose
    npm i uuid
   ```
    
You'll need to **_create a .env file in the file tree at the root. In it write_**:
    
    ACCESS_TOKEN_SECRET=
    REFRESH_TOKEN_SECRET=
    
These will require personal access tokens. To **_create a personal access token,_** write the following commands in your terminal:
  ```
    node
    require('crypto').randomBytes(64).toString('hex')
  ```
Generate, copy and paste each output from these commands to both ACCESS_TOKEN_SECRET and REFRESH_TOKEN_SECRET, excluding the ' ' around the supplied output.
    
   
    
## Additional Project Details : 

After some work, and following Dave Grey's YouTube tutorials, I finally have my server and API running! Though I don't have much against which to compare Thunder Client, I thought it was pretty neat to be able to run my tests with it inside VS.

In this code, you will find the following files:

  - config: the parameters for my HTML, roles, and security
  
  - controllers: these were built for the responses to be sent back to the browser. You will find code working with JWT for purposes such as authentication, registration, and get/set methods for my recipes
  
  - middleware: this is what I understand to be the "middleman" for "translating" the data. You will find middleware for credentials, error handling, event logging, and verifying roles as well as JWT's. 
  
  - model: you will find models for my recipes and users in this folder. From here I was able to create and store the data for users and recipes. 

  - routes: the "instructions" for directing the "traffic" of the requests

  - views: you'll find a very basic index html for my first page

  - server: operating as the "main" for my code


This was a lot of work and the final output is nowhere near perfect, but I'm happy with the hours and work I put into building it! 
