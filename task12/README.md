Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call


A screenshot of the accounts you created (account list) in ckb-cli.
<img width="692" alt="Account list" src="https://user-images.githubusercontent.com/44841666/130359535-ef0ba3f0-4591-4ec3-87b2-03b7743b0c7a.png">


A link to the Layer 1 address you funded on the Testnet Explorer:
https://explorer.nervos.org/aggron/address/ckt1qyqta8lp9j5za7vympry3dlr87lttge2cwdsnnfs90

<img width="902" alt="Deposit" src="https://user-images.githubusercontent.com/44841666/130360360-ea33f8ef-334a-4aad-a5bd-a244570e0265.png">

<img width="705" alt="Call" src="https://user-images.githubusercontent.com/44841666/130360824-1c74a7af-c7b3-4335-8409-bd33831407da.png">

The transaction hash of the "Contract call":
0xe6438239c582875f966cc96f9859f3fb1bd940c721d3f3b5c54fd6977a9d10cc

The contract address that you called (in text format):
0x62A0a95A09a5bD1589C4F93C6be6Fc74eDfA668a


The ABI for contract you made a call on (in text format):
[
  {
    "inputs": [],
    "stateMutability": "payable",
    "type": "constructor"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "x",
        "type": "uint256"
      }
    ],
    "name": "set",
    "outputs": [],
    "stateMutability": "payable",
    "type": "function"
  },
  {
    "inputs": [],
    "name": "get",
    "outputs": [
      {
        "internalType": "uint256",
        "name": "",
        "type": "uint256"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  }
]

Your Tron address (in text format):
TFqKSpXJcFYbEYKHZmWz6sGbNvTnrM7na3
