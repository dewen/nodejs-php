# [Arguments](arguments.md)

features | php | nodejs
--- | --- | ---
*Argument* | `$argv` | `process.argv`
Get options | `getopt()` | ???
Output | `echo` | `process.stdout.write`
User Input | `fgets(STDIN);` | `process.stdin.on('data', function(data){ ... })`
