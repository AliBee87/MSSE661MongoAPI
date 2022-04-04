## How Do You Like Your Salmon? 

The purpose of this project is to provide the backend for my web page, "How Do You Like Your Salmon?" The goal of the final project is to prompt the user with a series of questions that will provide them with a salmon recipe respective to their choices. 

This project is built with **JavaScript using Node Express and tested with Thunder Client** in VS. I used **MongoDB** for this project as well.

# Getting Started
  In your editor, apply: 
  ```
  git clone https://github.com/AliBee87/MSSE661MongoAPI
  
  cd MSSE661MongoAPI
  
  npm install
  ```
  

After installing NPM, ensure the following packages are installed. If not, you can **_install the following packages using_**:
  ```   
    npm i bcrypt
    npm i cookie-parser
    npm i cors
    npm i date-fns
    npm i dotenv
    npm i express
    npm i jsonwebtoken
    npm i mongoose
    npm i uuid
   ```
    
You'll need to **_create a .env file in the file tree at the root. In it copy and paste the following_**:
    
    ACCESS_TOKEN_SECRET=
    REFRESH_TOKEN_SECRET=
    DATABASE_URI=mongodb+srv://<username>:<password>@cluster0.ta6fn.mongodb.net/SalmonDB?retryWrites=true&w=majority
    
These will require personal access tokens. To **_create a personal access token,_** write the following commands in your terminal:
  ```
    node
    require('crypto').randomBytes(64).toString('hex')
  ```
Generate, copy and paste each output from these commands to both ACCESS_TOKEN_SECRET and REFRESH_TOKEN_SECRET, excluding the ' ' around the supplied output.


**To get the DATABASE URI**

  - Sign into Mongodb.com
  - Under "Security" select "Database Access"
  - Select "Add New Database User" and keep the Authentication Method at Password
  - Enter user and password, copy, select "Add User"
  - Back in your editor, in the .env, enter the username and password into the Database URI, excluding the carrots
  

**Then, in your terminal, enter npm run dev, and you should be good to go!**
         
  
  
