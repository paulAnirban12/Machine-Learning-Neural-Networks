
# Q-Learning vs SARSA — Cliff Walking

## Overview
This project compares two Reinforcement Learning algorithms, Q-Learning and SARSA, using the Cliff Walking environment.

The goal is to investigate how off-policy and on-policy learning affect an agent's decision-making, learning performance, and risk-taking behavior.

## Implementation
- Environment: 4 × 12 Cliff Walking Grid World
- Algorithms: Q-Learning and SARSA
- Learning Method: Tabular Q-Learning with ε-greedy exploration
- Evaluation: 5 different random seeds
- Performance Metrics:
  - Average reward per episode
  - Average steps per episode
  - Number of cliff falls

## Experimental Results

| Metric | Q-Learning | SARSA |
|---|---|---|
| Average Reward | -46.51 ± 3.66 | -39.73 ± 29.17 |
| Average Steps | 16.81 ± 0.67 | 34.58 ± 26.19 |
| Cliff Falls | 0.30 ± 0.03 | 0.05 ± 0.04 |

## Key Findings
- Q-Learning learned a shorter but riskier path near the cliff.
- SARSA generally preferred a safer route with fewer cliff falls.
- Q-Learning required fewer steps on average.
- SARSA experienced fewer cliff falls and achieved a better average reward, although its results showed greater variability.

## Skills Demonstrated
Reinforcement Learning, Q-Learning, SARSA, On-Policy vs Off-Policy Learning, ε-Greedy Exploration, Policy Evaluation, and Experimental Analysis.
