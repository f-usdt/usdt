# Flash USDT (USDT) Smart Contract
A Solidity implementation of the USDT (USDT) TRC20 token.

## Features
- **Name**: USDT
- **Symbol**: USDT
- **Decimals**: 6
- **Total Supply**: 100 Million USDT
- **Functionality**: Mintable and burnable

## Technical Details
This implementation uses OpenZeppelin's TRC20, TRC20Burnable, and Ownable contracts as a foundation. The contract allows:
- The owner to mint new tokens
- Any token holder to burn their tokens
- A fixed decimal of 6

## Dependencies
- OpenZeppelin Contracts v5.0.0 
