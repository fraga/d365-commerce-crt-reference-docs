# Other

## Handlers (175)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| AggregateSalesLinesCollectionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AggregateSalesLinesCollectionRequest |
| AggregateSalesLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AggregateSalesLinesRequest |
| AppInfoTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | UpdateApplicationVersionRealtimeRequest |
| AttributeDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetAttributeNamesByIdsDataRequest |
| AttributeGroupDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| AttributeGroupSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetAttributeGroupDefinitionsDataRequest |
| AttributeSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetAttributeDefinitionsDataRequest |
| AuditEventDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | ValidateAuditEventExistsDataRequest |
| AuditEventRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | ValidateAuditEventExistsRealtimeRequest, RegisterAuditEventRealtimeRequest, GetAuditEventsRealtimeRequest |
| AuditEventService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | RegisterAuditEventServiceRequest, RegisterAndGetAuditEventServiceRequest, GetAuditEventsServiceRequest, GetLastAuditEventWithFiscalRegistrationLinesServiceRequest |
| AuditEventSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetAuditEventsDataRequest |
| AuditEventSqlSharedDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | RegisterAuditEventDataRequest |
| AuditLogSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | InsertAuditLogDataRequest, PurgeAuditLogsDataRequest |
| AvailabilityTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetStoreAvailabilityRealtimeRequest, GetProductAvailabilityByDimensionsRealtimeRequest, GetAvailableToPromiseInventoryRealtimeRequest |
| AzureSearchPublishService | handler | Microsoft.Dynamics.Commerce.Runtime.SearchServices.Azure.dll | PublishCustomerSearchServiceRequest |
| BusinessIntelligenceDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetReportConfigurationDataRequest, GetOLTPReportDataRequest, GetSupportedReportsDataRequest |
| BusinessIntelligenceService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | GetReportDataServiceRequest |
| BusinessVerticalsDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | GetBusinessVerticalsDataRequest |
| BusinessVerticalsDataService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Messages.GetBusinessVerticalsDataRequest |
| CashOutGiftCardRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CashOutGiftCardRequest |
| ChangeDatabaseConnectionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ChangeDatabaseConnectionRequest |
| ChangeTrackingSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveChangedEntitiesIdsDataRequest, ReadChangedEntitiesIdsDataRequest, DeleteChangedEntitiesIdsDataRequest |
| ChecklistTaskDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| ChecklistTaskGraphDataService | handler | Microsoft.Dynamics.Commerce.Runtime.GraphServices.PlannerTask.dll | GetChecklistTasksDataRequest, GetChecklistTaskByTaskIdDataRequest, CreateChecklistTaskDataRequest, UpdateChecklistTasksDataRequest |
| ChecklistTaskService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | GetChecklistTasksServiceRequest, GetChecklistTaskByIdServiceRequest, CreateChecklistTaskServiceRequest, UpdateChecklistsServiceRequest, UpdateChecklistTasksServiceRequest (+1) |
| ChecklistTaskSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetChecklistTaskTeamsIntegrationConfigurationDataRequest, GetChecklistTasksChannelPlanIdDataRequest, GetChecklistTasksHeaderDataRequest, UpdateChecklistTasksHeaderDataRequest, GetChecklistTasksDataRequest (+4) |
| ClientBookService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll | UpdateClientBookServiceRequest, SearchClientBookCustomersServiceRequest, PopulateClientBookCustomerAttributesServiceRequest, GetClientBookSearchRefinersServiceRequest |
| ClientBookSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SearchClientBookCustomersDataRequest, GetClientBookSearchRefinersDataRequest |
| ClientBookTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | UpdateClientBookRealtimeRequest |
| CommerceDataExchangeService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.DataSync.dll | SyncOfflineTransactionsServiceRequest, ProcessDataPackageServiceRequest, RunSynchLibraryCheckDataRequest |
| CommerceDataExchangeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetDownloadIntervalRealtimeRequest, GetDownloadLinkRealtimeRequest, GetDownloadSessionsRealtimeRequest, GetInitialDownloadSessionsRealtimeRequest, GetTerminalDataStoreNameRealtimeRequest (+6) |
| CommerceIdentityProviderSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetCommerceIdentityProviderByIssuerDataRequest, GetCommerceIdentityProvidersDataRequest |
| CommerceListRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetCommerceListRealtimeRequest, SaveCommerceListRealtimeRequest, AcceptCommerceListInvitationRealtimeRequest |
| CommerceListService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | AddLineToCommerceListServiceRequest |
| CompanyInformationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.dll | GetNameAndCompanyRegistrationNumberDataRequest |
| ConfigurationService | single_handler | Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll | GetExtensionLocationsRequest |
| ConvertSalesLineCurrencyAmountsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ConvertSalesLineCurrencyAmountsRequest |
| CreditMemoRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetCreditMemoRealtimeRequest, IssueCreditMemoRealtimeRequest, PayCreditMemoRealtimeRequest, LockCreditMemoRealtimeRequest, UnlockCreditMemoRealtimeRequest (+1) |
| CreditMemoService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | CalculatePaymentAmountServiceRequest, AuthorizePaymentServiceRequest, VoidPaymentServiceRequest, CapturePaymentServiceRequest, GetChangePaymentServiceRequest (+2) |
| CreditMemoSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveCreditMemoChannelTransactionDataRequest |
| CurrencyDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetChannelCurrenciesDataRequest, GetCurrencyByCodeDataRequest |
| CurrencyService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetCurrencyValueServiceRequest, GetChannelCurrencyServiceRequest, CalculateTotalAmountServiceRequest, GetExchangeRateServiceRequest |
| CurrencySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetExchangeRatesDataRequest |
| DataProtectionRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | CertificateEncryptionServiceRequest, CertificateDecryptionServiceRequest, HashDataServiceRequest |
| DataSignatureRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | CertificateSignatureServiceRequest |
| DatabaseEnvironmentConfigurationDataService | single_handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | LogDatabaseEnvironmentConfigurationRequest |
| DeleteListingsByLanguagesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | DeleteListingsByLanguagesRequest |
| DictionaryEnumDataService | single_handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicReporting.dll | GetElectronicReportingDictionaryEnumRequest |
| DictionaryTableDataService | single_handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicReporting.dll | GetElectronicReportingDictionaryTableRequest |
| DocumentOperationDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetDocumentOperationDataRequest |
| DocumentOperationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | CommitDocumentOperationRequest, GetDocumentOperationStatusRequest |
| DocumentOperationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveDocumentOperationDataRequest |
| DocumentOperationTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | CommitDocumentOperationRealtimeRequest, GetDocumentOperationStatusRealtimeRequest |
| DocumentProviderGazt | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetFiscalDocumentDocumentProviderRequest, GetSupportedRegistrableEventsDocumentProviderRequest, GetFiscalIntegrationSequentialKeysDocumentProviderRequest, GetFiscalTransactionExtendedDataDocumentProviderRequest |
| DocumentProviderSequentialSignatureFrance | handler | Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll | GetFiscalDocumentDocumentProviderRequest, GetSupportedRegistrableEventsDocumentProviderRequest, GetFiscalIntegrationSequentialKeysDocumentProviderRequest, GetFiscalRegisterResponseToSaveDocumentProviderRequest, GetFiscalTransactionExtendedDataDocumentProviderRequest |
| DropAndDeclareSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveDropAndDeclareTransactionDataRequest, GetDropAndDeclareTransactionDataRequest, GetDropAndDeclareTransactionTenderDetailsDataRequest |
| DummyFraudProtectionService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | FraudProtectionPurchaseServiceRequest, FraudProtectionBankEventServiceRequest, FraudProtectionPurchaseStatusServiceRequest |
| ElectronicInvoicingService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicInvoicingService.dll | SubmitElectronicInvoicingServiceDocumentServiceRequest, ResubmitElectronicInvoicingServiceDocumentServiceRequest, GetElectronicInvoicingServiceDocumentServiceRequest, SetElectronicInvoicingServiceDocumentStateServiceRequest, GetElectronicInvoicingServiceOutputParameterServiceRequest (+1) |
| ElectronicInvoicingServiceDataService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicInvoicingService.dll | GetElectronicInvoicingServiceParametersDataRequest, GetElectronicInvoicingServiceRuntimeSettingsDataRequest |
| ElectronicReportingDataService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicReporting.dll | GetElectronicReportingLabelsDataRequest, GetFormatMappingGuidDataRequest |
| ElectronicReportingService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetElectronicReportRequest |
| EmailService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | SendEmailRealtimeRequest, SendEmailsRealtimeRequest |
| EmailSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetEmailTemplateDataRequest |
| EndSessionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | EndSessionRequest |
| EnrollUserCredentialsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | EnrollUserCredentialRequest |
| EntityTranslationService | single_handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | TranslateEntitiesDataRequest |
| ExtendedConfigurationRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | GetExtendedConfigurationServiceRequest |
| FeatureStateDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetFeatureStatesRequest |
| FedExService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetShippingRateFromCarrierServiceRequest, GetTrackingInformationFromCarrierServiceRequest, ValidateShippingAddressCarrierServiceRequest |
| FormattingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetFormattedCurrencyServiceRequest, GetFormattedNumberServiceRequest, GetFormattedPercentageServiceRequest, GetFormattedDateServiceRequest, GetFormattedTimeServiceRequest (+1) |
| FraudProtectionService | handler | Microsoft.Dynamics.Commerce.Runtime.FraudProtectionServices.dll | FraudProtectionPurchaseServiceRequest, FraudProtectionBankEventServiceRequest, FraudProtectionPurchaseStatusServiceRequest |
| GZipDataCompressionService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | CompressByteArrayRequest, DecompressByteArrayRequest, CompressStreamRequest, DecompressStreamRequest |
| GaztConnectorService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetServiceStatusConnectorRequest, SubmitDocumentConnectorRequest |
| GenerateSecureIdentifierRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | GenerateAlphanumericSecureIdentifierServiceRequest, GenerateUrlSafeSecureIdentifierServiceRequest |
| GetAggregationGrantRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetAggregationGrantRequest |
| GetApplicableWarrantiesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetApplicableWarrantiesRequest |
| GetCommerceListRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCommerceListRequest |
| GetDeletedLanguagesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetDeletedLanguagesRequest |
| GetDeletedListingsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetDeletedListingsRequest |
| GetEnvironmentConfigurationServiceRequestHandler | single_handler | Microsoft.Dynamics.Retail.RetailServerLibrary.dll | GetEnvironmentConfigurationServiceRequest |
| GetExtensionPackageDefinitionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetExtensionPackageDefinitionsRequest |
| GetReturnOptionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetReturnOptionsServiceRequest |
| GetScanResultRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetScanResultRequest |
| GetShipmentPublishingStatusRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetShipmentPublishingStatusRequest |
| GetUnitOfMeasureConversionsServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetUnitOfMeasureConversionsServiceRequest |
| GetyReadOnlyExemptionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetReadOnlyExemptionsRequest |
| GiftCardRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetGiftCardRealtimeRequest, IssueGiftCardRealtimeRequest, AddToGiftCardRealtimeRequest, PayGiftCardRealtimeRequest, VoidGiftCardRealtimeRequest (+4) |
| GiftCardService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | AddToGiftCardServiceRequest, AuthorizePaymentServiceRequest, CalculatePaymentAmountServiceRequest, CapturePaymentServiceRequest, GetChangePaymentServiceRequest (+7) |
| GiftCardSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveGiftCardChannelTransactionDataRequest |
| HealthCheckDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | RunDBHealthCheckDataRequest |
| HealthCheckService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | RunHealthCheckServiceRequest |
| HealthCheckTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | RunHealthCheckRealtimeRequest |
| IncomeExpenseAccountsSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetIncomeExpenseAccountsDataRequest |
| InvoiceHashService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CalculateInvoiceHashRequest |
| InvoiceService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetInvoicesServiceRequest |
| InvokeMethodTransactionServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | InvokeMethodRealtimeRequest, InvokeExtensionMethodRealtimeRequest |
| IssueOrAddToGiftCardRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | IssueOrAddToGiftCardRequest |
| KitTransactionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveKitTransactionDataRequest |
| LayoutService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetButtonGridsServiceRequest, GetButtonGridByIdServiceRequest, GetButtonGridsByIdsServiceRequest, GetImageBlobsServiceRequest, GetImageBlobsByPictureIdsServiceRequest |
| LedgerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetLedgerParametersDataRequest |
| LinkedRefundsRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | UpdateRefundableAmountsRealtimeRequest |
| LoggingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | InsertAuditLogServiceRequest |
| NotificationDetailsService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | GetNotificationDetailsServiceRequest |
| NotificationHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Framework.dll |  |
| NotificationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | GetNotificationsServiceRequest |
| NotificationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetNotificationAcknowledgementsDataRequest |
| NotificationSqlSharedDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | AcknowledgeNotificationDataRequest |
| NotificationTransactionServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetNotificationsRealtimeRequest |
| NumberSequenceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetNumberSequenceRequest |
| NumberSequenceSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetLatestNumberSequenceDataRequest |
| OperationalInsightsDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| OperationalInsightsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | GetOperationalInsightsDataRequest |
| OperationalInsightsSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetOperationalInsightsConfigurationRequest |
| PickingReceivingService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetPurchaseOrderRealtimeRequest, GetTransferOrderRealtimeRequest, SavePurchaseOrderRealtimeRequest, SaveTransferOrderRealtimeRequest, GetPickingListRealtimeRequest (+9) |
| PickupTimeslotDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| PickupTimeslotService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetEstimatedPickupTimeslotAvailabilitiesServiceRequest |
| PickupTimeslotSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetDefinedPickupTimeslotsDataRequest, GetEstimatedPickupTimeslotAvailabilitiesDataRequest |
| ReasonCodeDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetReasonCodesByTableRefTypeDataRequest, GetReturnOrderReasonCodesDataRequest, GetReasonCodeSettingsDataRequest, GetTransactionReasonCodesDataRequest |
| ReasonCodeService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetReasonCodesServiceRequest, CalculateRequiredReasonCodesServiceRequest, CalculateCartRequiredReasonCodesServiceRequest, CalculateDropAndDeclareTransactionRequiredReasonCodesServiceRequest, CalculateNonSalesTransactionRequiredReasonCodesServiceRequest (+2) |
| ReasonCodeSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetReasonCodesDataRequest, GetReasonCodeGroupsDataRequest |
| RecallSalesInvoiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | RecallSalesInvoiceRequest |
| RegisterAuditEventServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | RegisterAuditEventServiceRequest |
| RegisterAuditEventServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | RegisterAuditEventServiceRequest |
| RegisterAuditEventServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventAustria.dll | RegisterAuditEventServiceRequest |
| RegisterAuditEventServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventFrance.dll | RegisterAuditEventServiceRequest, GetSupportedRegistrableAuditEventTypesRequest |
| ReportRunService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicReporting.dll | GetElectronicReportingMappingRuntimeEnvironmentRequest, GetElectronicReportingQueryDataLoaderRequest, GetElectronicReportingReportDataServiceRequest, GetElectronicReportingModelMappingDataServiceRequest, GetFilteredModelMappingServiceRequest |
| RequestHandlerAdapter | handler | Microsoft.Dynamics.Commerce.Runtime.dll |  |
| RetailServiceConfigurationDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetRetailServiceConfigurationDataRequest, GetRetailPlanOffersDataRequest |
| ReturnLocationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll |  |
| ReturnLocationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetReturnLabelByInfoCodeDataRequest, GetReturnLabelByReasonCodeDataRequest, GetReturnLocationByInfoCodeDataRequest |
| ReturnPolicySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetReturnPolicyDataRequest, GetLocalOnlyCustomerOrderRefundableAmountsDataRequest, GetReturnPoliciesPresenceDataRequest |
| RoundingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetRoundedValueServiceRequest, GetRoundedValuesServiceRequest, GetPaymentRoundedValueServiceRequest, GetRoundedStringServiceRequest, GetRoundQuantityServiceRequest (+1) |
| RsaDataSignatureService | single_handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetDataSignatureRequest |
| SalesAgreementTransactionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetSalesAgreementTransactionsDataRequest |
| SaveKitTransactionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveKitTransactionRequest |
| SaveReasonCodeLineRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveReasonCodeLineRequest |
| SaveVoidTransactionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveVoidTransactionRequest |
| SequentialSignatureConnectorService | handler | Microsoft.Dynamics.Commerce.Runtime.Connector.SequentialSign.dll | GetServiceStatusConnectorRequest, SubmitDocumentConnectorRequest |
| ShipmentsTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetShipmentsRealtimeRequest |
| SortSalesLinesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SortSalesLinesRequest |
| SrsReportRunService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetSrsReportDataRealtimeRequest |
| StartSessionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | StartSessionRequest |
| StorageLookupDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetStorageLookupDataRequest |
| StorageResolverService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Infrastructure.dll | GetConnectionStringRequest |
| TaskIntegrationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | CreateChecklistTaskForOrderPickupServiceRequest |
| TaskManagementTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetChecklistsRealtimeRequest, GetChecklistTasksRealtimeRequest, CreateChecklistTaskRealtimeRequest, UpdateChecklistsRealtimeRequest, UpdateChecklistTasksRealtimeRequest |
| TillLayoutDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetButtonGridsDataRequest |
| TillLayoutSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetTillLayoutDataRequest |
| TotalingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | CalculateTotalsServiceRequest, CalculateAmountPaidAndDueServiceRequest, CalculateDepositServiceRequest, GetCustomerOrderCalculationModesServiceRequest |
| TransactionLogService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | SaveTransactionLogServiceRequest |
| TransactionLogSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveTransactionLogDataRequest, InsertTransactionLogDataRequest |
| UnenrollUserCredentialsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UnenrollUserCredentialRequest |
| UnitOfMeasureDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| UnitOfMeasureSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetUnitOfMeasureConversionDataRequest, GetProductItemUnitsDataRequest, GetUnitsOfMeasureDataRequest, GetItemInventoryUnitsOfMeasureDataRequest, GetUnitsOfMeasureOfProductsDataRequest |
| UnlockRegisterRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UnlockRegisterRequest |
| UnlockUserAtLogOffRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | UnlockUserAtLogOffDataRequest |
| UpdateCommissionSalesGroupHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UpdateCommissionSalesGroupRequest |
| UpsService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetShippingRateFromCarrierServiceRequest, GetTrackingInformationFromCarrierServiceRequest, ValidateShippingAddressCarrierServiceRequest |
| UserAlertService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | GetCartLinesUserAlertsForAddServiceRequest, GetCartLinesUserAlertsServiceRequest, GetCartLinesUserAlertErrorsServiceRequest, GetFulfillmentLinesUserAlertsServiceRequest, GetFulfillmentLinesUserAlertErrorsServiceRequest |
| UserDefinedCertificateProfileSqlServerDataService | single_handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetUserDefinedCertificateProfileDataRequest |
| UserDefinedSecretService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | GetUserDefinedSecretStringValueServiceRequest, GetUserDefinedSecretCertificateServiceRequest |
| UserDefinedSecretTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetUserDefinedSecretStringValueRealtimeRequest, GetUserDefinedSecretCertificateRealtimeRequest |
| UserLogOffRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UserLogOffRequest |
| ValidateCashDrawerLimitRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateCashDrawerLimitRequest |
| ValidateSalesLinesQuantityLimitsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateSalesLinesQuantityLimitsRequest |
| ValidateTransactionReturnReasonCodeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateTransactionReturnReasonCodeRequest |
| VendorService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | ValidateVendorApprovedForItemServiceRequest |
| WarrantyService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | ValidateWarrantyPriceApplicabilityServiceRequest |
| XZReportsAustriaService | single_handler | Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll | GetReceiptServiceRequest |
| XZReportsAustriaSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetAustriaShiftStaffTenderedAmountDataRequest, GetClosedAustriaShiftDetailsDataRequest, CalculateShiftAustriaDetailsDataRequest, UpdateShiftStagingTableDataRequest |
| XZReportsAustriaSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll | GetAustriaShiftStaffTenderedAmountDataRequest, GetClosedAustriaShiftDetailsDataRequest, CalculateShiftAustriaDetailsDataRequest, UpdateShiftStagingTableDataRequest |
| XZReportsNorwayService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetXAndZReportReceiptRequest, ChangeShiftStatusRequest |
| XZReportsNorwayService | handler | Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll | GetXAndZReportReceiptRequest, ChangeShiftStatusRequest |
| XZReportsNorwaySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CalculateShiftDetailsNorwayDataRequest, GetLastClosedShiftDetailsNorwayDataRequest, SaveXZReportDataRequest, SaveSalesTransactionDataRequest |
| XZReportsNorwaySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll | CalculateShiftDetailsNorwayDataRequest, GetLastClosedShiftDetailsNorwayDataRequest, SaveXZReportDataRequest, SaveSalesTransactionDataRequest |

## Triggers (3)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| PipelineRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll |  |
| RequestTriggerAdapter | Microsoft.Dynamics.Commerce.Runtime.dll |  |
| XZReportsAustriaService | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetReceiptServiceRequest |
