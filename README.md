# A/B Testing Simulation: Click-Through Rate (CTR) Analysis

This project simulates and analyzes an A/B test comparing two versions of a website or advertisement to determine which version achieves a higher click-through rate (CTR).

## Objective
To understand the A/B testing process using a simulated dataset and evaluate whether Version B performs significantly better than Version A in terms of CTR.

## Tools & Libraries
- Python
- NumPy
- SciPy (stats)
- Matplotlib (visualization)

## Methodology
1. **Simulated Dataset**  
   - Version A: 10,000 visitors --> 10% click rate  
   - Version B: 10,000 visitors --> 12% click rate

2. **Statistical Testing**
   - Z-Test for two proportions to determine statistical significance
   - Confidence Intervals for CTR estimates

3. **Visualization**
   - CTR with 95% Confidence Intervals for both versions

## Insights
- The Z-test yielded a p-value of 0.0000, indicating a statistically significant difference between Version A and B.
- Version B had a higher CTR with a non-overlapping confidence interval.
- Therefore, Version B is the better-performing version and should be preferred based on this analysis.

## Interpretation (in German)
- Variante B hat eine signifikant höhere Klickrate (CTR) als Variante A. Da sich die Konfidenzintervalle nicht überschneiden und der p-Wert nahe 0 liegt, ist es sehr wahrscheinlich, dass die bessere Leistung von Variante B kein Zufall ist.

## What I Learned
- Basics of A/B testing, statistical significance, and interpretation
- How to simulate experimental data in Python
- Use of Z-test for comparing conversion rates
- Confidence interval estimation and visualization
