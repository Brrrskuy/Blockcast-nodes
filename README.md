# Blockcast Nodes

- Buy VPS di : [t.me/skuycloud](t.me/skuycloud)
- Trakteer buat buy Kopi : https://trakteer.id/brrrskuy/tip `<---`

# Install Docker & Dependencies
Install Packages
```
sudo apt-get update && sudo apt-get upgrade -y sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y 
```
Install Docker
```
curl -fsSL https://get.docker.com | sh
```
# Register Nodes
register block cast nodes dashboard [https://app.blockcast.network](https://app.blockcast.network?referral-code=z2ayHK)
# Clone Repository 
```
git clone https://github.com/Blockcast/beacon-docker-compose.git
cd Blockcast
```
# Run Nodes
Pulls the image associated with the service defined in the `compose.yaml` file:
```
docker compose pull
```
Start Blockcast services:
```
docker compose up -d
```
Get Node info by running:
```
docker compose exec blockcastd blockcastd init
```
Register using the provided URL or by using the Hardware ID and Challenge Key manually.

Get location:
```
sudo install jq
curl -s https://ipinfo.io | jq '.city, .region, .country, .loc'
```
# Copy Register URL to Website
![image](https://github.com/user-attachments/assets/8ab72991-184f-4c26-aec4-a932294a7e33)

`And you see Online in Dashboard Nodes`
