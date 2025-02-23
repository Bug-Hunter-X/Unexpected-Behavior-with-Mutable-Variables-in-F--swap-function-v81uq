# F# Mutable Variable Swap Bug

This example demonstrates a common misconception when working with mutable variables in F#.  The `swap` function intends to exchange the values of `x` and `y`, but due to the pass-by-reference nature of mutable variables, the original variables are directly modified. This leads to unexpected results.

The solution shows how to correctly swap the values using a tuple or by returning new values.