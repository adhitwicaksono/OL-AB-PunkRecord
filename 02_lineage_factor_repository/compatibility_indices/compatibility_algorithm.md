# Compatibility Algorithm

```text
MODULE : compatibility_index_calculator
VERSION: 0.1
STATUS : public-node visible
```

## Score Components

```text
compatibility_score =
    0.40 * sequence_similarity
  + 0.30 * trait_fit
  + 0.20 * carrier_fit
  - 0.10 * instability_penalty
```

## Ethics Gate Override

The compatibility score is not the final decision.

```text
if consent_status in [unclear, coerced_or_unclear, not_recorded]:
    ethics_gate = review_required

if autonomy_control_marker detected:
    ethics_gate = restricted

if memory_suppression or cyborg_conversion detected:
    ethics_gate = blocked

if authority_layer == sealed:
    ethics_gate = sealed
```

## Warning

```text
The algorithm can estimate biological fit.
It cannot grant moral permission.
```
