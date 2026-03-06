# GetProductSearchResultsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductSearchResultsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** product
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ProductSearchSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ProductSearchSqlServerDataService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.PrependAzureCmsMediaBaseUrlTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `long` | CatalogId |
| `long?` | CategoryId |
| `long` | ChannelId |
| `string` | SearchText |
| `bool` | UseFuzzySearch |
