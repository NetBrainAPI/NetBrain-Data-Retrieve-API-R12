# Table of Contents
- [Overview](#overview)
- [Metric Info](#metric-info)
- [User-Defined Parameters](#user-defined-parameters)
- [Use Cases Example](#example)
    - [Use Case 1 -- Security Incident Detection](#example-1) 
    - [Use Case 2 -- Client Compatibility Issues](#example-2)
- [Reference](#reference)

# Overview <a name="overview"></a>
The <b>ClientTLSNegotiationErrorCount</b> is a metric that tracks the number of TLS negotiation errors encountered by an Network Load Balancer (NLB). By monitoring this metric, you can identify and troubleshoot issues related to client TLS connections, such as certificate misconfigurations or outdated client software.

# Metric Info <a name="metric-info"></a>
* <b>Metric Name</b>: ClientTLSNegotiationErrorCount
* <b>Namespace</b>: AWS/NetworkELB
* <b>Unit</b>: Count
* <b>Display Name in NetBrain</b>: Client TLS Negotiation Error Count

# User-Defined Parameters <a name="user-defined-parameters"></a>
* <b>Start Time / End Time</b>: Specify the time range for viewing data points. This is useful for historical analysis or monitoring recent trends. Default time range is last 24 hours.
* <b>Statistics</b>: Default value is Sum.
  * <b>Average</b>: The average number of TLS negotiation errors encountered by an Network Load Balancer.
  * <b>Sum</b>: The sum of the number of TLS negotiation errors encountered by an Network Load Balancer.
  * <b>Minimum</b>: Minimum of the number of TLS negotiation errors encountered by an Network Load Balancer.
  * <b>Maximum</b>: Maximum of the number of TLS negotiation errors encountered by an Network Load Balancer.
* <b>Period</b>: Default value is 3600 second.
  * <b>Recommended Values</b>:
    * <b>300 seconds</b> for real-time monitoring.
    * <b>3600 seconds</b> for broader trend analysis over longer durations.

# Use Cases Example <a name="example"></a>
## Use Case 1: Security Incident Detection <a name="example-1"></a>
A sudden spike in this metric could indicate a potential security attack, such as a denial-of-service attack or a man-in-the-middle attack. By monitoring this metric, one can quickly identify and respond to such threats.

## Use Case 2: Client Compatibility Issues <a name="example-2"></a>
When making changes to SSL/TLS certificates or configurations, an increase in TLS negotiation errors will occur. By monitoring this metric, one can identify and address any compatibility issues with clients.

# Reference <a name="reference"></a>
* <b>Metrics Details</b>: https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-cloudwatch-metrics.html
* <b>AWS CloudWatch Parameters</b>: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch/client/get_metric_data.html