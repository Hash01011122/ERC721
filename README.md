## OpenOcean
OpenOcean is NFT Marketplace contract built on ERC721 mainnet

## MyAwesomeArt
NFT contract built on ERC721 mainnet 

## Openzepplin Standards:
# <img src="logo.svg" alt="OpenZeppelin" height="40px">

[![NPM Package](https://img.shields.io/npm/v/@openzeppelin/contracts.svg)](https://www.npmjs.org/package/@openzeppelin/contracts)
[![Coverage Status](https://codecov.io/gh/OpenZeppelin/openzeppelin-contracts/graph/badge.svg)](https://codecov.io/gh/OpenZeppelin/openzeppelin-contracts)
[![GitPOAPs](https://public-api.gitpoap.io/v1/repo/OpenZeppelin/openzeppelin-contracts/badge)](https://www.gitpoap.io/gh/OpenZeppelin/openzeppelin-contracts)
[![Docs](https://img.shields.io/badge/docs-%F0%9F%93%84-yellow)](https://docs.openzeppelin.com/contracts)
[![Forum](https://img.shields.io/badge/forum-%F0%9F%92%AC-yellow)](https://docs.openzeppelin.com/contracts)

**A library for secure smart contract development.** Build on a solid foundation of community-vetted code.

 * Implementations of standards like [ERC20](https://docs.openzeppelin.com/contracts/erc20) and [ERC721](https://docs.openzeppelin.com/contracts/erc721).
 * Flexible [role-based permissioning](https://docs.openzeppelin.com/contracts/access-control) scheme.
 * Reusable [Solidity components](https://docs.openzeppelin.com/contracts/utilities) to build custom contracts and complex decentralized systems.

:mage: **Not sure how to get started?** Check out [Contracts Wizard](https://wizard.openzeppelin.com/) — an interactive smart contract generator.

:building_construction: **Want to scale your decentralized application?** Check out [OpenZeppelin Defender](https://openzeppelin.com/defender) — a secure platform for automating and monitoring your operations.

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
