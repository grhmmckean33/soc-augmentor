# Threat-Intelligence Design

Potential providers include AbuseIPDB, AlienVault OTX, URLhaus, VirusTotal, GreyNoise, PhishTank and RDAP/WHOIS services.

## Normalised result

```json
{
  "provider": "Example",
  "indicator": "example.invalid",
  "status": "ok",
  "verdict": "suspicious",
  "confidence": "medium",
  "detail": "Provider summary",
  "cached": false
}
```

## Controls

- environment-variable API keys
- availability checks
- timeouts, retries and rate limits
- result caching
- graceful failure
- analyst-safe error presentation

`unknown` does not mean clean. `not_available` means the lookup failed. `reference` means the IOC was deliberately excluded from attacker infrastructure.
