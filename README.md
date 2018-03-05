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

### BP "appointed"

If EOS Nation is "appointed" as Block Producer, only 1 Elastic Compute Cloud (EC2) instance will be running the main BP for the duration of the first election.

- **Nodes** 1x EC2 (x1.32xlarge)
- **vCPUs** 128 Cores
- **Memory** 2TB RAM
- **Storage (ipfs)** 2 x 1920GB (SSD)
- **Network** 25 Gigabit

### BP "elected"

If EOS Nation is "elected" as Block Producer, two Elastic Compute Cloud (EC2) instances will be running as full EOS nodes.  In the event of a failure of the main BP node, the secondary BP node will act as a backup and will become the main node. Minimal downtime shall be the main prorioty in case of a full node failure.

- **Nodes** 2x EC2 (x1.32xlarge)
- **vCPUs** 128 Cores
- **Memory** 2TB RAM
- **Storage (ipfs)** 2 x 1920GB (SSD)
- **Network** 25 Gigabit

### Scaling Plan

EOS Nation represents a global represenation of Canada, each major Canadian city will be expected to host an EOS full node which will be under the support of EOS Nation. Proper training of setting up & maintaining an EOS full node will be provided by EOS Nation. Once a city has proven they have the technical knowledge and bare metal hardware to provide support as a full node, their node will be added to the EOS Nation cluster BP and they will start to collect EOS Rewards.

### Geographical Expansion

**Planned** will require to be fully operational before June 3, 2018.

- Ottawa, ON - [EOS Nation](https://www.meetup.com/EOS-Nation)
- Toronto, ON - [EOS Toronto](https://www.meetup.com/EOS-Toronto)

**Proposed** are **not** required to be operational before June 3, 2018.

- Montreal, QC
- Vancouver, BC
- Calgary, AB
