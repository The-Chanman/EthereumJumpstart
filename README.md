# EthereumJumpstart
A starting point for those who want to write smart contracts

This will be using Solidity as our main language. Solidity is quite similar to Javascript in style.
We will be using the Truffle Framework on a Ethereumjs TestRPC.

We will be using geth to attach to the TestRPC and interact with it.

# First things first
Download if you don't have it
[NodeJS](https://www.google.com "NodeJS Homepage") &
[Homebrew](https://brew.sh)

Next install [geth](https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Mac "Geth Install Instructions") using Homebrew

Next use `npm install`
Then get started with [Truffle](http://truffleframework.com/docs/getting_started/project)

To interact wtih your TestRPC with geth open up another terminal window and type `geth attach http://localhost:8545`

Then use web3 commands to query the TestRPC
