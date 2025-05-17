# Altica: A Sovereign, Decentralized DNS Protocol

[![logo](./logo.png)](logo)

## Abstract

Altica is a fully sovereign, decentralized naming and resolution system designed for the next generation of web infrastructure. Unlike existing blockchain-based domain systems that often rely on centralized intermediaries or operate within constrained ecosystems, Altica proposes an autonomous root namespace. By leveraging peer-to-peer technologies, zero-knowledge (ZK) cryptography, and a modular architecture, Altica offers a censorship-resistant, privacy-preserving, and highly interoperable alternative to traditional DNS and current Web3 naming protocols.

## Introduction

The current internet naming infrastructure, built around ICANN's DNS, is centralized and susceptible to censorship, surveillance, and administrative bottlenecks. In response, blockchain-based alternatives like ENS, Handshake, and Unstoppable Domains have emerged. However, these projects either depend on existing Layer 1 blockchains or lack critical features such as privacy-preserving query resolution and full-stack decentralization.

Altica is conceived to address these shortcomings. Altica seeks to redefine the naming landscape by building a root-native DNS system with its own rules, governance, and infrastructure.

## Problem Statement

Most current decentralized naming solutions suffer from one or more of the following issues:

* **Centralized dependencies** (e.g., reliance on Ethereum or other base chains)
* **Limited privacy** (no ZK-resolved queries)
* **Poor interoperability** with ICANN DNS
* **Lack of resolver decentralization**

## Vision and Mission

Altica envisions a world where internet naming is universally accessible, censorship-resistant, and user-controlled. The mission is to:

* Build a sovereign, modular DNS protocol with a self-contained root zone
* Implement privacy-preserving name resolution using zero-knowledge technology
* Use peer-to-peer protocols (libp2p, DHT) for a decentralized resolver network
* Enable hybrid interoperability with existing DNS systems
* Govern development and upgrades through a community-driven DAO (Post-MVP)

## Core Components

### 1. Root Namespace

Altica creates its own root namespace (e.g., `.alt`) that is not beholden to ICANN or any external body. Top-level domains (TLDs) under this root are issued through an open and verifiable registration mechanism.

### 2. Decentralized Resolver Stack

Built using libp2p, IPFS, and custom DHT algorithms, Altica's resolver network is distributed and fault-tolerant. Resolver clients can operate independently or relay through community-run nodes.

### 3. ZK-Resolved Queries

To protect user privacy, Altica incorporates zero-knowledge proofs in its resolution layer, allowing names to be queried without revealing user identity or browsing intent.

### 4. Interoperability Layer

Altica supports optional fallback to traditional DNS via DNS-over-HTTPS or DNS-over-TLS gateways, ensuring compatibility with legacy systems while maintaining decentralization.

### 5. Governance: Infrade DAO

All core upgrades, TLD policy decisions, and incentive mechanisms are governed through Infrade, a DAO formed by core contributors, resolver operators, and token holders.

## Technical Roadmap

1. **Phase 1 - Bootstrapping**

   * Research & protocol design
   * Initial testnet implementation of resolver stack

2. **Phase 2 - Core Launch**

   * TLD issuance mechanism
   * ZK query engine alpha
   * Public resolver deployment

3. **Phase 3 - Ecosystem Growth**

   * Developer SDKs & APIs
   * Fallback resolver gateways
   * Interoperability with ENS, NameCoin, etc.
   * Community engagement and education
   * Launch DAO governance model

4. **Phase 4 - Governance Transition**
   * Tokenomics design and distribution
   * Governance model finalization

## Conclusion

Altica represents a paradigm shift in how internet names are assigned, resolved, and governed. By building a sovereign root, fully decentralized resolver stack, and privacy-preserving resolution protocol, Altica paves the way for a more open, secure, and censorship-resistant web. As part of its long-term vision, Altica aims to become the default naming layer for the decentralized internet.

## Call to Action

Infrade invites open-source contributors, protocol researchers, developers, and digital rights advocates to collaborate on the Altica project. Join us in shaping the future of naming.

Website: [www.altica.io](https://www.altica.io)
GitHub: [github.com/infrade/altica](https://github.com/infrade/altica)
Twitter: [@Altica](https://twitter.com/Altica)

---

Copyright 2025 Infrade. All rights reserved.
