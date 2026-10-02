# Evidence and Lineage

## Objective

Preserve the historical chain through which capabilities and architectural decisions emerged.

The preferred reconstruction is:

problem → experiment → observation → failure/success → mechanism → capability → evidence → subsequent system or capability

## Artifact record

Each artifact should retain, where available:

- artifact_id
- source
- repository
- path
- commit_or_version
- hash
- timestamp
- provenance
- architectural_purpose
- predecessor
- successor
- claims
- evidence_refs
- reproduction_state
- qualification_state
- lifecycle_state

## Lifecycle states

Examples:

- ACTIVE
- HISTORICAL
- EXPERIMENTAL
- EVIDENCE_ONLY
- DEPRECATED
- UNRESOLVED

Lifecycle state is not a capability qualification.

## Rule

An artifact may be architecturally important even when it is no longer active code.
