# Qualification gates

> Proposed baseline; not the completed/accepted standard. Common standard is
> [#2](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/2).
> No candidate gate has been tested or passed.

## Hard disqualifiers

A demonstrated failure of any required gate means NOT QUALIFIED for that evaluated configuration.
Unknown evidence means RESEARCH INCOMPLETE, never PASS. Prompts, purchase price or weighted scores
cannot compensate for a failed mandatory boundary.

| Gate | Disqualifying condition | Required future evidence |
|---|---|---|
| G01 | Household-sensitive data egresses by default | Default and explicit local-profile flow inventory + enforcement observations |
| G02 | Local-only policy cannot be technically enforced | Configurations, network controls and failure tests independent of model compliance |
| G03 | Silent cloud fallback | Offline/provider-failure observation and documented routing |
| G04 | Routine local use depends on vendor service/subscription | Offline/license/account renewal and vendor-exit evidence |
| G05 | Undocumented telemetry | Complete endpoints/payloads/retention and control documentation + observation |
| G06 | Standing support access to household content | Support identity/access/audit/revocation policy and enforceable controls |
| G07 | Connector transmits more information than authorized | Field/namespace/person scope and minimized transmission evidence |
| G08 | Unauthenticated or unnecessarily exposed APIs | Auth, bind/interface, TLS/trust, privilege and exposure tests |
| G09 | Credentials are stored or managed insecurely | Storage, scopes, rotation/revocation and secret-redaction evidence |
| G10 | Raw prompts/responses are retained indefinitely | Retention controls, actual deletion/backup behavior and minimal audit design |
| G11 | No export or secure erasure of household data | Export/readability/lineage and content/index/memory/replica erasure evidence |
| G12 | Vendor disappearance makes the appliance materially unusable | Meaningful local operation, recovery/license/model/export dependency analysis |
| G13 | Reasoning automatically becomes authoritative state | HTBW boundary, mutation denial and explicit promotion tests |
| G14 | Tool/API availability creates execution authority | Denial tests and independent HTBW permission/confirmation enforcement |
| G15 | Person-level or source-level scope cannot be enforced | Mixed-permission retrieval/disclosure/cache tests outside the LLM |
| G16 | Read access implies transaction authority | Distinct credentials/operations/policy for payments, email and scheduling |
| G17 | Derived representations escape source governance | Lineage, revocation/deletion, restore and person-disclosure tests |

## Evidence and decision rules

Use per-configuration, dated claims/docs/observations/unknowns. A broad marketing statement is not a
tested gate. Record failure and contradictory evidence, not only favorable demonstrations.

All applicable gates must be explicitly PASS under the Owner-accepted common standard before any
weighted score or qualified outcome. Applicability must itself be justified and reviewed; it cannot
be used to exempt a universal privacy/authority requirement.
QUALIFIED WITH CONDITIONS cannot waive a hard gate; conditions concern non-gating limits.

Canonical outcomes:

- QUALIFIED FOR REFERENCE HOME VALIDATION
- QUALIFIED WITH CONDITIONS
- RESEARCH INCOMPLETE
- NOT QUALIFIED
- DEFERRED, MARKET NOT MATURE

## Backlog and dependencies

[#1 bootstrap](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/1) has no dependency.
#2 depends on its baseline.
[Ghost #3](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/3) and
[grouped appliances #4](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/4) may gather
public evidence early, but cannot issue final qualification/comparison before #2 Owner acceptance.
[Software/DIY #5](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/5) provides controls.

See [compatibility matrix](compatibility-matrix.md) and [evaluation method](evaluation-method.md).
