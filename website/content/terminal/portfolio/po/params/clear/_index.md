```
usage: clear [-h]
```

Clear selected portfolio optimization models

```
optional arguments:
  -h, --help  show this help message (default: False)
```

Example:
```
2022 May 02, 05:51 (🦋) /portfolio/po/params/ $ ?
╭──────────────────────────────────────────────────────────────────────────────────────────── Portfolio - Portfolio Optimization - Parameters ────────────────────────────────────────────────────────────────────────────────────────────╮
│                                                                                                                                                                                                                                         │
│ Portfolio Risk Parameters (.ini or .xlsx)                                                                                                                                                                                               │
│                                                                                                                                                                                                                                         │
│ Loaded file: OpenBB_Parameters_Template v1.0.0.xlsx                                                                                                                                                                                     │
│                                                                                                                                                                                                                                         │
│     file          load portfolio risk parameters                                                                                                                                                                                        │
│     save          save portfolio risk parameters to specified file                                                                                                                                                                      │
│                                                                                                                                                                                                                                         │
│ Model of interest: maxsharpe                                                                                                                                                                                                            │
│                                                                                                                                                                                                                                         │
│     clear         clear model of interest from filtered parameters                                                                                                                                                                      │
│     set           set model of interest to filter parameters                                                                                                                                                                            │
│     arg           set a different value for an argument                                                                                                                                                                                 │
│                                                                                                                                                                                                                                         │
│ Parameters:                                                                                                                                                                                                                             │
│     historic_period         : 3y                                                                                                                                                                                                        │
│     log_returns             : 0                                                                                                                                                                                                         │
│     return_frequency        : d                                                                                                                                                                                                         │
│     max_nan                 : 0.05                                                                                                                                                                                                      │
│     threshold_value         : 0.3                                                                                                                                                                                                       │
│     nan_fill_method         : time                                                                                                                                                                                                      │
│     risk_free               : 0.003                                                                                                                                                                                                     │
│     significance_level      : 0.05                                                                                                                                                                                                      │
│     risk_measure            : MV                                                                                                                                                                                                        │
│     target_return           : -1                                                                                                                                                                                                        │
│     target_risk             : -1                                                                                                                                                                                                        │
│     expected_return         : hist                                                                                                                                                                                                      │
│     covariance              : hist                                                                                                                                                                                                      │
│     smoothing_factor_ewma   : 0.94                                                                                                                                                                                                      │
│     long_allocation         : 1                                                                                                                                                                                                         │
│     short_allocation        : 0                                                                                                                                                                                                         │
│                                                                                                                                                                                                                                         │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────── OpenBB Terminal ─╯
2022 May 02, 05:51 (🦋) /portfolio/po/params/ $ clear

2022 May 02, 05:51 (🦋) /portfolio/po/params/ $ ?
╭──────────────────────────────────────────────────────────────────────────────────────────── Portfolio - Portfolio Optimization - Parameters ────────────────────────────────────────────────────────────────────────────────────────────╮
│                                                                                                                                                                                                                                         │
│ Portfolio Risk Parameters (.ini or .xlsx)                                                                                                                                                                                               │
│                                                                                                                                                                                                                                         │
│ Loaded file: OpenBB_Parameters_Template v1.0.0.xlsx                                                                                                                                                                                     │
│                                                                                                                                                                                                                                         │
│     file          load portfolio risk parameters                                                                                                                                                                                        │
│     save          save portfolio risk parameters to specified file                                                                                                                                                                      │
│                                                                                                                                                                                                                                         │
│ Model of interest:                                                                                                                                                                                                                      │
│                                                                                                                                                                                                                                         │
│     clear         clear model of interest from filtered parameters                                                                                                                                                                      │
│     set           set model of interest to filter parameters                                                                                                                                                                            │
│     arg           set a different value for an argument                                                                                                                                                                                 │
│                                                                                                                                                                                                                                         │
│ Parameters:                                                                                                                                                                                                                             │
│     historic_period         : 3y                                                                                                                                                                                                        │
│     log_returns             : 0                                                                                                                                                                                                         │
│     return_frequency        : d                                                                                                                                                                                                         │
│     max_nan                 : 0.05                                                                                                                                                                                                      │
│     threshold_value         : 0.3                                                                                                                                                                                                       │
│     nan_fill_method         : time                                                                                                                                                                                                      │
│     risk_free               : 0.003                                                                                                                                                                                                     │
│     significance_level      : 0.05                                                                                                                                                                                                      │
│     technique               : maxsharpe                                                                                                                                                                                                 │
│     risk_measure            : MV                                                                                                                                                                                                        │
│     target_return           : -1                                                                                                                                                                                                        │
│     target_risk             : -1                                                                                                                                                                                                        │
│     expected_return         : hist                                                                                                                                                                                                      │
│     covariance              : hist                                                                                                                                                                                                      │
│     smoothing_factor_ewma   : 0.94                                                                                                                                                                                                      │
│     long_allocation         : 1                                                                                                                                                                                                         │
│     short_allocation        : 0                                                                                                                                                                                                         │
│     risk_aversion           : 1                                                                                                                                                                                                         │
│     amount_portfolios       : 100                                                                                                                                                                                                       │
│     random_seed             : 123                                                                                                                                                                                                       │
│     tangency                : 0                                                                                                                                                                                                         │
│     risk_parity_model       : A                                                                                                                                                                                                         │
│     penal_factor            : 1                                                                                                                                                                                                         │
│     equilibrium             : 1                                                                                                                                                                                                         │
│     optimize                : 1                                                                                                                                                                                                         │
│     co_dependence           : pearson                                                                                                                                                                                                   │
│     cvar_simulations_losses : 100                                                                                                                                                                                                       │
│     cvar_simulations_gains  : 100                                                                                                                                                                                                       │
│     cvar_significance       : 0.05                                                                                                                                                                                                      │
│     linkage                 : single                                                                                                                                                                                                    │
│     amount_clusters         : 10                                                                                                                                                                                                        │
│     max_clusters            : 10                                                                                                                                                                                                        │
│     amount_bins             : KN                                                                                                                                                                                                        │
│     alpha_tail              : 0.05                                                                                                                                                                                                      │
│     leaf_order              : 1                                                                                                                                                                                                         │
│     objective               : MinRisk                                                                                                                                                                                                   │
│                                                                                                                                                                                                                                         │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────── OpenBB Terminal ─╯
```