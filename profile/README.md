# Pairwise Alignment Benchmarks

This organisation hosts a number of repositories related to benchmarking
global pairwise aligners.

Feel free to reach out to get involved!

Repositories (planned to be) hosted here:

- `pa-types`: Rust library with core types.
- `pa-generate`: A crate to generate semi-random sequence pairs to test aligners on.
- Consistent Rust bindings for popular pairwise aligners.
- `pa-bench`: binaries to benchmark pairwise aligners.
- A thorough benchmark of existing aligners analysing:
  - random and real data,
  - sequence length from 100 to 1M,
  - error rate from 0.1% to 20%,
  - unit, linear, and (double) affine cost models.

Note:
library names start with `pa-` so that we can publish them to crates.io under the same name.
