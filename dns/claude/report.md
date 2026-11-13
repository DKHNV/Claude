# Claude DNS Maintenance Report

Generated: `2026-11-13T21:40:07Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 144 |
| Pending | 8 |
| Suspect | 6 |
| Quarantine | 15 |
| Excluded | 0 |
| Expired | 19 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 142 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **145**
Average stability: **97.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 297 | TIMEOUT | 18.119.81.85, 18.227.142.10, 18.227.5.129 | 0.0 | 38 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 297 | TIMEOUT | 3.135.60.169, 3.15.76.244, 3.16.104.24 | 0.0 | 38 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 297 | TIMEOUT | 3.147.173.186, 3.150.81.34, 3.22.176.20 | 0.0 | 38 |

## Discovery

Discovery state updated: `2026-11-13T21:40:07Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
