# HTBW Architecture Stewardship

> Proposed canonical architecture; awaiting Owner acceptance under bootstrap Issue #1.
> Future knowledge/review capability only; no decision reopened, migration or retirement executed.

## Purpose and Home Assistant First

Home Steward may help steward HTBW itself by comparing accepted architecture and implementation with
current authoritative platform evidence. Identify changed assumptions, native alternatives,
compatibility/workaround candidates and new obligations, not automatically obsolete decisions.

**HTBW SHOULD own only the behavior and governance responsibility that Home Assistant does not already
provide appropriately.** When HA introduces a native capability that may satisfy an HTBW requirement,
HTBW SHOULD deliberately evaluate migration rather than indefinitely maintain duplicate behavior.

"Appropriately" means satisfying accepted household outcomes, responsibility contracts, privacy/locality,
Operational Trust, Truth, Identity, Stewardship, Continuity, Concierge, Explainability/Decision Trace,
degradation, performance, configuration/migration, acceptance, rollback/recovery and lived validation.
This consumes accepted [Home Assistant First](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/home-assistant-boundary.md).

**Native availability does not authorize migration.** HTBW governance responsibility is distinct from
a replaceable implementation mechanism. A native entity, trace, setting or permission mechanism is not
automatically the corresponding governed HTBW Fact, Decision Trace, configuration or authority.
Do not surrender a governing responsibility because HA offers a technical primitive.

## Related, distinct applications

[Household Possibility Discovery](possibility-and-improvement-discovery.md):
"What can this Home now do that would improve household outcomes?"

HTBW Architecture Stewardship:
"What does HTBW no longer need to implement or maintain because the underlying platform has evolved?"

The former evaluates household opportunities; the latter evaluates architecture/implementation
dependencies. Both use authoritative evidence, the shared seven-level maturity/review boundaries and
governed authorization. Neither supplies an autonomous change or approval path.
Engineering review is a separately authorized context, not an implemented second household chatbot.

## Authoritative inputs and local knowledge intent

Potential separately governed inputs include the complete HTBW and Home Steward repositories;
Framework documentation; accepted ADRs/Decision Ledger/contracts/specifications; open/deferred
requirements and issues; existing technical-debt notes; implementation/commit history and attributable
acceptance reviews; official HA release/developer/blog/architecture/breaking-change/deprecation/Labs/
integration documentation; and approved related-platform sources.

Apply [HTBW authority order](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/governance/authority-order.md).
Accepted architecture governs architecture; implementation demonstrates mechanisms, not higher
authority. Issues govern their current status/dependencies, not accepted architecture. An external HA
change is evidence for review, not an automatic amendment of HTBW.

A qualified private-AI platform may eventually locally ingest/reason across **authorized** versions
of these sources inside the governed network boundary. This is future intent, not a claim of
qualification or unrestricted ingestion. Every repository/source, credential, namespace, branch/
revision, file class and review record remains independently scoped before indexing/retrieval.
No private repository, GitHub token, correspondence or Owner record is admitted by usefulness.
Publication alone does not waive licensing, source privacy or derived-data governance.

