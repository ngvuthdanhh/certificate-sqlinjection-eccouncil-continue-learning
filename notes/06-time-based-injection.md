# Time-based SQL Injection

## Concept
- Application does not return visible error messages.
- Delays are introduced in queries to test conditions.

## Behavior
- If a query takes significantly longer → condition likely true.
- Used to infer data bit by bit.

## Risk
- Harder to detect without monitoring response times.
