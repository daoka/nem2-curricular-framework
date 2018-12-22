---
layout: post
title:  "14. Security"
permalink: /units/security/
targets: 
    - "prototyping"
    - "developer"
    - "sysadmin"
---

    ⚠️️ Draft.

## Learning objectives 

| Learning Objective | Learning Level | Keywords |
| Identify the recommended security practices. | 1 - Remember | - Backup <br> - Multisig <br> - Private Key <br> - Access control<br> - Storage and interaction with private keys<br>  - Data validity|
| Apply recommended security practices. | 3 - Apply | |

## Proposed Outline

1. Introduction
    * Advise on secure common practices.
2. Private keys
    * Explain the importance of not sharing private keys.
    * Show how to create an offline backup.
    * Remark that sending mosaics to an account which is private key is not known will lead to the permanent loss of this mosaics. 
3. Multisig accounts
    * Remember that multisig accounts can’t initiate transactions on their own, so they can be used to increase an account's security adding two-factor authentication.
    * Warn about choosing wisely minimum removal parameter in multisig accounts.
4. Application Development (Developer / Sysadmin)
    * Encourage to have strict control of who access the servers.
    * Recommend separating private keys from code. The developer has to check the git repository does not contain any private key before making it public.
    * Encourage the usage of multisig accounts if are stored in a server to announce transactions automatically. Never store the cosignatories private key in the same server.
    * Advise keeping on the server the minimum amount of private keys as possible. If the account never announces transactions, create a deterministic public key. The server database should not store any private keys.
    * Explain that transactions that involve final users should be signed in the client side. Client-side applications should be able to sign transactions offline.
    * Warn about not trusting libraries asking for a private key or the complete account object.
5. Data validity (Developer / Sysadmin)
    * Advise in reading from at least two different nodes to avoid fake responses.
    * Advise in waiting for some confirmations before considering a transaction valid.
    * Explain how to validate block correctness.

## Activities

* Secure your NEM account with Trezor [NIS1](https://www.youtube.com/watch?v=HB5qBAqjxqg)

## Resources

* Common security practices. NEM Developer Documentation. [To be open sourced] 
* Manage secrets and protect sensitive data. [Vault](https://www.vaultproject.io/)