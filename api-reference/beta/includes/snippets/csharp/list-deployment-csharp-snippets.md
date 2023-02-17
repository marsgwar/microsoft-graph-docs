---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var deploymentAudiences = await graphClient.Admin.Windows.Updates.DeploymentAudiences
	.Request()
	.GetAsync();

```