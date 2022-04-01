# MSSE661MongoAPI

After some work and following Dave Grey's tutorials on getting a server going, I finally have my server and API running! I have built my code in Javascript using Node Express and working with MongoDB. Though I don't have much against which to compare Thunder Client, I thought it was pretty neat to be able to run my tests with it inside VS.

In this code, you will find the following files:
config: the parameters for my HTML, roles, and security
controllers: these were built for the responses to be sent back to the browser. You will find code working with JWT for purposes such as authentication, registration, and get/set methods for my recipes
middleware: this is what I understand to be the "middleman" for "translating" the data. You will find middleware for credentials, error handling, event logging, and verifying roles as well as JWT's. 
model: you will find models for my recipes and users in this folder. From here I was able to create and store the data for users and recipes. 
routes: the "instructions" for directing the "traffic" of the requests
views: you'll find a very basic index html for my first page
server: operating as the "main" for my code

packages employed:I learned how to install and use bcrypt, cookie-parser, cors, date-fns, dotenv, express, JWS, mongoose, and uuid. 

This was a lot of work and the final output is nowhere near perfect, but I'm happy with the hours and work I put into building it! 
