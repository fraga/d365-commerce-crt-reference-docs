# CreateOrUpdateAsyncCustomerContactsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateAsyncCustomerContactsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** customer
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.CustomerSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.CustomerSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | CustomerAccountNumber |
| `bool` | IsAsyncCustomer |
| `IList<ContactInfo>` | CustomerContacts |
| `CustomerAsyncOperationType` | OperationType |
