
This repository contains supplementary materials for the manuscript:

> **A Data-Driven Global Health Classification for Dairy Cows Using Milk Mid-Infrared Spectra and Machine Learning**  
> Chen et al.

The files provide additional methods, figures, sensitivity analyses, and model-evaluation results for the unsupervised clustering of milk mid-infrared (MIR)-related traits and the supervised reconstruction of the resulting cluster labels.

## Files

### 1. Supplementary methods and figures

[`Supplemental_file_S1_Supplemently_Unsupervised_learning_and_Supervsied_learing_using_MIR.docx`](Supplemental_file_S1_Supplemently_Unsupervised_learning_and_Supervsied_learing_using_MIR.docx) (1.02 MiB)

This Word document contains two groups of supplementary analyses:

- **Unsupervised learning:** evaluation of the selected number of clusters (`K = 2-6`), comparison of Ward.D2 hierarchical clustering with k-means, sensitivity to removing two highly correlated traits, and reproducibility across cow- and herd-grouped subsets.
- **Supervised learning:** evaluation of random forest (RF) and partial least squares discriminant analysis (PLS-DA) models trained to reconstruct the three unsupervised cluster labels directly from MIR spectra, including record-, cow-, and herd-grouped cross-validation.

The document includes Supplementary Figures S1, S1.1-S1.4, S2, S2.1, and S2.2, together with the corresponding methods, results, and interpretation.

### 2. RF and PLS-DA result tables

[`Supplemental_file_S2_35_MIR_related_trait_models_RF_PLS_results.xlsx`](Supplemental_file_S2_35_MIR_related_trait_models_RF_PLS_results.xlsx) (3.68 MiB)

This Excel workbook provides consolidated performance metrics and stratified results for RF and PLS-DA models associated with the 35 MIR-related traits. It contains 15 worksheets:

| Worksheet | Description |
|---|---|
| `Summary` | Reader-oriented overview of cross-validation metrics, cluster-specific performance, and major stratification patterns. |
| `Belgian_dataset_test` | Belgian-dataset validation material organized by early, mid, and late lactation stages. |
| `Strata_Extremes` | Highest and lowest cluster proportions across stratification variables, with small-stratum indicators. |
| `Model_Overall` | Overall RF and PLS-DA performance for training, out-of-fold cross-validation, and holdout validation. |
| `Cluster_Metrics` | Cluster-specific precision, recall, specificity, F1 score, ROC AUC, PR AUC, and related measures. |
| `Fold_Summary` | Fold-level summaries, variability, ranges, and 95% confidence intervals. |
| `RF_vs_PLS` | Paired fold-level comparison of RF and PLS-DA across principal metrics. |
| `CV_Confusion` | Cross-validation confusion counts and row-normalized proportions. |
| `Validation_CM` | Confusion matrices for validation and out-of-fold predictions. |
| `Fold_Overall` | Overall performance metrics for each cross-validation fold. |
| `Fold_Cluster` | Cluster-specific performance metrics for each cross-validation fold. |
| `Strata_Summary` | Summary of cluster composition by breed, lactation stage, parity group, and production quartile. |
| `Breed_Overall` | Breed-specific overall model performance. |
| `Breed_Cluster` | Breed- and cluster-specific model performance. |
| `Strata_Distribution` | Detailed cluster distributions across breeds, lactation stages, parity groups, production quartiles, and herds. |

## Abbreviations

- **MIR:** milk mid-infrared
- **RF:** random forest
- **PLS-DA:** partial least squares discriminant analysis
- **DIM:** days in milk
- **OOF:** out-of-fold
- **ARI:** adjusted Rand index
- **NMI:** normalized mutual information

## How to use these files

1. Start with the Word document for the analytical rationale, methods, supplementary figures, and interpretation.
2. Open the Excel workbook and begin with the `Summary` worksheet.
3. Use `Model_Overall`, `Cluster_Metrics`, and `RF_vs_PLS` for the main model comparisons.
4. Use the fold-level, breed-level, and stratification worksheets for detailed inspection and secondary analyses.

GitHub may not display all Microsoft Office content directly in the browser. If a preview is unavailable, select the file and use **Download raw file**, then open it with Microsoft Word/Excel, LibreOffice, or another compatible application.

## Scope and reuse

These files contain supplementary figures, model-evaluation outputs, and aggregated or stratified results. They do not constitute a deposit of the underlying raw MIR spectra or all individual-record source data.

When using or referring to these materials, please cite the associated article. This README does not grant a separate reuse licence; reuse remains subject to the licence and terms of the final publication and repository.
