# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1](https://github.com/alloy-rs/chains/releases/tag/v0.1.1) - 2023-11-14

### Added

- More implementations and delegated methods to `Chain` ([#6])

[#6]: https://github.com/alloy-rs/chains/pull/6

## [0.1.0](https://github.com/alloy-rs/chains/releases/tag/v0.1.0) - 2023-11-14

### Added

- Initial release, forked from [`ethers_core::types::Chain`](https://github.com/gakonst/ethers-rs/blob/f97bb1db0e34727d7d74549bba5f6e246d760c13/ethers-core/src/types/chain.rs#L55) ([#2]) as `NamedChain` ([#3]), and [`reth_primitives::Chain`](https://github.com/paradigmxyz/reth/blob/8ecd90b884d1ae9cf9119a743b658a4a6dd110c1/crates/primitives/src/chain/mod.rs#L97) ([#4])

### Changed

- split Chain into a struct and ChainKind enum ([#5])

[#2]: https://github.com/alloy-rs/chains/pull/2
[#3]: https://github.com/alloy-rs/chains/pull/3
[#4]: https://github.com/alloy-rs/chains/pull/4
[#5]: https://github.com/alloy-rs/chains/pull/5