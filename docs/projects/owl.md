# OWL

## Project Description

OWL is an extensible set of open-source testing tools designed to validate the functionality, scalability, and interoperability of wallets and other components within the decentralized trust ecosystems. A summary of its daily interoperability test runs can be published, such as on the website [aries-interop.info](https://aries-interop.info). The test harness components are crucial for ensuring that different decentralized trust agent implementations, which are responsible for handling decentralized identifiers (DIDs) and exchanging verifiable credentials, can interoperate seamlessly. OWL currently includes support for the OWF’s Credo-TS and Bifold projects, plus the proposed ACA-Py project and other Hyperledger Aries sub-projects.

The following are the key features of OWL supported by its different tools.

- Interoperability Testing: Agent and Mobile Test Harnesses are specifically designed to test the interoperability of wallets and agents by executing interactions between them, ensuring that agent implementations can communicate using standard protocols, exchange verifiable credentials, resolve DIDs, and perform other core functions reliably.
- Load Testing: Akrida provides a scriptable framework for generating load against a deployment of agents for messaging and exchanging credentials. This allows users of OWF technologies to apply a significant generated load on their deployment to ensure it will scale as needed, and to identify and address bottlenecks.
- Automation: Agent Test Harness automates the testing of agents, making it easier for developers to continuously verify the compliance and performance of their implementations. Developers can configure what agent implementations with whom they want to test interoperability and for each, what specific tests they want executed. Implementations can even include their CI pipelines select Agent Test Harness interoperability tests.
- Extensibility: The tools are highly extensible, allowing developers to add their implementations for testing and to construct custom tests and scenarios that suit a wide variety of use cases. This flexibility is important for testing a wide range of decentralized identity solutions across different industries.
- Comprehensive Coverage: OWL covers a wide array of functionalities that decentralized trust agents should support, including secure messaging, protocols, and credential issuance, verification and revocation across a range of credential formats.
- Community-Driven: OWL is developed and maintained by a global community of contributors to ensure that it stays up-to-date with the latest standards and best practices in the decentralized identity space.

## Source Repositories

- [owl](https://github.com/openwallet-foundation/owl)
- [owl-agent-test-harness](https://github.com/openwallet-foundation/owl-agent-test-harness)
- [owl-mobile-wallet-test-harness](https://github.com/openwallet-foundation/owl-mobile-wallet-test-harness)
- [owl-akrida](https://github.com/openwallet-foundation/owl-akrida)

## Chat Channel
- [owl](https://discord.com/channels/1022962884864643214/1214965981470924911) on the [OpenWallet Foundation Discord server](https://discord.gg/openwalletfoundation)

## History

- [Proposal to enter Growth stage](https://github.com/openwallet-foundation/project-proposals/blob/33a94777a2570521205ec88413339b88fd7fb39e/projects/OWL.md) -- Approved by TAC on [2024-09-18](../meetings/2024/2024-09-18.md)
