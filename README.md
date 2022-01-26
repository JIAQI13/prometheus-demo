# prometheus-demo
* This project is based on this tutorial https://medium.com/google-cloud/prometheus-and-stackdriver-fb8f7524ece0
* Understand prometheus architecture: server, web UI and Alertmanager 
* Understand prometheus data model: Counters and gauges, Histograms and summaries
* Use gauges most of the time for straightforward time-series metrics.
* Use counters for things you know to increase monotonically, e.g., if you are counting the number of times something happens.
* Use histograms for latency measurements with simple buckets, e.g., one bucket for "under SLO" and another for "over SLO."
* Prometheus query selection
* The four golden signals of monitoring are latency, traffic, errors, and saturation.
* Add nodejs prometheus monitoring code
* Deploy monitoring to Prometheus on Kubernetes
* Review metrics with query
* learned instrumenting application with custom metrics, and how to use it to measure SLO compliance
