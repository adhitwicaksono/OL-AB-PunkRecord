# Query Examples

## Query neural identity

```bash
python src/olab_punkrecord/query_neural_identity.py --subject PX_BEAR_00
```

Expected output:

```text
Subject: PX_BEAR_00

Memory status:
suppressed

Autonomy:
0.05 / command dominated

Personality retention:
fragmented retention / trace

Command override:
absolute / total platform control

Identity continuity:
fractured

Ethics gate:
BLOCKED
```

## Query autonomy

```bash
python src/olab_punkrecord/query_autonomy.py --subject UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01
Final autonomy score: 0.12
Class: command dominated
Ethics gate: BLOCKED

Warning:
Command response is not consent.
```

## Query identity continuity

```bash
python src/olab_punkrecord/query_identity.py --subject CLN_SNAKE_A01
```

Expected output:

```text
Subject: CLN_SNAKE_A01
Reference: SUBJ_SNAKE
Continuity class: emergent new identity

Interpretation:
Template sequence exists, but personal memory is not inherited.
New memory and behavior are developing.
Route to protection review.
```
