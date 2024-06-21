# MyToken

MyToken is a simple ERC-20-like token contract implemented in Solidity. It allows for minting and burning of tokens, as well as tracking balances of different addresses.

## Contract Details

- **Token Name**: The name of the token.
- **Token Abbreviation**: The abbreviation of the token.
- **Total Supply**: The total supply of the token.

## Features

- Public variables to store the details of the token (name, abbreviation, total supply).
- Mapping to track balances of addresses.
- `mint` function to increase the total supply and the balance of a specified address.
- `burn` function to decrease the total supply and the balance of a specified address, with checks to ensure sufficient balance.

## Functions

### mint

```solidity
function mint(address _to, uint256 _value) public
Increases the total supply by the specified value and credits the specified address with the same amount.

_to: The address to which the tokens will be minted.
_value: The amount of tokens to mint.
function burn(address _from, uint256 _value) public
Decreases the total supply by the specified value and debits the specified address with the same amount, ensuring the address has enough balance to burn.

_from: The address from which the tokens will be burned.
_value: The amount of tokens to burn.


Usage:
Deploy the contract: Deploy the MyToken contract to the Ethereum blockchain.

Mint tokens: Call the mint function with the desired address and value to mint new tokens.

Burn tokens: Call the burn function with the desired address and value to burn tokens, ensuring the address has sufficient balance.


