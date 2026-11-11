# Claude DNS Maintenance Report

Generated: `2026-11-11T22:18:21Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 143 |
| Pending | 6 |
| Suspect | 2 |
| Quarantine | 15 |
| Excluded | 0 |
| Expired | 24 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 140 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **143**
Average stability: **97.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 293 | TIMEOUT | 18.119.81.85, 18.227.142.10, 3.131.237.190 | 0.0 | 40 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 293 | TIMEOUT | 3.135.60.169, 3.147.9.226, 3.15.76.244 | 0.0 | 40 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 293 | TIMEOUT | 3.143.179.53, 3.150.81.34, 3.22.176.20 | 0.0 | 40 |

## Discovery

Discovery state updated: `2026-11-11T22:18:21Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
