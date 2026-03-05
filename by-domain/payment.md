# Payment

## Handlers (11)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| CalculateTenderDiscountRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CalculateTenderDiscountRequest |
| CardPaymentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll |  |
| CashPaymentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | CalculatePaymentAmountServiceRequest, AuthorizePaymentServiceRequest, VoidPaymentServiceRequest, GetChangePaymentServiceRequest, IsTenderLineLinkedRefundableServiceRequest |
| CheckPaymentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | CalculatePaymentAmountServiceRequest, AuthorizePaymentServiceRequest, VoidPaymentServiceRequest, GetChangePaymentServiceRequest, IsTenderLineLinkedRefundableServiceRequest (+1) |
| CurrencyPaymentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | CalculatePaymentAmountServiceRequest, AuthorizePaymentServiceRequest, VoidPaymentServiceRequest, GetChangePaymentServiceRequest, IsTenderLineLinkedRefundableServiceRequest (+1) |
| GetCardPaymentAcceptPointRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCardPaymentAcceptPointRequest |
| GetSupportedCardTypesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetSupportedCardTypesRequest |
| PaymentConnectorDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetPaymentConnectorConfigurationDataRequest |
| PaymentManagerService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | AuthorizePaymentServiceRequest, CapturePaymentServiceRequest, GetChangePaymentServiceRequest, ResolveCardTypesServiceRequest, GetGiftCardServiceRequest (+5) |
| SaveTenderLineRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveTenderLineRequest |
| ValidateTenderLineForAddRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateTenderLineForAddRequest |

## Triggers (1)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| GetCardTypeDataRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | GetCardTypeDataRequest |
