# Resilience and Recovery

Navigation and scope guidance only; not an architecture contract or roadmap. Browse the [scenario-family map](../README.md).

## Purpose

Understand known dependencies, manual alternatives, evidence gaps and documented recovery. Resilience includes continued operation, safe stopping, degradation and recovery, not running everything forever.

## Relationship to HTBW

Native HTBW, Home Assistant and device behavior remain independently owned. The developed unavailable-person briefing lives here because its primary outcome is whole-Home care and operating knowledge, not Asset-only inquiry. See the existing [HTBW boundary](../../architecture/htbw-boundary.md).

## Possible Home Steward extension

Explain authorized dependency and recovery evidence without claiming a complete infrastructure map or verified restoration. Any new source admission, representation, handoff or implementation is an OPEN ARCHITECTURAL QUESTION.

## Boundaries

No life-safety/emergency path depends on Home Steward or an LLM. No restart, restore, recovery-priority algorithm or unproved safe-operation guarantee; household-declared priorities and professional judgment remain authoritative.

Person/source/purpose/namespace/audience scope, household-controlled locality and source-derived lifecycle remain independent requirements. Potential evidence is not admitted access; knowledge is not action or disclosure authority. Source reports and inference are not automatic Truth; unknown is valid and correlation is not causation.

## Scenarios

Primary files: **1 developed + 17 Vision = 18**. Cross-links below do not add files or change target maturity.

### Developed / Canonical

- [What should someone else know if I am unavailable](what-should-someone-else-know-if-i-am-unavailable.md) — **CANONICAL SCENARIO**. Prepares a minimized authorized Home-care briefing without inferring incapacity or delegation.

### Vision — Not Yet Architected

