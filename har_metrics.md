**Table 1: Pairwise win rates of HAR vs. Baseline agents across dialogue quality metrics with Gemini-3.1-flash-lite judge)**

| Metric | HAR Wins | Baseline Wins | HAR Win% |
|---|---:|---:|---:|
| Dialogue Coherence | 15 | 11 | 57.7% |
| Communicative Efficiency | 13 | 14 | 48.1% |
| Role Fidelity | 22 | 4 | **84.6%** |
| **Overall** | **50** | **29** | **63.3%** |

---

**Table 2: Elo leaderboard averaged across all three dialogue quality metrics (k=16, Elo Δ from 1000 baseline; Gemini-3.1-flash-lite judge)**

| Model | Type | Avg Elo Δ | Win Rate | Matches |
|---|---|---:|---:|---:|
| HAR-1-Task-GRPO | **HAR** | **+44.9** | 86.7% | 15 |
| HAR-3-Task-GRPO | **HAR** | **+29.6** | 100.0% | 6 |
| HAR-3-Task-GRPO-Qwen-Think-Opponent | **HAR** | **+12.5** | 63.6% | 11 |
| HAR-1-Task-GRPO-Qwen-Think-Opponent | **HAR** | **−0.9** | 52.9% | 17 |
| RL-1-Task-GRPO-Qwen-Thought-Opponent | Baseline | −3.6 | 46.2% | 52 |
| RL-1-Task-GRPO | Baseline | −77.0 | 18.5% | 27 |
