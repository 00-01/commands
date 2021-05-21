## mongo v2.4
    sudo apt update
    sudo apt upgrade
    sudo apt install mongodb
    sudo systemctl enable mongodb
    sudo systemctl start mongodb
    mongo
    
## config network
    sudo nano /etc/mongodb.conf
bind_ip = 0.0.0.0
port = 27017

## python pip
    sudo pip3 install pymongo~=3.11.4
