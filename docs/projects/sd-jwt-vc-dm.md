# SD-JWT Verifiable Credentials Data Model

## Project Description

This project aims to provide a reference implementation of the [SD-JWT VC DM](https://github.com/danielfett/sd-jwt-vc-dm) (Selective Disclosure JWT Verifiable Credentials Data Model) specification in TypeScript/JavaScript. SD-JWT VC DM combines the best features of SD-JWT VC and W3C VCDM, offering:

- Selective disclosure capabilities with compact payloads
- Support for schemas and vocabularies
- Compatibility with JSON-LD payloads
- Alignment with JAdES signature standards
- Support for various credential types (Simple credentials, PID, ELM, etc.)

Key features of this implementation:

- Platform-agnostic implementation (works in Node.js, browsers, React Native)
- Modular architecture separating core functionality from platform-specific features
- Pluggable cryptographic interface ("bring your own crypto")
- Support for both compact and JSON serialization formats
- Implementation of all SD-JWT VC DM features including type metadata, schemas, and JAdES signatures
- Comprehensive test suite covering all specification requirements

## Source Repositories

- [openwallet-foundation-labs/sd-jwt-vc-dm](https://github.com/openwallet-foundation-labs/sd-jwt-vc-dm)

## Chat Channel

- [#sd-jwt-vc-dm](https://discord.com/channels/1022962884864643214/1331889781570932849) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History

- [Proposal to enter Labs](https://github.com/openwallet-foundation/project-proposals/blob/7fae7c84f57f0c6a2d1c6f1d469b281dc38283d5/projects/sd-jwt-vcdm.md) -- Approved by TAC on [2025-01-23 via GitHub](https://github.com/openwallet-foundation/project-proposals/pull/52)