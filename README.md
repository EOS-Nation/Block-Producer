# EOS Nation - Block Producer

## Official block producer candidate name.

EOS Nation

## Location of company headquarters.

Canada

## Expected location of servers.

Hybrid approach - Cloud (AWS) for main full node & backup/secondary full nodes located in different geographical regions using bare metal.

- **Cloud** For the cloud infrastructure we will be hosted our virtual instances with [AWS Canada](https://aws.amazon.com/canada/aws-in-canada/) in the `Canada (Central)` region.
- **Bare Metal** The first two cities chosen by EOS Nation will be involved in the initial EOS testnet, the following expantion cities will soon follow after the EOS launch date.
  - Toronto, ON (testnet)
  - Ottawa, ON (testnet)
  - Montreal, QC (proposed)
  - Calgary, AB (proposed)
  - Vancouver, BC (proposed)

## Technical Specifications
### Hardware

Proposed technical specifications and total expenditure of resources for BP.

**Notes:**

- Due to AWS's geographical hardware limitations, 4TB RAM is currently not available in AWS's `Canada (Central)` region.
- EOS.io has not yet defined the EOS Storage contract, the BP storage requirements may be upgraded and are subject to change if deemed valuable to the community.

### Common Hardware Specifications

- **Geographical Region** Toronto, Canada
- **Polical Region** Canada
- **Operating System** Ubuntu Server 16.10

### Singled Threaded (Election)

If nominated to run the EOS election, only 1 Elastic Compute Cloud (EC2) instance will be running the main BP.

- **Nodes** 1x EC2 (x1.32xlarge)
- **vCPUs** 128 Cores
- **Memory** 2TB RAM
- **Storage (ipfs)** 2 x 1920GB (SSD)
- **Network** 25 Gigabit

### Singled Threaded (Q1 & Q2)

Only 1 Elastic Compute Cloud (EC2) instance will be running the main BP. In the event of a failure of the main node, the 2nd EC2 node will act as a backup and will become the main node until the main node has been resolved.

- **Nodes** 2x EC2 (x1.32xlarge)
- **vCPUs** 128 Cores
- **Memory** 2TB RAM
- **Storage (ipfs)** 2 x 1920GB (SSD)
- **Network** 25 Gigabit

### Multi-Threaded/Parallelism (Q3 & Q4)

Once the EOS.io software can be hosted on a cluster of Nodes, the EOS Nation BP will upgrade the number of EC2 instances as the EOS infrastructure increases in demand.

- **Nodes** 12x EC2 (x1.32xlarge)
- **vCPUs** 128 Cores (1536 cores max)
- **Memory** 2TB RAM (24TB RAM max)
- **Storage (ipfs)** 2 x 1920GB (SSD) (48TB SSD max)
- **Network** 25 Gigabit
