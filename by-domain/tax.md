# Tax

## Handlers (62)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalIntegrationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalIntegrationDataService.md) | handler | [GetChannelFiscalIntegrationRegistrationProcessDataRequest](../by-request-type/GetChannelFiscalIntegrationRegistrationProcessDataRequest.md), [GetFiscalIntegrationFunctionalityProfileGroupDataRequest](../by-request-type/GetFiscalIntegrationFunctionalityProfileGroupDataRequest.md), [GetFiscalIntegrationFunctionalityProfileDataRequest](../by-request-type/GetFiscalIntegrationFunctionalityProfileDataRequest.md), [GetFiscalIntegrationDocumentProvidersDataRequest](../by-request-type/GetFiscalIntegrationDocumentProvidersDataRequest.md), [GetFiscalIngerationTechnicalProfileDataRequest](../by-request-type/GetFiscalIngerationTechnicalProfileDataRequest.md) (+2) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalTextDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalTextDataService.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.IndiaTaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.IndiaTaxDataService.md) | handler | [GetReceiptHeaderInfoIndiaDataRequest](../by-request-type/GetReceiptHeaderInfoIndiaDataRequest.md), [GetTaxSummarySettingIndiaDataRequest](../by-request-type/GetTaxSummarySettingIndiaDataRequest.md), [GetTaxComponentIndiaDataRequest](../by-request-type/GetTaxComponentIndiaDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxDataService.md) | handler | [GetTaxOverridesDataRequest](../by-request-type/GetTaxOverridesDataRequest.md), [GetTaxOverrideDetailsDataRequest](../by-request-type/GetTaxOverrideDetailsDataRequest.md), [GetSalesTaxGroupsDataRequest](../by-request-type/GetSalesTaxGroupsDataRequest.md), [GetTaxCodeFormulaIndiaDataRequest](../by-request-type/GetTaxCodeFormulaIndiaDataRequest.md), [GetTaxParameterDataRequest](../by-request-type/GetTaxParameterDataRequest.md) (+2) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxRegistrationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxRegistrationDataService.md) | handler | [GetTaxRegistrationsByChannelIdsDataRequest](../by-request-type/GetTaxRegistrationsByChannelIdsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AuditEventFiscalRegistrationLineSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AuditEventFiscalRegistrationLineSqlServerDataService.md) | handler | [SaveAuditEventFiscalRegistrationLineDataRequest](../by-request-type/SaveAuditEventFiscalRegistrationLineDataRequest.md), [GetAuditEventFiscalRegistrationLinesDataRequest](../by-request-type/GetAuditEventFiscalRegistrationLinesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalIntegrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalIntegrationSqlServerDataService.md) | handler | [SaveFiscalRegistrationProcessContextDataRequest](../by-request-type/SaveFiscalRegistrationProcessContextDataRequest.md), [GetLastSequentialSignaturesDataRequest](../by-request-type/GetLastSequentialSignaturesDataRequest.md), [GetFiscalIntegrationChannelFunctionalityProfilesByGroupDataRequest](../by-request-type/GetFiscalIntegrationChannelFunctionalityProfilesByGroupDataRequest.md), [GetHardwareProfileFiscalConnectorTechnicalProfilesDataRequest](../by-request-type/GetHardwareProfileFiscalConnectorTechnicalProfilesDataRequest.md), [GetActiveFiscalIntegrationProcessContextDataRequest](../by-request-type/GetActiveFiscalIntegrationProcessContextDataRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTextSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTextSqlServerDataService.md) | handler | [GetDiscountFiscalTextDataRequest](../by-request-type/GetDiscountFiscalTextDataRequest.md), [GetInfoCodeFiscalTextDataRequest](../by-request-type/GetInfoCodeFiscalTextDataRequest.md), [GetDiscountFiscalTextByOfferIdDataRequest](../by-request-type/GetDiscountFiscalTextByOfferIdDataRequest.md), [GetInfoCodeFiscalTextByInfoCodeIdDataRequest](../by-request-type/GetInfoCodeFiscalTextByInfoCodeIdDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTransactionSqlServerDataService.md) | handler | [SaveFiscalTransactionDataRequest](../by-request-type/SaveFiscalTransactionDataRequest.md), [GetSalesOrdersWithNoFiscalTransactionDataRequest](../by-request-type/GetSalesOrdersWithNoFiscalTransactionDataRequest.md), [GetFiscalTransactionsDataRequest](../by-request-type/GetFiscalTransactionsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.IndiaTaxSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.IndiaTaxSqlServerDataService.md) | handler | [GetReceiptHeaderTaxInfoIndiaDataRequest](../by-request-type/GetReceiptHeaderTaxInfoIndiaDataRequest.md), [GetWarehouseAddressIndiaDataRequest](../by-request-type/GetWarehouseAddressIndiaDataRequest.md), [GetTaxRegimeIndiaDataRequest](../by-request-type/GetTaxRegimeIndiaDataRequest.md), [GetTaxCodeIntervalsIndiaDataRequest](../by-request-type/GetTaxCodeIntervalsIndiaDataRequest.md), [GetApplyInterstateTaxIndiaDataRequest](../by-request-type/GetApplyInterstateTaxIndiaDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService.md) | handler | [GetTaxRegistrationDataRequest](../by-request-type/GetTaxRegistrationDataRequest.md), [SaveTaxRegistrationsDataRequest](../by-request-type/SaveTaxRegistrationsDataRequest.md), [GetTaxRegistrationsByChannelIdsDataRequest](../by-request-type/GetTaxRegistrationsByChannelIdsDataRequest.md), [DeleteTaxRegistrationsDataRequest](../by-request-type/DeleteTaxRegistrationsDataRequest.md), [GetTaxRegistrationTypeApplicabilityRulesDataRequest](../by-request-type/GetTaxRegistrationTypeApplicabilityRulesDataRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxSqlServerDataService.md) | handler | [GetSalesTaxGroupDataRequest](../by-request-type/GetSalesTaxGroupDataRequest.md), [GetTaxCodeGroupEntriesDataRequest](../by-request-type/GetTaxCodeGroupEntriesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.TaxSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.TaxSqlSharedDataService.md) | handler | [GetTaxCodeIntervalDataRequest](../by-request-type/GetTaxCodeIntervalDataRequest.md), [GetTaxCodeIntervalsDataRequest](../by-request-type/GetTaxCodeIntervalsDataRequest.md), [InsertShiftTaxLineDataRequest](../by-request-type/InsertShiftTaxLineDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService.md) | handler | [GetBacenCodeDataRequest](../by-request-type/GetBacenCodeDataRequest.md), [GetBenefitCodeDataRequest](../by-request-type/GetBenefitCodeDataRequest.md), [GetCfopDataRequest](../by-request-type/GetCfopDataRequest.md), [GetCfopGroupIdDataRequest](../by-request-type/GetCfopGroupIdDataRequest.md), [GetCnaeCodeDataRequest](../by-request-type/GetCnaeCodeDataRequest.md) (+32) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorContingencyFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorContingencyFiscalDocument.md) | handler | [SubmitDocumentConnectorRequest](../by-request-type/SubmitDocumentConnectorRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorEInvoicingFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorEInvoicingFiscalDocument.md) | handler | [SubmitDocumentConnectorRequest](../by-request-type/SubmitDocumentConnectorRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorStatusRequestFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorStatusRequestFiscalDocument.md) | handler | [SubmitDocumentConnectorRequest](../by-request-type/SubmitDocumentConnectorRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorSubmitFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.ConnectorSubmitFiscalDocument.md) | handler | [SubmitDocumentConnectorRequest](../by-request-type/SubmitDocumentConnectorRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderContingencyFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderContingencyFiscalDocument.md) | handler | [GetFiscalDocumentDocumentProviderRequest](../by-request-type/GetFiscalDocumentDocumentProviderRequest.md), [GetSupportedRegistrableEventsDocumentProviderRequest](../by-request-type/GetSupportedRegistrableEventsDocumentProviderRequest.md), [GetFiscalIntegrationSequentialKeysDocumentProviderRequest](../by-request-type/GetFiscalIntegrationSequentialKeysDocumentProviderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderEInvoicingFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderEInvoicingFiscalDocument.md) | handler | [GetFiscalDocumentDocumentProviderRequest](../by-request-type/GetFiscalDocumentDocumentProviderRequest.md), [GetSupportedRegistrableEventsDocumentProviderRequest](../by-request-type/GetSupportedRegistrableEventsDocumentProviderRequest.md), [GetFiscalTransactionExtendedDataDocumentProviderRequest](../by-request-type/GetFiscalTransactionExtendedDataDocumentProviderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderSatFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderSatFiscalDocument.md) | handler | [GetFiscalDocumentDocumentProviderRequest](../by-request-type/GetFiscalDocumentDocumentProviderRequest.md), [GetSupportedRegistrableEventsDocumentProviderRequest](../by-request-type/GetSupportedRegistrableEventsDocumentProviderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderStatusRequestFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderStatusRequestFiscalDocument.md) | handler | [GetFiscalDocumentDocumentProviderRequest](../by-request-type/GetFiscalDocumentDocumentProviderRequest.md), [GetSupportedRegistrableEventsDocumentProviderRequest](../by-request-type/GetSupportedRegistrableEventsDocumentProviderRequest.md), [GetFiscalTransactionExtendedDataDocumentProviderRequest](../by-request-type/GetFiscalTransactionExtendedDataDocumentProviderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderSubmitFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderSubmitFiscalDocument.md) | handler | [GetFiscalDocumentDocumentProviderRequest](../by-request-type/GetFiscalDocumentDocumentProviderRequest.md), [GetSupportedRegistrableEventsDocumentProviderRequest](../by-request-type/GetSupportedRegistrableEventsDocumentProviderRequest.md), [GetFiscalIntegrationSequentialKeysDocumentProviderRequest](../by-request-type/GetFiscalIntegrationSequentialKeysDocumentProviderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentElectronicReportingService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentElectronicReportingService.md) | handler | [GetFiscalDocumentElectronicReportingModelMappingDataServiceRequest](../by-request-type/GetFiscalDocumentElectronicReportingModelMappingDataServiceRequest.md), [GetFiscalDocumentElectronicReportingFormatMappingDataServiceRequest](../by-request-type/GetFiscalDocumentElectronicReportingFormatMappingDataServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentRealtimeService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentRealtimeService.md) | handler | [GetTechnicalResponsibleCsrtRealtimeRequest](../by-request-type/GetTechnicalResponsibleCsrtRealtimeRequest.md), [GetConsumerEFDocCscRealtimeRequest](../by-request-type/GetConsumerEFDocCscRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService.md) | handler | [CreateFiscalDocumentServiceRequest](../by-request-type/CreateFiscalDocumentServiceRequest.md), [CreateFiscalDocumentCancelServiceRequest](../by-request-type/CreateFiscalDocumentCancelServiceRequest.md), [CreateFiscalDocumentReturnServiceRequest](../by-request-type/CreateFiscalDocumentReturnServiceRequest.md), [SearchFiscalDocumentRequest](../by-request-type/SearchFiscalDocumentRequest.md), [SignFiscalDocumentXmlServiceRequest](../by-request-type/SignFiscalDocumentXmlServiceRequest.md) (+3) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentValidationService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentValidationService.md) | handler | [ValidateFiscalDocumentServiceRequest](../by-request-type/ValidateFiscalDocumentServiceRequest.md), [ValidateFiscalDocumentReasonCodeServiceRequest](../by-request-type/ValidateFiscalDocumentReasonCodeServiceRequest.md), [ValidateFiscalDocumentRefReceiptNumberLengthDataRequest](../by-request-type/ValidateFiscalDocumentRefReceiptNumberLengthDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService.md) | handler | [GetFiscalServiceStatusServiceRequest](../by-request-type/GetFiscalServiceStatusServiceRequest.md), [SubmitFiscalDocumentServiceRequest](../by-request-type/SubmitFiscalDocumentServiceRequest.md), [GetFiscalDocumentStatusServiceRequest](../by-request-type/GetFiscalDocumentStatusServiceRequest.md), [CancelFiscalDocumentServiceRequest](../by-request-type/CancelFiscalDocumentServiceRequest.md), [InquireFiscalDocumentServiceRequest](../by-request-type/InquireFiscalDocumentServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.IndiaTaxGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.IndiaTaxGteSqlServerDataService.md) | handler | [GetReceiptHeaderTaxInformationDataRequest](../by-request-type/GetReceiptHeaderTaxInformationDataRequest.md), [GetReceiptHeaderGteTaxInfoIndiaDataRequest](../by-request-type/GetReceiptHeaderGteTaxInfoIndiaDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.SaveGteTaxDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.SaveGteTaxDataRequestHandler.md) | single_handler | [SaveSalesTransactionDataRequest](../by-request-type/SaveSalesTransactionDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService.md) | handler | [InsertChargeTaxMeasureTableDataRequest](../by-request-type/InsertChargeTaxMeasureTableDataRequest.md), [InsertChargeTaxTransGteTableDataRequest](../by-request-type/InsertChargeTaxTransGteTableDataRequest.md), [InsertTaxTransGteTableDataRequest](../by-request-type/InsertTaxTransGteTableDataRequest.md), [InsertTaxTransIndiaTableDataRequest](../by-request-type/InsertTaxTransIndiaTableDataRequest.md), [InsertTaxMeasureTableDataRequest](../by-request-type/InsertTaxMeasureTableDataRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxCalculationRequestHandler.md) | handler | [CalculateTaxServiceRequest](../by-request-type/CalculateTaxServiceRequest.md), [GetTaxableDocumentMappingServiceRequest](../by-request-type/GetTaxableDocumentMappingServiceRequest.md), [PopulateSalesTransactionWithTaxesServiceRequest](../by-request-type/PopulateSalesTransactionWithTaxesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxEngineCacheService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxEngineCacheService.md) | handler | [RefreshTaxSolutionScopeCacheServiceRequest](../by-request-type/RefreshTaxSolutionScopeCacheServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.IndiaTaxGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.IndiaTaxGteSqlServerDataService.md) | handler | [GetReceiptHeaderTaxInformationDataRequest](../by-request-type/GetReceiptHeaderTaxInformationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.SaveGteTaxDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.SaveGteTaxDataRequestHandler.md) | single_handler | [SaveSalesTransactionDataRequest](../by-request-type/SaveSalesTransactionDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxConfigurationDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxConfigurationDataService.md) | handler | [GetTaxConfigurationDataRequest](../by-request-type/GetTaxConfigurationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxRegistrationIdDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxRegistrationIdDataService.md) | handler | [SaveAddressTaxInformationDataRequest](../by-request-type/SaveAddressTaxInformationDataRequest.md), [SaveCustomerTaxInformationDataRequest](../by-request-type/SaveCustomerTaxInformationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService.md) | handler | [InsertChargeTaxMeasureTableDataRequest](../by-request-type/InsertChargeTaxMeasureTableDataRequest.md), [InsertChargeTaxTransGteTableDataRequest](../by-request-type/InsertChargeTaxTransGteTableDataRequest.md), [InsertTaxTransGteTableDataRequest](../by-request-type/InsertTaxTransGteTableDataRequest.md), [InsertTaxTransIndiaTableDataRequest](../by-request-type/InsertTaxTransIndiaTableDataRequest.md), [InsertTaxMeasureTableDataRequest](../by-request-type/InsertTaxMeasureTableDataRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.ComplianceChecker.CheckFiscalIntegrationComplianceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.ComplianceChecker.CheckFiscalIntegrationComplianceRequestHandler.md) | handler | [CheckFiscalIntegrationComplianceRequest](../by-request-type/CheckFiscalIntegrationComplianceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxCalculationRequestHandler.md) | handler | [CalculateTaxServiceRequest](../by-request-type/CalculateTaxServiceRequest.md), [GetTaxableDocumentMappingServiceRequest](../by-request-type/GetTaxableDocumentMappingServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxEngineCacheService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxEngineCacheService.md) | handler | [RefreshTaxSolutionScopeCacheDataRequest](../by-request-type/RefreshTaxSolutionScopeCacheDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdRealtimeService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdRealtimeService.md) | handler | [SaveAddressTaxInformationRealtimeRequest](../by-request-type/SaveAddressTaxInformationRealtimeRequest.md), [SavePanNumberRealtimeRequest](../by-request-type/SavePanNumberRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdValidationService.md) | handler | [ValidateAddressTaxInformationRequest](../by-request-type/ValidateAddressTaxInformationRequest.md), [ValidateCustomerTaxInformationRequest](../by-request-type/ValidateCustomerTaxInformationRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdRealtimeService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdRealtimeService.md) | handler | [SaveCustomerFiscalCodeRealtimeRequest](../by-request-type/SaveCustomerFiscalCodeRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdValidationService.md) | handler | [ValidateCustomerFiscalCodeRequest](../by-request-type/ValidateCustomerFiscalCodeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Services.TaxRegistrationIdValidationService.md) | handler | [ValidateFiscalCustomerRequest](../by-request-type/ValidateFiscalCustomerRequest.md), [ValidateCustomerVatIdRequest](../by-request-type/ValidateCustomerVatIdRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService.md) | handler | [GetFiscalDocumentFiscalIntegrationServiceRequest](../by-request-type/GetFiscalDocumentFiscalIntegrationServiceRequest.md), [GetRegistrationProcessFiscalIntegrationServiceRequest](../by-request-type/GetRegistrationProcessFiscalIntegrationServiceRequest.md), [GetChannelSupportedEventsByGroupFiscalIntegrationServiceRequest](../by-request-type/GetChannelSupportedEventsByGroupFiscalIntegrationServiceRequest.md), [GetNonFiscalDocumentFiscalIntegrationServiceRequest](../by-request-type/GetNonFiscalDocumentFiscalIntegrationServiceRequest.md), [SaveRegistrationResultFiscalIntegrationServiceRequest](../by-request-type/SaveRegistrationResultFiscalIntegrationServiceRequest.md) (+17) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler.md) | handler | [GetTaxCodeServiceRequest](../by-request-type/GetTaxCodeServiceRequest.md), [GetBasePriceForTaxIncludedServiceRequest](../by-request-type/GetBasePriceForTaxIncludedServiceRequest.md), [GetIsTaxInclusiveServiceRequest](../by-request-type/GetIsTaxInclusiveServiceRequest.md), [CalculateTaxCodeTaxInclusiveAmountServiceRequest](../by-request-type/CalculateTaxCodeTaxInclusiveAmountServiceRequest.md), [CalculateTaxCodeTaxExclusiveAmountServiceRequest](../by-request-type/CalculateTaxCodeTaxExclusiveAmountServiceRequest.md) (+3) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync.md) | handler | [GetTaxCodeIntervalsDataRequest](../by-request-type/GetTaxCodeIntervalsDataRequest.md), [GetTaxCodeIntervalDataRequest](../by-request-type/GetTaxCodeIntervalDataRequest.md), [GetTaxationCodeDataRequest](../by-request-type/GetTaxationCodeDataRequest.md), [GetTaxExemptCodeDataRequest](../by-request-type/GetTaxExemptCodeDataRequest.md), [GetTaxPovertyTaxRateDataRequest](../by-request-type/GetTaxPovertyTaxRateDataRequest.md) (+2) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler.md) | handler | [GetTaxCodeIntervalsServiceRequest](../by-request-type/GetTaxCodeIntervalsServiceRequest.md), [GetTaxCodeServiceRequest](../by-request-type/GetTaxCodeServiceRequest.md), [CreateTaxLineServiceRequest](../by-request-type/CreateTaxLineServiceRequest.md), [GetTaxBasesServiceRequest](../by-request-type/GetTaxBasesServiceRequest.md), [GetTaxViewLinesServiceRequest](../by-request-type/GetTaxViewLinesServiceRequest.md) (+2) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.TaxRegistrationService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.TaxRegistrationService.md) | handler | [ValidateTaxRegistrationRequest](../by-request-type/ValidateTaxRegistrationRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.TaxService.md) | handler | [CalculateTaxServiceRequest](../by-request-type/CalculateTaxServiceRequest.md), [AssignTaxCodesServiceRequest](../by-request-type/AssignTaxCodesServiceRequest.md), [PopulateTaxRatesRequest](../by-request-type/PopulateTaxRatesRequest.md), [GetTaxableItemTaxCodesServiceRequest](../by-request-type/GetTaxableItemTaxCodesServiceRequest.md), [GetTaxCodeIntervalsServiceRequest](../by-request-type/GetTaxCodeIntervalsServiceRequest.md) (+13) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersDataService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersDataService.md) | handler | [GetTaxIdentifiersDataRequest](../by-request-type/GetTaxIdentifiersDataRequest.md), [SaveTaxIdentifiersDataRequest](../by-request-type/SaveTaxIdentifiersDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersRealtimeService.md) | handler | [SaveTaxIdentifiersRealtimeRequest](../by-request-type/SaveTaxIdentifiersRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersValidationService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersValidationService.md) | handler | [ValidateTaxIdentifiersRequest](../by-request-type/ValidateTaxIdentifiersRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdDataService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdDataService.md) | handler | [SaveAddressTaxInformationDataRequest](../by-request-type/SaveAddressTaxInformationDataRequest.md), [SaveCustomerTaxInformationDataRequest](../by-request-type/SaveCustomerTaxInformationDataRequest.md), [GetPrimaryAddressTaxInformationDataRequest](../by-request-type/GetPrimaryAddressTaxInformationDataRequest.md), [GetCustomerTaxInformationDataRequest](../by-request-type/GetCustomerTaxInformationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdRealtimeService.md) | handler | [SaveAddressTaxInformationRealtimeRequest](../by-request-type/SaveAddressTaxInformationRealtimeRequest.md), [SavePanNumberRealtimeRequest](../by-request-type/SavePanNumberRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdValidationService.md) | handler | [ValidateAddressTaxInformationRequest](../by-request-type/ValidateAddressTaxInformationRequest.md), [ValidateCustomerTaxInformationRequest](../by-request-type/ValidateCustomerTaxInformationRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdRealtimeService.md) | handler | [SaveCustomerFiscalCodeRealtimeRequest](../by-request-type/SaveCustomerFiscalCodeRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdValidationService.md) | handler | [ValidateCustomerFiscalCodeRequest](../by-request-type/ValidateCustomerFiscalCodeRequest.md), [ValidateFiscalCustomerDataRequest](../by-request-type/ValidateFiscalCustomerDataRequest.md), [ValidateCustomerLotteryCodeRequest](../by-request-type/ValidateCustomerLotteryCodeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Services.TaxRegistrationIdValidationService.md) | handler | [ValidateCustomerVatIdRequest](../by-request-type/ValidateCustomerVatIdRequest.md), [ValidateFiscalCustomerDataRequest](../by-request-type/ValidateFiscalCustomerDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TransactionService.TaxRegistrationRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.TaxRegistrationRealtimeService.md) | handler | [CreateOrUpdateCurrentTaxRegistrationRealtimeRequest](../by-request-type/CreateOrUpdateCurrentTaxRegistrationRealtimeRequest.md), [DeleteTaxRegistrationRealtimeRequest](../by-request-type/DeleteTaxRegistrationRealtimeRequest.md) |

