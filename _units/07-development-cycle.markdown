---
layout: post
title:  "03. Development cycle"
permalink: /units/developmeny-cycle/
targets: 
    - "prototyping"
    - "developer"
---

## Learning objectives


| Learning Objective | Learning Level | Keywords |
| --- | --- | --- |
| Describe existent built-in features. | 1 - Remember | |
| Recall possible ways to integrate NEM blockchain in a project. | 1 - Remember | - Direct<br> - Deferred <br> - Mixed |
| Interpret the NEM Development Cycle. | 2 - Understand | - Scope Definition - What<br> - Authorization modelling <br> - Who and How <br>- Data modelling<br> - Application development |
| Evaluate where makes sense to use blockchain technology. | 5 - Evaluate | Why? |
| Evaluate when to apply NEM blockchain.| 5 - Evaluate | |

## Proposed outline

1. Introduction
    * Introduce section.
2. Where (not) apply blockchain?
    * Explain when to apply blockchain, and when not.
    * Advise when to use public, private or permissioned approach.
3. Technology choice
    * Advise on technology choice:
        - Technologies must fit the use case.
        - Mitigate risk of immutability by choosing flexible technologies.
4. Architecting on NEM
    * Describe multiple ways to integrate NEM blockchain.
        - Application clients are directly connected with NEM nodes. The logic will happen client side.  
        - Application clients that directly communicate with NEM nodes and other clients communicate via application servers to the NEM nodes.
        - Application clients connect to an application server that is connected to the NEM nodes. 
5. Anatomy of a NEM application
    * Define the minimum viable product:
        - Define the exact value proposition to use blockchain. 
        - Narrow the scope.
    * Abstract the authorization model: Who is allowed to do what.
        - Identify every actor and entity.
        - Describe every process: what is the transaction model and the data model.
        - Define user interaction: how does an actor interact with the application.
    * Define the data modelling: Find out where NEM blockchain (and other technologies) plays its role in a use-case.

## Activities

* Defining a blockchain MVP Workshop. NEM Foundation, 2018. [To be open-sourced]

## Resources

* Wüst, Karl; Gervais, Arthur. Do you need a blockchain?, 2018. [Online](https://eprint.iacr.org/2017/375.pdf)
* Meunier, Sebastien. When do you need blockchain? Decision models, Medium, 2016. [Online](https://medium.com/@sbmeunier/when-do-you-need-blockchain-decision-models-a5c40e7c9ba1)
* Architecturing on NEM. NEM Developer Documentation. [Online](https://nemtech.github.io/getting-started/what-is-nem.html)
* Van de Reck, Kristof. Blockchain technologies implementation. NEM experience. 2017. [Video](https://www.youtube.com/watch?v=jTSNr2ocs5)