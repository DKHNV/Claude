# Claude DNS Maintenance Report

Generated: `2026-11-19T12:12:18Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 146 |
| Pending | 4 |
| Suspect | 8 |
| Quarantine | 21 |
| Excluded | 0 |
| Expired | 16 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 143 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **146**
Average stability: **97.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 311 | TIMEOUT | 18.116.101.233, 18.227.5.129, 3.130.176.201 | 0.0 | 36 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 311 | TIMEOUT | 13.185.122.205, 3.16.104.24, 3.21.217.103 | 0.0 | 36 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 311 | TIMEOUT | 3.131.45.70, 3.147.173.186, 3.22.176.20 | 0.0 | 36 |

## Discovery

Discovery state updated: `2026-11-19T12:12:18Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
