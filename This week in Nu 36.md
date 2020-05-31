# This week in Nu #36

- fdncred improved startup times by optimizing plugin loading ([#1689](https://github.com/nushell/nushell/pull/1689))
- jonathandturner fixed some issues with external args ([#1687](https://github.com/nushell/nushell/pull/1687)), remove per-item commands ([#1685](https://github.com/nushell/nushell/pull/1685)), added it-expansion ([#1681](https://github.com/nushell/nushell/pull/1681), [#1669](https://github.com/nushell/nushell/pull/1669), [#1668](https://github.com/nushell/nushell/pull/1668)), added a `drop` command to remove rows from the bottom of a table ([#1663](https://github.com/nushell/nushell/pull/1663)), added a `not-in:` operator ([#1661](https://github.com/nushell/nushell/pull/1661))
- andrasio added new commands for working with tables ([#1686](https://github.com/nushell/nushell/pull/1686)), added a command for checking for emptiness ([#1665](https://github.com/nushell/nushell/pull/1665)), added more functionality to `str` ([#1652](https://github.com/nushell/nushell/pull/1652))
- JosephTLyons and mhmdanas improved our .gitignore ([#1691](https://github.com/nushell/nushell/pull/1691), [#1684](https://github.com/nushell/nushell/pull/1684))
- mhmdanas also cleaned up the operator parsing code ([#1683](https://github.com/nushell/nushell/pull/1683))
- JosephTLyons added showing filesizes for symlinks themselves ([#1680](https://github.com/nushell/nushell/pull/1680))
- quebin31 replaced 'ichwh' for 'which' in a few places to improve auto-cd times ([#1672](https://github.com/nushell/nushell/pull/1672)), fixed cd'ing to symlinked directories ([#1651](https://github.com/nushell/nushell/pull/1651))
- rimathia made `trim` work for all cells rather than just strings ([#1664](https://github.com/nushell/nushell/pull/1664)), made `--help` work in more places ([#1659](https://github.com/nushell/nushell/pull/1659))
- thegedge cleaned up some of the auto-cd logic ([#1660](https://github.com/nushell/nushell/pull/1660))
- aeshirey added a `from-eml` command ([#1656](https://github.com/nushell/nushell/pull/1656))
- siedentop improved docs for `str` ([#1653](https://github.com/nushell/nushell/pull/1653))