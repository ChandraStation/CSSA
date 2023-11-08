# Chandra Station Services Available

## Table of Contents

- [Overview](#Overview)
- [Infrastructure](#Infrastructure)
  - [Hardware](#Hardware)
  - [Public Endpoints](#Public-endpoints)
  - [Data Indexers](#Data-Indexers)
  - [Validators](#Validators)
  - [White-label](#White-Label)
- [Software Development](#Software-Development)
  - [Front-end](#Front-end)
  - [Back-end](#Back-end)
  - [Blockchain Development](#Blockchain-Development)
- [Networking](#networking)


## Overview
Chandra Station specializes in infrastructure management and web application development. We are amongst the largest deployers of our own dedicated hardware in the Cosmos ecosystem. Alongside our focus on infrastructure we also develop and maintain multiple web apps for a basket of different ecosystems. Our combined expertise enables us to handle billions of API requests every month, maintain safe and reliant validators, and develop applications that facilitate better user interactions with blockchain systems.

## Infrastructure
We deploy and maintain hardware throughout the United States with our main deployment in Phoenix Arizona at a Tier IV data center, Aligned Phoenix. At Aligned, we have deployed a diverse range of servers from Dell PowerEdge to custom Supermicro builds.

* ### Hardware
    * We deploy and maintain hardware throughout the United States with our main deployment in Phoenix Arizona at a Tier IV data center, Aligned Phoenix. At Aligned, we have deployed a diverse range of servers from Dell PowerEdge to custom Supermicro builds.
    
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
    Our most used frameworks and langauges for front-end development: Typescript, Javascript, Vue, React Native, React, Chakra-Ui, Tailwind, Element, Css, Vite, Bun.
    * [**Gravity Pulse**](https://gravitypulse.app): An analytics dashboard for Gravity Bridge.

    * [**Gravity Pulse Bridge**](https://bridge.gravitypulse.app): A modified version of Cosmostation's original Gravity Bridge web app, known as "Space Station".

    * [**Althea.io**](https://chalabi2.github.io/althea-app): A reworked, deployed, and maintained version of canto.io designed for Althea, featuring a custom built multi-validator staking solution.
   
    * [**CCR App**](https://chalabi2.github.io/ccr-ui): Allows users to register their Canto Clusters.
    

    * [**Quicksilver**](https://github.com/notional-labs/quicksilver/tree/main/web-ui) V2 Web App: An in-house developed liquid staking and governance dashboard designed for Quicksilver V2.
    
    
    * [**Apollo**](): An older version of ping.pub, slated for an upgrade to ping.pub v2.
    
    <img src="https://hackmd.io/_uploads/rJmxhQzXp.png" alt="Gravity Pulse" width="300" height="150">
   
    <img src="https://pbs.twimg.com/media/F9QP9SXb0AAKYbJ?format=jpg&name=4096x4096" alt="Quicksilver" width="300" height="150">
    
    <img src="https://hackmd.io/_uploads/rk6E6mM7a.png" alt="althea app" width="200" height="250">
    
     <img src="https://hackmd.io/_uploads/SyTNpXfXT.png" alt="althea app" width="200" height="250">
     

* ### Back-end
    Our most used frameworks and langauges for back-end development: Rust, Express, Nodemon, Node.js, Bun, Solidity, Go.
    * [**Gravity Pulse Backend**](https://github.com/Gravity-Bridge/gravity-info-api/tree/main/gravity-info-server): A Cosmos block indexer developed in Rust.
    * [**Neons Dao Refund**](https://github.com/chalabi2/neons-refund): A smart contract designed to refund NFT holders
    * [**Chandra Station Endpoints**](https://www.chandrastation.com/services?tabIndex=1): Utilizes nginx and Express to enable automatic state-sync, snapshot, load balancing, and reverse proxying for multiple nodes.
    * [**Playmos**](https://playmos.app): Currently closed source, an evm based web3 casual gaming experince

* ### Blockchain Development
    Chandra Station offers a comprehensive platform for launching Cosmos SDK-based blockchains. We serve in advisory, development, and community management roles, with a profound expertise in Cosmos governance.

    We've successfully launched multiple chains and played significant roles, whether as genesis validators, contributors, or organizers, for prominent projects like Osmosis, Gravity, and Canto, among others.

    Every chain launch is unique, and we tailor our approach accordingly. Our services encompass fundamental Cosmos SDK development, backend infrastructure, and the orchestration of genesis events. We specialize in IBC (channels, connections, and relaying), IBC infrastructure, basic block explorers, validator sets, white-label validators, as well as Dapps for various chain interactions such as staking, governance and any custom chain features.

    Here is an in depth description of all the services we provide as it relates to the Cosmos SDK and building/deploying blockchains

    1. **Fundamental Cosmos SDK Development**: We offer core Cosmos SDK development services, ensuring that your blockchain is built on a solid foundation with the latest features and enhancements.
    
    2. **Genesis Event Coordination**: As previously mentioned we have participated in and/or coordinated genesis events for many large Cosmos networks. This includes but is not limited to, infrastructure, genesis file management, gentx, tokenomics and development.

    3. **Backend Infrastructure**: We deploy all the necessary infrastructure to ensure a smooth launch and operational chain.

    4. **Deploying IBC connections**: We specialize in IBC, covering aspects such as channel creation, connections, and relaying, facilitating seamless communication between blockchains.

    5. **IBC Infrastructure**: We provide the infrastructure needed to make IBC functionality a reality, enabling secure data transfer between interconnected blockchains.

    6. **Basic Block Explorers**: We operate and manage a customized version of the widely-used multi-chain block explorer, Ping.pub, tailored for Cosmos. This empowers us to promptly provide an extensive and feature-rich block explorer for any Cosmos chain or to develop a unique, one-of-a-kind explorer to meet specific needs.

    7. **Validator Sets**: We have a wide reach in the Cosmos ecosystem and are in daily communication with the best of the best for validators and infrastructure providers.

    8. **White-Label Validators**: We provide ready-made "white-label validator" solutions that are currently being utilized by foundation nodes, financial partners, and influencers.

    9. **Dapps for Chain Interactions**: We develop Dapps tailored for various chain interactions, including staking, governance, and any custom chain features, enhancing the functionality of your blockchain.

## Networking
Chandra Station participates in various validator subgroups, including the Good Validators Association, or the GVA, and the Bare Metal Alliance. We maintain strong ties with a diverse range of validators, differing in staked value and technical expertise. Ongoing collaboration or communication exists with Active Nodes, Cros-nest, Kingnodes, Lavender.Five, Notional, Polkachu, Rhino, Silk Nodes, and several other validators.
