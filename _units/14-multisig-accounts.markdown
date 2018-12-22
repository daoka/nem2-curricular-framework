---
layout: post
title:  "10. Multisig Accounts"
permalink: /units/multisig-accounts/
targets: 
     - "prototyping"
     - "developer"
     - "sysadmin"
---

  ℹ️ Multilevel Multisig Accounts are only available in Catapult.

## Learning objectives 

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Remember how losing keys could affect to your multisig account | 1- Remember | |
| Identify constraints of multisig accounts. | 1 - Remember | - Can’t initiate transactions <br>- Editable |
| Comprehend how multisig accounts can be used. | 2 - Understand  | - Joint accounts <br> - Increase security (2FA) <br> - Multilevel multisig: AND/OR logic |
| Understand the multisig account properties. | 2 - Understand | - M-of-N <br> - Min approval <br>- Min removal |
| Convert accounts to multisig accounts. | 3 - Apply |  | 
| Convert accounts to multi-level multisig accounts. | 3 - Apply | |
| Involve multisig accounts in aggregate transactions. | 3 - Apply | 

## Proposed outline

1. Introduction
    * Explain multisig account usage:
        - Joint accounts
        - Increase security (2FA)
        
2. Properties 
    * Describe M-of-N.
    * Remark once an account can become multisig, can no longer initiate transactions from that account.
    * Describe Minimum Approval and Minimum removal parameters.
    * Show how multisigs are modifiable contracts.
    * Describe restrictions (maximum number of cosignatories).
    * Explain multisig accounts can be undone, and the importance to keep multisig account private key.
    * Warn about losing fund access if minimum approval / removal is not reached (when keys are lost).

3. Create a multisig account
    * Create a multisig account.
    * Involve multisig accounts in aggregate bonded transactions.
    * Cosing transactions involving multisig accounts.

4. Multilevel Multisig Accounts
    * Show how MLMA add “AND/OR” logic to multi-signature transactions.
    * Show different use cases:
        - Supply Chain: Quality approval
        - Improved security
        - IA
    * Describe restrictions (maximum level).


## Activities

**Prototyping**                                                                                                                                                                                                                                                                            
* Creating a multisig account. [NIS1](http://docs.nem.io/en/nanowallet/multisignature-multiuser/multisig-create)  
* Modifying multisig account. [NIS1](http://docs.nem.io/en/nanowallet/multisignature-multiuser/multisig-create)
* How to send transactions from a multisig account. [NIS1](http://docs.nem.io/en/nanowallet/multisignature-multiuser/how-to-send-multisig)

**Developer**                                                                                                                                                                                                                                                                              
* Creating a multisig account. [NIS1](https://nemproject.github.io/nem-library-docs/guide/account/#how-to-convert-a-normal-account-into-multisig-account),  [Catapult](https://nemtech.github.io/guides/account/converting-an-account-to-multisig.html)
* Modifying multisig account [NIS1](https://nemproject.github.io/nem-library-docs/guide/account/#how-to-convert-a-normal-account-into-multisig-account), [Catapult](https://nemtech.github.io/guides/account/modifying-a-multisig-account.html)
* Get all cosigners from a multisig and multisigs involving given an account.                                                         [Catapult](https://nemtech.github.io/guides/account/converting-an-account-to-multisig.html)
* Creating a multi-level multisig account. [Catapult](https://nemtech.github.io/guides/account/creating-a-multi-level-multisig-account.html)
* How to send transactions from a multisig account. [NIS1](https://nemproject.github.io/nem-library-docs/guide/transaction/#how-to-create-a-multisig-transaction), [Catapult](https://nemtech.github.io/guides/transaction/sending-a-multisig-transaction.html)
* Signing pending multisig transactions. [NIS1](https://nemproject.github.io/nem-library-docs/guide/account/#how-to-sign-unconfirmed-multisig-transactions), [Catapult](https://nemtech.github.io/guides/transaction/signing-announced-aggregate-bonded-transactions.html)

## Resources

*  Multisig accounts. NEM Developer Documentation. [NIS1](http://docs.nem.io/en/nanowallet/multisignature-multiuser), [Catapult](https://nemtech.github.io/concepts/multisig-account.html)
* Multi-level multisig accounts. NEM Developer Documentation. [Catapult](https://nemtech.github.io/concepts/multi-level-multisig-account.html#)