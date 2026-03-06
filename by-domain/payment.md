# Payment

## Handlers (14)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PaymentConnectorDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PaymentConnectorDataService.md) | handler | [GetPaymentConnectorConfigurationDataRequest](../by-request-type/GetPaymentConnectorConfigurationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.PaymentDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.PaymentDataService.md) | handler | [GetChannelTenderTypesDataRequest](../by-request-type/GetChannelTenderTypesDataRequest.md), [GetCardTypeDataRequest](../by-request-type/GetCardTypeDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CardPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CardPaymentService.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService.md) | handler | [CalculatePaymentAmountServiceRequest](../by-request-type/CalculatePaymentAmountServiceRequest.md), [AuthorizePaymentServiceRequest](../by-request-type/AuthorizePaymentServiceRequest.md), [VoidPaymentServiceRequest](../by-request-type/VoidPaymentServiceRequest.md), [GetChangePaymentServiceRequest](../by-request-type/GetChangePaymentServiceRequest.md), [IsTenderLineLinkedRefundableServiceRequest](../by-request-type/IsTenderLineLinkedRefundableServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService.md) | handler | [CalculatePaymentAmountServiceRequest](../by-request-type/CalculatePaymentAmountServiceRequest.md), [AuthorizePaymentServiceRequest](../by-request-type/AuthorizePaymentServiceRequest.md), [VoidPaymentServiceRequest](../by-request-type/VoidPaymentServiceRequest.md), [GetChangePaymentServiceRequest](../by-request-type/GetChangePaymentServiceRequest.md), [IsTenderLineLinkedRefundableServiceRequest](../by-request-type/IsTenderLineLinkedRefundableServiceRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CommerceServicePaymentNotificationHandler (Microsoft.Dynamics.Commerce.Runtime.CopilotServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CommerceServicePaymentNotificationHandler.md) | handler | [CreatePaymentNotificationSubscriptionRequest](../by-request-type/CreatePaymentNotificationSubscriptionRequest.md), [DeletePaymentNotificationSubscriptionRequest](../by-request-type/DeletePaymentNotificationSubscriptionRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService.md) | handler | [CalculatePaymentAmountServiceRequest](../by-request-type/CalculatePaymentAmountServiceRequest.md), [AuthorizePaymentServiceRequest](../by-request-type/AuthorizePaymentServiceRequest.md), [VoidPaymentServiceRequest](../by-request-type/VoidPaymentServiceRequest.md), [GetChangePaymentServiceRequest](../by-request-type/GetChangePaymentServiceRequest.md), [IsTenderLineLinkedRefundableServiceRequest](../by-request-type/IsTenderLineLinkedRefundableServiceRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService.md) | handler | [AuthorizePaymentServiceRequest](../by-request-type/AuthorizePaymentServiceRequest.md), [CapturePaymentServiceRequest](../by-request-type/CapturePaymentServiceRequest.md), [GetChangePaymentServiceRequest](../by-request-type/GetChangePaymentServiceRequest.md), [ResolveCardTypesServiceRequest](../by-request-type/ResolveCardTypesServiceRequest.md), [GetGiftCardServiceRequest](../by-request-type/GetGiftCardServiceRequest.md) (+8) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.CalculateTenderDiscountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.CalculateTenderDiscountRequestHandler.md) | single_handler | [CalculateTenderDiscountRequest](../by-request-type/CalculateTenderDiscountRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardPaymentAcceptPointRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardPaymentAcceptPointRequestHandler.md) | single_handler | [GetCardPaymentAcceptPointRequest](../by-request-type/GetCardPaymentAcceptPointRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedCardTypesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedCardTypesRequestHandler.md) | single_handler | [GetSupportedCardTypesRequest](../by-request-type/GetSupportedCardTypesRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessPaymentLinkRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessPaymentLinkRequestHandler.md) | single_handler | [ProcessPaymentLinkRequest](../by-request-type/ProcessPaymentLinkRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTenderLineRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTenderLineRequestHandler.md) | single_handler | [SaveTenderLineRequest](../by-request-type/SaveTenderLineRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateTenderLineForAddRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateTenderLineForAddRequestHandler.md) | single_handler | [ValidateTenderLineForAddRequest](../by-request-type/ValidateTenderLineForAddRequest.md) |

## Triggers (1)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.GetCardTypeDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll) | [GetCardTypeDataRequest](../by-request-type/GetCardTypeDataRequest.md) |

