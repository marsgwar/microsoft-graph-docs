---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)


result, err := graphClient.IdentityGovernance().LifecycleWorkflows().DeletedItems().WorkflowsById("workflow-id").MicrosoftGraphIdentityGovernanceRestore().Post(context.Background(), nil)


```