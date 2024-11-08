# Table of Contents
- [Introduction](#introduction)


# Introduction <a name="introduction"></a>
The "HTTPCode_ELB_4XX_Count" metric in AWS is a crucial metric for monitoring the health and behavior of your Elastic Load Balancer (ELB). It counts the number of HTTP 4xx client error responses generated by the ELB, which can help identify issues related to client requests.

The API response contains the  number of HTTP 4xx status codes that the load balancer returns to clients.



This API is integrated into the AWS Application Loadbalancer in NetBrain. It corresponds with the `get_metric_data` function of the CloudWatch resource in the AWS REST API.





For more details about the AWS CloudWatch API, please refer to the following document: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch/client/get_metric_data.html

For more details about the HTTPCode_ELB_4XX_Count metric, please refer to the following document: https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-cloudwatch-metrics.html#load-balancer-metric-table:~:text=HTTPCode_ELB_4XX_Count