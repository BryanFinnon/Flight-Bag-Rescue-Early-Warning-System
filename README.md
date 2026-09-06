# Flight Bag Rescue — Early Warning System

> **Status: design and documentation stage. Implementation is not yet included in this repository.**

A proposed early-warning system for detecting operational risks around electronic flight bags and alerting crews before they become critical.

## Intended problem

Electronic flight bag failures can disrupt access to operational information. This project explores a system that would collect health signals, identify warning patterns, and present actionable alerts to flight operations teams.

## Proposed scope

- Device and application health monitoring
- Rule-based risk detection
- Prioritised alerts
- Operational dashboard
- Incident history and audit trail
- Future anomaly-detection experiments

## Planned architecture

```text
Telemetry sources → ingestion service → rules/anomaly engine → alert API → dashboard
```

## Implementation roadmap

- [ ] Define representative telemetry schema and synthetic sample data
- [ ] Build ingestion and validation service
- [ ] Implement baseline rules engine
- [ ] Add dashboard and alert lifecycle
- [ ] Add automated tests and CI
- [ ] Evaluate anomaly-detection approaches
- [ ] Document deployment and security model

## Why this repository remains public

The current material demonstrates problem framing and system-design thinking. It should not yet be evaluated as a completed software project; source code, tests, and a runnable demonstration will be added in later iterations.

## Author

Bryan Finnon — MSc Computer Science (Distinction), focused on applied AI and software engineering.
