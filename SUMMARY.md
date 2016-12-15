# Summary

* [General platform architecture](Architecture/README.md)
   * [Platform properties](Architecture/OSGPProperties.md)
   * [Architecture introduction](Architecture/Architecture-introduction.md)
   * [Architecture functional layers](Architecture/Functionallayersoverview.md)
   * [Architecture Principles](Architecture/Architecture-Principles.md)
   * [Platform components description](Architecture/Platform-components-description.md)
   * [Message flow examples](Architecture/Messageflow.md)
   * [Logical Authorisation Model](Architecture/Logical-Authorisation-Model.md)
   * [Non-functional overview](Architecture/Non-functional-overview.md)
      * [TimeBehavior](Architecture/TimeBehavior.md)
      * [Internationalization and localization](Architecture/Internationalizationlocalization.md)
      * [Security](Architecture/security.md)
      * [Scalability](Architecture/Scalability.md)
      * [Redundancy](Architecture/Redundancy.md)
      * [Performance](Architecture/Performance.md)
   * [Technical Overview](Architecture/Technical-overview/TechnicalOverview.md)
      * [Web Services Layer](Architecture/Technical-overview/WebServicesLayer.md)
      * [Domain Layer](Architecture/Technical-overview/DomainLayer.md)
      * [Core Layer](Architecture/Technical-overview/CoreLayer.md)
      * [Protocol Layer](Architecture/Technical-overview/ProtocolLayer.md)
      * [Technology Stack](Architecture/Technical-overview/Technologystack.md)
   * [Use cases](Architecture/Use-cases.md)

