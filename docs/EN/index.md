# Welcome to the AAPS documentation

![image](./images/basic-outline-of-AAPS.png)

\`\`\`{admonition} Latest Release :class: note

31/12/2025 : Version 3.4 is out. Check the [Release
Notes](#latestrelease) to see what's new and get update instructions.


    Android APS (**AAPS**) is an open source app for people living with insulin-dependent diabetes. It is an artificial pancreas system (APS) which runs on Android smartphones. **AAPS** uses an OpenAPS software algorithm and aims to do what a real pancreas does: keep blood sugar levels within healthy limits by using automated insulin dosing.

    To use **AAPS** you need **three** compatible devices:

    1. an Android phone  
    2. a continuous glucose monitor (CGM)  
    3. a FDA/CE approved insulin pump  

    Optionally you may also use cloud services to remote control **AAPS**, share data and store them in a reporting server, and optionally a smartwatch.

    This documentation explains how to setup and use **AAPS**. You can navigate through the documentation using the menu on the left or by using the [index](#index-aaps-documentation-index) at the bottom of this page.

    ---

    ## Overview of the AAPS documentation ("The docs")

    Section **2) Getting Started**, the [Introduction](Getting-Started/Introduction.md) explains the general concept of what an artificial pancreas system (APS) is designed to do. It outlines the background of looping in general, why **AAPS** was developed, compares **AAPS** to other systems, and addresses safety.

    [Preparing for AAPS](./Getting-Started/PreparingForAaps.md) gives more detail about safety considerations, and the phones, CGMs and insulin pumps which are compatible with **AAPS**. It provides an overview of the process and timeline for gaining full functionality.

    Section **3) Setting up AAPS** contains step-by-step instructions to build and configure the system, including connecting CGM, pump, and reporting servers.

    Section **4) Daily life with AAPS** covers key **AAPS** features including screens, COB, sensitivity detection, profiles, temp targets, automations, and DynamicISF.

    Section **5) Remote AAPS features** explains remote monitoring and remote control capabilities.

    Section **6) Wear OS smartwatches** explains how to use **AAPS** with Wear OS devices.

    Section **7) Maintenance of AAPS** explains backup, updates, release notes, and version upgrades.

    Section **8) Getting Help** explains where to ask questions and troubleshoot issues.

    Section **9) Advanced AAPS options** explains advanced and experimental features.

    Section **10) How to support AAPS** explains how users can contribute to documentation, translations, and development.

    Section **11) Resources** contains additional documentation, glossary, and external references.

    ---

    ### Interested in getting started with **AAPS**?

    Read more in the [Introduction](Getting-Started/Introduction.md).

    ---

    ```{admonition} SAFETY NOTICE
    :class: danger

    The safety of **AAPS** relies on the safety features of your hardware (phone, pump, CGM).

    Only use fully functioning FDA/CE approved insulin pumps and CGM devices.

    Do not use broken, modified or self-built pumps or CGM receivers.

    Only use original consumable supplies approved by the manufacturer.

    Do not use **AAPS** if you take SGLT-2 inhibitors (gliflozins), as they increase the risk of diabetic ketoacidosis.

\`\`\`{admonition} Disclaimer :class: note

All information and code described here is for informational and
educational purposes only.

Use **Nightscout** and **AAPS** at your own risk and do not use the
information or code to make medical decisions.

Nightscout currently makes no attempt at HIPAA privacy compliance.

Use of code from GitHub is without warranty or formal support.

All trademarks remain property of their respective holders.

**AAPS** has no association with or endorsement by SOOIL, Dexcom, Roche
Diabetes Care, Insulet or Medtronic.


    ---

    (index-aaps-documentation-index)=

    ## AAPS Documentation Index

    ```{toctree}
    :caption: 1) Change language
    :maxdepth: 2

    NavigateDoc/ChangeLanguage
    NavigateDoc/ChangeVersion

