# Security

## Handlers (6)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.LogAuthenticationDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.LogAuthenticationDataRequestHandler.md) | single_handler | [LogAuthenticationDataRequest](../by-request-type/LogAuthenticationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.UniqueSecretExtendedAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.UniqueSecretExtendedAuthenticationService.md) | handler | [GetUserEnrollmentDetailsServiceRequest](../by-request-type/GetUserEnrollmentDetailsServiceRequest.md), [GetUserAuthenticationCredentialIdServiceRequest](../by-request-type/GetUserAuthenticationCredentialIdServiceRequest.md), [OverrideUserCredentialServiceRequest](../by-request-type/OverrideUserCredentialServiceRequest.md), [ConfirmUserAuthenticationServiceRequest](../by-request-type/ConfirmUserAuthenticationServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService.md) | handler | [UserLogOnServiceRequest](../by-request-type/UserLogOnServiceRequest.md), [UserLogOffServiceRequest](../by-request-type/UserLogOffServiceRequest.md), [CheckAccessServiceRequest](../by-request-type/CheckAccessServiceRequest.md), [CheckAccessIsManagerServiceRequest](../by-request-type/CheckAccessIsManagerServiceRequest.md), [CheckAccessHasShiftServiceRequest](../by-request-type/CheckAccessHasShiftServiceRequest.md) (+12) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService.md) | handler | [UserResetPasswordRealtimeRequest](../by-request-type/UserResetPasswordRealtimeRequest.md), [UserChangePasswordRealtimeRequest](../by-request-type/UserChangePasswordRealtimeRequest.md), [StaffLogOnRealtimeRequest](../by-request-type/StaffLogOnRealtimeRequest.md), [UserLogOffRealtimeRequest](../by-request-type/UserLogOffRealtimeRequest.md), [UserLogOnRenewalRealtimeRequest](../by-request-type/UserLogOnRenewalRealtimeRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler.md) | single_handler | [UserAuthenticationRenewalRequest](../by-request-type/UserAuthenticationRenewalRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler.md) | single_handler | [UserAuthenticationRequest](../by-request-type/UserAuthenticationRequest.md) |

## Triggers (1)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.Workflow.OperationAccessCheckTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll) |  |

## Request Types (5)

### ConfirmUserAuthenticationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ConfirmUserAuthenticationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UniqueSecretExtendedAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | UserId |
| `string` | Password |
| `string` | Credential |
| `string` | AdditionalAuthenticationData |
| `IDictionary<string, object>` | ExtraAuthenticationParameters |

### GetUserAuthenticationCredentialIdServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetUserAuthenticationCredentialIdServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UniqueSecretExtendedAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Credential |
| `IDictionary<string, object>` | ExtraParameters |

### LogAuthenticationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LogAuthenticationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.LogAuthenticationDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StaffId |
| `AuthenticationStatus` | AuthenticationStatus |
| `AuthenticationOperation` | AuthenticationOperation |

### UserAuthenticationRenewalRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRenewalRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRenewalRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `bool` | NeedChannelIdFromPrincipal |

### UserAuthenticationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.UserAuthenticationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | StaffId |
| `string` | Password |
| `RetailOperation` | RetailOperation |
| `string` | DeviceId |
| `string` | DeviceToken |
| `IDictionary<string, object>` | AdditionalAuthenticationData |
| `string` | GrantType |
| `string` | Credential |
