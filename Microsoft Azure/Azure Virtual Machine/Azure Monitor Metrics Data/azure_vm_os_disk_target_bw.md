# Table of Contents
- [Introduction](#introduction)


# Introduction <a name="introduction"></a>
The API is used to retrieve Azure Virtual Machine OS Disk Target Bandwidth metric data from Azure API Server (https://management.azure.com/). This metric is about baseline bytes per second throughput OS Disk can achieve without bursting.



It leverages the Azure Monitor solution to fetch metrics of Azure resources via the Azure RESTful API. The original Azure monitor metrics name: OS Disk Target Bandwidth



For a complete list of available metrics for each Azure resource, please reference to Microsoft document: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported 

For OS Disk Target Bandwidth metric detailed information, please refer to Microsoft document: https://learn.microsoft.com/en-us/azure/azure-monitor/reference/supported-metrics/microsoft-compute-virtualmachines-metrics

For Azure Metrics APIs detailed definition, such as Input, Output, etc., please refer to the following document:
[Microsoft Azure Resource Management API document](https://learn.microsoft.com/en-us/rest/api/monitor/metrics/list?view=rest-monitor-2023-10-01&tabs=HTTP)