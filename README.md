# NovaLink Empire

NovaLink Empire is the business operating system and executive command center for NovaLink.

## Two-building architecture

NovaLink is one house with two separate applications:

### Building 1 — NovaLink Empire
The body and operational source of truth.

- CEO Command Center
- revenue and financial ledger
- clients and projects
- citizen applications and earnings
- workforce oversight
- opportunities and source health
- media/revenue engines
- approvals and audit history
- system health and integrations

NovaLink Empire does not become an AI chat application. It consumes intelligence and execution events from Nova AI Core through authenticated service/API boundaries.

### Building 2 — Nova AI Core
The intelligence and workforce engine.

- conversation
- voice
- model access
- reasoning/orchestration
- scouts and agents
- research
- automation
- work execution
- CEO-authorized tools

Nova AI Core does not replace the Empire command center or become the company's system of record.

## Connection

```text
NovaLink Citizen ────────┐
                         │
                         ▼
                 NovaLink Empire
                 body / system of record
                         │
                  secure API/events
                         │
                         ▼
                  Nova AI Core
                 brain / workforce
                         │
                         └──── execution results ────► Empire
```

CEO authorization is enforced server-side. A citizen must never be able to switch a client-side UI toggle into CEO mode.

## Production rule

Keep the two applications visually and operationally distinct while keeping them under one NovaLink architecture. Do not duplicate AI brains or create a second competing Empire dashboard inside Nova AI Core.
