---
title: "Bitcoin Core & Dogecoin on Kubernetes"
excerpt: ""
categories:
  - technology
tags:
  - bitcoin
  - dogecoin
  - kubernetes
---

### Brief history of inflation

Inflation is the rise in general price levels over time. Historically:

 * Ancient Times: Rome experienced inflation through coin debasement.
 * 16th Century: The Spanish influx of American silver led to the "Price Revolution."
 * 19th Century: Wars and currency changes caused inflation in Europe.
 * 1920s-1930s: The Great Depression saw deflation, not inflation.
 * 1970s: High inflation and stagflation occurred due to oil shocks.
 * 1980s-1990s: Inflation was controlled through tight monetary policies.
 * 2000s: Inflation was moderate but spiked due to the financial crisis.
 * 2020s: The COVID-19 pandemic and other factors led to rising inflation globally.

Inflation has varied across periods due to economic policies, wars, and major events.

---

### Cons of Proof of Stake (PoS):

 * Wealth Concentration: Richer stakeholders have more influence and rewards, which can centralize power.
 * Initial Distribution: Uneven initial coin distribution can lead to centralization and reduced fairness.
 * Security Risks: Potential for "nothing-at-stake" attacks where validators might vote on multiple chain histories.
 * Lower Decentralization Incentive: High stakes can discourage smaller participants from joining.
 * Long-Term Uncertainty: The long-term effectiveness of PoS for security and decentralization is still being tested.

---


### Cons of Proof of Work (PoW):

 * High Energy Consumption: Requires significant electricity, leading to environmental concerns.
 * Expensive Equipment: Involves costly mining hardware, which can centralize power among wealthier participants.
 * Centralization Risk: Mining power can concentrate in large pools or entities, reducing decentralization.
 * Slow Transactions: Can result in slower transaction processing times.
 * Resource Waste: The energy and effort used in mining don’t directly enhance the network’s functionality.

---

### Bitcoin and Dogecoin

Bitcoin:

 * Fixed Supply: Capped at 21 million coins.
 * Halving: Reward for mining new bitcoins is halved approximately every four years, reducing the rate of new bitcoins created and limiting inflation.

Dogecoin:

* Unlimited Supply: No cap on total number of coins.
* Fixed Issuance: New coins are created at a constant rate (about 5 billion per year), leading to continuous, predictable inflation.

---

### Links

Projects below run up-to-date (as of August 2024) Bitcoin Core and Dogecoin validator nodes as containers.

Images were build via Docker and uploaded to DockerHub, and sample manifest files for Kubernetes have been shared on GitHub as well.


#### Bitcoin Core
- GitHub (Manifest): [jkubo/bitcoin-kubernetes](https://github.com/jkubo/bitcoin-kubernetes)
- GitHub (Image Source): [jkubo/docker-bitcoin-core](https://github.com/jkubo/docker-bitcoin-core)
- DockerHub (Image): [jkubo/bitcoin-core](https://hub.docker.com/r/jkubo/bitcoin-core)

#### Dogecoin
- GitHub (Manifest): [jkubo/dogecoin-kubernetes](https://github.com/jkubo/dogecoin-kubernetes)
- GitHub (Image Source): [jkubo/docker-dogecoin](https://github.com/jkubo/docker-dogecoin)
- DockerHub (Image): [jkubo/dogecoin-core](https://hub.docker.com/r/jkubo/dogecoin-core)