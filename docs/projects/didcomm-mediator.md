# DIDComm Mediator Service

## Project Description

The DIDComm Mediator Service is an open-source project designed to facilitate DIDComm communication between Aries agents, particularly in situations where agents are on mobile devices, behind firewalls, or have intermittent connectivity. A DIDComm mediator serves as a persistent endpoint for client agents, allowing them to receive messages securely and efficiently, even when direct peer-to-peer communication is not possible. This allows a peer contact, such as an enterprise issuer or verifier, to initiate a messaging exchange with a mobile agent. This is a substantial improvement of the situation today, when enterprises are limited to initiating interactions or sending notifications via untrusted emails and SMSs that are often discarded as phishing attacks.

### Key Features

* **DIDComm Message Relaying**: The primary function of the DIDComm Mediator is to relay inbound DIDComm messages to client agents. It enables agents that cannot maintain an addressable endpoint to receive messages through a trusted third-party mediator, ensuring that communication remains uninterrupted. The mediator has no visibility to the embedded message being relayed.
* **Routing and Delivery**: The service offers routing capabilities, directing DIDComm messages to the correct recipient even if the recipient’s agent is temporarily offline. It queues messages and delivers them when the recipient becomes available, enhancing reliability in environments with unstable connections.
* **Extensibility and Customization**: DIDComm Mediator is designed to be flexible and customizable, allowing developers to extend its functionality according to specific use cases. It embeds the deployers' choice of ACA-Py or Credo-TS to handle the DIDComm messaging. That underlying power makes DIDComm Mediator Service adaptable to a wide range of deployment scenarios, from simple message relaying to more complex mediation tasks.
* **Community-Driven Development**: DIDComm Mediator Service is developed and maintained by a global community of contributors. This collaborative approach ensures that the service evolves in line with the needs of the broader decentralized identity ecosystem.

The service is particularly useful for agents operating on mobile devices or in environments where maintaining a constant connection is challenging. It ensures that unsolicited messages and notifications can be sent from a known peer via an established connection.

## Source Repositories

- [didcomm-mediator-service](https://github.com/openwallet-foundation/didcomm-mediator-service)

## Chat Channel
- [#didcomm-mediator-service](https://discord.com/channels/1022962884864643214/1286300013365952583) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History

- [Proposal to enter Growth stage](https://github.com/openwallet-foundation/project-proposals/blob/d05d22718371ee9ab74b2198edf28a11a014bccc/projects/didcomm-mediator.md) -- Approved by TAC on [2024-09-18](../meetings/2024/2024-09-18.md)
