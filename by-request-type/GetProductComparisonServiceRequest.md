# GetProductComparisonServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductComparisonServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** product
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.ProductComparisonService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ProductComparisonService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateBusinessPartnerCatalogTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `long` | CatalogId |
| `long` | ChannelId |
| `IEnumerable<long>` | ProductIds |
