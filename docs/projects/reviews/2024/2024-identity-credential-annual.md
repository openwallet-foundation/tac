# 2024 identity-credential (Identity Credential)

## Project Health

The goal of the project is to create libraries to enable easy construction
of real-world digital identity applications, including wallets, readers, and
issuance/provisioning systems.

The initial focus for this work was mdoc/mDL according to ISO/IEC 18013-5:2021
and related standards (mainly ISO 23220 series and ISO 18013-7) but the
current scope also include other credential formats (including SD-JWT VC)
and presentation and provisioning protocols (ISO, OpenID, and
[W3C Digital Credentials](https://wicg.github.io/digital-credentials/))

The project is healthy and contributions have increased steadily over the
past 12 months. Several individuals are contributing code on a regular
basis.

## Maintainer Diversity

The project has 9 maintainers on file and they all work for Google. This is
an increase from last year where we had around 5 maintainers.

## Project Adoption

Several entities use these libraries in one shape or another, the most
prominent examples being [Google Wallet](https://wallet.google/) and the
[EUDI Wallet Reference Implementation](https://github.com/eu-digital-identity-wallet/.github/blob/main/profile/reference-implementation.md).
The code is also used in several other places, including both wallet and
reader applications.

Google is using this code as a base for its participation in the
[SPRIN-D EUDI Wallet Funke competition](https://www.sprind.org/en/impulses/challenges/eudi-wallet-prototypes).

## Goals

### Performance Against Prior Goals

By the beginning of 2024, the team set out the following goals of which all
are almost 100% completed:

- Conversion to Kotlin: All code was ported from Java.
- SD-JWT support: Completed (and show-cases in SPRIN-D Funke)
- Wallet Server: Designed and implemented a wallet backend.
- Cloud Secure Area: Designed and implemented a Cloud Secure Area.
- Wallet rewrite: We rewrote the sample app included in our repo to showcase how to best use the libraries
- W3C Digital Credentials API: The project served as a test-bench for the Android/Chrome engineers working on this as well as the rest of the ecosystem.
- iOS support: Partially completed, expected to be 100% complete early next year.
- Releasing: We made two releases, one in August and one in November.

### Next Year's Goals

The tentative goals for 2025 include

- New name
- Convert Wallet App to Compose Multiplatform, for iOS support.
- Add module/extension system
- Address technical debt, stabilize code
- Work on developer documentation
- Regular releases (every two months or so)
- Publish Wallet App to Google Play and Apple App Store
- Stand up Wallet Server (for Wallet App instances from marketplaces to connect to)
- Stand up test issuers / relying parties (for Wallet App instances to use)
- Implement ZKP protocols: We are working with cryptographers and SDOs on devising new presentation protocols based on Zero-Knowledge Proofs.

## Help Required

The project is in good shape and does not require any help at the moment.

## Project Lifecycle Stage Recommendation

Most of the work done in 2024 was about creating a solid foundation for
future work, including converting to Kotlin Multiplatform. We are almost
done with  this but not quite and we expect a couple of additional iterations
of changes. As such we'd like to stay in the Labs stage for the next year.
