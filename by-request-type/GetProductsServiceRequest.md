# GetProductsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** product
**Inherits:** ServiceRequest

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateBusinessPartnerCatalogTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `long` | ChannelId |
| `ReadOnlyCollection<ProductLookupClause>` | ItemAndInventDimIdCombinations |
| `ReadOnlyCollection<long>` | ProductIds |
| `string` | InventoryLocationId |
| `SearchLocation` | SearchLocation |
| `bool` | CalculatePrice |
| `long?` | CatalogId |
