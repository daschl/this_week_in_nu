# This week in Nu #15

Major internals work this week as multiple refactorings land.

- sebastian-xyz added the new `range` command ([#1045](https://github.com/nushell/nushell/pull/1045))
- thegedge simplified the pipeline execution code ([#1039](https://github.com/nushell/nushell/pull/1039))
- wycats begun the process of reorganizing the codebase to use subcrates for better code modularity ([#1046](https://github.com/nushell/nushell/pull/1046), [#1044](https://github.com/nushell/nushell/pull/1044))
- jonathandturner continued extracting plugins into subcrates and organizing commands/plugins for maximal portability ([#1058](https://github.com/nushell/nushell/pull/1058), [#1055](https://github.com/nushell/nushell/pull/1055), [#1054](https://github.com/nushell/nushell/pull/1054), [#1052](https://github.com/nushell/nushell/pull/1052))
- jonathandturner also added a new type to represent a string with a carriage return, fixing an issue when stream large amounts of text ([#1047](https://github.com/nushell/nushell/pull/1047))
- jonathandturner shipped the 0.6.1 release with a fix for the starship prompt ([#1035](https://github.com/nushell/nushell/pull/1035), [#1029](https://github.com/nushell/nushell/pull/1029))
- andrasio updated `embed` to more naturally embed a single column ([#1049](https://github.com/nushell/nushell/pull/1049))
- tchak and sebastian-xyz added more command documentation ([#1041](https://github.com/nushell/nushell/pull/1041), [#1032](https://github.com/nushell/nushell/pull/1032))