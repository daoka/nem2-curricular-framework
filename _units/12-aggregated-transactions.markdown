---
layout: post
title:  "08. Aggregated Transactions"
permalink: /units/aggregated-transactions/
targets: 
    - "prototyping"
    - "developer"
---

  ℹ️ Aggregate transactions are only available in Catapult.

### Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Understand the aggregate transactions  properties. | 2 - Understand | - Inner transactions <br> - Co signatures |
| Comprehend situations where aggregate transactions can be used. | 2 - Understand | - Pull transactions <br> - Decentralized Swaps <br> - Automatic Transaction Fee Payment <br> - Token conversion |
| Understand the use of aggregate transactions. | 2 - Understand | atomic |
| Understand why it is required to send lock funds transactions (aggregate bonded). | 3 - Apply | - Prvent spam  |
| Announce and cosign aggregate transactions.| 3 - Apply | |
| (Developer) Apply RxJs functions and operators. | 3 - Apply |  - Map() <br> - MergeMap() <br> - Filter() <br> - toArray() |
|Differentiate between aggregate bonded and aggregate complete transactions | 4 - Analyze | |
| Judge when to use aggregate bonded or aggregate complete transactions. | 5 - Evaluate |


### Proposed outline

1. Introduction
    * Introduce section.
2. Aggregate Transactions
    * Describe the use of aggregate transactions.
        - Merge multiple transactions into one.
        - Add atomic logic.
        - One time smart contracts.
    * Explain aggregate transactions parameters: 
        - Inner transactions.
        - Co signatures.
    * Remark that every transaction except aggregate transactions can be included as inner Transactions.
3. Aggregate Complete Transaction
    * Explain that aggregate transactions are complete if before announcing it to the network, all cosigners have signed it.
    * Show a use case: sending payouts
4. Aggregate Bonded Transaction
    * Explain in case that the transaction requires signatures from other participants, then the transaction is considered aggregate bonded.
    * Explain why Lock funds Transaction are required.
        - Spam protection.
        - Ensure transactions are cosigned.
    * Show some use cases:
        - Pull transactions.
        - Decentralized Swaps.
        - Automatic Transaction Fee Payment.
        - Token conversion.
    * Show how to cosign an announced transaction.
    <br>**Developer**
    * Teach how to use most popular Rx operators (filter, map, flatmap, take, toArray).
    * Explain how aggregate bonded transactions can be turned into complete.


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
* Troncone, Brian. Learn RxJs. [Online](https://www.learnrxjs.io/)