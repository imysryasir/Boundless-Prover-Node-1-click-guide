# System Requirements

## CPU	16 cores
## RAM	32 GB
## GPU	NVIDIA GPU with >= 8GB of VRAM
## Disk/Storage	200 GB SSD
## Operating System	Ubuntu 22.04


# Necessities

## Claim USDC faucets here : https://faucet.circle.com/

## Get RPC for the network : https://dashboard.alchemy.com/chains
### Note : If you want to run this prover on eth-sepolia then u need to get eth sepolia rpc, if base-sepolia then base-sepoia rpc or if base mainnet then u need to get base mainnet rpc

# Installation Of the Node

## Install Curl if not installed before
```
apt update && apt install -y curl
```

## Deploy the Prover Node
```
[ -f boundless.sh ] && rm boundless.sh; curl -o boundless.sh https://raw.githubusercontent.com/imysryasir/Boundless-Prover-Node-1-click-guide/refs/heads/main/main-script.sh && chmod +x boundless.sh && . ./boundless.sh
```

## See Logs to check the Status of the Node


# Essantial commands👇

## If you need to Stop the Node Run any of the Specific Commands given below for different Chains
### For base-mainnet
```
just broker down ./.env.broker.base
```

### For eth-sepolia
```
just broker down ./.env.broker.eth-sepolia
```

### For base-sepolia
```
just broker down ./.env.broker.base-sepolia
```

## To Start Broker Again 👇
### For base-mainnet
```
just broker up ./.env.broker.base
```

### For eth-sepolia
```
just broker up ./.env.broker.eth-sepolia
```

### For base-sepolia
```
just broker up ./.env.broker.base-sepolia
```

# Note : Incentives for provers are not active for this phase.

## 📬 Video Guide: https://youtube.com/@KindCrypto
## 📢 TG Alpha Drops & Updates : https://t.me/kind_cr
## 📍 X : https://x.com/armaanbhat201
