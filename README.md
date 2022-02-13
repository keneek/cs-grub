# 🌮 Blockchain Grub for Python-Leaning Developers
Excellent information, articles, tools, and other internet finds for building python-based applications focused on blockchain integrations.

Note: popular languages for programming native chain or para chain (like Polkadot) requires knowledge of [Substrate](https://substrate.io/), [Rust](https://www.rust-lang.org/), [Node](https://nodejs.org/en/), and [Solidity](https://docs.soliditylang.org/en/v0.8.11/). We'll also include those references when Python libraries are non-performant or unavailable.

## 👾 Web3 / Blockchain

### 👩‍🏭 [Rust](https://www.rust-lang.org/)
Substrate sits on Rust, so implementing Substrate requires working knowledge of the language. Below are some resources to get things going.

- [The Rust Programming Language Book](https://doc.rust-lang.org/book/) - Read the first three chapters before diving into Substrate if you are unfamiliar with Rust.

### _ [Substrate](https://substrate.io/)
The Substrate framework is a modular framework for custom blockchains built using Rust and Wasm. Very powerful runtime, which includes **on-chain upgrades** (the run time source is stored on chain and can be updated on chain).

- [Intro to Substrate Crowdcast](https://www.youtube.com/watch?v=-6BBIr-DmI4) - Great video describing the Substrate framework and constructing the runtime with pallets.
- 
- [Substrate Recipes Workshop](https://www.youtube.com/watch?v=KVJIWxZSNHQ) - Learn to Build a Custom Blockchain

### ⚪️ [Polkadot](polkadot.network)
Polkadot is a cross-chain network built on the Substrate framework with powerful governance features and other features like para chains, etc.

- [Polkadot Governance](https://www.youtube.com/watch?v=VsZuDJMmVPY&t=24734s) - Dr. Gavin Wood presents the initial governance structure for Polkadot. (Video)

#### 🌕 [Moonbeam](https://docs.moonbeam.network/)
A Polkadot para chain which where Solidity contracts can deploy and operate. Moonbeam allows you to develop using the traditional tools from ETH, including web3.py, etc., and interact on the chain with virtually the same source code used for an Ethereum smart contract, but includes the benefit of the para chain features of Polkadot.
- [Moonbeam, Remix, OpenZeppelin](https://docs.moonbeam.network/builders/interact/oz-remix/) - Using OpenZeppelin Contracts and Remiz to Deploy To Moonbeam.

### 💠 [Etherium](https://ethereum.org/en/)
- [ERC20 Quick Video](https://www.youtube.com/watch?v=8rpir_ZSK1g) - Quick overview on configuring ERC20 tokens, adding supply, and sending to a wallet.
- [Ganache](https://www.npmjs.com/package/ganache) is an Ethereum simulator for developing applications.
- [User Contract](https://www.innoplexus.com/blog/how-to-develop-ethereum-contract-using-python-flask/) - A contract for persisting user data to chain. Note: uses some outdated libraries, but still a decent use case example.
- [Dev Setup for Etherium](https://levelup.gitconnected.com/dapps-development-for-python-developers-f52b32b54f28) is an excellent reference for setting up a modern development setup.

### 💭 Blockchain Organizations 
#### Technical Standards and Development
##### [Web3 Foundation](https://web3.foundation/) 
Web3 Foundation contributes to and funds research and development in web3 technology.

#### Architecture, Engineering, and Construction
##### [Construction Blockchain Constortium](https://www.linkedin.com/company/construction-blockchain/)
This group supports research and development in blockchain technology and services for the industry.

- 📄 White Paper: [Blockchain & Construction Cashflow](https://static1.squarespace.com/static/58b6047520099e545622d498/t/5fdb6089ad5a0604f7feaf5e/1608212649913/CBC2020-WP1_Cashflow.pdf) 

- 📄 White Paper: [Integrating Ethereum with Autodesk Forge](chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/https://static1.squarespace.com/static/58b6047520099e545622d498/t/5ef5fbbfe2d6737ff9ecb2f0/1593179078269/CBC-CS1_AutodeskForge_PDF-Version.pdf) - White Paper

#### [BuildCoin](https://www.buildcoinfoundation.org/buildcoin-ecosystem/)
An organization with proposed engines and protocols for the construction industry. Nonprofit.

## ⏩ [FastAPI](https://fastapi.tiangolo.com/)
Great way to develop back end architecture in Python. Fast in many ways.

- [User Management](https://github.com/fastapi-users/fastapi-users) - Quickly add registration and authentication for FastAPI projects.
- 🌱 [ODMantic](https://art049.github.io/odmantic/) - Async document mapper for MongoDB based on python type hints, built on pydantic for model definition and validation. Great shortcut tool for modeling mongo objects in a FastAPI application.
- [Rent-to-Own Token on FastAPI](https://towardsdatascience.com/creating-an-ethereum-token-to-enable-a-decentralized-rent-to-own-network-cc3786cf1142) - Creating an Ethereum Token to Enable a Decentralized Rent-to-Own Network. 

## 🎧 Other Cool Stuff
- [WakaTime](https://wakatime.com/) - Cool BI productivity tracker tracks what IDE, project, language, etc., is being worked on by the dev team in real-time. Great looking analytics.
- [libp2p](https://libp2p.io/) - Run your network applications free from runtime and address services, independently of their location.
