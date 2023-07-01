<!-- Navigation top -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`cli`__][content2] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`runter`__][bottom] _`home/cli/system_profiler`_

<!-- Navigation links -->
[home]:     ./home
[seiten]:   ./home-pages
[content]:  ./home-az
[content2]: ./cli-befehle-az
[left]:     ./cli-befehl-system_profiler
[up]:       ./home-cli
[right]:    ./cli-befehl-system_profiler
[top]:      #
[bottom]:   #links

<!-- CONTENT START ############################################## -->

## system_profiler

Gibt Systemdaten des Rechners aus. 

Inhalt:
- [-listDataTypes](#-listDataTypes)
- [SPDeveloperToolsDataType](#SPDeveloperToolsDataType)
- [SPHardwareDataType](#SPHardwareDataType)
- [SPPowerDataType](#SPPowerDataType)
- [SPSoftwareDataType](#SPSoftwareDataType) 

<br>

##### -listDataTypes

```console
> system_profiler -listDataTypes
Available Datatypes:
SPParallelATADataType
SPUniversalAccessDataType
SPSecureElementDataType
SPApplicationsDataType
SPAudioDataType
SPBluetoothDataType
SPCameraDataType
SPCardReaderDataType
SPiBridgeDataType
SPDeveloperToolsDataType
SPDiagnosticsDataType
SPDisabledSoftwareDataType
SPDiscBurningDataType
SPEthernetDataType
SPExtensionsDataType
SPFibreChannelDataType
SPFireWireDataType
SPFirewallDataType
SPFontsDataType
SPFrameworksDataType
SPDisplaysDataType
SPHardwareDataType
SPInstallHistoryDataType
SPInternationalDataType
SPLegacySoftwareDataType
SPNetworkLocationDataType
SPLogsDataType
SPManagedClientDataType
SPMemoryDataType
SPNVMeDataType
SPNetworkDataType
SPPCIDataType
SPParallelSCSIDataType
SPPowerDataType
SPPrefPaneDataType
SPPrintersSoftwareDataType
SPPrintersDataType
SPConfigurationProfileDataType
SPRawCameraDataType
SPSASDataType
SPSerialATADataType
SPSPIDataType
SPSmartCardsDataType
SPSoftwareDataType
SPStartupItemDataType
SPStorageDataType
SPSyncServicesDataType
SPThunderboltDataType
SPUSBDataType
SPNetworkVolumeDataType
SPWWANDataType
SPAirPortDataType
```

[__`rauf`__][top] [__`runter`__][bottom]

---
##### SPDeveloperToolsDataType

```console
> system_profiler SPDeveloperToolsDataType
Developer:

    Developer Tools:

      Version: 13.4.1 (13F100)
      Location: /Applications/Xcode.app
      Applications:
          Xcode: 13.4.1 (20504)
          Instruments: 13.4.1 (64553.4)
      SDKs:
          DriverKit:
              21,4:
          iOS:
              15,5: (19F64)
          iOS Simulator:
              15,5: (19F64)
          macOS:
              12,3: (21E226)
          tvOS:
              15,4: (19L439)
          tvOS Simulator:
              15,4: (19L439)
          watchOS:
              8,5: (19T241)
          watchOS Simulator:
              8,5: (19T241)
```

[__`rauf`__][top] [__`runter`__][bottom]

---
##### SPHardwareDataType

```console
> system_profiler SPHardwareDataType
Hardware:

    Hardware Overview:

      Model Name: MacBook Pro
      Model Identifier: MacBookPro12,1
      Processor Name: Dual-Core Intel Core i7
      Processor Speed: 3,1 GHz
      Number of Processors: 1
      Total Number of Cores: 2
      L2 Cache (per Core): 256 KB
      L3 Cache: 4 MB
      Hyper-Threading Technology: Enabled
      Memory: 16 GB
      System Firmware Version: 481.0.0.0.0
      OS Loader Version: 540.120.3~22
      SMC Version (system): 2.28f7
      Serial Number (system): C02QD33KFVH8
      Hardware UUID: EEED1B91-54BF-5776-9B19-85BBDDB77E1B
      Provisioning UDID: EEED1B91-54BF-5776-9B19-85BBDDB77E1B
```

[__`rauf`__][top] [__`runter`__][bottom]

---
##### SPPowerDataType

```console
❯  system_profiler SPPowerDataType
Power:

    Battery Information:

      Model Information:
          Serial Number: C01514309YEF90MA4
          Manufacturer: ifixit
          Device Name: bq20z451
          Pack Lot Code: 3230
          PCB Lot Code: 3230
          Firmware Version: 2d31
          Hardware Revision: 322d
          Cell Revision: 3036
      Charge Information:
          Fully Charged: Yes
          Charging: No
          Full Charge Capacity (mAh): 6227
          State of Charge (%): 100
      Health Information:
          Cycle Count: 24
          Condition: Normal

    ...
```

[__`rauf`__][top] [__`runter`__][bottom]

---
##### SPSoftwareDataType

```console
> system_profiler SPSoftwareDataType
Software:

    System Software Overview:

      System Version: macOS 12.6.6 (21G646)
      Kernel Version: Darwin 21.6.0
      Boot Volume: SSD
      Boot Mode: Normal
      Computer Name: Tests MacBook Pro
      User Name: volker (xxx)
      Secure Virtual Memory: Enabled
      System Integrity Protection: Enabled
      Time since boot: 6:04
```

[__`rauf`__][top] [__`runter`__][bottom]

<!--
```console
```
```console
```
```console
```
-->

<!-- Content navigation -->
[](#) [](#) [](#)

<!-- ToDos -->
<!-- 
-->

<!--
### CHAPTER

#### SUBCHAPTER
-->

<!-- Program code -->
<!--
```swift
// Programmcode
```
-->

<!-- CONTENT END ############################################## -->

<!-- Navigation [__`rauf`__][top] [__`runter`__][bottom] -->

<!-- Links --> <br>
##### Links:
<!--   
[`TEXT`](LINK) _<sub>`von apple documentation`</sub>_
[`TEXT`](LINK) _<sub>`von swift.org`</sub>_   
[`TEXT`](LINK) _<sub>`by AUTHOR, YEAR`</sub>_
-->

<!--
##### Videos:
[`TEXT`](LINK) _<sub>`by AUTHOR, YEAR, Xmin`</sub>_
-->

<!-- Navigation bottom --> <br>
<!-- ###### <sub>_</sub> Ersatz Sprungmarke, wenn keine '##### Links:' vorhanden ist. -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`cli`__][content2] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`rauf`__][top]