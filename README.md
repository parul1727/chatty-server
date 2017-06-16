# CHAT
This is a chat application that can be used for local usage in a small network. It creates a local server and people connected to the network can do a group or private chat. The chat also gives facilites to block someone from pinging unnecessarily.

# Instructions to run
Clone the project
git clone https://github.com/parul1727/chat_server.git

### DataBase - Mongo
* Check if mongodb service is running in your machine else start the service.
* steps to run mongodb service

    1) Download from http://www.mongodb.org/downloads
    2) Install .msi file in folder C:\mongodb
    3) Create data, data\db, log directories and mongo.config file under C:\mongodb.
    4) Add the following lines in "mongo.config" file
            dbpath=C:\mongodb\data\db\
            logpath=C:\mongodb\log\mongo.log
    5) Start server :
            mongod.exe --config="C:\mongodb\mongo.config"


### Server
* You need to have node and npm installed in your machine.
* open up your teminal or command prompt go to the directory `chat`
* Do install all dependencies using  
   `npm install`
   `npm install -g nodemon`
   `npm start`
Your server will be setup and ready for use.

### UI
* Go to browser and type `localhost:8080` in place of url.
* Register user by giving basic details.
* Login from the same screen.  
`Note: Handle should be unique for every user.`
