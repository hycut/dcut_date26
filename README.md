# DCut, DATE'26

1. Download .zip-file.
2. Unzip and enter directory.
3. `make clean && make all`
4. `./network_test 1 nnet/ACASXU_run2a_1_1_batch_2000.nnet 0` to run property 1 on NN 1_1 (target output neuron 0).
5. `scripts` folder contains script to run all instances for all properties, outputs in .csv-format.

Requires OpenBLAS and Gurobi.

`export OPENBLAS_NUM_THREADS=1` to avoid threading issues with OpenBLAS.
