# Fortnite Archive
## General Information
[Legendary and Manifest Download Tutorial](https://drive.google.com/drive/u/0/folders/1NXsfDJEwNBanjWFaLaZH7q3IdY3eKuEE)

How to View CL Versions
- CrashReportClient<sup>(Exceptions: v5.00 - v6.31-CL-4573279, v9.10-CL-6639283, and v11.40-CL-11039906)</sup>
- - Open `Fortnite\Engine\Binaries\Win64` -> right click CrashReportClient -> Properties -> Details -> Product Version
- - Open `Fortnite\Engine\Binaries\Win64` -> right click CrashReportClientEditor -> Properties -> Details -> Product Version
- - Open `Fortnite\Engine\Binaries\Win64` -> double click CrashReportClient -> `C:\Users\{user}\AppData\Local\CrashReportClient\Saved\Logs` -> LogInit: Build:
- [sysinternals](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer)
- - Double click sysinternals
- - Double click `Fortnite\FortniteGame\Binaries\Win64\FortniteClient-Win64-Shipping`
- - In sysinternals, find and double click `FortniteClient-Win64-Shipping.exe` -> Strings -> Save
- - In the saved .txt file, search for "-CL"
- - - Must be done quickly if the file opens the Epic Games launcher, closing `FortniteClient-Win64-Shipping.exe`.
- FortniteClient-Win64-Shipping<sup>(Only Works From: v5.?? - v6.31-CL-4573279)</sup>
- - Doule click `Fortnite\FortniteGame\Binaries\Win64\FortniteClient-Win64-Shipping.exe` -> top middle of the login screen
How to View Hotfixes: `C:\Users\{user}\AppData\Local\FortniteGame\Saved\PersistentDownloadDir\EMS`

## External Links
Build Archives
- [ElectricArchive - Me](https://archive.org/details/@electric_dragon155/uploads?sort=title&and%5B%5D=subject%3A%22Windows+Fortnite%22): Downloads for Online Test 6.5 - Season 11, v14.60, Season 24 and Season 34 - Season 39.
- [FortForge - Jalen and Pakked](https://fortforge.dev/builds): Downloads for Online Test 6.5 - Season 40. Includes AES Keys, Mapping Files, UE Versions and Build Dates.
- [Repressoh - Alberto](https://fn-builds.repressoh.it): Downloads for Online Test 6.5 - Season 40.
- [fortnite-builds-archive - Helix-Dev-Q](https://github.com/Helix-Dev-Q/fortnite-builds-archive): Downloads for Online Test 6.5 - Season 40.
- [fortnite-builds-archive - LlamaQwerty](https://github.com/llamaqwerty/fortnite-builds-archive): Downloads for Online Test 6.5 - Season 38 and QAGame
- [FortniteBuilds - Ralzify (Currently Down)](https://github.com/Ralzify/FortniteBuilds): Downloads for Online Test 6.5 - Season 35.
- [Fortnite-Versions - ByZNexus](https://github.com/ByZNexus/Fortnite-Versions): Downloads for Online Test 6.5 - Season 34. Includes UE Versions and Build Dates.
- [Fortnitebuilds - itztiva](https://github.com/itztiva/Fortnitebuilds): Downloads for Online Test 6.5 - Season 27.
- [Fortnite-Builds - VerzeHxD](https://github.com/VerzeHxD/Fortnite-Builds): Downloads for Online Test 6.5 - Season 24.
- [Fortnitebuilds - n6617x](https://github.com/n6617x/Fortnitebuilds): Downloads for Online Test 6.5 - Season 20. Includes UE Versions and Build Dates.
- [The-Archive - chipset808](https://github.com/chipset808/The-Archive): Downloads for Online Test 6.5 - Season X.
- [Fortnite-Builds - notsamicc (Currently Down)](https://github.com/notsamicc/Fortnite-Builds): Downloads for Online Test 6.5 - Season 7. Includes UE Versions and Build Dates.
- [Carbon Builds - Carbon Team](https://builds.cbn.lol/builds): Downloads for Pre-Season - Season 30.

## Tables
- Build: The version and changelist (CL) from `LogInit: Build:`, obtained from the CrashReportClient log file.
- Manifest: A download link to the corresponding manifest file.
- Mapping: A download link to the corresponding mapping file.
- AES Keys: A link to the corresponding AES keys.
- Unreal Engine: The UE version from `LogInit: Compatible Engine Version:`, obtained from the CrashReportClient log file.
- - The builds CL is the primary UE version, therefor the range is roughly this; `Compatible UE Version - UE Version`.
- Net CL: The network changelist from `LogInit: Net CL:`, obtained from the CrashReportClient log file.
- Build Date: The compilation date from `LogInit: Compiled (64-bit):`, obtained from the CrashReportClient log file.

# Builds
## Online Tests
| Build | Manifest | Mapping | AES | UE Version | Net CL | Build Date |
| ----- | -------- | ------- | --- | ---------- | ------ | ---------- |
| [OT6.5-Live-CL-2870186](https://archive.org/download/fn-ot-archive/OT6.5-Live-CL-2870186.7z) | None | None | None | 4.12.0-2870186 | 2870186 | 2016/02/17 |
| [OT??](https://archive.org/download/fortnite-ot-11-pc) | None | None | None | 4.16.0-3532353 | | 2017/06/0? |
| [OT11.??-Cert-CL-3532353](https://archive.org/download/fn-v0-archive/Cert-CL-3532353.7z) | None | None | None | 4.16.0-3532353 | 3528277 | 2017/07/11 |

| Build                   | Engine version | Net CL  | Build date | Manifest | Notes       |
| ----------------------- | -------------- | ------- | ---------- | -------- | ----------- |
| Cert-CL-3541083         | 4.16.0-3541083 | 3536423 | 2017-07-21 |          | Patch 1.2   |
| Release-Cert-CL-3681159 | 4.16.0-3681159 | 3603940 | 2017-10-05 |          |             |
| Release-Cert-CL-3700114 | 4.16.0-3700114 | 3603940 | 2017-10-17 |          | Patch 1.7   |
| Release-Live-CL-3724489 | 4.16.0-3724489 | 3709086 | 2017-10-25 |          | Patch 1.8   |
| Release-Live-CL-3757339 | 4.16.0-3757339 | 3752911 | 2017-11-14 |          | Patch 1.9   |
| Release-Cert-CL-3775276 | 4.16.0-3775276 | 3752911 | 2017-11-29 |          | Patch 1.9.1 |
| Release-Cert-CL-3785438 | 4.16.0-3785438 |         | 2017-12-02 |          |             |
| Release-Cert-CL-3790078 | 4.19.0-3790078 | 3752911 | 2017-12-05 |          | Patch 1.10  |
