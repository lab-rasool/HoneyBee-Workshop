## Survival Analysis C-Index Results (Cox Model)

| Modality | TCGA-ACC | TCGA-COAD | TCGA-KICH | TCGA-LIHC | TCGA-PAAD | TCGA-SKCM | TCGA-UCEC | TCGA-BLCA | TCGA-DLBC | TCGA-KIRC | TCGA-LUAD | TCGA-PCPG | TCGA-STAD | TCGA-UCS | TCGA-BRCA | TCGA-ESCA | TCGA-KIRP | TCGA-LUSC | TCGA-PRAD | TCGA-TGCT | TCGA-UVM | TCGA-CESC | TCGA-GBM | TCGA-LAML | TCGA-MESO | TCGA-READ | TCGA-THCA | TCGA-CHOL | TCGA-HNSC | TCGA-LGG | TCGA-OV | TCGA-SARC | TCGA-THYM |
|----------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|
| Clinical             | 0.883 ± 0.029 | 0.911 ± 0.018 | 0.882 ± 0.125 | 0.864 ± 0.027 | 0.757 ± 0.033 | 0.825 ± 0.014 | 0.936 ± 0.011 | 0.823 ± 0.012 | 0.705 ± 0.159 | 0.921 ± 0.014 | 0.826 ± 0.026 | 0.996 ± 0.007 | 0.831 ± 0.017 | 0.794 ± 0.101 | 0.920 ± 0.017 | 0.840 ± 0.036 | 0.929 ± 0.018 | 0.814 ± 0.024 | 0.933 ± 0.064 | 0.871 ± 0.194 | 0.844 ± 0.042 | 0.901 ± 0.019 | 0.702 ± 0.027 | 0.911 ± 0.019 | 0.542 ± 0.064 | 0.848 ± 0.122 | 0.989 ± 0.004 | 0.808 ± 0.080 | 0.837 ± 0.008 | 0.883 ± 0.013 | 0.747 ± 0.018 | 0.851 ± 0.021 | 0.978 ± 0.032 |
| Pathology            | 0.568 ± 0.069 | 0.463 ± 0.061 | 0.356 ± 0.095 | 0.586 ± 0.048 | 0.544 ± 0.063 | 0.468 ± 0.037 | 0.560 ± 0.082 | 0.557 ± 0.048 | 0.574 ± 0.177 | 0.489 ± 0.033 | 0.470 ± 0.071 | 0.277 ± 0.153 | 0.535 ± 0.058 | 0.523 ± 0.143 | 0.498 ± 0.058 | 0.494 ± 0.047 | 0.525 ± 0.073 | 0.524 ± 0.018 | 0.363 ± 0.152 | 0.237 ± 0.147 | 0.661 ± 0.111 | 0.512 ± 0.023 | 0.514 ± 0.023 | 0.540 ± 0.079 | 0.363 ± 0.102 | 0.333 ± 0.126 | 0.695 ± 0.168 | 0.262 ± 0.061 | 0.563 ± 0.035 | 0.553 ± 0.051 | 0.513 ± 0.062 | - | - |
| Radiology            | 0.513 ± 0.036 | 0.596 ± 0.036 | 0.640 ± 0.141 | 0.573 ± 0.043 | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
| Molecular            | 0.424 ± 0.097 | 0.524 ± 0.061 | 0.725 ± 0.173 | 0.543 ± 0.028 | 0.498 ± 0.044 | 0.493 ± 0.045 | 0.515 ± 0.019 | 0.501 ± 0.026 | 0.685 ± 0.253 | 0.552 ± 0.035 | 0.528 ± 0.048 | 0.314 ± 0.334 | 0.513 ± 0.030 | 0.415 ± 0.185 | 0.525 ± 0.066 | 0.611 ± 0.025 | 0.403 ± 0.125 | 0.539 ± 0.038 | 0.307 ± 0.222 | 0.243 ± 0.170 | 0.464 ± 0.098 | 0.543 ± 0.095 | 0.477 ± 0.018 | 0.563 ± 0.077 | 0.509 ± 0.063 | 0.480 ± 0.118 | 0.388 ± 0.185 | 0.293 ± 0.088 | 0.553 ± 0.029 | 0.556 ± 0.051 | 0.493 ± 0.046 | 0.525 ± 0.095 | 0.674 ± 0.200 |
| WSI                  | 0.413 ± 0.082 | 0.488 ± 0.097 | 0.521 ± 0.168 | 0.494 ± 0.052 | 0.479 ± 0.049 | 0.550 ± 0.048 | 0.495 ± 0.051 | 0.515 ± 0.053 | 0.566 ± 0.327 | 0.492 ± 0.023 | 0.517 ± 0.027 | 0.332 ± 0.281 | 0.469 ± 0.082 | 0.578 ± 0.101 | 0.458 ± 0.054 | 0.459 ± 0.071 | 0.549 ± 0.102 | 0.455 ± 0.045 | 0.455 ± 0.350 | 0.525 ± 0.173 | 0.605 ± 0.136 | 0.412 ± 0.107 | - | - | - | - | - | - | - | - | - | - | - |
| Multimodal (Concat)  | 0.667 ± 0.107 | 0.586 ± 0.044 | 0.671 ± 0.201 | 0.797 ± 0.039 | 0.707 ± 0.057 | 0.745 ± 0.020 | 0.721 ± 0.060 | 0.796 ± 0.015 | 0.470 ± 0.161 | 0.888 ± 0.009 | 0.680 ± 0.055 | 0.769 ± 0.385 | 0.654 ± 0.067 | 0.836 ± 0.070 | 0.769 ± 0.048 | 0.650 ± 0.040 | 0.644 ± 0.091 | 0.681 ± 0.037 | 0.228 ± 0.167 | 0.796 ± 0.164 | 0.854 ± 0.081 | 0.815 ± 0.032 | 0.578 ± 0.024 | 0.811 ± 0.040 | 0.418 ± 0.113 | 0.497 ± 0.072 | 0.956 ± 0.040 | 0.504 ± 0.202 | 0.769 ± 0.015 | 0.825 ± 0.013 | 0.655 ± 0.036 | 0.842 ± 0.032 | 0.983 ± 0.033 |
| Multimodal (Mean Pool) | 0.574 ± 0.094 | 0.551 ± 0.053 | 0.354 ± 0.097 | 0.608 ± 0.025 | 0.575 ± 0.051 | 0.596 ± 0.026 | 0.636 ± 0.027 | 0.655 ± 0.047 | 0.619 ± 0.275 | 0.692 ± 0.030 | 0.592 ± 0.064 | 0.367 ± 0.207 | 0.580 ± 0.083 | 0.732 ± 0.097 | 0.589 ± 0.043 | 0.552 ± 0.102 | 0.577 ± 0.069 | 0.542 ± 0.033 | 0.355 ± 0.145 | 0.667 ± 0.245 | 0.611 ± 0.169 | 0.566 ± 0.050 | 0.517 ± 0.028 | 0.680 ± 0.038 | 0.362 ± 0.096 | 0.340 ± 0.089 | 0.750 ± 0.149 | 0.262 ± 0.115 | 0.640 ± 0.020 | 0.624 ± 0.011 | 0.545 ± 0.036 | 0.746 ± 0.058 | 0.974 ± 0.034 |
| Multimodal (Kronecker) | 0.581 ± 0.130 | 0.574 ± 0.069 | 0.628 ± 0.225 | 0.747 ± 0.042 | 0.614 ± 0.040 | 0.627 ± 0.047 | 0.603 ± 0.059 | 0.709 ± 0.055 | 0.525 ± 0.152 | 0.728 ± 0.028 | 0.570 ± 0.020 | 0.623 ± 0.311 | 0.567 ± 0.035 | 0.654 ± 0.086 | 0.728 ± 0.030 | 0.514 ± 0.096 | 0.600 ± 0.053 | 0.564 ± 0.058 | 0.727 ± 0.156 | 0.542 ± 0.228 | 0.689 ± 0.100 | 0.600 ± 0.038 | 0.549 ± 0.036 | 0.769 ± 0.037 | 0.548 ± 0.083 | 0.683 ± 0.125 | 0.720 ± 0.134 | 0.565 ± 0.079 | 0.629 ± 0.052 | 0.623 ± 0.068 | 0.561 ± 0.040 | 0.625 ± 0.081 | 0.684 ± 0.143 |


