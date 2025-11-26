# Azure Service Retirement Queries
These queries identify resources in your subscription(s) that have been announced for deprecation or retirement. 

## Retirements

| Service | Date | Query | More Info |
| --- | --- | --- | --- |
| App Service PHP 8.1 | Dec 31, 2025 | [App Service 8.1](php81.kql) | [PHP Version Support](https://www.php.net/supported-versions.php) | 
| Azure Storage TLS 1.0 & 1.1 | February 3, 2026 | [Storage TLS](storagetls.kql) | [Azure PaaS Blog](https://techcommunity.microsoft.com/blog/azurepaasblog/azure-storage---tls-1-0-and-1-1-retirement/4281140) |
| AKS - Windows Server 2019 | March 1, 2026 | [AKS 2019 Nodes](aksws2019.kql) | [Azure AKS Blog](https://techcommunity.microsoft.com/blog/containers/announcing-the-3-year-retirement-of-windows-server-2019-on-azure-kubernetes-serv/3777341) |
| Azure Monitor App Insights TLS 1.0 & 1.1 | March 1, 2026 | --- | [Identifying TLS 1.0 in your code](https://learn.microsoft.com/en-us/security/engineering/solving-tls1-problem#finding-and-fixing-tls-1.0-dependencies-in-code) |
| App Service PHP 8.2 | Dec 31, 2026 | [App Service 8.2](php82.kql) | [PHP Version Support](https://www.php.net/supported-versions.php) | 

