# Shipping

## Handlers (15)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AddressDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AddressDataService.md) | handler | [GetStateProvincesDataRequest](../by-request-type/GetStateProvincesDataRequest.md), [GetSupportedLanguagesDataRequest](../by-request-type/GetSupportedLanguagesDataRequest.md), [GetPostalAddressesDataRequest](../by-request-type/GetPostalAddressesDataRequest.md), [ValidateAddressDataRequest](../by-request-type/ValidateAddressDataRequest.md), [GetCountryRegionDataRequest](../by-request-type/GetCountryRegionDataRequest.md) (+2) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShippingDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShippingDataService.md) | handler | [GetAllDeliveryOptionsDataRequest](../by-request-type/GetAllDeliveryOptionsDataRequest.md), [GetShippingAdapterConfigurationDataRequest](../by-request-type/GetShippingAdapterConfigurationDataRequest.md), [GetWarehouseDetailsDataRequest](../by-request-type/GetWarehouseDetailsDataRequest.md), [GetItemDimensionsDataRequest](../by-request-type/GetItemDimensionsDataRequest.md), [GetDeliveryOptionDataRequest](../by-request-type/GetDeliveryOptionDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AddressSqlServerDataService.md) | handler | [GetCountryRegionsForShippingDataRequest](../by-request-type/GetCountryRegionsForShippingDataRequest.md), [GetStateProvincesDataRequest](../by-request-type/GetStateProvincesDataRequest.md), [GetCitiesDataRequest](../by-request-type/GetCitiesDataRequest.md), [GetCountiesDataRequest](../by-request-type/GetCountiesDataRequest.md), [GetCountryRegionDataRequest](../by-request-type/GetCountryRegionDataRequest.md) (+6) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShippingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShippingSqlServerDataService.md) | handler | [GetProductIdDeliveryOptionsDataRequest](../by-request-type/GetProductIdDeliveryOptionsDataRequest.md), [CreateOrUpdateShipmentStatusDataRequest](../by-request-type/CreateOrUpdateShipmentStatusDataRequest.md), [GetItemDeliveryOptionsDataRequest](../by-request-type/GetItemDeliveryOptionsDataRequest.md), [GetLineDeliveryOptionsDataRequest](../by-request-type/GetLineDeliveryOptionsDataRequest.md), [GetChannelDeliveryOptionsDataRequest](../by-request-type/GetChannelDeliveryOptionsDataRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.AddressSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.AddressSqlSharedDataService.md) | handler | [GetAddressPurposesDataRequest](../by-request-type/GetAddressPurposesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.AdditionalAddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.AdditionalAddressSqlServerDataService.md) | handler | [InsertAdditionalAddressDataRequest](../by-request-type/InsertAdditionalAddressDataRequest.md), [GetAdditionalAddressTransDataRequest](../by-request-type/GetAdditionalAddressTransDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.AdditionalAddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.AdditionalAddressSqlServerDataService.md) | handler | [InsertAdditionalAddressDataRequest](../by-request-type/InsertAdditionalAddressDataRequest.md), [GetAdditionalAddressTransDataRequest](../by-request-type/GetAdditionalAddressTransDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Russia.AddressExtensionsDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Russia.AddressExtensionsDataService.md) | handler | [GetAddressExtensionsByDirectoryPartyDataRequest](../by-request-type/GetAddressExtensionsByDirectoryPartyDataRequest.md), [SaveAddressExtensionsDataRequest](../by-request-type/SaveAddressExtensionsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.AddressService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.AddressService.md) | handler | [GetCountryRegionsForShippingServiceRequest](../by-request-type/GetCountryRegionsForShippingServiceRequest.md), [GetCountryRegionsServiceRequest](../by-request-type/GetCountryRegionsServiceRequest.md), [GetStateProvincesServiceRequest](../by-request-type/GetStateProvincesServiceRequest.md), [GetCountiesServiceRequest](../by-request-type/GetCountiesServiceRequest.md), [GetCitiesServiceRequest](../by-request-type/GetCitiesServiceRequest.md) (+6) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.DeliveryOptionService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.DeliveryOptionService.md) | handler | [IsDeliveryModePickupServiceRequest](../by-request-type/IsDeliveryModePickupServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService.md) | handler | [GetDeliveryOptionsForProductsServiceRequest](../by-request-type/GetDeliveryOptionsForProductsServiceRequest.md), [GetOrderDeliveryOptionsServiceRequest](../by-request-type/GetOrderDeliveryOptionsServiceRequest.md), [GetLineDeliveryOptionsServiceRequest](../by-request-type/GetLineDeliveryOptionsServiceRequest.md), [GetProductDeliveryOptionsServiceRequest](../by-request-type/GetProductDeliveryOptionsServiceRequest.md), [GetChannelDeliveryOptionsServiceRequest](../by-request-type/GetChannelDeliveryOptionsServiceRequest.md) (+4) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler.md) | single_handler | [GetAddressRequest](../by-request-type/GetAddressRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler.md) | single_handler | [GetDeliveryOptionsRequest](../by-request-type/GetDeliveryOptionsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UnifyDeliveryInformationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UnifyDeliveryInformationRequestHandler.md) | single_handler | [UnifyDeliveryInformationServiceRequest](../by-request-type/UnifyDeliveryInformationServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateDeliverySpecificationsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateDeliverySpecificationsRequestHandler.md) | single_handler | [UpdateDeliverySpecificationsRequest](../by-request-type/UpdateDeliverySpecificationsRequest.md) |

