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
