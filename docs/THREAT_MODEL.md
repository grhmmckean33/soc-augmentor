# Threat Model

## Assets

Proprietary code, API credentials, analyst data, email evidence, reports, caches and configuration.

## Threats

Secret disclosure, sensitive-data uploads, unsafe URL resolution, malicious HTML, quota exhaustion, false-positive blocking and overreliance on automated verdicts.

## Controls

No secrets in Git, optional network lookups, strict timeouts, no form submission, no standard JavaScript execution, caching, evidence/confidence fields, sanitised examples and a private implementation.

SOC Augmentor is decision support. It does not guarantee an IOC is malicious or replace approved incident-response procedures.
