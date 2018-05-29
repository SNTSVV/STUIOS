# STUIOS

## Overview of the approach


Uncertainty in timing properties (e.g., detection time of external events) is a common reality in embedded software systems since these systems interact with complex physical environments.

Such time uncertainty leads to non-determinism. For example, as a result of time uncertainty, time-triggered operations may either generate di erent valid outputs across di erent executions, or experience failures (e.g., results not being generated in the expected time window) that occur only occasionally over many executions. For these reasons, time uncertainty makes the generation of e ective test oracles for timing requirements a challenging task.

To address the above challenge, we propose STUIOS (Stochastic Testing with Unique Input Output Se- quences), an approach for the automated generation of stochastic oracles for test cases that verify the capability of a software system to ful ll timing constraints in the presence of time uncertainty. Such stochastic oracles entail the statistical analysis of repeated test case executions based on test output probabilities predicted by means of statistical model checking. Results from two industrial case studies in the automotive domain demonstrate that this approach improves the fault detection e ectiveness of tests suites derived from timed automata, compared to traditional approaches.


## Case Studies and Empirical Results

The artifacts required to replicate the empirical results presented in the paper (case study systems, test suites, and faulty systems organized by research question) can be downloaded from the following GIT repositories
https://bitbucket.org/FPastore/stuios_casestudies_bodysense https://bitbucket.org/charles-wang/stuios_casestudies_hod
