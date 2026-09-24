# Security Policy

## Reporting a Vulnerability

Please do not publish sensitive vulnerability details in a public issue.

For a private report, use the repository's configured security contact or GitHub Security Advisories once the repository is published.

## Security Principles

RAAL is designed around:

- least privilege
- explicit authorization
- sandboxed execution
- protected core components
- audit logging
- anomaly detection
- circuit breakers
- recovery and rollback
- separation between autonomous proposals and privileged promotion

## Protected Areas

Governance, security controls, and persistence infrastructure should not be freely self-modifiable by autonomous agents.

## Operational Safety

Device, filesystem, process, network, deployment, and external-service actions must inherit RAAL governance zones and explicit scope.
