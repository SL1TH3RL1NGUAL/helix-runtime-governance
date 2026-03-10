cat << 'EOF' > RADIUS/operational-radius.md
# Operational Radius

Defines the spatial, temporal, and signal boundaries of jurisdiction.

## Components
- Spatial anchor (ENU origin)
- Signal envelope (allowed carriers, frequencies)
- Temporal validity window
- Forbidden external envelopes

## Enforcement
Runtime services must validate:
- Deployment location
- Signal source
- Envelope integrity
EOF

