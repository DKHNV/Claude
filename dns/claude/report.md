# Claude DNS Maintenance Report

Generated: `2026-10-08T09:31:14Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 121 |
| Pending | 2 |
| Suspect | 1 |
| Quarantine | 11 |
| Excluded | 0 |
| Expired | 31 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 118 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **121**
Average stability: **97.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 181 | TIMEOUT | 16.58.177.29, 18.225.191.179, 18.227.162.175 | 0.0 | 45 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 181 | TIMEOUT | 13.59.25.86, 18.190.134.41, 3.133.171.126 | 0.0 | 45 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 181 | TIMEOUT | 18.118.230.180, 3.129.169.2, 3.150.244.51 | 0.0 | 45 |

## Discovery

Discovery state updated: `2026-10-08T09:31:14Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
