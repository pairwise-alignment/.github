# Pairwise Alignment Benchmarks

This organisation hosts a number of repositories related to benchmarking
global pairwise aligners.

Feel free to reach out to get involved!

Repositories (planned to be) hosted here:

- Rust library with core types.
- Consistent Rust bindings for popular pairwise aligners.
- A _runner_ crate that provides a single API and CLI to all wrapped aligners
  that measures time and memory usage.
- A create to generate semi-random sequence pairs to test aligners on.
- An _orchestrator_ crate that creates _jobs_ (benchmark tasks) and calls the
  runner for each of them.
- A thorough benchmark of existing aligners analysing:
  - random and real data,
  - sequence length from 100 to 1M,
  - error rate from 0.1% to 20%,
  - unit, linear, and (double) affine cost models.

Note:
library names start with `pa-` so that we can publish them to crates.io under the same name.