See [future repository source requirements](governed-source-connections.md#future-governed-architecture-repository-evidence).
No repository crawler, credential storage, index, ingestion, watcher or private-AI runtime is built.

## Source freshness and capability proof

Each recommendation cites source URL/repository location, exact source version/commit, publication or
commit date, documentation review date, installed HA version where relevant, current-version
applicability, GA versus Labs/preview status, deprecation and stated removal version/date.
Unknown fields remain unknown. Fresh publication is not proof of effective-version availability.
Use the [authoritative evidence model](possibility-and-improvement-discovery.md#authoritative-technology-evidence-model).

All HA functionality claims require current official HA evidence. Community material may identify a
question, not prove a native supported equivalent. Similar names/APIs, popularity, a passing demo or
LLM memory are insufficient. Incomplete official evidence yields unresolved and a request for the
missing evidence, **not a migration recommendation**. Stale documentation is not current capability.

Illustrative official evidence reviewed 2026-11-07:
[2026.11 target exclusions](https://www.home-assistant.io/blog/2026/11/04/release-202611/)
may justify investigating a custom target-selection mechanism, but
[native target semantics](https://www.home-assistant.io/docs/automation/targets/) include exclusions,
groups and dynamic membership that must be compared, not assumed equivalent to HTBW participation.
[Naming changes](https://www.home-assistant.io/blog/2026/11/03/naming-things-in-home-assistant/)
do not authorize overwriting household vocabulary.
[Undefined helpers](https://contributors.home-assistant.io/blog/2026/11/01/undefined-helper/) are
announced on 2026-11-01 but deprecated **as of 2026.12**, not an established 2026.11 failure.
No actual affected HTBW implementation or native migration is claimed by these examples.

## Future reconsideration conventions

The following are a **future governance/documentation convention only**. Do not retrofit fields into
existing ADRs, Ledger rows, tests, models or decisions during this task; no runtime schema is defined.

### Native-Capability Dependency

An HTBW behavior exists because HA did not provide an **adequate** native capability when the decision
was accepted. Record the decision/rationale, exact historical version/evidence, limitation and accepted
outcome/contract requiring the extension. Do not fabricate a missing original rationale.

### Reconsideration Condition

Reevaluate when HA introduces the specific functionality or changes the relevant developer boundary.
Identify the measurable gap to test, official effective version, affected contracts/issues and evidence
needed. A trigger produces a review candidate, not an automatically reopened decision.

### Retirement Preference

If the native path satisfies accepted architecture/contracts/outcomes, privacy/authority, performance,
degradation and acceptance criteria, prefer deliberate migration over indefinite duplicate maintenance.
Retirement still requires governed review, tested rollback, HA-DEV validation, Reference Home lived
validation and attributable Owner acceptance of the exact replacement.

These are not a new Decision Trace field, acceptance record, Technical Debt framework or general
canonical HTBW decision schema. Existing decisions and their histories remain unchanged.

## Native-capability comparison and reconsideration

For every candidate:

- Locate decision identifier, accepted rationale and historical platform limitation.
- Cite current official evidence/version and compare scope rather than product/API names.
- Determine fully removed, partially removed, unchanged or unresolved limitation, with evidence.
- Identify current HTBW mechanism and native HA path, retained governance and behavioral gaps.
- Identify affected responsibilities, issues, ADRs, contracts, specifications, tests, code and docs.
- Compare current configuration/adoption, privacy/locality/authority, data, failure/degradation,
  diagnostics/explainability, performance, upkeep, new dependencies and reversibility.
- Return no review required, monitor, governed reconsideration warranted or evidence insufficient.

Open-issue review may recommend proceed as written, update implementation mapping, architecture
reconciliation, defer or remediation required. It does not edit/close the issue, reopen a decision or
declare accepted rationale obsolete. Requirements unsupported by current official evidence block
migration advice; lack of retained historical evidence is a named gap, never reconstructed by invention.

## Required native-capability migration-review package

Prepare, do not execute:

1. Current accepted household outcome and exact acceptance/version references.
2. Existing HTBW behavior.
3. Original rationale and historical platform limitation.
4. Native HA candidate.
5. Authoritative versioned sources and effective/installed applicability.
6. Behavioral-equivalence analysis: ordinary paths, exceptions, scope and contrary evidence.
7. Responsibility-boundary analysis: retained governance versus replaced mechanism.
8. Privacy/locality, Identity, Operational Trust and consent/disclosure implications.
9. Data/configuration migration, adoption, stable identity and history-preservation requirements.
10. Failure/unavailable/degradation comparison and manual/native fallback.
11. Performance/resource-use comparison with explicit baselines and measurable criteria.
12. Diagnostics, Explainability and unchanged Decision Trace requirements.
13. Affected issues/ADRs/contracts/specifications, tests, implementation and documentation.
14. Separately authorized implementation plan, dependencies and responsible human owner.
15. Rollback/recovery plan, reversibility limits and validation of restored permissions/configuration.
16. Unit/static/type checks and applicable official integration tests for the actual change.
17. HA-DEV exact-version validation before production transition.
18. Reference Home lived validation of preserved/improved outcome.
19. Attributable Owner acceptance requirement for the replacement.
20. Retirement criteria for superseded HTBW logic, met only after that acceptance.

Backup existence is not proven restore, data migration is not behavior preservation, passing unit
tests are not HA-DEV/lived acceptance, and a native trace is not automatically an HTBW Decision Trace.
Preserve intentional beneficial production behavior under DL-89 until approved replacement/retirement.
No retirement, migration, deploy or restart is executed by preparing this package.

## Technical Debt and new obligations

Compare obsolete adapters/workarounds, duplicate state/configuration/lifecycle mechanisms and potential
simplification with new vendor/cloud/security, credential, maintenance, learning/support and migration
obligations. A documented future deprecation may create a review/testing obligation without current
failure. No removal date or actual code dependency is invented.

Technical Debt remains an assessment lens and existing governed notes, not a new responsibility,
runtime registry or general accepted model. DL-89's literal-endpoint convention stays narrow; the
separate Framework/HTBW reconciliation and broader debt-construct question remain untouched.
Stewardship/other responsible owners evaluate obligations; Home Steward does not create or satisfy them.

## Recommendation, change and upstream limits

Home Steward may compare evidence, locate rationale, identify gaps/dependencies/affected artifacts,
draft a reconsideration proposal or migration acceptance criteria and recommend governed review.
Any future monitoring is separately authorized and unimplemented.

It may **not** declare a decision obsolete, reopen a decision, alter the Decision Ledger, rewrite an
ADR, create/close an issue, remove functionality/custom code, migrate data/configuration, replace logic,
modify production code, enable automation/Labs/integrations, change HTBW policy or install/roll back HA.
It cannot bypass Owner acceptance, HA-DEV or Reference Home validation. The responsible HTBW/human
governance process owns any subsequent decision or implementation.

AI may assist a responsible human who understands, reviews, validates and owns development.
An autonomous Home Steward agent must not independently submit Home Assistant upstream contributions.
No contribution, code generation, migration executor or automated decision-amendment path exists here.

## Existing authority and open questions

Foundation model/configuration; Truth Facts/current/historical evidence; Identity requester and consent;
Stewardship care; Continuity preferences/context; Operational Trust request-specific permission;
Concierge orchestration/governed formulation/Trace. Learned-policy and contextual acceptance remain
DL-123/DL-148-owned, not a new review inbox. The original source histories, amended Explainability
retention and source [lifecycle](derived-knowledge-lifecycle.md) stay unchanged.

Source admission, exact review/transport representation, authorized implementation workflow, host
qualification and contextual review UI remain open. No platform qualification or Issues #2-#5 work.
This document records proposed architecture, not Owner acceptance or amendments to HTBW.

### HTBW Architecture Stewardship scenario family

- [What HTBW capabilities now exist natively in Home Assistant?](../scenarios/what-htbw-capabilities-now-exist-natively-in-home-assistant.md)
- [Which HTBW decisions should be reconsidered?](../scenarios/which-htbw-decisions-should-be-reconsidered.md)
- [Should we implement this open issue as written?](../scenarios/should-we-implement-this-open-issue-as-written.md)
- [Can we retire this custom HTBW implementation?](../scenarios/can-we-retire-this-custom-htbw-implementation.md)
- [What Home Assistant changes affect HTBW?](../scenarios/what-home-assistant-changes-affect-htbw.md)
- [What should HTBW stop owning?](../scenarios/what-should-htbw-stop-owning.md)
- [What new native capability could simplify HTBW?](../scenarios/what-new-native-capability-could-simplify-htbw.md)
- [Did Home Assistant create a new obligation for HTBW?](../scenarios/did-home-assistant-create-a-new-obligation-for-htbw.md)
- [Prepare an HTBW native-capability migration review](../scenarios/prepare-an-htbw-native-capability-migration-review.md)
