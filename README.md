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

| Repo | Description |
|------|------------|
| [core-v3](https://github.com/Gearbox-protocol/core-v3) | Core contracts of Gearbox Protocol V3 — credit accounts, leverage mechanics, and execution logic |
| [oracles-v3](https://github.com/Gearbox-protocol/oracles-v3) | Oracle and pricing infrastructure for collateral valuation and risk management |
| [permissionless](https://github.com/Gearbox-protocol/permissionless) | Permissionless market engine with governance and bytecode verification (BCR) |
| [integrations-v3](https://github.com/Gearbox-protocol/integrations-v3) | Adapters enabling interaction with external DeFi protocols |
| [peripheral-v3](https://github.com/Gearbox-protocol/peripheral-v3) | Auxiliary contracts supporting integrations and protocol operations |
| [router-v3](https://github.com/Gearbox-protocol/router-v3) | Routing layer for composing and executing multi-step strategies |
| [bots-v3](https://github.com/Gearbox-protocol/bots-v3) | Infrastructure and interfaces for building automation and bot integrations |

## Backend Services

| Repo | Description |
|------|------------|
| [liquidator-v2](https://github.com/Gearbox-protocol/liquidator-v2) | Open-source liquidation bot for Gearbox Protocol — anyone can run it to perform liquidations |
| [safe-watcher](https://github.com/Gearbox-protocol/safe-watcher) | Open-source utility for monitoring Safe transactions and detecting suspicious activity |
| [apy-server](https://github.com/Gearbox-protocol/apy-server) | Production service for calculating APY, including rewards and incentive programs |
| [charts_server](https://github.com/Gearbox-protocol/charts_server) | Legacy charts backend supporting historical data visualization |
| [gearbox-backend](https://github.com/Gearbox-protocol/gearbox-backend) | Core backend service indexing protocol state and historical data for APIs and analytics |
| [strategies-apy-lambda](https://github.com/Gearbox-protocol/strategies-apy-lambda) | Serverless component for computing strategy-level APY and performance metrics |
| [dns-checker](https://github.com/Gearbox-protocol/dns-checker) | Monitoring bot that tracks DNS changes and triggers alerts on unexpected updates |
| [microservices](https://github.com/Gearbox-protocol/microservices) | Internal services for monitoring accounts, protocol state, and security-related events |
| [optimist](https://github.com/Gearbox-protocol/optimist) | Service for optimistic liquidation checks, detecting accounts that may become liquidatable |
| [anvil-manager](https://github.com/Gearbox-protocol/anvil-manager) | Tooling for managing local test environments and pre-deployment testing workflows |
---

## Frontend

| Domain | Service | Repo | Description |
|--------|--------|------|------------|
| https://gearbox.finance | Landing | [landing-v3](https://github.com/Gearbox-protocol/landing-v3) | Marketing website and primary entry point |
| https://app.gearbox.finance | Main App | [client-v3](https://github.com/Gearbox-protocol/client-v3) | Main user interface for interacting with the protocol |
| https://x.gearbox.finance | Intent-based Lending Interface | [gearbox-x-interface](https://github.com/Gearbox-protocol/gearbox-x-interface) | Frontend prototype for intent-based lending |
| https://safe.gearbox.finance | Safe Interface | [permissionless-safe](https://github.com/Gearbox-protocol/permissionless-safe) | Safe integration for governance and operations |
| https://permissionless.gearbox.finance | Interface Layer | [permissionless-interface](https://github.com/Gearbox-protocol/permissionless-interface) | Interface layer connecting UI with backend services |
| https://bcr.gearbox.finance | Verification Interface | [bcr-interface](https://github.com/Gearbox-protocol/bcr-interface) | Bytecode verification (BCR) interface |
| https://data.gearbox.finance | Analytics | [analytics](https://github.com/Gearbox-protocol/analytics) | Data processing and insights |
| https://gov.gearbox.finance | Governance | [gov](https://github.com/Gearbox-protocol/gov) | Governance interface and proposal system |
---

## Data

| Repo | Description | 
|------|------------|
| [gearbox-revenue-graph](https://github.com/Gearbox-protocol/gearbox-revenue-graph) | Revenue analytics | 
| [gearbox-revenue-swap](https://github.com/Gearbox-protocol/gearbox-revenue-swap) | Revenue flows |
| [defillama](https://github.com/Gearbox-protocol/defillama) | TVL / metrics adapter | 
| [defillama-server](https://github.com/Gearbox-protocol/defillama-server) | Data ingestion |

---

## Docs 

| Repo | Description |  
|------|------------|
| [docs-knowledge](https://github.com/Gearbox-protocol/docs-knowledge) | Internal docs | 
| [style-guide](https://github.com/Gearbox-protocol/style-guide) | Coding standards | 

---

## Libraries

Libraries provide shared components, SDKs, and assets used across the Gearbox ecosystem.

| Repo | Description |
|------|------------|
| [sdk](https://github.com/Gearbox-protocol/sdk) | TypeScript SDK for interacting with Gearbox Protocol — typed wrappers around contracts and the main entry point for integrations |
| [ui-kit](https://github.com/Gearbox-protocol/ui-kit) | Shared UI component library used across all Gearbox interfaces |
| [static](https://github.com/Gearbox-protocol/static) | Static asset storage (token icons, metadata, and shared resources) served across services and interfaces |

## DevOps

| Repo | Description | 
|------|------------|
| [deploy-tools](https://github.com/Gearbox-protocol/deploy-tools) | Deployment scripts | 
| [aws](https://github.com/Gearbox-protocol/aws) | Infra configs | 
| [keystore](https://github.com/Gearbox-protocol/keystore) | Key management |
| [latitude](https://github.com/Gearbox-protocol/latitude) | Unknown | 

---

## Branding

| Repo | Description |
|------|------------|
| [brand-assets](https://github.com/Gearbox-protocol/brand-assets) | Logos and assets |

