# Guidelines for the C++ implementation of computing single-user MIMO capacity under per-antenna power constraint 

* DATE OF CURRENT VERSION (V1.0): Nov 2017 
* CONTENTS: C++ implementation of fixed point and alternating optimization algorithms for finding the capacity of a single user MIMO with per-antenna power constraint
  - main.cpp: Main C++ file contains the scenario and implementation of Algorithm 1 (Fixed point) and Algorithm 2 (Alternating optimization)
  - Snapshot_example
* RELATED PUBLICATION: 
T. M. Pham, R. Farrell and L. N. Tran, "Low-Complexity Approaches for MIMO Capacity with Per-Antenna Power Constraint," 2017 IEEE 85th Vehicular Technology Conference (VTC Spring), Sydney, Australia, 2017, pp. 1-7.
* REQUIREMENTS: Armadillo library must be available and configured properly. The version of the library in this implementation is Amardillo-7.400.2
* NOTICE:
  - The current code using C++11 was built and debugged on Netbeans IDE 8.1.
  - The implementation generates results for the covariance matrix, capacity, duality gap/ relative objective error, and number of iterations. One can then save and plot the data using any available software or scripts as an example in the snapshot.  
* BUG REPORTS: If you find any bug, please send your feedback to m.phamminhthuy@gmail.com.
* LICENSE: The code is licensed under the GPLv2.


If you use our code in your research and/or software, we would appreciate citations to the following paper:

T. M. Pham, R. Farrell and L. N. Tran, "Low-Complexity Approaches for MIMO Capacity with Per-Antenna Power Constraint," 2017 IEEE 85th Vehicular Technology Conference (VTC Spring), Sydney, Australia, 2017, pp. 1-7.