## Triggers (3)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.SaveFiscalTransactionDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll) | [SaveFiscalTransactionDataRequest](../by-request-type/SaveFiscalTransactionDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxBasesServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll) | [GetTaxBasesServiceRequest](../by-request-type/GetTaxBasesServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.Triggers.AssignTaxCodesServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll) | [AssignTaxCodesServiceRequest](../by-request-type/AssignTaxCodesServiceRequest.md) |

## Request Types (121)

### AdjustTaxBasisServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AdjustTaxBasisServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxableItem` | TaxableItem |
| `IEnumerable<TaxCode>` | TaxCodes |

### AssignTaxCodesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AssignTaxCodesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.Triggers.AssignTaxCodesServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### BackupFiscalRegistrationProcessContextServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.BackupFiscalRegistrationProcessContextServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SerializedContext |
| `string` | StoreId |
| `string` | TerminalId |
| `bool` | ProcessCompleted |
| `long` | ChannelId |

### CalculateTaxCodeTaxExclusiveAmountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTaxCodeTaxExclusiveAmountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCode` | TaxCode |
| `ReadOnlyCollection<TaxCode>` | TaxCodes |
| `TaxableItem` | TaxableEntity |
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `decimal` | IntervalBasis |
| `bool` | IsTaxInStoreCurrency |

