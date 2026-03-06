# GetProductKitComponentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductKitComponentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** product
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.ProductKitService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ProductKitService.md)

## Properties

| Type | Name |
|------|------|
| `long` | ChannelId |
| `long` | KitMasterProductId |
| `bool` | RetrieveOnlyDefaultComponents |
| `IEnumerable<long>` | SlotIds |
| `bool` | SummarizeVariants |
| `long?` | ProductComponentId |
| `IEnumerable<ComponentInSlotRelation>` | SelectedComponents |
