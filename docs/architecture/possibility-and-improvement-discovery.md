# Possibility and Improvement Discovery

> Proposed canonical architecture; awaiting Owner acceptance under bootstrap Issue #1.
> Documentation only: no watcher, ingestion, recommendation engine or implementation authorization.

## Purpose and related applications

**Household Possibility Discovery:** "What can this Home now do that would improve household outcomes?"
Home Steward compares authoritative technology evidence with authorized household evidence to identify
evidence-supported possibilities, not to maximize automation, AI usage, novelty or device count.

**HTBW Architecture Stewardship:** "What does HTBW no longer need to implement or maintain because the
underlying platform has evolved?" See [the related architecture](htbw-architecture-stewardship.md).
Both use governed evidence and review; neither authorizes autonomous change.

Inputs are authoritative technology-capability evidence, authorized household evidence, unmet/deferred
requirements, eligible historical behavior and the current governed Home architecture. Outputs may be
an observation, candidate opportunity, evidence-grounded interpretation/recommendation, proposal draft,
"nothing worth doing" or an explicit evidence gap.

Native HTBW answers remain native. Home Steward does not own current Facts, household values,
preferences, acceptance, implementation or the authoritative formulation of a Learned Suggestion.

## Discovery-to-outcome pipeline

External capability evidence + governed household evidence
-> possibility discovery
-> evidence-supported candidate
-> household review
-> governed proposal
-> Operational Trust / applicable HTBW governance
-> separately authorized implementation work
-> acceptance
-> lived-outcome review.

Never: observed pattern -> AI writes automation -> AI enables automation.
No transition is self-authorized by Home Steward. Household confirmation of an outcome is evidence,
not consent, permission or acceptance of an implementation.

## Canonical seven-level possibility maturity model

These are proposed **possibility maturity levels**, not Operational Trust autonomy levels, platform
qualification scores or new persisted record classes. Source evidence stays source-owned.

| Level | Name | Evidence and boundary |
|---|---|---|
| 1 | Observation | Evidence exists that something repeatedly occurs, where recurrence is claimed; identify the actual sample/context. A documented technology change can also be observed without fabricating recurrent household behavior. No recommendation is implied. |
| 2 | Candidate Opportunity | An evidence-supported possible unmet outcome or simplification is identified. Repetition is not intent and technical availability is not household suitability. No implementation is authorized. |
| 3 | Household-Confirmed Opportunity | A sufficiently authorized participant confirms the specified intent/outcome, for example intentionally doing a sequence and wishing it easier. Attributable confirmation becomes scoped evidence, not permission to implement. |
| 4 | Governed Proposal | The responsible HTBW capability/human review process evaluates a complete proposal; Home Steward may supply a draft. Required content is below. A proposal is not an approved change. |
| 5 | Authorized Implementation Work | Work begins only through a separately governed implementation process with applicable authorization and responsible human ownership. Home Steward cannot authorize or execute this transition. |
| 6 | Accepted Capability | Required tests and attributable household/Owner acceptance have passed for the exact version and scope under the owning lifecycle. Neither a model answer nor this document records acceptance. |
| 7 | Lived-Outcome Review | Later eligible evidence evaluates intended improvement, friction, use/overrides, maintenance, privacy/vendor obligation and KEEP / ADAPT / REMOVE candidates. No automatic disposition. |

Unknown, declined, deferred, no-action and insufficient evidence are legitimate outcomes, not maturity
failures. Do not force advancement or create periodic acceptance nudges.

### Existing learned-policy and acceptance boundaries

The accepted [glossary](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/models/glossary.md)
and DL-123 control Learned Suggestions: observing responsibilities supply evidence; a Pattern is
**not a persisted record/store**; Concierge formulates/presents the authoritative Suggestion; applicable
acceptance governs separate Continuity preference and Operational Trust permission Change Records.
Home Steward's consultation/draft is not the reasoning of record or a new suggestion authority.

Level 3's conversational confirmation is **not DL-123 acceptance**, never writes those records, and
never lowers the existing confirmation-strength floor for a permission change. Level 4 cannot bypass
that lifecycle. This maturity model adds no Adaptive Policy lifecycle or central Opportunity store.

