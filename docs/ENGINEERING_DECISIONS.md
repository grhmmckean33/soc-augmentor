# Engineering Decisions

- **Streamlit first:** fastest route to a complete browser prototype.
- **Modular Python pipeline:** parsers, enrichers, scorers and reports evolve independently.
- **Private implementation:** protects commercial and misuse-sensitive details.
- **Environment variables:** secrets never belong in source control.
- **Optional URL checks:** suspicious network interaction is disabled by default.
- **Context before scoring:** reference URLs cannot inflate risk.
- **Weighted categories with caps:** reduces double-counting.
- **Provider errors are operational data:** they do not become threat findings.
- **Explainability first:** evidence and reasoning accompany scores.
