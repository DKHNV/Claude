# Claude DNS Maintenance Report

Generated: `2026-11-22T01:39:51Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 149 |
| Pending | 3 |
| Suspect | 7 |
| Quarantine | 25 |
| Excluded | 0 |
| Expired | 16 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 145 |
| Unknown | 2 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **150**
Average stability: **96.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_ERROR | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 317 | TIMEOUT | 18.116.101.233, 3.130.176.201, 3.147.214.35 | 0.0 | 34 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 317 | TIMEOUT | 13.185.122.205, 3.143.193.60, 3.21.217.103 | 0.0 | 34 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 317 | TIMEOUT | 18.220.174.187, 3.131.45.70, 3.150.100.125 | 0.0 | 34 |
| `operator.certification-staging.anthropic.com` | unknown | `2026-11-19T22:46:35Z` | 6 | TLS_ERROR | 136.82.91.96 | 0.0 | 6 |
| `operator.certification.anthropic.com` | unknown | `2026-11-19T22:46:35Z` | 6 | TLS_ERROR | 136.68.147.187 | 0.0 | 6 |

## Discovery

Discovery state updated: `2026-11-22T01:39:51Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
