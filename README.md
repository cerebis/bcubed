# bcubed and weighted bcubed external validation indices

This tool calculates bcubed or weighted bcubed, returning a set of relevant values in CSV format.

Effort has been made to reduce the computation time for large problems, although much more could probably be done.

When compared to other codebases, this implementation is much faster (possibly orders of magnitude).

## Limitations:

- The implementation was original part of another work, as such, the input formats are not as generic as they could be.
- Parallelism is achieved only for mulitple independent calculations.
