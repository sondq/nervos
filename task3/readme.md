## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](1.png)
## 2. The transaction hash from the console output (in text format).
0xeb3c196290ebd0b7b8707e0d94cb54b33ecf80caa41f878e8db2db86e833755c
## 3. The contract address that you called (in text format).
0x61f85Dd3E5CEB97afE58261806cB911a4436d15A
## 4. The ABI for contract you made a call on (in text format).
```json
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
```