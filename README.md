# Janette

A persistant REPL.

You can use janette to have a persistant repl between bash calls.

 * `janette "(def x 1)"` - will execute the code and marshall the state in a `.janette.image` file
 * `janette "(print x)"` - will then print 1 since that is the state.
 * `janette file` - will execute a whole file.

## TODO

If no arguments are given, launch a repl, the trick will be to make sure after every call, the state
is saved.
