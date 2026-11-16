# Claude DNS Maintenance Report

Generated: `2026-11-16T12:05:43Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 145 |
| Pending | 6 |
| Suspect | 12 |
| Quarantine | 13 |
| Excluded | 0 |
| Expired | 17 |

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
| TIMEOUT | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 305 | TIMEOUT | 18.116.101.233, 18.227.5.129, 3.130.176.201 | 0.0 | 38 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 305 | TIMEOUT | 3.135.60.169, 3.15.76.244, 3.16.104.24 | 0.0 | 38 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 305 | TIMEOUT | 3.147.173.186, 3.150.81.34, 3.22.176.20 | 0.0 | 38 |
| `metrics.anthropic.com` | alive | `2026-11-16T12:05:43Z` | 1 | TIMEOUT | 136.113.71.169, 34.123.83.248, 35.239.79.203 | 97.4 | 38 |

## Discovery

Discovery state updated: `2026-11-16T12:05:43Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
