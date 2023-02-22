[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Security Policies

## Vulnerability Management Team
The OpenWallet Foundation's Vulnerability Management Team (VMT) is responsible for managing vulnerability reports for the OWF's projects.

### Team Members

* Two volunteer developers from each OWF project will serve on the security team.
* Each volunteer will have a 12 month commitment to the security team.

### Responsibilities
The VMT has the following responsibilities:

* help triage and respond to reports following the [responsible disclosure policy](#responsible-disclosure).
* keep the reporter informed of the status of their report by sending updates at a minimum of once per week.

## Responsible Disclosure

* 48 working hours to respond to reporter acknowledging the report.
* 1 week to triage, report, and coordinate with the affected project maintainers to plan the fix of the bug.
* 90 days to fix and release a fix or disclose the security bug.
* Any "critical" errors shall be assigned a CVE number and disclosed through the formal CVE system.

!!! example "Example Acknowledgment Response"
    Dear _hacker_,

    Thank you for your recent report of a security bug. I am emailing to let you know that we are in the process of investigating your report and will reply to you again when we have determined the validity of your report. We may have further questions that come up as part of our investigation. We appreciate your contribution to _project name_.

    Thank you,

    _your name_

!!! example "Example Update"
    Dear _hacker_,

    I'm emailing to let you know that we have confirmed your bug report as a valid security concern and have filed a bug in our system. We will keep you informed of the status of the bug.

    Thank you,

    _your name_

## Security Markdown
Each project must have the following information included in the `SECURITY.md` file at the root of the project:

```
# How to Report a Security Bug
To report a security issue, please email
[security@lists.openwallet.foundation](mailto:security@lists.openwallet.foundation)
with a description of the issue, the steps you took to create the issue,
affected versions, and if known, mitigations for the issue. Our vulnerability
management team will acknowledge receiving your email within 2 working days.
This project follows a 90 day disclosure timeline.
```
