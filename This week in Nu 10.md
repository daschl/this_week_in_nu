# This week in Nu #10

Lots of new commands this week, some updates in how we handle paths and column paths, better debugging capabilities, improved command help, more work towards getting Nu ready to be a login shell, and more documentation.

- We're currently running a [short survey about Nu](https://t.co/nujSjnI0dr?amp=1). Even if you aren't a Nu user, we'd love to hear from you!
- wycats added better tracing for debugging the parser ([#892](https://github.com/nushell/nushell/pull/892))
- notryanb updated `fetch` to be able to load URLs from strings and $it ([#886](https://github.com/nushell/nushell/pull/886))
- jonathandturner added updates to always save history ([#881](https://github.com/nushell/nushell/pull/881)); added parameter descriptions to command help ([#882](https://github.com/nushell/nushell/pull/882)); added new builtin variables `$nu:config`, `$nu:env`, and `$nu:path`([#883](https://github.com/nushell/nushell/pull/883), [#884](https://github.com/nushell/nushell/pull/884)); added support for reading the PATH from config ([#885](https://github.com/nushell/nushell/pull/885)), added a new `read` command for easier text handling ([#889](https://github.com/nushell/nushell/pull/889)), and added `prepend` and `append` for adding rows to tables ([#890](https://github.com/nushell/nushell/pull/890))
- andrasio added more support for working with ~ in paths across platforms ([#879](https://github.com/nushell/nushell/pull/879)) as well as added initial support for row numbers in column paths ([#892](https://github.com/nushell/nushell/pull/892), [#898](https://github.com/nushell/nushell/pull/898))
- andrasio also worked on better separation between the parser and other subsystems ([#874](https://github.com/nushell/nushell/pull/874))
- oknozor and loksonarius added more documentation for commands ([#871](https://github.com/nushell/nushell/pull/871), [#873](https://github.com/nushell/nushell/pull/873), [#899](https://github.com/nushell/nushell/pull/899))