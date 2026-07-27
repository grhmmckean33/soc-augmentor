# Build Journey

## Phase 1 — Product concept

The project began as a search for a painfully specific, monetisable Python application. SOC augmentation was selected because analysts repeatedly perform manual enrichment, explanation and reporting.

## Phase 2 — Streamlit proof of concept

The first browser version accepted sample JSON and generated findings, basic enrichment, risk scores, ATT&CK mappings, timelines, actions and Markdown reports.

## Phase 3 — Email ingestion

Ordinary and Outlook-style email input was converted into the same normalised schema used for alerts.

## Phase 4 — Threat intelligence

Optional external providers were introduced. Key lessons included secrets management, caching, timeouts, graceful failure and the distinction between “unknown” and “clean”.

## Phase 5 — Phishing analysis

The application added urgency, fear, credential pressure, financial targeting, brand impersonation, suspicious domains and likely attacker objectives.

## Phase 6 — Raw-email intelligence

Testing revealed the importance of full message source. The application added authentication, SpamAssassin, HTML-only/image-heavy analysis, PHP mailer indicators, CTA extraction and Unicode homoglyph detection.

## Phase 7 — Context-aware IOC hygiene

Reference URLs and embedded resources were separated from attacker infrastructure. This materially improved precision and analyst trust.

## Phase 8 — Evidence-led precision

The platform added per-finding confidence, stable URL roles, evidence provenance, capped scoring, redirect chains, corrected ATT&CK mappings, campaign fingerprints and machine-readable exports.

## Development method

Realistic test messages were compared with generated reports. Missed or incorrect findings became requirements, modular changes and regression cases. This demonstrated requirements elicitation, debugging, threat reasoning, product prioritisation and user-centred refinement.
