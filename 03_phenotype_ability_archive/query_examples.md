# Query Examples

## Query ability

```bash
python src/olab_punkrecord/query_ability.py --ability ABL_REPULSE
```

Expected output:

```text
Ability: ABL_REPULSE
Class: paramecia_like
Primary effect: force-like displacement of targets
Plausibility: BOUNDARY_CASE
Risk: CRITICAL

Route:
- body_state_alteration
- transfer_events
- plausibility_classification
- ethics_risk_monitor
```

## Query observed trait by subject

```bash
python src/olab_punkrecord/query_trait.py --subject UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01

Observed traits:
TR_UNIT_BEAR_001 enhanced_durability
TR_UNIT_BEAR_002 restricted_autonomy_response

Critical warning:
restricted_autonomy_response detected.
Route to Neural Identity Log and Ethics & Risk Monitor.
```

## Classify body-state alteration

```bash
python src/olab_punkrecord/classify_body_state.py --event BSA_007
```

Expected output:

```text
Event: BSA_007
Subject: PX_BEAR_00
Alteration: neural_behavioral_shift
From: autobiographical response
To: suppressed memory response
Review: BLOCKED

Archive warning:
This is an identity continuity crisis.
```
