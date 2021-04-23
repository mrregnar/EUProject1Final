You must have MongoDB installed to play this game. MongoD needs to running in a terminal window or as a service on your system.

For instructions on how to install MongoDB on all platforms see this link: https://docs.mongodb.com/manual/installation/

Run this command to import into a local installation of mongodb from the same directory as this README.md file is located:
mongoimport --db UnknownOrigins -c scenes --file exportUnkOri.json

From a terminal window in the same directory that the server.js is found, run these commands:

npm install
npm start

browse to http://localhost:4000 to start game



