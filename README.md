This project contains the workload traces used in the simulations for the paper entitled "Virtual Machine Consolidation with Multiple Usage Prediction for Energy-Efficient Cloud Data Centers", which has been published to IEEE Transactions on Services Computing.

A set of the CPU and Memory utilization was created from the original Google Cluster Data (GCD) dataset (https://github.com/google/cluster-data). 

To create the CPU and the Memory utilization, the tasks of each job were aggregated by summing their CPU and Memory consumption every five minutes in a period of 24 hours. The dataset was extracted over the first ten days period (10 days May 2011) by filtering the utilization of CPU and memory from 5 to 90 percent, resulting in a total of 1,600 VMs.

Each txt file contains two columns:
- first column: CPU utilization (%)
- second column: Memory utilization (%)

Charactristics of the workload traces:
- CPU: 
    + Mean: 21.84
    + St. dev: 13.62
    + Median: 18
- Memory:
    + Mean: 19.55
    + St. dev: 16.66
    + Median: 12

When you use this dataset, please cite to the original Google cluster workload traces (https://github.com/google/cluster-data) and our paper mentioned above.
