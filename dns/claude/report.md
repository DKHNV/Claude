# Claude DNS Maintenance Report

Generated: `2026-10-25T08:44:29Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 130 |
| Pending | 1 |
| Suspect | 0 |
| Quarantine | 21 |
| Excluded | 0 |
| Expired | 25 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 127 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **130**
Average stability: **97.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 241 | TIMEOUT | 3.133.10.11, 3.140.10.151, 3.20.100.197 | 0.0 | 52 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 241 | TIMEOUT | 18.222.89.254, 18.226.244.154, 3.128.249.144 | 0.0 | 52 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 241 | TIMEOUT | 18.118.234.93, 18.225.26.50, 3.136.137.215 | 0.0 | 52 |

## Discovery

Discovery state updated: `2026-10-25T08:44:29Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
