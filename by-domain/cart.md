# Cart

## Handlers (24)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| AddCartLineChargeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AddCartLineChargeRequest |
| AddCartLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AddCartLinesRequest |
| AddOrderInvoiceToCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AddOrderInvoiceToCartRequest |
| AddReturnCartLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AddReturnCartLinesRequest |
| CartService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetSalesTransactionsServiceRequest, GetCartServiceRequest, CalculateSalesTransactionServiceRequest, CalculateRefundableAmountsServiceRequest, CalculateEstimatedShippingAuthorizationAmountServiceRequest (+11) |
| CheckoutCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CheckoutCartRequest |
| CopyCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CopyCartRequest |
| CreateCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CreateCartRequest |
| GetCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCartRequest |
| GetProductsInCartLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetProductsInCartLinesRequest |
| OverrideCartLineChargeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | OverrideCartLineChargeRequest |
| OverrideCartLinePriceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | OverrideCartLinePriceRequest |
| ProcessCartWarrantiesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ProcessCartWarrantiesRequest |
| RemoveCartLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | RemoveCartLinesRequest |
| ResumeCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ResumeCartRequest |
| SaveCartLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveCartLinesRequest |
| SaveCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveCartRequest |
| SuspendCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SuspendCartRequest |
| TransferCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | TransferCartRequest |
| UpdateCartLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UpdateCartLinesRequest |
| UpdateCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UpdateCartRequest |
| ValidateCartForCheckoutRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateCartForCheckoutRequest |
| ValidateCartRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateCartRequest |
| VoidSuspendedCartsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | VoidSuspendedCartsRequest |

## Triggers (9)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| SaveCartRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | SaveCartRequest |
| SaveCartRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCartRequest |
| SaveCartRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCartRequest |
| SaveCartRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCartRequest |
| SaveCartRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | SaveCartRequest |
| SaveCartRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | SaveCartRequest |
| SaveCartVersionedDataRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | SaveCartVersionedDataRequest |
| ValidateCartForCheckoutRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | ValidateCartForCheckoutRequest |
| ValidateCartForCheckoutRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.MandatoryTaxGroupItaly.dll | ValidateCartForCheckoutRequest |
