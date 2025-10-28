This repository contains code and results for experiments on three classes of instances: **BBLIP**, **MKIP**, and **BLIPI**. Below is an overview of the files associated with each instance.


---


## BBLIP Instance


The **BBLIP** folder contains all codes and results for generating and running the **BBLIP** test instances.


1. **Running the Reformulations**
   - **`BBLIP_instances.py`**: Generates random test instances, saved in the file `BBLIP_instances.json`.
   - **`BBLIP_bounds.py`**: Calculate the required big-Ms, saved in the file `BBLIP_bounds.json`.
   - **`BBLIP_experiments.py`**: Runs tests on the generated instances, using `BBLIP_instances.json` and `BBLIP_bounds.json`, with results saved in `BBLIP_results.json`.
   - **`BBLIP_print_results.ipynb`**: A Python notebook for displaying the test results in `BBLIP_results.json`.


2. **Performance Gap Analysis**
   - **`BBLIP_ub_and_lb_L2.py`**: Computes the performance gap for reformulation L2, with results stored in `BBLIP_ub_and_lb_L2.json`.
   - **`BBLIP_ub_and_lb_L3.py`**: Computes the performance gap for reformulation L3, with results stored in `BBLIP_ub_and_lb_L3.json`.
   - **`BBLIP_print_ub_and_lb.ipynb`**: A Python notebook to display the performance gap results in `.json` files `BBLIP_results.json`, `BBLIP_ub_and_lb_L2.json`, and `BBLIP_ub_and_lb_L3.json`.


---


## MKIP Instance


In a parallel manner, the **MKIP** folder contains all codes and results for generating and running the **MKIP** test instances.


1. **Running the Reformulations**
   - **`MKIP_instances.py`**: Generates random test instances, saved in the file `MKIP_instances.json`.
   - **`MKIP_bounds.py`**: Calculate the required big-Ms, saved in the file `MKIP_bounds.json`.
   - **`MKIP_experiments.py`**: Runs tests on the generated instances, using `MKIP_instances.json` and `MKIP_bounds.json`, with results saved in `MKIP_results.json`.
   - **`MKIP_print_results.ipynb`**: A Python notebook for displaying the test results in `MKIP_results.json`.


2. **Performance Gap Analysis**
   - **`MKIP_ub_and_lb_L2.py`**: Computes the performance gap for reformulation L2, with results stored in `MKIP_ub_and_lb_L2.json`.
   - **`MKIP_ub_and_lb_L3.py`**: Computes the performance gap for reformulation L3, with results stored in `MKIP_ub_and_lb_L3.json`.
   - **`MKIP_print_ub_and_lb.ipynb`**: A Python notebook to display the performance gap results in `.json` files `MKIP_results.json`, `MKIP_ub_and_lb_L2.json`, and `MKIP_ub_and_lb_L3.json`.


---


## BLIPI Instance


Similarly, the **BLIPI** folder contains all codes and results for generating and running the **BLIPI** test instances.


1. **Running the Reformulations**
   - **`BLIPI_instances.py`**: Generates random test instances, saved in the file `BLIPI_instances.json`.
   - **`BLIPI_bounds.py`**: Calculate the required big-Ms, saved in the file `BLIPI_bounds.json`.
   - **`BLIPI_experiments.py`**: Runs tests on the generated instances, using `BLIPI_instances.json` and `BLIPI_bounds.json`, with results saved in `BLIPI_results.json`.
   - **`BLIPI_print_results.ipynb`**: A Python notebook for displaying the test results in `BLIPI_results.json`.


2. **Performance Gap Analysis**
   - **`BLIPI_ub_and_lb_L2.py`**: Computes the performance gap for reformulation L2, with results stored in `BLIPI_ub_and_lb_L2.json`.
   - **`BLIPI_print_ub_and_lb.ipynb`**: A Python notebook to display the performance gap results in `.json` files `BLIPI_results.json` and `BLIPI_ub_and_lb_L2.json`.


---
