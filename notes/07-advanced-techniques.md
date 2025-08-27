# Advanced SQL Injection Techniques

## Out-of-band Injection
- Data exfiltration using alternative channels (DNS, HTTP requests).
- Useful when responses are not directly returned.

## WAF / Filter Bypass
- Using encoding, comments, or alternate syntax to evade filters.
- Exploiting DB-specific quirks (MySQL vs Oracle).

## Second-order SQL Injection
- Injection payload stored in DB and later executed in another context.
