# Claude DNS Maintenance Report

Generated: `2026-09-11T13:01:57Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 107 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 45 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 104 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **107**
Average stability: **97.1%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 87 | TIMEOUT | 18.188.223.71, 18.227.115.25, 3.18.98.79 | 0.0 | 58 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 87 | TIMEOUT | 18.189.133.118, 3.130.212.53, 52.14.88.38 | 0.0 | 58 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 87 | TIMEOUT | 16.58.216.3, 18.116.146.29, 3.150.233.90 | 0.0 | 58 |

## Discovery

Discovery state updated: `2026-09-11T13:01:57Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
