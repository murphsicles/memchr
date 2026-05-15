# @std/memchr — SIMD-Accelerated Byte Search for Zeta

Auto-converted from [memchr](https://crates.io/crates/memchr) v2.8.0 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **memchr** — find first occurrence of a byte in memory (SIMD on x86_64, aarch64)
- **memrchr** — find last occurrence of a byte
- **memmem** — find first occurrence of a substring (Two-Way algorithm + SIMD)
- **find** — iterator over all occurrences
- **rfind** — reverse iterator over all occurrences

## Performance
Uses SIMD (SSE2, AVX2 on x86_64; NEON on aarch64) for sub-linear byte search performance. Typically 5-10x faster than naive byte-at-a-time scanning.

## Stats: ~6,173 lines, 0 unsupported items

## License: MIT