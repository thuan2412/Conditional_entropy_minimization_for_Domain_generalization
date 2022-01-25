Conditional entropy invariant risk minimization for CS-CMNIST

Please run "sweep_train.py" to get the final result. There are some parameters that can be selected. For example, --test_val to control the tuning procedures, --env_seed to select the oracle model, --holdout_fraction to control the validation set. 

To reproduce the results from IRM, ERM, IB-IRM and IB-ERM, you need to change the name of algorithm or, just use the original code from https://github.com/ahujak/IB-IRM 

The checkpoints are not stored, and the final results will be printed after the whole run. 

Our code is based on the [this repo](https://github.com/ahujak/IB-IRM) at https://github.com/ahujak/IB-IRM.    