## Request Types (54)

### AddInShiftTenderedAmountsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddInShiftTenderedAmountsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |
| `ICollection<ShiftTenderLine>` | TenderLines |

### AuthorizePaymentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `TenderLine` | TenderLine |
| `bool` | AllowPartialAuthorization |
| `bool` | SkipLimitValidation |
| `bool` | IsCardTokenRequired |
| `string` | ConnectorName |

### CalculatePaymentAmountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculatePaymentAmountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TenderLine` | TenderLine |

### CalculateRefundableTenderLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRefundableTenderLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CartService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `string` | TenderLineId |

### CalculateTenderDiscountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.CalculateTenderDiscountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.CalculateTenderDiscountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `long?` | CartVersion |
| `TenderLine` | TenderLine |

### CalculateTenderDiscountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTenderDiscountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `TenderLineBase` | TenderLine |

### CancelPaymentLinkServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CancelPaymentLinkServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `PaymentLink` | PaymentLink |

### CapturePaymentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TenderLine` | TenderLine |
| `SalesTransaction` | Transaction |

### CreatePaymentLinkServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreatePaymentLinkServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `CreatePaymentLinkParameters` | CreatePaymentLinkParameters |
| `string` | ReferenceId |
| `SalesTransaction` | SalesTransaction |

### CreatePaymentNotificationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreatePaymentNotificationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.NotificationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PaymentNotification` | Notification |

### CreatePaymentNotificationSubscriptionRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreatePaymentNotificationSubscriptionRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CommerceServicePaymentNotificationHandler (Microsoft.Dynamics.Commerce.Runtime.CopilotServices.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | ReferenceId |
| `IList<string>` | EventTypes |
| `string` | PaymentConnectorName |

### DeletePaymentNotificationSubscriptionRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeletePaymentNotificationSubscriptionRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CommerceServicePaymentNotificationHandler (Microsoft.Dynamics.Commerce.Runtime.CopilotServices.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | ReferenceId |

### FillInLoyaltyRewardPointLinesForPaymentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FillInLoyaltyRewardPointLinesForPaymentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `LoyaltyCard` | LoyaltyCard |
| `decimal` | RedeemAmount |
| `string` | RedeemCurrency |

### GetAustriaShiftStaffTenderedAmountDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Austria.GetAustriaShiftStaffTenderedAmountDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.XZReports.XZReportsAustriaSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.XZReportsAustriaSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |

### GetCardPaymentAcceptPointRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardPaymentAcceptPointRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCardPaymentAcceptPointRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `CardPaymentAcceptSettings` | CardPaymentAcceptSettings |

### GetCardTypeDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCardTypeDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PaymentDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.GetCardTypeDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | CardTypeId |
| `bool` | HasConnectorMapping |

### GetCashTenderTypeIdentifierServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCashTenderTypeIdentifierServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ExtensibleTransactionType` | ExtensibleTransactionType |

### GetChangePaymentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `decimal` | ChangeAmount |
| `string` | CurrencyCode |
| `string` | PaymentTenderTypeId |
| `string` | ChangeTenderTypeId |

### GetChannelTenderTypesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelTenderTypesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PaymentDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `bool?` | CountingRequired |
| `long` | ChannelId |

### GetDropAndDeclareTransactionTenderDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDropAndDeclareTransactionTenderDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DropAndDeclareSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DropAndDeclareTransactionId |

### GetFiscalCardTypeDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalCardTypeDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | CardTypeId |

### GetNonSaleTenderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonSaleTenderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** NonSaleTenderServiceRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |

### GetOnlineChannelMerchantPaymentProviderDataRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOnlineChannelMerchantPaymentProviderDataRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChannelManagementTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `IEnumerable<PaymentConnectorConfiguration>` | Connectors |

### GetPaymentConnectorConfigurationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPaymentConnectorConfigurationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PaymentConnectorDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |

### GetPaymentConnectorDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPaymentConnectorDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TerminalDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |

### GetPaymentLinkDefaultParametersServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetPaymentLinkDefaultParametersServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `long?` | CartVersion |

### GetPaymentMerchantInformationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetPaymentMerchantInformationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChannelManagementTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `ReadOnlyCollection<string>` | ServiceAccountIds |

### GetPaymentNotificationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPaymentNotificationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.NotificationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | Reference |
| `long` | ChannelId |

### GetPaymentNotificationsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentNotificationsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Reference |
| `long` | ChannelId |

### GetPaymentRoundedValueServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.RoundingService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | TenderTypeId |
| `decimal` | Value |
| `bool` | IsChange |

### GetShiftRequiredAmountsPerTenderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftRequiredAmountsPerTenderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `string` | ShiftId |

### GetShiftTenderLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftTenderLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `long` | ShiftId |
| `string` | TerminalId |

### GetShiftTenderLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShiftTenderLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `long` | ShiftId |
| `string` | TerminalId |

### GetShiftTenderedAmountDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftTenderedAmountDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |

### GetSupportedCardTypesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedCardTypesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetSupportedCardTypesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | Currency |

### GetTenderSuggestionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTenderSuggestionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | CartId |
| `string` | TenderTypeId |
| `string` | CurrencyCode |

### GetTenderTypeIdentifierServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTenderTypeIdentifierServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `RetailOperation` | PaymentMethod |
| `ExtensibleTransactionType` | ExtensibleTransactionType |

### GetTerminalMerchantPaymentProviderDataRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetTerminalMerchantPaymentProviderDataRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChannelManagementTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | MerchantPropertiesHash |

### GetTokenizedPaymentSessionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTokenizedPaymentSessionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | CartId |

### GetTransactionTenderTypeDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTransactionTenderTypeDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.NonSalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |

### IsTenderLineLinkedRefundableServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IsTenderLineLinkedRefundableServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TenderLine` | TenderLine |
| `long` | ChannelId |

### PostPaymentNotificationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PostPaymentNotificationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `PaymentNotification` | Notification |

### ProcessPaymentLinkRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessPaymentLinkRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessPaymentLinkRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `string` | PaymentReferenceId |
| `long?` | CartVersion |

### ProcessPaymentNotificationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessPaymentNotificationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `PaymentNotification` | Notification |
| `AsynchronousPayment` | AsynchronousPayment |

### ResolveCardTypesByPaymentTypeServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResolveCardTypesByPaymentTypeServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ResolveCardTypesServiceRequest

| Type | Property |
|------|----------|
| `string` | PaymentConnectorName |
| `string` | PaymentVariant |

### ResolveCardTypesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResolveCardTypesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | CardNumberPrefix |
| `CardType` | CardTypeFilter |
| `string` | PaymentToken |

### SaveNonSaleTenderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** NonSaleTenderServiceRequest

| Type | Property |
|------|----------|
| `decimal` | Amount |
| `string` | Currency |
| `string` | Description |
| `string` | TenderTypeId |
| `string` | TransactionId |
| `TransactionStatus` | TransactionSatus |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
| `ICollection<DenominationDetail>` | DenominationDetails |
| `decimal` | GiftCardBalance |
| `decimal` | GiftCardIssueAmount |
| `DateTimeOffset` | GiftCardActiveFrom |
| `DateTimeOffset` | GiftCardExpiryDate |
| `string` | GiftCardHistoryDetails |
| `string` | GiftCardIdMasked |
| `string` | GiftCardCurrencyCode |
| `string` | FromSafe |
| `string` | ToSafe |
| `string` | FromShiftTerminalId |
| `string` | ToShiftTerminalId |
| `string` | FromShiftId |
| `string` | ToShiftId |
| `CashManagementTransactionContext` | TransactionSourceContextType |
| `CashManagementTransactionContext` | TransactionDestinationContextType |

### SaveShiftTenderLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveShiftTenderLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Shift` | Shift |

### SaveTenderLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTenderLineRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `long?` | CartVersion |
| `string` | CustomerAccountNumber |
| `CartTenderLine` | TenderLine |
| `TenderLine` | PreprocessedTenderLine |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
| `TenderLineOperationType` | OperationType |

### SetTokenizedPaymentSessionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SetTokenizedPaymentSessionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | CartId |
| `string` | TokenizedPaymentSession |

### ValidatePaymentAmountForOnlineStoreCheckoutRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidatePaymentAmountForOnlineStoreCheckoutRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `IEnumerable<CartTenderLine>` | CartTenderLines |

### ValidateTenderLineForAddRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateTenderLineForAddRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateTenderLineForAddRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `TenderLine` | TenderLine |

### ValidateTenderLineForAddServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateTenderLineForAddServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `TenderLine` | TenderLine |
| `TenderType` | TenderType |

### VoidPaymentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidPaymentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CashPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CheckPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll), Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `TenderLine` | TenderLine |
