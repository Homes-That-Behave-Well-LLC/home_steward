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

Primary files: **1 developed + 14 Vision = 15**. Cross-links below do not add files or change target maturity.

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
