# ERP


## Simple is Powerful

EOS has the limitless potential to empower us to tackle some of the most important issues we face as a global society. But before we secure life, liberty, and property, the community must develop the tools to help answer the basic questions. No matter what their goal, every developer will start with a single question when building on the EOS.IO platform, “How many EOS tokens do I need to power my idea?”.

Per our roadmap item, [Community dApp Project](https://steemit.com/eos/@eosnewyork/eos-new-york-initial-roadmap-and-milestones), EOS New York is developing a tool that will answer this question.

## The EOS Resource Planner or ERP

We are developing both a standalone and modular service that will be queryable by anyone in order to understand, at that point in time, the amount of staked tokens needed to secure desired resources. Yes, it will be centrally available at [www.eosrp.io](http://eosrp.io) (under construction) but for convenience only. The code will be open source and can be used anywhere by anyone

At this time, accurate resource estimates will not be available until the network is launched. Per the EOS.IO whitepaper, “Block producers publish their available capacity for bandwidth, computation, and state.” [source](https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md#token-model-and-resource-usage). We anticipate all Block Producers to comply and make accessible their network statistics to help power this tool. 

## Phased Approach

Below is the “features-in-phases” approach for deploying the EOS Resource Planner.

* Phase 1 (Available near launch): Point-in-time estimate of EOS tokens required for X resources <> Point-in-time estimate of resources afforded from Y EOS tokens.
* Phase 2 (Q4 2018): Average look-back window of additional resources afforded based on fractional reserve system.
* Phase 3 (Pending Chintai Development): Average lease price of Y EOS tokens available.
* Phase 4 (Pending EOS Ecosystem): Multi-chain resource estimation.

The tool is of straightforward design and we do not foresee challenges hitting the deployment date close to EOS launch. Phase 2 must occur toward the end of the year so that we can accrue enough data to provide a statistically significant average of fractional reserve resources allocated over different lengths of time.

## Process Flows and Interfaces (illustrative)

Below are a flowchart and sample user interface design which visualizes the intended direction of the EOS Resource Planner:

### Process Flow
*For illustrative purposes only*
![process_flow](process_flow.png "Process flow")

### Sample User Interface
*For illustrative purposes only*
![sample_ui](sample_ui.png "Sample UI")

Once the tool is finished, we hope it's deployed across voting portals, block explorers, and many other community-developed tools. Our goal is that the ERP is flexible enough to plug-in anywhere needed.

Note: The current design and architecture is based on our understanding of resource staking and the underlying software. All that is stated herein is subject to change based on software updates and/or fundamental token resource adjustments. Please feel free to help contribute to this open source project by making a PR on this repo.
