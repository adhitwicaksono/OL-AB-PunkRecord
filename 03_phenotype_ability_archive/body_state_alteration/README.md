# Body-State Alteration

```text
NODE : 03_phenotype_ability_archive/body_state_alteration
TYPE : body-form, tissue-state, neural-state, and carrier-mediated alteration records
LINK : artificial_abilities + engineering_pipeline_records
```

Body-state alteration records track transitions from one biological state to another.

## Main Files

```text
body_state_events.csv
body_state_constraints.yaml
state_transition_map.tsv
```

## Archive Rule

```text
State change must specify:
initial_state
altered_state
trigger
reversibility
stability
plausibility_class
review_status
```

## Warning

```text
A reversible transformation is not automatically safe.
An irreversible transformation is not automatically acceptable.
```
