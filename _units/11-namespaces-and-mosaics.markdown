---
layout: post
title:  "07. Namespaces & Mosaics"
permalink: /units/namespaces-and-mosaics/
targets: 
    - "prototyping"
    - "developer"
---

## Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify situations where namespaces and mosaics can be used. | 1 - Remember | |
| Understand the utility of namespaces. | 2 - Understand | - Account identifier <br> - Mosaic identifier <br> - Classify mosaics |
|  Understand the different mosaic properties. |  2 - Understand | - Divisibility <br> - Duration <br> - Supply <br> - Mutability <br> - Transferability <br> Levy |
| Understand the utility of mosaics. |  2 - Understand | - Configurable token |
| Register a namespace. | 3 - Apply | |
| Register a subnamespace. | 3 - Apply | |
| Register a mosaic. | 3 - Apply | |
| Send a transaction with multiple mosaics. | 3 - Apply | |
| Distinguish between namespaces and subnamespaces. | 4 - Evaluation | - Domain <br>  - Subdomain |
| Judge when to use accounts or mosaics to represent assets. | 5 - Evaluate | |

## Proposed outline

1. Introduction
    * Introduce section.
2. Namespaces
    * Describe namespaces use.
        - Identify accounts
        - Organize mosaics
    * Remark uniqueness of namespaces.
    * Explain the use of subnamespaces.
    * Describe namespace name restrictions.
    * Reference namespace maximum levels.
    * Describe the duration and renewal period.
    * Describe the namespace owner.
    * Show how to register a namespace.
3. Mosaics
    * Describe mosaics usage and relation with namespaces.
    * Explain when to use mosaics to represent assets and when accounts.
    * Describe mosaic properties
        - Divisibility
        - Duration
        - Supply
        - Mutability
        - Transferability
        - Levy
    * Show how to register a mosaic.


## Activities

**Prototyping**                                                                                                                                                                                                                                                       
* Send a transfer transaction containing multiple mosaics. [NIS1](http://docs.nem.io/en/nanowallet/mosaics/send-mosaic-asset), [Catapult](https://flows.nodered.org/flow/3d87669bfc71e99f29f5ad82ba2a402e)
* Register a namespace. [NIS1](http://docs.nem.io/en/nanowallet/namespaces), [Catapult](https://flows.nodered.org/flow/3d87669bfc71e99f29f5ad82ba2a402e)
* Register a mosaic. [Catapult](http://docs.nem.io/en/nanowallet/mosaics/create-mosaic-asset),[Catapult](https://flows.nodered.org/flow/04a643b66a8e0daa1e12fa61e3b36b7c)
* Editing a mosaic [NIS1](http://docs.nem.io/en/nanowallet/mosaics/edit-mosaic-asset)

**Developer**                                                                                                                                                                                                                                                         
* Send a transfer transaction containing multiple mosaics. [NIS1](https://nemlibrary.com/guide/transaction/#how-to-create-a-transfer-transaction-with-mosaics), 
[Catapult](https://nemtech.github.io/guides/transaction/sending-a-transfer-transaction.html)
* Register a namespace. [NIS1](https://nemlibrary.com/guide/namespace/#how-to-create-a-namespace), [Catapult](https://nemtech.github.io/guides/namespace/registering-a-namespace.html)
* Register a subnamespace. [NIS1](https://nemlibrary.com/guide/namespace/#how-to-create-a-sub-namespace),                                  [Catapult](https://nemtech.github.io/guides/namespace/registering-a-subnamespace.html)
* Register a mosaic. [NIS1](https://nemlibrary.com/guide/mosaic/), [Catapult](https://nemtech.github.io/guides/mosaic/creating-a-mosaic.html)
* Modifying mosaic supply. [NIS1](https://nemlibrary.com/guide/mosaic/), [Catapult](https://nemtech.github.io/guides/mosaic/modifying-mosaic-supply.html)

## Resources

* Namespace. NEM Developer Documentation. [NIS1](http://docs.nem.io/en/gen-info/namespaces), [Catapult](https://nemtech.github.io/concepts/namespace.html)
* Mosaic. NEM Developer Documentation. [NIS1](http://docs.nem.io/en/gen-info/namespaces), [Catapult](https://nemtech.github.io/concepts/mosaic.html)