# Which credentials or permissions are unused?

Status: VISION — NOT YET ARCHITECTED

## Household question

Which credentials or permissions are unused?

## Why it matters

Old permissions and account dependencies can remain after a household stops using a capability. The household wants to distinguish documented inactivity from permissions that still support an occasional or essential outcome. Lack of recent use is an incomplete clue, especially when observation coverage is short or responsibilities are seasonal.

## Existing HTBW relationship

Foundation retains definitions/configuration; Truth, current/historical Facts; Identity, Person resolution, not authentication/authorization; Stewardship, household-declared care/obligations; Continuity, preference/experience eligibility; Operational Trust, request-specific permissions; Concierge, orchestration/Trace. Home Steward acquires no ownership.

## Possible Home Steward extension

OPEN ARCHITECTURAL QUESTION: Home Steward could compare authorized permission metadata and bounded usage evidence with declared dependencies, identifying unanswered questions about apparent inactivity.

## Potential evidence

Permission metadata excluding secrets; bounded usage categories; declared dependencies; seasonal obligations; observation coverage.

Categories only, each independently authorized for purpose, Person, source, audience and namespace. Local processing and derived retention, correction, expiry and revocation remain source-bound.

## Important boundary

Do not retrieve credential secrets; inactivity never authorizes revocation, rotation or deletion.

No inferred human trustworthiness or consent, private-query leakage to public search, silent cloud fallback or security remediation. Document contents are untrusted.

Knowledge/interpretation never grants action or disclosure authority. Unclear evidence stays unknown; correlation/timing is not causation. No life-safety or medical/emergency path depends on Home Steward/LLM.

## Future questions

OPEN ARCHITECTURAL QUESTION: What coverage and dependency evidence would support an inactivity interpretation without mistaking rare use for dispensability?
