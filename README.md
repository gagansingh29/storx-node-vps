# StorX Storage Node on Ubuntu VPS

## Overview

This repository documents my experience deploying, maintaining, upgrading, and operating a StorX storage node on Ubuntu using Docker.

The node was initially deployed on the StorX Testnet in June 2022 and later migrated to Mainnet as part of the network's roadmap transition.

The goal of this repository is to showcase practical Linux server administration, VPS management, Docker operations, node maintenance, troubleshooting, and long-term infrastructure operations.

---

## Infrastructure

| Component         | Details            |
| ----------------- | ------------------ |
| Provider          | Servarica          |
| VPS Plan          | Big Storage Plan   |
| CPU               | 2 vCPU             |
| RAM               | 2 GB               |
| Storage           | 2 TB               |
| Operating System  | Ubuntu 20.04.6 LTS |
| Container Runtime | Docker             |
| Deployment Type   | Single Container   |
| Region            | Canada             |

---

## Node Statistics

* Initial Deployment: June 2022
* Migration: Testnet → Mainnet
* Current Status: Online
* Current Version: 1.1.0
* Reputation Score: 5000
* Node Uptime Example: 239+ days
* Last Contact: Active

---

## My Responsibilities

### Infrastructure

* Provisioned VPS instance
* Configured Ubuntu server
* Managed SSH access
* Performed system updates
* Maintained server availability

### Docker Operations

* Deployed StorX container
* Managed container lifecycle
* Verified container health
* Reviewed container logs
* Performed node upgrades

### Maintenance

* Executed regular Ubuntu updates
* Applied StorX software upgrades
* Performed Testnet → Mainnet migration
* Monitored node status and reputation
* Investigated synchronization issues

---

## Docker Deployment

Container Image:

```text
storxnetwork/storxnode-2:latest
```

Container Name:

```text
storage_node_container
```

Published Ports:

```text
14002/tcp
28967/tcp
28967/udp
```

---

## Storage Utilization

Filesystem Capacity:

```text
2 TB
```

Current Usage Example:

```text
Used: 15 GB
Available: 1.9 TB
```

---

## Repository Contents

* docs/architecture.md
* docs/deployment.md
* docs/migration-testnet-to-mainnet.md
* docs/troubleshooting.md
* docs/lessons-learned.md
* scripts/useful-commands.sh

---

## Disclaimer

This repository is intended as a technical case study and operational documentation of my StorX node deployment experience.

