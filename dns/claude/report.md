# Claude DNS Maintenance Report

Generated: `2026-10-20T18:46:12Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 128 |
| Pending | 0 |
| Suspect | 2 |
| Quarantine | 19 |
| Excluded | 0 |
| Expired | 26 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 126 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 3 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **129**
Average stability: **97.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 223 | TIMEOUT | 3.12.236.204, 3.133.10.11, 3.20.100.197 | 0.0 | 48 |
| `atlantis-staging.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 223 | TIMEOUT | 18.189.164.194, 18.226.244.154, 3.132.243.93 | 0.0 | 48 |
| `atlantis.c.anthropic.com` | dead | `2026-08-20T17:28:27Z` | 223 | TIMEOUT | 18.225.26.50, 3.136.137.215, 3.141.86.168 | 0.0 | 48 |
| `metrics.anthropic.com` | alive | `2026-10-20T18:46:12Z` | 1 | TIMEOUT | 136.113.71.169, 34.123.83.248, 35.239.79.203 | 95.8 | 48 |

## Discovery

Discovery state updated: `2026-10-20T18:46:12Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
