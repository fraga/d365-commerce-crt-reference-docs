# CommitDocumentOperationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitDocumentOperationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** other
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.DocumentOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.DocumentOperationService.md)

## Properties

| Type | Name |
|------|------|
| `Guid` | RequestId |
| `string` | OperationName |
| `string` | Document |
| `OperationInvocationPriority` | Priority |
| `bool` | IsAsyncCommit |
| `bool` | DisableQueueing |
