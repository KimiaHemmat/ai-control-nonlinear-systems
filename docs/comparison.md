# Comparison Framework

## Criteria

| Criterion | Description |
|----------|------------|
| Stability | Guaranteed vs empirical |
| Robustness | Sensitivity to noise/disturbance |
| Data Requirement | Amount of training data |
| Interpretability | Ease of understanding |
| Computation | Real-time feasibility |

## Comparison Table

| Method | Stability | Data | Interpretability | Robustness |
|--------|----------|------|------------------|------------|
| PID | High | None | High | Medium |
| MPC | High | Low | Medium | High |
| BO-PID | Medium | Low | Medium | Medium |
| SVM | Low | Medium | Low | Low |
| MLP | Low | High | Very Low | Low |

## Key Observations
- Classical methods dominate in reliability
- ML helps with tuning and modeling
- Deep learning struggles with guarantees