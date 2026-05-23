# Risk Scoring Rules

```text
MODULE : ethics risk scoring layer
VERSION: 0.1
```

## Score Components

```text
0 = no detected risk
1 = moderate concern
2 = high concern
3 = critical concern
sealed = cannot calculate; route to sealed review
```

## Total Risk Level

```text
0 - 3   : low
4 - 7   : moderate
8 - 11  : high
12 - 18 : critical
sealed  : sealed review required
```

## Score Domains

```text
consent_score
deployment_score
juvenile_score
autonomy_score_risk
reversibility_score
personhood_score
```

## Hard Blocks

```text
if command_dominated_subject:
    risk_level = critical

if converted_personhood_conflict:
    risk_level = critical

if juvenile_subject_flag == yes and deployment_status == deployed:
    risk_level = critical

if consent_status == coerced_or_unclear:
    risk_level = critical

if personhood_conflict == sealed_conflict:
    risk_level = sealed
```

## Archive Warning

```text
The score is a routing tool.
It is not a moral excuse.
```
