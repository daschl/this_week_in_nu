# This week in Nu #16

This week in Nu we continued to refactor the codebase to prepare for the next set of features. We've moved from the old plugin setup to the new subcrates setup for plugins and fixed some issues along the way.

- wycats landed multiple refactorings to move Nu to a multi-crate model, improve how we do syntax coloring, add a new Range primitive, and begin support for the new Signature style ([#1078](https://github.com/nushell/nushell/pull/1078), [#1077](https://github.com/nushell/nushell/pull/1077))
- jonathandturner reorganized what is a core command and what is a plugin, and moved a set of commands to subcrates as plugins ([#1076](https://github.com/nushell/nushell/pull/1076), [#1075](https://github.com/nushell/nushell/pull/1075), [#1073](https://github.com/nushell/nushell/pull/1073), [#1072](https://github.com/nushell/nushell/pull/1072), [#1070](https://github.com/nushell/nushell/pull/1070), [#1069](https://github.com/nushell/nushell/pull/1069), [#1062](https://github.com/nushell/nushell/pull/1062))
- thibran fixed a bunch of clippy warnings ([#1066](https://github.com/nushell/nushell/pull/1066), [#1061](https://github.com/nushell/nushell/pull/1061))
- naufraghi fixed tilde expansion ([#1060](https://github.com/nushell/nushell/pull/1060))
-