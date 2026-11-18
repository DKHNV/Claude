# Claude DNS Maintenance Report

Generated: `2026-11-18T12:18:28Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 145 |
| Pending | 4 |
| Suspect | 10 |
| Quarantine | 19 |
| Excluded | 0 |
| Expired | 15 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 142 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **145**
Average stability: **97.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 309 | TIMEOUT | 18.116.101.233, 18.227.5.129, 3.130.176.201 | 0.0 | 37 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 309 | TIMEOUT | 3.135.60.169, 3.16.104.24, 3.21.217.103 | 0.0 | 37 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 309 | TIMEOUT | 3.147.173.186, 3.150.81.34, 3.22.176.20 | 0.0 | 37 |

## Discovery

Discovery state updated: `2026-11-18T12:18:28Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
