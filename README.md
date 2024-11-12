# SPALB 2024 Model Ensemble

Download SPALB 2024 assessment report:

- **Stock assessment of South Pacific albacore tuna in the western and central Pacific Ocean: 2024**\
  **[WCPFC-SC20-2024/SA-WP-02](https://meetings.wcpfc.int/node/23119)**

Download SPALB 2024 diagnostic model:

- Clone the **[alb-2024-diagnostic](https://github.com/PacificCommunity/ofp-sam-alb-2024-diagnostic)** repository or download as **[main.zip](https://github.com/PacificCommunity/ofp-sam-alb-2024-diagnostic/archive/refs/heads/main.zip)** file

Download SPALB 2024 model ensemble results:

- The **[alb-2024-model-ensemble](https://github.com/PacificCommunity/ofp-sam-alb-2024-model-ensemble)** repository includes a **[alb-2024_model_ensemble_results.zip](https://github.com/PacificCommunity/ofp-sam-alb-2024-model-ensemble/releases/download/alb_2024_model_ensemble_results.zip/alb_2024_model_ensemble_results.zip)** file

## Uncertainty

The SPALB 2024 assessment uncertainty was estimated using a Monte Carlo model ensemble approach in which 100 models incorporated uncertainty in average natural mortality, stock-recruitment steepness and
estimation error for individual models:

## Model ensemble results

The [alb-2024-model-ensemble-results.zip](https://github.com/PacificCommunity/ofp-sam-alb-2024-model-ensemble/releases/download/file/alb-2024-model-ensemble-results.zip) file contains all files necessary to run or browse the SPALB 2024 model ensemble.

The ensemble models are run from a par file, as described in the corresponding `doitall.sh` script.

The final par and rep files are consistently named `09.par` and `plot-09.par.rep` to facilitate harvesting results from across the 100 ensemble models.

## Estimating uncertainty

See also Section 8, Section 10.6 and Table 9 in the SPALB 2024 stock assessment [report](https://meetings.wcpfc.int/node/23119).

The script requires the FLR and FLR4MFCL packages:
```
install_github("flr/FLCore")
install_github("PacificCommunity/FLR4MFCL")
```
