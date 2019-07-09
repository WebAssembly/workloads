# WebAssembly Workloads

**This project never materialized and ongoing benchmark/measurement work has moved
to the [benchmark](https://github.com/WebAssembly/benchmarks) repo.**

This repo contains a collection of snapshots of WebAssembly workloads
served at [webassembly.github.io/workloads](https://webassembly.github.io/workloads).

The goals of the repo are:
* to provide a common place to share workloads between developers of
  WebAssembly applications, engines and toolchains
* to provide meaningful measurements of realistic paths through realistic
  codebases (i.e., not collect synthetic benchmarks) that are dominated by
  WebAssembly performance (i.e., not APIs like WebGL)
* to contain builds that can both be run locally and served via
  GitHub Pages (at least until a common non-Web embedding emerges)
* to stay up-to-date with the latest recommended best practices and toolchain
  developments (archiving snapshots of older builds)
* to include sources whenever possible so that workloads can be rebuilt in order
  to test toolchains and keep builds up-to-date

## Contributing

Do you have a workload that meets the goals above? We'd love to share it! Please
feel free to create a PR against this repo.

The workload should contain a LICENSE in the root directory that is sufficiently
permissive as to allow:
* copying the workload into various engine or toolchain test harnesses
* hosting the workload via this and other GitHub Pages

If sources are provided, they should include build instructions and the LICENSE
should permit modification of the workload for measurement and experimental
purposes.
