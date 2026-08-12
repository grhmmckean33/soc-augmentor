# Testing and Validation

Testing has been driven by benchmark comparison against manually investigated incidents.

## Benchmark approach
1. Investigate an incident manually and establish a trusted report.
2. Run the original alert artefact through SOC Augmentor.
3. Compare field extraction, classification, timeline, MITRE, IOC roles, Threat Intelligence and limitations.
4. Convert discrepancies into regression requirements.
5. Re-run historical cases after each architectural change.

## Accuracy statement
Internal case-specific comparisons on mature benchmark cases have shown approximately **97–99% alignment on tested alert-level outputs**. This figure is informal and benchmark-specific. It is **not** a universal product accuracy rate and does not indicate that 97–99% of incidents are correctly resolved.

SOC Augmentor cannot discover evidence that is absent from the supplied artefact. A human analyst must investigate the originating telemetry to validate and corroborate the generated report.
