---
layout: post
title:  "05. Accounts"
permalink: /units/accounts/
targets: 
    - "prototyping"
    - "developer"
    - "sysadmin"
---

## Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Remember security issues regarding private keys. | 1 - Remember | |
| Remember how to do account/wallet backups. | 1 - Remember | |
| Comprehend different uses for accounts. | 1 - Understand | - Asset container <br> - Identifier <br> - Unique assets <br> - Pointer account <br> - Not only persons |
| Understand what an account, and address and a key pair are. | 2 - Understand | |
| Create an account. | 3 - Apply | |
| Create a wallet. | 3 - Apply | |
| Distinguish the differences between a wallet and an account. | 4 - Analyze |  |

## Proposed outline

1. Introduction
    * Define the components that compose an account:
        - Private Key
        - Public Key
        - Address
    * Remark the importance of not sharing private keys.
    
2. Cryptography (Developer)
    * Explain how public key is derived from the private key.
    * Explain how an address is derived from the public key.
    * Generate deterministic private and public keys.
 
3. Account
    * Define an account as a container of assets.
    * Define an account as an identifier.
    * Remark that accounts do not only represent people. Also different actors and objects.
    * Introduce that accounts can be configured with special rules (multisig).
    * Create an account.

4. Wallet
    * Define wallet.
    * Explain the difference between an account and a wallet.
    * Create a wallet.
    * Advise how to do backups of generated accounts.

## Activities

* Backup a wallet. [NIS1](http://docs.nem.io/en/nanowallet/backup-wallet)
* Create a wallet. [NIS1](http://docs.nem.io/en/nanowallet/creating-a-wallet)
* Getting account information. [NIS1](http://docs.nem.io/en/nanowallet/nanowallet-explorer)  

**Developer**                                                                                                                                              
* Create a wallet. [NIS1](https://nemproject.github.io/nem-library-docs/documentation/wallet/), [Catapult](https://nemtech.github.io/guides/account/creating-and-opening-an-account.html)
* Create an account. [NIS1](https://nemproject.github.io/nem-library-docs/documentation/wallet/), [Catapult](https://nemtech.github.io/guides/account/creating-and-opening-an-account.html)
* Getting account information. [NIS1](https://nemproject.github.io/nem-library-docs/guide/account/), [Catapult](https://nemtech.github.io/guides/account/getting-account-information.html)

## Resources

* Account. NEM Developer Documentation. [NIS1](https://docs.nem.io/en/address-components), [Catapult](https://nemtech.github.io/concepts/account.html)