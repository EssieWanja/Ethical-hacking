The meaning of each line of is as follows:

   Line 2 is a comment line that begins with a hash tag #. Lines starting with # are used to document the script. Comment lines are ignored by the command interpreter.
    Line 3 starts a test to determine if the input option variable $1 exists. By default, Bash scripts accept command line options into variables numbered by their position in the command. The -z returns "true" if the value of $1 is null. Bash requires a space after the first bracket [ and a space before the last bracket ].
    Line 4 indicates what to do if the option variable does not exist (is null). Lines 5 and 6 are indented to indicate that they are part of the then clause.
    Line 5 prints a message to the screen. Bash uses the echo command to print what is in the double quotes to the screen.
    Line 6 will cause the script execution to stop and exit to the CLI if the condition is met.
    Line 7 indicates what to do if the if condition is false.
    Line 8 prints a message with the input value that was supplied and stored in the $1 variable. Note that further work is required to validate that the input was actually a valid IP address. This is beyond the scope of this lab.
    Line 9 indicates that the if/then clauses are complete.
