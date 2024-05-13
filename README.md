# ETH-AVAX Token Functionality 
Hello Everyone!! This is the overview. 

This Solidity smart contract, named MyToken, is a basic ERC20 token implementation facilitating minting, burning, and token transfers. It inherits functionalities from the OpenZeppelin ERC20 contract.

## Prerequisites
Solidity compiler version 0.8.25
OpenZeppelin contracts library


## How to Use
Follow these steps to utilize this smart contract:

* Deploy the MyToken contract, specifying the desired name, symbol, and initial supply.
* Employ the mint function to create tokens and allocate them.
* Utilize the burn function to eliminate tokens.
* Employ the standard ERC20 transfer function to move tokens between addresses.


## Contract Components
* MyToken: Primary contract implementing ERC20 token features.
* constructor: Initializes the token with a name, symbol, and initial supply.
* onlyOwner: Modifier restricting access to specific functions solely to the contract owner.
* mint: Function to create new tokens, exclusively accessible by the contract owner.
* burn: Function to eliminate tokens.
* transfer: Overridden ERC20 function for transferring tokens between addresses.
