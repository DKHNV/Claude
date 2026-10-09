# Claude DNS Maintenance Report

Generated: `2026-10-09T19:50:52Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 122 |
| Pending | 4 |
| Suspect | 1 |
| Quarantine | 12 |
| Excluded | 0 |
| Expired | 28 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 119 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **122**
Average stability: **97.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 185 | TIMEOUT | 16.58.177.29, 18.225.191.179, 18.227.162.175 | 0.0 | 43 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 185 | TIMEOUT | 13.59.25.86, 18.190.134.41, 3.133.171.126 | 0.0 | 43 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 185 | TIMEOUT | 18.118.230.180, 3.129.169.2, 3.150.244.51 | 0.0 | 43 |

## Discovery

Discovery state updated: `2026-10-09T19:50:52Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
