]1655
# KQL Detection Rules — TitanShield Threat Hunt

A collection of KQL detection rules written against 
a simulated enterprise security dataset (TitanShield).

## Detections

| # | File | What it Detects |
|---|------|-----------------|
| 1 | 01-external-ip-detection.kql | External IP login attempts |
| 2 | 02-aggressive-ip-ranking.kql | Most aggressive attacker IPs |
| 3 | 03-breach-confirmation.kql | Confirmed account breaches |
| 4 | 04-credential-stuffing.kql | Credential stuffing attacks |
| 5 | 05-after-hours-detection.kql | After hours external logins |

## Tools
- Azure Data Explorer
- KQL (Kusto Query Language)
- TitanShield sample security dataset
