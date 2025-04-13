# 2025-04-14

## Chapter
1 — Location and Variability Estimators

## Dataset
Structured Apache logs from LogHub  
Source: https://github.com/logpai/loghub/tree/master/Apache

## Concepts Studied
- Aggregation of log events by hour
- Central tendency: mean, median, trimmed mean (10%)
- Dispersion: standard deviation, IQR
- Percentile analysis: 95th percentile (p95)
- Distribution visualization: histogram, KDE, boxplot
- Outlier detection with IQR
- Categorical activity heatmaps

## Actions
- Used the `Hour` field to count hourly logs
- Calculated summary statistics to describe variability
- Visualized distribution to identify skewness and cauda longa
- Computed upper outlier bounds and flagged extreme hours
- Created a heatmap to classify hours into Low, Moderate, and High activity

## Conclusions
- Hourly log volume is highly variable and skewed
- Mean values were biased; median and p95 were more robust
- Heavy-tailed behavior confirmed by KDE and boxplot
- Categorical heatmaps enabled intuitive understanding of system pressure by time

## Observability Takeaways
- Averages should not be used alone to define alert thresholds
- p95 and IQR are better suited for resilience and anomaly detection
- Categorical encoding of log activity can simplify dashboards and improve cognitive ergonomics

## Next Steps
- Move beyond descriptive stats toward correlation and multivariate pattern discovery