### CalculateTaxCodeTaxInclusiveAmountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTaxCodeTaxInclusiveAmountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCode` | TaxCode |
| `ReadOnlyCollection<TaxCode>` | TaxCodes |
| `TaxableItem` | TaxableEntity |
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `decimal` | IntervalBasis |
| `bool` | IsTaxInStoreCurrency |
| `bool` | IsTaxExemptedForPriceInclusive |

### CalculateTaxServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTaxServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### CancelFiscalDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.CancelFiscalDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `string` | EndpointAddress |
| `X509Certificate2` | Certificate |

### CheckFiscalIntegrationComplianceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckFiscalIntegrationComplianceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.ComplianceChecker.CheckFiscalIntegrationComplianceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |

### CreateFiscalDocumentCancelServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.CreateFiscalDocumentCancelServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |

### CreateFiscalDocumentReturnServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.CreateFiscalDocumentReturnServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `FiscalDocumentNumberSeries` | FiscalDocumentNumberSeries |

### CreateFiscalDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.CreateFiscalDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `FiscalDocumentNumberSeries` | FiscalDocumentNumberSeries |
| `TerminalOperationMode` | TerminalOperationMode |

### CreateFiscalTransactionFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateFiscalTransactionFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalIntegrationRegistrationResult` | FiscalRegistrationResult |
| `string` | FunctionalityProfileGroupId |
| `FiscalIntegrationConnectorType` | ConnectorType |

