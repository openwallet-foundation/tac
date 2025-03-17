# VCX

## Project Description
VCX is an open-source codebase that provides a wide suite of Rust modules for building DID & Aries-related applications (client/mobile and server). VCX is designed with a heavily modularized structure (20+ crates in the workspace) such that consumers can pick-and-choose which components they wish to build their DI application with. Currently, some of the significant modules provided by VCX include:
* `did_doc`, `did_parser`, `did_resolver` - a set of lightweight libraries which provide well-typed structures and interfaces for DID building, parsing, and resolving. We envision these components becoming defacto libraries for Rust projects involving DIDs.
* DID Method Crates - several DID method-specific crates for resolving and managing DIDs (peer, cheqd, web, key, jwk, sov/unqualified).
* `aries_vcx_ledger`, `aries_vcx_wallet`, `aries_vcx_anoncreds` - a set of libraries with interfaces for performing ledger, wallet, and anoncred operations involved in Aries protocols. Includes implementations for Indy & Cheqd ledgers (i.e. resolving anoncreds objects), Askar wallets, and anoncreds-rs.
* `messages` - well-typed library for building and parsing Aries (DIDComm V1) messages
* `aries_vcx` - Implementation of Aries protocol state machines, which provide APIs to step through Aries protocols, utilizing lots of the above-mentioned modules. Currently mostly for AIP1 protocols, but some AIP2 protocols such as DIDExchange/OOB.

VCX has a long history, it has been around since 2017 and is one of the first implementations of an Aries protocol-compliant library, and was originally embedded in the Indy SDK. In 2020, the project was moved into a dedicated Hyperledger project by Absa Group, beginning a new era of development beyond the Indy SDK. Anonyome Labs joined the Hyperledger project in 2022 and the project has been maintained since. VCX has been actively involved in the Aries community, including fortnightly community meetings, and previous participation in Linux Foundation Mentorship programs.

VCX has been used in industry projects, including mediator & cloud applications previously at Absa, and is a core component behind [Anonyome Lab's DI Edge Agent Mobile SDK](https://anonyome.com/resources/blog/aries-vcx-anonyomes-commitment-to-decentralized-identity/). Instnt is also building using VCX as a key component for their Multipass product.
## Source Repositories
- [https://github.com/openwallet-foundation/vcx](https://github.com/openwallet-foundation/vcx)
## Chat Channel
[#vcx](https://discord.com/channels/1022962884864643214/1344319756324311123) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)
## History
- Proposal to OWF TAC: [https://github.com/openwallet-foundation/project-proposals/pull/54/files](https://github.com/openwallet-foundation/project-proposals/pull/54/files) -- Approved by OWF TAC on 19 February 2025
