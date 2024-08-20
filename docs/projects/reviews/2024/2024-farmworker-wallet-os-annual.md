# 2024 Farmworker Wallet OS (FWOS)

## Project Health

The Farmworker Wallet OS is an ecosystem of modules that enable the development of a Native Wallet Agent and a Cloud Wallet Agent in the low-code platform [Mendix](https://www.mendix.com). The FWOS project remains healthy and active with one reference implementation deployed to a production environment and a second implementation soon to be released in Q3. As noted in our original project [proposal](https://tac.openwallet.foundation/projects/fwos/), the FWOS project has been focused on building interoperability with [Aries](https://hyperledger.github.io/aries-rfcs/latest/) digital trust ecosystems. We continue to build our low-code SDK components on top of [Credo](https://github.com/openwallet-foundation/credo-ts) and have completed ~90% coverage of Aries Interoperability Profiles 1 and 2. To date, the project has successfully completed 4 upgrades of the Credo toolkit (v0.4.2, v0.5.3, v0.5.6, v0.5.9) and are actively working on the upgrade to v0.5.10. This is important as it highlights the ability for this project to stay up to speed with the rapid rate of change of the underlying standards and open-source toolkits that this project depends on.

## Maintainer Diversity

Contributions to the FWOS have been primarily from the [Entidad](https://www.entidad.io) development team. A couple of inquiries have come in via the project [Discord](https://discord.com/channels/1022962884864643214/1138937641123987466) channel with interest in participation but we have no concrete knowledge of any work done outside of the contributions from the project maintainers. We did add a new [maintainer](https://github.com/Entidad/farmworker-wallet-os/blob/main/MAINTAINERS.md) internally who helped us with the implementation of the [DIDComm Survey](https://didcomm.org/survey/0.1/) protocol recently submitted as a proposal. This demonstrates that a traditional Mendix developer is able to learn and understand the underlying Aries and DIDComm architectures and contribute to the implementation of a new DIDComm protocol after only a few weeks of knowledge transfer and experimentation.

## Project Adoption

The FWOS project has one reference implementation deployed to a production environment in February 2024. This release consisted of a mobile agent implemented on version 0.4.2 of the open-source Aries Framework JavaScript (AFJ) toolkit. Note that AFJ rebranded to Credo after it was accepted into the OpenWallet Foundation. Although no digital trust interactions were enabled outside of wallet onboarding and agent initialization, this first release was significant as it allowed us to demonstrate the viability of having the FWOS wallet engine running at scale within the target end-user community.

## Goals

### Performance Against Prior Goals

The goal of the Farmworker Wallet OS project is to promote the adoption of mobile (native) and cloud wallets. We are proud of the progress achieved to date in producing a stable production ready wallet holder toolkit that enables Mendix developers to jumpstart the integration of digital trust technologies with their Mendix native apps. The following collection of trust protocols have been implemented this year:

- [DID Exchange v1](https://github.com/hyperledger/aries-rfcs/tree/main/features/0023-did-exchange)
- [Out-of-Band Protocol v1](https://github.com/hyperledger/aries-rfcs/tree/main/features/0434-outofband)
- [Issue Credential v1](https://github.com/hyperledger/aries-rfcs/tree/main/features/0036-issue-credential)
- [Present proof v1](https://github.com/hyperledger/aries-rfcs/tree/main/features/0037-present-proof)
- [Mediator coordination protocol v1](https://github.com/hyperledger/aries-rfcs/tree/main/features/0211-route-coordination)
- [Message Pickup v1](https://github.com/hyperledger/aries-rfcs/tree/main/features/0212-pickup)
- [Basic Message](https://github.com/hyperledger/aries-rfcs/tree/main/features/0095-basic-message)
- [Question Answer v1](https://didcomm.org/question-answer/1.0)
- [Issue Credential v2](https://github.com/hyperledger/aries-rfcs/tree/main/features/0453-issue-credential-v2)
- [Mediator coordination protocol v2](https://didcomm.org/coordinate-mediation/2.0/)
- [Present proof v2](https://github.com/hyperledger/aries-rfcs/tree/main/features/0454-present-proof-v2)
- [Message Pickup v2](https://didcomm.org/messagepickup/2.0)
- [Out-Of-Band Protocol v2](https://identity.foundation/didcomm-messaging/spec/#out-of-band-messages)
- [Basic Message v2](https://didcomm.org/basicmessage/2.0)
- [Discover Features v2](https://didcomm.org/discover-features/2.0)
- [Media Sharing](https://didcomm.org/media-sharing/1.0)
- [DIDComm Remote Procedure Call](https://github.com/hyperledger/aries-rfcs/tree/main/features/0804-didcomm-rpc)
- [Survey protocol proposal](https://didcomm.org/survey/0.1/)
- [did:web AnonCreds Method](https://github.com/2060-io/did-web-anoncreds-method/blob/main/spec.md)
- [~~cheqd DID Method~~](https://docs.cheqd.io/product/architecture/adr-list/adr-001-cheqd-did-method) `deprecated`

For the remainder of the 2024 year, the project hopes to commence implementing support for AnonCreds presentation exchange over Bluetooth supported by:

- [DIDComm over Bluetooth](https://github.com/decentralized-identity/didcomm-bluetooth/blob/main/spec.md)
- [Bluetooth Low Energy transport for Credo](https://www.npmjs.com/package/@credo-ts/transport-ble)

Additionally, the project hopes to initiate exploration and prototyping of a mobile driver's license verifier component (ISO mDL 18013-5 and ISO 18013-7: mdoc + OID4VP or Digital Credentials API).

#### FWOS Native Agent Architecture

![Farmworker Wallet OS Native Agent Architecture]https://github.com/Entidad/farmworker-wallet-os/blob/main/img/fwos-architecture-native-agent.png)

### Next Year's Goals

For the next year, the FWOS project aims to introduce cloud agent components to support credential Issuer and Verifier use cases. This work is already in-progress and will be integrated formerly into the FWOS toolkit:

- [DigitalID SDK](https://marketplace.mendix.com/link/component/227014)
- [DIDComm SDK](https://marketplace.mendix.com/link/component/226667)
- [AnonCreds VC SDK](https://marketplace.mendix.com/link/component/227012)
- [Paradym Connector](https://marketplace.mendix.com/link/component/226659)


#### FWOS Cloud Agent Architecture

![Farmworker Wallet OS Cloud Agent Architecture]https://github.com/Entidad/farmworker-wallet-os/blob/main/img/fwos-architecture-cloud-agent.png)

## Help Required

The project is advancing steadily and does not require any help at the moment.

## Project Lifecycle Stage Recommendation

The project is recommended to remain in the Labs stage.
