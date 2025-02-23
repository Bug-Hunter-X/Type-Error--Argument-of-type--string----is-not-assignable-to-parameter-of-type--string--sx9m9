# Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'
This bug demonstrates a common type error in TypeScript where an array of strings is passed to a function expecting a single string.  The solution involves modifying the function signature or the way the array is handled.

## Bug
The `greeter` function expects a single string as input, but an array of strings is passed. This results in a type error.

## Solution
The solution involves changing the function signature to accept an array of strings or modifying how the input is processed.