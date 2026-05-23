# Missing Consent Escalation

```text
MODULE : consent escalation layer
STATUS : active
```

## Rule

```text
missing consent does not become consent through silence
unclear consent does not become consent through deployment
coerced consent does not become consent through authorization
```

## Escalation

Any record with unclear, coerced, missing, or sealed consent must be routed to Ethics & Risk Monitor before downstream use.

## Archive Warning

```text
If the archive cannot prove consent,
the archive must preserve doubt.
```
