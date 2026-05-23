# OL-AB Punk Record

> **A fictional bioinformatics archive for lineage-factor research, engineered bodies, artificial abilities, and posthuman biology.**

Welcome to **OL-AB Punk Record**, a prototype biological information system designed to catalog experimental subjects, lineage-factor profiles, engineered phenotypes, artificial abilities, clone-derived identities, cybernetic modifications, neural identity records, and ethical risk flags.

This repository imagines how a high-level biotechnology research facility might organize biological data when life itself becomes readable, editable, transferable, programmable, and politically dangerous.

---

## Access Level

```text
SYSTEM        : OL-AB Punk Record
ARCHIVE TYPE  : Fictional Bioinformatics Database
STATUS        : Prototype / Educational Simulation
DATA CLASS    : Synthetic, fictional, non-human-readable until annotated
PRIMARY USE   : Science communication, biotechnology discussion, posthumanism mapping
WARNING       : Engineered-life records may contain severe ethical anomalies
```

---

## Core Question

If biology becomes editable, what should be recorded?

A simple genome database is not enough.

An engineered being is not only a sequence.  
It is also a body, a history, a memory, a legal status, a social identity, and possibly a person.

**OL-AB Punk Record** treats fictional biotechnology as a thought experiment:

> **Before asking whether we can engineer life, we must ask whether our database even knows what kind of life it is looking at.**

---

## System Overview

OL-AB Punk Record is organized around six major archives.

### 1. Subject Registry

Catalogs original individuals, clones, engineered units, cyborgs, experimental biological entities, and posthuman subjects.

Example records may include:

- original biological subjects
- clone-derived subjects
- engineered childlike units
- cyborg-converted subjects
- subjects with artificial ability transfer
- subjects with altered autonomy or memory status

---

### 2. Lineage Factor Repository

Stores genome-like sequences, variant profiles, trait annotations, donor templates, biological compatibility metadata, and intervention history.

In real biological terms, a "lineage factor" record may be imagined as a fictional composite of:

```text
genome + variants + epigenetic state + developmental program + phenotype metadata + intervention history
```

Example data types:

- FASTA-like sequence records
- VCF-like variant records
- donor-template metadata
- trait-associated annotations
- compatibility scores
- intervention logs

---

### 3. Phenotype & Ability Archive

Links observable traits, artificial abilities, body modifications, and biological plausibility scores.

The archive separates fictional abilities into broad interpretive classes:

| Ability class | Description | Biological analogy | Plausibility |
|---|---|---|---|
| `zoan_like` | Body-form transformation | developmental reprogramming | very low |
| `paramecia_like` | Specialized body property or external effect | tissue biomechanics / synthetic physiology | low to impossible |
| `logia_like` | Elemental body-state transformation | mostly non-biological physics fantasy | impossible |
| `transfer_like` | Ability transplantation or replication | gene therapy / cell therapy analogy | very low |
| `cybernetic_like` | Biological-mechanical integration | prosthetics, neural interface, cyborg biology | partially plausible |

---

### 4. Engineering Pipeline Records

Tracks experimental interventions and their biological consequences.

Possible pipeline modules:

- cloning protocol
- developmental acceleration
- artificial trait insertion
- cybernetic integration
- artificial ability transfer
- blood or carrier-system modification
- command hierarchy encoding
- biological stability monitoring

---

### 5. Neural Identity Log

Records memory status, autonomy score, behavioral control layers, personality retention, and consciousness-related metadata.

This archive asks whether a subject remains biologically alive, psychologically continuous, legally autonomous, and socially recognizable.

Example fields:

| Field | Meaning |
|---|---|
| `memory_status` | whether autobiographical memory is intact, fragmented, suppressed, or erased |
| `autonomy_score` | rough index of independent decision-making capacity |
| `command_override` | whether external command hierarchy exists |
| `personality_retention` | whether the original personality remains detectable |
| `identity_continuity` | whether the subject can plausibly be considered continuous with the original person |

---

### 6. Ethics & Risk Monitor

Flags consent issues, dual-use risk, autonomy restriction, biological instability, juvenile subject status, and posthuman personhood concerns.

This module does not ask only:

> "Did the experiment work?"

It also asks:

> "Should this experiment have existed?"

Example risk categories:

- unclear consent
- coerced consent
- military deployment
- memory/personality suppression
- engineered childlike subject
- restricted autonomy
- irreversible modification
- biological instability
- clone identity ambiguity
- weaponization of living beings

---

## Suggested Repository Structure

