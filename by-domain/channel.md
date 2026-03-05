# Channel

## Handlers (22)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| ChannelDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetStoreAddressBooksDataRequest, GetChannelConfigurationDataRequest, GetTimeZonesByCodeDataRequest, SearchOrgUnitDataRequest, GetChannelCategoriesDataRequest (+15) |
| ChannelManagementTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | UpdateChannelPublishingStatusRealtimeRequest, GetTerminalMerchantPaymentProviderDataRealtimeRequest, GetOnlineChannelMerchantPaymentProviderDataRealtimeRequest, GetPaymentMerchantInformationRealtimeRequest, GetChannelsRealtimeRequest |
| ChannelService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | UpdateChannelPublishStatusServiceRequest, GetChannelIdServiceRequest, SearchChannelsServiceRequest, IsConfigurationParameterEnabledServiceRequest |
| ChannelSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetChannelCategoryAttributesDataRequest, ResolveOperatingUnitNumberDataRequest, UpdateChannelPropertiesByChannelIdDataRequest, UpdateOnlineChannelPublishStatusDataRequest, GetDownloadingDataSetDataRequest (+36) |
| DeactivateDeviceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | DeactivateDeviceRequest |
| DeviceManagementService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | ActivateDeviceServiceRequest, MassActivateDeviceServiceRequest, AuthenticateDeviceServiceRequest, DeactivateDeviceServiceRequest, CreateHardwareStationTokenServiceRequest (+1) |
| DeviceManagementSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | CreateOrUpdateDeviceDataRequest |
| DeviceManagementTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | ActivateDeviceRealtimeRequest, MassActivateDeviceRealtimeRequest, DeactivateDeviceRealtimeRequest, AuthenticateDeviceRealtimeRequest, GetNumberSequenceSeedDataRealtimeRequest (+2) |
| GetAvailableStoresRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetAvailableStoresRequest |
| GetChannelCurrencyRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetChannelCurrencyAmountRequest |
| GetDeviceConfigurationRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetDeviceConfigurationRequest |
| GetHardwareStationProfileRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetHardwareStationProfileRequest |
| GetOnlineChannelRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetOnlineChannelRequest |
| HardwareProfileDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetHardwareProfileDataRequest, GetHardwareProfileCashDrawersDataRequest |
| HardwareStationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetHardwareStationDataRequest |
| OfflineTerminalStateSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SetOfflineTerminalStateDataRequest |
| PickupAtStoreRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | PickupAtStoreRequest |
| StoreLocatorDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetOrgUnitAddressDataRequest, GetOrgUnitContactsDataRequest |
| StoreLocatorSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetStoresDataRequest, SearchStoresDataRequest, GetOrgUnitContactsDataRequest, GetOrgUnitAddressDataRequest |
| StoreOperationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | SaveNonSaleTenderServiceRequest, SaveDropAndDeclareServiceRequest, GetNonSaleTenderServiceRequest, SearchJournalTransactionsServiceRequest, GetShiftReconciliationLinesServiceRequest (+6) |
| TerminalDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetTerminalDataRequest, GetPaymentConnectorDataRequest, GetCurrentTerminalIdDataRequest |
| VisualProfileSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetVisualProfileDataRequest |

## Triggers (10)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.RestrictShiftDuration.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | GetDeviceConfigurationRequest |
| GetDeviceConfigurationRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.UseAdvanceInvoice.dll | GetDeviceConfigurationRequest |