### CreateOrUpdateCurrentTaxRegistrationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.CreateOrUpdateCurrentTaxRegistrationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.TaxRegistrationRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `long` | DirectoryPartyLocationRecordId |
| `TaxRegistrationType` | TaxRegistrationType |
| `string` | RegistrationNumber |
| `DateTime` | EffectiveDate |

### CreateTaxLineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateTaxLineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `decimal` | TaxAmount |
| `TaxCode` | TaxCode |
| `bool` | IsPriceTaxInclusive |

### DeleteTaxRegistrationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.DeleteTaxRegistrationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.TaxRegistrationRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `long` | RecordId |

### DeleteTaxRegistrationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteTaxRegistrationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | TaxRegistrationIds |

### GetActiveFiscalIntegrationProcessContextDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetActiveFiscalIntegrationProcessContextDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalIntegrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StoreId |
| `string` | TerminalId |
| `long` | ChannelId |

### GetActiveFiscalRegistrationProcessContextBackupServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetActiveFiscalRegistrationProcessContextBackupServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | StoreId |
| `string` | TerminalId |
| `long` | ChannelId |

### GetAddressTaxGroupServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressTaxGroupServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Address` | Address |
| `string` | ShippingFromInventLocation |

### GetAuditEventFiscalRegistrationLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAuditEventFiscalRegistrationLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AuditEventFiscalRegistrationLineSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `AuditEventFiscalRegistrationLineSearchCriteria` | SearchCriteria |

### GetBenefitCodeTaxationCodesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetBenefitCodeTaxationCodesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StateId |

### GetFiscalAuthorityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalAuthorityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | AuthorityId |

### GetFiscalDocumentByAccessKeyDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentByAccessKeyDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | AccessKey |

### GetFiscalDocumentCancelDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentCancelDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StoreId |
| `string` | TerminalId |
| `string` | TransactionId |

### GetFiscalDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StoreId |
| `string` | TerminalId |
| `string` | TransactionId |

### GetFiscalDocumentDocumentProviderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.FiscalIntegration.DocumentProvider.Messages.GetFiscalDocumentDocumentProviderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.FIF.DocumentProvider.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.DocumentProviderSequentialSignatureFrance (Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderContingencyFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderEInvoicingFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderSatFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderStatusRequestFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderSubmitFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Services.DocumentProviderGazt (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** DocumentProviderRequest

| Type | Property |
|------|----------|
| `FiscalIntegrationDocumentRetrievalCriteria` | FiscalDocumentRetrievalCriteria |
| `SalesOrder` | SalesOrder |
| `NonSalesTransaction` | NonSalesTenderTransaction |
| `DropAndDeclareTransaction` | DropAndDeclareTransaction |
| `Shift` | Shift |

### GetFiscalDocumentElectronicReportingFormatMappingDataServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.GetFiscalDocumentElectronicReportingFormatMappingDataServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentElectronicReportingService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |
| `FiscalDocumentCancel` | FiscalDocumentCancel |
| `Guid` | FormatMappingId |
| `string` | CancelTransactionId |
| `bool` | UseInMemoryDataSources |

