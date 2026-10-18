# Saeid Monfared

**Solutions Architect for Mission-Critical Broadcast & IT Infrastructure** · Istanbul

I design systems where servers, shared storage, networks, broadcast equipment and software have to work together with no single point of failure. For 20+ years I took them from tender to handover and into operation for a national broadcaster.

- Won roughly **70%** of the tenders I designed solutions for
- Six new IT-based TV channels (about **US$1M** tender): kept all six on air 24/7 for **three years** after handover with no off-air incidents caused by system failure
- Converted **26** provincial radio stations from analog reels to an IT-based system, the first project of its kind in the country
- Founded a broadcast software department; our playout system sold **200+** licenses in two to three years

## Engineering lab

The same fault-tolerant thinking, applied to software I build and run myself.

| Project | What it shows | Live |
|---|---|---|
| [Server Monitor (SRM)](https://github.com/codemonix/server-monitor) | Cross-platform agent (Linux .deb, Windows .exe) streaming CPU, memory, disk and network metrics. WebSockets with automatic HTTP fallback and offline disk queueing during outages; JWT with refresh-token rotation and RBAC; CI/CD for versioned builds; Docker on AWS. | [srm.saeidmon.com](https://srm.saeidmon.com) |
| [Inventory Management System (IMS)](https://github.com/codemonix/inventory-management-system) | Multi-location stock with a two-phase transfer engine; JWT/RBAC; Node.js/Express + MongoDB; Docker on AWS Lightsail behind Nginx with zero-downtime updates; transactional backup and restore, tested end to end. | [ims.saeidmon.com](https://ims.saeidmon.com) |

## Toolbox

**Architecture:** high availability, automatic failover, disaster recovery, SAN/NAS shared storage, network and NOC design, broadcast playout and automation, SDI routing, IPTV, SMPTE ST 2110 concepts
**Software and DevOps:** Node.js, TypeScript, React, MongoDB, WebSockets, Docker, Nginx, AWS, GitHub Actions, Linux, Bash, Python

## Contact

[saeidmon.com](https://www.saeidmon.com) · [LinkedIn](https://www.linkedin.com/in/saeid-monfared/)
