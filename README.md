# LS-IQCQP
# 

## LS-IQCQP is a Local Search solver for Binary QCQP problem.

#### Local Search is an incomplete algorithm that continuously improves the quality of solutions through a finite number of iterations within a cutoff time. After the cutoff period, it outputs the found optimal objective function value and solution set.





- To use the solver,  **run ./qpsolver cutoff_time(second) filename.lp.** 



- The "sonet" folder contains instances for **testing.**



- "run.sh" is a simple example of using the solver.

  

-  Experiments are conducted on a server with Intel Xeon Platinum 8153 2.00GHz and 2048G RAM under the system CentOS 7.7.1908. we found the new primal bound of two instances within cutoff **300s**

