---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var events = await graphClient.Me.Events
	.Request()
	.OrderBy("createdDateTime")
	.Skip(20)
	.GetAsync();

```