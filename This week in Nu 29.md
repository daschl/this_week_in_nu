# This week in Nu #29

Released 0.11.0!

- quebin31 added `--all` flag to `ls` to show hidden files (#1483)
- waldyrious and kloun made a lot of cleanups to command documentation (#1481, #1477)
- neuronull changed `sys | get host.users` to `sys | get host.sessions` to make it more obvious it lists user sessions (#1480)
- andrasio fixed the directory permissions check for `cd` (#1476), converted `shuffle` from a plugin to an internal command (#1475), and added column-path support to `format` (#1472)
- jonathandturner released 0.11.0 (#1474), and merged `env` into `$nu` (#1463)
- thegedge fixed some upcoming compiler warnings (#1468), switched autoview to not add a newline (#1466)
- lincis fixed named pipe support in `ls` (#1461)
- JCavallo added autodetection logic in `save` to handle both binary and text (#1459)
- rabisg0 fixed the flag handler to allow `-h` in more places (#1454)