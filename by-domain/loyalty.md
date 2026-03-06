# Loyalty

## Handlers (9)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AffiliationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AffiliationDataService.md) | handler | [GetAffiliationsDataRequest](../by-request-type/GetAffiliationsDataRequest.md), [GetAffiliationByAffiliationIdDataRequest](../by-request-type/GetAffiliationByAffiliationIdDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.LoyaltyDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.LoyaltyDataService.md) | handler | [GetCustomerLoyaltyCardsDataRequest](../by-request-type/GetCustomerLoyaltyCardsDataRequest.md), [GetCustomerLoyaltyCardAffiliationsRequest](../by-request-type/GetCustomerLoyaltyCardAffiliationsRequest.md), [GetLoyaltyCardAffiliationsDataRequest](../by-request-type/GetLoyaltyCardAffiliationsDataRequest.md), [GetLoyaltyCardDataRequest](../by-request-type/GetLoyaltyCardDataRequest.md), [GetAffiliationChannelsRequest](../by-request-type/GetAffiliationChannelsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AffiliationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AffiliationSqlServerDataService.md) | handler | [GetAffiliationsDataRequest](../by-request-type/GetAffiliationsDataRequest.md), [GetAffiliationsByNameDataRequest](../by-request-type/GetAffiliationsByNameDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService.md) | handler | [GetCustomerLoyaltyCardsDataRequest](../by-request-type/GetCustomerLoyaltyCardsDataRequest.md), [GetCustomerBlockedLoyaltyEnrollmentDataRequest](../by-request-type/GetCustomerBlockedLoyaltyEnrollmentDataRequest.md), [GetLoyaltyCardDataRequest](../by-request-type/GetLoyaltyCardDataRequest.md), [GetLoyaltyGroupsAndTiersDataRequest](../by-request-type/GetLoyaltyGroupsAndTiersDataRequest.md), [GetLoyaltyCardAffiliationsDataRequest](../by-request-type/GetLoyaltyCardAffiliationsDataRequest.md) (+3) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyCardService.md) | handler | [CalculatePaymentAmountServiceRequest](../by-request-type/CalculatePaymentAmountServiceRequest.md), [AuthorizePaymentServiceRequest](../by-request-type/AuthorizePaymentServiceRequest.md), [CapturePaymentServiceRequest](../by-request-type/CapturePaymentServiceRequest.md), [VoidPaymentServiceRequest](../by-request-type/VoidPaymentServiceRequest.md), [GetChangePaymentServiceRequest](../by-request-type/GetChangePaymentServiceRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService.md) | handler | [GetLoyaltyCardStatusServiceRequest](../by-request-type/GetLoyaltyCardStatusServiceRequest.md), [GetCustomerBlockedLoyaltyEnrollmentStatusServiceRequest](../by-request-type/GetCustomerBlockedLoyaltyEnrollmentStatusServiceRequest.md), [CalculateLoyaltyRewardPointsServiceRequest](../by-request-type/CalculateLoyaltyRewardPointsServiceRequest.md), [IssueLoyaltyCardServiceRequest](../by-request-type/IssueLoyaltyCardServiceRequest.md), [FillInLoyaltyRewardPointLinesForSalesServiceRequest](../by-request-type/FillInLoyaltyRewardPointLinesForSalesServiceRequest.md) (+11) |
| [Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler.md) | handler | [IssueLoyaltyCardRealtimeRequest](../by-request-type/IssueLoyaltyCardRealtimeRequest.md), [GetLoyaltyCardTransactionsRealtimeRequest](../by-request-type/GetLoyaltyCardTransactionsRealtimeRequest.md), [GetLoyaltyCardRewardPointsStatusRealtimeRequest](../by-request-type/GetLoyaltyCardRewardPointsStatusRealtimeRequest.md), [GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest](../by-request-type/GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest.md), [PostLoyaltyCardRewardPointRealtimeRequest](../by-request-type/PostLoyaltyCardRewardPointRealtimeRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardTransactionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardTransactionsRequestHandler.md) | single_handler | [GetLoyaltyCardTransactionsRequest](../by-request-type/GetLoyaltyCardTransactionsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueLoyaltyCardRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueLoyaltyCardRequestHandler.md) | single_handler | [IssueLoyaltyCardRequest](../by-request-type/IssueLoyaltyCardRequest.md) |

## Triggers (1)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.Services.IssueLoyaltyCardServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll) | [IssueLoyaltyCardServiceRequest](../by-request-type/IssueLoyaltyCardServiceRequest.md) |

## Request Types (37)

### CalculateLoyaltyRewardPointsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateLoyaltyRewardPointsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |

### CheckLoyaltyRewardLinesExistenceServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckLoyaltyRewardLinesExistenceServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |

### FillInLoyaltyRewardPointLinesForEarnOrDeductServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FillInLoyaltyRewardPointLinesForEarnOrDeductServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `ICollection<LoyaltySchemeLineEarn>` | EarnSchemeLines |
| `LoyaltyRewardPointEntryType` | EntryType |

### FillInLoyaltyRewardPointLinesForRefundServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FillInLoyaltyRewardPointLinesForRefundServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `LoyaltyCard` | LoyaltyCard |
| `decimal` | RefundAmount |
| `string` | RefundCurrency |

### FillInLoyaltyRewardPointLinesForReturnServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FillInLoyaltyRewardPointLinesForReturnServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `ICollection<LoyaltySchemeLineEarn>` | EarnSchemeLines |

### FillInLoyaltyRewardPointLinesForSalesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FillInLoyaltyRewardPointLinesForSalesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `ICollection<LoyaltySchemeLineEarn>` | EarnSchemeLines |

### GetAffiliationByAffiliationIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationByAffiliationIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AffiliationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | AffiliationId |

### GetAffiliationChannelsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.GetAffiliationChannelsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.LoyaltyDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long[]` | AffiliationIds |

### GetAffiliationsByNameDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsByNameDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AffiliationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `RetailAffiliationType` | AffiliationType |
| `IEnumerable<string>` | AffiliationNames |

### GetAffiliationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AffiliationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AffiliationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `AffiliationSearchCriteria` | SearchCriteria |
| `RetailAffiliationType` | AffiliationType |

### GetLoyaltyCardAffiliationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyCardAffiliationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.LoyaltyDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `SalesTransaction` | Transaction |

### GetLoyaltyCardDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyCardDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.LoyaltyDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |

### GetLoyaltyCardProgramPointsToNextTierRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyCardProgramPointsToNextTierRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |

### GetLoyaltyCardRewardPointsStatusRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyCardRewardPointsStatusRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |
| `bool` | ExcludeBlocked |
| `bool` | ExcludeNoTender |
| `bool` | IncludeRelatedCardsForContactTender |
| `bool` | IncludeNonRedeemablePoints |
| `bool` | IncludeActivePointsOnly |

### GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |
| `bool` | ExcludeWhenBlocked |
| `bool` | ExcludeWhenNoTender |
| `bool` | IncludeRelatedCardsForContactTender |
| `bool` | IncludeNonRedeemablePoints |
| `bool` | IncludeActivePointsOnly |
| `bool` | IncludeExpiringAndUnvestedPoints |
| `int` | DaysToExpiry |

### GetLoyaltyCardStatusServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `bool` | RetrieveFutureLoyaltyCardTiers |
| `bool` | RetrieveRewardPointStatus |

### GetLoyaltyCardTransactionsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyCardTransactionsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |

### GetLoyaltyCardTransactionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetLoyaltyCardTransactionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |

### GetLoyaltyGroupsAndTiersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyGroupsAndTiersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `bool` | RetrieveFutureLoyaltyCardTiers |

### GetLoyaltyRewardPointActivityTimelineForExpiredPointsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyRewardPointActivityTimelineForExpiredPointsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |

### GetLoyaltyRewardPointActivityTimelineForExpiredPointsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyRewardPointActivityTimelineForExpiredPointsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |

### GetLoyaltyRewardPointActivityTimelineRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyRewardPointActivityTimelineRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |

### GetLoyaltyRewardPointActivityTimelineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyRewardPointActivityTimelineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |

### GetLoyaltyRewardPointLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyRewardPointLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `LoyaltyRewardPointLinesQueryCriteria` | Criteria |

### GetLoyaltyRewardPointsExpiringSoonRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyRewardPointsExpiringSoonRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |
| `int` | DaysToExpiry |
| `bool` | CalculateAggregatedPoints |

### GetLoyaltyRewardPointsExpiringSoonServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyRewardPointsExpiringSoonServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `string` | RewardPointId |
| `int` | DaysToExpiry |

### GetLoyaltySchemeLineEarnDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineEarnDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | LoyaltyCardNumber |
| `Collection<SalesAffiliationLoyaltyTier>` | TransactionAffiliation |
| `string` | ActivityTypeId |
| `long` | AffiliationId |

### GetLoyaltySchemeLineRedeemDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineRedeemDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | LoyaltyCardNumber |
| `string` | LoyaltyRewardPointId |
| `Collection<SalesAffiliationLoyaltyTier>` | TransactionAffiliation |

### GetMaxLoyaltyPointsToRedeemForTransactionBalanceServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetMaxLoyaltyPointsToRedeemForTransactionBalanceServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | CartId |
| `string` | LoyaltyCardNumber |
| `string` | RedeemCurrency |

### InsertLoyaltyCardDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertLoyaltyCardDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.LoyaltySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `LoyaltyCard` | LoyaltyCard |

### IssueLoyaltyCardRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.IssueLoyaltyCardRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `LoyaltyCardTenderType` | LoyaltyCardTenderType |
| `long` | PartyRecordId |
| `long` | ChannelId |

### IssueLoyaltyCardRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.IssueLoyaltyCardRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueLoyaltyCardRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `string` | CustomerAccountNumber |
| `LoyaltyCardTenderType` | CardTenderType |

### IssueLoyaltyCardServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Services.IssueLoyaltyCardServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `LoyaltyCardTenderType` | LoyaltyCardTenderType |
| `string` | CustomerAccountNumber |
| `long` | PartyRecordId |
| `long` | ChannelId |

### PostLoyaltyCardRewardPointForNonTransactionalActivityRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.PostLoyaltyCardRewardPointForNonTransactionalActivityRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `LoyaltyRewardPointEntryType` | EntryType |
| `Collection<LoyaltyRewardPointLine>` | LoyaltyRewardPointLines |
| `long` | ChannelId |
| `string` | ActivityTypeId |

### PostLoyaltyCardRewardPointRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.PostLoyaltyCardRewardPointRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `LoyaltyRewardPointEntryType` | EntryType |
| `SalesTransaction` | Transaction |

### PostLoyaltyRewardPointsNonTransactionalActivityServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PostLoyaltyRewardPointsNonTransactionalActivityServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | LoyaltyCardNumber |
| `long` | ChannelId |
| `long` | AffiliationId |
| `string` | ActivityTypeId |

### ValidateLoyaltyCardServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateLoyaltyCardServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.LoyaltyService (Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `LoyaltyCard` | LoyaltyCard |
| `string` | CustomerAccountNumberOnTransaction |
