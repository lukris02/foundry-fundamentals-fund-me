# Foundry Fundamentals Fund Me
## Description
A decentralized crowdfunding contract. Users can deposit funds into the `FundMe.sol` contract. A minimum deposit of $5 USD is required. The contract owner has the ability to withdraw all deposited funds.

## Topics
Solidity, Foundry, Chainlink Price Feeds

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

## Quickstart

```
git clone https://github.com/lukris02/foundry-fundamentals-fund-me
cd foundry-fundamentals-fund-me
make
```

## Deploy

```
forge script script/DeployFundMe.s.sol
```

## Testing

```
forge test
```
