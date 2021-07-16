# azureDockerWP
An azure quickstart template for docker-wordpress-mysql. Attempting a revision of [@akhilthomas011's AZ model](https://github.com/Azure/azure-quickstart-templates/tree/master/application-workloads/wordpress) as I was running into errors deploying their template.


How to write a [compile to Azure function](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button)
```
$url = "https://raw.githubusercontent.com/loreleim/azureDockerWP/main/azuredeploy.json"
[uri]::EscapeDataString($url)
```

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Floreleim%2FazureDockerWP%2Fmain%2Fazuredeploy.json)


## Error Research

[A note from late 2020 on the same database error](https://wordpress.org/support/topic/database-connection-error-for-azure-hosted-wordpress-sites/)
