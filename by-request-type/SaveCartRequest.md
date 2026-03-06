# SaveCartRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveCartRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveCartRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.SaveCartRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Russia.SaveCartRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Triggers.SaveCartRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Triggers.SaveCartRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
- Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Triggers.SaveCartRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll)
- Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Triggers.SaveCartRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll)
- Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `Cart` | Cart |
| `CalculationModes?` | CalculationModes |
| `SearchLocation?` | ReturnTransactionSearchLocation |
| `TransactionOperationType` | OperationType |
| `bool` | IsGiftCardOperation |
| `bool` | IsTransactionResume |
| `SalesTransaction` | SalesTransaction |
