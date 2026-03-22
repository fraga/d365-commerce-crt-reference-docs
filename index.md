# CRT Extension Point Guide

SDK Version: `9.56.26056.3`
Generated from: `sdk/9.56`

## Start Here

1. Pick your business area in [Domain Index](by-domain/index.md).
2. Open a request type page in [Request Type Index](by-request-type/index.md).
3. Open concrete implementations in [Handler Index](by-handler/index.md).
4. Check assembly coverage in [Assembly Inventory](assemblies.md).

## Requirement-to-Entrypoint Flow

1. Requirement mentions business concept (cart, customer, tax): start in `by-domain/`.
2. Requirement mentions API/request name: start in `by-request-type/`.
3. Requirement mentions existing class/assembly: start in `by-handler/`.
4. Validate request neighbors: use the handler page's `Neighboring Triggers` section.

## 9.56 Changelog

The following extension points are new in 9.56:

**Cart & Checkout:**
* `SetCartLockRequest`
* `CreateAndSaveAsynchronousPaymentToCartRequest`
* `CreateAsynchronousPaymentServiceRequest`
* `GetSalesTransactionCheckoutResultByTransactionIdRequest`
* `CheckSalesTransactionExistenceDataRequest`
* `SetCartLockRequestHandler`
* `CreateAsynchronousPaymentServiceRequestHandler`
* `CreateAndSaveAsynchronousPaymentToCartRequestHandler`

**Payment Notifications:**
* `PostPaymentNotificationRequest`
* `UpdatePaymentNotificationProcessingStatusDataRequest`
* `UpdatePaymentNotificationProcessingStatusServiceRequest`
* `PostPaymentNotificationHandler`

**Diagnostics & Error Logging:**
* `GetCheckoutErrorLogDataRequest`
* `InsertCheckoutErrorLogDataRequest`
* `CheckoutErrorLogSqlServerDataService`

**System & Infrastructure:**
* `GetEmailTemplateByEventNotificationTypeDataRequest`
* `GetNonDefaultLanguageIdDataRequest`
* `PurgeTerminalStateDataRequest`

## C# Anatomy

- Use a request handler when you own the request implementation.
- Use a request trigger when you want before/after behavior around an existing pipeline.
- Prefer `SingleAsyncRequestHandler<TRequest>` over the obsolete synchronous base classes.

### Request Handler Stub

```csharp
using System.Threading.Tasks;
using Microsoft.Dynamics.Commerce.Runtime;
using Microsoft.Dynamics.Commerce.Runtime.Messages;
using Microsoft.Dynamics.Commerce.Runtime.Services.Messages;

namespace Contoso.Commerce.Runtime.Extensions;

public sealed class SaveCustomerRequestHandler
    : SingleAsyncRequestHandler<SaveCustomerServiceRequest>
{
    protected override async Task<Response> Process(
        SaveCustomerServiceRequest request)
    {
        ThrowIf.Null(request, nameof(request));

        var customer = request.CustomerToSave;

        // 1. Validate or enrich the request.
        // 2. Call other CRT requests through request.RequestContext if needed.
        // 3. Return the response expected by this request.

        throw new System.NotImplementedException();
    }
}
```

### Request Trigger Stub

```csharp
using System;
using System.Collections.Generic;
using System.Threading.Tasks;
using Microsoft.Dynamics.Commerce.Runtime;
using Microsoft.Dynamics.Commerce.Runtime.Messages;
using Microsoft.Dynamics.Commerce.Runtime.Services.Messages;

namespace Contoso.Commerce.Runtime.Extensions;

public sealed class SaveCustomerTrigger : IRequestTriggerAsync
{
    public IEnumerable<Type> SupportedRequestTypes =>
        new[] { typeof(SaveCustomerServiceRequest) };

    public Task OnExecuting(Request request)
    {
        var saveRequest = (SaveCustomerServiceRequest)request;

        // Pre-processing: validate, enrich, reject, log.
        return Task.CompletedTask;
    }

    public Task OnExecuted(Request request, Response response)
    {
        var saveRequest = (SaveCustomerServiceRequest)request;
        // Cast response to the concrete response type if you need it.
        // var typedResponse = (SaveCustomerServiceResponse)response;

        // Post-processing: inspect result, add telemetry, react to output.
        return Task.CompletedTask;
    }
}
```

## Catalog Summary

| Item | Count |
|------|-------|
| Assemblies | 136 |
| Handlers | 626 |
| Triggers | 80 |
| Request Types | 1664 |
