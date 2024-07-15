# Studio Mirai: Security Audit Report

## Overview

Studio Mirai is a lifestyle brand focused on innovative NFT collections and interactive experiences. Originally launched on the ICON blockchain in October 2021, it has since transitioned to the Sui blockchain to leverage its advanced features.

**Key Highlights**:
- **Dynamic NFT Collections**: Including Prime Machin and Enforcer Machin, which feature dynamic properties allowing NFTs to evolve from black and white to color, and offer object composability and real-time 3D rendering.
- **Coda Music Platform**: Aims to disrupt the music industry by allowing artists to directly sell albums and tickets, bypassing traditional barriers and empowering artists with more control and quicker payments.
- **Community and Engagement**: Studio Mirai emphasizes community involvement with daily events, a vibrant storyline, and a variety of projects that build confidence and engagement among participants.
- **Technological Integration**: Studio Mirai utilizes the full spectrum of Sui's capabilities, such as fast path transactions, shared objects, and on-chain storage solutions to enhance their NFTs' functionality and interactivity within the blockchain space.
- **Future Prospects**: Studio Mirai continues to expand its influence within the Sui ecosystem, partnering with various tech and creative entities to push the boundaries of what can be achieved with NFT technology on modern blockchains.

For more detailed information, explore [here](https://twitter.com/_StudioMirai).

## Audit Summary

This report outlines the findings from a comprehensive security audit conducted for **Studio Mirai**. The audit targeted the project's smart contract suite with the objective of identifying and mitigating potential vulnerabilities, thereby strengthening the security and robustness of the project's blockchain infrastructure.

## Findings Summary

The audit revealed findings categorized under high and informational severity levels. Recommendations for remediation are provided to address these vulnerabilities effectively.

### Vulnerabilities Overview

| ID       | Title                              | Impact                                                                                                       | Severity | Status    |
|----------|------------------------------------|--------------------------------------------------------------------------------------------------------------|----------|-----------|
| VUL-001  | Data Integrity and System Reliability Issue | **High Impact**: Mismatched IDs could result in the wrong image being deleted, leading to loss of important data and affecting the consistency of the system's state. | High     | Resolved  |
| VUL-002  | Administrative Function Concerns          | **Informational Impact**: Centralization of power in administrative functions poses security risks if administrative access is compromised. | Informational | Unresolved  |

### Finding Count by Severity

- **High Severity**: 1
- **Informational Severity**: 1
