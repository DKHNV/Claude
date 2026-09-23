# Claude DNS Maintenance Report

Generated: `2026-09-23T23:13:12Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 116 |
| Pending | 5 |
| Suspect | 2 |
| Quarantine | 10 |
| Excluded | 0 |
| Expired | 28 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 113 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **116**
Average stability: **97.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 135 | TIMEOUT | 18.117.22.35, 3.146.114.200, 3.147.149.10 | 0.0 | 54 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 135 | TIMEOUT | 16.59.99.5, 18.225.144.192, 3.20.45.24 | 0.0 | 54 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 135 | TIMEOUT | 13.59.31.58, 3.129.116.237, 3.23.2.132 | 0.0 | 54 |

## Discovery

Discovery state updated: `2026-09-23T23:13:12Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
