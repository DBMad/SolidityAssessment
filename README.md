# Metacrafters: Solidity Smart Contract Token

This Solidity program is a simple smart contract, that demonstrates minting and burning custom tokens called "GIGA".

## REQUIREMENTS

    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

## Executing program

To run this program, you can use Remix, an online Solidity IDE. (https://remix.ethereum.org/)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to a compatible version (in this case I used pragma solidity >=0.7.0 <0.9.0), and then click on the "Compile Filename.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar.

For the demonstration:

  1. Minting tokens:
     - Provide the address (any valid address given from the IDE is valid) and the number of tokens that you want to mint.
     - Click "transact" to mint.

  2. Burning tokens:
     - Provide the address (any valid address given from the IDE is valid) and the number of tokens that you want to burn.
     - Click "transact" to burn.

## Author

Darryl B. Madarang 202110370@fit.edu.ph - FEU Institute of Technology
