# JuniperHomework

This is a simple client-server application with Docker. It supports multiple connections between the client and the server and it sends string messages
between them using send(), respectively recv() API calls. 

Please run the below commands in the terminal:
git clone https://github.com/DianaDedinoiu/JuniperHomework.git
docker-compose build
docker-compose up


# How to kill a process that owns a particular port

1. sudo netstat -ap | grep:<port_np> # the output will show the process
2. kill <pid>	

# How to chapture the traffic on an intf(to check the 3-way handshake between the client and the server ):

sudo tshark -i <interface_name> 'tcp port X' (X is the port given as an argument in Docker-compose.yml)' 

# Git commands

git remote add origin https://github.com/NdagiStanley/new-repository.git
git branch -M main
git push -u origin main
git add .
git commit -m "Commit message"
git push origin main


# resources

1. https://realpython.com
2. https://www.freecodecamp.org



