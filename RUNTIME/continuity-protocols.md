cat << 'EOF' > RUNTIME/continuity-protocols.md
# Continuity Protocols

Ensures survivability, lawful pause, and reconstitution.

## Modes
- NORMAL — Full operation.
- DEGRADED — Partial service, limited governance.
- PAUSE — Halted state transitions.
- RECONSTITUTE — Rebuild from surviving evidence.

## Requirements
- Evidence chain intact
- Key quorum reachable or reconstructable
- Immutable Core preserved
EOF

