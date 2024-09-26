# 2024 VC API Implementation

## Project Health

The project remains healthy.
Contributions for the initial portions of the year were focused on housekeeping items, however the project currently has development activity for functional and non-functional changes to increase the likelihood of further adoption and impact in the year ahead.

Contributions have been made by two organizations, Energy Web and Impactility.
Several forks have been made in the past year, suggesting some initial community attention.

The underlying [VC API specification](https://w3c-ccg.github.io/vc-api/) (currently developed in the context of the W3C Credentials Community Group) is active and the specification group has the intention of bringing the specification to a W3C standards track in the months ahead.

## Maintainer Diversity

The project currently has four maintainers, from two organizations, Energy Web & Impactility.

## Project Adoption

The project currently has one primary adoption organization, Elia Group. Elia continues to showcase the VC API project on their SSI demonstration site (https://ssi4energy.eliagroup.eu/en).
This is roughly the same amount of adoption as when accepted into the OpenWallet Foundation last year. 

## Goals

### Performance Against Prior Goals

The project proposal mentioned the following aims in the "Alignment with the OpenWallet Foundation Mission" section:
- Advance the adoption of interoperable and privacy enhancing digital wallets.
- Promote the development and proliferation of the VC API specification itself

Progress towards the above objectives has been small over the past year.
However, the main functional enhancement undertaken in recent months (the migration of core key & credential operations to Credo) sets up the project well for progress on the objectives in the year ahead.
For example, listing in the VC Playground (https://vcplayground.org/) is an opportunity to further both of the above objectives, however this was blocked by that lack of flexibility with JSON-LD context document loading in the implementation prior to the Credo integration.

### Next Year's Goals

The current goals of the project are to:
1. Increase use and adoption of the project, both by existing user organizations (Elia and Energy Web) and new organizations. The target metric is between 1 and 5 new organizations using the app in projects within the year.
2. Support the development of the VC API specification.
3. Provide feedback into the development of other OWF projects.

On-going and planned work items which further these goals are detailed below.

#### Migrating to Credo for key and credential operations

GitHub Issue: https://github.com/openwallet-foundation-labs/vc-api/issues/20

The benefits of this item include:
- Synergy with an existing OWF project, allowing work on the VC API implementation to feed back into other OWF work
  - Examples of this are the following GitHub issues:
    - [Credo Issue #2038- Make verifiableCredential property on W3cPresentation optional](https://github.com/openwallet-foundation/credo-ts/issues/2038) 
    - [Credo Issue #2043 - Fix W3cCredentialsApi verifyCredential types](https://github.com/openwallet-foundation/credo-ts/issues/2043)
- The ability to use load additional JSON LD contexts, unlocking new use cases
- A clearer path to supporting further VC technology such as SD-JWT and BBS signatures

Work on this item can be seen in the following PR: https://github.com/openwallet-foundation-labs/vc-api/pull/36

#### Improving documentation for technology adoption decision makers

GitHub Issue: https://github.com/openwallet-foundation-labs/vc-api/issues/29 

This item aims to improve the ability of technology selection decision makers, such as CTOs or Software Architects, to assess whether or not the VC API implementation is suitable for their use cases and technology context.
The key output is a new documentation site.

#### Listing in the VC Playground

GitHub Issue: https://github.com/openwallet-foundation-labs/vc-api/issues/28

The VC Playground is a demonstration application for Verifiable Credential issuance and verification: https://vcplayground.org.
Listing in the VC Playground is an opportunity to gain visibility on the project and test interoperability.

## Help Required

The following actions from the OWF would likely be helpful in achieving the upcoming goals:
- Advice on future architectural directions, such as transforming the project into a Credo plugin
- Notification on any publicity opportunities for the project

## Project Lifecycle Stage Recommendation

Our recommendation is to remain a Labs project.