```text
OL-AB_Punk_Record/
├── README.md
├── LICENSE
├── CITATION.cff
├── pyproject.toml
│
├── data/
│   ├── subjects.csv
│   ├── engineered_units.csv
│   ├── fictional_abilities.csv
│   ├── trait_annotations.csv
│   ├── ethics_registry.csv
│   ├── sample_lineage_factor.fasta
│   └── lineage_factor_variants.vcf
│
├── data/ontology/
│   ├── fictional_biology_ontology.tsv
│   ├── ability_classes.tsv
│   └── ethics_terms.tsv
│
├── notebooks/
│   ├── 01_query_subject_database.ipynb
│   ├── 02_trait_matching_demo.ipynb
│   ├── 03_clone_identity_demo.ipynb
│   ├── 04_ethics_risk_scoring.ipynb
│   └── 05_ability_plausibility_classifier.ipynb
│
├── src/olab_punkrecord/
│   ├── __init__.py
│   ├── load_database.py
│   ├── query_subject.py
│   ├── score_ethics.py
│   └── classify_ability.py
│
├── docs/
│   ├── database_schema.md
│   ├── fictional_biology_mapping.md
│   ├── posthumanism_discussion_notes.md
│   └── archive_note.md
│
└── figures/
    ├── database_architecture.png
    └── lineage_factor_to_phenotype.png
```

---

## Example Data Tables

### `data/subjects.csv`

```csv
subject_id,subject_type,donor_template,status,notes
SUBJ_BEAR,original_human,None,archived,baseline biological subject with unusual lineage traits
SUBJ_HAWK,original_human,None,archived,baseline subject associated with enhanced combat phenotype
SUBJ_SNAKE,original_human,None,archived,baseline subject associated with affective-control phenotype
UNIT_BEAR_01,engineered_unit,SUBJ_BEAR,active,clone-derived engineered unit with modified autonomy
UNIT_HAWK_01,engineered_unit,SUBJ_HAWK,active,clone-derived engineered unit with combat optimization
UNIT_SNAKE_01,engineered_unit,SUBJ_SNAKE,active,clone-derived engineered unit with artificial ability phenotype
```

---

### `data/engineered_units.csv`

```csv
unit_id,template_subject,added_trait,ability_class,autonomy_score,memory_status,development_stage,ethics_flag
UNIT_BEAR_01,SUBJ_BEAR,enhanced_durability,repulsion_like,0.12,suppressed,juvenile,critical
UNIT_HAWK_01,SUBJ_HAWK,enhanced_combat_reflex,blade_like,0.35,unknown,juvenile,high
UNIT_SNAKE_01,SUBJ_SNAKE,affective_control,petrification_like,0.42,developing,juvenile,high
```

---

### `data/fictional_abilities.csv`

```csv
ability_id,ability_name,ability_class,primary_effect,biological_analogy,plausibility_score
ABL_REPULSE,repulsion-like ability,paramecia_like,force-like displacement of targets,biomechanics and mechanotransduction fantasy,very_low
ABL_ELASTIC,elastic body phenotype,paramecia_like,extreme tissue elasticity,extracellular matrix and polymer biomechanics fantasy,very_low
ABL_FIRE,fire-body phenotype,logia_like,combustion-like body state,non-biological physics fantasy,impossible
ABL_ANIMAL_FORM,animal transformation,zoan_like,body plan conversion,developmental reprogramming fantasy,very_low
ABL_PETRIFY,petrification-like effect,paramecia_like,body-state immobilization or mineralization,biomineralization fantasy,very_low
```

---

### `data/ethics_registry.csv`

```csv
record_id,unit_id,consent_status,military_use,autonomy_restriction,memory_modified,juvenile_subject,risk_level
ETH_001,UNIT_BEAR_01,unclear,yes,yes,yes,yes,critical
ETH_002,UNIT_HAWK_01,not_applicable_or_unknown,yes,yes,unknown,yes,high
ETH_003,UNIT_SNAKE_01,not_applicable_or_unknown,yes,yes,unknown,yes,high
```

---

## Example Synthetic Lineage-Factor Record

### `data/sample_lineage_factor.fasta`

```fasta
>SUBJ_BEAR|synthetic_lineage_factor|fictional_demo_sequence
ATGCGTACCGTTAACGATCGATCGTACCGATCGATGCTAGCTAGGCTAACCGTATCG
>UNIT_BEAR_01|synthetic_lineage_factor|engineered_demo_sequence
ATGCGTACCGTTAACGATCGATCGTACCGATCGATGCTAGCTAGGCTAACCGTATTA
```

---

## Example Variant Record

### `data/lineage_factor_variants.vcf`

```vcf
##fileformat=VCFv4.2
##source=OL-AB_Punk_Record_synthetic_demo
#CHROM POS ID REF ALT QUAL FILTER INFO
LF01 60 LF_VAR_001 C T . PASS TRAIT=enhanced_durability;EFFECT=fictional_trait_marker
LF01 61 LF_VAR_002 G A . PASS TRAIT=autonomy_restriction;EFFECT=fictional_control_marker
```

---

## Example Query

A future script may allow users to query engineered subjects:

```bash
python src/olab_punkrecord/query_subject.py --subject UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01
Template subject: SUBJ_BEAR
Subject type: engineered_unit
Added trait: enhanced_durability
Ability class: repulsion_like
Autonomy score: 0.12
Memory status: suppressed
Development stage: juvenile
Ethics flag: CRITICAL

Recommended discussion:
- posthuman personhood
- biological consent
- dual-use biotechnology
- clone-derived identity
- weaponization of engineered life
```

