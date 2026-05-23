# Query Examples

## Query by subject

```bash
python src/olab_punkrecord/query_lineage_factor.py --subject UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01
Lineage Factor Record: LF_UNIT_BEAR_01
Template: SUBJ_BEAR
Record class: engineered
Lineage tags:
- LF_BUC_rare
- LF_DURABILITY_plus
- LF_CONTROL_lowautonomy

Risk:
CRITICAL autonomy marker detected.
Route to Ethics & Risk Monitor.
```

## Query by marker

```bash
python src/olab_punkrecord/query_marker.py --marker LF_CONTROL_lowautonomy
```

Expected output:

```text
Marker: LF_CONTROL_lowautonomy
Trait: low_autonomy_control
Domain: governance
Risk: CRITICAL

Linked subjects:
UNIT_BEAR_01

Archive warning:
If autonomy is engineered downward, the subject record must be escalated.
```

## Query compatibility

```bash
python src/olab_punkrecord/query_compatibility.py \
  --donor SUBJ_BEAR \
  --recipient UNIT_BEAR_01
```

Expected output:

```text
Compatibility ID: CMP_002
Score: 0.86
Ethics gate: RESTRICTED

Reason:
High technical compatibility with critical autonomy concern.
```
