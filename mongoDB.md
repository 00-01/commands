### Install the MongoDB 4.4 GPG key:
    wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -

### Add the source location for the MongoDB packages:
    echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list

### Download the package details for the MongoDB packages:
    sudo apt-get update

### Install MongoDB:
    sudo apt-get install -y mongodb-org











### 1. update and upgrade all existing packages by running the command below.
    sudo apt update
    sudo apt upgrade

### 2. install MongoDB server from the Raspbian repository.
    sudo apt install mongodb

### 3. enable and start the MongoDB service.
    sudo systemctl enable mongodb
    sudo systemctl start mongodb

### 4. run mongoDB
    mongo



    sudo apt-get install mongo-tools
    
    sudo apt-get install mongodb-clients
    
    sudo apt-get install mongodb-server
    
    sudo apt-get install mongodb
