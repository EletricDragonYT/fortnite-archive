# Fortnite Archive
## Navigation
- Available Builds
  - [Windows](/Available/Windows%20Archive.md)
  - UEFN
  - MacOS
  - Xbox
  - PlayStation
  - Switch
  - Android
  - IOS

- Unavailable Builds
  - [Windows](/Unavailable/Windows%20Archive.md)
  - UEFN
  - MacOS
  - Xbox
  - PlayStation
  - Switch
  - Android
  - IOS

## General Information
[Legendary and Manifest Download Tutorial](https://drive.google.com/drive/u/0/folders/1NXsfDJEwNBanjWFaLaZH7q3IdY3eKuEE)

How to View CL Versions
- CrashReportClient<sup>(Exceptions: v5.00 - v6.31-CL-4573279, v9.10-CL-6639283, and v11.40-CL-11039906)</sup>
  - Open `Fortnite\Engine\Binaries\Win64` -> right click CrashReportClient -> Properties -> Details -> Product Version
  - Open `Fortnite\Engine\Binaries\Win64` -> right click CrashReportClientEditor -> Properties -> Details -> Product Version
  - Open `Fortnite\Engine\Binaries\Win64` -> double click CrashReportClient -> `C:\Users\{user}\AppData\Local\CrashReportClient\Saved\Logs` -> LogInit: Build:
- [sysinternals](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer)
  - Double click sysinternals
  - Double click `Fortnite\FortniteGame\Binaries\Win64\FortniteClient-Win64-Shipping`
  - In sysinternals, find and double click `FortniteClient-Win64-Shipping.exe` -> Strings -> Save
  - In the saved .txt file, search for "-CL"
    - Must be done quickly if the file opens the Epic Games launcher, closing `FortniteClient-Win64-Shipping.exe`.
- FortniteClient-Win64-Shipping<sup>(Only v5.21-CL-4288479 - v6.31-CL-4573279)</sup>
  - Doule click `Fortnite\FortniteGame\Binaries\Win64\FortniteClient-Win64-Shipping.exe` -> top middle of the login screen

How to View Hotfixes: `C:\Users\{user}\AppData\Local\FortniteGame\Saved\PersistentDownloadDir\EMS`

## Tables
- Build: The version and changelist (CL) from `LogInit: Build:`, obtained from the CrashReportClient log file.
- Manifest: A file used to install a corresponding build.
- Mapping: A file used within FModel to view the names and structure of files within a build.
- AES Keys: A key or collection of keys used within FModel to decrypt .pak files.
- Unreal Engine: The UE version from `LogInit: Compatible Engine Version:`, obtained from the CrashReportClient log file.
- - The builds CL is the primary UE version, therefor the range is this; `Compatible UE Version` - `UE Version`.
- Net CL: The network changelist from `LogInit: Net CL:`, obtained from the CrashReportClient log file.
- Build Date: The compilation date from `LogInit: Compiled (64-bit):`, obtained from the CrashReportClient log file.

## External Links
All download ranges should be taken with a grain of salt, many builds are lost, unavailable and/or gatekept.

Windows Build Archives
- [ElectricArchive - Me](https://archive.org/details/@electric_dragon155/uploads?sort=title&and%5B%5D=subject%3A%22Windows+Fortnite%22): Online Test 6.5 - Season 11, v14.60, Season 24 and Season 34 - Season 39.
- [FortForge - Jalen and Pakked](https://fortforge.dev/builds): Online Test 6.5 - Season 40. Includes AES Keys, Mapping Files, UE Versions and Build Dates.
- [Repressoh - Alberto](https://fn-builds.repressoh.it): Online Test 6.5 - Season 40.
- [fortnite-builds-archive - Helix-Dev-Q](https://github.com/Helix-Dev-Q/fortnite-builds-archive): Online Test 6.5 - Season 40.
- [fortnite-builds-archive - LlamaQwerty](https://github.com/llamaqwerty/fortnite-builds-archive): Online Test 6.5 - Season 38 and QAGame
- [FortniteBuilds - Ralzify (Currently Down)](https://github.com/Ralzify/FortniteBuilds): Online Test 6.5 - Season 35.
- [Fortnite-Versions - ByZNexus](https://github.com/ByZNexus/Fortnite-Versions): Online Test 6.5 - Season 34. Includes UE Versions and Build Dates.
- [Fortnitebuilds - itztiva](https://github.com/itztiva/Fortnitebuilds): Online Test 6.5 - Season 27.
- [Fortnite-Builds - VerzeHxD](https://github.com/VerzeHxD/Fortnite-Builds): Online Test 6.5 - Season 24.
- [Fortnitebuilds - n6617x](https://github.com/n6617x/Fortnitebuilds): Online Test 6.5 - Season 20. Includes UE Versions and Build Dates.
- [The-Archive - chipset808](https://github.com/chipset808/The-Archive): Online Test 6.5 - Season X.
- [Fortnite-Builds - notsamicc (Currently Down)](https://github.com/notsamicc/Fortnite-Builds): Online Test 6.5 - Season 7. Includes UE Versions and Build Dates.
- [Carbon Builds - Carbon Team](https://builds.cbn.lol/builds): Pre-Season - Season 30.

Windows Manifest Archives
- [ElectricArchive - Me](https://archive.org/details/@electric_dragon155/uploads?sort=title&and%5B%5D=subject%3A%22Fortnite+Manifests%22): Season 3 - Season 11, and Season 24.
- [fn-releases - Polynite](https://github.com/polynite/fn-releases): Season 1 - Season 40. Includes Net CLs, UE Versions and Build Dates
- [FortniteManifestArchive - VastBlast](https://github.com/VastBlast/FortniteManifestArchive): Season 2 - Season 21.

UEFN Archives
- [ElectricArchive - Me](https://archive.org/details/@electric_dragon155/uploads?sort=title&and%5B%5D=subject%3A%22Fortnite%3A+UEFN%22): Season 24.
- [FortForge - Jalen and Pakked](https://fortforge.dev/builds): Season 24 - Season 40.

UEFN Manifest Archives
- [ElectricArchive - Me](https://archive.org/details/@electric_dragon155/uploads?sort=title&and%5B%5D=subject%3A%22Fortnite%3A+UEFN+Manifests%22): Season 24.
- [UEFN-releases - Mast3rGamers](https://github.com/Mast3rGamers/UEFN-releases): Season 24 - Season 40.

China Build and Installer Archives
- [Tencent-Fortnite-China-Archive - KPMisParrot](https://github.com/KPMisParrot/Tencent-Fortnite-China-Archive): Season 5 - Season 18.
- [Fortnite-China-Archive - simonhxd](https://github.com/simonhxd/Fortnite-China-Archive): Season 5 - Season 18.

MacOS Build Archives
- [Repressoh - Alberto](https://fn-builds.repressoh.it/MacBuilds/): v3.1-3915963 and v7.00.

Xbox Build and .xvc Archives
- [FortniteXboxBuilds - Xader726](https://github.com/Xader726/FortniteXboxBuilds): Online Test 11.0.?-CL-3472997 - Season 38.
- [fortnite-xbox-one-dumps - somexboxdumps](https://archive.org/download/fortnite-xbox-one-dumps): Online Test 11.0.?-CL-3472997 - Season 10

PlayStation Build and .pkg Archives
- [CUSA07022 - orbispatches](https://orbispatches.com/CUSA07022) (US): Season 0 - Season 39.<sup>.pkg only</sup>
- [CUSA07669 - orbispatches](https://orbispatches.com/CUSA07669) (EU): Season 0 - Season 39.<sup>.pkg only</sup>
- [FortnitePS4ArchiveBuild - YorhaX2P](https://github.com/YorhaX2P/FortnitePS4ArchiveBuild): Season 0 and Season 1.<sup>.pkg only</sup>
- [CUSA07574 - orbispatches](https://orbispatches.com/CUSA07574): Download for Online Test 10 / MailApp.<sup>.pkg only</sup>
- [fortnite-mailapp-ot10 - galaxify](https://archive.org/details/fortnite-mailapp-ot10): Download for Online Test 10 / MailApp

Android .apk Archives
- [FortniteAndroidBuilds - andr1ww](https://github.com/andr1ww/FortniteAndroidBuilds): Season 5 - Season 21.

IOS Build and .ipa Archives
- [Repressoh - Alberto](https://fn-builds.repressoh.it/IPAs/): Season 3 - Season 13.<sup>.ipa only</sup>
- [FNiOS-Archive - Crunnie](https://github.com/Crunnie/FNiOS-Archive): Season 3 - Season 13.<sup>.ipa only</sup>
- [FN-IOS-Archive - mtbr29](https://github.com/mtbr29/FN-IOS-Archive): Season 3 - Season 13.

Switch .nsp Archives
- [Repressoh - Alberto](https://fn-builds.repressoh.it/Switch/): Season 4 - Season 19 and Base
- [FortniteSwitchBuilds - n6617x](https://github.com/n6617x/FortniteSwitchBuilds): Season 4 - Season 19 and Base

## Credits
There is a lack of credits here, this isn't because I'm selfish but because the origin of a build varies heavily. Strictly speaking, all builds originate from Epic Games, the developers and publishers of Fortnite. 
However, that isn't where modern day downloads to builds before v24.20 originate from anymore. Below is a sort of extension of the external links section, and many familiar names will popup.
- Alberto
- andr1ww
- ByZNexus
- Carbon Team
- chipset808
- Crunnie
- [evan_runner](https://archive.org/details/@evan_runner): OT11.??-Cert-CL-3532353
- galaxify
- Helix-Dev-Q: Their archive mentions more people
- itztiva
- Jalen
- Ka Pum: v19.01-CL-18489740
- KPMisParrot
- LlamaQwerty: Their archive used to mention more people
- Mast3rGamers
- mtbr29
- n6617x
- notsamicc: Decided they were better than us and left
- orbispatches
- Pakked
- Polynite
- Ralzify: Decided they were better than us and left
- simonhxd
- somexboxdumps
- VastBlast
- Xader726
- YorhaX2P


- Unknown (builds.rebootfn.org): v1.7.2-Cert-CL-3700114 - v10.31-CL-8723043, minus some exceptions
- Unknown (cdn.cbn.lol): v12.41-CL-12905909, v18.10-CL-17661844 and v18.20-CL-17745267, v20.30-CL-19950687, and v21.20-CL-20978394
- Unknwon (public-build-archives-bucket.erafn.dev): v5.41-CL-4363240 and v6.21-CL-4526925
- Unknown (public.simplyblk.xyz - Currently Down): Online Test 6.5, v1.7.2-Cert-CL-3700114 - v23.50-CL-24441668, minus lost and unavailable builds
- Unknown (r2.kovryn.xyz - Currently Down): v23.50-CL-24441668
- Unknown (r2.ploosh.dev): v15.30-CL-15341163 and v21.00-CL-20463113
- Unknown (titanac.xyz): v23.50-CL-24441668
- Varies ([Internet Archive](https://archive.org/)): The Internet Archive has builds from many seasons.
