# MongoDB-Server
This doesn't need to be our main repository, I was just making one so we will all have access to the code I was able to work out if you are specifically working with databse functionality.

To run this you will likely need to install node.js: https://nodejs.org/en

You will probably need to first dowload Atlas by installing Atlas here: https://www.mongodb.com/docs/atlas/cli/stable/install-atlas-cli/
After that you will probably need to login to atlas through the command prompt by following this guide: https://www.mongodb.com/docs/atlas/cli/stable/connect-atlas-cli/
(NOTE: you may need to first login to MongoDB using the Username and Password to set up your email address so you can login through Atlas, otherwise you may use my account but I will need to be online to verify your identity)

You will need to go into both the connect.js and insert-data.js files and manually insert the password from discord in the section where it says "PASSWORD GOES HERE!!!" where there is a Connection String (likely the 2nd or 3rd const variable).

Haven't tested it on my laptop yet, but you may need to use "npm install cors dotenv express mongodb" & "npm install --save-dev typescript @types/cors @types/express @types/node ts-node" in command prompt (doing this will at worst just waste your time for 5 seconds, it won't add any files that aren't on this github).

Given that your files are set up correctly and your command promt is located in the correct directory, you must first connect using "node connect.js". After successfully connecting, you must insert the data using "node insert-data.js" which should put in another entry into our cluster on MongoDB for the "GettingStarted" Database, the "people" Collection,  which most likely says "Alan Turing" assuming nothing was changed in the insert-data.js file.

For further information or help, this is what I used to set it up: https://www.mongodb.com/docs/atlas/
