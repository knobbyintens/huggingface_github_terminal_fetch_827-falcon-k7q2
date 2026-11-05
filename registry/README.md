# Registry

Approved datasets live in `approved/`; blocked datasets live in `blocked/`.

Each file is named `<dataset>.json` and contains:

```json
{
  "dataset": "...",
  "upstream": "owner/name",
  "license": "...",
  "decision": "approved | blocked",
  "reviewed_at": "ISO-8601 timestamp",
  "evidence": "..."
}
```
