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