* [General User's Guide](Userguide/README.md)
   * [Installation Guide](Userguide/Installation/Installationguide.md)
      * [Installation](Userguide/Installation/installation.md)
	    * [Vagrant](Userguide/Installation/Setup-VM-Vagrant.md)
	    * [Manual Setup](Userguide/Installation/manualInstallation.md)
      * [Platform Setup](Userguide/Installation/setupOSGP.md)
      * [Test the Platform](Userguide/Installation/request.md)
        * [Using SoapUi](Userguide/Installation/testOSGP.md)
        * [Using the Demo App](Userguide/Installation/TestOsgpDemoApp.md)
   * [Configuration](Userguide/Configuration.md)
      * [Add a device](Userguide/Addadevice.md)
      * [Users](Userguide/Users.md)
      * [Add a new organisation](Userguide/addOrganisation.md)
   * [Web Services](Userguide/GuideToWebServices.md)
   * [Deployment](Userguide/Deployment.md)
   * [FAQ](Userguide/FAQ.md)

* [Open Source Community](Opensourcecommunity/README.md)
   * [Start contributing](Opensourcecommunity/Getstarted.md)
   * [Developers 101](Opensourcecommunity/ToolsguidelinesCI.md)
   * [Contributing to the code](Opensourcecommunity/Contributing-to-the-code.md)
   * [Contributing to documentation](Opensourcecommunity/Contributing-to-documentation.md)
   * [Communication and Contact](Opensourcecommunity/Communication-and-contact.md)
   * [Governance](Opensourcecommunity/Governance.md)
   * [Code of Conduct](Opensourcecommunity/Code-of-conduct.md)
   * [Foundation](Opensourcecommunity/Foundation.md)

* [Domains](Domains/README.md)
   * [Admin](Domains/Admin/README.md)
   * [Smart lighting](Domains/Smartlighting/README.md)
      * [Use cases](Domains/Smartlighting/Smartlightning-use-cases.md)
   * [Tariff switching](Domains/Tariffswitching/README.md)
   * [Microgrids](Domains/Microgrids/README.md)
   * [SmartMetering](Domains/Smartmetering/README.md)
     * [Web Services](Domains/Smartmetering/smartmeteringwebservices/SmartMeteringWs.md)
        * [AdHocManagement](Domains/Smartmetering/smartmeteringwebservices/AdHocManagement.md)
            * [GetAssociationLnObjects](Domains/Smartmetering/smartmeteringwebservices/GetAssociationLnObjects.md)
            * [GetGetAssociationLnObjectsResponse](Domains/Smartmetering/smartmeteringwebservices/GetGetAssociationLnObjectsResponse.md)
            * [RetrieveConfigurationObjects](Domains/Smartmetering/smartmeteringwebservices/RetrieveConfigurationObjects.md)
            * [GetRetrieveConfigurationObjectsResponse](Domains/Smartmetering/smartmeteringwebservices/GetRetrieveConfigurationObjectsResponse.md)
            * [SpecificConfigurationObject](Domains/Smartmetering/smartmeteringwebservices/SpecificConfigurationObject.md)
            * [SynchronizeTime](Domains/Smartmetering/smartmeteringwebservices/SynchronizeTime.md)
            * [GetSynchronizeTimeResponse](Domains/Smartmetering/smartmeteringwebservices/GetSynchronizeTimeResponse.md)
        * [Bundle](Domains/Smartmetering/smartmeteringwebservices/bundeling.md)
            * [Bundle](Domains/Smartmetering/smartmeteringwebservices/Bundle.md)
            * [GetBundleResponse](Domains/Smartmetering/smartmeteringwebservices/GetBundleResponse.md)
        * [Configuration](Domains/Smartmetering/smartmeteringwebservices/Configuration.md)
            * [GetAdministrativeStatus](Domains/Smartmetering/smartmeteringwebservices/GetAdministrativeStatus.md)
            * [GetGetAdministrativeStatusResponse](Domains/Smartmetering/smartmeteringwebservices/GetGetAdministrativeStatusResponse.md)
            * [GetFirmwareVersion](Domains/Smartmetering/smartmeteringwebservices/GetFirmwareVersion.md)
            * [GetGetFirmwareVersionResponse](Domains/Smartmetering/smartmeteringwebservices/GetGetFirmwareVersionResponse.md)
            * [UpdateFirmware](Domains/Smartmetering/smartmeteringwebservices/UpdateFirmware.md)
            * [GetUpdateFirmwareResponse](Domains/Smartmetering/smartmeteringwebservices/GetUpdateFirmwareResponse.md)
            * [ReplaceKeys](Domains/Smartmetering/smartmeteringwebservices/ReplaceKeys.md)
            * [GetReplaceKeysResponse](Domains/Smartmetering/smartmeteringwebservices/GetReplaceKeysResponse.md)
            * [SetActivityCalendar](Domains/Smartmetering/smartmeteringwebservices/SetActivityCalendar.md)
            * [GetSetActivityCalendarResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetActivityCalendarResponse.md)
            * [SetAdministrativeStatus](Domains/Smartmetering/smartmeteringwebservices/SetAdministrativeStatus.md)
            * [GetSetAdministrativeStatusResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetAdministrativeStatusResponse.md)
            * [SetAlarmNotifications](Domains/Smartmetering/smartmeteringwebservices/SetAlarmNotifications.md)
            * [GetSetAlarmNotificationsResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetAlarmNotificationsResponse.md)
            * [SetConfigurationObject](Domains/Smartmetering/smartmeteringwebservices/SetConfigurationObject.md)
            * [GetSetConfigurationObjectResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetConfigurationObjectResponse.md)
            * [SetEncryptionKeyExchangeOnGMeter](Domains/Smartmetering/smartmeteringwebservices/SetEncryptionKeyExchangeOnGMeter.md)
            * [GetSetEncryptionKeyExchangeOnGMeterResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetEncryptionKeyExchangeOnGMeterResponse.md)
            * [SetPushSetupAlarm](Domains/Smartmetering/smartmeteringwebservices/SetPushSetupAlarm.md)
            * [GetSetPushSetupAlarmResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetPushSetupAlarmResponse.md)
            * [SetPushSetupSms](Domains/Smartmetering/smartmeteringwebservices/SetPushSetupAlarm.md)
            * [GetSetPushSetupSmsResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetPushSetupSmsResponse.md)
            * [SetSpecialDays](Domains/Smartmetering/smartmeteringwebservices/SetSpecialDays.md)
            * [GetSetSpecialDaysResponse](Domains/Smartmetering/smartmeteringwebservices/GetSetSpecialDaysResponse.md)
        * [Installation](Domains/Smartmetering/smartmeteringwebservices/Installation.md)
            * [AddDevice](Domains/Smartmetering/smartmeteringwebservices/AddDevice.md)
            * [GetAddDeviceResponse](Domains/Smartmetering/smartmeteringwebservices/GetAddDeviceResponse.md)
            * [CoupleMbusDevice](Domains/Smartmetering/smartmeteringwebservices/CoupleMbusDevice.md)
            * [GetCoupleMbusDeviceResponse](Domains/Smartmetering/smartmeteringwebservices/GetCoupleMbusDeviceResponse.md)
            * [DeCoupleMbusDevice](Domains/Smartmetering/smartmeteringwebservices/DeCoupleMbusDevice.md)
            * [GetDeCoupleMbusDeviceResponse](Domains/Smartmetering/smartmeteringwebservices/GetDeCoupleMbusDeviceResponse.md)
        * [Management](Domains/Smartmetering/smartmeteringwebservices/Management.md)
            * [FindEvents](Domains/Smartmetering/smartmeteringwebservices/FindEvents.md)
            * [GetFindEventsResponse](Domains/Smartmetering/smartmeteringwebservices/GetFindEventsResponse.md)
            * [GetDevices](Domains/Smartmetering/smartmeteringwebservices/GetDevices.md)

            * [EnableDebugging](Domains/Smartmetering/smartmeteringwebservices/EnableDebugging.md)
            * [DisableDebugging](Domains/Smartmetering/smartmeteringwebservices/DisableDebugging.md)
            * [FindMessageLogs](Domains/Smartmetering/smartmeteringwebservices/FindMessageLogs.md)
        * [Monitoring](Domains/Smartmetering/smartmeteringwebservices/Monitoring.md)
            * [GetActualMeterReads](Domains/Smartmetering/smartmeteringwebservices/GetActualMeterReads.md)
            * [GetActualMeterReadsResponse](Domains/Smartmetering/smartmeteringwebservices/GetActualMeterReadsResponse.md)
            * [GetActualMeterReadsGas](Domains/Smartmetering/smartmeteringwebservices/GetActualMeterReadsGas.md)
            * [GetActualMeterReadsGasResponse](Domains/Smartmetering/smartmeteringwebservices/GetActualMeterReadsGasResponse.md)
            * [GetPeriodicMeterReads](Domains/Smartmetering/smartmeteringwebservices/GetPeriodicMeterReads.md)
            * [GetPeriodicMeterReadsResponse](Domains/Smartmetering/smartmeteringwebservices/GetPeriodicMeterReadsResponse.md)
            * [GetPeriodicMeterReadsGas](Domains/Smartmetering/smartmeteringwebservices/GetPeriodicMeterReadsGas.md)
            * [GetPeriodicMeterReadsGasResponse](Domains/Smartmetering/smartmeteringwebservices/GetPeriodicMeterReadsGasResponse.md)
            * [ReadAlarmRegister](Domains/Smartmetering/smartmeteringwebservices/ReadAlarmRegister.md)
            * [GetReadAlarmRegisterResponse](Domains/Smartmetering/smartmeteringwebservices/GetReadAlarmRegisterResponse.md)
            * [RetrievePushNotificationAlarm](Domains/Smartmetering/smartmeteringwebservices/RetrievePushNotificationAlarm.md)
        * [Notification](Domains/Smartmetering/smartmeteringwebservices/Notifications.md)
            * [SendNotification](Domains/Smartmetering/smartmeteringwebservices/SendNotification.md)
     * [ResponseMessages](Domains/Smartmetering/smartmeteringwebservices/ResponseMessages.md)
     * [Use cases](Domains/Smartmetering/Smartmetering-use-cases.md)
* [Protocols](Protocols/README.md)
   * [IEC 61850](Protocols/IEC61850/README.md)
   * [DLMS / COSEM](Protocols/DLMS/README.md)
      * [DLMS device simulator](Protocols/DLMS/Devicesimulator.md)
   * [OSLP](Protocols/OSLP/README.md)
      * [OSLP v0.5.1](Protocols/OSLP/oslp-v0.5.1.md)
         * [RegisterDevice](Protocols/OSLP/v0.5.1/RegisterDevice.md)
         * [ConfirmRegisterDevice](Protocols/OSLP/v0.5.1/ConfirmRegisterDevice.md)
         * [GetConfiguration](Protocols/OSLP/v0.5.1/GetConfiguration.md)
         * [SetConfiguration](Protocols/OSLP/v0.5.1/SetConfiguration.md)
         * [SetEventNotifications](Protocols/OSLP/v0.5.1/SetEventNotifications.md)
         * [EventNotification](Protocols/OSLP/v0.5.1/EventNotification.md)
         * [SetSchedule](Protocols/OSLP/v0.5.1/SetSchedule.md)
         * [ResumeSchedule](Protocols/OSLP/v0.5.1/ResumeSchedule.md)
         * [GetFirmwareVersion](Protocols/OSLP/v0.5.1/GetFirmwareVersion.md)
         * [UpdateFirmware](Protocols/OSLP/v0.5.1/UpdateFirmware.md)
         * [SetReboot](Protocols/OSLP/v0.5.1/SetReboot.md)
         * [StartSelfTest](Protocols/OSLP/v0.5.1/StartSelfTest.md)
         * [StopSelfTest](Protocols/OSLP/v0.5.1/StopSelfTest.md)
         * [SetLight](Protocols/OSLP/v0.5.1/SetLight.md)
         * [SetTransition](Protocols/OSLP/v0.5.1/SetTransition.md)
         * [GetStatus](Protocols/OSLP/v0.5.1/GetStatus.md)
         * [GetActualPowerUsage](Protocols/OSLP/v0.5.1/GetActualPowerUsage.md)
         * [GetPowerUsageHistory](Protocols/OSLP/v0.5.1/GetPowerUsageHistory.md)
         * [Protobuf Contract](Protocols/OSLP/v0.5.1/oslp.proto.v0.5.1.md)
      * [OSLP v0.6.1](Protocols/OSLP/oslp-v0.6.1.md)
         * [GetConfiguration](Protocols/OSLP/v0.6.1/GetConfiguration.md)
         * [SetConfiguration](Protocols/OSLP/v0.6.1/SetConfiguration.md)
         * [SetSchedule](Protocols/OSLP/v0.6.1/SetSchedule.md)
         * [GetStatus](Protocols/OSLP/v0.6.1/GetStatus.md)
         * [UpdateDeviceSslCertification](Protocols/OSLP/v0.6.1/UpdateDeviceSslCertification.md)
         * [SetDeviceVerificationKey](Protocols/OSLP/v0.6.1/SetDeviceVerificationKey.md)
         * [SwitchFirmware](Protocols/OSLP/v0.6.1/SwitchFirmware.md)
         * [SwitchConfiguration](Protocols/OSLP/v0.6.1/SwitchConfiguration.md)
         * [Protobuf Contract](Protocols/OSLP/v0.6.1/oslp.proto.v0.6.1.md)
* [Support](Support/README.md)
* [License](Apache-license/README.md)