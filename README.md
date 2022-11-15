# pdns-fetch-pt
Wrapper client to fetch, store and render passive DNS (PDNS) data from RiskIQ
PassiveTotal API.

This wrapper utilizes the [passivetotal](pypi.org/project/passivetotal) Python
library for RiskIQ to query PDNS data and perform the following:

- Format result data, producing a columnar, line-based record with a slightly
  modified ISO 8601 timestamp suited for text-processing.
- Output a timestamped copy of the JSON result data to disk.
- Output formatted result data to standard output.