\`\`\`{toctree} :caption: 2) Getting started :maxdepth: 2

Getting-Started/Introduction Getting-Started/PreparingForAaps
Getting-Started/ComponentOverview Getting-Started/CompatiblePumps
Getting-Started/CompatiblesCgms Getting-Started/Phones
Getting-Started/Watches


    ```{toctree}
    :caption: 3) Setting up AAPS
    :maxdepth: 2

    SettingUpAaps/SettingUpTheReportingServer
    SettingUpAaps/Nightscout
    SettingUpAaps/Tidepool
    SettingUpAaps/BuildingAaps
    SettingUpAaps/BrowserBuild
    SettingUpAaps/ComputerBuild
    SettingUpAaps/TransferringAndInstallingAaps
    SettingUpAaps/SetupWizard
    SettingUpAaps/YourAapsProfile
    SettingUpAaps/ChangeAapsConfiguration
    SettingUpAaps/ConfigBuilder
    SettingUpAaps/Preferences
    SettingUpAaps/CompletingTheObjectives

\`\`\`{toctree} :caption: 4) Daily Life with AAPS :maxdepth: 2

DailyLifeWithAaps/AapsScreens DailyLifeWithAaps/KeyAapsFeatures
DailyLifeWithAaps/CobCalculation
DailyLifeWithAaps/SensitivityDetectionAndCob
DailyLifeWithAaps/ProfileSwitch-ProfilePercentage
DailyLifeWithAaps/TempTargets DailyLifeWithAaps/ExtendedCarbs
DailyLifeWithAaps/Automations DailyLifeWithAaps/DynamicISF
DailyLifeWithAaps/AapsForChildren DailyLifeWithAaps/PumpsAndCannulas
DailyLifeWithAaps/TimezoneTraveling-DaylightSavingTime


    ```{toctree}
    :caption: 5) Remote AAPS features
    :maxdepth: 2

    RemoteFeatures/RemoteMonitoring
    RemoteFeatures/RemoteControl
    RemoteFeatures/SMSCommands
    RemoteFeatures/FollowingOnly
    RemoteFeatures/AndroidAuto

\`\`\`{toctree} :caption: 6) Wear OS Smartwatches :maxdepth: 2

WearOS/BuildingAapsWearOS WearOS/WearOsSmartwatch
RemoteFeatures/RemoteControlWearOS
ExchangeSiteCustomWatchfaces/CustomWatchfaceReference
ExchangeSiteCustomWatchfaces/index


    ```{toctree}
    :caption: 7) Maintenance of AAPS
    :maxdepth: 2

    Maintenance/ExportImportSettings
    Maintenance/Reviewing
    Maintenance/ReleaseNotes
    Maintenance/DocumentationUpdate
    Maintenance/UpdateToNewVersion
    Maintenance/UpdateBrowserBuild
    Maintenance/UpdateComputerBuild

\`\`\`{toctree} :caption: 8) Getting Help :maxdepth: 2

GettingHelp/WhereCanIGetHelp GettingHelp/GeneralTroubleshooting
GettingHelp/BluetoothTroubleshooting GettingHelp/ProfileTuning
GettingHelp/TroubleshootingAndroidStudio GettingHelp/AccessingLogFiles


    ```{toctree}
    :caption: 9) Advanced AAPS options
    :maxdepth: 2

    AdvancedOptions/FullClosedLoop
    AdvancedOptions/DevBranch
    AdvancedOptions/Autotune

\`\`\`{toctree} :caption: 10) How to support AAPS :maxdepth: 2

SupportingAaps/HowCanIHelp SupportingAaps/HowToEditTheDocs
SupportingAaps/Translations SupportingAaps/StateOfTranslations
SupportingAaps/OpenHumans


    ```{toctree}
    :caption: 11) Resources
    :maxdepth: 2

    UsefulLinks/Glossary
    UsefulLinks/FAQ
    UsefulLinks/BackgroundReading
    UsefulLinks/DedicatedGoogleAccountForAaps
    UsefulLinks/ClinicianGuideToAaps
