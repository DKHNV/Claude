# Claude DNS Maintenance Report

Generated: `2026-11-20T12:13:51Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 150 |
| Pending | 5 |
| Suspect | 6 |
| Quarantine | 22 |
| Excluded | 0 |
| Expired | 17 |

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
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 313 | TIMEOUT | 18.116.101.233, 18.227.5.129, 3.130.176.201 | 0.0 | 35 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 313 | TIMEOUT | 13.185.122.205, 3.143.193.60, 3.21.217.103 | 0.0 | 35 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 313 | TIMEOUT | 18.220.174.187, 3.131.45.70, 3.147.173.186 | 0.0 | 35 |
| `operator.certification-staging.anthropic.com` | unknown | `2026-11-19T22:46:35Z` | 2 | TLS_ERROR | 136.82.91.96 | 0.0 | 2 |
| `operator.certification.anthropic.com` | unknown | `2026-11-19T22:46:35Z` | 2 | TLS_ERROR | 136.68.147.187 | 0.0 | 2 |

## Discovery

Discovery state updated: `2026-11-20T12:13:51Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
