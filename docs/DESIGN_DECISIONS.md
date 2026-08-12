# Design Decisions

## Evidence before certainty
Unknown evidence remains unknown. The application should never turn "not present in supplied evidence" into "not found during investigation".

## Enrichment is not attribution
A VirusTotal or AbuseIPDB result is contextual evidence. It does not automatically make a host-owned public IP an attacker IOC.

## One canonical model
Different sources feed a shared investigation model so reporting and validation logic can be reused.

## Human analyst remains accountable
The tool accelerates triage and report preparation; final validation and incident disposition remain analyst responsibilities.

## Public portfolio, private implementation
The engineering story, architecture, testing and outputs are public. Source code remains private to preserve future commercial options.
