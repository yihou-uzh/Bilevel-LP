This repository contains code and results for experiments on two classes of instances: **BBLIP** and **BLIPI**. Below is an overview of the files associated with each instance.


---


## BBLIP Instance


The **BBLIP** folder contains all codes and results for generating and running the test instances.


1. **Running the Reformulations**
   - **`BBLIP_test_instances.py`**: Generates random test instances, saved in the file `BBLIP_test_instances.json`.
   - **`BBLIP_run_tests.py`**: Runs tests on the generated instances, with results saved in `BBLIP_big_M.json` and `BBLIP_test_results.json`.
   - **`BBLIP_print_test_results.ipynb`**: A Jupyter notebook for displaying the test results in `BBLIP_test_results.json`.


2. **Performance Gap Analysis**
   - **`BBLIP_ub_and_lb_L2.py`**: Computes the performance gap for reformulation L2, with results stored in `BBLIP_ub_and_lb_L2.json`.
   - **`BBLIP_ub_and_lb_L3.py`**: Computes the performance gap for reformulation L3, with results stored in `BBLIP_ub_and_lb_L3.json`.
   - **`BBLIP_print_ub_and_lb.ipynb`**: Jupyter notebook to display the performance gap results in `.json` files.


---


## BLIPI Instance


In a parallel manner, the **BLIPI** folder contains all codes and results for generating and running the test instances.


1. **Running the Reformulations**
   - **`BLIPI_test_instances.py`**: Generates random test instances, saved in the file `BLIPI_test_instances.json`.
   - **`BLIPI_run_tests.py`**: Runs tests on the generated instances, with results saved in `BLIPI_big_M.json` and `BLIPI_test_results.json`.
   - **`BLIPI_print_test_results.ipynb`**: A Jupyter notebook for displaying the test results in `BLIPI_test_results.json`.


2. **Performance Gap Analysis**
   - **`BLIPI_ub_and_lb_L2.py`**: Computes the performance gap for reformulation L2, with results stored in `BLIPI_ub_and_lb_L2.json`.


---
