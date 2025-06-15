# Scalability
*Scalability* is the ability of a [[data-intensive|system]] to cope with increased load.

Importantly, scalability is not one-dimensional; there are often many different places a system can be scaled.

Typically, we describe the load on a system with [[load_parameter|load parameters]], and then measure the system's performance with [[performance_metric|performance metrics]].

Often we talk about scaling up versus scaling out. In reality, good architectures use the most pragmatic combination of both.

An *elastic* system is one that can scale up and down automatically in response to load changes.