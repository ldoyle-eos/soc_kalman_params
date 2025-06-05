# soc_kalman_params
Repository for Z3 Kalman Filter SoC algorithm parameters. The algorithm function definitions and testing scripts can be found [here](https://github.com/EosEnergyStorage/soc_kalman_filter). 

Each set of 3 files corresponds with a different module product version. The prefixes indicate the module version and the suffixes indicate the file purpose as follows:

* *_params.json - provides Kalman Filter behavioral parameters for the functions in z3_kalman_filter.py

* *_timeseries_pbu_unit_test.csv - provides table of values satisfying timeseries_unit_test.py test when corresponding parameter file is active

* *_subfunc_unit_test.csv - provides table of values satisfying sub_function_tests.py test when corresponding parameter file is active

# Change Log

## V1.4.0 - Z3.5.1 parameters established for v1.4 of SoC Algorithm

The outputs of functions in v1.4.0 of soc_kalman_filter using v1.4.0 of z3_5_1_params.json should be identical to v1.3.0 of soc_kalman_filter (excepting rounding errors)