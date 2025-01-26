# BRIN_Internship
Type: Internship
## Introduction

1. A company is required to try to increase the interest of 01 investors to buy the company's shares.
2. Return and risk are factors that need to be considered in investing, especially stocks. The procedure in optimizing a portfolio includes choosing the right asset proportion to get the best portfolio.
3. In this project, quantum computing is applied in selecting the best assets for portfolio optimization. And a comparison of the computation results is carried out on USA and IDX assets.

---

## Method

### 1. QUBO Problem to Final Equation

To solve the QUBO equation with a quantum computer, we transform the components x ∈ {0, 1} into Pauli operators Z with z ∈ {−1, 1}. For details of the formula derivation that I did, you can see what I attached above.

### 2. VQE (Variational Quantum Eigensolver)

For the adaptation and application of this algorithm in the field of finance, a quantum computer simulator called Pennylane is used, which is a module that runs in the Python programming language that integrated with machine learning algorithm.

---

## Result/Conclusion

From the simulation using the variational quantum eigensolver (VQE) method carried out on both types of assets (USA and IDX), quite significant differences were obtained related to the simulation results of both. In the simulation of USA assets, the results obtained from the optimized ansatz and exact solution were in accordance and the results tended to match the asset graph on January 1, 2024 to August 26, 2024.
Different from the simulation on IDX assets. There were various discrepancies in the results obtained from the simulations carried out, both related to the discrepancy between the results obtained and the asset graph on January 1, 2024 to August 26, 2024, or the discrepancy between the results on the optimized ansatz and the exact solution. After making several changes to the values of the variables in carrying out the optimized ansatz simulation for IDX assets, no significant changes were found that made the results obtained in accordance with expectations.
Specifically for Indonesian assets, it is necessary to examine various other considerations that result in discrepancies in the simulation results. The considerations in question include issues occurring in the country, internal or external problems occurring in the company, and other factors that have a significant impact on the company and influence the value trend of these assets.
