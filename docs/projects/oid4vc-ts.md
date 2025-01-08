# OID4VC TypeScript

## Project Description
The OpenID for Verifiable Credentials set of standards provide integration of existing OpenID and OAuth2 standards with verifiable credentials.

OID4VC TypeScript is a generic, and low-level implementation of specifications. Currently it provides APIs for Issuers, Wallets, Clients, Authorization Servers and Resource Providers, covering OpenID for Verifiable Credential Issuance, and OAuth2. In addition, it supports a wide range of other OAuth2 related specifications for interoperability and security (such as Pushed Authorization Requests, Demonstrating Proof of Possesion, and PKCE).

Having experience with integration of these standards into another OWF project, Credo, we were able to create a lower-level reusable library that handles the complex parts of the specification, while still allowing full control over the full flow.

In the coming months this project will be extended with support for OpenID for Verifiable Presentations and related specifications.

The goal of this library is to stay as agnostic as possible to the credential formats being used. This keeps the dependencies minimal, while also making it less opinionated. Dependent libraries or frameworks (such as Credo) can provide the needed credential formats, crypto suites, and persistence.

The library was created by Animo as part of the SPRIN-D Funke wallet competition.

## Source Repositories
- [openwallet-foundation-labs/oid4vc-ts](https://github.com/openwallet-foundation-labs/oid4vc-ts)

## Chat Channel
- [#oid4vc-ts](https://discord.com/channels/1022962884864643214/1326616895453007933) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History
- [Proposal to enter labs stage](https://github.com/openwallet-foundation/project-proposals/blob/ec783163aa71ebafe82068fbef75dcb5cc20a86c/projects/oid4vc-ts) -- Approved by TAC on [2025-01-08](../meetings/2025/2025-01-08.md)
