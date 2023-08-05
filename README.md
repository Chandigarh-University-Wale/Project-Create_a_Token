# Project-Create_a_Token

This is the final assessment/project of the course - ETH PROOF: Beginner EVM Course. In this, we create our first token. "Well, not really, but kinda!"

## Description

This program is a contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has two functions namely 'mint' and 'burn'.
The mint function takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the “sender” address by that amount.
The burn function works the opposite of the mint function, as it destroys tokens. It takes an address and value just like the mint function. It then deducts the value from the total supply and from the balance of the “sender”.

## Getting Started

### Executing program

We can use Remix, an online Solidity IDE at https://remix.ethereum.org/. We can create a new file by clicking on the "+" icon in the left-hand sidebar. Also, we can save the file with a .sol extension.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile final_assessment.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "MyToken" contract in the left-hand sidebar, and then click on the respective functions to do the related task. Then, the values of the parameters can be inputted. Finally, click on the "transact" button to execute the function and retrieve the output message.

## Authors

Contributors names and contact info

Harpreet Singh

[My X Handle](https://twitter.com/Harpree07603234)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
