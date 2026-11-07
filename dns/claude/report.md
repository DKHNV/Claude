# Claude DNS Maintenance Report

Generated: `2026-11-07T10:42:24Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 137 |
| Pending | 2 |
| Suspect | 2 |
| Quarantine | 15 |
| Excluded | 0 |
| Expired | 29 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 134 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **137**
Average stability: **97.8%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 281 | TIMEOUT | 18.119.81.85, 18.225.132.215, 3.131.237.190 | 0.0 | 44 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 281 | TIMEOUT | 13.58.222.50, 18.116.217.208, 3.147.9.226 | 0.0 | 44 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 281 | TIMEOUT | 18.226.204.59, 3.143.179.53, 3.151.175.156 | 0.0 | 44 |

## Discovery

Discovery state updated: `2026-11-07T10:42:24Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
