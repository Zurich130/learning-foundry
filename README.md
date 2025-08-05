# FundMe - A Solidity Crowdfunding Contract

![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-%23FFD43B.svg?style=for-the-badge)

A decentralized crowdfunding contract built with Solidity and Foundry that allows users to send ETH with a minimum USD value requirement.

## Features

- Accepts ETH contributions with a minimum USD value (currently $5)
- Tracks all funders and their contributions
- Only contract owner can withdraw funds
- Uses Chainlink Price Feeds for ETH/USD conversion
- Optimized for gas efficiency with:
  - Immutable variables
  - Constant variables
  - Cheaper withdrawal function
- Supports fallback and receive functions

## Prerequisites

- [Foundry](https://getfoundry.sh/)
- Node.js (for zkSync development)
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/fund-me.git
cd fund-me