# Claude DNS Maintenance Report

Generated: `2026-10-20T13:52:09Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 127 |
| Pending | 0 |
| Suspect | 2 |
| Quarantine | 19 |
| Excluded | 0 |
| Expired | 26 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 125 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **128**
Average stability: **97.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 222 | TIMEOUT | 3.12.236.204, 3.133.10.11, 3.20.100.197 | 0.0 | 47 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 222 | TIMEOUT | 18.189.164.194, 18.226.244.154, 3.132.243.93 | 0.0 | 47 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 222 | TIMEOUT | 18.225.26.50, 3.136.137.215, 3.141.86.168 | 0.0 | 47 |

## Discovery

Discovery state updated: `2026-10-20T13:52:09Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
