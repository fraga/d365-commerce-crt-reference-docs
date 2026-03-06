# GetProductsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** product
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.ProductSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.ProductSqlSharedDataService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.PrependAzureCmsMediaBaseUrlTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `ReadOnlyCollection<ProductLookupClause>` | ItemAndInventDimIdCombinations |
| `ReadOnlyCollection<long>` | ProductIds |
| `bool?` | DownloadedProductsFilter |
| `long?` | CatalogId |