## LaTeX Table

```latex
\begin{table}[htbp]
\centering
\caption{Survival Analysis C-Index Results (Cox Model) for Different Modalities Across TCGA Projects}
\label{tab:survival_cindex}
\resizebox{\textwidth}{!}{%
\begin{tabular}{lccccccccccccccccccccccccccccccccc}
\toprule
Modality & ACC & COAD & KICH & LIHC & PAAD & SKCM & UCEC & BLCA & DLBC & KIRC & LUAD & PCPG & STAD & UCS & BRCA & ESCA & KIRP & LUSC & PRAD & TGCT & UVM & CESC & GBM & LAML & MESO & READ & THCA & CHOL & HNSC & LGG & OV & SARC & THYM \\
\midrule
\multicolumn{34}{l}{\textit{Unimodal}} \\
Clinical & $0.883 \pm 0.029$ & $0.911 \pm 0.018$ & $0.882 \pm 0.125$ & $0.864 \pm 0.027$ & $0.757 \pm 0.033$ & $0.825 \pm 0.014$ & $0.936 \pm 0.011$ & $0.823 \pm 0.012$ & $0.705 \pm 0.159$ & $0.921 \pm 0.014$ & $0.826 \pm 0.026$ & $0.996 \pm 0.007$ & $0.831 \pm 0.017$ & $0.794 \pm 0.101$ & $0.920 \pm 0.017$ & $0.840 \pm 0.036$ & $0.929 \pm 0.018$ & $0.814 \pm 0.024$ & $0.933 \pm 0.064$ & $0.871 \pm 0.194$ & $0.844 \pm 0.042$ & $0.901 \pm 0.019$ & $0.702 \pm 0.027$ & $0.911 \pm 0.019$ & $0.542 \pm 0.064$ & $0.848 \pm 0.122$ & $0.989 \pm 0.004$ & $0.808 \pm 0.080$ & $0.837 \pm 0.008$ & $0.883 \pm 0.013$ & $0.747 \pm 0.018$ & $0.851 \pm 0.021$ & $0.978 \pm 0.032$ \\
Pathology & $0.568 \pm 0.069$ & $0.463 \pm 0.061$ & $0.356 \pm 0.095$ & $0.586 \pm 0.048$ & $0.544 \pm 0.063$ & $0.468 \pm 0.037$ & $0.560 \pm 0.082$ & $0.557 \pm 0.048$ & $0.574 \pm 0.177$ & $0.489 \pm 0.033$ & $0.470 \pm 0.071$ & $0.277 \pm 0.153$ & $0.535 \pm 0.058$ & $0.523 \pm 0.143$ & $0.498 \pm 0.058$ & $0.494 \pm 0.047$ & $0.525 \pm 0.073$ & $0.524 \pm 0.018$ & $0.363 \pm 0.152$ & $0.237 \pm 0.147$ & $0.661 \pm 0.111$ & $0.512 \pm 0.023$ & $0.514 \pm 0.023$ & $0.540 \pm 0.079$ & $0.363 \pm 0.102$ & $0.333 \pm 0.126$ & $0.695 \pm 0.168$ & $0.262 \pm 0.061$ & $0.563 \pm 0.035$ & $0.553 \pm 0.051$ & $0.513 \pm 0.062$ & - & - \\
Radiology & $0.513 \pm 0.036$ & $0.596 \pm 0.036$ & $0.640 \pm 0.141$ & $0.573 \pm 0.043$ & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - & - \\
Molecular & $0.424 \pm 0.097$ & $0.524 \pm 0.061$ & $0.725 \pm 0.173$ & $0.543 \pm 0.028$ & $0.498 \pm 0.044$ & $0.493 \pm 0.045$ & $0.515 \pm 0.019$ & $0.501 \pm 0.026$ & $0.685 \pm 0.253$ & $0.552 \pm 0.035$ & $0.528 \pm 0.048$ & $0.314 \pm 0.334$ & $0.513 \pm 0.030$ & $0.415 \pm 0.185$ & $0.525 \pm 0.066$ & $0.611 \pm 0.025$ & $0.403 \pm 0.125$ & $0.539 \pm 0.038$ & $0.307 \pm 0.222$ & $0.243 \pm 0.170$ & $0.464 \pm 0.098$ & $0.543 \pm 0.095$ & $0.477 \pm 0.018$ & $0.563 \pm 0.077$ & $0.509 \pm 0.063$ & $0.480 \pm 0.118$ & $0.388 \pm 0.185$ & $0.293 \pm 0.088$ & $0.553 \pm 0.029$ & $0.556 \pm 0.051$ & $0.493 \pm 0.046$ & $0.525 \pm 0.095$ & $0.674 \pm 0.200$ \\
WSI & $0.413 \pm 0.082$ & $0.488 \pm 0.097$ & $0.521 \pm 0.168$ & $0.494 \pm 0.052$ & $0.479 \pm 0.049$ & $0.550 \pm 0.048$ & $0.495 \pm 0.051$ & $0.515 \pm 0.053$ & $0.566 \pm 0.327$ & $0.492 \pm 0.023$ & $0.517 \pm 0.027$ & $0.332 \pm 0.281$ & $0.469 \pm 0.082$ & $0.578 \pm 0.101$ & $0.458 \pm 0.054$ & $0.459 \pm 0.071$ & $0.549 \pm 0.102$ & $0.455 \pm 0.045$ & $0.455 \pm 0.350$ & $0.525 \pm 0.173$ & $0.605 \pm 0.136$ & $0.412 \pm 0.107$ & - & - & - & - & - & - & - & - & - & - & - \\
\midrule
\multicolumn{34}{l}{\textit{Multimodal}} \\
(Concat) & $\mathbf{0.667 \pm 0.107}$ & $\mathbf{0.586 \pm 0.044}$ & $\mathbf{0.671 \pm 0.201}$ & $\mathbf{0.797 \pm 0.039}$ & $\mathbf{0.707 \pm 0.057}$ & $\mathbf{0.745 \pm 0.020}$ & $\mathbf{0.721 \pm 0.060}$ & $\mathbf{0.796 \pm 0.015}$ & $0.470 \pm 0.161$ & $\mathbf{0.888 \pm 0.009}$ & $\mathbf{0.680 \pm 0.055}$ & $\mathbf{0.769 \pm 0.385}$ & $\mathbf{0.654 \pm 0.067}$ & $\mathbf{0.836 \pm 0.070}$ & $\mathbf{0.769 \pm 0.048}$ & $\mathbf{0.650 \pm 0.040}$ & $\mathbf{0.644 \pm 0.091}$ & $\mathbf{0.681 \pm 0.037}$ & $0.228 \pm 0.167$ & $\mathbf{0.796 \pm 0.164}$ & $\mathbf{0.854 \pm 0.081}$ & $\mathbf{0.815 \pm 0.032}$ & $\mathbf{0.578 \pm 0.024}$ & $\mathbf{0.811 \pm 0.040}$ & $0.418 \pm 0.113$ & $0.497 \pm 0.072$ & $\mathbf{0.956 \pm 0.040}$ & $0.504 \pm 0.202$ & $\mathbf{0.769 \pm 0.015}$ & $\mathbf{0.825 \pm 0.013}$ & $\mathbf{0.655 \pm 0.036}$ & $\mathbf{0.842 \pm 0.032}$ & $\mathbf{0.983 \pm 0.033}$ \\
(Mean Pool) & $0.574 \pm 0.094$ & $0.551 \pm 0.053$ & $0.354 \pm 0.097$ & $0.608 \pm 0.025$ & $0.575 \pm 0.051$ & $0.596 \pm 0.026$ & $0.636 \pm 0.027$ & $0.655 \pm 0.047$ & $\mathbf{0.619 \pm 0.275}$ & $0.692 \pm 0.030$ & $0.592 \pm 0.064$ & $0.367 \pm 0.207$ & $0.580 \pm 0.083$ & $0.732 \pm 0.097$ & $0.589 \pm 0.043$ & $0.552 \pm 0.102$ & $0.577 \pm 0.069$ & $0.542 \pm 0.033$ & $0.355 \pm 0.145$ & $0.667 \pm 0.245$ & $0.611 \pm 0.169$ & $0.566 \pm 0.050$ & $0.517 \pm 0.028$ & $0.680 \pm 0.038$ & $0.362 \pm 0.096$ & $0.340 \pm 0.089$ & $0.750 \pm 0.149$ & $0.262 \pm 0.115$ & $0.640 \pm 0.020$ & $0.624 \pm 0.011$ & $0.545 \pm 0.036$ & $0.746 \pm 0.058$ & $0.974 \pm 0.034$ \\
(Kronecker) & $0.581 \pm 0.130$ & $0.574 \pm 0.069$ & $0.628 \pm 0.225$ & $0.747 \pm 0.042$ & $0.614 \pm 0.040$ & $0.627 \pm 0.047$ & $0.603 \pm 0.059$ & $0.709 \pm 0.055$ & $0.525 \pm 0.152$ & $0.728 \pm 0.028$ & $0.570 \pm 0.020$ & $0.623 \pm 0.311$ & $0.567 \pm 0.035$ & $0.654 \pm 0.086$ & $0.728 \pm 0.030$ & $0.514 \pm 0.096$ & $0.600 \pm 0.053$ & $0.564 \pm 0.058$ & $\mathbf{0.727 \pm 0.156}$ & $0.542 \pm 0.228$ & $0.689 \pm 0.100$ & $0.600 \pm 0.038$ & $0.549 \pm 0.036$ & $0.769 \pm 0.037$ & $\mathbf{0.548 \pm 0.083}$ & $\mathbf{0.683 \pm 0.125}$ & $0.720 \pm 0.134$ & $\mathbf{0.565 \pm 0.079}$ & $0.629 \pm 0.052$ & $0.623 \pm 0.068$ & $0.561 \pm 0.040$ & $0.625 \pm 0.081$ & $0.684 \pm 0.143$ \\
\bottomrule
\end{tabular}%
}
\end{table}
```