### GetFiscalDocumentElectronicReportingModelMappingDataServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.GetFiscalDocumentElectronicReportingModelMappingDataServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentElectronicReportingService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |
| `Guid` | ModelMappingId |
| `IList<CommerceProperty>` | Parameters |
| `string` | CancelTransactionId |

### GetFiscalDocumentFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalDocumentFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | FiscalIntegrationFunctionalityProfileGroupId |
| `FiscalIntegrationDocumentRetrievalCriteria` | DocumentRetrievalCriteria |
| `FiscalIntegrationConnectorType` | ConnectorType |

### GetFiscalDocumentLegalTextsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentLegalTextsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |

### GetFiscalDocumentLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |

### GetFiscalDocumentMaxNumberRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentMaxNumberRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StoreId |
| `string` | TerminalId |
| `string` | Series |

### GetFiscalDocumentSeriesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentSeriesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |

### GetFiscalDocumentSourceTextDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentSourceTextDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TextId |

### GetFiscalDocumentStatusServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.GetFiscalDocumentStatusServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `string` | EndpointAddress |
| `X509Certificate2` | Certificate |

### GetFiscalDocumentTaxesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentTaxesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |

### GetFiscalDocumentWebServiceParametersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalDocumentWebServiceParametersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | AuthorityId |
| `FiscalDocumentEnvironment` | FiscalDocumentEnvironment |
| `FiscalDocumentServiceType` | FiscalDocumentServiceType |

### GetFiscalEstablishmentAddressDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalEstablishmentAddressDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | LocationId |

### GetFiscalEstablishmentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetFiscalEstablishmentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StoreNumber |

### GetFiscalIngerationTechnicalProfileDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFiscalIngerationTechnicalProfileDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalIntegrationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ProfileId |

### GetFiscalIngerationTechnicalProfileOverridesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFiscalIngerationTechnicalProfileOverridesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalIntegrationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ProfileId |

### GetFiscalIntegrationFiscalRegistrationProcessSummaryServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalIntegrationFiscalRegistrationProcessSummaryServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |

### GetFiscalIntegrationFunctionalityProfileDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFiscalIntegrationFunctionalityProfileDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalIntegrationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ProfileId |

### GetFiscalIntegrationFunctionalityProfileGroupDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFiscalIntegrationFunctionalityProfileGroupDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FiscalIntegrationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | GroupId |

### GetFiscalIntegrationSequentialKeysByGroupIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalIntegrationSequentialKeysByGroupIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | FiscalIntegrationFunctionalityProfileGroupId |

### GetFiscalIntegrationServiceStatusServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalIntegrationServiceStatusServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalIntegrationServiceInfo` | FiscalIntegrationServiceInfo |

### GetFiscalRegisterResponseToSaveDocumentProviderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.FiscalIntegration.DocumentProvider.Messages.GetFiscalRegisterResponseToSaveDocumentProviderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.FIF.DocumentProvider.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.DocumentProviderSequentialSignatureFrance (Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll)
**Inherits:** DocumentProviderRequest

| Type | Property |
|------|----------|
| `FiscalIntegrationRegistrationResult` | FiscalRegistrationResult |

### GetFiscalServiceReadDataDocumentFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalServiceReadDataDocumentFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | FiscalIntegrationFunctionalityProfileGroupId |
| `FiscalIntegrationConnectorType` | ConnectorType |

### GetFiscalServiceSetupDocumentFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalServiceSetupDocumentFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | FiscalIntegrationFunctionalityProfileGroupId |
| `FiscalIntegrationConnectorType` | ConnectorType |

### GetFiscalServiceStatusServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.GetFiscalServiceStatusServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `string` | EndpointAddress |
| `X509Certificate2` | Certificate |

### GetFiscalTransactionExtendedDataDocumentProviderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.FiscalIntegration.DocumentProvider.Messages.GetFiscalTransactionExtendedDataDocumentProviderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.FIF.DocumentProvider.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.DocumentProviderSequentialSignatureFrance (Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderEInvoicingFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.FiscalIntegration.DocumentProviderStatusRequestFiscalDocument (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Services.DocumentProviderGazt (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** DocumentProviderRequest

| Type | Property |
|------|----------|
| `FiscalIntegrationRegistrationResult` | FiscalRegistrationResult |

### GetFiscalTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFiscalTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<string>` | TransactionIds |
| `long` | ChannelId |
| `string` | StoreId |
| `string` | TerminalId |

### GetFunctionalityProfileFiscalConnectorTechnicalProfilesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFunctionalityProfileFiscalConnectorTechnicalProfilesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalIntegrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | FunctionalityProfileId |

### GetInfoCodeFiscalTextByInfoCodeIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInfoCodeFiscalTextByInfoCodeIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTextSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ReadOnlyCollection<string>` | InfoCodeIds |
| `string` | FunctionalityProfileGroupId |

### GetInfoCodeFiscalTextDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInfoCodeFiscalTextDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTextSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | FunctionalityProfileGroupId |

### GetIsTaxInclusiveServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetIsTaxInclusiveServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCode` | TaxCode |
| `bool` | IsTaxIncludedInPriceByDefault |
| `TaxableItem` | TaxableEntity |
| `CustomerOrderMode` | CustomerOrderMode |

### GetLastAuditEventWithFiscalRegistrationLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLastAuditEventWithFiscalRegistrationLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AuditEventService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `AuditEventSearchCriteria` | SearchCriteria |

### GetNonFiscalDocumentFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonFiscalDocumentFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | FiscalIntegrationFunctionalityProfileGroupId |
| `FiscalIntegrationDocumentRetrievalCriteria` | DocumentRetrievalCriteria |
| `FiscalIntegrationConnectorType` | ConnectorType |

### GetPrimaryAddressTaxInformationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.India.GetPrimaryAddressTaxInformationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.CustomerTaxInformationDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdDataService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | LogisticsLocationRecordId |

### GetSalesTaxGroupDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTaxGroupDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `Dictionary<string, string>` | Predicates |

### GetTaxBasesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxBasesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxBasesServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCode` | TaxCode |
| `ReadOnlyCollection<TaxCode>` | TaxCodes |
| `TaxableItem` | TaxableEntity |
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `decimal` | IntervalBasis |
| `bool` | CalculateBasePrice |
| `bool` | IsTaxInStoreCurrency |
| `bool` | IsTaxIncludedInPrice |
| `bool` | IsTaxExemptedForPriceInclusive |

### GetTaxBurdenDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.GetTaxBurdenDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ItemId |
| `bool` | IsInternational |
| `string` | ExceptionCode |
| `string` | TaxFiscalClassificationId |

### GetTaxCodeFormulaIndiaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeFormulaIndiaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ItemTaxGroupId |
| `string` | TaxCode |

### GetTaxCodeGroupEntriesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeGroupEntriesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | SalesTaxGroupId |

### GetTaxCodeIntervalDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.TaxSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TaxCode |
| `DateTimeOffset` | TransactionDate |
| `decimal` | BaseTaxAmount |

### GetTaxCodeIntervalsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.TaxSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | SalesTaxGroupId |
| `string` | ItemTaxGroupId |
| `DateTimeOffset` | TransactionDate |

### GetTaxCodeIntervalsIndiaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsIndiaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.IndiaTaxSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | SalesTaxGroupId |
| `string` | ItemTaxGroupId |
| `DateTimeOffset` | TransactionDate |

### GetTaxCodeIntervalsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxCodeIntervalsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SalesTaxGroupId |
| `string` | ItemTaxGroupId |
| `DateTimeOffset` | TransDate |

### GetTaxCodePriorityServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxCodePriorityServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCode` | TaxCode |

### GetTaxCodeServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxCodeServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCodeInterval` | TaxCodeInterval |

### GetTaxComponentIndiaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxComponentIndiaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.IndiaTaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TaxCode |

### GetTaxConfigurationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.India.GetTaxConfigurationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxConfigurationDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | TaxSolutionScopeId |

### GetTaxExemptCodeDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxExemptCodeDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TaxItemGroupId |
| `string` | TaxGroupId |
| `string` | TaxCode |

### GetTaxExemptPercentageDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxExemptPercentageDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | SalesTaxGroupId |
| `string` | ItemTaxGroupId |

### GetTaxExemptPercentageServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxExemptPercentageServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SalesTaxGroupId |
| `string` | ItemTaxGroupId |
| `decimal` | TaxBase |

### GetTaxIdentifiersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Messages.GetTaxIdentifiersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersDataService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | CustomerAccountNumber |

### GetTaxLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll), Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | TransactionIds |

### GetTaxOverrideDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverrideDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TaxOverrideCode |

### GetTaxOverridesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverridesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TaxDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `TaxOverrideBy` | OverrideBy |

### GetTaxPovertyTaxRateDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxPovertyTaxRateDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ItemGroup |
| `string` | CountryRegionId |
| `string` | State |
| `DateTimeOffset` | AccountingDate |
| `string` | AccountGroup |
| `string` | AccountNumber |
| `string` | ItemId |

### GetTaxRegistrationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxRegistrationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | DirectoryPartyLocationRecordId |
| `TaxRegistrationType` | TaxRegistrationType |

### GetTaxRegistrationTypeApplicabilityRulesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxRegistrationTypeApplicabilityRulesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `TaxRegistrationType` | TaxRegistrationType |
| `string` | CountryRegionId |

### GetTaxRegistrationsByNumberAndRuleRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxRegistrationsByNumberAndRuleRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | RegistrationNumber |
| `long` | ApplicabilityRuleId |

### GetTaxSubstitutionCodeDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxSubstitutionCodeDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ItemId |
| `string` | TaxFiscalClassification |

### GetTaxViewLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxViewLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `Collection<ChargeLine>` | ChargeLines |

### GetTaxableDocumentMappingServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxableDocumentMappingServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### GetTaxationCodeDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxationCodeDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxSqlServerDataServiceBrazilAsync (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TaxItemGroupId |
| `string` | TaxGroupId |
| `string` | TaxCode |

### GetTechnicalProfilesByFunctionalityGroupIdsFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTechnicalProfilesByFunctionalityGroupIdsFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `IEnumerable<string>` | FunctionalityProfileGroupIds |

### GetTechnicalProfilesFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTechnicalProfilesFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `FiscalIntegrationTechnicalProfileSearchCriteria` | TechnicalProfileSearchCriteria |

### InquireFiscalDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.InquireFiscalDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `string` | EndpointAddress |
| `X509Certificate2` | Certificate |

### InsertTaxMeasureTableDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTaxMeasureTableDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<TaxMeasure>` | TaxMeasures |

### InsertTaxTransGteTableDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTaxTransGteTableDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<TaxLineGTE>` | TaxLinesGte |

### InsertTaxTransIndiaTableDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTaxTransIndiaTableDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<TaxLineIndia>` | TaxLinesIndia |

### PopulateTaxRatesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.PopulateTaxRatesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### PopulateTaxSummaryIndiaServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PopulateTaxSummaryIndiaServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.GteReceiptService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Receipt.GteReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `TaxSummarySettingIndia` | TaxSummarySetting |

### ProcessFiscalServiceReadDataResultFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessFiscalServiceReadDataResultFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | FiscalIntegrationFunctionalityProfileGroupId |
| `string` | Document |
| `FiscalIntegrationConnectorType` | ConnectorType |

### RefreshTaxSolutionScopeCacheDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Internal.India.RefreshTaxSolutionScopeCacheDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxEngineCacheService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `bool` | WithWarmup |
| `bool` | ForceRereadChangeTime |

### RefreshTaxSolutionScopeCacheServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RefreshTaxSolutionScopeCacheServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxEngineCacheService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `bool` | WithWarmup |
| `bool` | ForceRereadChangeTime |

### ResolveFunctionalProfileByFunctionalityGroupIdFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResolveFunctionalProfileByFunctionalityGroupIdFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | HardwareProfileId |
| `string` | FunctionalityProfileGroupId |
| `FiscalIntegrationConnectorType` | ConnectorType |

### SaveAddressTaxInformationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.India.SaveAddressTaxInformationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxRegistrationIdDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdDataService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<AddressTaxInformationIndia>` | AddressTaxInformationEntities |

### SaveAddressTaxInformationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.RealtimeServices.Messages.India.SaveAddressTaxInformationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdRealtimeService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `AddressTaxInformationIndia` | AddressTaxInformation |

### SaveAuditEventFiscalRegistrationLineDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveAuditEventFiscalRegistrationLineDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AuditEventFiscalRegistrationLineSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `AuditEventFiscalRegistrationLine` | FiscalRegistrationLine |
| `FiscalIntegrationSequentialSignatureData` | SequentialSignatureData |

### SaveFiscalRegistrationProcessContextDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveFiscalRegistrationProcessContextDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalIntegrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | SerializedContext |
| `string` | StoreId |
| `string` | TerminalId |
| `long` | ChannelId |
| `bool` | ProcessCompleted |

### SaveFiscalTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveFiscalTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll), Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.SaveFiscalTransactionDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `FiscalTransaction` | FiscalTransaction |
| `FiscalIntegrationSequentialSignatureData` | SequentialSignatureData |

### SaveRegistrationResultFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveRegistrationResultFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalIntegrationRegistrationResult` | FiscalRegistrationResult |
| `string` | HardwareProfileId |
| `string` | FunctionalityProfileGroupId |
| `FiscalIntegrationConnectorType` | ConnectorType |

### SaveTaxIdentifiersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Messages.SaveTaxIdentifiersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersDataService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `TaxIdentifiersData` | TaxIdentifiersDataEntity |

### SaveTaxIdentifiersRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Messages.SaveTaxIdentifiersRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `TaxIdentifiersData` | TaxIdentifiersDataEntity |

### SaveTaxRegistrationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTaxRegistrationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.TaxRegistrationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<TaxRegistration>` | TaxRegistrations |

### SearchFiscalDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.SearchFiscalDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalDocumentSearchCriteria` | FiscalDocumentSearchCriteria |

### SetElectronicFiscalDocumentPropertiesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.SetElectronicFiscalDocumentPropertiesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<CommerceProperty>` | ElectronicFiscalDocumentProperties |

### SignFiscalDocumentXmlServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.SignFiscalDocumentXmlServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `string` | CertificateProfileId |
| `string` | ElementToBeSigned |

### SubmitDocumentFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SubmitDocumentFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `FiscalIntegrationServiceInfo` | FiscalIntegrationServiceInfo |

### SubmitFiscalDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.SubmitFiscalDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.Services.FiscalSoapService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Document |
| `string` | EndpointAddress |
| `X509Certificate2` | Certificate |

### UpdateLastFiscalDocumentNumberDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.UpdateLastFiscalDocumentNumberDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | FiscalDocumentNumber |
| `string` | SequenceKey |

### UpdateSalesLineTaxInformationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateSalesLineTaxInformationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StoreId |
| `string` | TerminalId |
| `string` | TransactionId |
| `string` | DataAreaId |
| `IEnumerable<SalesLine>` | SalesLines |

### ValidateAddressTaxInformationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.India.ValidateAddressTaxInformationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdValidationService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `AddressTaxInformationIndia` | AddressTaxInformation |

### ValidateFiscalDocumentReasonCodeServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.ValidateFiscalDocumentReasonCodeServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentValidationService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | ReasonCode |

### ValidateFiscalDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.ValidateFiscalDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentValidationService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |

### ValidateTaxIdentifiersRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Brazil.ValidateTaxIdentifiersRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersValidationService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxIdentifiersData` | TaxIdentifiersDataEntity |
| `Address` | CustomerPrimaryAddress |
| `CustomerType` | CustomerType |

### ValidateTaxRegistrationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateTaxRegistrationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxRegistrationService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `Customer` | Customer |
| `CustomerType` | CustomerType |
| `Address` | Address |
| `string` | ThreeLetterISORegionName |
| `TaxRegistration` | TaxRegistration |
| `bool` | SkipUniquenessCheck |
| `bool?` | IsNewAddress |

### VerifyFiscalDocumentCancelExistenceDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.VerifyFiscalDocumentCancelExistenceDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Data.Services.FiscalDocumentDataService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StoreId |
| `string` | TerminalId |
| `string` | TransactionId |
