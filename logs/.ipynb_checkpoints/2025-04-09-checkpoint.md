# 2025-04-14

## Chapter
1 — Location and Variability Estimators (continued)

## Dataset
Apache structured logs from LogHub  
Source: https://github.com/logpai/loghub/tree/master/Apache

## Concepts Studied
- Aggregation of log events by hour
- Central tendency: mean, median, trimmed mean (10%)
- Dispersion: standard deviation, IQR
- Percentile analysis: 95th percentile
- Robust estimators and their application in production systems

## Actions
- Loaded structured Apache logs directly from GitHub
- Parsed timestamps and extracted temporal dimensions (hour, day)
- Aggregated hourly log volumes to simulate system workload
- Calculated and compared summary statistics
- Visualized distributions using histograms and boxplots
- Interpreted skewness, variability and extremes in the data
- Related statistical estimators to alerting, SLOs and engineering use cases

## Extended Interpretation
- Mean overestimates due to extreme hourly peaks
- Median and trimmed mean better reflect the "typical" system behavior
- High IQR and std dev indicate unstable or bursty log generation
- p95 defines a clear upper bound for monitoring thresholds
- These estimators support resilient observability and alert systems

## Next Steps
- Advance to distribution shapes, tail behavior and probabilistic modeling
