# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

- Handle entry file redirects (re: [denoland/deno/issues/3082](https://github.com/denoland/deno/issues/3082))
- Rollup cache support for incremental compiles in [denofn/denopack/pull/5](https://github.com/denofn/denopack/pull/5)
- File watch mode (pluginTypescriptCompile is **not** supported) in [denofn/denopack/pull/5](https://github.com/denofn/denopack/pull/5)

### Changed

- Default plugin hook changed from useCompile to useCache in [denofn/denopack/pull/5](https://github.com/denofn/denopack/pull/5)
- Extra CLI options like print, watch and cache are now verbose in [denofn/denopack/pull/5](https://github.com/denofn/denopack/pull/5)

## [0.3.2](https://github.com/denofn/denopack/compare/0.3.0..0.3.2) - 2020-08-08

### Fixed

- Load config from file URI relative to CWD instead of absolute path (this broke stuff on installs from registries)

## [0.3.0](https://github.com/denofn/denopack/compare/0.2.0..0.3.0) - 2020-08-07

### Added

- Source map support in [denofn/denopack/pull/2](https://github.com/denofn/denopack/pull/2)
- Lockfile integrity checking in [denofn/denopack/pull/4](https://github.com/denofn/denopack/pull/4)

### Changed

- Hooks now take one configuration object as parameter where needed in [denofn/denopack/pull/4](https://github.com/denofn/denopack/pull/4)