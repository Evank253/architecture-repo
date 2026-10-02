# System and Capability Catalog

## Status

INITIAL / EVIDENCE-BUILDING

This catalog is intentionally system-agnostic until each participating system is inspected and its identity, history, capabilities, and evidence are established.

## Required system record

Each participating system should have:

- system_id
- canonical_name
- repository
- status
- architectural_purpose
- predecessor_systems
- successor_systems
- capabilities
- mechanisms
- dependencies
- tests
- evidence
- known limitations
- authority_boundary
- provenance

## Capability record

A capability is tracked independently from the repository that contains it.

Required fields:

- capability_id
- name
- provider_system
- description
- inputs
- outputs
- dependencies
- evidence_refs
- qualification_state
- historical_lineage
- interface_status

## Qualification states

Use evidence-backed states only:

- DEMONSTRATED
- PARTIALLY_DEMONSTRATED
- EVIDENCE_INSUFFICIENT
- CONTRADICTED
- NOT_MEASURED
- UNABLE_TO_REPRODUCE
- REQUIRES_FURTHER_TESTING

No state should be assigned without a recorded basis.
