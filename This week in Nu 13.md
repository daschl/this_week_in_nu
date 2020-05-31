# This week in Nu #13

Lucky #13! Welcome to our 13th edition of "This Week in Nu". 

- We've just begun to create new websites. You can see the early versions live at [www.nushell.sh](http://www.nushell.sh) and [blog.nushell.sh](http://blog.nushell.sh). If you'd like to help or share your feedback, we'd love to have it! Big thanks to sebastian-xyz for kicking this off!
- wycats landed a rewrite of how column-paths work, improved debugging, and added a new `what?` command to help with debugging commands from inside of Nu ([#986](https://github.com/nushell/nushell/pull/986))
- drmason13 has been cleaning up some of our csv/tsv handling logic ([#990](https://github.com/nushell/nushell/pull/990))
- jonathandturner added smaller `ls` and a new `ls --full` option. As part of this umasks for unix-based were also added ([#979](https://github.com/nushell/nushell/pull/979), [#988](https://github.com/nushell/nushell/pull/988))
- jonathandturner (building on the work of Southclaws) added support for the [starship.rs](http://starship.rs) prompt 🚀 ([#804](https://github.com/nushell/nushell/pull/804), [#970](https://github.com/nushell/nushell/pull/970))
- jonathandturner also added support for durations and comparisons with durations ([#978](https://github.com/nushell/nushell/pull/978)) and initial support for loading Excel files ([#977](https://github.com/nushell/nushell/pull/977))
- Aloso improved how durations were formatted ([#982](https://github.com/nushell/nushell/pull/982))
- For folks waiting for homebrew, it's now up to date again! [https://formulae.brew.sh/formula/nushell](https://formulae.brew.sh/formula/nushell)