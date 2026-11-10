# Open questions

> Proposed governance baseline; awaiting Owner review. No answer is implied by a vendor feature.

## Public Framework alignment

**Resolved at the repository level by HTBW DL-153 (2026-11-10).** The public Framework's six stages
(Truth, Identity, Operational Trust, Stewardship, Continuity, Concierge) are correct. Foundation is
**Layer 0** of a BehavesWell Core implementation, not a seventh Framework stage.
[Updated relationship](../architecture/behaves-well-framework-relationship.md).
Remaining: how the public specification words three stages (Identity 02.01, Operational Trust
03.02/03.03, Continuity 05.01) is tracked at
[Core #215](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/215).
The earlier wording of this question (six versus seven) is retained in #1's history.

## Licensing

HTBW has no license; several sibling repositories use MIT. There is no consistent convention
sufficient to select this repository's license. All rights remain reserved pending an explicit
Owner choice. Which documentation/code licenses and contribution terms should apply?
Future HA Core dependencies require a separately licensed OSI-compatible client; this repository's
current public visibility does not satisfy that requirement.

## Source and derived governance

What fine-grained source/question taxonomy, policy record and enforcement mechanism should be adopted?
How do Foundation consent records, Identity lifecycle and Operational Trust policy coordinate scope?
Which derived representations are reconstructable? How does revocation/erasure propagate across
indexes, memory, paired clients, offline replicas, exports and restored backups? How do governed
holds and original-source retention interact without creating a new history/hold authority?

## Discovery and interface

What confirmation strength, attribution and conflict handling permits candidate relationship
promotion? What durable Foundation schema/transaction/versioning applies? What minimal provenance
supports explanation without raw content retention?
What governed transport, errors, timeout/cancellation and native HA integration surface should be adopted?

## Qualification and Reference Home

Issue #2 must finalize gates, evidence ratings, weighted criteria only after gates, candidate
lifecycle, compatibility schema and safe entry criteria. No weighting is approved.
Which locally enforceable configurations meet person/source isolation and vendor-exit needs?
Which maintenance/upgrade/security workload is acceptable at explicit Owner time cost?
What Reference Home synthetic-data plan, rollback, budget and acceptance are authorized later?

## Research workflow

#3/#4 may gather before #2 closure, not issue final outcomes before #2 Owner acceptance.
#5 supplies the software/DIY control baseline. Who maintains each future integration/client?
The Owner's Ghost inquiry is a possible evidence source only with authorized, publishable summaries;
private correspondence is not copied and no relationship is implied.
