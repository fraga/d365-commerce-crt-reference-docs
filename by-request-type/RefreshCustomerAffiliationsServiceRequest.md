# RefreshCustomerAffiliationsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RefreshCustomerAffiliationsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** customer
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.RefreshCustomerAffiliationsServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.RefreshCustomerAffiliationsServiceRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `IList<SalesAffiliationLoyaltyTier>` | AffiliationLoyaltyTierLines |
| `IList<AffiliationLoyaltyTier>` | AffiliationLines |
| `string` | CustomerId |
| `CustomerStatus` | CustomerStatus |
