# FilterOutAlreadyRefundedChargeLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FilterOutAlreadyRefundedChargeLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** pricing
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService.md)

## Properties

| Type | Name |
|------|------|
| `IEnumerable<ChargeLine>` | ChargeLines |
| `SalesTransaction` | OriginalTransaction |
| `decimal` | SalesLineNum |
