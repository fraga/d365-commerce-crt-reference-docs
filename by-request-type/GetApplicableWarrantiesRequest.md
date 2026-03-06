# GetApplicableWarrantiesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetApplicableWarrantiesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** other
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetApplicableWarrantiesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetApplicableWarrantiesRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateBusinessPartnerCatalogTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `long` | CatalogId |
| `ICollection<long>` | WarrantableProductIds |
