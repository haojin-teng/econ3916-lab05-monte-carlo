# Monte Carlo Engine -- Probability & Simulation

## Objective
I used Monte Carlo simulation to estimate probabilities and portfolio risk measures, and to check how simulation error changes with the number of trials.

## Methodology
- I simulated 10,000 coin flips and plotted the running share of heads as the number of flips increased.
- I simulated 10,000 Monty Hall games and recorded how often switching doors won.
- I simulated a disease screening test on 100,000 people with a prevalence of 1%, a sensitivity of 95%, and a specificity of 90%, then calculated the share of positive tests that came from sick people.
- I computed Monte Carlo Value at Risk (VaR) and Expected Shortfall (ES) for a $1M portfolio.
- I estimated pi by simulation and checked that the Monte Carlo error shrinks like 1/sqrt(n).

## Key Findings
- Switching won [YOUR VALUE] of the 10,000 Monty Hall games.
- [YOUR VALUE]% of positive screening tests were from people who were sick.
- The error in my pi estimate shrank like 1/sqrt(n) as the number of samples grew.
- For the $1M portfolio, the 95% VaR was $[YOUR VALUE] and the 95% ES was $[YOUR VALUE].
