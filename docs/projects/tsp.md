# Trust Spanning Protocol

## Project Description

This project is an early impementation of the [draft Trust Spanning Protocol (TSP)](https://github.com/trustoverip/tswg-tsp-specification).

According to the above referenced specification, "The Trust Spanning Protocol (TSP) facilitates secure communication between endpoints with potentially different identifier types, using message-based exchanges. As long as these endpoints use identifiers based on public key cryptography (PKC) with a verifiable trust root, TSP ensures their messages are authentic and, if optionally chosen, confidential. Moreover, it presents various privacy protection measures against metadata-based correlation exploitations. These attributes of TSP together allow endpoints to form authentic relationships rooted in their respective verifiable identifiers (VIDs), viewing TSP messages as virtual channels for trustworthy communication.
".

A shorter introduction of TSP can be found in [this blog post](https://www.trustoverip.org/blog/2023/08/31/mid-year-progress-report-on-the-toip-trust-spanning-protocol/).

This project's current code includes a Rust implementation of all TSP features. We also plan to incorporate/develop related features such as additional Verifiable Identifier types, additional transport layer mechanisms, different language bindings as needed and integration modules needed to be compatible with other OpenWallet projects.

In addition, we may add and welcome trust task or application specific extensions.

## Source Repositories

- [openwallet-foundation-labs/tsp](https://github.com/openwallet-foundation-labs/tsp)

## Chat Channel

- [#tsp](https://discord.com/channels/1022962884864643214/1240339063618277467) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History

- [Proposal to enter Labs](https://github.com/openwallet-foundation/project-proposals/blob/cbdd0477bf98b48d1790d6b5dcbff043db001a4d/projects/rust-tsp.md) -- Approved by TAC on [2024-05-15](../meetings/2024/2024-05-15.md)
