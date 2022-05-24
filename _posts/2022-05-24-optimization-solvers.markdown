---
published: true
title: Optimization Solvers for Power Grids
layout: post
---

Chen et al(2021) suggest that a optimization solver may be hard to obtain good enough solutions a Day-Ahead(DA) SCUC problem
(as large as 50k binary variables and 15k transmission constraints) within available time. 
Thus, efforts are made from both sides: faster solvers and more efficient ad-hoc algorithms. 
Since the first release of the mathematical programming package CPLEX in 1988, the advancement in algorithm, 
along with the improvement in hardware, has speeded up the problem solving by 5.28 million times till 2004 (Bixby, 2012).
That has enabled more and more industries to embrace optimization solvers, including power grids. 
From the recent benchmarking results of Mittlemann (2022), the fastest commercial LP solver runs more than 90 times faster than 
a popular open-source one, and 20 times faster for MILP solvers. 





* Bixby, R. E. (2012). A brief history of linear and mixed-integer programming computation. Documenta Mathematica, 2012, 107-121.
* Mitllemann, H. (2022). http://plato.asu.edu/ftp/lpsimp.html (retrieved on 24 May, 2022)
* Chen, Y., Pan, F., Holzer J., Rothberg E., Ma, Y. and Veeramany, A. (2021) A high performance computing based market economics driven 
  neighborhood search and polishing algorithm for security constrained unit commitment. IEEE Transactions on Power Systems, 36(1), 292-302
