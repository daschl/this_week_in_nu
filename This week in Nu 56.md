# This week in Nu #56

* LhKipp posted a [new RFC](https://github.com/nushell/rfcs/blob/f0f9e384e0307d4039631fb1ef5fbb420301a9c3/text/0004-type-deduction.md) about extending our type inference logic and how we might extend the logic for working with aliases.
* notryanb updated the [git parsing examples in the cookbook](https://github.com/nushell/cookbook/pull/17)
* gorogoroumaru extended [`math avg` to work with durations](https://github.com/nushell/nushell/pull/2529)
* andrasio extended the [folding logic to work with tables](https://github.com/nushell/nushell/pull/2538), improved [plugin loading and testing](https://github.com/nushell/nushell/pull/2544), cleaned up [configuration reading](https://github.com/nushell/nushell/pull/2559)
* gillespiecd switched [active shell to be displayed as a boolean](https://github.com/nushell/nushell/pull/2540), did some [code cleanup around booleans](https://github.com/nushell/nushell/pull/2543), [removed `trim` in favor of `str trim`](https://github.com/nushell/nushell/pull/2560), [cleaned up the help text](https://github.com/nushell/nushell/pull/2566)
* radekvit added [non-inclusive ranges](https://github.com/nushell/nushell/pull/2541), made [ctrl-c work during sleep](https://github.com/nushell/nushell/pull/2550), cleaned up [logic for `get` and `nu-value-ext`](https://github.com/nushell/nushell/pull/2563)
* jonathandturner fixed a [yanked crossterm version](https://github.com/nushell/nushell/pull/2542)
* fdncred and jonathandturner updated the [rustyline version](https://github.com/nushell/nushell/pull/2565), fixing some instability during line editing
* lidin fixed [rawkey for ARM](https://github.com/nushell/nushell/pull/2547)
* fdncred fixed a [ctrl-c issue](https://github.com/nushell/nushell/pull/2548), added a few more [ansi escape sequences](https://github.com/nushell/nushell/pull/2553), added [replace all to `str find-replace`](https://github.com/nushell/nushell/pull/2569)
* thegedge refactored [the completion trait](https://github.com/nushell/nushell/pull/2555)
* rezural added [case-sensitive/case-insensitive completion matching](https://github.com/nushell/nushell/pull/2556)