Acceptance stays with its owning object/capability/configuration/lifecycle under
[DL-148](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-contextual-governed-acceptance-placement.md).
Concierge may orchestrate presentation, not own acceptance. A monthly report is not an approval inbox
or a new centralized acceptance record. Dismissal or silence never implies acceptance.

## Minimum governed-proposal content

Each proposal addresses all of:

1. Household outcome.
2. Beneficiary/requesting context and authorized reviewer.
3. Current evidence, source references and uncertainty.
4. Proposed capability and verified installed-version applicability.
5. Expected benefit and how it will be measured.
6. Required devices/capabilities and current participation.
7. Authority implications and applicable approvals.
8. Privacy and locality implications.
9. Failure/degradation behavior and safe unavailable handling.
10. Manual control and preserved native fallback.
11. Exceptions and deliberately excluded behavior.
12. Implementation obligation and responsible maintainer.
13. Technical Debt implications.
14. Vendor/cloud dependency, credentials and ongoing support.
15. Rollback/removal path, data/configuration recovery and reversibility limits.
16. Acceptance criteria, exact-version tests and later lived-outcome review.

No missing item receives a success-shaped default. Every recommendation, including a suggestion to
investigate, identifies the expected household outcome and known new obligation; uncertainty remains
visible. A technically possible feature with no evidenced benefit receives "No action recommended."

## Authoritative technology-evidence model

