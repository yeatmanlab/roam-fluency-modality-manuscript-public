# Response modality study: Data cleaning and analysis code

This repository contains the R Markdown scripts for the data cleaning and analyses reported in the manuscript. The `data_cleaning/` scripts clean the data and compute the scores for both students and the adults samples. The `analysis/` scripts produce the tables and figures reported in the manuscript.

## Data cleaning

Students sample:

| Script | What it does |
|---|---|
| `cleaning_arf_calf.Rmd` | Removes RT control outlier trials, those who did not pass the RT control, and very fast (and, for FC, near-chance) responders; makes Figure S4 |
| `get_scores_df.Rmd` | Computes the task and RT control scores, split-half scores and RT control residuals, and adds the scores of the other measures (AlPaCa, PA, SWR, SRE) |

Adults sample:

| Script | What it does |
|---|---|
| `cleaning_prolific.Rmd` | Removes RT control outlier trials, those who did not pass the RT control, and very fast (and, for FC, near-chance) responders |
| `get_scores_prolific_df.Rmd` | Computes the task and RT control scores, split-half scores and RT control residuals |


## Analysis

| Script | Produces |
|---|---|
| `exclusion_analysis.Rmd` | Table 4 |
| `descriptive_analysis.Rmd` | Tables 5 and 7, Figures 3 and 4; Tables S9.7 and S9.9, Figures S9.1 and S9.2 |
| `reliability_analysis.Rmd` | Table 1, RT control reliability, Tables S7.1-S7.3; Tables S9.1-S9.4 |
| `correlation_analysis.Rmd` | Table 2 and the corrected correlations; Table S9.5 |
| `other_apps_comparison.Rmd` | Table 3 and the Fisher's z-tests; Table S9.6 |
| `regression_analysis.Rmd` | Table 6 and Table S6; Table S9.8 |
| `descriptives_other_apps.Rmd` | Table S3, Figure S3, Table S8, Figure S8 |
| `prolific_data_analysis.Rmd` | Adult rows of Tables 1 and 7 (and S9.1 and S9.9), Supplement 5 |
