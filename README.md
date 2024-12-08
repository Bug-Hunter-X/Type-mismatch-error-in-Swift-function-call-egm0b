# Type Mismatch Error in Swift Function Call

This example demonstrates a common error in Swift: passing a value of the wrong type to a function parameter.  The `calculateArea` function expects `Double` values for both `width` and `height`, but the code attempts to pass a String ("20") as the `height`. This will result in a compile-time error, preventing the code from running.

The solution involves ensuring that all arguments passed to the function match the expected types. This often requires explicit type conversions or careful data handling.