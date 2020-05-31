# This week in Nu #25

Don't read this list if want a surprise for next week's release 

- thegedge and jonathandturner added support for running scripts (#1368, #1386)
- Amanita-muscaria added support for shorthand flags, letting you type `ls -f` instead of `ls --full`, for example (#1384)
- Amanita-muscaria also added support for parsing datetime strings (#1381)
- andrasio fixed Nu to warn if a command is given an incorrect flag (#1383)
- andrasio also added support for using the `$nu` variable when calling external commands (#1379), allowing flags anywhere in command (#1375), ensures the full set of stable plugins is installed with `--features=stable`(#1373)
- coolshaurya added a new error when running `calc` on divide by zero (#1376)
- notryanb added more code documentation (#1366)
- jonathandturner added support for running commands from outside nu with `-c`(#1361, #1367)
- thegedge fixed a major performance issue with running external commands (#1358)
- UltraWelfare fixed an issue where `mv` was given an incorrect path (#1351)