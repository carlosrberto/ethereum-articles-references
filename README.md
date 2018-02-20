# Ethereum articles and references

## Installation instructions for Mac
- https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Mac

## Setup private blockchain

Create account
```
geth --datadir ~/.ethereum_private account new
```

Create private blockchain
```
geth --datadir ~/.ethereum_private init ~/dev/genesis.json
```

Initialize
```
geth --fast --cache 512 --ipcpath ~/Library/Ethereum/geth.ipc --networkid 1995 --datadir ~/.ethereum_private
``` 

Attach terminal
```
geth attach ipc_url
```

Start mining
```
geth --fast --cache 512 --mine --minerthreads=1  --ipcpath ~/Library/Ethereum/geth.ipc --networkid 1995 --datadir ~/.ethereum_private
```

## geth

### Private blockchain
- Installing `geth` - https://ethereum.org/cli
- Genesis block - https://github.com/ethereum/go-ethereum/wiki/Private-network
- Adding ether to account - https://ethereum.stackexchange.com/questions/125/how-do-i-set-up-a-private-ethereum-network/16306#16306
- Sending ether - https://github.com/chafey/ethereum-private-network#send-ether-from-one-account-to-another
- Private miner - https://github.com/ethereum/go-ethereum/wiki/Private-network#running-a-private-miner

## Ethereum concepts
- [What is the "Gas" in Ethereum?](https://www.cryptocompare.com/coins/guides/what-is-the-gas-in-ethereum/)

## Ethereum tutorials
- [Create your own Crypto Currency with Ethereum](https://www.ethereum.org/token)


## Smart Contracts (Solididy)
### Introduction
- Intro to Smart Contracts - http://solidity.readthedocs.io/en/latest/introduction-to-smart-contracts.html
- Basic intro - https://learnxinyminutes.com/docs/solidity/
- Introduction to Solidity - https://blockgeeks.com/introduction-to-solidity-part-1/
- Learning Solidity : Tutorial 1 The Basics - https://www.youtube.com/watch?v=v_hU0jPtLto&t=5s
- [Build Your First Ethereum Smart Contract](https://codeburst.io/build-your-first-ethereum-smart-contract-with-solidity-tutorial-94171d6b1c4b)
- [First Contract Tutorial](https://github.com/ethereum/go-ethereum/wiki/Contract-Tutorial)

### Examples
- https://github.com/mbeaudru/ethereum-todolist/blob/master/contracts/TodoList.sol

### Tools  
- Online compiler (JSFiddle like) https://ethfiddle.com/
- Remix - Solidity IDE - https://remix.ethereum.org/
