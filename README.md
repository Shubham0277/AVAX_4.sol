# AVAX_4.sol

# DegenToken (DT) - ERC20 Token

## Overview

DegenToken is an ERC20 token built on the Ethereum blockchain. This smart contract provides basic functionality for minting, transferring, redeeming, and burning tokens. It also includes an event for tracking token redemptions.

## Features

- **Minting New Tokens:** Only the owner of the contract can mint new tokens. Minting is typically used to create the initial token supply or add tokens to the supply.

- **Transferring Tokens:** Token holders can transfer their tokens to other addresses using standard ERC20 transfer functions.

- **Redeeming Tokens:** Token holders can redeem tokens for prizes, with each prize costing a specified amount of DT tokens. Once redeemed, prizes are marked as claimed and cannot be redeemed again.

- **Burning Tokens:** Any token holder can burn their own tokens, reducing the total supply.

## Getting Started

To deploy and interact with this contract, you can follow these steps:

1. **Deployment:** Deploy this contract to the Ethereum blockchain using a tool like Remix, Hardhat, or Truffle. Ensure you have enough ETH in your deploying account for gas fees.

2. **Mint Tokens:** As the owner, you can mint new tokens using the `createTokens` function by specifying the recipient's address and the amount of tokens to mint.

3. **Transfer Tokens:** Token holders can transfer tokens to other addresses using the standard ERC20 transfer functions.

4. **Redeem Tokens:** Token holders can redeem tokens for prizes using the `redeemTokens` function by specifying the prize ID. Prizes have a specified cost in DT tokens.

5. **Burn Tokens:** Any token holder can burn their own tokens using the `destroyTokens` function.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


