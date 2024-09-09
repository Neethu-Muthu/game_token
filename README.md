Verification Link: 
https://sepolia.etherscan.io/verifyContract-solc-multiple?a=0x02ca8F74eBE1801ed07DD5f0cC130Ab2a40A2F1A&c=v0.8.23%2bcommit.f704f362&lictype=3

# Game Token (GT)
Game Token (GT) is an ERC-20 token designed for in-game transactions and reward systems. This smart contract is deployed on the Sepolia Testnet and allows the admin to mint tokens for users within the game environment.

## Contract Details
Token Name: Game
Token Symbol: GT
Total Supply: 100 GT initially minted to the admin's address.
Contract Type: ERC-20 Token
Network: Sepolia Testnet

## Features
Minting:

The admin has the ability to mint additional tokens using the safeMint function.
Only the admin can mint tokens, ensuring controlled token supply within the game.
Admin Role:

The admin is the address that deployed the contract.
Only the admin can invoke certain functions like safeMint.
ERC-20 Standard:

The token follows the ERC-20 standard, ensuring compatibility with wallets and exchanges that support ERC-20 tokens.
## Functions
constructor()
Initializes the token with the name "Game" and symbol "GT".
Mints 100 GT to the admin address upon deployment.
Sets the deployer as the admin.
safeMint(address to, uint value)
Mints the specified number of tokens (value) to the provided address (to).
Can only be called by the admin.
onlyAdmin
A modifier that restricts access to admin-only functions.

## Use Case: Game Tournament Prize Pool
## Overview:
Game Token (GT) can be used as a prize pool for competitive gaming tournaments. This encourages participation by providing a tangible reward for players or teams who win tournaments or complete competitive challenges.

## Use Case:
In decentralized gaming ecosystems, GT can serve as the prize for winning teams or top players in tournaments. Organizers can distribute GT tokens as winnings to players after each competition.

## Example:
A game organizes a weekly multiplayer tournament, where players compete in various challenges. The top 3 players with the highest scores receive GT tokens as part of the prize pool.

### How it works:
The admin can mint a fixed number of tokens using the safeMint function to create the tournament prize pool.
Tokens are distributed automatically to winning addresses upon completion of the tournament or manually by the admin.
Players can use their winnings for in-game purchases, upgrades, or trade them on decentralized exchanges.
Benefits:
Competitive Incentive: Players are motivated to improve their skills to earn tokens.
Community Engagement: Regular tournaments foster a strong gaming community and increase player retention.
Cross-Platform Prizes: GT tokens can be traded or used across different gaming platforms, expanding their utility beyond a single game.
