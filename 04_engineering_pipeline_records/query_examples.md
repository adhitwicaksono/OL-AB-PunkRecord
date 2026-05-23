# Query Examples

## Query an engineering chain

```bash
python src/olab_punkrecord/query_pipeline.py --subject UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01

Pipeline chain:
SUBJ_BEAR → CLN_BEAR_A01 → UNIT_BEAR_01

Records:
CLP_006 clone_to_engineered_unit
DVA_006 accelerated_unit_maturation
TIN_001 enhanced_durability
TIN_002 restricted_autonomy_response
CMD_001 command hierarchy active

Warning:
Autonomy-control marker detected.
Route to Neural Identity Log and Ethics & Risk Monitor.
```

## Query a cyborg conversion

```bash
python src/olab_punkrecord/query_cybernetic.py --subject PX_BEAR_00
```

Expected output:

```text
Subject: PX_BEAR_00
Integration: CYB_001
Interface: neural_command_interface
Replacement level: extreme
Memory impact: suppressed
Autonomy impact: severe
Ethics gate: BLOCKED

Archive warning:
A converted body may still contain a person.
```

## Query command hierarchy

```bash
python src/olab_punkrecord/query_command.py --subject PX_BEAR_00
```

Expected output:

```text
Command ID: CMD_006
Authority: world_government_mandate
Priority: absolute
Override scope: total_platform_control
Autonomy penalty: 0.95
Ethics gate: BLOCKED

Warning:
Absolute command priority is an ethics alarm.
```