Future source category within existing public/external knowledge; not an admitted feed or new accepted
taxonomy. See [source requirements](governed-source-connections.md#future-authoritative-technology-capability-evidence).

Each finding must support:

| Required information | Treatment |
|---|---|
| Source authority and citation | Official HA release/developer/integration/architecture/deprecation/Labs documentation first for HA claims; approved related-platform documentation for its own claims. Community material supplies inspiration only. |
| Version/release and publication date | Record the documented effective version separately from publication date. For repository evidence, use commit/version and commit date. Do not infer applicability from a recent publication. |
| Last reviewed | Date of actual review, not an invented publication date or an LLM's remembered currency. |
| Applicable installed version | Verify the actual governed installation and relevant dependency versions; a test target or current website version is not proof of deployment. |
| Relevance | Match actual integrations/devices/capabilities, goals, exclusions and accepted architecture. Irrelevant release volume has no weight. |
| Stability / GA versus preview/Labs | Identify released/GA, beta, Labs/preview or unresolved status from evidence. Do not promote preview to standard or assume tested preview means household acceptance. |
| Deprecation / removal | Distinguish announcement, effective deprecation, stated removal version/date and unknown deadline. Future obligation is not current failure. |

If official documentation is incomplete, label unresolved, name missing evidence and do not recommend
migration. A community example, similarly named API or successful demonstration does not prove support.
Undated/current documentation requires a review date and applicable version/revision verification;
missing publication/version information remains explicitly unknown.

### Official evidence reviewed for this documentation

Reviewed **2026-11-07**; no Home's installed version/configuration was queried.

| Official source | Evidenced scope and date/version limits |
|---|---|
| [HA Core releases](https://www.home-assistant.io/blog/categories/core/) / [2026.11 release](https://www.home-assistant.io/blog/2026/11/04/release-202611/) | Published 2026-11-04 for Core 2026.11. Documents target exclusions and other release changes; does not prove household relevance/adoption. |
| [Automation targets](https://www.home-assistant.io/docs/automation/targets/) | Current, undated reference reviewed above; documents exclusions and group/target semantics. Installed-version and behavioral-equivalence checks still required. |
| [Naming changes](https://www.home-assistant.io/blog/2026/11/03/naming-things-in-home-assistant/) | Published 2026-11-03, effective 2026.11; entity IDs remain, naming/display and friendly-name/template considerations require scoped review. Not proof HTBW vocabulary should be rewritten. |
| [Developer documentation](https://contributors.home-assistant.io/core/) / [developer blog](https://contributors.home-assistant.io/blog/) | Current official contributor/developer authorities; index dates are per article, not every linked capability's effective version. |
| [Undefined sentinel announcement](https://contributors.home-assistant.io/blog/2026/11/01/undefined-helper/) | Published 2026-11-01; deprecation is **as of Core 2026.12**, not 2026.11. Removal date not stated there; no claim HTBW uses these helpers. |
| [Labs](https://www.home-assistant.io/integrations/labs/) / [Labs developer guidance](https://contributors.home-assistant.io/core/development/labs/) | Undated references reviewed above: preview features are tested/usable, optional and off by default; design/behavior can change. They are not equivalent to beta releases or automatic GA/adoption. Disabling a flag does not prove all migration effects were reversed. |
| [Conversation](https://www.home-assistant.io/integrations/conversation/) | Undated reference reviewed above; native sentence/intent capability is documented. It is not voice-history capture permission or proof of media transfer support. |
| [Automations](https://www.home-assistant.io/docs/automation/) / [scripts](https://www.home-assistant.io/docs/script/) | Undated native-mechanism references; no automation/script/blueprint is created here. A deliberately invoked experience need not become passive automation. |
| [Backup](https://www.home-assistant.io/integrations/backup/) | Undated reference reviewed above; native backup mechanisms do not prove a particular backup covers external knowledge, permissions or every migration artifact. |
| [Music Assistant](https://www.music-assistant.io/) | Approved-source candidate for related-platform research, not a selected/admitted integration or proof every provider supports the same transfer. No version-specific household qualification claimed. |

These are bounded citations/paraphrases, not copied documentation or a running release catalog.
No claim that four changes actually apply to the Reference Home is made.

## Authorized household-evidence model

Potential inputs: HTBW configuration; Foundation capabilities/participation/deliberate exclusions;
Stewardship obligations; Truth/Historical Facts; authoritative Decision Traces; separately authorized
HA history/logs; declared outcomes; existing technical-debt notes; Repairs; manual overrides/sequences;
failed or deliberately retired automations; eligible voice requests and failed/unfulfilled requests;
authorized useful dashboard interactions; wish lists/deferred requirements; Change Records and
approved Reference Home observations.

Each source requires independent owner, Person/beneficiary, purpose, namespace/fields/time,
retrieval/reasoning/disclosure and derived-lifecycle scope. Useful does not mean authorized. Logs and
requests are operational evidence, not automatic Truth; sequence recurrence does not prove intent,
causation, identity or desired automation. Do not profile/rank people.

Voice-request evidence is not voice identity evidence, permission to retain audio, or authorization to
process biometrics. Accepted HA-Prod-local biometric and Person-consent restrictions remain intact.
Transcript content is minimized/redacted before retrieval; do not retain every utterance by default.
Person/actor movement reconstruction follows HTBW's dedicated classified historical path.

Retain [investigation evidence rules](knowledge-architecture.md#evidence-and-epistemic-rules):
named sample/window/exposure, provenance/quality/clock limits, missing/expired/never-held evidence,
correlation not causation, hypotheses not diagnosis/Truth, no automatic indefinite raw-log memory or
expired Explainability shadow, and no unauthorized source/cloud fallback.

## Deferred / wish-list knowledge

Document the need for governed evidence containing: desired capability; original household outcome;
date identified; reason deferred; original technical blocker; privacy/governance blocker where
applicable; current relevance; and evidence supporting reconsideration.

Use owner-held requirement/document/issue/Change Record references where accepted architecture
already provides them. Final storage, shape, lifecycle and capture mechanism remain open; no runtime
Wish List model, Pattern store, approval queue or automatic reconsideration field is created.

**Technical blocker removed does not imply household governance objection removed.**
Rejected privacy/authority/value choices and deliberately retired behavior remain respected.
Reconsideration requires current appropriate review; historical interest is not present consent.

## Future Home Possibility Review / release watch

Provisionally **Home Possibility Review**: a requested, evidence-grounded monthly comparison of
authoritative platform changes and this Home's governed needs. A future approved process may monitor
monthly HA releases, developer docs/blog, Labs, integration documentation and approved related releases.
No monitoring, crawler/feed/watch process, schedule or notification is implemented.

Every finding checks installed HA version, actual integrations/devices, HTBW architecture, goals,
privacy/locality, Operational Trust, Technical Debt, Stewardship obligation, reversibility and
acceptance evidence. Monthly cadence is not entitlement to interrupt or repeat declined suggestions.

### Canonical monthly report sections

1. Newly possible
2. Newly relevant
3. Newly risky
4. Deprecated or changing
5. Repeated household friction
6. Previously deferred ideas now worth reconsidering
7. Candidate improvements
8. Potential simplification / native replacement
9. Suggested experiments
10. No-action items
11. Evidence gaps
12. Questions for the household

Every externally grounded capability has a citation/version/date/applicability/status, even in a
summary. "No material change", "nothing worth doing" and insufficient authorized evidence are
different valid results. Suggested experiments require separate authorization, rollback and
Reference Home classification; the report never starts them or records acceptance.

## Obligation-aware evaluation and Technical Debt

Compare declared outcome/measurable benefit with implementation complexity, privacy, vendor/cloud
dependence, maintenance, credentials, support, failure modes, recoverability, reversibility,
Technical Debt and household learning. Prefer meaningful improvement with the lowest **justified**
additional obligation; no universal numeric score or model-authored household value hierarchy.

Technical Debt is an assessment lens here, **not a new HTBW framework/model/responsibility**.
DL-89's accepted narrow literal-endpoint recording convention remains narrow and unchanged.
Existing owners evaluate configuration/care/authority implications; the separate public Framework
reconciliation and broader ungoverned debt construct are not resolved by this document.

## AI/change and upstream contribution boundary

Home Steward may identify, explain, compare, synthesize, discover, recommend and draft requirements,
acceptance criteria or an implementation/reconsideration proposal as consultation.

It must not autonomously create/enable automations, alter scripts, change HTBW configuration, enable
integrations, expose entities, alter Operational Trust, modify preferences/Stewardship obligations,
install/roll back HA updates, enable Labs, write production code or submit upstream contributions.
No source content, model confidence, prior confirmation or enumerated tool grants these powers.

AI may assist a responsible human in a separately authorized development process; that human must
understand, review, validate and own any contribution. An autonomous Home Steward agent must not
independently submit Home Assistant upstream work. No development/runtime path is implemented here.

## Authority, navigation and open questions

Foundation definitions/participation; Stewardship declared significance/care; Identity effective
Person/consent lifecycle; Truth current/historical Facts; Continuity preferences/context; Operational
Trust permission for this request/context; Concierge governed formulation/orchestration/Trace.
Consume [HTBW boundary](htbw-boundary.md), [source authorization](source-authorization.md),
[derived lifecycle](derived-knowledge-lifecycle.md) and accepted [authority order](../governance/authority-order.md).

Exact finding/proposal transport, source admission/capture, qualified local host, comparison tests,
review UX, retention/deletion mechanics and implementation/acceptance mapping remain open.
No platform is selected; Issues #2-#5 are not begun.

### Possibility and Improvement Discovery scenario family

- [What is new that matters to our Home?](../scenarios/possibility-and-improvement/what-is-new-that-matters-to-our-home.md)
- [What can the Home do now that it could not before?](../scenarios/possibility-and-improvement/what-can-the-home-do-now-that-it-could-not-before.md)
- [Which previously deferred ideas are now possible?](../scenarios/possibility-and-improvement/which-previously-deferred-ideas-are-now-possible.md)
- [What repetitive actions might represent an unmet outcome?](../scenarios/possibility-and-improvement/what-repetitive-actions-might-represent-an-unmet-outcome.md)
- [What voice requests reveal a missing capability?](../scenarios/possibility-and-improvement/what-voice-requests-reveal-a-missing-capability.md)
- [Which custom automations now have native HA support?](../scenarios/possibility-and-improvement/which-custom-automations-now-have-native-ha-support.md)
- [Which device capabilities are not participating?](../scenarios/possibility-and-improvement/which-device-capabilities-are-not-participating.md)
- [What could improve the Home with the least new obligation?](../scenarios/possibility-and-improvement/what-could-improve-the-home-with-the-least-new-obligation.md)
- [What should we review before the next HA update?](../scenarios/possibility-and-improvement/what-should-we-review-before-the-next-ha-update.md)
- [Did this release create new risk or Technical Debt?](../scenarios/possibility-and-improvement/did-this-release-create-new-risk-or-technical-debt.md)
- [Prepare the monthly Home Possibility Review](../scenarios/possibility-and-improvement/prepare-the-monthly-home-possibility-review.md)
- [What opportunity do our history and current platform suggest?](../scenarios/possibility-and-improvement/what-opportunity-do-our-history-and-current-platform-suggest.md)
- [What public idea is worth testing here?](../scenarios/possibility-and-improvement/what-public-idea-is-worth-testing-here.md)
