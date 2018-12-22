---
layout: post
title:  "06. Transfer Transactions"
permalink: /units/transfer-transactions/
targets: 
    - "prototyping"
    - "developer"
    - "sysadmin"
---

## Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify transfer transaction parameters. | 1 - Remember | - Recipient<br> - Mosaic <br> - Message |
| Comprehend the usage of transfer transactions. | 2 - Understand | - Transfer mosaics<br> - Messaging (encrypted or not) |
| Recognize transaction status errors. | 2 - Understand | |
| Comprehend transaction cycle. | 2 - Understand | - Validation <br> - Confirmed <br> - Unconfirmed <br> - Error - Status |
| Developer: Understand Reactive Programming basics. | 2 - Understand | Observer pattern |
| Create transactions. | 3 - Apply | |
| Sign transactions. | 3 - Apply | |
| Announce transactions. | 3 - Apply | |
| Monitor transaction status. | 3 - Apply |

## Proposed outline

1. Introduction
    * Explain transfer transactions usage:
        - Transfer and store of value
        - Transfer Mosaics
        - Send messages
        - Timestamp data

2. Defining a transfer transaction
    * Define transfer transactions parameters:
        - Deadline
        - Recipient
        - Mosaic
        - Message
    * Explain different transactions messages:
        - Plain
        - Empty
        - Encrypted
        - Hex
    * Transaction fees

3. Signing a transaction
    * Explain the necessity of signing transactions to ensure that the network validates the transaction comes from our account, relating the concept to the account key pair.
    
4. Announcing a transaction    
    * Explain how to announce a transaction.
    * Describe the possible transaction status (confirmed, unconfirmed).
    * Explain where the validation happens (API, P2P network) and how to monitor errors. 
    * Introduce Listeners: Monitor transactions once sent to the blockchain.
    * Explain the possibility of having roll-back, remarking the minimum number of confirmations when the transaction cannot be revoked.

5.  Reactive Programming, Rx library, and the Observer Pattern (Developer)
    * Encourage to use Reactive Programming instead of futures/promises.
    * Explain how to turn the asynchronous announcement into synchronous.

## Activities

**Prototyping**                                                                                                                                                                                                                                      
* Send a transfer transaction. [NIS1](http://docs.nem.io/en/nanowallet/send-receive), [Catapult](https://flows.nodered.org/flow/7061090eb3cbf724c80e4f49e03e1b94)

**Developer**                                                                                                                                                                                                                                                      
* Send a transfer transaction. [NIS1](https://nemproject.github.io/nem-library-docs/guide/transaction/), [Catapult](https://nemtech.github.io/guides/transaction/sending-a-transfer-transaction.html)
* Get the amount of XEM sent to an account. [Catapult](https://nemtech.github.io/guides/account/getting-the-amount-of-XEM-sent-to-an-account.html)
* Fetch confirmed and unconfirmed transactions. [NIS1](https://nemproject.github.io/nem-library-docs/guide/account/#how-to-receive-all-transactions-for-an-account),  [Catapult](https://nemtech.github.io/guides/account/receiving-transactions-from-an-account.html)
* Turning the asynchronous transaction announcement into synchronous. [Catapult](https://nemtech.github.io/guides/transaction/turning-the-asynchronous-transaction-announcement-into-synchronous.html)

**Developer / Sysadmin**
* Avoid roll-back. [NIS1](https://gist.github.com/aleixmorgadas/3d856d318e60f901be09dbd23467b374)
* Monitoring announced transactions. [NIS1](https://nemproject.github.io/nem-library-docs/guide/listener/),[Catapult](https://nemtech.github.io/guides/transaction/debugging-transactions.html)

## Resources

* Transaction. NEM Developer Documentation. [NIS1](http://docs.nem.io/en/transaction-components), [Catapult](https://nemtech.github.io/concepts/transaction.html)
* Transfer Transaction. NEM Developer Documentation. [Catapult](https://nemtech.github.io/concepts/transfer-transaction.html)
* Staltz, Andre. The introduction to Reactive Programming you've been missing. Github. 2014.  [Online](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)   
