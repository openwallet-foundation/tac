# 2024 Credo

## Project Health

Credo has seen contributions from 26 contributors over the last 12 months, of which 4 have made significant contributions (over 10 PRs merged). Well over 200 pull requests have been merged.

Overall the project is super healthy and has seen large contributions over the last year. Animo has been able to make a lot of contributions due to the participation in the German government SPRIN-D EUDI Funke Wallet Competition, which funds development of open source EUDI Wallet Prototypes. Community funded efforst have been a great way to source funding for the maintenance and development of the framework. In addition the government of Ireland has made significant contributions to the project over the last year, expanding alignment with the EU Architecture Reference Framework.

All releases made in the past year were for the 0.5.x version. We tried to minimize breaking changes. Recently we started working on 0.6.x which will provide quite extensive breaking changes. We feel these breaking changes are neccessary to stay up to date with latest advancements in the ecosystem. Once specifications stabilize we want to focus more on stabilization of APIs (we aim to reach 1.0 by either 2025 or 2026).

## Maintainer Diversity

Credo currently has 5 maintainers associated with three different organizations. One maintainer (Jakub) has been less active in contributions and reviews over the last year, but still regurarly attends working groups calls.

Two maintainers were removed (Karim, Jan) and one maintainer was added (Martin). All these maintainers are associated with Animo.

It would be good for Credo to attract a more diverse set of maintainers from different organizations.

Current state: https://github.com/openwallet-foundation/credo-ts/pull/2134
State last year: https://github.com/openwallet-foundation/credo-ts/blob/97d617d6bec10dd2e1f1ba7be94a5ab93bd1c628/MAINTAINERS.md

## Project Adoption

Last year Credo already had great adoption by both governments and private organizations. Over the last year the usage of Credo has expanded, especially related to adoption

Credo is being used by goverments in North America ([British Columbia](https://www2.gov.bc.ca/gov/content/governments/government-id/bc-wallet)), organizations in North America ([Northern Block](https://northernblock.io/blog/aip-2-interoperability), [Entidad](https://www.entidad.io/) (through Farmworker Wallet OS)), organizations in South America ([2060.io](https://2060.io/)), governments in Asia ([Bhutan](https://www.biometricupdate.com/202408/bhutans-self-sovereign-digital-id-switches-to-polygon-blockchain) through [Credebl](https://credebl.id/)), organizations in Asia ([Ayanworks](https://www.ayanworks.com/)), governments in Europe (Government of Ireland), organizations in Europe ([Animo](https://animo.id/), [ID Crypt](https://idcrypt.global)), and more. This list is not exhaustive, but based on public announcements governments and organizations have made about using Credo.

Alghtough we would like to see more large scale deployments of Credo (there are some but not many), we're really happy with the diverse adoption of the framework around the world. We think this is partly due to the support for both DIDComm/Aries as well as OpenID4VC standards.

## Goals

### Performance Against Prior Goals

A big goal of Credo over the last year been has been staying on top of latest advandcements in digital credentials. A lot of progress has been made in adding support for OpenID for Verifiable Credentials, SD-JWT VC, mDOC, DCQL (a new credential query langauge) and X509 certificates. Current work is ongoing to support OpenID Federation and in-person exchange of mDOC credentials.

In addition a lot of refactoring has been done and is being done to generalize the architecture of the framework. From being fully Hyperledger Indy / Hyperledger AnonCreds / Hyperledger Aries focussed, to providing the needed interface to support any protocol, ledger or credential format.

Pull requests to add support for DIDComm v2 have been open for over a year, and still haven't been merged. Part of the refactoring that is currently ongoing are the first steps to also get DIDComm v2 merged. We've not seen a lot of need or adoption of DIDComm v2, and therefore it's not been prioritized by any of the current contributors or maintainers.

We didn't specify specific goals last year, but we're really happy with the progress that has been made over the last year. We didn't meet our goals related to writing documentation, making it easeir to adopt the framework.

### Next Year's Goals

For 2025 Credo has a good list of ambitious goals:

- New Key Management System inteface to allow integratin with multiple crypto backends, Hardware Secure Modules, etc. Ambition is to have out of the box support for OpenBAO (open source fork of Hashicorp Vault), Google Cloud KMS, and AWS KMS.
- Add missing features and stay up to date with latest drafts and advancements in OpenID for Verifiable Credentials
- Finish and stay up to date with advancements in the High Assurance Interoperability Profile
- Remove DIDComm out of core (similar to how OpenID4VC is a plugin) and merge support for DIDComm v2
- New Credo Mediator repository that provides everything needed to deploy a highly scalable Credo DIDComm Mediator
- New and improved APIs to coverge all the different credentials formats and trust mecahnisms. A lot of new APIs have been added and with our experience using them we would like to make it simpler to leverage different credential formats, exchange protocols, and trust mecahnishms.
- New APIs for managment of revocation status lists, issuance of revocable credentials
- Assist in large scale deployments of Credo, providing caching, K8S deployment files, or whatever is needed to make it easier.
- Documentation for at least the most used features within the framework
- A lot of small things related to existing features

## Help Required

More publicity for the project. We're really happy with the support from OWF, so mostly looking to collaborate on oportunities to spread the word about Credo.

## Project Lifecycle Stage Recommendation

Still Growth due to the big refactorings and changes being made at the moment, as well as the low number of large scale deployments being out there today. Some larger deployments are in development and expected to deploy in the coming year.

A big topic for Credo in 2025 is making it ready for highly scalable server side deployments and by next year we hope to reach impact.
