# testnet-binaries
Binaries for Testnet Nodes



# Quick Start: run a Testnet docker container #

Step 1: Start Freeflow router (one instance per server)
```
sudo docker run --name node -e moniker='Your_moniker' -e chain='Your_Chain' -e accountname='Your_account' -e api='your_api_token' -itd idepnetwork/testnet-denali
```

Then log into the Node container with
```
sudo docker exec -it node bash
```
# Docker Installation: #
if you don't have docker on your host, you can simply install it with
```
sudo curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh
```

# Contacts #
