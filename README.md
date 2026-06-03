# Blockchain AML/CFT Monitoring & Rules Engine

An enterprise-grade, decentralized real-time financial surveillance system designed to detect and intercept cross-border financial crime. This framework replaces legacy retrospective batch auditing with preventative, on-chain smart contract validation hooks, backed by Graph Neural Network (GNN) analytics.

---

## Key Framework Pillars

* **In-Flight Validation Engine:** Evaluates transactional parameters natively before block settlement occurs.
* **Unified Ledger Topology:** Replaces disconnected bank data silos with a shared, permissioned consensus state.
* **Deep Network Tracking:** Maps complex multi-hop layering schemes using graph clustering algorithms.

---

## System Architecture & Workflow

The system is split into three foundational layers, mapped directly by the included system design schematics:

### 1. Network Node Topology (`AML-BLOCKCHAIN-ARCHITECTURE.png`)
* Integrates an **Oracle Bridge Router** to safely ingest transactions from traditional legacy Core Banking Systems (CBS).
* Distributes transaction verification across a network of trusted **Validator Bank Nodes** and regulatory monitoring nodes.

### 2. Synchronous Settlement Pipeline (`AML-BLOCKCHAIN-WORKFLOW.png`)
* Intercepts transaction flight requests post-initiation.
* Routes payloads through smart contract constraints where rules are evaluated via Byzantine Fault Tolerant (**IBFT 2.0**) consensus before committing state immutably.

### 3. Behavioral Fraud Network (`GNN-FRAUD-NETWORK.png`)
* Implements **Graph Neural Networks (GNN)** to identify suspicious structural transaction clustering.
* Exposes advanced multi-hop placement and layering loops spanning across 10+ proxy account hops.

---

## Interactive Presentation & Prototype

The repository contains an all-in-one interactive web-based interface: `AML_Interactive_Briefing.html`. 

### Features Built into the Interface:
* **Live Rules Simulator:** Dynamic sliders to real-time test compliance criteria adjustments (Transaction Amount thresholds, Transfer Velocity, Account Incubation Age, and Sanction Match queries).
* **On-Chain Log Stream:** A virtual terminal simulation displaying block rejection alerts and cryptographic state logs based on running parameter risks.
* **Embedded Graphics:** Automatically pairs the code playground with the structural architecture layouts.

### How to Run Locally:
1. Download the `AML_Interactive_Briefing.html` file from this repository.
2. Ensure your three diagram files (`AML-BLOCKCHAIN-ARCHITECTURE.png`, `AML-BLOCKCHAIN-WORKFLOW.png`, and `GNN-FRAUD-NETWORK.png`) are located inside the **same directory folder**.
3. Double-click the `.html` file to open it in any standard web browser (Chrome, Safari, Edge) to run the full presentation completely offline.

---

## Technical Rules Engine Specifications

The core simulation evaluates state entries across a multi-tiered risk weight hierarchy:
* **Threshold Guard:** flag matches for transaction amounts $\ge$ ₹10,00,000 (+30% Risk Index weight).
* **Velocity Sentinel:** triggers on automated transfer frequencies exceeding 3 transactions/hr (+25% Risk Index weight).
* **Incubation Check:** tracks high-volume transfers routed through accounts active for less than 30 days (+20% Risk Index weight).
* **Sanction Intercept:** immediate 100% risk index ceiling override and execution block on any wallet blacklist matches.
