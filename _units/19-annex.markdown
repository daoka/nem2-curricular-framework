---
layout: post
title:  "Annex: NIS1/Catapult: Comparison Matrix"
permalink: /annex/nis1-catapult-comparison-matrix/
---

| Topic | Subtopic | NIS1 | Catapult | Comment |
| --- | --- | --- | --- | --- |
| **Public network** | | Since 2015 | TBD | |
| **Node** | | | | |
| | **Architecture** | NEM infrastructure server | 1) Mongo DB & API Server <br> 2) Core Blockchain Server for P2P transactions | |
| | **Server Language** | Java | C++ | |
| | **Minimum requirements** | RAM: At leat 2GB recommended <br> CPU: 1Ghz+ single core or more is recommended. | TBD | |
| **Consensus Algorithm** | | Public chain: PoI <br> Private chain: PoS | TBD | |
| **Transaction fees** | | [NIS1 transaction fees](https://nemproject.github.io/#transaction-fees) | TBD | |
| **API** | | [Reference](https://nemproject.github.io/) | [Reference](https://nemtech.github.io/api/requests.html) | Incompatible API contracts |
| **Main Wallet** | | [NanoWallet](https://nem.io/downloads/) | TBD | |
| **Dev tools** | | [NEM-SDK](https://github.com/QuantumMechanics/NEM-sdk), [nem-library](https://github.com/aleixmorgadas/nem-library-ts) | [NEM2-SDK](https://nemtech.github.io/sdk/languages.html) | |
| **Transfer Transaction** | | Yes | Yes | |
| | Multiple Mosaics | Yes | Yes | | 
| | Messaging | Yes | Yes |  | 
| | Encrypted Messages | Yes | Yes | Not available in NEM2-SDK yet| 
| **Namespace** | | Yes | Yes | |
| | Subnamespace | Yes | Yes | | 
| | Renting duration | Yearly | Per block | | 
| | Levels | 3 | TBD |  |
| **Mosaics** | | Yes | Yes | |
| | Description | Yes | TBD | |
| | Duration | Attached to the namespace | TBD | |
| | Mutable | Yes | Yes | |
| | Transferability | Yes | Yes | |
| | Non-expirable | No | TBD | |
| | Levy | Yes | TBD | |
| **Multisig Accounts** | | Yes | Yes, multisig tx are now aggregate transactions | |
| | Delete cosignatory | N-1 | Configurable with minimum removal| |
| | Maximum number of cosignatories | 64 | TBD | Editable in private networks |
| | Maximum number of multisig accounts | | TBD | Editable in private networks |
| | Multilevel multisig accounts | No | Yes | Editable in private networks |
| | Convert multisig accounts back to normal | No | Yes  | |
| **Aggregate Transactions** | | With multisig accounts | Yes | |
| | Multi asset escrow | N/A | Yes | |
| | Automatic fee payment | N/A  | Yes | |
| | Pull transactions | N/A | Yes | |
| | Multisig transactions | Yes | Yes | |
| | Lock funds transactions | N/A  | Yes | |
| **Cross chain transactions** | | No | Yes | |
| **Create on-chain plugins** | | No | TBD | |


* Differences between NEM-library and NEM2-SDK. NEM Developer Documentation. [Online](https://nemtech.github.io/sdk/release-notes/00-migration.html)