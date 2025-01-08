# OpenID Federation TypeScript

## Project Description
Trust is still a complex and relatively unsolved topic in the decentralized identity, EU Identity Wallet and digital credential ecosystems.

OpenID Federation defines basic components used to build multilateral federations for building trust infrastructure.

OpenID Federation TypeScript is a generic, and low-level implementation of the OpenID Federation specification, with a focus on [OpenID Federation Wallet Architecture](https://openid.net/specs/openid-federation-wallet-1_0.html). Currently it provides APIs for creating and resolving of entity configuration and statements. In the coming months support will be added for metadata policies and trust marks.

The goal of this library is to provide minimal and reusable primitives for building a federation client or server. This keeps the dependencies minimal, while also making it less opinionated. Dependent libraries or frameworks (such as Credo) can provide the needed hosting of endpoints, signing callbacks, and persistence.

The library was created by Animo as part of the SPRIN-D Funke wallet competition.

## Source Repositories
- [openwallet-foundation-labs/openid-federation-ts](https://github.com/openwallet-foundation-labs/openid-federation-ts)

## Chat Channel
- [#openid-federation-ts](https://discord.com/channels/1022962884864643214/1326618196245221426) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History
- [Proposal to enter labs stage](https://github.com/openwallet-foundation/project-proposals/blob/d206049c0533093733d468e908987a4f7d77b89d/projects/openid-federation-ts.md) -- Approved by TAC on [2025-01-08](../meetings/2025/2025-01-08.md)