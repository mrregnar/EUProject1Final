You must have MongoDB installed to play this game. MongoD needs to running in a terminal window or as a service on your system.

For instructions on how to install MongoDB on all platforms see this link: https://docs.mongodb.com/manual/installation/

In the root folder of the git clone you will find a file called exportUnkOri.json.delext. Rename it too: exportUnkOri.json

Run this command to import into a local installation of mongodb from the same directory as this README.md file is located:
mongoimport --db UnknownOrigins -c scenes --file exportUnkOri.json

*** Do not run this... Shown only here as an example
mongoexport --db UnknownOrigins -c scenes --out exportUnkOri.json

From a terminal window in the same directory that the server.js is found, run these commands:

npm install
npm start

browse to http://localhost:4000 to start game



