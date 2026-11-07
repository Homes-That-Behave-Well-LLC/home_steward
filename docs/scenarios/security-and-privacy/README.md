# Security and Privacy

Navigation and scope guidance only; not an architecture contract or roadmap. Browse the [scenario-family map](../README.md).

## Purpose

Understand authorized access, disclosures, external dependencies and privacy questions without making people objects of suspicion or continuous monitoring.

## Relationship to HTBW

Identity context is not authentication or authorization. Operational Trust applies request-specific source/action/disclosure policy; owning responsibilities retain consent and configuration. See the existing [HTBW boundary](../../architecture/htbw-boundary.md).

## Possible Home Steward extension

Explain governed scope, eligible evidence and unresolved privacy or dependency concerns. Any new source admission, representation, handoff or implementation is an OPEN ARCHITECTURAL QUESTION.

## Boundaries

No inferred human trustworthiness, consent or permission. No silent cloud fallback, private-query leakage, security-remediation engine or source instructions overriding governance.

Person/source/purpose/namespace/audience scope, household-controlled locality and source-derived lifecycle remain independent requirements. Potential evidence is not admitted access; knowledge is not action or disclosure authority. Source reports and inference are not automatic Truth; unknown is valid and correlation is not causation.

## Scenarios

Primary files: **0 developed + 27 Vision = 27**. Cross-links below do not add files or change target maturity.

### Developed / Canonical

No developed primary scenario in this family; new content remains Vision.

### Vision — Not Yet Architected

- [What security-related events deserve attention?](what-security-related-events-deserve-attention.md) — **VISION — NOT YET ARCHITECTED**. A household may see many security-related records without knowing which are relevant to its stated concerns.
- [Was this access event normal for this household?](was-this-access-event-normal-for-this-household.md) — **VISION — NOT YET ARCHITECTED**. An unexpected access entry can be a legitimate visit, a changed routine or a record with missing context.
- [Which outside services receive information from the Home?](which-outside-services-receive-information-from-the-home.md) — **VISION — NOT YET ARCHITECTED**. Outside services can receive different kinds of information for different household capabilities.
- [What information leaves the Home when this capability is used?](what-information-leaves-the-home-when-this-capability-is-used.md) — **VISION — NOT YET ARCHITECTED**. A capability may feel local while relying on an outside service for some operations.
- [Did the last update change external connections?](did-the-last-update-change-external-connections.md) — **VISION — NOT YET ARCHITECTED**. An update can change documented dependencies even when the visible household experience looks unchanged.
- [Which cloud dependencies could be removed?](which-cloud-dependencies-could-be-removed.md) — **VISION — NOT YET ARCHITECTED**. A household may prefer fewer outside dependencies but still value reliable care, accessibility and familiar interactions.
- [What devices have started communicating with new external destinations?](what-devices-have-started-communicating-with-new-external-destinations.md) — **VISION — NOT YET ARCHITECTED**. A device communicating with an unfamiliar destination raises a question about changed dependencies, not an automatic security conclusion.
- [Who has access to the gate?](who-has-access-to-the-gate.md) — **VISION — NOT YET ARCHITECTED**. Gate access can involve different people, services and temporary purposes.
- [Who has access to cameras?](who-has-access-to-cameras.md) — **VISION — NOT YET ARCHITECTED**. Camera access is not a single permission: viewing live imagery, recordings or administration can expose different household details.
- [Who has access to dashboards?](who-has-access-to-dashboards.md) — **VISION — NOT YET ARCHITECTED**. A dashboard may combine harmless room help with private household context or sensitive controls.
- [Who has access to household knowledge?](who-has-access-to-household-knowledge.md) — **VISION — NOT YET ARCHITECTED**. Household knowledge can contain many people's documents, stories and sensitive details.
- [Which credentials or permissions are unused?](which-credentials-or-permissions-are-unused.md) — **VISION — NOT YET ARCHITECTED**. Old permissions and account dependencies can remain after a household stops using a capability.
- [What household information could this integration correlate?](what-household-information-could-this-integration-correlate.md) — **VISION — NOT YET ARCHITECTED**. An integration may receive several ordinary data categories that become revealing when combined.
- [If this service is revoked, what stops working?](if-this-service-is-revoked-what-stops-working.md) — **VISION — NOT YET ARCHITECTED**. Revoking a service can affect more than its most visible feature.
- [What does this guest account allow?](what-does-this-guest-account-allow.md) — **VISION — NOT YET ARCHITECTED**. A guest account can mean different things across rooms, information sources and controls.
- [When does temporary access expire?](when-does-temporary-access-expire.md) — **VISION — NOT YET ARCHITECTED**. Temporary access should be understandable without guessing from a visit ending or an account becoming quiet.
- [Show me what information about our lives crosses the household boundary and why.](show-me-what-information-about-our-lives-crosses-the-household-boundary-and-why.md) — **VISION — NOT YET ARCHITECTED**. Household information can cross the governed boundary through several capabilities, each with a different stated purpose.

