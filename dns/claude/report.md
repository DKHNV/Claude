# Claude DNS Maintenance Report

Generated: `2026-11-01T10:49:02Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 130 |
| Pending | 3 |
| Suspect | 2 |
| Quarantine | 13 |
| Excluded | 0 |
| Expired | 29 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 127 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **130**
Average stability: **97.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 264 | TIMEOUT | 18.225.132.215, 3.18.244.171, 77.113.2.159 | 0.0 | 50 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 264 | TIMEOUT | 18.222.89.254, 3.128.249.144, 3.13.250.10 | 0.0 | 50 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 264 | TIMEOUT | 16.59.248.75, 18.118.234.93, 18.218.3.70 | 0.0 | 50 |

## Discovery

Discovery state updated: `2026-11-01T10:49:02Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
