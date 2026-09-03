# Claude DNS Maintenance Report

Generated: `2026-09-03T18:06:36Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 104 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 45 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 101 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **104**
Average stability: **97.1%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 56 | TIMEOUT | 18.188.223.71, 18.227.115.25, 3.136.175.50 | 0.0 | 54 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 56 | TIMEOUT | 18.189.116.204, 3.12.101.120, 3.17.15.237 | 0.0 | 54 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 56 | TIMEOUT | 3.136.53.238, 3.14.101.156, 3.17.247.188 | 0.0 | 54 |

## Discovery

Discovery state updated: `2026-09-03T18:06:36Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
