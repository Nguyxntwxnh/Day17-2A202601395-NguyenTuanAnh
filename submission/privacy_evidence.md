# Privacy Drill Evidence (Forget & Verification)

Log output from `python -m src.forget --user-id minh-lab17 --verify-only`:

```text
Deleting user-scoped memory for 'minh-lab17'...
Redis keys deleted: 0
Zep user absent: True
Redis user keys remaining: 0
Shared semantic KB remains intact because it stores domain knowledge, not user PII.
```

Verification status:
- Zep user absent: True
- Redis user keys remaining: 0
- Consent & opt-in gate enforced via data/consent.json.
