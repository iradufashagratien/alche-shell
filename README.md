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
