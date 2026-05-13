# UKB-Hepatitis-Dyslipidemia-Codelists
This repository contains the clinical codelists used for identifying hepatitis and dyslipidemia cases within the UK Biobank (UKB) population.

**Methodology & Coding Strategy**:
Primary Identification: ICD-10 codes were initially identified through the OpenSAFELY platform (Nab et al., 2024).

**Hepatitis**

Included: Viral hepatitis conditions with chronic liver disease potential (e.g., Hepatitis B and C) and other chronic hepatitis-related conditions.

Excluded: Self-limiting conditions (Hepatitis A and E) and secondary hepatitis caused by drugs or other infections.

**Dyslipidemia**

Included: Diagnostic codes capturing hyperlipidemia-related conditions.

Excluded: Rare genetic lipid disorders that do not follow typical metabolic pathways.

**Code Mapping**

CTV3: Developed using the same diagnostic definitions as the ICD-10 selections.

ICD-9: Mapped from ICD-10 using “icd9_icd10” lookup tables.

Read Code Version 2: Converted from ICD-10 using the “read_v2_icd10” mappings from the all_lkps_maps_v4 dataset (UK Biobank).

**Contents:**

Dyslipidemia-codelist/: Contains ICD-9, ICD-10, CTV3, and Read2 codes for dyslipidemia.

Hepatitis codelist/: Contains ICD-9, ICD-10, CTV3, and Read2 codes for hepatitis.

**Usage**:
These lists were curated for a retrospective cohort study.

**Reference**:

Nab, L., Schaffer, A. L., Hulme, W., Devito, N. J., Dillingham, I., Wiedemann, M.,…Goldacre, B. (2024). OpenSAFELY: A platform for analysing electronic health records designed for reproducible research. Pharmacoepidemiology and Drug Safety, 33(6). https://doi.org/10.1002/pds.5815

UK Biobank. (n.d.-b). UK Biobank resource 592: Clinical coding classification systems and maps.
