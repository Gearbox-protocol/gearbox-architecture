# Gearbox Architecture

This repository documents the system architecture of Gearbox Protocol.

It provides a structured overview of:
- smart contracts
- services
- interfaces
- frontend
- data systems

The goal is to maintain a clear, evolving map of the system.

---

## Smart Contracts

| Repo | Description | Used in |
|------|------------|--------|
| [core-v3](https://github.com/Gearbox-protocol/core-v3) | Core protocol contracts: credit accounts, leverage, execution | Entire protocol |
| [oracles-v3](https://github.com/Gearbox-protocol/oracles-v3) | Pricing and oracle infrastructure | Risk, liquidations |
| [permissionless](https://github.com/Gearbox-protocol/permissionless) | Market deployment, governance, BCR verification | Market creation |
| [integrations-v3](https://github.com/Gearbox-protocol/integrations-v3) | Adapters to external DeFi protocols | Strategy execution |
| [peripheral-v3](https://github.com/Gearbox-protocol/peripheral-v3) | Helper contracts and utilities | Integrations |
| [router-v3](https://github.com/Gearbox-protocol/router-v3) | Routing layer for complex execution | Execution layer |
| [bots-v3](https://github.com/Gearbox-protocol/bots-v3) | Bot interaction layer (contracts/tools) | Automation |

---

## Backend Services

| Repo | Description | Used in |
|------|------------|--------|
| [liquidator-v2](https://github.com/Gearbox-protocol/liquidator-v2) | Liquidation service | Risk management |
| [safe-watcher](https://github.com/Gearbox-protocol/safe-watcher) | Monitoring accounts and safety | Alerts, protection |
| [apy-server](https://github.com/Gearbox-protocol/apy-server) | Yield calculation | Frontend |
| [charts_server](https://github.com/Gearbox-protocol/charts_server) | Charts backend | UI |
| [gearbox-backend](https://github.com/Gearbox-protocol/gearbox-backend) | Main API layer | Frontend |
| [strategies-apy-lambda](https://github.com/Gearbox-protocol/strategies-apy-lambda) | Strategy analytics | Analytics |
| [dns-checker](https://github.com/Gearbox-protocol/dns-checker) | Infra monitoring | DevOps |
| [microservices](https://github.com/Gearbox-protocol/microservices) | Legacy services | ⚠️ Review needed |
| [optimist](https://github.com/Gearbox-protocol/optimist) | Unknown service | ⚠️ Review needed |
| [anvil-manager](https://github.com/Gearbox-protocol/anvil-manager) | Local dev chain | Dev/testing |

---

## Frontend

| Repo | Description | Used in |
|------|------------|--------|
| [client-v3](https://github.com/Gearbox-protocol/client-v3) | Main user interface | Users |
| [landing-v3](https://github.com/Gearbox-protocol/landing-v3) | Marketing site | Onboarding |
| [gearbox-x-interface](https://github.com/Gearbox-protocol/gearbox-x-interface) | Experimental UI | New UX |
| [permissionless-ui](https://github.com/Gearbox-protocol/permissionless-ui) | Market UI | Governance |
| [permissionless-safe](https://github.com/Gearbox-protocol/permissionless-safe) | Safe integration | Governance |
| [permissionless-interface](https://github.com/Gearbox-protocol/permissionless-interface) | Interface layer | Backend/UI |
| [bcr-interface](https://github.com/Gearbox-protocol/bcr-interface) | Bytecode verification | Deployment |
| [analytics](https://github.com/Gearbox-protocol/analytics) | Data processing | Insights |
| [gov](https://github.com/Gearbox-protocol/gov) | Governance | ⚠️ review |
---

## Data

| Repo | Description | Used in |
|------|------------|--------|
| [gearbox-revenue-graph](https://github.com/Gearbox-protocol/gearbox-revenue-graph) | Revenue analytics | Reporting |
| [gearbox-revenue-swap](https://github.com/Gearbox-protocol/gearbox-revenue-swap) | Revenue flows | Treasury |
| [defillama](https://github.com/Gearbox-protocol/defillama) | TVL / metrics adapter | Public metrics |
| [defillama-server](https://github.com/Gearbox-protocol/defillama-server) | Data ingestion | Reporting |

---


---

## 📚 Docs / Knowledge

| Repo | Description | Used in |
|------|------------|--------|
| [docs-knowledge](https://github.com/Gearbox-protocol/docs-knowledge) | Internal docs | Team |
| [dev-docs](https://github.com/Gearbox-protocol/dev-docs) | Dev documentation | External |
| [style-guide](https://github.com/Gearbox-protocol/style-guide) | Coding standards | Dev |

---

## Libraries

| Repo | Description | Status |
|------|------------|--------|
| [static](https://github.com/Gearbox-protocol/static) | Static assets | ⚠️ unclear |
| [sdk](https://github.com/Gearbox-protocol/sdk) | SDK | ⚠️ review |


## DevOps

| Repo | Description | Used in |
|------|------------|--------|
| [deploy-tools](https://github.com/Gearbox-protocol/deploy-tools) | Deployment scripts | DevOps |
| [aws](https://github.com/Gearbox-protocol/aws) | Infra configs | Backend |
| [keystore](https://github.com/Gearbox-protocol/keystore) | Key management | Security |
| [latitude](https://github.com/Gearbox-protocol/latitude) | Unknown | ❗ investigate |

---

## Branding

| Repo | Description |
|------|------------|
| [brand-assets](https://github.com/Gearbox-protocol/brand-assets) | Logos and assets |

