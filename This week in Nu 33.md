# This week in Nu #33

New parser changes to prepare for aliases, better path shorthands, slighty better compile times, and more

- quebin31 added support for using multiple dots to mean changing multiple directories (eg `...` now means going back two directories), which is a common shorthand in some shells (#1547)
- thegedge fixed an issue with deleting symlinks (#1550)
- jonathandturner updated core parser logic to prepare for adding aliases (#1554)
- jonathandturner also updated a lot of dependencies and removed dead code, trimming the compile time from 3m48s to 3m 29s (#1560, #1562, #1563, #1567)
- Bonus: Nu got a mention in both [https://cppcast.com/](https://cppcast.com/) and [https://linuxunplugged.com/](https://linuxunplugged.com/) this week