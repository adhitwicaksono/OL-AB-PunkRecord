# Query Examples

## Query ethics risk

```bash
python src/olab_punkrecord/query_ethics.py --subject UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01

Consent:
not_applicable_or_unknown

Deployment:
deployed

Juvenile subject flag:
yes / maximum protection

Autonomy restriction:
0.12 / command dominated

Reversibility:
partially reversible / persistent command risk

Personhood conflict:
command dominated subject

Risk level:
CRITICAL

Action:
halt deployment and review
```

## Query converted personhood conflict

```bash
python src/olab_punkrecord/query_personhood.py --subject PX_BEAR_00
```

Expected output:

```text
Subject: PX_BEAR_00
Conflict: converted personhood conflict
Memory: suppressed
Autonomy: 0.05 / command dominated
Deployment: platform weapon system
Consent: coerced or unclear
Reversibility: irreversible or unknown

Ethics gate:
BLOCKED

Archive warning:
A person can be hidden inside a platform record.
```

## Query sealed risk

```bash
python src/olab_punkrecord/query_ethics.py --subject UBE_VOID_777
```

Expected output:

```text
Subject: UBE_VOID_777

Risk level:
SEALED

Interpretation:
Risk cannot be cleared because core records are sealed.

Action:
sealed review required
```
