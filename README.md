Code/
Contains the Python scripts for running the model and processing results:

MANGO_elecCH_cluster.py – Main model clustering script.

PMD_elecCH_cluster_min_imports.py – Model execution script with minimal imports.

detailed_results_elec_200_128_BASE_OPT.xlsx – Detailed outputs for the BASE_OPT scenario.

detailed_results_elec_200_128_delayed_2.xlsx – Detailed outputs for the DELAY_1 scenario.

detailed_results_elec_200_128_delayed_3.xlsx – Detailed outputs for the DELAY_2 scenario.

Data/
Contains the input datasets for the Swiss electricity system model:

MANGOelec_conversion_CH.xlsx – Conversion technology data (capacities, costs, retirements).

MANGOelec_miscellaneous_CH.xlsx – Miscellaneous parameters (import/export, carbon factors, discount rates, etc.).

MANGOelec_storage_CH.xlsx – Storage data (efficiency, capacity, lifetimes, costs).

MANGOelec_time_series_8TD_CH.xlsx – Hourly/typical-day demand and renewable generation profiles.

MANGOelec_MC_update.xlsx – Updated Monte Carlo data inputs.

Results/
Contains aggregated model outputs:

BASE_OPT.xlsx – Aggregated results for the BASE_OPT scenario.

DELAYED_1.xlsx – Aggregated results for the DELAY_1 scenario.

DELAYED_2.xlsx – Aggregated results for the DELAY_2 scenario.

Scenario Descriptions
BASE_OPT – Optimal policy implementation without delays.

DELAYED_1 – Policy intervention delayed by one period.

DELAYED_2 – Policy intervention delayed by two periods.

