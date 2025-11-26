# Azure Service Retirement Queries
These queries identify resources in your subscription(s) that have been announced for deprecation or retirement. 

## Retirements

| Service | Date | Query | More Info |
| --- | --- | --- | --- |
| App Service PHP 8.1 | Dec 31, 2025 | [App Service 8.1](/queries/php81.kql) | [PHP Version Support](https://www.php.net/supported-versions.php) | 
| Azure Storage TLS 1.0 & 1.1 | February 3, 2026 | [Storage TLS](/queries/storagetls.kql) | [Azure PaaS Blog](https://techcommunity.microsoft.com/blog/azurepaasblog/azure-storage---tls-1-0-and-1-1-retirement/4281140) |
| AKS - Windows Server 2019 | March 1, 2026 | [AKS 2019 Nodes](/queries/aksws2019.kql) | [Azure AKS Blog](https://techcommunity.microsoft.com/blog/containers/announcing-the-3-year-retirement-of-windows-server-2019-on-azure-kubernetes-serv/3777341) |
| Azure Monitor App Insights TLS 1.0 & 1.1 | March 1, 2026 | --- | [Identifying TLS 1.0 in your code](https://learn.microsoft.com/en-us/security/engineering/solving-tls1-problem#finding-and-fixing-tls-1.0-dependencies-in-code) <br>*This requires ensuring that your connections do not use TLS 1.0 or 1.1.* |
| Application Gateway v1 | April 28, 2026 | [App Gateway v1](/queries/appgwv1.kql) | [App Gateway v1](https://azure.microsoft.com/en-us/updates?id=application-gateway-v1-will-be-retired-on-28-april-2026-transition-to-application-gateway-v2) | 
| App Service Node 20 LTS | April 30, 2026 | [Node 20 LTS](/queries/node20lts.kql)  | [App Service Node 20 LTS](https://azure.microsoft.com/en-us/updates?id=485072) <br>*This query currently identifies Linux-based App Service Plans only.* |
| VPN Gateway Non-AZ SKUs | September 30, 2026 | [VPN Gaateway AZ SKU](/queries/vpnaz.kql) | [VPN Gateway Non-AZ SKU](https://azure.microsoft.com/en-us/updates?id=vpngw1-5-non-az-skus-will-be-retired-on-30-september-2026) | 
| Application Insights URL Ping Tests | September 30, 2026 | [URL Ping Test](/queries/urlpingtest.kql) | [Ping Test Migration](https://learn.microsoft.com/en-us/azure/azure-monitor/app/availability?tabs=standard#types-of-availability-tests) |
| Azure API for FHIR | September 30, 2026 | --- | [API Migration](https://azure.microsoft.com/en-us/updates?id=azure-api-for-fhir-retirement) <br>*This requires migrating APIs in your apps.* |
| Azure Anomaly Detector | October 1, 2026 | [Azure Anomaly Detector](/queries/azanomalydetector.kql) | [Azure Anomaly Detector](https://azure.microsoft.com/en-us/updates?id=ai-services-anomaly-detector-will-be-retired-on-1-october-2026) |
| App Service PHP 8.2 | Dec 31, 2026 | [App Service 8.2](/queries/php82.kql) | [PHP Version Support](https://www.php.net/supported-versions.php) | 

