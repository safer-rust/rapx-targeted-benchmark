# RAPx 0.7.68 targeted results

Toolchain: `nightly-2026-11-01`

**Soundness pass rate: 59 / 564 = 10.46%**

| Result | Count | Rate |
|---|---:|---:|
| SOUND | 59 | 10.46% |
| UNSOUND | 18 | 3.19% |
| UNKNOWN | 251 | 44.50% |
| NOT_RUN | 236 | 41.84% |

| UNKNOWN category | Unproved checks |
|---|---:|
| No classified UNKNOWN results | 0 |

| Crate | Targets | SOUND | UNSOUND | UNKNOWN | NOT_RUN |
|---|---:|---:|---:|---:|---:|
| `openssl 0.10.81` | 166 | 8 (4.82%) | 1 (0.60%) | 157 (94.58%) | 0 (0.00%) |
| `heapless 0.9.3` | 75 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 75 (100.00%) |
| `bumpalo 3.20.3` | 17 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 17 (100.00%) |
| `allocator-api2 0.4.0` | 61 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 61 (100.00%) |
| `bitvec 1.1.1` | 54 | 24 (44.44%) | 0 (0.00%) | 30 (55.56%) | 0 (0.00%) |
| `rkyv 0.8.18` | 48 | 11 (22.92%) | 5 (10.42%) | 32 (66.67%) | 0 (0.00%) |
| `slotmap 1.1.1` | 43 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 43 (100.00%) |
| `memchr 2.8.3` | 27 | 9 (33.33%) | 10 (37.04%) | 8 (29.63%) | 0 (0.00%) |
| `smallvec 1.16.2` | 40 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 40 (100.00%) |
| `pyo3 0.29.2` | 33 | 7 (21.21%) | 2 (6.06%) | 24 (72.73%) | 0 (0.00%) |

## UNKNOWN categories and unsupported operations
- None reported
