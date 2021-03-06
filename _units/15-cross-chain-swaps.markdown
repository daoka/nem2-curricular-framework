---
layout: post
title:  "11. Cross-chain Swaps"
permalink: /units/cross-chain-swaps/
targets: 
    - "developer"
---
  ℹ️ Cross-chain Swaps are only available in Catapult.

## Learning objectives 

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify the use of cross-chain swaps | 1 - Remember | |
| Understand cross-chain swaps algorithm | 2 - Understand | <br> - HashType <br> - Secret <br> - Proof <br> - Secret Lock Transaction <br> - Secret Proof Transaction |
| Implement atomic trading between NEM public and private chain  | 3 - Apply | |

## Proposed Outline


1. Introduction
    * Explain the necessity of cross-chain swaps.
    * Remark that the swap is not actually between chains, but locking and unlocking funds in each blockchain using cryptography.
    * Mention blockchains compatible with the  SecretLock/Secret Proof mechanism.
2. SecretLock / Secret Proof transactions
    * Understand how the algorithm works (proof, secret, transactions involved).
    * Implement atomic trading between NEM public and private.
    
## Activities

**Developer**                                                                    
* Using secret lock for atomic cross chain swap. [Catapult](https://nemtech.github.io/guides/transaction/atomic-cross-chain-swap-between-NEM-public-and-private-chain.html)
* Atomic Cross Chain Trading workshop. NEM Foundation, 2018. [To be open-sourced]

## Resources

* Secret lock transaction. NEM Developer Documentation. [Online](https://nemtech.github.io/concepts/cross-chain-swaps.html#secret-lock-transaction)
* Secret proof transaction. NEM Developer Documentation. [Online](https://nemtech.github.io/concepts/cross-chain-swaps.html#secret-proof-transaction)
* Atomic Cross Chain Trading. Bitcoin. [Online](https://en.bitcoin.it/wiki/Atomic_cross-chain_trading)