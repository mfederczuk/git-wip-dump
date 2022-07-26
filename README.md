<!--
  Copyright (c) 2022 Michael Federczuk
  SPDX-License-Identifier: CC-BY-SA-4.0
-->

# git-wip-dump #

[version_shield]: https://img.shields.io/badge/version-0.1.0-informational.svg
[release_page]: https://github.com/mfederczuk/git-wip-dump/releases/tag/v0.1.0 "Release v0.1.0"
[![version: 0.1.0][version_shield]][release_page]
[![Changelog](https://img.shields.io/badge/-Changelog-informational.svg)](CHANGELOG.md "Changelog")

## About ##

`git-wip-dump` is a custom Git command to temporarily save uncommitted work into a commit and restore it afterwards.

## Usage ##

Current the command only has two subcommands: `save`, which will create a WIP commit, and `restore`, which will reset
the WIP commit again.

With `save`, the option `--push` can also be given to also push the commit to the tracked upstream branch.

## Download & Installation ##

Simply download the [`git-wip-dump`](git-wip-dump) file and place it into a directory that is inside your `PATH`
environment variable.

## Contributing ##

Read through the [Contribution Guidelines](CONTRIBUTING.md) if you want to contribute to this project.

## License ##

**git-wip-dump** is licensed under both the [**Mozilla Public License 2.0**](LICENSES/MPL-2.0.txt) AND the
[**Apache License 2.0**](LICENSES/Apache-2.0.txt).  
For more information about copying and licensing, see the [`COPYING.txt`](COPYING.txt) file.
