# LS-IQCQP 
## LS-IQCQP is a Local Search solver for large scale Binary Integer QCQP problem.
## Author: XiangHe and Shaowei Cai
#### Local Search is an incomplete algorithm that continuously improves the quality of solutions through a finite number of iterations within a cutoff time. After the cutoff period, it outputs the found optimal objective function value and solution set.





- To use the solver,  **run ./qpsolver cutoff_time(second) filename.lp**. 



-  BQCQP is the problem type LS-IQCQP can solve, and the ralated instances in the MINLPLIB (QPLIB) is located in the 'sonet' folder for **testing**.


-  Experiments are conducted on a server with Intel Xeon Platinum 8153 2.00GHz and 2048G RAM under the system CentOS 7.7.1908. we found the new primal bound of two instances within cutoff **300s**.


- "run.sh" is a simple example of using the solver.

  

