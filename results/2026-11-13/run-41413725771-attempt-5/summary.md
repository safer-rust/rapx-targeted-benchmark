# RAPx 0.7.73 targeted results

Toolchain: `nightly-2026-11-12`

**Soundness pass rate: 37 / 564 = 6.56%**

| Result | Count | Rate |
|---|---:|---:|
| SOUND | 37 | 6.56% |
| UNSOUND | 25 | 4.43% |
| UNKNOWN | 62 | 10.99% |
| NOT_RUN | 440 | 78.01% |

| UNKNOWN category | Unproved checks |
|---|---:|
| No classified UNKNOWN results | 0 |

| Crate | Targets | SOUND | UNSOUND | UNKNOWN | NOT_RUN |
|---|---:|---:|---:|---:|---:|
| `openssl 0.10.81` | 166 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 166 (100.00%) |
| `heapless 0.9.3` | 75 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 75 (100.00%) |
| `bumpalo 3.20.3` | 17 | 12 (70.59%) | 5 (29.41%) | 0 (0.00%) | 0 (0.00%) |
| `allocator-api2 0.4.0` | 61 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 61 (100.00%) |
| `bitvec 1.1.1` | 54 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 54 (100.00%) |
| `rkyv 0.8.18` | 48 | 11 (22.92%) | 9 (18.75%) | 28 (58.33%) | 0 (0.00%) |
| `slotmap 1.1.1` | 43 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 43 (100.00%) |
| `memchr 2.8.3` | 27 | 9 (33.33%) | 10 (37.04%) | 8 (29.63%) | 0 (0.00%) |
| `smallvec 1.16.2` | 40 | 5 (12.50%) | 1 (2.50%) | 26 (65.00%) | 8 (20.00%) |
| `pyo3 0.29.2` | 33 | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 33 (100.00%) |

## UNKNOWN categories and unsupported operations
- None reported
