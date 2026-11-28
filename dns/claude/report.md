# Claude DNS Maintenance Report

Generated: `2026-11-28T12:26:47Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 152 |
| Pending | 1 |
| Suspect | 2 |
| Quarantine | 33 |
| Excluded | 0 |
| Expired | 14 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 147 |
| Unknown | 0 |
| Suspect | 2 |
| Dead | 4 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **153**
Average stability: **95.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_ERROR | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 331 | TIMEOUT | 3.147.214.35, 3.151.85.3, 3.21.153.250 | 0.0 | 32 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 331 | TIMEOUT | 18.119.249.226, 3.128.13.101, 3.133.230.181 | 0.0 | 32 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 331 | TIMEOUT | 3.137.118.49, 3.138.148.190, 3.150.100.125 | 0.0 | 32 |
| `hooks.certification-staging.anthropic.com` | suspect | `2026-11-25T00:08:46Z` | 8 | TLS_ERROR | 34.149.2.31 | 0.0 | 8 |
| `hooks.certification.anthropic.com` | suspect | `2026-11-25T00:08:46Z` | 8 | TLS_ERROR | 34.98.113.53 | 0.0 | 8 |
| `operator.certification.anthropic.com` | dead | `2026-11-19T22:46:35Z` | 20 | TLS_ERROR | 136.68.147.187 | 0.0 | 20 |

## Discovery

Discovery state updated: `2026-11-28T12:26:47Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
