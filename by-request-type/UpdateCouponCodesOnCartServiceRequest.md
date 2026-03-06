# UpdateCouponCodesOnCartServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateCouponCodesOnCartServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** cart
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.CouponService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CouponService.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `ReadOnlyCollection<string>` | CouponCodes |
| `CouponCodesOperation` | CouponCodesOperation |
| `bool` | IsLegacyDiscountCode |
