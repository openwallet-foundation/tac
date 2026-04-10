[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Defining Adopters

## Introduction

The **ADOPTERS** file serves as a living registry of organizations — and occasionally individuals — that actively **adopt and use OWF-hosted open source projects**. It differs from membership or contribution lists; rather, it showcases those who:

- **Use OWF technologies internally or publicly**, integrating them into their systems, platforms, or services.
- Provide **real-world validation**, demonstrating that OWF solutions are stable, scalable, and production-ready.
- May offer **feedback, use cases, or success stories**, helping guide project direction and priorities.

### Why It Matters

1. **Transparency & Credibility**  
   Displaying a diverse and growing list of adopters builds confidence in our ecosystem — signaling to others that OWF projects are trusted and battle-tested.

2. **Community Insight**  
   ADOPTERS files help the OWF Technical Advisory Council and project governance bodies understand adoption trends, key use cases, and potential areas of improvement.

3. **Recognition & Encouragement**  
   Acknowledging adopters encourages broader involvement and can motivate organizations to deepen their collaboration with OWF and OWF projects.

As OWF continues to grow, maintaining up-to-date project ADOPTERS files is instrumental in telling the story of our impact, forging stronger community bonds, and steering future development based on real-world usage.

## Definitions

Adopters of an OpenWallet Foundation (OWF) project are organizations or communities that successfully leverage the project as intended—whether integrating it into their systems, building on top of it, or offering it as a foundational component of a service or solution.

To better understand how a project is adopted, we distinguish between **direct adopters** and **transitive adopters**. For example, if a service provider uses a project from OWF as the backbone of a digital credentialing solution, the service provider is a *direct adopter*. If their customers use that solution without directly engaging with or deploying the underlying project, those customers are *transitive adopters*.

- **Direct adopters** are responsible for actively developing, packaging, configuring, or deploying the OWF project as part of their use.

- **Transitive adopters** benefit from the project indirectly but are not responsible for its integration or operation. However, if a transitive adopter gains the ability to configure or extend the project due to the service provider’s implementation, they may become direct adopters as well.

The intent of identifying adopters within the OWF community is to gain insight into real-world, production-level usage of its projects or specifications. This helps assess project maturity, community engagement, and long-term viability within the broader digital wallet ecosystem.

In some cases, original sponsoring organizations or maintainers may also be recognized as adopters. The OWF and the associated OWF projects’ technical and community leadership reserves the discretion to determine whether an adopter can offer meaningful feedback to guide the evolution of a project.

Adopters of OWF projects may include the following (noting that a single organization may fit more than one category):

- **Ecosystem Participant** – An organization actively engaged in developing, deploying, or operating one or more OWF projects.

- **Service Provider** – An entity offering OWF projects as part of a larger solution (e.g., a platform or product). This entity repackages an open source project as a core component of a service offering and sells decentralized trust services externally. Examples might include:  
  - APIs  
  - SaaS  
  - Repackaged supported software

  NOTE: A Service Provider’s customers are considered transitive adopters and should be excluded from identification within the ADOPTERS.md file.

- **Upstream or Downstream Project** – An open source project that depends on or integrates with an OWF project for functionality, compatibility, or supply chain inclusion.

- **End user** – A company or institution that uses an OWF-hosted open source technologies internally to build, deploy, and operate software, systems, or services — but does not commercially distribute, support, or sell software derived from OWF projects, nor sell related services or training. An end-user organization may not necessarily contribute upstream.

  An **end user** can also mean any individual or organization that utilizes or benefits from OWF-hosted project deliverables, and may provide feedback, requirements, or real-world usage data to guide project direction and priorities.

- **Consultancy** - an entity whose purpose is to assist other organizations in developing a solution leveraging open wallet technology. They may be embedded in the end user team and are responsible for the execution of the service. Service Providers may also provide consultancy services, they may also package open wallet technologies for reuse as part of their offerings. These function as proxies for an end user.

Projects may leverage the above guidelines to list organizations in their ADOPTERS.md file within their repo, projects are not required to identify the type of adopter in their ADOPTERS.md file; however, projects are encouraged to identify the category or categories each adopter fits under, and to list the adopter only once. This helps the OWF community track usage patterns and adoption trends more effectively.

If you’re not sure if your organization falls into any of these categories you can ask in the #tac discord channel or email [tac@lists.openwallet.foundation](mailto:tac@lists.openwallet.foundation) and we’ll help you.

## ADOPTERS.md File

### Maintenance Guidelines

Projects are encouraged to have an `ADOPTERS.md` file in the root of each of their GitHub repositories, and to keep the file **accurate and up-to-date**. Adopters are encouraged to add and remove their own entry in the ADOPTERS file via pull requests. If the adopting organization cannot find the time to submit the pull request it is also acceptable for a maintainer of the project to create the adoption record's pull request and then have someone belonging to the adopting organization's GitHub account sign off in a PR comment. This way their required level of effort is minimized.

To ensure both transparency and respect for commercially sensitive information:

- **Self-submission is preferred**: Where possible, the adopter organization should submit the pull request (PR) to add, update, or remove their entry in the ADOPTERS file.
  This ensures explicit consent for their inclusion.
- **Commercial sensitivity**: Some organizations may be unable or unwilling to disclose their technology stack publicly. In such cases, maintainers should respect this decision and only add adopters that have given explicit permission.

### Sample ADOPTERS.md File

The following is a sample `ADOPTERS.md` file (raw markdown) that projects can use as a template. Adjustments to the contents are permitted to suit the specific needs of the project, but the core elements and guidance must remain consistent to ensure clarity and uniformity across OWF projects.

```markdown
# OWF-PROJECT Adopters

An adopter of the OWF-PROJECT project is any organization that successfully leverages the OWF-PROJECT project in the manner it was intended or repackages it as a core component of a service offering. If your organization is deploying an application or service based on the OWF-PROJECT project please add your organization's name to this list. 

The OWF-PROJECT project’s intent in identifying adopters is to highlight and better understand the real-world use of the project by its operators and users. A populated adopters file helps newcomers to quickly see who is using the project, where it is being deployed, and in what kinds of environments—providing tangible evidence of community engagement and ecosystem adoption. This visibility fosters trust and confidence for potential contributors, implementers, and decision-makers. In addition, the information helps the project team gauge the maturity of the project, understand its interactions with adopters, and assess its trajectory for continued growth and relevance within the broader ecosystem.

Each entry in this file must contain:

- The name of the organization.
- A link to the website for the project or business.
- A statement describing how the organization is using the OWF-PROJECT project. The statement can include include links to public case studies or other information that describes the use of OWF-PROJECT by the organization.

Organizations are encouraged to submit issues or pull requests to add their information to this file. The maintainers would also be happy to submit a pull request to the ADOPTERS.md file on behalf of the organization based on a submitted issue. As with all pull requests, submissions will be reviewed by the project maintainers for formatting, accuracy, or duplicates. Entries will not be added without the adopter’s explicit submission or approval via an issue, pull request comment or pull request approval.

## List of Adopters

| Name          | Website       |  Statement                                       |
|---------------|---------------|--------------------------------------------------|
|  |  |  |
|  |  |  |
```

## References

- [CNCF Definitions](https://github.com/cncf/toc/blob/main/FAQ.md#what-is-the-definition-of-an-adopter)

- [OWF-PROJECT Adopters.md](https://github.com/OWF-PROJECT-ledger/OWF-PROJECT/blob/main/ADOPTERS.md)
