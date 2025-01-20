<p align="center">
  <img height="100" height="auto" src="https://github.com/user-attachments/assets/6a46cc26-cc46-4437-bd93-41ed5b9aef57">
</p>

# OpenLedger Testnet

Official documentation:
>- [Validator setup instructions](https://openledger.gitbook.io/openledger)

Explorer:
>- [Explorer]()

### Minimum Hardware Requirements
 - 1x CPUs; the faster clock speed the better
 - 2GB RAM
 - 30GB of storage (SSD or NVME)

### Recommended Hardware Requirements 
 - 2x CPUs; the faster clock speed the better
 - 4GB RAM
 - 100GB of storage (SSD or NVME)

 - Ubuntu 24.04

Устанавливаем ноду:

``sudo apt update & sudo apt upgrade -y``

``sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev ubuntu-desktop xrdp docker.io -y``

``sudo systemctl start gdm``

``sudo adduser xrdp ssl-cert``

``sudo systemctl restart xrdp``

``sudo systemctl start docker``

``sudo systemctl enable docker``

``wget https://cdn.openledger.xyz/openledger-node-1.0.0-linux.zip``

``unzip openledger-node-1.0.0-linux.zip``

``sudo dpkg -i openledger-node-1.0.0.deb``
