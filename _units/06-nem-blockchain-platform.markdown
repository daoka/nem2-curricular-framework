---
layout: post
title:  "02. NEM blockchain platform"
permalink: /units/nem-blockchain-platform/
targets: 
    - "prototyping"
    - "developer"
    - "sysadmin"
---

## Learning objectives

| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Identify NEM Blockchain characteristics. | 1 - Remember | - API <br> - Built-in features <br> - Private/Public approach |
| Recognize node layers. | 1 - Remember | |
| Identify the usage of XEM. | 1 - Remember | |
| Comprehend how much business logic should be stored in the blockchain. | 2 - Understand | |
| Comprehend NEM consensus algorithm. | 2 - Understand | - PoI <br>- Harvesting <br>- Delegated harvesting <br>- Vested <br>- Unvested |
| Distinguish what makes NEM special, comparing it with other blockchain solutions. | 4 - Analyze | - Ease of development<br>- Scalable<br>- Built-in features Security|
| Judge when to use built-in features or create your new plugin. | 5 - Evaluate | |

## Proposed outline

1. Introduction
    * Introduce section.
2. What is NEM?
    * Blockchain Platform.
    * Speed
        - Ease of development and integration (cutting costs/time).
        - SDK and API based (develop in any language).
        - Smart Assets System (Built-in features overview).
    * Secure
        - Built from scratch and running since 2015.
        - Keep business logic off-chain, logic can be changed in case of error.
        - Eigentrust++ score system.
        - Spam protection.
    * Scalable
        - Public and private approach: seamless integration using the same tools and core.
        - Cost-effective infrastructure.
        - Keep business logic off-chain, logic can be adapted to new requirements.
3. Nodes
    * Detail how NEM nodes consensus algorithm works.
    * Introduce XEM cryptocurrency, and its usage (pay transaction and services fees).
4. Architecture
    * Describe NEM 4-layered architecture.
        -  Core
        - API & MongoDB
        - SDKs
        - NEM Apps
    * Advise on when to use built-in features or add plugins at the blockchain layer (private networks).
5. NEM business cases
    * Show real uses of NEM applied to different industries.

### Activities

**SysAdmin**                                                                                                                                                                                                        
* Running your own NEM public node ([NIS1](https://forum.nem.io/t/nem-supernode-command-line-tutorial-for-debian-8-4/2211), Catapult TBD)

## Resources

* Official website. NEM. [Online](https://nem.io)
* Mijin website. Tech Bureau. [Online](https://mijin.io/en/)  
* NEM 101 slides. NEM Foundation. 2018. [Online](https://docs.google.com/presentation/d/1dOxob0dOr07EqMCQObwZtU2cd-b9xt4oEG2Sn6O3wDY/edit#slide=id.g3d837a48e0_2_0)         
* Enterprise use cases. NEM. [Online](https://nem.io/enterprise/use-cases/)                                                                  
* NEM Developer Documentation. NEM. [NIS1](https://docs.nem.io), [Catapult](https://nemtech.github.io/)                            
* BloodyRookie; gimre; Jaguar0625; Makoto. NEM Technical Reference. 1.2.1 NEM. 2018. [Online](https://nem.io/wp-content/themes/nem/files/NEM_techRef.pdf)
* NEM 4-layered achitecture. NEM Developer Center. [Online](https://nemtech.github.io/concepts/node.html)
* McDonald, Jeff. Unlocking Advanced Blockchain applications. 2018. [Video](https://www.youtube.com/watch?v=VvKItFs5lzE)