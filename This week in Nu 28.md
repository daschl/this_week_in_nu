# This week in Nu #28

- Bocom updated `ls` to now continue listing files even if a file couldn't be fully listed (#1435)
- coolshaurya added docs for `debug` (#1438)
- thegedge further improved stdin/stdout streaming to allow for infinite streams (#1440)
- notryanb added support for unknown MIME types when downloading (#1441)
- hirschenberger added a `shuffle` command to shuffle the order of rows (#1443, #1455)
- thegedge and andrasio refactored the codebase to move CLI work into its own crate (#1445, #1450, #1451)
- andrasio added the `rename` command to allow columns to be renamed (#1447)
- quebin31 fixed `cd` to correctly error on directory execute permissions in Unix (#1452)
- andrasio fixed some issues with the line editor coloring (#1453)
- jonathandturner added a new internal codec for handling external→internal that works with both binary and text data (#1457)