# RAPx 0.7.71 targeted results

Toolchain: `nightly-2026-11-02`

**Soundness pass rate: 106 / 564 = 18.79%**

| Result | Count | Rate |
|---|---:|---:|
| SOUND | 106 | 18.79% |
| UNSOUND | 60 | 10.64% |
| UNKNOWN | 390 | 69.15% |
| NOT_RUN | 8 | 1.42% |

| UNKNOWN category | Unproved checks |
|---|---:|
| No classified UNKNOWN results | 0 |

| Crate | Targets | SOUND | UNSOUND | UNKNOWN | NOT_RUN |
|---|---:|---:|---:|---:|---:|
| `openssl 0.10.81` | 166 | 5 (3.01%) | 1 (0.60%) | 160 (96.39%) | 0 (0.00%) |
| `heapless 0.9.3` | 75 | 6 (8.00%) | 1 (1.33%) | 68 (90.67%) | 0 (0.00%) |
| `bumpalo 3.20.3` | 17 | 12 (70.59%) | 5 (29.41%) | 0 (0.00%) | 0 (0.00%) |
| `allocator-api2 0.4.0` | 61 | 17 (27.87%) | 17 (27.87%) | 27 (44.26%) | 0 (0.00%) |
| `bitvec 1.1.1` | 54 | 30 (55.56%) | 5 (9.26%) | 19 (35.19%) | 0 (0.00%) |
| `rkyv 0.8.18` | 48 | 14 (29.17%) | 9 (18.75%) | 25 (52.08%) | 0 (0.00%) |
| `slotmap 1.1.1` | 43 | 1 (2.33%) | 9 (20.93%) | 33 (76.74%) | 0 (0.00%) |
| `memchr 2.8.3` | 27 | 9 (33.33%) | 10 (37.04%) | 8 (29.63%) | 0 (0.00%) |
| `smallvec 1.16.2` | 40 | 5 (12.50%) | 1 (2.50%) | 26 (65.00%) | 8 (20.00%) |
| `pyo3 0.29.2` | 33 | 7 (21.21%) | 2 (6.06%) | 24 (72.73%) | 0 (0.00%) |

## UNKNOWN categories and unsupported operations
- None reported
