# Error-based SQL Injection

## Concept
- Relies on database error messages.
- Attackers manipulate queries to force database to return error with useful details.

## Example Info Leaked
- DB version
- Table names
- Column names

## Mitigation
- Suppress verbose errors in production.
- Use generic error messages.
