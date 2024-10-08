<!--
  Copyright (c) 2024 Michael Federczuk
  SPDX-License-Identifier: CC-BY-SA-4.0
-->

<!-- markdownlint-disable no-duplicate-heading -->

# Changelog #

All notable changes to this project will be documented in this file.
The format is based on [**Keep a Changelog v1.0.0**](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [**Semantic Versioning v2.0.0**](https://semver.org/spec/v2.0.0.html).

## [v0.2.0] - 2024-10-04 ##

[v0.2.0]: https://github.com/mfederczuk/git-wip-dump/releases/tag/v0.2.0

### Added ###

* The commit message is now customizable using the Git config `wip-dump.message`
* The commit hooks (`pre-commit` and `commit-msg`) can now be enabled using
  the Git config `wip-dump.commit-hooks-enabled`

### Changed ###

* The `--help` and `--version` options now write to `stdout` instead of `stderr`

## [v0.1.0] - 2022-07-26 ##

[v0.1.0]: https://github.com/mfederczuk/git-wip-dump/releases/tag/v0.1.0

Initial Release
