# Rolling-horizon-based TMA multiple flights scheduler considering travel uncertainty

This scheduler is a closed-loop framework to provide conflict-free routing and scheduling solutions for Terminal Manoeuvring Area (TMA) multi-aircraft, with the aim to smooth the landing process and reduce the TMA congestion.

For more details, please find from paper: "Rolling-horizon-based TMA multiple flights routing
and scheduling considering travel uncertainty", submitted to Fifteenth USA/Europe Air Traffic Management Research and Development Seminar (ATM2025)

## Repository structure

Folder "exp1_computationTest" gives the first experiment results in the paper, targeting on computational time and cost quality analysis.

Folder "exp2_with_without_rolling_test" provides the second experiment results in the paper, including both numerical results and video animations.

Folder "exp3_monte_carlo_test" provides the third experiment results in the paper, aiming to compare the robustness between Gurobi-based MPC and search-based MPC.
