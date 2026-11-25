# RAPx 0.7.81 targeted results

Toolchain: `nightly-2026-11-24`

**Soundness pass rate: 94 / 564 = 16.67%**

| Result | Count | Rate |
|---|---:|---:|
| SOUND | 94 | 16.67% |
| UNSOUND | 100 | 17.73% |
| UNKNOWN | 360 | 63.83% |
| NOT_RUN | 10 | 1.77% |

| UNKNOWN category | Unproved checks |
|---|---:|
| No classified UNKNOWN results | 0 |

| Crate | Targets | SOUND | UNSOUND | UNKNOWN | NOT_RUN |
|---|---:|---:|---:|---:|---:|
| `openssl 0.10.81` | 166 | 5 (3.01%) | 1 (0.60%) | 160 (96.39%) | 0 (0.00%) |
| `heapless 0.9.3` | 75 | 8 (10.67%) | 34 (45.33%) | 32 (42.67%) | 1 (1.33%) |
| `bumpalo 3.20.3` | 17 | 11 (64.71%) | 5 (29.41%) | 1 (5.88%) | 0 (0.00%) |
| `allocator-api2 0.4.0` | 61 | 17 (27.87%) | 22 (36.07%) | 22 (36.07%) | 0 (0.00%) |
| `bitvec 1.1.1` | 54 | 28 (51.85%) | 5 (9.26%) | 21 (38.89%) | 0 (0.00%) |
| `rkyv 0.8.18` | 48 | 13 (27.08%) | 13 (27.08%) | 22 (45.83%) | 0 (0.00%) |
| `slotmap 1.1.1` | 43 | 0 (0.00%) | 4 (9.30%) | 38 (88.37%) | 1 (2.33%) |
| `memchr 2.8.3` | 27 | 0 (0.00%) | 10 (37.04%) | 17 (62.96%) | 0 (0.00%) |
| `smallvec 1.16.2` | 40 | 5 (12.50%) | 1 (2.50%) | 26 (65.00%) | 8 (20.00%) |
| `pyo3 0.29.2` | 33 | 7 (21.21%) | 5 (15.15%) | 21 (63.64%) | 0 (0.00%) |

## UNKNOWN categories and unsupported operations
- None reported
