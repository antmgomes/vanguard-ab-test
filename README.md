1. Objective

Evaluate whether the new digital redesign (Test) performs better than the current design (Control).
Focus: completion rate, session time, step duration, error rate, and drop-off.

2. Data

Two files were concated:
df_web_data_1
df_web_data_2

And then merged with:
Experiment assignments
Client demographic info

Into df_master

Which was cleaned and sorted by session.

3. KPIs Measured

Completion Rate (%)
Average Session Time (min)
Average Time per Step (min)
Error Rate (%)
Drop-off Rate per Step (%)

These KPIs compare Control vs. Test.

4. Hypothesis Testing
H1 — Completion Rate
Test: Chi-Square Test
Result: p < 0.05 → Significant difference

H2 — Session Time
Test: Two-sample t-test
Result: p < 0.05 → Significant difference

5. Summary
The Test design shows statistically significant differences in completion and session time.
Drop-off and timing metrics reveal where users slow down or exit.
These KPIs feed into the Tableau dashboard.