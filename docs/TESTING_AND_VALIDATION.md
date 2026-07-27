# Testing and Validation

Development used realistic synthetic and sanitised email samples. Raw evidence was compared against generated reports.

Issues found through testing included missed shortened URLs, homoglyphs, incorrect DKIM interpretation, ignored SpamAssassin rules, reference URLs marked malicious, incorrect ATT&CK mappings, provider errors in analyst reports, PDF Unicode limitations and Streamlit syntax/AST issues.

Validation covers:

- functional ingestion, parsing, enrichment and export;
- authentication and IOC accuracy;
- malformed inputs and missing providers;
- timeouts and empty results;
- safe URL-analysis defaults;
- regression samples for every corrected defect.
