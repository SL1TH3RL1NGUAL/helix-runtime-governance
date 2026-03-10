cat << 'EOF' > GOVERNANCE/placeholder-credential.md
# Placeholder Credential Schema

Minimal governance credential for early-stage testing.

## Fields
- subject_id
- role
- branch
- key_ref
- valid_from
- valid_until
- issuing_authority

## Example
{
  "subject_id": "did:example:123",
  "role": "LEGISLATIVE",
  "branch": "LEGISLATIVE",
  "key_ref": "keystore://legislative/123",
  "valid_from": "2026-01-01T00:00:00Z",
  "valid_until": "2026-12-31T23:59:59Z",
  "issuing_authority": "LEGISLATIVE_MULTISIG"
}
EOF
