# Claude DNS Maintenance Report

Generated: `2026-11-25T13:34:41Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 153 |
| Pending | 1 |
| Suspect | 3 |
| Quarantine | 30 |
| Excluded | 0 |
| Expired | 15 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 148 |
| Unknown | 2 |
| Suspect | 1 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **154**
Average stability: **95.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_ERROR | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 325 | TIMEOUT | 3.147.214.35, 3.151.85.3, 3.21.153.250 | 0.0 | 33 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 325 | TIMEOUT | 13.185.122.205, 3.143.193.60, 3.21.217.103 | 0.0 | 33 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 325 | TIMEOUT | 18.220.174.187, 3.131.45.70, 3.150.100.125 | 0.0 | 33 |
| `hooks.certification-staging.anthropic.com` | unknown | `2026-11-25T00:08:46Z` | 2 | TLS_ERROR | 34.149.2.31 | 0.0 | 2 |
| `hooks.certification.anthropic.com` | unknown | `2026-11-25T00:08:46Z` | 2 | TLS_ERROR | 34.98.113.53 | 0.0 | 2 |
| `operator.certification.anthropic.com` | suspect | `2026-11-19T22:46:35Z` | 14 | TLS_ERROR | 136.68.147.187 | 0.0 | 14 |

## Discovery

Discovery state updated: `2026-11-25T13:34:41Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
