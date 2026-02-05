# Baseline Source

- **R repo**: https://github.com/xihaoli/STAAR
- **Commit**: 9db9dd504905b9f469146f670e5f6dbe3e08d01a
- **Extraction date**: 2026-02-05
- **Extracted by**: codex
- **Hardware capture**: `baselines/hardware.txt`

## Commands used

```bash
R CMD check . --no-manual 2>&1 | tee baselines/r_cmd_check.log
Rscript baselines/scripts/environment_capture.R
bash baselines/scripts/capture_hardware.sh
Rscript baselines/scripts/fingerprint_example_data.R
Rscript baselines/scripts/prepare_example_data.R
Rscript baselines/scripts/extract_unrelated_glm.R
Rscript baselines/scripts/extract_related_sparse_glmmkin.R
Rscript baselines/scripts/extract_related_dense_glmmkin.R
```

## Notes

- R version: 4.5.0 (2025-04-11)
- Seed used: 600 for all stochastic operations
- `R CMD check --no-manual` completed with 3 WARNINGs and 4 NOTEs (see `baselines/r_cmd_check.log`).
