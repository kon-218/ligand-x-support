# Ligand-X Support

Official public issue tracker and community support hub for **Ligand-X**, the local computational
chemistry and drug-discovery platform from Ligand-X Inc.

[![Website](https://img.shields.io/badge/website-ligand--x.com-1d4ed8)](https://ligand-x.com)
[![Report an issue](https://img.shields.io/badge/support-report_an_issue-0f766e)](https://github.com/kon-218/ligand-x-support/issues/new/choose)

## How can we help?

| I want to… | Use… |
|---|---|
| Report a launcher problem | [Launcher problem](https://github.com/kon-218/ligand-x-support/issues/new?template=01-launcher.yml) |
| Report a Core/Free platform problem | [Core platform problem](https://github.com/kon-218/ligand-x-support/issues/new?template=02-core.yml) |
| Report a Pro module problem | [Pro module problem](https://github.com/kon-218/ligand-x-support/issues/new?template=03-pro.yml) |
| Get help installing or updating | [Installation or update problem](https://github.com/kon-218/ligand-x-support/issues/new?template=04-installation.yml) |
| Raise a scientific correctness or reproducibility concern | [Scientific result concern](https://github.com/kon-218/ligand-x-support/issues/new?template=05-scientific.yml) |
| Suggest a capability or improvement | [Feature request](https://github.com/kon-218/ligand-x-support/issues/new?template=06-feature.yml) |
| Correct product documentation or the website | [Documentation issue](https://github.com/kon-218/ligand-x-support/issues/new?template=07-documentation.yml) |
| Ask a usage question | [GitHub Discussions](https://github.com/kon-218/ligand-x-support/discussions) |
| Discuss an account, licence key, billing, or confidential matter | Email [support@ligand-x.com](mailto:support@ligand-x.com) |
| Report a security vulnerability | Use [private vulnerability reporting](https://github.com/kon-218/ligand-x-support/security/advisories/new) and follow [SECURITY.md](SECURITY.md) |

If you are unsure, use the [general product issue](https://github.com/kon-218/ligand-x-support/issues/new?template=08-other.yml).

## What this repository covers

This tracker covers the complete Ligand-X product: the desktop launcher, installation and updates,
the web interface and gateway, Free services, Pro modules, documentation, and scientific behavior.
Core and Pro implementation repositories are private and distribute versioned runtime images; users
do not need access to those repositories to report, follow, or verify a fix. The public issue remains
the customer-visible record through triage, implementation, and release.

## Before submitting

1. Search [open and closed issues](https://github.com/kon-218/ligand-x-support/issues) for an existing report.
2. Record the Ligand-X and launcher versions shown in the application.
3. Reduce the problem to the smallest safe reproduction you can provide.
4. Remove secrets and confidential data from logs and screenshots.

**Never post licence keys, API tokens, passwords, private registry credentials, proprietary molecular
structures, unpublished datasets, patient information, or other regulated/confidential data.** If a
reproduction requires sensitive material, open a sanitized issue first or contact
[support@ligand-x.com](mailto:support@ligand-x.com).

## What happens after submission

Maintainers classify each report and use public status labels to communicate its state. Confirmed work
may be assigned to a release milestone. When a fix ships, the issue is updated with the first released
version containing it. See [TRIAGE.md](TRIAGE.md) for the workflow and label meanings.

Ligand-X is a scientific computing product. Reports about scientific results are investigated as
reproducibility and correctness concerns, but issue discussion is not scientific, medical, regulatory,
or professional advice.

## Company

Ligand-X is developed by **Ligand-X Inc.** Product information and documentation are available at
[ligand-x.com](https://ligand-x.com). Use of this repository is governed by the
[Code of Conduct](CODE_OF_CONDUCT.md) and [privacy guidance](PRIVACY.md).
