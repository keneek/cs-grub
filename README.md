# 🌮 Blockchain Grub for Python-Leaning Developers
Cool information, articles, tools, and other internet finds for building python-based applications with a focus on blockchain integrations.

Note: popular languages for programming native chain or parachain (like Polkadot) requires knowledge of [Substrate](https://substrate.io/), [Rust](https://www.rust-lang.org/), [Node](https://nodejs.org/en/), and [Solidity](https://docs.soliditylang.org/en/v0.8.11/). We'll also be including those references when Python libraries are non-performant or not available.

## 👾 Web3 / Blockchain
### 💭 Organizations 
- [Web3 Foundation](https://web3.foundation/) - Research and development for organizations and teams building applications for web3.

### Substrate
Substrate is a modular framework for building custom blockchains built using Rust and Wasm. Very powerful runtime which includes **on chain upgrades**.

- [Intro to Substrate Crowdcast](https://www.youtube.com/watch?v=-6BBIr-DmI4) - Great video describing the Substrate framework and how to construct the runtime with pallets. 

### ⚪️ [Polkadot](polkadot.network)
A cross-chain network built on Substrate framework with powerful governance features and other features like parachains, etc.

- [Polkadot Governance](https://www.youtube.com/watch?v=VsZuDJMmVPY&t=24734s) - Dr. Gavin Wood presents the initial governance structure for Polkadot. (Video)

#### 🌕 [Moonbeam](https://docs.moonbeam.network/)
A Polkadot parachain which where Solidity contracts can deploy and operate. Moonbeam allows you to develop using the traditional tools from ETH, including `web3.py` etc. and interact on the chain with virtually the same source code used for an Etherium smart contract; but includes the benefit of the parachain features of Polkadot.
- [Moonbeam, Remix, OpenZeppelin](https://docs.moonbeam.network/builders/interact/oz-remix/) - Using OpenZeppelin Contracts and Remiz to Deploy To Moonbeam.

### 💠 [Etherium](https://ethereum.org/en/)
- [ERC20 Quick Video](https://www.youtube.com/watch?v=8rpir_ZSK1g) - Quick overview on configuring ERC20 tokens, adding supply, and sending to wallet.
- [Rent-to-Own Token on FastAPI](https://towardsdatascience.com/creating-an-ethereum-token-to-enable-a-decentralized-rent-to-own-network-cc3786cf1142) - Creating an Ethereum Token to Enable a Decentralized Rent-to-Own Network. 
- [Ganache](https://www.npmjs.com/package/ganache) - Ethereum simulator for developing applications.
- [User Contract](https://www.innoplexus.com/blog/how-to-develop-ethereum-contract-using-python-flask/) - A contract for persisting user data to chain. Note: uses some outdated libraries, but still a decent use case example.
- [Dev Setup for Etherium](https://levelup.gitconnected.com/dapps-development-for-python-developers-f52b32b54f28) - Good reference for a modern development setup.

## ⏩ [FastAPI](https://fastapi.tiangolo.com/)
Great way to develop back end architecture in Python. Fast in many ways.
- [User Management](https://github.com/fastapi-users/fastapi-users) - Quickly add registration and authentication for FastAPI projects.
- 🌱 [ODMantic](https://art049.github.io/odmantic/) - Async document mapper for MongoDB based on python type hints, built on pydantic for model definition and validation. Great shortcut tool for modeling mongo objects in a FastAPI application.

## 🎧 Other Cool Stuff
- [WakaTime](https://wakatime.com/) - Cool BI productivity tracker which tracks what IDE, project, language, etc is being worked on by the dev team in real time. Great looking analytics.
- [libp2p](https://libp2p.io/) - Run your network applications free from runtime and address services, independently of their location.