## Summary Statistics

### Best Performing Modality by Project (Cox Model)

- **TCGA-ACC**: Clinical (C-index: 0.883)
- **TCGA-COAD**: Clinical (C-index: 0.911)
- **TCGA-KICH**: Clinical (C-index: 0.882)
- **TCGA-LIHC**: Clinical (C-index: 0.864)
- **TCGA-PAAD**: Clinical (C-index: 0.757)
- **TCGA-SKCM**: Clinical (C-index: 0.825)
- **TCGA-UCEC**: Clinical (C-index: 0.936)
- **TCGA-BLCA**: Clinical (C-index: 0.823)
- **TCGA-DLBC**: Clinical (C-index: 0.705)
- **TCGA-KIRC**: Clinical (C-index: 0.921)
- **TCGA-LUAD**: Clinical (C-index: 0.826)
- **TCGA-PCPG**: Clinical (C-index: 0.996)
- **TCGA-STAD**: Clinical (C-index: 0.831)
- **TCGA-UCS**: Multimodal (Concat) (C-index: 0.836)
- **TCGA-BRCA**: Clinical (C-index: 0.920)
- **TCGA-ESCA**: Clinical (C-index: 0.840)
- **TCGA-KIRP**: Clinical (C-index: 0.929)
- **TCGA-LUSC**: Clinical (C-index: 0.814)
- **TCGA-PRAD**: Clinical (C-index: 0.933)
- **TCGA-TGCT**: Clinical (C-index: 0.871)
- **TCGA-UVM**: Multimodal (Concat) (C-index: 0.854)
- **TCGA-CESC**: Clinical (C-index: 0.901)
- **TCGA-GBM**: Clinical (C-index: 0.702)
- **TCGA-LAML**: Clinical (C-index: 0.911)
- **TCGA-MESO**: Multimodal (Kronecker) (C-index: 0.548)
- **TCGA-READ**: Clinical (C-index: 0.848)
- **TCGA-THCA**: Clinical (C-index: 0.989)
- **TCGA-CHOL**: Clinical (C-index: 0.808)
- **TCGA-HNSC**: Clinical (C-index: 0.837)
- **TCGA-LGG**: Clinical (C-index: 0.883)
- **TCGA-OV**: Clinical (C-index: 0.747)
- **TCGA-SARC**: Clinical (C-index: 0.851)
- **TCGA-THYM**: Multimodal (Concat) (C-index: 0.983)

