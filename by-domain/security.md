# Security

## Handlers (6)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| LogAuthenticationDataRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | LogAuthenticationDataRequest |
| UniqueSecretExtendedAuthenticationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | GetUserEnrollmentDetailsServiceRequest, GetUserAuthenticationCredentialIdServiceRequest, OverrideUserCredentialServiceRequest, ConfirmUserAuthenticationServiceRequest |
| UserAuthenticationRenewalRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UserAuthenticationRenewalRequest |
| UserAuthenticationRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UserAuthenticationRequest |
| UserAuthenticationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | UserLogOnServiceRequest, UserLogOffServiceRequest, CheckAccessServiceRequest, CheckAccessIsManagerServiceRequest, CheckAccessHasShiftServiceRequest (+11) |
| UserAuthenticationTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | UserResetPasswordRealtimeRequest, UserChangePasswordRealtimeRequest, StaffLogOnRealtimeRequest, UserLogOffRealtimeRequest, UserLogOnRenewalRealtimeRequest (+6) |

## Triggers (1)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| OperationAccessCheckTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll |  |
