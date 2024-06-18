# Project-Create-a-Token

This Solidity program demonstrates essential programming concepts including declaring variables, using mappings as reference types, creating functions, and performing conditional expressions. This program, designed to illustrate the abilities I've gained from metacrafters' fundamental Ethereum course, reflects my first attempt into blockchain development, with an emphasis on developing a small Token system to use these new learnings in a practical situation.
## Description

This program creates MyToken, a simple smart contract designed for maintaining a digital currency on the Ethereum network. The contract defines basic parameters such as the tokenName, abbreviation (tokenAbbrv), and total quantity of tokens (totalSupply), which are all set as public variables for easy access. It includes a mapping to monitor specific address balances, ensuring that each transaction accurately updates these balances. Functionality is given in two main ways: mint and burn. The mint function creates and allocates tokens to a given address, raising both the overall supply and the address's balance. The burn function is meant to eliminate tokens, lowering them from both the overall supply and the balance of the given address, with protections to avoid burning more than the address holds. 
## Getting Started

### Executing program

To execute this program, you may use Remix, an online Solidity IDE; to get started, go visit https://remix.ethereum.org/.

Once on the Remix website, click the "+" symbol in the left-hand sidebar to create a new file. Save the file as HelloWorld.sol. Copy and paste the code below into the file.

```javascript
// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;

contract MyToken {

    // public variables here

    // mapping variable here

    // mint function

    // burn function

}

```


To compile the code, select the "Solidity Compiler" tab from the left sidebar. Set the "Compiler" option to "0.8.4" (or any suitable version), then click the "Compile HelloWorld.sol" button.

Once the code has been built, you can deploy the contract by selecting the "Deploy & Run Transactions" tab in the left-hand sidebar. Choose the "HelloWorld" contract from the dropdown menu, and then click the "Deploy" button.

Once the contract has been deployed, you can interact with it by using the sayHello method. Click the "HelloWorld" contract in the left-hand sidebar, followed by the "sayHello" function. Finally, click the "transact" button to call the function and get the "Hello World!" message.
## Authors

Metacrafter Student Harley Ramone Tesorero
[@harleyramonee](https://twitter.com/harleyramonee)


## License

This project is licensed under the Harley Ramone Tesorero License - see the LICENSE.md file for details
