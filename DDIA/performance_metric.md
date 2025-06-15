# Performance Metrics
A *performance metric* is a numeric value that quantifies some aspect of the performance of a [[data-intensive|system]].

Different systems usually care about different performance metrics. For example:
- Batch processing systems like Hadoop care about throughput
- Online systems care about response time

Usually, it is better to look at performance metrics in percentiles than arithmetic means due to outliers. 

Percentiles are often used in service level objectives (SLOs) and service level agreements (SLAs) to define acceptable performance levels.

Related: [[scalability|Scalability]]