# MongoDB-Server
This doesn't need to be our main repository, I was just making one so we will all have access to the code I was able to work out if you are specifically working with databse functionality.

To run this you will likely need to install node.js: https://nodejs.org/en

Haven't tested it on my laptop yet, but you may need to use "npm install cors dotenv express mongodb" & "npm install --save-dev typescript @types/cors @types/express @types/node ts-node" in command prompt.

Given that your files are set up correctly and your command promt is located in the correct directory, using "node insert-data.js" should put in another entry into our cluster on MongoDB for the "GettingStarted" Database, the "people" Collection, and then created a document which most likely says "Alan Turing" given nothing was changed in the insert-data.js file.
