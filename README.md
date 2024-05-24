# geth-cheat-sheet

# Docs
- https://geth.ethereum.org/docs


<br><br>

# Guides
- https://beincrypto.com/learn/how-to-install-geth-node/


<br><br>
<br><br>
_____________________________________
_____________________________________
<br><br>
<br><br>

# Install

## Docker
```
sudo docker pull ethereum/client-go
sudo docker run -it -p 30303:30303 ethereum/client-go
```

## Executuable
- https://geth.ethereum.org/downloads






<br><br>
<br><br>
_____________________________________
_____________________________________
<br><br>
<br><br>

# Consensus Clients
- Geth is an execution client. Historically, an execution client alone was enough to run a full Ethereum node. However, since Ethereum swapped from proof-of-work (PoW) to proof-of-stake (PoS) based consensus, Geth needs to be coupled to another piece of software called a "consensus client". There are five consensus clients available, all of which connect to Geth in the same way
- https://geth.ethereum.org/docs/getting-started/consensus-clients

## lodestar
- https://chainsafe.github.io/lodestar/

<br><br>

### Quickstart scripts
```shell
sudo apt install gnome-terminal
git clone https://github.com/ChainSafe/lodestar-quickstart.git

./setup.sh --dataDir sepolia-data --elClient nethermind --network sepolia --withTerminal "gnome-terminal --disable-factory --" --dockerWithSudo 
```
