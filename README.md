# USDT0 Audit Reports

Deployment → report mapping for USDT0, XAUt0 and USAT (generated 2026-10-05).

Contract names link to the deployed contract on the chain's explorer (the proxy where there is one). **Version** is the last change to the deployed contract's source (commit and date); **Audited by** lists the code audits covering that version. **Deployed** is the commit that recorded the deployment, or the creation transaction where no commit exists; **Deployment verified by** lists the reports that verified it on-chain, including reviews of an OFT's LayerZero wiring. Report IDs link to the report PDFs.

For all contract addresses, see the [USDT0 documentation](https://docs.usdt0.to/technical-documentation/deployments).

## USDT0

#### Ethereum

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OAdapterUpgradeable](https://etherscan.io/address/0x6C96dE32CEa08842dcc4058c14d3aaAD7Fa41dee) | `18c2b4d` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `7841d17` 2025-01-08 | [CS-04](ChainSecurity/ChainSecurity_USDT0_Flare_audit.pdf), [CS-05](ChainSecurity/ChainSecurity_USDT0_Ink_audit.pdf), [GA-47](Guardian/USDT0-Stellar-Deployment-Guardian-Report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf) |

#### Ethereum — IOTA adapter

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OAdapterUpgradeable](https://etherscan.io/address/0xAEf027F94008430BF4Fc27FFABB49ea6F1dd3414) | `18c2b4d` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `c2f618b` 2026-08-26 |  |

#### Arbitrum One

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://arbiscan.io/address/0x14E4A1B13bf7F943c8ff7C51fb60FA964A298D92) | `7dd2007` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `5627746` 2025-01-16 | [CS-04](ChainSecurity/ChainSecurity_USDT0_Flare_audit.pdf), [CS-05](ChainSecurity/ChainSecurity_USDT0_Ink_audit.pdf), [GA-47](Guardian/USDT0-Stellar-Deployment-Guardian-Report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf) |
| Token | [ArbitrumExtensionV2](https://arbiscan.io/address/0xFd086bC7CD5C481DCC9C85ebE478A1C0b69FCbb9) | `01cdf1d` 2025-01-20 | [CS-02](ChainSecurity/ChainSecurity_USDT0_Arbitrum_v2_audit.pdf), [OZ-01](Openzeppelin/USDT0_Audit.pdf), [GA-02](Guardian/USDT0_Arbitrum_Upgrade.pdf) | impl `8c281dc` 2025-01-27<br>proxy `d63d342` 2025-01-14 |  |

#### OP Mainnet

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://optimistic.etherscan.io/address/0xF03b4d9AC1D5d1E7c4cEf54C2A313b9fe051A0aD) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `483775c` 2025-03-14 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://optimistic.etherscan.io/address/0x01bFF41798a0BcF287b996046Ca68b395DbC1071) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `75e33fd` 2025-03-14 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Unichain

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://uniscan.xyz/address/0xc07bE8994D035631c36fb4a89C918CeFB2f03EC3) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `2b70253` 2025-03-14 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://uniscan.xyz/address/0x9151434b16b9763660705744891fA906F660EcC5) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `d916ffb` 2025-03-14 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Ink

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://explorer.inkonchain.com/address/0x1cB6De532588fCA4a21B7209DE7C456AF8434A65) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `38a358a` 2025-03-14 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [CS-04](ChainSecurity/ChainSecurity_USDT0_Flare_audit.pdf), [CS-05](ChainSecurity/ChainSecurity_USDT0_Ink_audit.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://explorer.inkonchain.com/address/0x0200C29006150606B650577BBE7B6248F58470c1) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | impl `f9b9aa7` 2025-03-14<br>proxy `1484c92` 2025-01-05 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Berachain

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://berascan.com/address/0x3Dc96399109df5ceb2C226664A086140bD0379cB) | `7dd2007` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `1cf28c1` 2025-01-26 | [CS-04](ChainSecurity/ChainSecurity_USDT0_Flare_audit.pdf), [CS-05](ChainSecurity/ChainSecurity_USDT0_Ink_audit.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://berascan.com/address/0x779Ded0c9e1022225f8E0630b35a9b54bE713736) | `1278dad` 2025-01-13 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf) | `5a6170f` 2025-01-20 |  |

#### Flare

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://flare-explorer.flare.network/address/0x567287d2A9829215a37e3B88843d32f9221E7588) | `7dd2007` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `7d7af3a` 2025-02-16 | [CS-04](ChainSecurity/ChainSecurity_USDT0_Flare_audit.pdf), [GA-17](Guardian/USDT0_Flare_Deployment_report.pdf), [CS-05](ChainSecurity/ChainSecurity_USDT0_Ink_audit.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://flare-explorer.flare.network/address/0xe7cd86e13AC4309349F30B3435a9d337750fC82D) | `05393c9` 2025-01-17 | [CS-02](ChainSecurity/ChainSecurity_USDT0_Arbitrum_v2_audit.pdf), [OZ-01](Openzeppelin/USDT0_Audit.pdf) | `675d3a0` 2025-02-16 | [CS-04](ChainSecurity/ChainSecurity_USDT0_Flare_audit.pdf), [GA-17](Guardian/USDT0_Flare_Deployment_report.pdf) |

#### Corn (Maizenet)

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://cornscan.io/address/0x3f82943338a8a76c35BFA0c1828aA27fd43a34E4) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `b54fcb1` 2025-03-12 | [GA-16](Guardian/USDT0_Corn_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-45](Guardian/2026-05-27_USDT0_Corn_Network_Delisting_Txns.pdf) |
| Token | [TetherTokenOFTExtension](https://cornscan.io/address/0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `7eaec29` 2025-03-07 | [GA-16](Guardian/USDT0_Corn_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Sei

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://seiscan.io/address/0x56Fe74A2e3b484b921c447357203431a3485CC60) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `fd41851` 2025-03-26 | [GA-19](Guardian/USDT0_Sei_Deployment_report.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://seiscan.io/address/0x9151434b16b9763660705744891fA906F660EcC5) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `f93d13c` 2025-03-26 | [GA-19](Guardian/USDT0_Sei_Deployment_report.pdf) |

#### HyperEVM (Hyperliquid)

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://hyperevmscan.io/address/0x904861a24F30EC96ea7CFC3bE9EA4B476d237e98) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `a94cc3c` 2025-04-29 | [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-10](Guardian/2025-05-09_USDT0_HyperEVM.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [HyperliquidExtension](https://hyperevmscan.io/address/0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb) | `0e28691` 2025-03-02 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [GA-13](Guardian/Guardian_XAUT0_Report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-03](ChainSecurity/ChainSecurity_USDT0_HyperLiquid_and_Stable_audit.pdf) | `254cd24` 2025-04-29 | [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-11](Guardian/Guardian_USDT0_HyperEVM_Report.pdf) |

#### Rootstock

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://rootstock.blockscout.com/address/0x1a594d5d5d1c426281C1064B07f23F57B2716B61) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `e05a317` 2025-06-20 | [GA-18](Guardian/USDT0_Rootstock_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-27](Guardian/2025-10-09_USDT0_RootStock_Confirmations_Update.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-45](Guardian/2026-05-27_USDT0_Corn_Network_Delisting_Txns.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://rootstock.blockscout.com/address/0x779Ded0c9e1022225f8E0630b35a9b54bE713736) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `2e33f36` 2025-06-19 | [GA-18](Guardian/USDT0_Rootstock_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Polygon PoS

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://polygonscan.com/address/0x6BA10300f0DC58B7a1e4c0e41f5daBb7D7829e13) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `19d31b9` 2025-07-03 | [GA-20](Guardian/USDT0_Polygon_Deployment_and_Peer_Verification_report.pdf), [GA-47](Guardian/USDT0-Stellar-Deployment-Guardian-Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf) |
| Token | [UChildUSDT0](https://polygonscan.com/address/0xc2132D05D31c914a87C6611C10748AEb04B58e8F) | `e07b735` 2025-07-26 | [GA-15](Guardian/2025-06-05_USDT0_Polygon_Upgrade.pdf), [OZ-07](Openzeppelin/USDT0%20Child%20Token%20Audit.pdf) | [`0x920dba95`](https://polygonscan.com/tx/0x920dba951276c7cd557574494c20202030e1aa9a62c3a8859c13f7b827c4b48a) 2025-08-13 | [GA-20](Guardian/USDT0_Polygon_Deployment_and_Peer_Verification_report.pdf) |

#### X Layer

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://www.oklink.com/xlayer/address/0x94BCCa6bdfd6A61817Ab0E960bFedE4984505554) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `8c27fba` 2025-08-29 | [GA-25](Guardian/USDT0_XLayer_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-26](Guardian/USDT0_XLayer_and_Plasma_Peer_Verification_Report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://www.oklink.com/xlayer/address/0x779Ded0c9e1022225f8E0630b35a9b54bE713736) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `e80e58a` 2025-09-08 | [GA-25](Guardian/USDT0_XLayer_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Plasma

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://plasmascan.to/address/0x02ca37966753bDdDf11216B73B16C1dE756A7CF9) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `f2a98ce` 2025-09-11 | [GA-23](Guardian/USDT0_XAUT0_Plasma_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-47](Guardian/USDT0-Stellar-Deployment-Guardian-Report.pdf), [GA-26](Guardian/USDT0_XLayer_and_Plasma_Peer_Verification_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf) |
| Token | [TetherTokenOFTExtension](https://plasmascan.to/address/0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `468bcf6` 2025-09-09 | [GA-23](Guardian/USDT0_XAUT0_Plasma_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Conflux eSpace

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://evm.confluxscan.org/address/0xC57efa1c7113D98BdA6F9f249471704Ece5dd84A) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `e7edb23` 2025-10-27 | [GA-28](Guardian/USDT0_Conflux_Deployment_and_Peer_Verification_report.pdf), [GA-31](Guardian/2025-12-04_USDT0_Conflux_Monad_Mesh_Update.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://evm.confluxscan.org/address/0xaf37E8B6C9ED7f6318979f56Fc287d76c30847ff) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `465b3ed` 2025-10-27 | [GA-28](Guardian/USDT0_Conflux_Deployment_and_Peer_Verification_report.pdf) |

#### Mantle

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://mantlescan.xyz/address/0xcb768e263FB1C62214E7cab4AA8d036D76dc59CC) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `20de3ac` 2025-11-01 | [GA-29](Guardian/USDT0_Mantle_Deployment_and_Peer_Verification_report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://mantlescan.xyz/address/0x779Ded0c9e1022225f8E0630b35a9b54bE713736) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `9c7f1b7` 2025-11-01 | [GA-29](Guardian/USDT0_Mantle_Deployment_and_Peer_Verification_report.pdf) |

#### Stable

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://stablescan.xyz/address/0xedaba024be4d87974d5aB11C6Dd586963CcCB027) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `2b78b84` 2025-11-07 | [GA-57](Guardian/2025-11-13_USDT0_XAUT0_Monad_Stable_Wiring.pdf), [OZ-10](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20Token%20%26%20OFT%20on%20Stable%20Deployment%20Review-report.pdf), [GA-30](Guardian/2025-11-21_USDT0_XAUT0_Stable_Deployment.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [StableOFTExtension](https://stablescan.xyz/address/0x779Ded0c9e1022225f8E0630b35a9b54bE713736) | `a1baf64` 2025-11-12 | [OZ-10](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20Token%20%26%20OFT%20on%20Stable%20Deployment%20Review-report.pdf) | impl `a1baf64` 2025-11-12<br>proxy `910f6a4` 2025-10-30 | [OZ-10](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20Token%20%26%20OFT%20on%20Stable%20Deployment%20Review-report.pdf) |

#### Monad

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://monadscan.com/address/0x9151434b16b9763660705744891fA906F660EcC5) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `e7edb23` 2025-10-27 | [GA-56](Guardian/2025-11-07_USDT0_Monad_Deployment.pdf), [GA-31](Guardian/2025-12-04_USDT0_Conflux_Monad_Mesh_Update.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://monadscan.com/address/0xe7cd86e13AC4309349F30B3435a9d337750fC82D) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `3282208` 2025-10-27 | [GA-56](Guardian/2025-11-07_USDT0_Monad_Deployment.pdf) |

#### MegaETH

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://mega.etherscan.io/address/0x9151434b16b9763660705744891fA906F660EcC5) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `adbf5f3` 2026-01-15 | [GA-34](Guardian/USDT0_MegaETH_Deployment_Review_report.pdf), [GA-41](Guardian/USDT0_Plasma_Config_Change_Review_Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://mega.etherscan.io/address/0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `7173c02` 2025-12-30 | [GA-34](Guardian/USDT0_MegaETH_Deployment_Review_report.pdf) |

#### Morph

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://explorer.morphl2.io/address/0xcb768e263FB1C62214E7cab4AA8d036D76dc59CC) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `4c0d8d7` 2026-01-27 | [GA-35](Guardian/USDT0_Morph_Deployment_Review_%26_Peer_Connections_report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-60](Guardian/2026-06-02_USDT0_Polygon_Enforced_Gas_Change.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [TetherTokenOFTExtension](https://explorer.morphl2.io/address/0xe7cd86e13AC4309349F30B3435a9d337750fC82D) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `26dd085` 2026-01-27 | [GA-35](Guardian/USDT0_Morph_Deployment_Review_%26_Peer_Connections_report.pdf) |

#### Tempo

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeableTempo](https://explore.tempo.xyz/address/0xaf37E8B6C9ED7f6318979f56Fc287d76c30847ff) | `5eb7ba0` 2026-01-13 | [GA-36](Guardian/USDT0_Tempo_OFT_Adapter_report.pdf) | `c3d8543` 2026-02-17 | [GA-58](Guardian/2026-02-19_USDT0_Tempo_Deployments_and_Config.pdf), [OZ-15](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20Tempo%20Deployment%20Verification-report.pdf), [GA-47](Guardian/USDT0-Stellar-Deployment-Guardian-Report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf) |
| Token | [Tempo-native USDT0 token](https://explore.tempo.xyz/address/0x20c00000000000000000000014f22ca97301eb73) |  |  |  |  |

#### Hedera

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [HTSConnectorUpgradeable](https://hashscan.io/mainnet/contract/0xe3119e23fC2371d1E6b01775ba312035425A53d6) | `26fa1c3` 2026-01-15 | [GA-37](Guardian/USDT0_Hedera_USDT0_Connector_report.pdf) | `b753696` 2026-02-17 | [GA-39](Guardian/USDT0_Hedera_Deployment_Review_Report.pptx.pdf), [OZ-16](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20Hedera%20Mainnet%20Deployment%20Review-report.pdf), [GA-42](Guardian/USDT0_Tempo_Peer_Connections_Review_Report.pdf), [GA-61](Guardian/2026-08-06_USDT0_Multi_Chain_Deployment.pdf) |
| Token | [HTS token](https://hashscan.io/mainnet/contract/0x00000000000000000000000000000000009ce723) |  | [GA-38](Guardian/USDT0_Hedera_HTS_and_EVM_Report.pdf) |  |  |

#### Stellar

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [everdawn-oft](https://stellar.expert/explorer/public/contract/CBOWOLFSDM5PZXNFIVDMP5NZ7U2GSIHED6H6R446QOHF266XINKUMMF6) | `342ce81` 2026-04-09 | [GA-46](Guardian/USDT0-Stellar-Contracts-Guardian-Report-August-2026.pdf), [OS-04](OtterSec/Stellar_OFT-Ottersec-26Mar2026.pdf), [ZE-04](Zellic/Stellar_OFT-Zellic-27Mar2026.pdf), [OZ-18](Openzeppelin/USDT0%20Stellar%20OFT%20Audit.pdf) | [`8b2672956c`](https://stellar.expert/explorer/public/tx/8b2672956c57fcf79027f584758160a40b15d29589c8331b158a5c4dbe05c23a) 2026-07-26 | [OZ-19](Openzeppelin/Everdawn%20USDT0%20Stellar%20Deployment%20Assessment.pdf), [GA-47](Guardian/USDT0-Stellar-Deployment-Guardian-Report.pdf) |
| Token | [USDT0 (Stellar Asset Contract)](https://stellar.expert/explorer/public/contract/CBSJZEIO5C7KC2SF3MKSNXXJSW5G3VTNBX4ATMKUI3B2MR4JKM4R26YF) |  |  | [`5c1ceca840`](https://stellar.expert/explorer/public/tx/5c1ceca84007be63961422477c4c8253a81edfcf89438d81161a44ca8469f197) 2026-07-21 | [OZ-19](Openzeppelin/Everdawn%20USDT0%20Stellar%20Deployment%20Assessment.pdf) |

#### IOTA

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [oft package](https://explorer.iota.org/object/0xe6a11eb6a514b5510d731e5ed9d8e9294bcaad3b4696fa5d45406d11560b5902?network=mainnet) | `c213287` 2025-11-28 | [OZ-14](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20IOTA%20Contracts%20Audit-report.pdf), [CE-01](Certora/Iota%20Coin%20-%20Certora%20FV%20Report.pdf) | [`HvrnYGRspL`](https://explorer.iota.org/txblock/HvrnYGRspL6shwPvACkPyUFvVMfrNyYQL49EdXF5HGcf?network=mainnet) 2026-03-20 | [OZ-17](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20IOTA%20Deployment%20Review-report.pdf) |
| Token | [usdt0 coin package](https://explorer.iota.org/object/0x25afeacdd3b0e757ae40aa4b9852261003e1dffeeb37d2c4f2904bb809807ac9?module=usdt0&network=mainnet) | `ae9d81e` 2025-11-19 | [OZ-14](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20IOTA%20Contracts%20Audit-report.pdf), [CE-01](Certora/Iota%20Coin%20-%20Certora%20FV%20Report.pdf) | [`2xMwnPxGuM`](https://explorer.iota.org/txblock/2xMwnPxGuMd9qgFhdoFkYg8133CqYog5ofkJZszSjxYj?network=mainnet) 2026-03-20 | [OZ-17](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20IOTA%20Deployment%20Review-report.pdf) |

## XAUt0 (Tether Gold)

#### Ethereum

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OAdapterUpgradeable](https://etherscan.io/address/0xb9c2321BB7D0Db468f570D10A424d1Cc8EFd696C) | `18c2b4d` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `b2c53dc` 2025-04-22 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |

#### Arbitrum One

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://arbiscan.io/address/0xf40542a7B66AD7C68C459EE3679635D2fDB6dF39) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `b2c53dc` 2025-04-22 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://arbiscan.io/address/0x40461291347e1eCbb09499F3371D3f17f10d7159) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `6ae7baa` 2025-04-24 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Ink

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://explorer.inkonchain.com/address/0xA1bE1572B4beef24f812EfDc58bdc41D56a0dAB2) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `1767a37` 2025-09-11 | [GA-21](Guardian/USDT0_XAUT0_INK_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-32](Guardian/2025-12-10_USDT0_XAUT0_Wiring.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://explorer.inkonchain.com/address/0xF50258D3c1dd88946C567920B986A12e65b50dAc) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | impl `f9b9aa7` 2025-03-14<br>proxy `9f2ca0f` 2025-09-02 | [GA-21](Guardian/USDT0_XAUT0_INK_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### HyperEVM (Hyperliquid)

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://hyperevmscan.io/address/0x4E41cfc3F3B19E29E323D2c36F8f202a1e151dAF) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `3f80661` 2025-04-28 | [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [HyperliquidExtension](https://hyperevmscan.io/address/0xf4D9235269a96aaDaFc9aDAe454a0618eBE37949) | `0e28691` 2025-03-02 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [GA-13](Guardian/Guardian_XAUT0_Report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-03](ChainSecurity/ChainSecurity_USDT0_HyperLiquid_and_Stable_audit.pdf) | `ffd78fc` 2025-04-28 | [GA-13](Guardian/Guardian_XAUT0_Report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Polygon PoS

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://polygonscan.com/address/0x5421Cf4288d8007D3c43AC4246eaFCe5b049e352) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `b2c53dc` 2025-04-22 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://polygonscan.com/address/0xF1815bd50389c46847f0Bda824eC8da914045D14) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `6ae7baa` 2025-04-24 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Avalanche C-Chain

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://snowscan.xyz/address/0x7E7866bc840aFf9f517a49AfDbfC9e7C7Aba9a68) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `4edbf26` 2025-05-21 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://snowscan.xyz/address/0x2775d5105276781B4b85bA6eA6a6653bEeD1dd32) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `0de57b0` 2025-05-21 | [GA-12](Guardian/2025-05-16_USDT0_XAUt.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Plasma

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://plasmascan.to/address/0x63aB93cBC9d4ecD9c4947b1A38F458147C08E6F7) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `f2a98ce` 2025-09-11 | [GA-22](Guardian/USDT0_XAUT0_Plasma_Deployment_2_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://plasmascan.to/address/0x1B64B9025EEbb9A6239575dF9Ea4b9Ac46D4d193) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | impl `468bcf6` 2025-09-09<br>proxy `50ae619` 2025-09-11 | [GA-22](Guardian/USDT0_XAUT0_Plasma_Deployment_2_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf) |

#### Celo

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://celoscan.io/address/0x21cAef8A43163Eea865baeE23b9C2E327696A3bf) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `081a8cf` 2025-09-18 | [GA-62](Guardian/USDT0_XAUT0_Celo_Deployment_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [CeloOFTExtension](https://celoscan.io/address/0xaf37E8B6C9ED7f6318979f56Fc287d76c30847ff) | `6278b85` 2026-04-06 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [OZ-21](Openzeppelin/USDT0%20-%20%2304%20Retainer%20%2825%20Tether%20Contracts%20PR%20%23110%20Review%29-report.pdf), [GA-48](Guardian/USDT0-Tether-Contracts-PR110-Upgrade-Guardian-Report-September-2026.pdf) | impl `4287751` 2026-04-06<br>proxy `ce7c583` 2025-09-14 | [GA-54](Guardian/2025-04-08_USDT0_Celo_XAUT0_Upgrade_USAT_Deployment.pdf) |

#### Conflux eSpace

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://evm.confluxscan.org/address/0x06d886Ff518b5E642E7E6aaD3cE797B7DABD8e9a) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `1ce2574` 2026-04-02 | [GA-53](Guardian/2025-04-03_USDT0_XAUT0_Conflux_Deployment.pdf), [GA-44](Guardian/2026-05-12_USDT0_Canary_Chain_Configs_Tx_Verifications.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://evm.confluxscan.org/address/0xACc6EFBE554397b741BaAdEcF0120780b858f5F4) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `029b80f` 2026-04-02 | [GA-53](Guardian/2025-04-03_USDT0_XAUT0_Conflux_Deployment.pdf) |

#### Stable

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://stablescan.xyz/address/0xD8479f87686ed263D00Ca7505F86327dbeD4171A) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `2b78b84` 2025-11-07 | [GA-57](Guardian/2025-11-13_USDT0_XAUT0_Monad_Stable_Wiring.pdf), [GA-30](Guardian/2025-11-21_USDT0_XAUT0_Stable_Deployment.pdf), [GA-32](Guardian/2025-12-10_USDT0_XAUT0_Wiring.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://stablescan.xyz/address/0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | impl `910f6a4` 2025-10-30<br>proxy `471b1c0` 2025-10-30 | [GA-57](Guardian/2025-11-13_USDT0_XAUT0_Monad_Stable_Wiring.pdf), [GA-30](Guardian/2025-11-21_USDT0_XAUT0_Stable_Deployment.pdf) |

#### Monad

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://monadscan.com/address/0x21cAef8A43163Eea865baeE23b9C2E327696A3bf) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `e7edb23` 2025-10-27 | [GA-56](Guardian/2025-11-07_USDT0_Monad_Deployment.pdf), [GA-32](Guardian/2025-12-10_USDT0_XAUT0_Wiring.pdf), [GA-52](Guardian/2025-03-29_USDT0_XAUT0_BSC_Wiring.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://monadscan.com/address/0x01bFF41798a0BcF287b996046Ca68b395DbC1071) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | impl `3282208` 2025-10-27<br>proxy `66b9ce3` 2025-10-27 | [GA-56](Guardian/2025-11-07_USDT0_Monad_Deployment.pdf) |

#### BNB Smart Chain

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://bscscan.com/address/0x53C3A64c8942288e12813C1F8457Db45980BcfC2) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `6271cc3` 2026-03-17 | [GA-40](Guardian/XAUt_BSC_Deployment_Review_Report.pdf), [GA-44](Guardian/2026-05-12_USDT0_Canary_Chain_Configs_Tx_Verifications.pdf), [GA-55](Guardian/2025-04-08_USDT0_XAUT0_Conflux_Wiring.pdf) |
| Token | [TetherTokenOFTExtension](https://bscscan.com/address/0x21cAef8A43163Eea865baeE23b9C2E327696A3bf) | `0e28691` 2025-03-02 | [GA-08](Guardian/USDT0%20-%20Superchain%20Deployment_report.pdf), [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [OZ-20](Openzeppelin/USDT0%20-%20Retainer%20%2304%20-%20%2824%20USDT%20on%20Avalanche%20Token%20Upgrade%20%2B%20Playbook%20Review%29-report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `00db1df` 2026-03-17 | [GA-40](Guardian/XAUt_BSC_Deployment_Review_Report.pdf) |

#### Solana

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OFT store (LayerZero OFT program)](https://explorer.solana.com/address/XWxJJE6Dq8EgdnhMWYU587f7St4HJuWbBHPstV2GtKR) | `dab81ac` 2024-12-06 |  | `ddcdb00` 2025-09-11 | [GA-24](Guardian/USDT0_XAUT0_SOL_Deployment_and_Peer_Verification_report.pdf), [OZ-08](Openzeppelin/Everdawn%20Deployment%20Assessment.pdf), [GA-32](Guardian/2025-12-10_USDT0_XAUT0_Wiring.pdf), [GA-43](Guardian/2026-05-04_USDT0_Solana_Transaction_Verification.pdf), [GA-44](Guardian/2026-05-12_USDT0_Canary_Chain_Configs_Tx_Verifications.pdf) |
| Token | [XAUt0 SPL mint](https://explorer.solana.com/address/AymATz4TCL9sWNEEV9Kvyz45CHVhDZ6kUgjTJPzLpU9P) |  |  | [`T44aQvnmzT`](https://solscan.io/tx/T44aQvnmzTmZZzLnoMr1vr9WAwyx2AGBbFhgRvfVdUPBn5zGhMtqZsvjp5YtfnS7EXRrC1Vo8Fg3Y45Skj1U3EG) 2025-09-11 |  |

#### TON

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [BamOFT](https://tonviewer.com/EQCQ2f8ceBRwX8x0-LdZhHbWXzuVNvwTJymwYG8L6C5hf_5V) | `5b04713` 2025-04-28 | [OZ-06](Openzeppelin/XAUt0%20TON%20OFT%20Audit.pdf), [ZE-02](Zellic/TON_OFT-Zellic-19May2025.pdf), [OS-01](OtterSec/TON_OFT-Ottersec-23May2025.pdf) | `5b04713` 2025-04-28 | [OZ-09](Openzeppelin/USDT0%20-%20Retainer%20%2309%20-%20TON%20Multisig%20Transaction%20Review-report.pdf), [OZ-11](Openzeppelin/USDT0%20-%20Retainer%20%2303%20-%20TON%20Multisig%20Transaction%20Re-Review-report.pdf) |
| Token | [JettonMinter](https://tonviewer.com/EQA1R_LuQCLHlMgOo1S4G7Y7W1cd0FrAkbA10Zq7rddKxi9k) | `5b04713` 2025-04-28 | [OZ-06](Openzeppelin/XAUt0%20TON%20OFT%20Audit.pdf), [ZE-02](Zellic/TON_OFT-Zellic-19May2025.pdf), [OS-01](OtterSec/TON_OFT-Ottersec-23May2025.pdf) | `5b04713` 2025-04-28 |  |

## USAT

#### Ethereum

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OAdapterUpgradeable](https://etherscan.io/address/0x18171f318A49051301C3422b6042fcA2d8Be43DF) | `18c2b4d` 2025-01-04 | [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf) | `066efd2` 2026-04-01 | [GA-59](Guardian/2026-04-28_USDT0_Celo_USAT_Wirings.pdf) |

#### Avalanche C-Chain

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://snowscan.xyz/address/0xDCee5eF6779567C27e69D57f6A143449372D1784) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `46a8706` 2026-09-16 | [GA-51](Guardian/USDT0-Avalanche-Deployment-Guardian-Report-September-2026_v2.pdf) |
| Token | [TetherTokenOFTExtension](https://snowscan.xyz/address/0x9A5926fd88F747c357738b1e82aFB46AB80f0A6b) | `daa70ff` 2026-09-04 | [GA-48](Guardian/USDT0-Tether-Contracts-PR110-Upgrade-Guardian-Report-September-2026.pdf), [OZ-21](Openzeppelin/USDT0%20-%20%2304%20Retainer%20%2825%20Tether%20Contracts%20PR%20%23110%20Review%29-report.pdf) | `95509a5` 2026-09-07 | [GA-51](Guardian/USDT0-Avalanche-Deployment-Guardian-Report-September-2026_v2.pdf) |

#### Celo

|  | Contract | Version (last change) | Audited by | Deployed | Deployment verified by |
|---|---|---|---|---|---|
| OFT | [OUpgradeable](https://celoscan.io/address/0xC8F467E1Ba04FFdECA1Cd1878ca3416D84045d0E) | `a132aa0` 2025-02-27 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [CS-01](ChainSecurity/ChainSecurity_USDT0_audit.pdf), [GA-01](Guardian/2025-01-14_USDT0.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [GA-05](Guardian/2025-03-12_USDT0_IERC7802_Support.pdf) | `f065980` 2026-04-06 | [GA-59](Guardian/2026-04-28_USDT0_Celo_USAT_Wirings.pdf) |
| Token | [CeloOFTExtension](https://celoscan.io/address/0xD2ab3C9A02DBBAB236BfEC45D1d755DF4267F771) | `6278b85` 2026-04-06 | [OZ-02](Openzeppelin/Everdawn%20USDT0%20ERC-7802%20Upgrade%20Audit.pdf), [PA-01](Paladin/20250110_Paladin_Everdawn_Final_Report.pdf), [OZ-21](Openzeppelin/USDT0%20-%20%2304%20Retainer%20%2825%20Tether%20Contracts%20PR%20%23110%20Review%29-report.pdf), [GA-48](Guardian/USDT0-Tether-Contracts-PR110-Upgrade-Guardian-Report-September-2026.pdf) | `6278b85` 2026-04-06 | [GA-48](Guardian/USDT0-Tether-Contracts-PR110-Upgrade-Guardian-Report-September-2026.pdf), [OZ-21](Openzeppelin/USDT0%20-%20%2304%20Retainer%20%2825%20Tether%20Contracts%20PR%20%23110%20Review%29-report.pdf), [GA-54](Guardian/2025-04-08_USDT0_Celo_XAUT0_Upgrade_USAT_Deployment.pdf) |

