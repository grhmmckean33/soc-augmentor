# IOC Classification

Raw extraction creates noise. SOC Augmentor assigns context before scoring.

| Context | Meaning | Action |
|---|---|---|
| `cta_link` | Login, verify, review or payment action | Investigate and block if confirmed |
| `redirector` | Shortener or redirect service | Resolve safely |
| `body_link` | Ordinary message link | Investigate in context |
| `embedded_resource` | Image, logo, CSS or tracking resource | Supporting evidence |
| `reference_url` | Help or documentation | Do not treat as attacker infrastructure |
| `header_reference` | Anti-spam/header reference | Exclude from attacker IOC list |

A mature IOC record includes indicator, type, role, context, confidence, evidence source, risk contribution, recommended action and enrichment results.

```json
{
  "indicator": "hxxps://example[.]invalid",
  "type": "url",
  "role": "Primary phishing URL",
  "context": "redirector",
  "confidence": "high",
  "recommended_action": "Resolve safely and block if confirmed malicious"
}
```
