# Claude DNS Maintenance Report

Generated: `2026-09-18T22:50:39Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 108 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 45 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 105 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **108**
Average stability: **97.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 116 | TIMEOUT | 18.220.75.250, 3.137.16.135, 3.18.98.79 | 0.0 | 55 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 116 | TIMEOUT | 18.225.144.192, 3.130.212.53, 3.140.235.105 | 0.0 | 55 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 116 | TIMEOUT | 13.59.31.58, 3.129.116.237, 3.150.233.90 | 0.0 | 55 |

## Discovery

Discovery state updated: `2026-09-18T22:50:39Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
