# Welcome to FINOS OSERA, The Open Source Enterprise Resiliency Alliance

**Open Source Enterprise Resiliency Alliance** — a [FINOS](https://www.finos.org/) initiative that helps regulated institutions close open source patch-coverage gaps and operationalize remediation at scale.

This repository is the **developer landing page** for the alliance. The public site is [osera.finos.org](https://osera.finos.org).

## Quick Links

| What                       | Where to go                                                    |
| -------------------------- | -------------------------------------------------------------- |
| Public                     | [osera.finos.org](https://osera.finos.org)                     |
| Remediation standards      | [standards.osera.finos.org](https://standards.osera.finos.org) |
| Risk prioritization        | [risknav.osera.finos.org](https://risknav.osera.finos.org)     |
| OSERA Components           | [github.com/finos-osera](https://github.com/finos-osera)       |
| OSERA Maintained Project   | [github.com/finos-osera-forks](https://github.com/finos-osera-forks)|

## How OSERA is structured

Work lives in the `[finos-osera](https://github.com/finos-osera)` GitHub organization. It groups into software projects, a standards project, backpatch source lines, and task forces.

```text
OSERA (FINOS)
├── Public sites
│   ├── osera.finos.org                 this repo (website/)
│   ├── standards.osera.finos.org       remediation-standards
│   └── risknav.osera.finos.org         risk-navigator
├── Software projects
│   └── risk-navigator                  remediation prioritization tool
├── Standards
│   └── remediation-standards           open patching / attestation standards
├── Maintained Projects
│   └── github.com/finos-osera-forks    public source for maintained lines
└── Private Operational Repositories
    └── operations-taskforce            operational coordination
    └── osera-platform                  where the OSERA platform is built
```



### Software projects


| Project            | What it is                                                                                                                          | Links                                                                                                              |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **Risk Navigator** | Decision-enablement tool for ranking vulnerable libraries, seeing estate exposure, and identifying upgrade or backpatch candidates. | [repo](https://github.com/finos-osera/risk-navigator) · [risknav.osera.finos.org](https://risknav.osera.finos.org) |




### Standards

| Project                              | What it is                                                                                                                                                                                                      | Links                                                                                                                             |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Remediation / patching standards** | Financial Services grade standards for patch remediation and attesttation. for producing, publishing, and consuming (fork management, provenance, release evidence, VEX/SBOM feeds, recipient test guidance).  | [repo](https://github.com/finos-osera/remediation-standards) · **[standards.osera.finos.org](https://standards.osera.finos.org)** |


### Hardened Open Source Projects library

Public repositories in [finos-osera-forks](https://github.com/orgs/finos-osera-forks) hold the maintained source for lines the sector still runs, often past upstream end of life. Naming, branches, release metadata and attestations follow standards defined by our Members at [standards.osera.finos.org](standards.osera.finos.org).

Source is public by default. Built, participant-ready artifacts are delivered through formation participation. Browse the org, or start from the lines already piloted on [osera.finos.org](https://osera.finos.org).

### Task forces


| Task force                | What it is                                                                                                       | Links                                                                                                                                     |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Operations Task Force** | Working repository for operational coordination of the alliance (process, intake, and cross-project operations). | [repo](https://github.com/finos-osera/operations-taskforce) · [issue tracker](https://github.com/finos-osera/operations-taskforce/issues) |


## Get involved

- Join OSERA: [osera.finos.org/#involved](https://osera.finos.org/#involved)
- Guiding principles: [osera.finos.org/guiding-principles](https://osera.finos.org/guiding-principles)
- Contribute via GitHub issues and pull requests in the relevant project (see [CONTRIBUTING.md](CONTRIBUTING.md))
- Membership: [membership@finos.org](mailto:membership@finos.org)
