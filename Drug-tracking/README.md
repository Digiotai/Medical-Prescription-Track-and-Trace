-- From the drup-app folder, to remove any pre-existing Docker containers, run:

-- docker rm -f $(docker ps -aq)

-- Start up Hyperledger

-- sudo ./startFabric.sh

Now we install the required Node packages and register the Admin and User components of the network before starting the application.

-- npm install

-- node registerAdmin.js

-- node registerUser.js

-- node server.js

The client should launch on localhost:8000 in any web browser.
