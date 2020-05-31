# This week in Nu #3

Lots of stability improvements this week with better support for parsing, external commands, and more.

- vsoch continues pushing Docker support forward, and added support for Ubuntu 18.04 ([#663](https://github.com/nushell/nushell/pull/663))
- androbtech removed our dependency on regex, as part of the effort to improve build times ([#651](https://github.com/nushell/nushell/pull/651))
- max-sixty landed a CI guard to ensure the codebase was properly formatted ([#649](https://github.com/nushell/nushell/pull/649))
- wycats landed an improved parser that is both more stable and handles external commands better ([#632](https://github.com/nushell/nushell/pull/632))
- chhetripradeep added a `pwd` command ([#612](https://github.com/nushell/nushell/pull/612))
- tim77 added instructions for Fedora ([#607](https://github.com/nushell/nushell/pull/607))
- Lots of bugfixes by est31, tim77, pmeredit, vsoch, lesichkovm. Big thanks to bug reporters jeka, stephanemagnenat, twe4ked, rrichardson, bmurphy1976, joedborg, and lienke.
- Fix for long-standing issue where externals freeze when outputting large amounts of output ([#664](https://github.com/nushell/nushell/pull/664))
- Added support for "did you mean?"-style errors when a column is mistyped. ([#662](https://github.com/nushell/nushell/pull/662))
- Added a lighter-weight table output format ([#631](https://github.com/nushell/nushell/pull/631))
- More plugins were made optional to help with build times. To get the full behavior be sure to build with `--all-features`([#617](https://github.com/nushell/nushell/pull/617))
- Improved help system was added. Type `help` to get started ([#657](https://github.com/nushell/nushell/pull/657))
- Updates by ymgyt, androbtech, and pka to the [Nu book](https://book.nushell.sh/)
- Updates to the [Contributor Handbook](https://github.com/nushell/contributor-handbook), a guide for developers working on Nu