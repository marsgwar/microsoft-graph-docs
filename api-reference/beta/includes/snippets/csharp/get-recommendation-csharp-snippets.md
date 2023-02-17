---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var recommendation = await graphClient.Directory.Recommendations["{recommendation-id}"]
	.Request()
	.GetAsync();

```