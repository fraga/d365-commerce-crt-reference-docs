# GetProductSearchResultsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductSearchResultsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** product
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.SearchServices.Azure.ProductSearchAzureService (Microsoft.Dynamics.Commerce.Runtime.SearchServices.Azure.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.SearchServices.Azure.ProductSearchAzureService.md)
- [Microsoft.Dynamics.Commerce.Runtime.SearchServices.Bing.ProductSearchBingService (Microsoft.Dynamics.Commerce.Runtime.SearchServices.Bing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.SearchServices.Bing.ProductSearchBingService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.PrependAzureCmsMediaBaseUrlTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `ProductSearchCriteria` | SearchCriteria |
| `bool` | SearchForBarcodeItem |
