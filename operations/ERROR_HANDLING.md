# Error Handling

## Principle

Errors should be understandable to both users and technical operators.

## Error Categories

### Configuration Error

Example:

Required parameter is missing.

Action:

Prevent workflow activation.

---

### Authentication Error

Example:

Integration credentials expired.

Action:

Mark execution as failed and provide a clear remediation message.

---

### Temporary Integration Error

Example:

External API unavailable.

Action:

Retry according to retry policy.

---

### Permanent Error

Example:

Requested entity does not exist.

Action:

Stop execution and provide actionable error information.
