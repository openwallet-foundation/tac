# Multiformat VC for iOS

## Project Description

Pure Swift package for creating Verifiable Credentials (VCs) in multiple formats

- SD-JWT VC: Selective Disclosure JWT based Verifiable Credentials - using the specification defined at https://datatracker.ietf.org/doc/draft-ietf-oauth-sd-jwt-vc/
- VC JWT: Verifiable Credentials as JWT - using the format defined at JWT VC Presentation Profile https://identity.foundation/jwt-vc-presentation-profile/

Support for multiple data types for disclosed values including

- String
- Int
- Boolean
- Array of Strings - [String]
- Dictionary of String keys and String values - [String:String]

This project is a contribution of the work done at Ping Identity to test and establish interoperability of the various formats representing the Verifiable Credentials Data Model https://www.w3.org/TR/vc-data-model/. Along with the SD-JWT VC and JWT VC formats described above, Ping Identity has also participated in the interoperability event for OpenID4VP to present a VC JWT. That code will also be released as a part of this project.

## Source Repositories

[openwallet-foundation-labs/multiformat-vc-ios](https://github.com/openwallet-foundation-labs/multiformat-vc-ios)

## Chat Channel
- [#multiformat-vc-ios](https://discord.com/channels/1022962884864643214/1199766370880069762) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History

- [Proposal to enter Labs](https://github.com/openwallet-foundation/project-proposals/blob/13967e30a67df0289b1e4bfaff0491167aad0647/projects/multiformat-vc-ios.md) -- Approved by TAC on [2024-01-24](../meetings/2024/2024-01-24.md)
