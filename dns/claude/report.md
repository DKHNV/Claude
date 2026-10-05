# Claude DNS Maintenance Report

Generated: `2026-10-05T09:37:46Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 118 |
| Pending | 1 |
| Suspect | 2 |
| Quarantine | 10 |
| Excluded | 0 |
| Expired | 32 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 115 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **118**
Average stability: **97.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 173 | TIMEOUT | 18.119.251.107, 3.146.129.234, 3.147.162.60 | 0.0 | 48 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 173 | TIMEOUT | 13.59.25.86, 18.188.33.188, 3.133.171.126 | 0.0 | 48 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 173 | TIMEOUT | 18.118.230.180, 18.189.144.65, 3.23.150.223 | 0.0 | 48 |

## Discovery

Discovery state updated: `2026-10-05T09:37:46Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
