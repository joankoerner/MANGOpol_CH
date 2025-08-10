# MANGOpol_CH
Data, code, and results from MANGOpol_CH
.
├── Code/
│   ├── MANGO_elecCH_cluster.py                       # Main model clustering script
│   ├── PMD_elecCH_cluster_min_imports.py             # Model execution script with minimal imports
│   ├── detailed_results_elec_200_128_BASE_OPT.xlsx   # Detailed outputs for BASE_OPT scenario
│   ├── detailed_results_elec_200_128_delayed_2.xlsx  # Detailed outputs for DELAY_1 scenario
│   └── detailed_results_elec_200_128_delayed_3.xlsx  # Detailed outputs for DELAY_2 scenario
│
├── Data/
│   ├── MANGOelec_conversion_CH.xlsx      # Conversion technology data (capacities, costs, retirements)
│   ├── MANGOelec_miscellaneous_CH.xlsx   # Miscellaneous parameters (carbon factors, discount rates, etc.)
│   ├── MANGOelec_storage_CH.xlsx         # Storage data (efficiency, capacity, lifetimes, costs)
│   ├── MANGOelec_time_series_8TD_CH.xlsx # Hourly/typical-day demand and renewable profiles
│   └── MANGOelec_MC_update.xlsx          # Updated MC data inputs
│
└── Results/
    ├── BASE_OPT.xlsx     # Aggregated results for BASE_OPT scenario
    ├── DELAYED_1.xlsx    # Aggregated results for DELAYED_1 scenario
    └── DELAYED_2.xlsx    # Aggregated results for DELAYED_2 scenario
