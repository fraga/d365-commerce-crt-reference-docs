# Security

## Handlers (6)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.LogAuthenticationDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.LogAuthenticationDataRequestHandler.md) | single_handler | [LogAuthenticationDataRequest](../by-request-type/LogAuthenticationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.UniqueSecretExtendedAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.UniqueSecretExtendedAuthenticationService.md) | handler | [GetUserEnrollmentDetailsServiceRequest](../by-request-type/GetUserEnrollmentDetailsServiceRequest.md), [GetUserAuthenticationCredentialIdServiceRequest](../by-request-type/GetUserAuthenticationCredentialIdServiceRequest.md), [OverrideUserCredentialServiceRequest](../by-request-type/OverrideUserCredentialServiceRequest.md), [ConfirmUserAuthenticationServiceRequest](../by-request-type/ConfirmUserAuthenticationServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService.md) | handler | [UserLogOnServiceRequest](../by-request-type/UserLogOnServiceRequest.md), [UserLogOffServiceRequest](../by-request-type/UserLogOffServiceRequest.md), [CheckAccessServiceRequest](../by-request-type/CheckAccessServiceRequest.md), [CheckAccessIsManagerServiceRequest](../by-request-type/CheckAccessIsManagerServiceRequest.md), [CheckAccessHasShiftServiceRequest](../by-request-type/CheckAccessHasShiftServiceRequest.md) (+11) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService.md) | handler | [UserResetPasswordRealtimeRequest](../by-request-type/UserResetPasswordRealtimeRequest.md), [UserChangePasswordRealtimeRequest](../by-request-type/UserChangePasswordRealtimeRequest.md), [StaffLogOnRealtimeRequest](../by-request-type/StaffLogOnRealtimeRequest.md), [UserLogOffRealtimeRequest](../by-request-type/UserLogOffRealtimeRequest.md), [UserLogOnRenewalRealtimeRequest](../by-request-type/UserLogOnRenewalRealtimeRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler.md) | single_handler | [UserAuthenticationRenewalRequest](../by-request-type/UserAuthenticationRenewalRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler.md) | single_handler | [UserAuthenticationRequest](../by-request-type/UserAuthenticationRequest.md) |

## Triggers (1)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.Workflow.OperationAccessCheckTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll) |  |
