# Chandra Station Services Available

## Table of Contents

- [Overview](#Overview)
- [Infrastructure](#Infrastructure)
  - [Hardware](#Hardware)
  - [Cloud](#Cloud)
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

- ### Hardware

  - We deploy and maintain hardware throughout the United States with our main deployment in Phoenix Arizona at a Tier IV data center, Aligned Phoenix. At Aligned, we have deployed a diverse range of servers from Dell PowerEdges to custom Supermicro builds.
    - Build Flavors:
      - Dell PowerEdge R620 (XEON)
      - Dell PowerEdge R815 (XEON)
      - Supermicro X14 Cloud DC (XEON Silver 4314 CPU)
      - Supermicro X12 (XEON Silver 4216)
      - Lenovo ThinkSystem SR635 (AMD EPYC 7302P)
      - ASUS RS700A-E10-RS12 (AMD EPYC 7402)
      - Supermicro SYS-221GE-TNHT-LCC (2x Nvidia HGX H100)
      - DIY CHASIS (RTX4090)

- ### Cloud

  - We maintain a large amount of cloud infrastructure primarly as backups or to connect to geographically isolated networks. Our cloud infrastructure is deployed on HETZER, AWS, and Digital Ocean. Our cloud machines are also configured in multiple flavors to provide the best performance for the network they are connected to.

- ### Public Endpoints
  - Endpoints for each supported network are deployed without rate limits, offering 1G up and down connections. Examples of our most used public endpoints are canto and gravity bridge. **_All our nodes are deployed on our machines with an exception for networks that are geographically isolated to one region._** More information on our public endpoints can be found on our [website](https://www.chandrastation.com/services?tabIndex=0).
- ### Data Indexers
  - We have developed and deployed an extremely performant indexer for Cosmos blockchains in Rust, it is currently used in production to store and sort all Gravity Bridge transaction data and serve that data to various applications. You can view more information about the indexer or fork it and run it on your own chain [here](https://github.com/ChandraStation/cosmos-indexer). We offer indexing your chain as a service or can help you deploy your own indexer.
- ### Validators
  - Chandra Station is a validator for multiple Cosmos networks. We use a multi sentry node configuration behind a VPN and TMKMS or Horcrux depending on the network specifications. **_All our nodes are deployed on our machines with an exception for networks that are geographically isolated to one region._**
- ### White-label
  - Our white label solution is extremely selective, only onboarding clients who aim to bring value to the network such as institutional investors and KOLS. Our current clients are Ovrclk, Horizon Law, Altcoin Psycho, and Four Moons Capital. These clients receive the same infrastructure as Chandra Station, hosted on similarly configured servers.

## Software Development

Chandra Station has expertise in a range of technologies including React, Bun, Node, Express, Vite, Typescript, Javascript, Rust, Cosmology's stack, Solidity, Python, and various CSS frameworks. Our focus is on building and maintaining software primarily for Cosmos and EVM-based networks like Ethereum, Akash, Canto, and Arbitrum.

- ### Front-end

  Our most used frameworks and langauges for front-end development: Typescript, Javascript, Vue, React Native, React, Chakra-Ui, Tailwind, Element, Css, Vite, Bun.

  - [**Manifest App**](https://manifest-app-delta.vercel.app/): The web application for the Manifest Network a Cosmos SDK chain built with the PoA & Group module. The application allows users to create, manage, and participate in groups, the Proof of Authority Admin to manage the network, and interfacing with the tokenFacotry & bank modules.

  - [**Quicksilver**](https://github.com/notional-labs/quicksilver/tree/main/web-ui) V2 Web App: An in-house developed liquid staking and governance dashboard for Quicksilver V2.

  - [**althea.link**](https://chalabi2.github.io/althea-app): A reworked, deployed, and maintained version of canto.io designed for Althea, featuring a custom built multi-validator staking solution.

  - [**gravitypulse.app**](https://gravitypulse.app): An analytics dashboard for Gravity Bridge.

  - [**bridge.gravitypulse.app**](https://bridge.gravitypulse.app): A modified version of Cosmostation's original Gravity Bridge web app, known as "Space Station".

  - [**auction.gravitypulse.app**](https://auction.gravitypulse.app): An application that allows you to bid on Gravity Bridge fee auctions.

  - [**CCR App**](https://chalabi2.github.io/ccr-ui): Allows users to register their Canto Clusters.

  - [**Playmos**](https://playmos.app): Currently closed source, an evm based web3 casual gaming experience.

- ### Back-end

  Our most used frameworks and langauges for back-end development: Rust, Express, Nodemon, Node.js, Bun, Solidity, Go.

  - **Chandra Station Operations**: Our overall infrastructure and operations to support our validators, public endpoints, and other services.
  - [**Gravity Pulse Backend**](https://github.com/Gravity-Bridge/gravity-info-api/tree/main/gravity-info-server): A Cosmos block indexer developed in Rust tweaked for Gravity Bridge.
  - [**Cosmos Indexer**](https://github.com/ChandraStation/cosmos-indexer): A performant Cosmos SDK block indexer.
  - [**Neons Dao Refund**](https://github.com/chalabi2/neons-refund): A smart contract designed to refund NFT holders
  - [**Chandra Station Endpoints**](https://www.chandrastation.com/services?tabIndex=1): Utilizes nginx and Express to enable automatic state-sync, snapshot, load balancing, and reverse proxying for multiple nodes.
  - [**Playmos**](https://playmos.app): Currently closed source, an evm based web3 casual gaming experience.
  - [**Manifest Network**](https://github.com/liftedinit/manifest-ledger): A CosmosSDK chain built with the PoA module.

- ### Blockchain Development

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

  _Case Study: [Manifest Network](https://github.com/liftedinit/manifest-ledger)_

## Networking

Chandra Station participates in various validator subgroups, including the Good Validators Association, or the GVA, and the Bare Metal Alliance. We maintain strong ties with a diverse range of validators, differing in staked value and technical expertise. Ongoing collaboration or communication exists with Active Nodes, Cros-nest, Kingnodes, Lavender.Five, Notional, Polkachu, Rhino, Silk Nodes, and several other validators.
