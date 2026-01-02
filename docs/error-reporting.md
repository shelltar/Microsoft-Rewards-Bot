# Error Reporting

Automatically sends anonymized error reports to help improve the project.

## Configuration

In `src/config.jsonc`:

```jsonc
{
  "errorReporting": {
    "enabled": true  // Set to false to disable
  }
}
```

## Privacy

- No sensitive data sent (emails, passwords, tokens, paths are redacted)
- Only genuine bugs reported (config errors filtered)
- Optional - can be disabled anytime

---
**[Back to Documentation](index.md)**