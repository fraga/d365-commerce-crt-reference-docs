# Loyalty

## Handlers (8)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| AffiliationDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetAffiliationByAffiliationIdDataRequest |
| AffiliationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetAffiliationsDataRequest, GetAffiliationsByNameDataRequest |
| GetLoyaltyCardTransactionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetLoyaltyCardTransactionsRequest |
| IssueLoyaltyCardRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | IssueLoyaltyCardRequest |
| LoyaltyCardService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | CalculatePaymentAmountServiceRequest, AuthorizePaymentServiceRequest, CapturePaymentServiceRequest, VoidPaymentServiceRequest, GetChangePaymentServiceRequest (+1) |
| LoyaltyService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll | GetLoyaltyCardStatusServiceRequest, GetCustomerBlockedLoyaltyEnrollmentStatusServiceRequest, CalculateLoyaltyRewardPointsServiceRequest, IssueLoyaltyCardServiceRequest, FillInLoyaltyRewardPointLinesForSalesServiceRequest (+11) |
| LoyaltySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetCustomerLoyaltyCardsDataRequest, GetCustomerBlockedLoyaltyEnrollmentDataRequest, GetLoyaltyCardDataRequest, GetLoyaltyGroupsAndTiersDataRequest, GetLoyaltyCardAffiliationsDataRequest (+3) |
| LoyaltyTransactionServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | IssueLoyaltyCardRealtimeRequest, GetLoyaltyCardTransactionsRealtimeRequest, GetLoyaltyCardRewardPointsStatusRealtimeRequest, GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest, PostLoyaltyCardRewardPointRealtimeRequest (+4) |

## Triggers (1)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| IssueLoyaltyCardServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Services.Loyalty.dll | IssueLoyaltyCardServiceRequest |
