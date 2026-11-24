# RAPx 0.7.80 targeted results

Toolchain: `nightly-2026-11-23`

**Soundness pass rate: 79 / 564 = 14.01%**

| Result | Count | Rate |
|---|---:|---:|
| SOUND | 79 | 14.01% |
| UNSOUND | 59 | 10.46% |
| UNKNOWN | 417 | 73.94% |
| NOT_RUN | 9 | 1.60% |

| UNKNOWN category | Unproved checks |
|---|---:|
| No classified UNKNOWN results | 0 |

| Crate | Targets | SOUND | UNSOUND | UNKNOWN | NOT_RUN |
|---|---:|---:|---:|---:|---:|
| `openssl 0.10.81` | 166 | 5 (3.01%) | 1 (0.60%) | 160 (96.39%) | 0 (0.00%) |
| `heapless 0.9.3` | 75 | 3 (4.00%) | 2 (2.67%) | 70 (93.33%) | 0 (0.00%) |
| `bumpalo 3.20.3` | 17 | 11 (64.71%) | 5 (29.41%) | 1 (5.88%) | 0 (0.00%) |
| `allocator-api2 0.4.0` | 61 | 12 (19.67%) | 18 (29.51%) | 31 (50.82%) | 0 (0.00%) |
| `bitvec 1.1.1` | 54 | 26 (48.15%) | 5 (9.26%) | 23 (42.59%) | 0 (0.00%) |
| `rkyv 0.8.18` | 48 | 11 (22.92%) | 9 (18.75%) | 28 (58.33%) | 0 (0.00%) |
| `slotmap 1.1.1` | 43 | 0 (0.00%) | 4 (9.30%) | 38 (88.37%) | 1 (2.33%) |
| `memchr 2.8.3` | 27 | 0 (0.00%) | 10 (37.04%) | 17 (62.96%) | 0 (0.00%) |
| `smallvec 1.16.2` | 40 | 4 (10.00%) | 0 (0.00%) | 28 (70.00%) | 8 (20.00%) |
| `pyo3 0.29.2` | 33 | 7 (21.21%) | 5 (15.15%) | 21 (63.64%) | 0 (0.00%) |

## UNKNOWN categories and unsupported operations
- None reported
