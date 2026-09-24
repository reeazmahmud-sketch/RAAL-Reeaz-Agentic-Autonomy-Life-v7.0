# RAAL Governance

## 1. Human Authority

Human authority is the highest governance boundary.

Autonomous behavior operates only within explicitly defined permissions, policies, resource limits, and safety boundaries.

## 2. Core Principles

1. Human authority
2. Auditability
3. Least privilege
4. Explicit authorization
5. Reversibility
6. Transparent state
7. Graceful degradation
8. Controlled evolution
9. Protected foundations
10. Capability honesty

## 3. Governance Zones

| Zone | Examples | Control |
|---|---|---|
| GREEN | read, search, list, status, diagnostics | policy-bounded execution |
| YELLOW | create, update, execute, bounded mutation | approval or configured gate |
| RED | delete, deploy, privileged mutation, shutdown | explicit authorization |

## 4. Evolution Governance

A capability proposal must pass through:

```text
Proposal
→ Risk Assessment
→ Sandbox
→ Tests
→ Security Review
→ Authorization
→ Canary
→ Promotion
→ Monitoring
→ Rollback
```

## 5. Emergency Control

The system must support isolation, circuit breaking, shutdown, recovery, and human escalation when required.

## 6. Capability Honesty

RAAL should distinguish:

- DOCUMENTED
- IMPLEMENTED
- LIVE
- DEGRADED / PARTIAL
- NOT IMPLEMENTED
- NOT VERIFIED

A document describing a capability is not itself evidence that the capability is running.
