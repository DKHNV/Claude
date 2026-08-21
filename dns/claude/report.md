# Claude DNS Maintenance Report

Generated: `2026-08-21T03:37:15Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 101 |
| Pending | 8 |
| Suspect | 0 |
| Quarantine | 35 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 98 |
| Unknown | 38 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **136**
Average stability: **72.1%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 38 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `atlantis-sandbox.c.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 4 | TIMEOUT | 18.227.223.115, 3.130.143.161, 3.136.92.242 | 0.0 | 4 |
| `atlantis-staging.c.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 4 | TIMEOUT | 18.189.116.204, 3.148.54.199, 3.17.15.237 | 0.0 | 4 |
| `atlantis.c.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 4 | TIMEOUT | 18.216.87.155, 3.136.53.238, 3.14.101.156 | 0.0 | 4 |
| `sandbox-chs2.staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 242.243.0.66 | 0.0 | 1 |
| `sandbox.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.8 | 0.0 | 1 |
| `sandbox.staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.117 | 0.0 | 1 |
| `stt-flux-a100.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-flux-a100.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-flux-multi-a100.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-flux-multi-a100.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-flux-multi-chs2.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 242.243.0.68 | 0.0 | 1 |
| `stt-flux-multi-chs2.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 242.243.0.69 | 0.0 | 1 |
| `stt-flux-multi.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-flux-multi.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-flux.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-flux.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s0.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s0.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s1.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s1.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s2.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s2.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s3.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s3.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s4.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s4.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s5.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s5.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s6.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s6.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s7.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s7.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3-s8.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3-s8.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt-nova3.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt-nova3.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |
| `stt.titanium-staging.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.5 | 0.0 | 1 |
| `stt.titanium.api.anthropic.com` | unknown | `2026-08-20T17:28:27Z` | 1 | TIMEOUT | 10.104.0.6 | 0.0 | 1 |

## Discovery

Discovery state updated: `2026-08-21T03:37:15Z`

## Notes

- Public active DNS file: `Claude_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
