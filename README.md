# Chandra Station Services Available (CSSA)

## Table of Contents

- [Overview](#overview)
- [Infrastructure](#infrastructure)
  - [Hardware](#hardware)
  - [Public Endpoints](#public-endpoints)
  - [Data Indexers](#data-indexers)
  - [Validators](#validators)
  - [White-label](#white-label)
- [Software Development](#software-development)
  - [Front-end](#front-end)
    - [Gravity Pulse](#gravity-pulse)
    - [Gravity Pulse Bridge](#gravity-pulse-bridge)
    - [Althea.io](#altheaio)
    - [CCR App](#ccr-app)
    - [Quicksilver V2 Web App](#quicksilver-v2-web-app)
    - [Apollo](#apollo)
  - [Back-end](#back-end)
    - [Gravity Pulse Backend](#gravity-pulse-backend)
    - [Neons Dao Refund](#neons-dao-refund)
    - [Chandra Station Endpoints](#chandra-station-endpoints)
    - [Playmos](#playmos)
  - [Blockchain Development](#blockchain-development)
    - [Fundamental Cosmos SDK Development](#fundamental-cosmos-sdk-development)
    - [Genesis Event Coordination](#genesis-event-coordination)
    - [Backend Infrastructure](#backend-infrastructure)
    - [Deploying IBC connections](#deploying-ibc-connections)
    - [IBC Infrastructure](#ibc-infrastructure)
    - [Basic Block Explorers](#basic-block-explorers)
    - [Validator Sets](#validator-sets)
    - [White-Label Validators](#white-label-validators)
    - [Dapps for Chain Interactions](#dapps-for-chain-interactions)
- [Networking](#networking)


## Overview
Chandra Station specializes in infrastructure management and web application development. We are amongst the largest deployers of our own dedicated hardware in the Cosmos ecosystem. Alongside our focus on infrastructure we also develop and maintain multiple web apps for a basket of different ecosystems. Our combined expertise enables us to handle billions of API requests every month, maintain safe and reliant validators, and develop applications that facilitate better user interactions with blockchain systems.

## Infrastructure
We deploy and maintain hardware throughout the United States with our main deployment in Phoenix Arizona at a Tier IV data center, Aligned Phoenix. At Aligned, we have deployed a diverse range of servers from Dell PowerEdge to custom Supermicro builds.

* ### Hardware
    * We deploy and maintain hardware throughout the United States with our main deployment in Phoenix Arizona at a Tier IV data center, Aligned Phoenix. At Aligned, we have deployed a diverse range of servers from Dell PowerEdge to custom Supermicro builds.
![image alt][reference]
* ### Public Endpoints
    * Endpoints for each supported network are deployed without rate limits, offering 1G up and down connections. Examples of our most used public endpoints are canto and gravity bridge. ***All our nodes are deployed on our machines with an exception for networks that are geographically isolated to one region.***
* ### Data Indexers
    * We have developed and deployed an extremely performant indexer for Cosmos blockchains in Rust, it is currently used in production to store and sort all Gravity Bridge transaction data and serve that data to various applications.
* ### Validators
    * Chandra Station is a validator for multiple Cosmos networks. We use a multi sentry node configuration behind a VPN and TMKMS or Horcrux depending on the network specifications. ***All our nodes are deployed on our machines with an exception for networks that are geographically isolated to one region.***
* ### White-label
    * Our white label solution is extremely selective, only onboarding clients who aim to bring value to the network such as institutional investors and influencers. Our current clients are Ovrclk, Horizon Law, Altcoin Psycho, and Four Moons Capital. These clients receive the same infrastructure as Chandra Station, hosted on similarly configured servers.

## Software Development
Chandra Station has expertise in a range of technologies including React, Bun, Node, Express, Vite, Typescript, Javascript, Rust, Cosmology's stack, Solidity, Python, and various CSS frameworks. Our focus is on building and maintaining software primarily for Cosmos and EVM-based networks like Ethereum, Akash, Canto, and Arbitrum.

* ### Front-end
    * [**Gravity Pulse**](): An analytics dashboard for Gravity Bridge.![pulse.png](https://hackmd.io/_uploads/rJmxhQzXp.png)


    * [**Gravity Pulse Bridge**](): A modified version of Cosmostation's original Gravity Bridge web app, known as "Space Station".

    * [**Althea.io**](): A reworked, deployed, and maintained version of canto.io designed for Althea, featuring a custom built multi-validator staking solution.
    ![Screenshot 2023-11-03 at 1.18.27 AM.png](https://hackmd.io/_uploads/rk6E6mM7a.png)![Screenshot 2023-11-03 at 1.18.03 AM.png](https://hackmd.io/_uploads/SyTNpXfXT.png)
    * [**CCR App**](): Allows users to register their Canto Clusters.
    ![Screenshot 2023-11-03 at 1.23.20 AM.png](https://hackmd.io/_uploads/B1UM0mz7a.png)

    * [**Quicksilver**]() V2 Web App: An in-house developed liquid staking and governance dashboard designed for Quicksilver V2.
    <img src="https://pbs.twimg.com/media/F9QP9SXb0AAKYbJ?format=jpg&name=4096x4096" alt="Quicksilver" width="600" height="333">
    
    * [**Apollo**](): An older version of ping.pub, slated for an upgrade to ping.pub v2.
    
* ### Back-end
    * [**Gravity Pulse Backend**](): A Cosmos block indexer developed in Rust.
    * [**Neons Dao Refund**](): A smart contract designed to refund NFT holders
    * [**Chandra Station Endpoints**](): Utilizes nginx and Express to enable automatic state-sync, snapshot, load balancing, and reverse proxying for multiple nodes.
    * [**Playmos**](https://playmos.app): Currently closed source, an evm based web3 casual gaming experince

* ### Blockhain Development
    Chandra Station offers a comprehensive platform for launching Cosmos SDK-based blockchains. We serve in advisory, development, and community management roles, with a profound expertise in Cosmos governance.

    We've successfully launched multiple chains and played significant roles, whether as genesis validators, contributors, or organizers, for prominent projects like Osmosis, Gravity, and Canto, among others.

    Every chain launch is unique, and we tailor our approach accordingly. Our services encompass fundamental Cosmos SDK development, backend infrastructure, and the orchestration of genesis events. We specialize in IBC (channels, connections, and relaying), IBC infrastructure, basic block explorers, validator sets, white-label validators, as well as Dapps for various chain interactions such as staking, governance and any custom chain features.

    Here is an in depth description of all the services we provide as it relates to the Cosmos SDK and building/deploying blockchains

    1. **Fundamental Cosmos SDK Development**: We offer core Cosmos SDK development services, ensuring that your blockchain is built on a solid foundation with the latest features and enhancements.
    
    2. **Genesis Event Coordination**: As previously mentioned we have participated in and/or coordinated genesis events for many large Cosmos networks. This includes but is not limited to, infrastructure, genesis file management, gentx, tokenomics and development.

    3. **Backend Infrastructure**: Our expertise extends to setting up the necessary backend infrastructure and skillfully coordinating genesis events for a smooth chain launch.

    4. **Deploying IBC connections**: We specialize in IBC, covering aspects such as channels, connections, and relaying, facilitating seamless communication between blockchains.

    5. **IBC Infrastructure**: We provide the infrastructure needed to make IBC functionality a reality, enabling secure data transfer between interconnected blockchains.

    6. **Basic Block Explorers**: We operate and manage a customized version of the widely-used multi-chain block explorer, Ping.pub, tailored for Cosmos. This empowers us to promptly provide an extensive and feature-rich block explorer for any Cosmos chain or to develop a unique, one-of-a-kind explorer to meet specific needs.

    7. **Validator Sets**: We have a wide reach in the Cosmos ecosystem and are in daily communication with the best of the best for validators and infrastructure providers.

    8. **White-Label Validators**: Our white-label validators can be customized to meet your specific branding and operational requirements, offering flexibility in validator services.

    9. **Dapps for Chain Interactions**: We develop decentralized applications (Dapps) tailored for various chain interactions, including staking, governance, and any custom chain features, enhancing the functionality of your blockchain.

## Networking
Chandra Station participates in various validator subgroups, including the Good Validators Association, or the GVA, and the Bare Metal Alliance. We maintain strong ties with a diverse range of validators, differing in staked value and technical expertise. Ongoing collaboration or communication exists with Active Nodes, Cros-nest, Kingnodes, Lavender.Five, Notional, Polkachu, Rhino, Silk Nodes, and several other validators.
