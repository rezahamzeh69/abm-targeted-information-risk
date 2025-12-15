abm-targeted-information-risk

Overview
This repository provides a reproducible agent-based simulation framework
for the quantitative modeling of targeted information attacks and
decision-oriented risk in organizational settings.

The project models how misinformation propagates through multi-layer
organizational networks, how it affects employees’ beliefs and cognitive
states, and how these effects accumulate into managerial decision risk.

The framework integrates adaptive attackers, dynamic defense policies,
and Monte Carlo–based sensitivity analysis.

This implementation accompanies and operationalizes an academic study
on information warfare, organizational decision-making, and systemic risk.


Key Features
- Agent-Based Modeling (ABM)
  * Employees with heterogeneous beliefs, cognitive limits, and social behavior
  * Managerial decision-making under uncertainty and cognitive load

- Multi-layer Organizational Networks
  * Formal (hierarchical / official) communication network
  * Informal (social / trust-based) communication network

- Adaptive Adversary
  * Targeted information injection
  * Strategy adaptation based on observed outcomes

- Dynamic Defense Mechanisms
  * Training policies
  * Communication control
  * Risk-based activation thresholds

- Decision-Oriented Risk Metrics
  * Information contamination
  * Decision degradation
  * Structural vulnerability
  * Cognitive overload
  * Interaction-based risk aggregation

- Monte Carlo Simulation
  * Multiple stochastic runs
  * Sensitivity analysis over attack and defense parameters

- Reproducible Outputs
  * Time-series logs
  * Aggregated statistics
  * Phase diagrams and confidence intervals


Repository Structure
.
├── notebooks/
│   ├── 01_dataset_and_simulation.ipynb
│   ├── 02_monte_carlo.ipynb
│   ├── 03_analysis_and_plots.ipynb
│   └── 04_extract_and_reproduce.ipynb
│
├── data/
│   └── abm_risk_dataset/
│
├── docs/
│   └── paper_inputs/
│
├── README.txt
└── requirements.txt


Methodological Summary
At each simulation step:
1. The attacker selects targets based on network position and prior rewards.
2. Information propagates through formal and informal channels.
3. Employees update beliefs under cognitive and informational constraints.
4. Employees decide whether and how to share information.
5. Network connections adapt dynamically.
6. The manager aggregates signals under limited processing capacity.
7. A managerial decision is made under uncertainty.
8. Decision quality is evaluated against a latent reference state.
9. A decision-oriented risk index is computed.
10. The attacker adapts its strategy based on outcomes.
11. Defensive mechanisms activate when risk exceeds predefined thresholds.

Monte Carlo repetitions are used to estimate distributions, confidence
intervals, and phase transitions.


How to Run (Recommended: Google Colab)
1. Open and run the notebooks in order:
   - 01_dataset_and_simulation.ipynb
   - 02_monte_carlo.ipynb
   - 03_analysis_and_plots.ipynb

2. Each notebook is self-documented and executable cell-by-cell.

3. Outputs are saved automatically into scenario-specific or
   timestamped folders.

No external datasets are required.


Reproducibility
- All simulations are seed-controlled
- Configuration files are stored alongside outputs
- Monte Carlo runs are isolated to avoid overwriting
- Results can be regenerated directly from the source documents


Intended Use
This repository is intended for:
- Academic research in information security and decision science
- Graduate-level projects and theses
- Agent-based modeling of organizational risk
- Teaching simulation and Monte Carlo methods


