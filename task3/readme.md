A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](https://github.com/AlexFedotovqq/nervos/blob/main/task3/smart.png)

The transaction hash from the console output (in text format).
```0x35104e0d80168e043e414fdbae8acec1818227ceab09e2dd6f9e7568f0356dfc```

The contract address that you called (in text format).
```0x30bd52fb02d441960912589A08d3a6cfC22c1Bb6```

The ABI for contract you made a call on (in text format).
```
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
