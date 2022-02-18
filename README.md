# 🌮 Web3 Grub for Developers
Excellent information, articles, tools, and other internet finds for building applications focused on blockchain integrations. This list favors python when possible.

If you are just starting this journey, be prepared to take on [Solidity](https://docs.soliditylang.org/en/v0.8.11/) and [Rust](https://www.rust-lang.org/). It may be best to start in Solidity and familiarize yourself with smart contracts on the Ethereum network. Many of those tools will be applicable if you decide to move from contract development into chain dev with [Substrate](https://substrate.io/). 

*Note: popular languages for programming native chain or para chain (like Polkadot) requires knowledge of [Substrate](https://substrate.io/), [Rust](https://www.rust-lang.org/), [Node](https://nodejs.org/en/), and [Solidity](https://docs.soliditylang.org/en/v0.8.11/). That said, this list is python-leaning and includes references when Python packages when unavailable (eg `web3.py`, `FastAPI`, etc).*

## 👾 Fundamentals for Web3

### 📺 [Introduction to Blockchain](https://www.youtube.com/channel/UCsYYksPHiGqXHPoHI-fm5sg)
If you already understand these concepts, just skip to the lists below. These are a few videos from the Youtube channel [Whiteboard Crypto](https://www.youtube.com/channel/UCsYYksPHiGqXHPoHI-fm5sg) which has easy-to-understand explainer videos about the technology.
- [What is a Blockchain?](https://www.youtube.com/watch?v=kHybf1aC-jE) Explanation of blocks, and how they are chained together.
- [What is a Wallet?](https://www.youtube.com/watch?v=SQyg9pyJ1Ac) Quick explainer about wallets
- [What is Ethereum Gas?](https://www.youtube.com/watch?v=3ehaSqwUZ0s) Explainer for Ethereum Gas
- [Crypto Coin vs Token?](https://www.youtube.com/watch?v=422HORNUfkU) Understanding tokens as more than just money.
- [What is Polkadot?](https://www.youtube.com/watch?v=YlAdEQp6ekM&feature=youtu.be) DOT explained with animations.
- [Blockchain Consensus Mechanisms](https://tokens-economy.gitbook.io/consensus/) Tokens economy information regarding the kinds of consensus methods known.


### 💠 [Etherium](https://ethereum.org/en/)
#### 🧰 Tools
- [Solidity](https://docs.soliditylang.org/en/v0.8.11/) Solidity is an object-oriented, high-level lanugage for implimenting smart contracts.
- [Ganache](https://www.npmjs.com/package/ganache) is an Ethereum simulator for developing applications.
- [openzeppelin](https://openzeppelin.com/) has a library of open sourced, battle-tested Solidity contracts with dev tools to help understand how to compile, deploy, and test them.

#### 🧑🏻‍🏫 Useful Tutorials
- [Dev Setup for Etherium](https://levelup.gitconnected.com/dapps-development-for-python-developers-f52b32b54f28) is an excellent reference for setting up a modern development setup.
- [ERC20](https://www.youtube.com/watch?v=8rpir_ZSK1g) Quick overview on configuring ERC20 tokens, adding supply, and sending to a wallet.
- [User Contract](https://www.innoplexus.com/blog/how-to-develop-ethereum-contract-using-python-flask/) A contract for persisting user data to chain. Note: uses some outdated libraries, but still a decent use case example.


### 👩‍🏭 [Rust](https://www.rust-lang.org/)
Substrate sits on Rust, so implementing Substrate requires working knowledge of the language. Below are some resources to get things going.

- [The Rust Programming Language Book](https://doc.rust-lang.org/book/) Read the first three chapters before diving into Substrate if you are unfamiliar with Rust.

### ⚗️ [Substrate_](https://substrate.io/)
The Substrate framework is a modular framework for custom blockchains built using Rust and Wasm. Very powerful runtime, which includes **on-chain upgrades** (the run time source is stored on chain and can be updated on chain).

- [Intro to Substrate](https://www.youtube.com/watch?v=-6BBIr-DmI4) Great crowdcast describing the Substrate framework and constructing the runtime with pallets.
- [Official Substrate Tutorials](https://docs.substrate.io/tutorials/v3/) is a series of the official Substrate tutorials with great examples and use cases.
- [Substrate Recipes Workshop](https://www.youtube.com/watch?v=KVJIWxZSNHQ) Learn to Build a Custom Blockchain
- [Substrate How-to Guides](https://docs.substrate.io/how-to-guides/v3/) Includes guidance on building recipes, other exmaples.
- [Substrate Recipes](https://substrate.recipes/) a hands-on cookbook for aspiring blockchain chefs, by [Josh Orndorff](https://github.com/JoshOrndorff). Josh Orndorff also published a repo of example [recipes](https://github.com/JoshOrndorff/recipes).
- [Substrate Developer Hub](https://github.com/substrate-developer-hub) Repo's and tools for the dev community.
- [Substrate Community Questions](https://substrate.stackexchange.com/) StackExchange account targeted toward answering questions about Substrate.

### 🖋 [ink](https://github.com/paritytech/ink)!
Ink is Parity's contract writing language for Substrate based block chain.


### ⚪️ [Polkadot](https://www.polkadot.network)
Polkadot is a cross-chain network built on the Substrate framework with powerful governance features and other features like para chains, etc.

- [What is Polkadot?](https://www.youtube.com/watch?v=YlAdEQp6ekM&feature=youtu.be) DOT explained with animations.
- [Polkadot Governance](https://www.youtube.com/watch?v=VsZuDJMmVPY&t=24734s) Dr. Gavin Wood presents the initial governance structure for Polkadot. (Video)
- [Polkadot Paper](https://polkadot.network/PolkaDotPaper.pdf) Dr. Gavin Wood's `Polkadot Paper` about Polkadot introducing para chains and other new ideas for governance, proof of stake (*nominated proof of stake*), and other novel ideas about exensible block chain future.

#### 🌕 [Moonbeam](https://docs.moonbeam.network/)
A Polkadot para chain which where Solidity contracts can deploy and operate. Moonbeam allows you to develop using the traditional tools from ETH, including web3.py, etc., and interact on the chain with virtually the same source code used for an Ethereum smart contract, but includes the benefit of the para chain features of Polkadot.
- [Moonbeam, Remix, OpenZeppelin](https://docs.moonbeam.network/builders/interact/oz-remix/) Using OpenZeppelin Contracts and Remiz to Deploy To Moonbeam.

### 💫 [Holochain](https://developer.holochain.org/concepts/)
### 💽 [IPFS](https://ipfs.io/)
A peer-to-peer hypermedia protocol for distributed data storage with unique finger prints. Use cases include archivists, researchhers, blockchain developers, content creators, offlien users, and more.

## ⏩ [FastAPI](https://fastapi.tiangolo.com/)
Great way to develop back end architecture in Python. Fast in many ways.

- [User Management](https://github.com/fastapi-users/fastapi-users) Quickly add registration and authentication for FastAPI projects.
- 🌱 [ODMantic](https://art049.github.io/odmantic/) Async document mapper for MongoDB based on python type hints, built on pydantic for model definition and validation. Great shortcut tool for modeling mongo objects in a FastAPI application.
- [Rent-to-Own Token on FastAPI](https://towardsdatascience.com/creating-an-ethereum-token-to-enable-a-decentralized-rent-to-own-network-cc3786cf1142) Creating an Ethereum Token to Enable a Decentralized Rent-to-Own Network. 

## ➬ [React](https://reactjs.org/)
Some tools to help build a quick front end for the application.
-[Semantic UI](https://react.semantic-ui.com/usage) The official Semantic-Ui-React integration

## 🙌 Blockchain R&D
### 🔬 General Research and Theory
- [Web3 Foundation](https://web3.foundation/) 
Web3 Foundation contributes to and funds research and development in web3 technology.

- [Finality Grandpa Gadget](https://research.web3.foundation/en/latest/polkadot/finality.html) A protocol that can be used to provide proveable finality for a blockchain.
- [BABE](https://research.web3.foundation/en/latest/polkadot/block-production/Babe.html) How Polkadot produces relay chain blocks using Blind Assignment for Blockchain Extension protocol, abbreviated as BABE.

### 🆔 Self-Sovereign Identity
- [Hyperledger Foundation](https://www.hyperledger.org/use/hyperledger-indy) Hyperledger Indy provides tools, libraries, and reusable components for providing digital identities rooted on blockchains or otehr distributed ledgers so that they are interoperable across administrative domains, applications, and any other silo.

- [The Sovrin Foundation](https://sovrin.org/) The Sovrin Foundation is a nonprofit organization established to administer the Governance Framework governing the Sovrin Network, a public service utility enabling self-soverign identity on the internet.

- [Identity Foundation](https://identity.foundation/) A foundation developing foundational components of an open, standards-based, decentralized identity ecosystem for people, organizations, apps, and devices.

### 👷🏾‍♂️ Decentralized Construction
- [The Innovation Bank](https://www.coengineers.com/wp-content/uploads/2021/04/R8_IMECE2020-23015.pdf) This white paper proposes a novel business method of decentralizing the engineering professions by integrating and capitalizing knowledge assets.
- [Blockchain Technology: Implications and Opportunities for Professional Engineers](https://www.nspe.org/sites/default/files/resources/pdfs/NSPE-Whitepaper-Blockchain-Technology-2016-final.pdf) - NSPE white paper about blockchain technology and professional licensure.

- [Build3 Foundation](https://www.build3.foundation) A foundation claiming the ethical imperative to pursue blockchain in the practice of engineering.

- [Construction Blockchain Constortium](https://www.linkedin.com/company/construction-blockchain/) This group supports research and development in blockchain technology and services for the industry. Some white papers from their work:
    - [Blockchain & Construction Cashflow](https://static1.squarespace.com/static/58b6047520099e545622d498/t/5fdb6089ad5a0604f7feaf5e/1608212649913/CBC2020-WP1_Cashflow.pdf) 
    - [Integrating Ethereum with Autodesk Forge](https://static1.squarespace.com/static/58b6047520099e545622d498/t/5ef5fbbfe2d6737ff9ecb2f0/1593179078269/CBC-CS1_AutodeskForge_PDF-Version.pdf)

- [BuildCoin](https://www.buildcoinfoundation.org/buildcoin-ecosystem/)
An organization with proposed engines and protocols for the construction industry. Nonprofit.

## 🎧 Other Cool Stuff
- [WakaTime](https://wakatime.com/) - Cool BI productivity tracker tracks what IDE, project, language, etc., is being worked on by the dev team in real-time. Great looking analytics.
- [libp2p](https://libp2p.io/) - Run your network applications free from runtime and address services, independently of their location.
