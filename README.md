# Project Title

This is a simple solidity program to create a Token.

## Description

* This is a simple smart contract written in Solidity to create a Token.
* Here, the contract have public variables that store the details about the coin (Token Name, Token Abbrv., Total Supply). It is also having a mapping of addresses to balances (address => uint).
* The smart contract has a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the “sender” address by that amount.
* The contract is also having a burn function, which works the opposite of the mint function, as it will destroy tokens. It takes an address and value just like the mint functions and deducts the value from the total supply and from the balance of the “sender”, if the balance of "sender" is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Installing

* To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
* Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol). Then, copy opy and paste the code into the file.

### Executing program

* To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar then click on the "Compile MyToken.sol" button.
* Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar, then click on the "Deploy" button.
* Once the contract is deployed, you can interact with it by calling the Mint & Burn function. Also, you can check the balance by clicking on Balance button


## Authors

Mukesh Kumar 
Email: mks.mukesh11nov@gmail.com


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
