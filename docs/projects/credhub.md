# Credhub

!!! danger "Project Archived – No Longer Maintained"

    This project has been archived and is no longer actively maintained. The decision to discontinue maintenance was made during the [TAC meeting on Feb 19, 2025](https://tac.openwallet.foundation/meetings/2025/2025-02-19/#meeting-minutes).
    
    If you are interested in taking over and reactivating the project, we encourage you to reach out to the [TAC](https://tac.openwallet.foundation/) to discuss possibilities for its future development.

    For any questions or further details, please contact the [TAC](https://tac.openwallet.foundation/).
    
## Project Description

When talking about wallets for natural persons, a lot of people think that a smartphone based wallet is the only way to go. The user should feel the security and privacy by being independent from an external provider. But we are forgetting that online based services have a great user experience in daily life:
- As a user I can use multiple clients where my data is synced, we do not have to care about backups or data recovery.
- As a developer I can implement the business logic into the cloud and only need the rendering on the client side.

Yes, when I am offline, I do not have access to my data anymore. But beside that the user experience is great!

The credhub project is a typescript based monorepo, using [nx](https://nx.dev) to manage multiple components. Compared to other approaches, it also comes with an issuer and verifier service to issue and verify credentials.

### Clients
There are two clients that can be used to interact with a cloud wallet
- a PWA based on Angular
- a Chrome Browser Extension based on Angular

While the PWA is using the camera to scan QR codes, the browser extension is scanning the opened taps for QR codes and is able to show a little button next to the QR code to interact with the wallet. This approach was inspired by password managers like 1Password. In the daily use, People do not want to take out their smartphone to scan a QR code, they want an easy one click solution.

By implementing the whole business logic in the cloud, the client is only responsible for the rendering. Therefore building new clients in other programming languages is easy by using the OpenAPI endpoints. For authentication the OpenID Connect protocol is used, the project is using the [Keycloak](https://www.keycloak.org/) server for that.

### Issuer and Verifier

Both relying parties are implemented as separate services, each of them comes with a web client for demo purposes. Further integration like webhooks or other services can be implemented in the future. The authentication is done by using the OpenID Connect protocol.

### Modular approach
The usage of NX allows reusable components with a modular approach. Each backend implementation supports low security key management by storing the keys in the filesystem or the database, or the integration with Hashicorp Vault for high security key management. Other implementations are possible.

### Identity Stack
By validating existing SSI frameworks like Credo or Veramo, this project should primary focus on the architecture reference framework of the EU. Therefore other credential formats, transport protocols or key managements like multiple DIDs methods are not supported.

**Credential Profile:**

- Credential Format: SD-JWT-VC
- Key Management (issuer): VC-ISSUER Meta data, DID, X509
- Key Management (holder): CNF (json web key)
- Transport Protocol: OID4VC
- Signature Algorithm: P-256
- Status Management: OAUTH Status List

## Source Repositories

- [openwallet-foundation-labs/credhub](https://github.com/openwallet-foundation-labs/credhub)

## Chat Channel

- [#credhub](https://discord.com/channels/1022962884864643214/1245393681901686913) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History

- [Proposal to enter Labs](https://github.com/openwallet-foundation/project-proposals/blob/ee1acec74fa98400a166f2e09452746b3998668b/projects/credhub.md) -- Approved by TAC on [2024-05-29](../meetings/2024/2024-05-29.md)
- Project archived – Decision made during the TAC meeting on [2025-02-19](../meetings/2025/2025-02-19/)
