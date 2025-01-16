# Kotlin MutableList removeIf Unexpected Behavior

This repository demonstrates an uncommon bug in Kotlin involving the use of `removeIf` on a `MutableList`.  The issue arises from modifying the list during iteration, which can cause elements to be skipped or produce incorrect results.

The `bug.kt` file contains the problematic code, while `bugSolution.kt` provides a corrected approach.

This example highlights the importance of understanding the side effects of list modification functions when used iteratively.

## Reproducing the Bug

1. Clone this repository.
2. Run the `bug.kt` file.
3. Observe that the output is not what might be initially expected.