## CloudWatch Agent for StatsD

* [cwagent-statsd.yaml](cwagent-statsd.yaml) provides the functionality that enables `StatsD`. It provides the CloudWatch Agent as a Sidecar to your application to receive StatsD metrics.

A default configuration is defined in a ConfigMap in the example YAML file. For more configuration options for StatsD, see [CloudWatch Agent StatsD Configuration](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Agent-custom-metrics-statsd.html)

### IAM permissions required by CloudWatch Agent for this functionality:
* CloudWatchAgentServerPolicy