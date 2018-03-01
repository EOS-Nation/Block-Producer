# EOS Nation - Block Producer

EOS Nation will be submiting it's candidacy for Block Producer (BP) on EOS's blockchain. This document has been prepared to highlight some of the core values & beliefs behind the EOS Nation organization.

## Core Values

- Open & Transparent
- Contributing back to the EOS Community
- Supporting Open Source Projects

## Hardware

Proposed Hardware specifications for the first two quarters or as long as the EOS software continues to be single threaded. Once the EOS.io software can be hosted on a cluster of Nodes, the EOS Nation BP will upgrade up to 10x EC2 instances as the EOS infrastructure increases in demand.

**Notes:**

- Due to AWS's geographical hardware limitations, 4TB RAM is currently not available in AWS's Canada (Central) region.
- EOS.io has not yet defined the EOS Storage contract, the BP storage requirements may be upgraded if required.

### Singled Threaded (Q1 & Q2)

Only 1 EC2 instance will be running the main BP. In the event of a failure of the main node, the 2nd EC2 node will act as a backup and will become the main node until the main node has been resolved.

- Hosted in Canada
- Ubuntu Server 16.10 
- 2x EC2 (x1.32xlarge)
- 128 Cores / node
- 2TB RAM / node
- 2 x 1920GB (SSD) / node

### Multi-Threaded/Parallelism (Q3 & Q4)

- Hosted in Canada
- Ubuntu Server 16.10 
- 10x EC2 (x1.32xlarge)
- 128 Cores / node
- 2TB RAM / node
- 2 x 1920GB (SSD) / node
