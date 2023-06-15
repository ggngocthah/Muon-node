# Muon-node
Run testnet
Running the Node
Before installing a Muon node, one needs to install Docker. To do so, you can use Install Docker Engine, where you should first choose your server's operating system, and then follow the installation instructions. 
The first step is to get the Muon docker-compose.yml : 
curl -o docker-compose.yml https://raw.githubusercontent.com/muon-protocol/muon-node-js/testnet/docker-compose-pull.yml
Now the node can be run using the following command.
docker compose up -d