- [What still works if Home Assistant is unavailable?](what-still-works-if-home-assistant-is-unavailable.md) — **VISION — NOT YET ARCHITECTED**. A Home Assistant outage should not be described as the loss of every physical household function.
- [What still works if Home Steward is unavailable?](what-still-works-if-home-steward-is-unavailable.md) — **VISION — NOT YET ARCHITECTED**. Losing optional reasoning should not remove HTBW's accepted native outcomes.
- [What stops if the Internet goes down?](what-stops-if-the-internet-goes-down.md) — **VISION — NOT YET ARCHITECTED**. An Internet outage may interrupt vendor services, updates or external information while leaving some local functions intact.
- [What depends on this server?](what-depends-on-this-server.md) — **VISION — NOT YET ARCHITECTED**. A server may support several seemingly unrelated household experiences.
- [Which capabilities are currently degraded?](which-capabilities-are-currently-degraded.md) — **VISION — NOT YET ARCHITECTED**. A capability may be unavailable, limited or operating with reduced evidence rather than wholly failed.
- [What should we recover first after an extended outage?](what-should-we-recover-first-after-an-extended-outage.md) — **VISION — NOT YET ARCHITECTED**. After a long outage, the household may need to understand restoration dependencies and already-declared priorities before people choose a recovery sequence.
- [Did everything return normally after the power outage?](did-everything-return-normally-after-the-power-outage.md) — **VISION — NOT YET ARCHITECTED**. Power returning does not prove that every capability recovered its intended behavior.
- [What failed to recover after the restart?](what-failed-to-recover-after-the-restart.md) — **VISION — NOT YET ARCHITECTED**. A restart can leave one function unavailable while other services appear healthy.
- [Do we have current recovery instructions for every critical capability?](do-we-have-current-recovery-instructions-for-every-critical-capability.md) — **VISION — NOT YET ARCHITECTED**. Recovery instructions can exist but be stale, inaccessible during an outage or untested.
- [Which systems depend on one person's knowledge?](which-systems-depend-on-one-person-s-knowledge.md) — **VISION — NOT YET ARCHITECTED**. A household function can depend on tacit knowledge held by one person even when its technical dependencies are documented.
- [What backups have never been proven through restoration?](what-backups-have-never-been-proven-through-restoration.md) — **VISION — NOT YET ARCHITECTED**. A successful backup report is not evidence that restoration has worked.
- [What can the household still operate manually?](what-can-the-household-still-operate-manually.md) — **VISION — NOT YET ARCHITECTED**. Manual control can be an important household alternative when intelligence or connectivity is missing.
- [What intelligence can disappear without making the Home unsafe?](what-intelligence-can-disappear-without-making-the-home-unsafe.md) — **VISION — NOT YET ARCHITECTED**. The household wants to understand which intelligence is optional without making safety depend on a reasoning service.
- [What should safely stop when intelligence disappears?](what-should-safely-stop-when-intelligence-disappears.md) — **VISION — NOT YET ARCHITECTED**. Some enriched experiences should become unavailable when their evidence or intelligence disappears rather than continue on guesses.

### Explicit coverage / no duplicate file

- [What knowledge would another household member need if I were unavailable?](what-should-someone-else-know-if-i-am-unavailable.md) — **DUPLICATE / COVERED ELSEWHERE** (catalog disposition; target remains **CANONICAL SCENARIO**). Existing minimized beneficiary-specific Home-care briefing covers this contingency.

Related outcomes: [Counterfactual and Planning](../counterfactual-and-planning/README.md) | [Travel, Absence and Return](../travel-absence-and-return/README.md) | [Transitions and Succession](../transitions-and-succession/README.md) | [Asset Intelligence](../asset-intelligence/README.md).

## Open questions

What is documented versus independently demonstrated? What is unavailable, safely stopped or unknown rather than successfully recovered? Promotion requires [separate governed review](../README.md#promotion); recurring similarities do not establish solution ownership.

## Reference Home discovery increment

Documented, tested, currently qualified and unexercised fallback evidence differ. Existing recovery order and manual-control scenarios are reused. No failure test, reset, controller operation, recovery guarantee or LLM-dependent safety is introduced; source uncertainty remains explicit.

New primary files in this increment: **3**. Each is catalogued only in this primary family. All earlier bodies and maturity remain unchanged.

- [What remains operational when the network controller is unavailable?](what-remains-operational-when-the-network-controller-is-unavailable.md) — **VISION — NOT YET ARCHITECTED**. Network-controller loss may affect administration, discovery or forwarding differently depending on the installed system and conditions. The household wants those documented distinctions and observed outcomes understood without assuming the network either entirely stops or entirely continues. An unavailable management screen is not a complete household outage.
- [Which system should not be reset without understanding its downstream effects?](which-system-should-not-be-reset-without-understanding-its-downstream-effects.md) — **VISION — NOT YET ARCHITECTED**. Resetting a seemingly isolated system can interrupt downstream services, erase useful evidence or make a care task harder. The household wants existing restrictions and documented consequences understood before anyone attempts a reset. Unknown downstream effects are a reason for qualified review, not confidence that restarting is harmless.
- [Does recovery require external vendor support?](does-recovery-require-external-vendor-support.md) — **VISION — NOT YET ARCHITECTED**. A recovery document can omit that a vendor, account administrator or support service must participate. The household wants that declared dependency and its limits understood before assuming local equipment can be restored independently. Availability of external support is not guaranteed by a subscription or a past successful recovery.

## Reference Home requested-entry coverage

Every occurrence retains its requested wording. Coverage links and new-primary aliases do not create additional primaries or change the target's maturity.

| Entry | Requested wording | Primary coverage | Disposition and rationale |
|---|---|---|---|
| resilience-1 | What should the household recover first after this dependency fails? | [What should we recover first after an extended outage?](../resilience-and-recovery/what-should-we-recover-first-after-an-extended-outage.md) | EXISTING COVERAGE — Existing recovery-prerequisite and household-declared-priority review applies after this failure without creating a rescue order. |
| resilience-2 | Which experiences have a tested manual fallback? | [Which manual fallbacks have never been tested?](../commissioning-configuration-and-acceptance/which-manual-fallbacks-have-never-been-tested.md) | NEW PRIMARY ALIAS — One primary explicitly includes this wording variant and its scoped evidence/authority limits; no second file or additional maturity claim. |
| resilience-3 | Which manual fallbacks exist only in documentation? | [Which manual fallbacks have never been tested?](../commissioning-configuration-and-acceptance/which-manual-fallbacks-have-never-been-tested.md) | NEW PRIMARY ALIAS — One primary explicitly includes this wording variant and its scoped evidence/authority limits; no second file or additional maturity claim. |
| resilience-4 | Which fallback procedures have never been exercised? | [Which manual fallbacks have never been tested?](../commissioning-configuration-and-acceptance/which-manual-fallbacks-have-never-been-tested.md) | NEW PRIMARY ALIAS — One primary explicitly includes this wording variant and its scoped evidence/authority limits; no second file or additional maturity claim. |
| resilience-5 | Did dual-ISP failover preserve what mattered? | [Did ISP failover preserve the intended household outcome?](../investigation-and-explainability/did-isp-failover-preserve-the-intended-household-outcome.md) | NEW PRIMARY ALIAS — One primary explicitly includes this wording variant and its scoped evidence/authority limits; no second file or additional maturity claim. |
| resilience-6 | Which local capabilities still depend on vendor authentication? | [What depends on cloud authentication?](../investigation-and-explainability/what-depends-on-cloud-authentication.md) | NEW PRIMARY ALIAS — One primary explicitly includes this wording variant and its scoped evidence/authority limits; no second file or additional maturity claim. |
| resilience-7 | What remains operational when the private-AI appliance is unavailable? | [What still works if Home Steward is unavailable?](../resilience-and-recovery/what-still-works-if-home-steward-is-unavailable.md) | EXISTING COVERAGE — Existing native-versus-enriched unavailable-Home-Steward boundary applies to loss of its prospective private-AI host without universal guarantees. |
| resilience-8 | What remains operational when the network controller is unavailable? | [What remains operational when the network controller is unavailable?](../resilience-and-recovery/what-remains-operational-when-the-network-controller-is-unavailable.md) | NEW PRIMARY — No controller-independence guarantee, topology inventory, restart, configuration change or outage test is introduced. |
| resilience-9 | Which recovery procedure depends on one person's knowledge? | [Which systems depend on one person's knowledge?](../resilience-and-recovery/which-systems-depend-on-one-person-s-knowledge.md) | EXISTING COVERAGE — Existing explicitly evidenced single-Person operating-knowledge gap includes recovery knowledge without profiling or copying private records. |
| resilience-10 | What should another household steward know before attempting recovery? | [What should someone else know if I am unavailable](../resilience-and-recovery/what-should-someone-else-know-if-i-am-unavailable.md) | EXISTING COVERAGE — Existing minimized beneficiary-specific Home-care briefing includes permitted operating knowledge without credentials or delegation. |
| resilience-11 | Which system should not be reset without understanding its downstream effects? | [Which system should not be reset without understanding its downstream effects?](../resilience-and-recovery/which-system-should-not-be-reset-without-understanding-its-downstream-effects.md) | NEW PRIMARY — No reset instructions, restart, remediation or permission to act is supplied. Professional and native safety constraints remain independent of Home Steward. |
| resilience-12 | Does recovery require external vendor support? | [Does recovery require external vendor support?](../resilience-and-recovery/does-recovery-require-external-vendor-support.md) | NEW PRIMARY — No vendor contact, credential disclosure, restore operation or recovery guarantee is introduced. A known support dependency is not platform qualification. |

## Reference Home related outcomes

[Investigation and Explainability](../investigation-and-explainability/README.md) | [Commissioning, Configuration and Acceptance](../commissioning-configuration-and-acceptance/README.md) | [Household Coordination](../household-coordination/README.md) | [Offline Household Intelligence](../offline-household-intelligence/README.md) | [Reference Home walkthrough](../reference-home-walkthrough.md).

## Reference Home future questions

- **OPEN ARCHITECTURAL QUESTION:** What independently eligible source/context and responsible owner review could support these questions without changing native authority?
- **OPEN ARCHITECTURAL QUESTION:** What actual evidence, scope and separate governance would be required before any mechanism or promotion could be considered?
