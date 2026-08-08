# alche-shell

Shell scripting basics: aliases, environment/local variables, `$PATH`,
shell arithmetic, and base conversions. All scripts are Bash, exactly
two lines long, Ubuntu 20.04-compatible, and avoid `&&`, `||`, `;`,
`bc`, `sed`, and `awk` per project constraints.

## init_files_variables_and_expansions

| File | Description |
|---|---|
| `0-alias` | Creates an alias `ls` whose value is `rm *`. |
| `1-hello_you` | Prints `hello $USER`. |
| `2-path` | Appends `/action` to the end of `$PATH` (must be `source`d). |
| `3-paths` | Counts the number of directories currently in `$PATH`. |
| `4-global_variables` | Lists all environment (global) variables via `env`. |
| `5-local_variables` | Lists all variables and functions via `set`. |
| `6-create_local_variable` | Creates a local variable `BEST=School`. |
| `7-create_global_variable` | Creates a global (exported) variable `BEST=School`. |
| `8-true_knowledge` | Prints `128 + $TRUEKNOWLEDGE`. |
| `9-divide_and_rule` | Prints `$POWER / $DIVIDE` (integer division). |
| `10-love_exponent_breath` | Prints `$BREATH ** $LOVE`. |
| `11-binary_to_decimal` | Converts `$BINARY` (base 2) to base 10. |
| `12-combinations` | Prints every two-letter combo `aa`-`zz` except `oo`. |
| `13-print_float` | Prints `$NUM` to two decimal places. |
| `14-decimal_to_hexadecimal` | Converts `$DECIMAL` (base 10) to base 16. |
| `15-rot13` | Applies ROT13 to stdin via `tr`. |
| `16-odd` | Prints every other line of stdin, starting with the first. |
| `17-water_and_stir` | Converts `$WATER` (base "water") and `$STIR` (base "stir") to decimal, sums them, prints in base "bestchol". |

## loops_conditions_and_parsing

| File | Description |
|---|---|
| `1-for_best_school` | Displays "Best School" 10 times using a `for` loop. |
| `2-while_best_school` | Displays "Best School" 10 times using a `while` loop. |
| `3-until_best_school` | Displays "Best School" 10 times using an `until` loop. |
| `4-if_9_say_hi` | Displays "Best School" 10 times, printing "Hi" after the 9th. |
| `5-4_bad_luck_8_is_your_chance` | Loops 1-10, printing "bad luck" on 4, "good luck" on 8, else "Best School". |
| `6-superstitious_numbers` | Loops 1-20, using `case` to print superstition messages on 4, 9, 17. |
| `7-clock` | Displays hours 0-12 and minutes 1-59 using nested `while` loops. |
| `8-for_ls` | Lists current directory contents, showing only the part after the first dash. |
| `9-to_file_or_not_to_file` | Reports whether a file named `school` exists, is empty, and is a regular file. |
| `10-fizzbuzz` | Classic FizzBuzz from 1 to 100. |
| `11-read_and_cut` | Displays username, UID, and home directory from `/etc/passwd`. |
| `12-tell_the_story_of_passwd` | Narrates each `/etc/passwd` entry as a sentence. |
| `13-lets_parse_apache_logs` | Uses `awk` to extract IP and HTTP status code from an Apache log. |
| `14-dig_the-data` | Groups Apache log entries by IP/status code and counts occurrences. |
