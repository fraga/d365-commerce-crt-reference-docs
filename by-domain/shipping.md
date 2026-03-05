# Shipping

## Handlers (14)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| AdditionalAddressSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | InsertAdditionalAddressDataRequest, Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAdditionalAddressTransDataRequest |
| AdditionalAddressSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | InsertAdditionalAddressDataRequest, GetAdditionalAddressTransDataRequest |
| AddressDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetSupportedLanguagesDataRequest, GetPostalAddressesDataRequest |
| AddressExtensionsDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | GetAddressExtensionsByDirectoryPartyDataRequest, SaveAddressExtensionsDataRequest |
| AddressService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetCountryRegionsForShippingServiceRequest, GetCountryRegionsServiceRequest, GetStateProvincesServiceRequest, GetCountiesServiceRequest, GetCitiesServiceRequest (+6) |
| AddressSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetCountryRegionsForShippingDataRequest, GetStateProvincesDataRequest, GetCitiesDataRequest, GetCountiesDataRequest, GetCountryRegionDataRequest (+7) |
| DeliveryOptionService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | IsDeliveryModePickupServiceRequest |
| GetAddressRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetAddressRequest |
| GetDeliveryOptionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetDeliveryOptionsRequest |
| ShippingDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetAllDeliveryOptionsDataRequest, GetShippingAdapterConfigurationDataRequest, GetWarehouseDetailsDataRequest, GetItemDimensionsDataRequest, GetDeliveryOptionDataRequest |
| ShippingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetDeliveryOptionsForProductsServiceRequest, GetOrderDeliveryOptionsServiceRequest, GetLineDeliveryOptionsServiceRequest, GetProductDeliveryOptionsServiceRequest, GetChannelDeliveryOptionsServiceRequest (+4) |
| ShippingSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetProductIdDeliveryOptionsDataRequest, CreateOrUpdateShipmentStatusDataRequest, GetItemDeliveryOptionsDataRequest, GetLineDeliveryOptionsDataRequest, GetChannelDeliveryOptionsDataRequest (+1) |
| UnifyDeliveryInformationRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UnifyDeliveryInformationServiceRequest |
| UpdateDeliverySpecificationsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UpdateDeliverySpecificationsRequest |

## Triggers (1)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| GetAddressRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetAddressRequest |
