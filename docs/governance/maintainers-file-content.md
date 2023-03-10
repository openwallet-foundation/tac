[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# MAINTAINERS.md File Contents
All OpenWallet Foundation projects MUST have a `MAINTAINERS` file (`MAINTAINERS.md` or `MAINTAINERS.rst`) at the top-level directory of the source code. This document will provide specifics on what to include in the `MAINTAINERS` file.

## List of Project Maintainers
The first thing that MUST be included in the `MAINTAINERS` file is a list of the project's maintainers, both active and emeritus.

It is recommended that the lists be sorted alphabetically and contain the maintainers name, GitHub ID, LFID, Chat ID, Email, Company Affiliation, and Scope.

!!! success "Important"
    * The email for a maintainer MUST be specified and be a reliable mechanism to contact the maintainer.
    * Scope is dependent on the project and may not exist for a given project. Scope could be the whole project, a specific repository, specific directories in a repository, or high-level description of responsibility (e.g., Documentation).

The following shows the suggested format for the information:

!!! example
    **Active Maintainers**

    | Maintainer | GitHub ID | LFID | Email | Chat ID | Company Affiliation | Scope |
    | ---------- | --------- | ---- | ----- | ------- | ------------------- | ----- |
    |            |           |      |         |       |                     |       |

    **Emeritus Maintainers**

    | Maintainer | GitHub ID | LFID | Email | Chat ID | Company Affiliation | Scope |
    | ---------- | --------- | ---- | ----- | ------- | ------------------- | ----- |
    |            |           |      |         |       |                     |       |

## What Does Being a Maintainer Entail
The `MAINTAINERS` file SHOULD contain information about the different types of maintainers that exist (whole project, repo, part of repo) and what their duties are (e.g., maintainers calls, quarterly reports, code reviews, issue cleansing).

## How to Become a Maintainer
The `MAINTAINERS` file SHOULD contain information about how to become a maintainer for the project. This section SHOULD list specific information about what is required. Information that SHOULD be included in this section:

* What is required before someone can be considered to become a maintainer
* Consider whether there should be different requirements based on the scope (whole project, repo, part of repo) of maintainership
* Whether sponsorship by an existing maintainer is required
* How maintainers are proposed to the community. A number of open source projects require that a PR be done against the `MAINTAINERS` file to make this proposal
* How many maintainers must approve the proposed maintainer. This should include information about what happens if someone vetoes the proposal
* How long the existing maintainers have to respond to the proposal

## How Maintainers are Removed or Moved to Emeritus Status
The `MAINTAINERS` file SHOULD contain information about how a maintainer is removed from the list of active maintainers. Information that SHOULD be included in this section:

* What are the reasons a maintainer would be removed from the list of active maintainers
* How this is proposed; similar to the way in which maintainers are added, one way to do this is via a PR against the `MAINTAINERS` file
* How an emeritus maintainer becomes active again

## Credits

This document is based on the [Hyperledger Foundation's MAINTAINERS guideline](https://toc.hyperledger.org/guidelines/MAINTAINERS-guidelines.html).
