---
layout: post
title:  "09. Aggregated Transactions"
permalink: /units/aggregated-transactions/
targets: 
    - "prototyping"
    - "developer"
---

  ℹ️ Aggregate transactions are only available in Catapult.

### Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify the aggregate transactions  properties. | 1 - Remember | - Inner transactions <br> - Cosignatures |
| Understand the use of aggregate transactions. | 2 - Understand | - Atomic transacitons <br> - Merge multiple transactions into one |
| Comprehend situations where aggregate transactions can be used. | 2 - Understand | - Pull transactions <br> - Escrow or decentralized swap <br> - Automatic Transaction Fee Payment <br> - Token conversion |
| Understand why it is required to send lock funds transactions before announcing an aggregate bonded transaction. | 3 - Apply | - Prevent spam  |
| Announce and cosign aggregate transactions.| 3 - Apply | |
| Apply RxJs functions and operators. (Developer) | 3 - Apply |  - Map() <br> - MergeMap() <br> - Filter() <br> - toArray() |
| Differentiate between aggregate bonded and aggregate complete transactions | 4 - Analyze | |
| Judge when to use aggregate bonded or aggregate complete transactions. | 5 - Evaluate |


### Proposed outline

1. Introduction
    * Describe the use of aggregate transactions.
        - Merge multiple transactions into one.
        - Add atomic logic
        - One time smart contracts
    * Show some use cases:
        - Pull transactions
        - Escrow or decentralized swap
        - Automatic Transaction Fee Payment
        - Token conversion
        - Sending payouts
2. Properties
    * Explain aggregate transactions parameters: 
        - Inner transactions
        - Cosignatures
    * Remark that every transaction except aggregate transactions can be included as inner transactions.
3. Aggregate complete transaction
    * Explain that aggregate transactions are complete if before announcing it to the network, all cosigners have signed it.
    * Announce an aggregate complete transaction
4. Aggregate bonded transaction
    * Explain in case that the transaction requires signatures from other participants, then the transaction is considered aggregate bonded.
    * Explain why lock funds Transaction are required.
        - Spam protection.
        - Ensure transactions are cosigned.
    * Announce an aggregate bonded transaction
5. Cosign an aggregate bonded transaction (Developer)
    * Cosign an announced transaction.
    * Use the most popular Rx operators (filter, map, mergeMap, take, toArray).
    * Turn an aggregate bonded transactions into complete.

## Activities

**Developer**                                                             
* Sending payouts. [Catapult](https://nemtech.github.io/guides/transaction/sending-payouts-with-aggregate-complete-transaction.html)
* Asking for mosaics. [Catapult](https://nemtech.github.io/guides/transaction/asking-for-mosaics-with-aggregate-bonded-transaction.html)
* Creating an escrow. [Catapult](https://nemtech.github.io/guides/transaction/creating-an-escrow-with-aggregate-bonded-transaction.html)
* Using aggregate bonded transactions to pay others fees. [Catapult](https://nemtech.github.io/guides/transaction/asking-for-mosaics-with-aggregate-bonded-transaction.html)
* Receiving funds. [Catapult](https://nemtech.github.io/guides/transaction/asking-for-mosaics-with-aggregate-bonded-transaction.html)
* Signing aggregate transactions. [Catapult](https://nemtech.github.io/guides/transaction/signing-announced-aggregate-bonded-transactions.html)
* Monitor aggregate bonded transactions added and cosign. [Catapult](https://nemtech.github.io/guides/blockchain.html#listening-new-blocks)
* Signing aggregate transactions automatically. [Catapult](https://nemtech.github.io/guides/transaction/signing-announced-aggregate-bonded-transactions-automatically.html)

## Resources

* Transaction. NEM Developer Documentation. [NIS1](http://docs.nem.io/en/transaction-components), [Catapult](https://nemtech.github.io/concepts/transaction.html)
* Aggregate Transactions. [Catapult](https://nemtech.github.io/concepts/transaction.html#aggregate-transaction)
* Daniels,  Paul P; Atencio, Luis;. RxJS in Action, Manning, 2017.                                                                  
* Troncone, Brian. Learn RxJs. [Online](https://www.learnrxjs.io)