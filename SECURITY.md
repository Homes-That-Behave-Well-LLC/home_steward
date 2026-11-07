# Security and sensitive information

There is no runtime release, supported deployed version or configured service in this repository.
This policy does not certify any researched platform.

Do not put secrets, private correspondence, household source content or exploitable household
configuration into public issues. Use GitHub private vulnerability reporting if it is available.
Otherwise request a private reporting route from the repository maintainers without including the
sensitive details. A private route must be established before transmitting them.

Reports should identify the affected public document/proposal, authority boundary, threat model,
impact and sanitized reproduction. Never test a household/vendor endpoint or collect personal data
without separate authorization.

Qualification must examine authentication, least privilege, source/person isolation, egress, prompt
injection, delegated credentials, vendor support access, retention/lineage, export/erasure and backup
restore. Unknown is not PASS. Local networking alone does not create trust.

See [qualification gates](docs/platforms/qualification-gates.md) and
[derived-data lifecycle](docs/architecture/derived-knowledge-lifecycle.md).
