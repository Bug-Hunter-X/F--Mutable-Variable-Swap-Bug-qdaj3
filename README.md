# F# Mutable Variable Swap Bug

This example demonstrates a common error when working with mutable variables in F#.  Because mutable variables are passed by reference, modifying them within a function alters the original variables, rather than creating copies. This can lead to unexpected and incorrect results.

The `bug.fs` file contains code illustrating this error.  The `bugSolution.fs` file demonstrates a corrected approach using tuples or a more functional style to achieve the desired swap behavior without the unintended side effects.