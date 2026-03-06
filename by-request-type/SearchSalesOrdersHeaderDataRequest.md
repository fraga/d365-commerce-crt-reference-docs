# SearchSalesOrdersHeaderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesOrdersHeaderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** order
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.SalesOrderSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.SalesOrderSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | SalesId |
| `string` | ReceiptId |
| `string` | ChannelReferenceId |
| `string` | CustomerName |
| `string` | CustomerAccountNumber |
| `string` | Store |
| `string` | TerminalId |
| `string` | StaffId |
| `DateTimeOffset?` | StartDateTime |
| `DateTimeOffset?` | EndDateTime |
| `string` | EmailAddress |
| `string` | LoyaltyCardNumber |
| `string` | CustomerPhoneNumber |
| `string` | CustomerRequisition |
| `IEnumerable<SalesTransactionType>` | SalesTransactionTypes |
| `IEnumerable<ExtensibleSalesTransactionType>` | ExtensibleSalesTransactionTypes |
| `IEnumerable<SalesStatus>` | OrderStatus |
| `ICollection<string>` | CustomTransactionIds |
| `string` | BusinessPartnerId |
| `ICollection<long>` | ChannelIds |
