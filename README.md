# MRS_TOPMed
# Stress-Related and Monocyte-Specific Methylation Risk Scores Predict Coronary Heart Disease in Postmenopausal Women

## Discovery analyses performed in the Women's Health Initiative (WHI) cohort.
- Cox regression associating stress with CHD and MI
- Epigenome wide association study (EWAS)
- Calculation of MRS
- Cox regression associating MRS values with CHD and MI
- Tensor Composition Analysis (TCA)
- Permutation resampling analysis

"GREAT.R" - Gene set enrichment analysis using GREAT
"EWAS_catalogue_13_sites.R" - Generation of EWAS catalogue for 13 Bonferroni sites

## Generalization meta-analyses performed in the Jackson Heart Study (JHS) and Multi-Ethnic Study of Atherosclerosis (MESA) cohort data.
Found under path "JHS_MESA_meta_analysis/"

1. "Data_prep.R" - Data prep
2. "MRS_calculation.R" - Calculation of MRS
3. "Cox_meta_sex_interaction.R"
  - Cox regression associating MRS values with all CHD, hard CHD, and MI 
  - Cox regression test with sex interaction
4. "MRS_permutations.R"
  - Permutation resampling analysis
