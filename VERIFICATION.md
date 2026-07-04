# CRP BscScan Verification Guide

This document provides a quick verification summary for the CopyrightPass (CRP) core contracts deployed on BNB Smart Chain Mainnet.

The full verification bundle is published through GitHub Releases.

---

## Purpose

This document is used for:

- BscScan verification reference
- Auditor review
- Contract source reproducibility
- Constructor argument checking
- Verification bundle documentation

It does not contain private keys, wallet mnemonics, server passwords, private RPC endpoints, or real API keys.

---

## Network

| Item | Value |
|---|---|
| Chain | BNB Smart Chain Mainnet |
| Chain ID | 56 |
| Compiler | `v0.8.24+commit.e11b9ed9` |
| Optimizer | Enabled, 200 runs |
| EVM Version | `cancun` |
| viaIR | `false` |
| License | MIT |
| Code Format | Solidity Standard JSON Input |

---

## Core Contracts

| Contract | Address | Contract Name |
|---|---|---|
| CopyrightPass (CRP Token) | `0x2059b3cdb31abaeBc9E313246795b754F8A2784c` | `src/CopyrightPass.sol:CopyrightPass` |
| VotingEscrow | `0xf34376DED6806afD98fc5CA164582459D0A62bF3` | `src/VotingEscrow.sol:VotingEscrow` |
| CRPGovernor | `0x7F115028C2E1f70cb4A8E84062e1803e8AfA080b` | `src/CRPGovernor.sol:CRPGovernor` |
| ProtocolTimelock | `0x955262f7ED80708d09643195c2a4Cf45abdee3eC` | `src/ProtocolTimelock.sol:ProtocolTimelock` |
| OperationalTimelock | `0xea9B9a25532481cd89236Ec5612282dA8d6E6305` | `src/OperationalTimelock.sol:OperationalTimelock` |
| CRPEcosystemRegistry | `0x152E93dE6c1e02a726f11C672B641FDf4e3179C8` | `src/CRPEcosystemRegistry.sol:CRPEcosystemRegistry` |

---

## Verification Bundle

Recommended release asset name:

```text
CRP_BscScan_Verification_Bundle_v1.0.0.zip
