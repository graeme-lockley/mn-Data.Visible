
The Visible interface allows values to be converted into a human-readable String representation.

While not required, it is recommended that for any expression `x`, the string `x.show()` be executable JavaScript
code which evaluates to the same value as the expression `x`.

```haskell
interface Show a where
    show :: a -> String
```
This interface offers no default implementations.

