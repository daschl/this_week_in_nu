# This week in Nu #30

Some long-awaited features have landed!

- quebin31 improved how we canonicalize paths inside of Nu (#1485)
- jonathandturner added `to-html` (#1487), `to-md` for markdown output (#1503), automatically change directory when you give a path by itself (#1496, #1506), changing drives in Windows + remembering the previous directory (#1500), and added a `--full` mode to `ps` (#1507)
- jonathandturner also started work on a jupyter notebook kernel for Nu ([https://github.com/nushell/nu_jupyter](https://github.com/nushell/nu_jupyter))
- Sosthene-Guedon improved errors when opening CSV files (#1490, #1492) as well as more generally using `open` (#1495)
- andrasio began to add support for inferring types in unstructured data (#1494), moved the `sum` plugin to an internal command (#1501)
- pulpdrew added docs for `skip` and `skip-while` (#1499)