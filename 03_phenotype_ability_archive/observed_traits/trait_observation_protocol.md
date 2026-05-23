# Trait Observation Protocol

```text
MODULE : observed_trait_recorder
VERSION: 0.1
```

## Required Observation Layers

```text
1. subject identity
2. registry class
3. observation context
4. measurement proxy
5. lineage-factor marker link
6. confidence level
7. plausibility class
8. ethics note
```

## Confidence Rules

```text
HIGH   : repeated observation + marker support + low ambiguity
MEDIUM : repeated observation or marker support, but mechanism uncertain
LOW    : limited observation, weak marker link, or unstable condition
UNKNOWN: record corrupted, sealed, or unreproducible
```

## Archive Warning

```text
A trait can be real while its explanation remains wrong.
```
