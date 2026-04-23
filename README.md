# Binary-Derived CHC Problems

This repository contains bit-vector CHC problems derived from AArch64 Linux binaries for (slightly adapted versions of) the benchmarks from [LinearArbitrary-SeaHorn](https://github.com/GaloisInc/LinearArbitrary-SeaHorn).
The CHC problems are the unformatted/unsimplified benchmarks from the paper "Bit-Vector CHC Solving for Binary Analysis and Binary Analysis for Bit-Vector CHC Solving" by Aaron Bembenek and Toby Murray, presented at the NASA Formal Methods Symposium (NFM 2026).

The file [expected_results.csv](expected_results.csv) contains what result we expect for each benchmark, based on what the solvers found in our experiments (we treat the result for a benchmark as "unknown" if the solvers were inconsistent on that benchmark).
The ground truth result for each benchmark is not known.