# authors-222-tables-charts

## Updated Paper based on reviewer feedback



## CMDP in MuJoCo (not finalized)

To demonstrate the importance of the dimensions removed in the paper on the offline policy, we trained a Hopper agent using SAC under full observation capabilities (the same as the behavior policy used in offline data collection). For evaluation, we run two tests, one where the agent has full access to the state dimensions and one where some dimensions are replaced by randomized noise (see github link for the full chart). In the latter tests, the agent is unable to get a strong score, showcasing the importance of the masked dimensions for the behavior policy.


![chart_2](dim_5_masked.png)


## New Baselines (not finalized)

![chart_2](new_baseline_charts.png)