---

## Example Ethics Risk Output

A future ethics-scoring script may read metadata from `engineered_units.csv` and `ethics_registry.csv`.

```bash
python src/olab_punkrecord/score_ethics.py --unit UNIT_BEAR_01
```

Expected output:

```text
Subject: UNIT_BEAR_01

Risk level: CRITICAL

Detected concerns:
- restricted autonomy
- memory/personality suppression
- military deployment
- unclear consent
- juvenile engineered subject
- engineered identity derived from original subject

Recommended discussion:
posthuman personhood, biological consent, dual-use biotechnology,
clone identity, and weaponization of engineered life
```

---

## Fictional Biology Mapping

This repository treats fictional biotechnology as a layered model.

| Fictional concept | Possible scientific discussion |
|---|---|
| lineage factor | genome, epigenome, developmental program, cell identity |
| engineered soldiers | genome editing, developmental engineering, enhancement, coercion |
| clones | genetic identity vs personal identity |
| artificial abilities | phenotype engineering, synthetic biology, impossible traits |
| cyborg conversion | prosthetics, neural interface, biohybrid systems |
| memory alteration | neuroscience, connectomics, identity, autonomy |
| posthuman subjects | personhood, rights, consent, governance |

---

## Why Bioinformatics Matters Here

Before biology can be engineered, it must be read.

A fictional biotechnology empire would not only need wet-lab scientists. It would need:

- sequence databases
- variant annotation
- phenotype ontologies
- subject metadata
- intervention tracking
- risk scoring
- lineage comparison
- biological plausibility assessment
- reproducibility logs
- ethics and governance records

In short:

> **No database, no biotechnology empire.**

And perhaps more importantly:

> **No ethics layer, no trustworthy science.**

---

## Notebook Ideas

### `01_query_subject_database.ipynb`

Demonstrates how to load subject metadata and query specific engineered units.

### `02_trait_matching_demo.ipynb`

Demonstrates how fictional traits can be linked to biological analogies such as extracellular matrix remodeling, developmental reprogramming, or neural control.

### `03_clone_identity_demo.ipynb`

Compares genetic identity, developmental history, memory status, and autonomy to show why a clone is not automatically the same person.

### `04_ethics_risk_scoring.ipynb`

Builds a simple toy scoring system for consent, autonomy, military deployment, memory modification, and juvenile subject status.

### `05_ability_plausibility_classifier.ipynb`

Classifies fictional abilities into categories such as biologically plausible, speculative, extremely unlikely, or physically impossible.

---

## Minimum Viable Demo

The first version of this repository can be very small:

```text
README.md
data/
├── subjects.csv
├── engineered_units.csv
├── fictional_abilities.csv
└── ethics_registry.csv

notebooks/
└── 04_ethics_risk_scoring.ipynb
```

With only these files, the archive can already demonstrate the main idea:

> Biology is not only sequence data.  
> Engineered life requires phenotype, identity, intervention, and ethics metadata.

---

## Future Development

Possible future modules:

- toy phenotype ontology builder
- trait-to-gene analogy table
- synthetic lineage-factor FASTA generator
- artificial ability plausibility classifier
- clone identity comparison notebook
- ethics risk dashboard
- subject relationship network visualization
- fictional biotechnology timeline
- posthumanism discussion map

---

## Archive Rules

1. Do not treat fictional powers as real biological mechanisms.
2. Do not reduce identity to DNA sequence.
3. Do not describe clones as copies of persons.
4. Do not ignore autonomy, consent, and personhood.
5. Do not build a database that records power but forgets suffering.
6. Do not let engineering language erase the subject.

---

## Real-World Note

This repository is an educational science communication project developed for a public discussion on fictional biotechnology, bioinformatics, and posthuman biology.

It was prepared as a conceptual companion to the talk:

**“One Piece & Bioteknologi: Ketika Fiksi Menyentuh Realitas”**

The project is intended to help audiences explore how fictional concepts such as lineage factor, engineered bodies, cloning, artificial abilities, cybernetic modification, and posthuman identity can be connected to real scientific discussions in genomics, bioinformatics, synthetic biology, biotechnology ethics, and science communication.

This repository is not affiliated with, endorsed by, or connected to any official franchise, publisher, animation studio, or rights holder.

All fictional references are used only as conceptual inspiration for public science education.

---

## Suggested Citation

If you use or adapt this educational demo, please cite:

```text
Wicaksono, A. (2026). OL-AB Punk Record: A fictional bioinformatics archive for biotechnology and posthumanism science communication. Aether Biomics / OmicsLite educational demo.
```

---

## License

Recommended license: **MIT License** for code and **CC BY 4.0** for documentation and educational materials. 

If fictional references are expanded further, keep the repository free of official images, manga panels, anime screenshots, copyrighted logos, or unauthorized character artwork.
