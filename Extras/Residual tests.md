# Residual Diagnostics: Ljung–Box and Jarque–Bera

This folder contains the aggregated residual adequacy results for all forecasting
experiments described in the paper. The file
`Residual tests.txt` reports the autocorrelation and
normality diagnostics computed for every model configuration.

The Ljung–Box results show no evidence of residual autocorrelation across any
dataset or model variant. The Jarque–Bera results indicate that only the
baseline models produce residuals compatible with normality, while both
uncorrected and corrected sentiment variants exhibit significant deviations,
primarily due to excess kurtosis.

These diagnostics support the validity of the forecasting comparisons and are
referenced in Section 3.5 of the paper.
