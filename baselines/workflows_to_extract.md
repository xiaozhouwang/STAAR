## Workflows to extract

1. **staar_unrelated_glm** — `docs/STAAR_vignette.html` ("Analyzing the simulated data using STAAR" → "Unrelated samples")
- Inputs: STAAR package dataset `example` (genotype/maf/snploc), simulated covariates/annotations
- Key sentinels: `results_STAAR_O`, conventional test p-values, STAAR-S/B/A tables (first row), `num_variant`, null model coefficients

2. **staar_related_sparse_glmmkin** — `docs/STAAR_vignette.html` ("Related samples" → "Analyzing data using sparse GRM")
- Inputs: STAAR `example` dataset, simulated covariates/annotations, sparse kinship matrix
- Key sentinels: `results_STAAR_O`, conventional test p-values, STAAR-S/B/A tables (first row), `num_variant`, null model coefficients/variance

3. **staar_related_dense_glmmkin** — `docs/STAAR_vignette.html` ("Related samples" → "Analyzing data using dense GRM")
- Inputs: STAAR `example` dataset, simulated covariates/annotations, dense kinship matrix
- Key sentinels: `results_STAAR_O`, conventional test p-values, STAAR-S/B/A tables (first row), `num_variant`, null model coefficients/variance
