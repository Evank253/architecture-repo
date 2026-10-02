# Relationship Model

The architecture records relationships between independent systems and their artifacts.

## Relationship vocabulary

- originated_from
- branched_from
- contains
- implements
- extends
- depends_on
- tests
- provides_evidence_for
- consumes_evidence_from
- supersedes
- interoperates_with
- composes_with
- produces_capability
- exposes_capability
- historical_evidence_from

## Important distinction

A relationship does not merge the entities it connects.

For example:

System A --exposes_capability--> Capability A1
Capability A1 --composes_with--> Capability B2
System B --provides--> Capability B2

This records a functional relationship while preserving the independent identity of System A and System B.

## Provenance requirement

Every asserted relationship should have a provenance reference whenever the relationship is evidence-derived.

Unverified relationships remain proposed rather than canonical.
