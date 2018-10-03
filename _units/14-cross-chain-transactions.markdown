---
layout: post
title:  "10. Cross-Chain Transactions"
permalink: /units/cross-chain-transactions/
targets: 
    - "developer"
---
  ℹ️ Cross Chain Transactions are only available in Catapult.

## Learning objectives 

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify the use of cross chain transactions | 1 - Remember | |
| Understand  the cross chain transactions algorithm | 2 - Understand | <br> - HashType <br> - Secret <br> - Proof <br> - Secret Lock Transaction <br> - Secret Proof Transaction |
| Implement atomic trading between NEM public and private chain  | 3 - Apply | |

## Proposed Outline


1. Introduction
    * Introduce section.
2. SecretLock / Secret Proof
    * Explain the necessity of cross chain transactions.
    * Remark that the swap is not actually between chains, but locking and unlocking funds in each blockchain using cryptography.
    * Mention blockchains compatible with the  SecretLock/Secret Proof mechanism.
    * Understand how the algorithm works (proof, secret, transactions involved).
    * Implement atomic trading between NEM public and private.
    
## Activities

**Developer**                                                                    
* Using secret lock for atomic cross chain swap transactions. [Catapult](https://nemtech.github.io/guides/transaction/using-secret-lock-transaction-for-atomic-cross-chain-swap.html)
* Atomic Cross Chain Trading workshop. NEM Foundation, 2018. [To be open-sourced]

## Resources

* Secret lock transaction. NEM Developer Documentation. [Online](https://nemtech.github.io/concepts/transaction.html#secret-lock-transaction)
* Secret proof transaction. NEM Developer Documentation. [Online](https://nemtech.github.io/concepts/transaction.html#secret-proof-transaction)
* Atomic Cross Chain Trading. Bitcoin. [Online](https://en.bitcoin.it/wiki/Atomic_cross-chain_trading)