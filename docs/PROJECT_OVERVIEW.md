# Project Overview

SOC Augmentor is a locally hosted analyst-augmentation platform for structuring SOC alert investigations from supplied evidence. Current inputs include Microsoft Defender XDR JSON, Splunk alert JSON and email/phishing evidence.

The project is intentionally public as a **documentation and engineering portfolio only**. The production source code is not published because the project may be commercialised.

## Current operating model
- Runs on localhost for an individual analyst.
- Accepts supplied alert artefacts rather than directly exploring a live SIEM/EDR.
- Produces an investigation foundation that must be validated and corroborated by a human analyst.
- Future versions are planned for secure online availability.