Related outcomes: [Guests and Temporary Authority](../guests-and-temporary-authority/README.md) | [Communication and Notification](../communication-and-notification/README.md) | [Transitions and Succession](../transitions-and-succession/README.md).

## Ambient privacy and sensitive cross-source increment

NOTICE != DIAGNOSE; NOTICE != DISCLOSE; NOTICE != RETAIN; NOTICE != RECOMMEND; NOTICE != ACT. Noticing is not authority or automatic Truth, household significance, notification or action.

Combination and disclosure require independent Person/source/purpose/namespace/audience eligibility before reasoning. A warning or 'continue' confirmation does not widen grants; most restrictive source constraints and source-owner revocation remain binding. No consent engine is designed.

- [Tell us when an authorized integration begins communicating differently.](tell-us-when-an-authorized-integration-begins-communicating-differently.md) — **VISION — NOT YET ARCHITECTED**. An authorized integration may change message timing, volume or destinations while its visible feature appears unchanged. The household wants broader communication differences understood without assuming compromise, capturing payloads or confusing first observation with actual onset.
- [Notice when a previously local capability introduces a new external dependency.](notice-when-a-previously-local-capability-introduces-a-new-external-dependency.md) — **VISION — NOT YET ARCHITECTED**. A capability previously understood as local may begin depending on an outside service. The household wants that boundary change explained even when no particular update is established as its cause, without confusing an endpoint observation with operational dependency.
- [Tell us when a source's privacy terms or technical behavior materially change.](tell-us-when-a-source-s-privacy-terms-or-technical-behavior-materially-change.md) — **VISION — NOT YET ARCHITECTED**. A source's declared privacy terms or actual technical scope can change after initial authorization. The household wants the difference visible against its granted purpose, not old consent treated as agreement to a new audience or retention practice.
- [Notice when newly available evidence would require more disclosure than before.](notice-when-newly-available-evidence-would-require-more-disclosure-than-before.md) — **VISION — NOT YET ARCHITECTED**. New evidence may answer a useful question while revealing more than earlier evidence did. The household wants that change in sensitivity understood before combination or disclosure, because usefulness does not remove the original source's audience and purpose limits.
- [This answer would combine financial and health information. Continue?](this-answer-would-combine-financial-and-health-information-continue.md) — **VISION — NOT YET ARCHITECTED**. Financial and health information can reveal sensitive context when combined even if each source has some authorization. The household wants the combination boundary recognized before reasoning, because a continue response cannot erase source-purpose limits or make the resulting conclusion safe for a shared audience.
- [This investigation would search private-room visual history.](this-investigation-would-search-private-room-visual-history.md) — **VISION — NOT YET ARCHITECTED**. Private-Room visual history can reveal intimate context beyond an ordinary investigation. The household wants explicit exclusion and purpose boundaries preserved, rather than a useful question or household membership being treated as authority to search bedrooms, bathrooms or other excluded spaces.
- [This caregiver summary may disclose wearable evidence.](this-caregiver-summary-may-disclose-wearable-evidence.md) — **VISION — NOT YET ARCHITECTED**. A caregiver summary may reveal wearable observations without showing the original records. The household wants that derived disclosure considered explicitly, so minimum wording, family relationship or a caring purpose does not launder Person-private evidence into an automatically eligible summary.
- [This question requires information from two different people's private sources.](this-question-requires-information-from-two-different-people-s-private-sources.md) — **VISION — NOT YET ARCHITECTED**. Two people's private sources can jointly reveal more than either alone. The household wants independent Person, purpose and audience constraints preserved before comparison, because consent from one contributor or separate access to both documents does not authorize a merged personal profile.
- [External research would reveal the nature of the household inquiry to a third party.](external-research-would-reveal-the-nature-of-the-household-inquiry-to-a-third-party.md) — **VISION — NOT YET ARCHITECTED**. External research can disclose an inquiry's subject even without sending names or documents. The household wants that exposure understood before research, so private Asset, financial, health or travel interests do not leak through seemingly generic query wording or an automatic fallback.
- [This answer may expose travel absence information.](this-answer-may-expose-travel-absence-information.md) — **VISION — NOT YET ARCHITECTED**. An answer about an Asset or service can indirectly reveal that the household is away. The household wants travel absence treated as sensitive derived context, not a harmless side detail, because a useful summary on a shared screen or to a provider can expose security-relevant information.

[Complete explicit dispositions](../README.md#ambient-and-household-intelligence-increment) include existing dependency-aware permission-necessity coverage; apparent inactivity is not expiry or revocation. All previously developed and Vision bodies remain unchanged.

## Open questions

Who may ask and receive the answer? Can the concern be explained without retrieving or revealing protected content? Promotion requires [separate governed review](../README.md#promotion); recurring similarities do not establish solution ownership.

## Reference Home coverage cross-links

Existing primary bodies and maturity are unchanged. The following families record explicit requested occurrences covered here; no duplicate scenario or additional source authority is created.

[Counterfactual and Planning](../counterfactual-and-planning/README.md#reference-home-requested-entry-coverage) | [Navigation-only walkthrough](../reference-home-walkthrough.md).
