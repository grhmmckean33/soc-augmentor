# Phishing Analysis Methodology

## Delivery and authentication

- DKIM, SPF and DMARC status
- ARC and DomainKey
- Received hops
- first public sender IP
- HELO and relay observations

## URL behaviour

- CTA and body links
- shorteners and redirect chains
- tracking parameters
- suspicious TLDs
- entropy
- displayed-link mismatch
- final landing domain and metadata

## Content and presentation

- HTML-only and image-heavy messages
- hidden content
- forms and credential fields
- CTA buttons
- brand references outside approved domains

## Evasion

- Latin/Cyrillic/Greek script mixing
- homoglyph substitution
- invisible Unicode controls
- destination concealment

## Social engineering

- urgency and fear
- fake security alerts
- credential pressure
- trust abuse
- financial or crypto targeting

## Classification

Possible outcomes include no strong indicators, low-confidence suspicious, suspicious, likely phishing and confirmed phishing. Confidence is based on evidence quality and diversity.

## Safety

The standard workflow does not submit credentials, complete forms or execute JavaScript. Network interaction is optional and should be isolated.
