# RAPx 0.7.78 targeted results

Toolchain: `nightly-2026-11-20`

**Soundness pass rate: 96 / 564 = 17.02%**

| Result | Count | Rate |
|---|---:|---:|
| SOUND | 96 | 17.02% |
| UNSOUND | 59 | 10.46% |
| UNKNOWN | 401 | 71.10% |
| NOT_RUN | 8 | 1.42% |

| UNKNOWN category | Unproved checks |
|---|---:|
| No classified UNKNOWN results | 0 |

| Crate | Targets | SOUND | UNSOUND | UNKNOWN | NOT_RUN |
|---|---:|---:|---:|---:|---:|
| `openssl 0.10.81` | 166 | 5 (3.01%) | 1 (0.60%) | 160 (96.39%) | 0 (0.00%) |
| `heapless 0.9.3` | 75 | 6 (8.00%) | 2 (2.67%) | 67 (89.33%) | 0 (0.00%) |
| `bumpalo 3.20.3` | 17 | 12 (70.59%) | 5 (29.41%) | 0 (0.00%) | 0 (0.00%) |
| `allocator-api2 0.4.0` | 61 | 15 (24.59%) | 18 (29.51%) | 28 (45.90%) | 0 (0.00%) |
| `bitvec 1.1.1` | 54 | 29 (53.70%) | 5 (9.26%) | 20 (37.04%) | 0 (0.00%) |
| `rkyv 0.8.18` | 48 | 11 (22.92%) | 9 (18.75%) | 28 (58.33%) | 0 (0.00%) |
| `slotmap 1.1.1` | 43 | 0 (0.00%) | 4 (9.30%) | 39 (90.70%) | 0 (0.00%) |
| `memchr 2.8.3` | 27 | 7 (25.93%) | 10 (37.04%) | 10 (37.04%) | 0 (0.00%) |
| `smallvec 1.16.2` | 40 | 4 (10.00%) | 0 (0.00%) | 28 (70.00%) | 8 (20.00%) |
| `pyo3 0.29.2` | 33 | 7 (21.21%) | 5 (15.15%) | 21 (63.64%) | 0 (0.00%) |

## UNKNOWN categories and unsupported operations
- None reported
