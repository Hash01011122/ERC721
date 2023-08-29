## OpenOcean
OpenOcean is NFT Marketplace contract built on ERC721 mainnet

## MyAwesomeArt
NFT contract built on ERC721 mainnet 

## Openzepplin Standards:
# <img src="logo.svg" alt="OpenZeppelin" height="40px">
- Both contracts are developed with Openzeppelin Standards

## Overview

### Installation

```
$ npm install @openzeppelin/contracts
```

OpenZeppelin Contracts features a [stable API](https://docs.openzeppelin.com/contracts/releases-stability#api-stability), which means that your contracts won't break unexpectedly when upgrading to a newer minor version.

An alternative to npm is to use the GitHub repository (`openzeppelin/openzeppelin-contracts`) to retrieve the contracts. When doing this, make sure to specify the tag for a release such as `v4.5.0`, instead of using the `master` branch.

### Usage

Once installed, you can use the contracts in the library by importing them:

```solidity
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC721/ERC721.sol";

contract MyCollectible is ERC721 {
    constructor() ERC721("MyCollectible", "MCO") {
    }
}
```

_If you're new to smart contract development, head to [Developing Smart Contracts](https://docs.openzeppelin.com/learn/developing-smart-contracts) to learn about creating a new project and compiling your contracts._

To keep your system secure, you should **always** use the installed code as-is, and neither copy-paste it from online sources nor modify it yourself. The library is designed so that only the contracts and functions you use are deployed, so you don't need to worry about it needlessly increasing gas costs.
