# UpdateEmployeePasswordDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateEmployeePasswordDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** employee
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | StaffId |
| `string` | PasswordHash |
| `string` | PasswordSalt |
| `string` | PasswordHashAlgorithm |
| `DateTimeOffset` | PasswordLastChangedDateTime |
| `AuthenticationOperation` | PasswordLastUpdatedOperation |
| `bool` | ChangePasswordAtNextLogOn |
| `string` | LegacyLocalContext |
| `string` | LegacyRegistryData2 |
