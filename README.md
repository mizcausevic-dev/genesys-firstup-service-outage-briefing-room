# Genesys FirstUp Service Outage Briefing Room

Service outage briefing room tying Genesys demand spikes to FirstUp internal communication coverage.

![ci](https://github.com/mizcausevic-dev/genesys-firstup-service-outage-briefing-room/actions/workflows/ci.yml/badge.svg)

## What this ships

This repo is a static Kinetic Gain evidence surface, not a placeholder page. It packages Genesys, FirstUp signals into a board-readable operating view with decision workflow, board-pack copy, related links, and validation checks:

- Exposure: where workflow, platform, or communications risk can become visible.
- Savings: where duplicate effort, drift, or manual coordination can be reduced.
- Investment: which next action deserves funding, ownership, or escalation.
- Story: how the evidence should be explained to executives or investors.

## Operating workflow

1. Ingest current platform signals, ownership notes, exception records, and timing windows.
2. Score exposure, savings, and investment pressure separately.
3. Route every lane to one accountable owner, one audience, and one next action.
4. Brief the decision in language that can survive board, investor, or diligence review.

## Live surface

- Product page: https://mizcausevic-dev.github.io/genesys-firstup-service-outage-briefing-room/
- Repository: https://github.com/mizcausevic-dev/genesys-firstup-service-outage-briefing-room
- Portfolio atlas: https://portfolio.kineticgain.com/

## Evidence lanes

- exposure
- savings
- investment

## Related surfaces

- [Genesys FirstUp Agent Readiness Broadcast](https://mizcausevic-dev.github.io/genesys-firstup-agent-readiness-broadcast/)
- [Genesys FirstUp Incident Comms Bridge](https://mizcausevic-dev.github.io/genesys-firstup-incident-comms-bridge/)
- [CyberArk FirstUp Access Risk Comms Ledger](https://mizcausevic-dev.github.io/cyberark-firstup-access-risk-comms-ledger/)
- [CyberArk FirstUp Privileged Change Briefing](https://mizcausevic-dev.github.io/cyberark-firstup-privileged-change-briefing/)
- [FirstUp Employee Incident Narrative Pack](https://mizcausevic-dev.github.io/firstup-employee-incident-narrative-pack/)

## Local verification

```bash
npm test
```

The validation script checks the data payload, generated page, interactive evidence table, related links, and footer links.
