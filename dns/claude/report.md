# Claude DNS Maintenance Report

Generated: `2026-10-01T09:26:29Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 117 |
| Pending | 1 |
| Suspect | 2 |
| Quarantine | 9 |
| Excluded | 0 |
| Expired | 33 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 114 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **117**
Average stability: **97.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 160 | TIMEOUT | 18.117.22.35, 18.119.251.107, 3.146.114.200 | 0.0 | 51 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 160 | TIMEOUT | 18.188.33.188, 3.17.52.203, 3.20.45.24 | 0.0 | 51 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 160 | TIMEOUT | 18.189.144.65, 3.23.150.223, 52.15.174.127 | 0.0 | 51 |

## Discovery

Discovery state updated: `2026-10-01T09:26:29Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
