# IndicMAG: A Multilingual Multidimensional Aggression Detection Benchmark

## Overview

IndicMAG is a multilingual benchmark dataset for multidimensional aggression content detection in Indian context. The dataset comprises **78,875 manually annotated social media posts** across four major Indian languages: **English**, **Hindi**, **Bengali**, and **Marathi**.

### Key Features

- **Multilingual**: Coverage of 4 major Indian languages with balanced representation
- **Multidimensional**: Annotations for aggression level, aggression type, and multiple social content categories
- **Large-scale**: 78,875 samples
- **Culturally-aware**: Reflects natural regional communication patterns and cultural contexts
- **Validated**: Rigorous statistical validation with computational verification methods

## Dataset Information

### Languages
- English (EN)
- Hindi (HI) 
- Bengali (BN)
- Marathi (MR)

### Total Dataset Size
- **Full Dataset**: 78,875 samples
- **Sample Test Set** (provided): 1,000 samples

## Annotation Schema

### Aggression Level
- **NAG** (Non-Aggressive)
- **CAG** (Covertly Aggressive)  
- **OAG** (Overtly Aggressive)

### Aggression Type
- **UNC** (Unclassified-N/A)
- **NTAG** (Non-threatening Aggression)
- **CAG** (Abuse)
- **PTH** (Physical Threat)
- **STH** (Sexual Threat)

### Cultural Content Categories

#### Gender
- **NGEN** (Not Gendered)
- **GEN** (Gendered Remarks)
- **GENT** (Gendered Threats)

#### Religious
- **NCOM** (Not Communal)
- **COM** (Communal Remarks)
- **COMT** (Communal Threats)

#### Caste
- **NCAS** (Not Casteist)
- **CAS** (Casteist Remarks)
- **CAST** (Casteist Threats)

#### Ethnicity
- **NETH** (Not Racist)
- **ETH** (Racist Remarks)
- **ETHT** (Racist Threats)

## Data Schema

### Sample Test Set Structure

The provided test set contains the following columns:

- `tid`: Tweet ID (anonymized)
- `text`: Tweet content (anonymized)
- `aggression_level`: NAG/CAG/OAG
- `aggression_type`: UNC/NtAG/CuAG/PTH/STH
- `gender_bias`: NGEN/GEN/GENT
- `religious_bias`: NCOM/COM/COMT
- `caste_bias`: NCAS/CAS/CAST
- `ethnicity_bias`: NETH/ETH/ETHT
- `lang`: EN/HI/BN/MR

### Sample Test Set Size
- **Total Sample Test Set**: 1000 samples
- **English**: 250 samples
- **Bengali**: 250 samples
- **Hindi**: 250 samples
- **Marathi**: 250 samples

## Data Anonymization

All personally identifiable information has been removed.


## Ethical Considerations

- **Privacy**: All content anonymized following best practices
- **Consent**: Data collected from public platforms with appropriate permissions
- **Responsible Use**: Dataset intended for research purposes only
- **Cultural Sensitivity**: Annotations reflect authentic patterns without amplification

