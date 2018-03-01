# EOS Nation - Block Producer

EOS Nation will be submiting it's candidacy for Block Producer (BP) on EOS's blockchain. This document has been prepared to highlight some of the core values & beliefs behind the EOS Nation organization.

## Core Values

- Open & Transparent
- Contributing back to the EOS Community
- Supporting [Open Source Projects](https://github.com/EOS-Nation/eosnation-open-source)

## Hardware

Proposed Hardware specifications for the first (x4) quarters based on the EOS.io software.

**Notes:**

- Due to AWS's geographical hardware limitations, 4TB RAM is currently not available in AWS's `Canada (Central)` region.
- EOS.io has not yet defined the EOS Storage contract, the BP storage requirements may be upgraded if required.

### Common Hardware Specifications

- **Geographical Region**: Toronto, Canada
- **Polical Region:** Canada
- **Operating System:** Ubuntu Server 16.10
- **vCPUs:** 128 Cores
- **Memory:** 2TB RAM
- **Storage:** 2 x 1920GB (SSD)
- **Network:** 25 Gigabit

### Singled Threaded (Q1 & Q2)

Only 1 EC2 instance will be running the main BP. In the event of a failure of the main node, the 2nd EC2 node will act as a backup and will become the main node until the main node has been resolved.

- **Nodes:** 2x EC2 (x1.32xlarge)
- **vCPUs:** 128 Cores (max)
- **Memory:** 2TB RAM (max)
- **Storage:** 4TB (SSD)

### Multi-Threaded/Parallelism (Q3 & Q4)

Once the EOS.io software can be hosted on a cluster of Nodes, the EOS Nation BP will upgrade the number of EC2 instances as the EOS infrastructure increases in demand.

- **Nodes:** 12x EC2 (x1.32xlarge)
- **vCPUs:** 1536 Cores (max)
- **Memory:** 24TB RAM (max)
- **Storage:** 48TB (SSD)
