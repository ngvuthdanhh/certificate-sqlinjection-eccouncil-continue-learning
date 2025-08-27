# Classic SQL Injection (In-band)

## Union-based Injection
- Leverages the `UNION` SQL operator to append additional queries.
- Useful for retrieving columns or database structure.

## Authentication Bypass
- Manipulating login queries to always return `true`.

## Risk
- Direct data leakage.
- Full visibility if errors are displayed.