### Multimodal vs Best Unimodal Performance

- **TCGA-ACC**: -24.4% (degradation)
- **TCGA-COAD**: -35.7% (degradation)
- **TCGA-KICH**: -23.9% (degradation)
- **TCGA-LIHC**: -7.8% (degradation)
- **TCGA-PAAD**: -6.6% (degradation)
- **TCGA-SKCM**: -9.8% (degradation)
- **TCGA-UCEC**: -22.9% (degradation)
- **TCGA-BLCA**: -3.3% (degradation)
- **TCGA-DLBC**: -12.2% (degradation)
- **TCGA-KIRC**: -3.6% (degradation)
- **TCGA-LUAD**: -17.7% (degradation)
- **TCGA-PCPG**: -22.8% (degradation)
- **TCGA-STAD**: -21.3% (degradation)
- **TCGA-UCS**: +5.2% (improvement)
- **TCGA-BRCA**: -16.4% (degradation)
- **TCGA-ESCA**: -22.6% (degradation)
- **TCGA-KIRP**: -30.7% (degradation)
- **TCGA-LUSC**: -16.3% (degradation)
- **TCGA-PRAD**: -22.1% (degradation)
- **TCGA-TGCT**: -8.6% (degradation)
- **TCGA-UVM**: +1.1% (improvement)
- **TCGA-CESC**: -9.6% (degradation)
- **TCGA-GBM**: -17.7% (degradation)
- **TCGA-LAML**: -11.0% (degradation)
- **TCGA-MESO**: +1.0% (improvement)
- **TCGA-READ**: -19.4% (degradation)
- **TCGA-THCA**: -3.4% (degradation)
- **TCGA-CHOL**: -30.0% (degradation)
- **TCGA-HNSC**: -8.0% (degradation)
- **TCGA-LGG**: -6.6% (degradation)
- **TCGA-OV**: -12.3% (degradation)
- **TCGA-SARC**: -1.0% (degradation)
- **TCGA-THYM**: +0.5% (improvement)


