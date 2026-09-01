# Claude DNS Maintenance Report

Generated: `2026-09-01T17:59:22Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 102 |
| Pending | 0 |
| Suspect | 1 |
| Quarantine | 44 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 100 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **103**
Average stability: **97.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 48 | TIMEOUT | 18.188.223.71, 18.227.115.25, 3.136.175.50 | 0.0 | 48 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 48 | TIMEOUT | 18.189.116.204, 3.12.101.120, 3.17.15.237 | 0.0 | 48 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 48 | TIMEOUT | 3.136.53.238, 3.14.101.156, 3.17.247.188 | 0.0 | 48 |

## Discovery

Discovery state updated: `2026-09-01T17:59:22Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
