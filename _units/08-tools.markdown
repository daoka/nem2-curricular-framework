---
layout: post
title:  "04. Tools"
permalink: /units/tools/
targets: 
    - "prototyping"
    - "developer"
    - "sysadmin"
---

## Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify the different tools available in the NEM ecosystem. | 1 - Remember | - Explorer <br> - CLI <br> - Wallet  <br> - Prototyping Tool <br> - SDK |
| Identify NEM block structure and transaction properties. | 1 - Remember | - Deadline <br> - Signer <br> - Signature <br> - Height <br> - Hash  |
| Install the NEM tools. | 3 - Apply | |
| Evaluate which tool use depending on the situation. | 5 - Evaluate | | 


## Proposed outline

1. Introduction
    * Present and install NEM Wallet.

2. Setup/Connect to a test network
    * Connect to testnet (NIS1).
    * Setup and connect to Catapult Service bootstrap (Catapult).

3. Setup prototyping environment (Prototyping)
    * Present and install NEM2-Prototyping Tool.
    * Create an account.
    * Explore a block and a transaction.

4. Setup development environment (Developer)
    * Present and install NEM2-CLI.
    * Present and install NEM2-SDK.
    * Create an account.
    * Explore a block and a transaction.
    * Explain the benefits of using NEM-SDK instead of raw API.
    * Advise which tool use, depending on the case: 
        - NEM2-CLI: Setup task.
        - NEM2-SDK: Task is regularly executed.

## Activities

**Prototyping**    

* Set up the environment. [NIS1](http://docs.nem.io/en/nanowallet/download-and-open), [Catapult](https://nemtech.github.io/prototyping-tool/overview.html)
* Open the explorer. [NIS1](http://docs.nem.io/en/blockexplorers)
* Creating a Wallet [NIS1](http://docs.nem.io/en/nanowallet/creating-a-wallet)

**Developer**                                                                                                                                   
* Set up the environment. [NIS1](http://docs.nem.io/en/nem-sdk/nem-sdk-install), [Catapult](https://nemtech.github.io/getting-started/setup-workstation.html)
* Running the explorer. [Catapult](https://github.com/tech-bureau/catapult-service-bootstrap\#starting-with-test-block-explorer)
* Creating an Account. [NIS1](https://nemproject.github.io/nem-library-docs/documentation/wallet/), [Catapult](https://nemtech.github.io/guides/account/creating-and-opening-an-account.html)
* Creating a Wallet. [NIS1](https://nemproject.github.io/nem-library-docs/documentation/wallet/), [Catapult](https://nemtech.github.io/guides/account/creating-and-opening-an-account.html)

## Resources

* Official repositories. [NIS1](https://github.com/NEMproject), [Catapult](https://github.com/nemtech)                      
* Wallet. [NIS1](https://nem.io/downloads/) 
* Explorers. [NIS1](http://docs.nem.io/en/blockexplorers), [Catapult](https://github.com/tech-bureau/catapult-service-bootstrap)
* NEM Prototyping Tool. [Catapult](https://nemtech.github.io/prototyping-tool/overview.html)
* NEM SDKs references. [NIS1](https://nem.io/developers/), [Catapult](https://nemtech.github.io/sdk/languages.html)