## Simplified Best Performance Table

| Project | Best Unimodal | C-Index | Best Multimodal | C-Index |
|---------|---------------|---------|-----------------|---------|
| TCGA-ACC | Clinical | 0.883 ± 0.029 | (Concat) | 0.667 ± 0.107 |
| TCGA-COAD | Clinical | 0.911 ± 0.018 | (Concat) | 0.586 ± 0.044 |
| TCGA-KICH | Clinical | 0.882 ± 0.125 | (Concat) | 0.671 ± 0.201 |
| TCGA-LIHC | Clinical | 0.864 ± 0.027 | (Concat) | 0.797 ± 0.039 |
| TCGA-PAAD | Clinical | 0.757 ± 0.033 | (Concat) | 0.707 ± 0.057 |
| TCGA-SKCM | Clinical | 0.825 ± 0.014 | (Concat) | 0.745 ± 0.020 |
| TCGA-UCEC | Clinical | 0.936 ± 0.011 | (Concat) | 0.721 ± 0.060 |
| TCGA-BLCA | Clinical | 0.823 ± 0.012 | (Concat) | 0.796 ± 0.015 |
| TCGA-DLBC | Clinical | 0.705 ± 0.159 | (Mean Pool) | 0.619 ± 0.275 |
| TCGA-KIRC | Clinical | 0.921 ± 0.014 | (Concat) | 0.888 ± 0.009 |
| TCGA-LUAD | Clinical | 0.826 ± 0.026 | (Concat) | 0.680 ± 0.055 |
| TCGA-PCPG | Clinical | 0.996 ± 0.007 | (Concat) | 0.769 ± 0.385 |
| TCGA-STAD | Clinical | 0.831 ± 0.017 | (Concat) | 0.654 ± 0.067 |
| TCGA-UCS | Clinical | 0.794 ± 0.101 | (Concat) | 0.836 ± 0.070 |
| TCGA-BRCA | Clinical | 0.920 ± 0.017 | (Concat) | 0.769 ± 0.048 |
| TCGA-ESCA | Clinical | 0.840 ± 0.036 | (Concat) | 0.650 ± 0.040 |
| TCGA-KIRP | Clinical | 0.929 ± 0.018 | (Concat) | 0.644 ± 0.091 |
| TCGA-LUSC | Clinical | 0.814 ± 0.024 | (Concat) | 0.681 ± 0.037 |
| TCGA-PRAD | Clinical | 0.933 ± 0.064 | (Kronecker) | 0.727 ± 0.156 |
| TCGA-TGCT | Clinical | 0.871 ± 0.194 | (Concat) | 0.796 ± 0.164 |
| TCGA-UVM | Clinical | 0.844 ± 0.042 | (Concat) | 0.854 ± 0.081 |
| TCGA-CESC | Clinical | 0.901 ± 0.019 | (Concat) | 0.815 ± 0.032 |
| TCGA-GBM | Clinical | 0.702 ± 0.027 | (Concat) | 0.578 ± 0.024 |
| TCGA-LAML | Clinical | 0.911 ± 0.019 | (Concat) | 0.811 ± 0.040 |
| TCGA-MESO | Clinical | 0.542 ± 0.064 | (Kronecker) | 0.548 ± 0.083 |
| TCGA-READ | Clinical | 0.848 ± 0.122 | (Kronecker) | 0.683 ± 0.125 |
| TCGA-THCA | Clinical | 0.989 ± 0.004 | (Concat) | 0.956 ± 0.040 |
| TCGA-CHOL | Clinical | 0.808 ± 0.080 | (Kronecker) | 0.565 ± 0.079 |
| TCGA-HNSC | Clinical | 0.837 ± 0.008 | (Concat) | 0.769 ± 0.015 |
| TCGA-LGG | Clinical | 0.883 ± 0.013 | (Concat) | 0.825 ± 0.013 |
| TCGA-OV | Clinical | 0.747 ± 0.018 | (Concat) | 0.655 ± 0.036 |
| TCGA-SARC | Clinical | 0.851 ± 0.021 | (Concat) | 0.842 ± 0.032 |
| TCGA-THYM | Clinical | 0.978 ± 0.032 | (Concat) | 0.983 ± 0.033 |
