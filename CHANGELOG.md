# Common Lisp Action

## 1.0.1 (2025-02-03)

#### Changed

- The cache is now keyed on the chosen compiler as well. This allows separate,
  per-compiler caches to be saved when the user has specified multiple jobs via
  a matrix.

## 1.0.0 (2025-01-25)

#### Added

- Compiler installation.
- Vend installation.
- Dependency fetching.
- Simple caching of FASL files.
