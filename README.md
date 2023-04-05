# Multiple target tracking with external information

Author: Andrey Babushkin \<babusand@fit.cvut.cz\>

## Task description

The state-of-the-art multiple-target tracking (MTT) algorithms can be used to monitor several observed targets simultaneously. They are mostly not limited to permanently existing targets but also admit their random spawning and disappearance, misdetections, and false alarms. However, some targets may be temporarily or permanently hidden from detection due to the sensing principles. For instance, the primary active radars may not see targets that move at low altitudes. If there are other sensors that can provide any (external) information about these targets, it could be beneficial to incorporate this information.

## Goal

The aim of the thesis is to propose a framework fusing external information into the knowledge of the multiple-target tracking algorithm. The steps are as follows:

1. Study and describe a selected MTT algorithm, its working principles, advantages, and disadvantages.
2. Propose a method for fusing external information into the knowledge of the MTT algorithm.
3. Experimentally assess the feasibility of the resulting framework. That is, provide some simulation examples and evaluate the results.
4. Discuss the properties of the proposed framework, its performance, advantages and disadvantages. Suggest possible future research directions.

## References

- \[1\] Á. F. García-Fernández and B. -N. Vo, "Derivation of the PHD and CPHD Filters Based on Direct Kullback–Leibler Divergence Minimization," in IEEE Transactions on Signal Processing, vol. 63, no. 21, pp. 5812-5820, Nov.1, 2015, doi: 10.1109/TSP.2015.2468677.
- \[2\] C. Fantacci, B. -N. Vo, B. -T. Vo, G. Battistelli and L. Chisci, "Robust Fusion for Multisensor Multiobject Tracking," in IEEE Signal Processing Letters, vol. 25, no. 5, pp. 640-644, May 2018, doi: 10.1109/LSP.2018.2811750.
- \[3\] B. Ristic, B. -T. Vo, B. -N. Vo and A. Farina, "A Tutorial on Bernoulli Filters: Theory, Implementation and Applications," in IEEE Transactions on Signal Processing, vol. 61, no. 13, pp. 3406-3430, July1, 2013, doi: 10.1109/TSP.2013.2257765.
- \[4\] D. E. Clark, K. Panta and B. -n. Vo, "The GM-PHD Filter Multiple Target Tracker," 2006 9th International Conference on Information Fusion, Florence, Italy, 2006, pp. 1-8, doi: 10.1109/ICIF.2006.301809.
