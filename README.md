# Decentralizing Trust with Resilient Group Signatures in Blockchains

The porpose of this repository is to host sublinks and explain the porpouse of each git repository for each component of the prorotype for the MSc. The main goal of the thesis [[1](#thesis)] was to create agnostic component able to descentralise conventional digital signatures in blockchains or other distributed systems.


## Context

Blockchains were ﬁrst introduced by Bitcoin with the goal of promoting the decentralization of cryptocurrency transactions in a P2P-based internetworking model that does not depend on centralized trust parties. Along with research on better scalability, performance, consistency control, and security guarantees in their service planes, other challenges aimed at better trust decentralization and fairness models for blockchains are on the research community’s agenda today.

Asymmetric cryptography and especially digital signatures are key components of blockchain systems. As a common ﬂaw in different blockchains, public keys and verification of single-signed transactions are handled under the principle of trust centralization. In this dissertation, we propose a better fairness and trust decentralization model by prototyping a service plane for blockchains that provides support for collective digital signatures and allows transactions to be collaboratively authenticated and veriﬁed with witnessed guarantees. This will be achieved by using resilient group-oriented signatures from randomly and dynamically assigned groups. Our solution will be based on Threshold-Byzantine Fault Tolerant Digital Signatures to improve the global resilience and robustness of blockchain systems while preserving their decentralization nature.

To this end, we will design and implement a modular and portable cryptographic provider that supports cryptographic operations that can be expressed and executed by smart contracts. Our system will be designed to be agnostic and adaptable to dfferent service planes and diﬀerent blockchains (independent of consensus and consistency control solutions and will be adaptable to permissionless or permissioned models). Therefore, we envision our solution as a portable and adaptable plugin service plane for blockchains that provides authenticated group-signed transactions with decentralized auditing, fairness, and long-term security guarantees to leverage a better trust-based decentralized model. For validation and experimental evaluation of the deployed solution, we will observe the beneﬁts of our proposal, which must do without sacriﬁcing throughput and latency conditions for each blockchain without degrading these metrics compared to using single digital signatures under centralized trust model assumptions. We will perform our validations in a cloud-based testbench pilot, running our service plane in two different blockchains using at least twenty blockchain nodes distributed in three different data

## Architecture


### Links to each component
This repository was created with the purpose of aggregating the various components that make up my thesis.


* Signer Node - https://github.com/jffp113/SignerNode_Thesis
* Go CryptoProviderSDK - https://github.com/jffp113/CryptoProviderSDK
* Sawtooth Validator - https://github.com/jffp113/sawtooth-core
* Sawtooth SmartContract - https://github.com/jffp113/sawtooth-smartcontract
* go util - https://github.com/jffp113/go-util
* algorand sdk - https://github.com/jffp113/go-algorand-sdk
* algorand validator - https://github.com/jffp113/go-algorand
* Blockchain Benchmarker - https://github.com/jffp113/Thesis_Client

The latex for the thesis can be found here: https://github.com/jffp113/JPereira_Thesis


## Pre-requisites

## Reference

<a name="thesis"> </a>
