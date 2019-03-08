# simpleDatabaseApp
This is a simplified way of creating a node.js integrated mysql database in which usernames and passwords are stored from a website. I used this website in order to create this repository: https://hackernoon.com/setting-up-node-js-with-a-database-part-1-3f2461bdd77f  (full credit to them- this project is just for me to learn how to use node.js and mysql together.)


!!!Make sure you download node.js before cloning; 
Type this into the directory as well to download NVM:
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash

I also used homebrew to install mysql. Here is the commands for that:

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install mysql

brew services start mysql

mysqladmin -u root password 'password'


Now you're all ready and set. Let's go!
