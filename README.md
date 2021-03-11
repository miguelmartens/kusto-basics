# kusto-basics
Learning the basics of Kusto Query Language (KQL)

This repository will serve as a very basic introduction to KQL, the language within the Azure Log Analytics environment.

**Resources**

* [Log Analytics demo environment](https://ms.portal.azure.com/#blade/Microsoft_Azure_Monitoring_Logs/DemoLogsBlade)

## Search

Search all columns in the Perf table for the value "K8SContainer"
```
Perf
| search "K8SContainer"
```