## Triggers (1)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Russia.GetAddressRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [GetAddressRequest](../by-request-type/GetAddressRequest.md) |

## Request Types (30)

### CreateAddressRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.CreateAddressRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `Customer` | Customer |
| `Address` | Address |

### DeactivateAddressRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.DeactivateAddressRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `long` | AddressId |
| `long` | CustomerId |

### GetAdditionalAddressTransDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAdditionalAddressTransDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.AdditionalAddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.AdditionalAddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `ExtensibleAdditionalAddressType` | AddressType |

### GetAddressDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CustomerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | RecordId |
| `long?` | CustomerRecordId |
| `ColumnSet` | ColumnSet |

### GetAddressExtensionsByDirectoryPartyDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.Russia.GetAddressExtensionsByDirectoryPartyDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Russia.AddressExtensionsDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | DirectoryPartyRecordId |

### GetAddressRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAddressRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Russia.GetAddressRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `AddressFilter` | AddressFilter |
| `string` | LanguageId |
| `string` | CountryRegionId |
| `string` | StateProvinceId |
| `string` | CountyId |
| `string` | City |
| `string` | District |
| `string` | ZipCode |

### GetAddressesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CustomerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | AddressRecordIds |

### GetDeliveryOptionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeliveryOptionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShippingDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | Code |

### GetDeliveryOptionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `IEnumerable<LineShippingAddress>` | LineShippingAddresses |
| `long?` | ChannelId |
| `bool` | FetchDeliveryOptionsForLines |
| `Address` | HeaderShippingAddress |
| `FilterDeliveryModeOption` | FilterOption |
| `bool` | UseChannelIdsBasedOnFulfillmentStore |
| `bool` | IgnoreLinesWithDeliveryMode |

### GetDeliveryPreferencesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeliveryPreferencesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShippingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<SalesLine>` | SalesLines |

### GetDeliveryPreferencesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDeliveryPreferencesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |

### GetExternalShippingRateServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ReadOnlyCollection<SalesLine>` | SalesLines |

### GetLineDeliveryOptionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLineDeliveryOptionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShippingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<SalesLine>` | SalesLines |
| `bool` | DoNotFilterByChannel |

### GetLineDeliveryOptionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<SalesLine>` | SalesLines |
| `long?` | ChannelId |
| `FilterDeliveryModeOption` | FilterOption |

### GetOrgUnitAddressDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOrgUnitAddressDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StoreLocatorSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.StoreLocatorDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | ChannelIds |

### GetPostalAddressesByRecIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPostalAddressesByRecIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AddressDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | AddressRecordIds |

### GetPostalAddressesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPostalAddressesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AddressDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | AddressRecordIds |

### GetShippingAdapterConfigurationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShippingAdapterConfigurationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShippingDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | DeliveryModeIds |

### GetShippingRateFromCarrierServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FedExService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll), Microsoft.Dynamics.Commerce.Runtime.Services.UpsService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ParameterSet` | AdapterConfig |
| `ShippingRateInfo` | ShippingRateInfo |

### InsertAdditionalAddressDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAdditionalAddressDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.AdditionalAddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.AdditionalAddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `Address` | Address |
| `SalesTransaction` | Transaction |
| `ExtensibleAdditionalAddressType` | AddressType |

### IsDeliveryModePickupServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IsDeliveryModePickupServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.DeliveryOptionService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DeliveryModeCode |

### SaveAddressExtensionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.Russia.SaveAddressExtensionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Russia.AddressExtensionsDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<AddressExtension>` | AddressExtensions |

### UnifyDeliveryInformationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UnifyDeliveryInformationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.UnifyDeliveryInformationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Cart` | UpdatedCart |
| `SalesTransaction` | ExistingCart |

### UpdateAddressRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.UpdateAddressRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `Customer` | Customer |
| `Address` | Address |

### UpdateDeliverySpecificationsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateDeliverySpecificationsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateDeliverySpecificationsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `DeliverySpecification` | DeliverySpecification |
| `IEnumerable<LineDeliverySpecification>` | LineDeliverySpecifications |
| `bool` | UpdateOrderLevelDeliveryOptions |
| `SalesTransaction` | ExistingCart |

### ValidateAddressDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AddressSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.AddressDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** GetAddressInfoDataRequest

| Type | Property |
|------|----------|
| `Address` | Address |

### ValidateAddressLengthServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAddressLengthServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AddressService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Address` | Address |

### ValidateElectronicAddressServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateElectronicAddressServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AddressService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `Customer` | Customer |
| `string` | CountryRegionCode |

### ValidateShippingAddressCarrierServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FedExService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll), Microsoft.Dynamics.Commerce.Runtime.Services.UpsService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ParameterSet` | AdapterConfig |
| `Address` | AddressToValidate |
| `bool` | SuggestAddress |

### ValidateShippingAddressServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Address` | AddressToValidate |
| `bool` | SuggestAddress |
| `string` | DeliveryModeId |
