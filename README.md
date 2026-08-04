# Linux Server (linux-server)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Linux Server is a topic catalog covering management, administration, and monitoring interfaces used to operate Linux servers in production. It organizes references to systemd, cockpit, the Linux audit framework, package managers (apt, dnf, rpm), configuration management and provisioning tooling, and remote administration protocols commonly used on Linux servers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/linux-server/refs/heads/main/apis.yml)

## Scope
- **Type:** Topic
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:
 - Infrastructure, Linux, Server, System Administration, DevOps

## Timestamps
- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### systemd
System and service manager for Linux, providing process supervision, socket activation, journaled logging, and a D-Bus management API.

**Human URL:** [https://systemd.io/](https://systemd.io/)

#### Tags:
 - Service Management, Init, D-Bus

#### Properties
- [Documentation](https://www.freedesktop.org/software/systemd/man/)
- [Reference](https://www.freedesktop.org/wiki/Software/systemd/dbus/)
- [Source Code](https://github.com/systemd/systemd)

### Cockpit
Web-based graphical interface for Linux server administration, providing tools for managing services, storage, networking, and accounts.

**Human URL:** [https://cockpit-project.org/](https://cockpit-project.org/)

#### Tags:
 - Administration, Web UI, Remote

#### Properties
- [Documentation](https://cockpit-project.org/documentation.html)
- [Source Code](https://github.com/cockpit-project/cockpit)

### Linux Audit
The Linux audit subsystem and userspace tools for tracking security-relevant events on a Linux server.

**Human URL:** [https://github.com/linux-audit/audit-documentation](https://github.com/linux-audit/audit-documentation)

#### Tags:
 - Security, Auditing, Compliance

#### Properties
- [Documentation](https://github.com/linux-audit/audit-documentation/wiki)
- [Source Code](https://github.com/linux-audit/audit-userspace)

### APT
The Advanced Package Tool used by Debian, Ubuntu, and derivatives for installing, upgrading, and removing software packages.

**Human URL:** [https://wiki.debian.org/Apt](https://wiki.debian.org/Apt)

#### Tags:
 - Package Management, Debian, Ubuntu

#### Properties
- [Documentation](https://manpages.debian.org/bookworm/apt/apt.8.en.html)

### DNF
The Dandified YUM package manager used on Fedora, RHEL, CentOS Stream, and related distributions.

**Human URL:** [https://dnf.readthedocs.io/](https://dnf.readthedocs.io/)

#### Tags:
 - Package Management, Fedora, RHEL

#### Properties
- [Documentation](https://dnf.readthedocs.io/en/latest/)
- [Source Code](https://github.com/rpm-software-management/dnf)

### OpenSSH
The de facto standard suite for secure remote login, command execution, and file transfer on Linux servers.

**Human URL:** [https://www.openssh.com/](https://www.openssh.com/)

#### Tags:
 - Remote Access, Security, SSH

#### Properties
- [Documentation](https://www.openssh.com/manual.html)
- [Source Code](https://github.com/openssh/openssh-portable)

### systemd-journald
The systemd journal daemon, providing structured, indexed logs for the Linux server with a query API via journalctl and libsystemd.

**Human URL:** [https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html](https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html)

#### Tags:
 - Logging, Observability

#### Properties
- [Documentation](https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html)

## Common Properties
- [Linux Foundation](https://www.linuxfoundation.org/)
- [Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)
- [Linux man-pages](https://man7.org/linux/man-pages/)

## Maintainers
**FN:** Kin Lane
**Email:** kin@apievangelist.com
