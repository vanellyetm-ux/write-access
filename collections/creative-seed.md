# Write Access — Creative Seed

This collection explores authorization as a visible, reviewable creative process. It does not grant or imply permissions beyond the repository's actual GitHub access controls.

## Story — The Gate That Asked Why
A gatekeeper was given a key that could open every door. Instead of turning it, the keeper asked who requested entry, what room was needed, and how the visit would be recorded. The key became less powerful and more trustworthy because every use had a purpose and a receipt.

## Art direction — Permission garden
A circular gate with three visible rings: PURPOSE, SCOPE, and APPROVAL. Beyond it, small labeled paths lead to READ, PROPOSE, REVIEW, and PUBLISH. No path is hidden; no single symbol implies universal access.

## Music sketch — “Scoped Key” (original)
A 4-note motif D–F–A–E, played once for request, twice softly for review, then resolved to D only after a full bar of silence. Keep the silence as part of the composition.

## Data representation (§) — Authorization request
```json
{
  "request_id": "permission-seed-001",
  "actor": "IDENTIFIED_ACTOR",
  "purpose": "DESCRIBE_ACTION",
  "scope": ["EXPLICIT_RESOURCE"],
  "requested_effect": "PROPOSE_ONLY",
  "approval": "PENDING",
  "receipt": null
}
```

## Curation rules
Repository permissions remain governed by GitHub. A proposal is not an approval, and a successful write is not proof of authorization for a different action. Never store credentials, tokens, or private keys in this repository.