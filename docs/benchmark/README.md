# Benchmark

The throughput increases proportionally to the number of nodes in Kubernetes cluster, with negligible overhead from container initialization and network messaging.


| Benchmark \ System | Old Judge Girl | New Judge Girl |
| --- | --- | ---|
| Subset Sum <br> 40 submissions, 1 CPU| 3m 43s| 35s|
| Dot Product <br> 20 submissions, 1 GPU| 5m 48s| 3m 38s|
