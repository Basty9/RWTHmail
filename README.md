# RWTH MAIL CLIENT APP
Mail Browser Client as Snap or .deb

change the link to your email browser link in index.js
adjust icon in ./resources/

# How to compile

https://www.electron.build/#quick-setup-guide

### Linux

Works also with NPM!

sudo apt install npm

// choose version 14 or higher, tested only for version 14

curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -

sudo apt-get install -y nodejs

// go to folder RWTHmail

npm install electron-builder

npm run dist