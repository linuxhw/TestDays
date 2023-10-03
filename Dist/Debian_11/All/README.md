Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 9505

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aae60ff071](https://linux-hardware.org/?probe=aae60ff071) | Oct 01, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4aa68077](https://linux-hardware.org/?probe=ba4aa68077) | Sep 30, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [c7b049f922](https://linux-hardware.org/?probe=c7b049f922) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Intel         | DP35DP AAD81073-206         | Desktop     | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [acde6e2ba0](https://linux-hardware.org/?probe=acde6e2ba0) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8a7db88ae5](https://linux-hardware.org/?probe=8a7db88ae5) | Sep 25, 2023 |
| MSI           | MS-7318                     | Desktop     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| HP            | 250 G4                      | Notebook    | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| HP            | 1905                        | Desktop     | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| MSI           | MS-7318                     | Desktop     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [6f6fbfc86f](https://linux-hardware.org/?probe=6f6fbfc86f) | Sep 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | Notebook    | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Dell          | Precision 7550              | Notebook    | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | Desktop     | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| HP            | 8158 A01                    | Mini pc     | [bd8aa3d09c](https://linux-hardware.org/?probe=bd8aa3d09c) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | Notebook    | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| Google        | Droid                       | Notebook    | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [f8e68bfc81](https://linux-hardware.org/?probe=f8e68bfc81) | Sep 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [f89ec253d3](https://linux-hardware.org/?probe=f89ec253d3) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae1f2b94e5](https://linux-hardware.org/?probe=ae1f2b94e5) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | 970A-G46                    | Desktop     | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| Panasonic     | CF-19RHR3DPM                | Notebook    | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| HP            | 876C SMVB                   | Desktop     | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| Acer          | Extensa 5220                | Notebook    | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e8fe3531c7](https://linux-hardware.org/?probe=e8fe3531c7) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6bea6e300b](https://linux-hardware.org/?probe=6bea6e300b) | Sep 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da21e863a4](https://linux-hardware.org/?probe=da21e863a4) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | Desktop     | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | Desktop     | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | Desktop     | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | Desktop     | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0841c5e196](https://linux-hardware.org/?probe=0841c5e196) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8d52d37e1e](https://linux-hardware.org/?probe=8d52d37e1e) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c3fe8cb8e9](https://linux-hardware.org/?probe=c3fe8cb8e9) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e0133bb14e](https://linux-hardware.org/?probe=e0133bb14e) | Sep 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a200aa5407](https://linux-hardware.org/?probe=a200aa5407) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| HP            | 1495                        | Desktop     | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [52306fce15](https://linux-hardware.org/?probe=52306fce15) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 1495                        | Desktop     | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| HP            | 158A                        | Desktop     | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Rockchip      | RK3568 EVB1 DDR4 V10        | Soc         | [846c733ed7](https://linux-hardware.org/?probe=846c733ed7) | Aug 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a1bdeba9c8](https://linux-hardware.org/?probe=a1bdeba9c8) | Aug 23, 2023 |
| Lenovo        | IdeaPad Z485 20151          | Notebook    | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | Notebook    | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [5f5f76ff98](https://linux-hardware.org/?probe=5f5f76ff98) | Aug 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fd5614f8d1](https://linux-hardware.org/?probe=fd5614f8d1) | Aug 21, 2023 |
| Bananapi      | BPI-M5                      | Soc         | [0bd2202791](https://linux-hardware.org/?probe=0bd2202791) | Aug 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| Medion        | MS-7728                     | Desktop     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [8b347c4d9d](https://linux-hardware.org/?probe=8b347c4d9d) | Aug 19, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [b88e1a5605](https://linux-hardware.org/?probe=b88e1a5605) | Aug 18, 2023 |
| Acer          | Aspire one                  | Notebook    | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4906f87d9e](https://linux-hardware.org/?probe=4906f87d9e) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | Notebook    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | Notebook    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [defef9b917](https://linux-hardware.org/?probe=defef9b917) | Aug 16, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [12e5d1c399](https://linux-hardware.org/?probe=12e5d1c399) | Aug 15, 2023 |
| Unknown       | Variscite DART-MX8M-MINI... | Soc         | [a185c83285](https://linux-hardware.org/?probe=a185c83285) | Aug 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [4c24f10db4](https://linux-hardware.org/?probe=4c24f10db4) | Aug 15, 2023 |
| Dell          | 0CT017                      | Desktop     | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | Desktop     | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Lenovo        | ThinkPad W530 24477V0       | Notebook    | [2e09955f2f](https://linux-hardware.org/?probe=2e09955f2f) | Aug 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c7bc7c3f16](https://linux-hardware.org/?probe=c7bc7c3f16) | Aug 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3508d6c711](https://linux-hardware.org/?probe=3508d6c711) | Aug 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Unknown       | Unknown                     | Soc         | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Soc         | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ed029dd5e3](https://linux-hardware.org/?probe=ed029dd5e3) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [053608e18a](https://linux-hardware.org/?probe=053608e18a) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | Notebook    | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| AZW           | GTR V01                     | Mini pc     | [8b0b0e8cc4](https://linux-hardware.org/?probe=8b0b0e8cc4) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | Desktop     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [42d4093f63](https://linux-hardware.org/?probe=42d4093f63) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Biostar       | B365MHC                     | Desktop     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [079428c572](https://linux-hardware.org/?probe=079428c572) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [663f989185](https://linux-hardware.org/?probe=663f989185) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [c157382bd3](https://linux-hardware.org/?probe=c157382bd3) | Aug 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da2ada0c83](https://linux-hardware.org/?probe=da2ada0c83) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [1b1f671f30](https://linux-hardware.org/?probe=1b1f671f30) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df3495c01c](https://linux-hardware.org/?probe=df3495c01c) | Aug 04, 2023 |
| HP            | Lantis                      | Notebook    | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [127555ff0c](https://linux-hardware.org/?probe=127555ff0c) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Packard Be... | H17HV                       | Notebook    | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | Desktop     | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cd8671be26](https://linux-hardware.org/?probe=cd8671be26) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | Notebook    | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Intel         | NUC7i7DNB J83500-207        | Mini pc     | [e18855dc59](https://linux-hardware.org/?probe=e18855dc59) | Jul 30, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | Notebook    | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| Sony          | SVS13A1Z9RN                 | Notebook    | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | Notebook    | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | Desktop     | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [c7373023dd](https://linux-hardware.org/?probe=c7373023dd) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2fa28e6952](https://linux-hardware.org/?probe=2fa28e6952) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Dell          | 09CGW2 A04                  | Server      | [159d6b1be1](https://linux-hardware.org/?probe=159d6b1be1) | Jul 26, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [787c6a9252](https://linux-hardware.org/?probe=787c6a9252) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [5a9a1e320d](https://linux-hardware.org/?probe=5a9a1e320d) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9243bb6a08](https://linux-hardware.org/?probe=9243bb6a08) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [73f0811a7b](https://linux-hardware.org/?probe=73f0811a7b) | Jul 23, 2023 |
| Dell          | Latitude E7250              | Notebook    | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| Dell          | 0K7CVF A03                  | Server      | [228949ef5a](https://linux-hardware.org/?probe=228949ef5a) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | Desktop     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [b2938336ce](https://linux-hardware.org/?probe=b2938336ce) | Jul 22, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | Notebook    | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f26110e1a](https://linux-hardware.org/?probe=8f26110e1a) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | Desktop     | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | Notebook    | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [00c711574a](https://linux-hardware.org/?probe=00c711574a) | Jul 17, 2023 |
| HP            | 805A                        | Desktop     | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [15d31e889c](https://linux-hardware.org/?probe=15d31e889c) | Jul 16, 2023 |
| Unknown       | Unknown                     | Soc         | [99bfa94ff7](https://linux-hardware.org/?probe=99bfa94ff7) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [d2620e5fee](https://linux-hardware.org/?probe=d2620e5fee) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | Notebook    | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| Intel         | M70KLP2SB M22209-100        | Server      | [afa5fbc4a3](https://linux-hardware.org/?probe=afa5fbc4a3) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c4af2e9b6c](https://linux-hardware.org/?probe=c4af2e9b6c) | Jul 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [70b2ff6533](https://linux-hardware.org/?probe=70b2ff6533) | Jul 13, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [13f3a107dc](https://linux-hardware.org/?probe=13f3a107dc) | Jul 13, 2023 |
| MSI           | H170M PRO-VDH               | Desktop     | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| Dell          | Latitude E6330              | Notebook    | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | Desktop     | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| Positivo      | Mobile                      | Notebook    | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [02a820f6b2](https://linux-hardware.org/?probe=02a820f6b2) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1e6fc6f253](https://linux-hardware.org/?probe=1e6fc6f253) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ba7cde1766](https://linux-hardware.org/?probe=ba7cde1766) | Jul 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [798f921e70](https://linux-hardware.org/?probe=798f921e70) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| AZW           | U59                         | Desktop     | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | Desktop     | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| AZW           | MINI S                      | Desktop     | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0a2ad7c1a6](https://linux-hardware.org/?probe=0a2ad7c1a6) | Jul 08, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | Notebook    | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f4b26c97fe](https://linux-hardware.org/?probe=f4b26c97fe) | Jul 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8daacdd31c](https://linux-hardware.org/?probe=8daacdd31c) | Jul 06, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [4bbbfd7eb9](https://linux-hardware.org/?probe=4bbbfd7eb9) | Jul 05, 2023 |
| HP            | 895C                        | Desktop     | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57d7c40d](https://linux-hardware.org/?probe=1e57d7c40d) | Jul 05, 2023 |
| NEC Comput... | PC-VK27MBZCG                | Notebook    | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | Desktop     | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| Dell          | 0X904N A05                  | Server      | [b7335a46c8](https://linux-hardware.org/?probe=b7335a46c8) | Jul 03, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | Desktop     | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8bb4af1cb5](https://linux-hardware.org/?probe=8bb4af1cb5) | Jul 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cd68e8f8b](https://linux-hardware.org/?probe=7cd68e8f8b) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| Unknown       | Unknown                     | Soc         | [bc8f4620bd](https://linux-hardware.org/?probe=bc8f4620bd) | Jul 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a66c76ab6c](https://linux-hardware.org/?probe=a66c76ab6c) | Jul 02, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bd84f79486](https://linux-hardware.org/?probe=bd84f79486) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [7e37520061](https://linux-hardware.org/?probe=7e37520061) | Jun 30, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cb124d729](https://linux-hardware.org/?probe=7cb124d729) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Dell          | Latitude 7370               | Notebook    | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Shuttle       | FS61                        | Desktop     | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f60ead06fd](https://linux-hardware.org/?probe=f60ead06fd) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | Notebook    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [29cc577c0c](https://linux-hardware.org/?probe=29cc577c0c) | Jun 26, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9dce40179d](https://linux-hardware.org/?probe=9dce40179d) | Jun 25, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | Notebook    | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [71f114122e](https://linux-hardware.org/?probe=71f114122e) | Jun 23, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | Desktop     | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| VIT           | P2423                       | Notebook    | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| Supermicro    | X8DTU                       | Server      | [d8d978bd73](https://linux-hardware.org/?probe=d8d978bd73) | Jun 22, 2023 |
| HP            | 3397                        | Desktop     | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [f18c138ec9](https://linux-hardware.org/?probe=f18c138ec9) | Jun 21, 2023 |
| Lenovo        | 01GR176                     | Server      | [6d28cbec97](https://linux-hardware.org/?probe=6d28cbec97) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| MSI           | H81M-P33                    | Desktop     | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | Desktop     | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Amlogic       | Meson GXL (S905X) P212 D... | Soc         | [7c79fa6641](https://linux-hardware.org/?probe=7c79fa6641) | Jun 19, 2023 |
| Dell          | 0PU052                      | Desktop     | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [640ff2ce2e](https://linux-hardware.org/?probe=640ff2ce2e) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| AZW           | U59                         | Desktop     | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [ec95321dfb](https://linux-hardware.org/?probe=ec95321dfb) | Jun 17, 2023 |
| Dell          | Precision M2800             | Notebook    | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1cabb1c87f](https://linux-hardware.org/?probe=1cabb1c87f) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| HP            | 1589                        | Desktop     | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| Medion        | E6214                       | Notebook    | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c1375ab639](https://linux-hardware.org/?probe=c1375ab639) | Jun 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2754ddde7f](https://linux-hardware.org/?probe=2754ddde7f) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Dell          | Latitude 5480               | Notebook    | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Supermicro    | X11DPU                      | Server      | [f7937cfbf6](https://linux-hardware.org/?probe=f7937cfbf6) | Jun 14, 2023 |
| Supermicro    | X11DPH-T                    | Server      | [ed5dc59bc2](https://linux-hardware.org/?probe=ed5dc59bc2) | Jun 14, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3b954125c5](https://linux-hardware.org/?probe=3b954125c5) | Jun 13, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [84cd8a6537](https://linux-hardware.org/?probe=84cd8a6537) | Jun 13, 2023 |
| HP            | 2AED                        | Desktop     | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Intel         | JSL MRD                     | Desktop     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| Dell          | Inspiron 1521               | Notebook    | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f7397ff305](https://linux-hardware.org/?probe=f7397ff305) | Jun 11, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5e3b6bfb4c](https://linux-hardware.org/?probe=5e3b6bfb4c) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| Dell          | Latitude 7440               | Notebook    | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4527394e](https://linux-hardware.org/?probe=ba4527394e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | Notebook    | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [af396cb333](https://linux-hardware.org/?probe=af396cb333) | Jun 10, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [012e8255f3](https://linux-hardware.org/?probe=012e8255f3) | Jun 09, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [50844825e2](https://linux-hardware.org/?probe=50844825e2) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | Notebook    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | Notebook    | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | Notebook    | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| HP            | Pavilion 17                 | Notebook    | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| HP            | ProBook 4530s               | Notebook    | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | Notebook    | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | Desktop     | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | Notebook    | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [2532dfadd0](https://linux-hardware.org/?probe=2532dfadd0) | Jun 06, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [5cc10b1e1e](https://linux-hardware.org/?probe=5cc10b1e1e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c685007aa8](https://linux-hardware.org/?probe=c685007aa8) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da03bf4e08](https://linux-hardware.org/?probe=da03bf4e08) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | Notebook    | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | Notebook    | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | Notebook    | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | Notebook    | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | Notebook    | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | Notebook    | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Gigabyte      | P75-D3                      | Desktop     | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| Dell          | 0D456H A00                  | Server      | [4e0d53d64d](https://linux-hardware.org/?probe=4e0d53d64d) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [2a1e548be7](https://linux-hardware.org/?probe=2a1e548be7) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a4363d8242](https://linux-hardware.org/?probe=a4363d8242) | Jun 01, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [19043cab25](https://linux-hardware.org/?probe=19043cab25) | Jun 01, 2023 |
| Positivo      | C500                        | Notebook    | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | Notebook    | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [1e5f49bbf4](https://linux-hardware.org/?probe=1e5f49bbf4) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aad1baf686](https://linux-hardware.org/?probe=aad1baf686) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | Latitude 5411               | Notebook    | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | Desktop     | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| Dell          | Latitude E5510              | Notebook    | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | Notebook    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e4fde15d9f](https://linux-hardware.org/?probe=e4fde15d9f) | May 30, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [afcfc0fdf3](https://linux-hardware.org/?probe=afcfc0fdf3) | May 30, 2023 |
| MSI           | H55M-ED55                   | Desktop     | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dd6ecadb7e](https://linux-hardware.org/?probe=dd6ecadb7e) | May 30, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6e68e63f53](https://linux-hardware.org/?probe=6e68e63f53) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | Notebook    | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca1cea162c](https://linux-hardware.org/?probe=ca1cea162c) | May 29, 2023 |
| Dell          | 0D456H A00                  | Server      | [3151099615](https://linux-hardware.org/?probe=3151099615) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | Notebook    | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [54afc82ebc](https://linux-hardware.org/?probe=54afc82ebc) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7ac306d4fa](https://linux-hardware.org/?probe=7ac306d4fa) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| HP            | Mini 110-3700               | Notebook    | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [671d716ee3](https://linux-hardware.org/?probe=671d716ee3) | May 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [69adae13fe](https://linux-hardware.org/?probe=69adae13fe) | May 27, 2023 |
| HP            | G42                         | Notebook    | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| AZW           | MINI S                      | Desktop     | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [b99041460e](https://linux-hardware.org/?probe=b99041460e) | May 27, 2023 |
| MSI           | H55M-ED55                   | Desktop     | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| Dell          | 0WCJNT A06                  | Server      | [b3215bf901](https://linux-hardware.org/?probe=b3215bf901) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | Desktop     | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | Desktop     | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| Acer          | Aspire V3-551               | Notebook    | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| Acer          | EG31M R01-A4                | Desktop     | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [3a85770148](https://linux-hardware.org/?probe=3a85770148) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | Desktop     | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | Notebook    | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | Desktop     | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [84b7538837](https://linux-hardware.org/?probe=84b7538837) | May 23, 2023 |
| Boot Hardw... | MBD-B650-10G                | Server      | [00e04948fa](https://linux-hardware.org/?probe=00e04948fa) | May 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7b6c90320b](https://linux-hardware.org/?probe=7b6c90320b) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [b3062be7f2](https://linux-hardware.org/?probe=b3062be7f2) | May 23, 2023 |
| HP            | 530                         | Notebook    | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Intel         | S2600STB J17012-601         | Server      | [2fa80c021a](https://linux-hardware.org/?probe=2fa80c021a) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [db6ba1c42e](https://linux-hardware.org/?probe=db6ba1c42e) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | Desktop     | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [46de86898c](https://linux-hardware.org/?probe=46de86898c) | May 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [17d027794e](https://linux-hardware.org/?probe=17d027794e) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | Desktop     | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| HP            | 2B38                        | Desktop     | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | Desktop     | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | Inspiron 3451               | Notebook    | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b7463aea3a](https://linux-hardware.org/?probe=b7463aea3a) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | Notebook    | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| MSI           | 2AE0                        | Desktop     | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | Desktop     | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| Dell          | Latitude 5411               | Notebook    | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Gigabyte      | GA-6LASL 01234567           | Server      | [13eb4e7266](https://linux-hardware.org/?probe=13eb4e7266) | May 19, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | Notebook    | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c9d1849e5e](https://linux-hardware.org/?probe=c9d1849e5e) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| HP            | 8076                        | Desktop     | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Pegatron      | Yangtze                     | Desktop     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | Desktop     | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46b31c9243](https://linux-hardware.org/?probe=46b31c9243) | May 16, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [af42d74d41](https://linux-hardware.org/?probe=af42d74d41) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | Notebook    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | Notebook    | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | Notebook    | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4ad39c5d7](https://linux-hardware.org/?probe=d4ad39c5d7) | May 15, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3e839501e9](https://linux-hardware.org/?probe=3e839501e9) | May 15, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | 339A                        | Desktop     | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | Desktop     | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e887133fce](https://linux-hardware.org/?probe=e887133fce) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Dell          | Latitude 7410               | Notebook    | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| AMI           | Intel                       | Notebook    | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | Notebook    | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [72ba449391](https://linux-hardware.org/?probe=72ba449391) | May 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a712c6b44a](https://linux-hardware.org/?probe=a712c6b44a) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | Notebook    | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [036fd352bf](https://linux-hardware.org/?probe=036fd352bf) | May 13, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| HP            | 1632                        | Desktop     | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [3a92115c6c](https://linux-hardware.org/?probe=3a92115c6c) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | Notebook    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Apple         | MacBook10,1                 | Notebook    | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c686c521dd](https://linux-hardware.org/?probe=c686c521dd) | May 12, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| AZW           | Green G3                    | Desktop     | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Medion        | E2292                       | Convertible | [116727a473](https://linux-hardware.org/?probe=116727a473) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [e07b012f6b](https://linux-hardware.org/?probe=e07b012f6b) | May 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Supermicro    | X10DRi                      | Server      | [5fc37f06cb](https://linux-hardware.org/?probe=5fc37f06cb) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Dell          | 0C1R19 A01                  | Desktop     | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | Notebook    | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d9681f2d77](https://linux-hardware.org/?probe=d9681f2d77) | May 09, 2023 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [0971c53d86](https://linux-hardware.org/?probe=0971c53d86) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c95999b5ad](https://linux-hardware.org/?probe=c95999b5ad) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [670e910889](https://linux-hardware.org/?probe=670e910889) | May 08, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c5687c048f](https://linux-hardware.org/?probe=c5687c048f) | May 08, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [d0cef22171](https://linux-hardware.org/?probe=d0cef22171) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | Desktop     | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [83c0f8e7e5](https://linux-hardware.org/?probe=83c0f8e7e5) | May 08, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| MSI           | H61M-E23                    | Desktop     | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | Notebook    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | Notebook    | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| ASUSTek       | K73SJ                       | Notebook    | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Unknown       | Unknown                     | Soc         | [55f6caec2d](https://linux-hardware.org/?probe=55f6caec2d) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | Notebook    | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | Notebook    | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [2d767e0513](https://linux-hardware.org/?probe=2d767e0513) | May 06, 2023 |
| HP            | 1998                        | Desktop     | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | Notebook    | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Dell          | 0RN474                      | Desktop     | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| Dell          | Latitude D630               | Notebook    | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [7b25457d55](https://linux-hardware.org/?probe=7b25457d55) | May 04, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8a4aacb421](https://linux-hardware.org/?probe=8a4aacb421) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| sunxi         | Unknown                     | Soc         | [952b46c211](https://linux-hardware.org/?probe=952b46c211) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HPE           | ProLiant DL360 Gen10 Plu... | Server      | [74466ad718](https://linux-hardware.org/?probe=74466ad718) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | Notebook    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | Notebook    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | Notebook    | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| Dell          | Latitude 5414               | Notebook    | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [d0c2c987fc](https://linux-hardware.org/?probe=d0c2c987fc) | May 03, 2023 |
| HP            | 83C3 A01                    | Mini pc     | [bb29a94285](https://linux-hardware.org/?probe=bb29a94285) | May 03, 2023 |
| GreatWall     | DF                          | Soc         | [5a3cb266db](https://linux-hardware.org/?probe=5a3cb266db) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| BESSTAR Te... | DMAF5                       | Desktop     | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fabcbe5dc](https://linux-hardware.org/?probe=2fabcbe5dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fa453d9183](https://linux-hardware.org/?probe=fa453d9183) | May 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | Desktop     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7ae18f770d](https://linux-hardware.org/?probe=7ae18f770d) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [c1bf3a9c44](https://linux-hardware.org/?probe=c1bf3a9c44) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | Notebook    | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f5f4abd1f3](https://linux-hardware.org/?probe=f5f4abd1f3) | May 01, 2023 |
| HP            | 2B38                        | Desktop     | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | Desktop     | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | Notebook    | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | Notebook    | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [c8c9c1e591](https://linux-hardware.org/?probe=c8c9c1e591) | Apr 30, 2023 |
| Positivo      | Q464C                       | Notebook    | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | Notebook    | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7804689b38](https://linux-hardware.org/?probe=7804689b38) | Apr 30, 2023 |
| COPELION I... | QX-250 Series               | Notebook    | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | Desktop     | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4cc7c839fb](https://linux-hardware.org/?probe=4cc7c839fb) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | Notebook    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Medion        | MS-7708                     | Desktop     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Rockchip      | Unknown                     | Soc         | [5236b9452c](https://linux-hardware.org/?probe=5236b9452c) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | Desktop     | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Supermicro    | X12SPL-F                    | Server      | [8382988ca9](https://linux-hardware.org/?probe=8382988ca9) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | Desktop     | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Unknown       | Unknown                     | Soc         | [e5ff381254](https://linux-hardware.org/?probe=e5ff381254) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bab222234a](https://linux-hardware.org/?probe=bab222234a) | Apr 27, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| HP            | 17E2                        | Mini pc     | [02ee837763](https://linux-hardware.org/?probe=02ee837763) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| AMD           | Volcano                     | Server      | [b7e67f8130](https://linux-hardware.org/?probe=b7e67f8130) | Apr 27, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [475e46f565](https://linux-hardware.org/?probe=475e46f565) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Google        | Terra                       | Notebook    | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| HP            | ENVY 15                     | Notebook    | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | Notebook    | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [23571a99b1](https://linux-hardware.org/?probe=23571a99b1) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [f1fb89d0f7](https://linux-hardware.org/?probe=f1fb89d0f7) | Apr 25, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | Notebook    | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | Notebook    | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | Desktop     | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| HP            | 8056                        | Desktop     | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | Desktop     | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | Desktop     | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | Desktop     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | Desktop     | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Dell          | 03FV9K A00                  | Server      | [4d9f06ca7b](https://linux-hardware.org/?probe=4d9f06ca7b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5f760ed90e](https://linux-hardware.org/?probe=5f760ed90e) | Apr 23, 2023 |
| Biostar       | B350ET2                     | Desktop     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| HP            | 15                          | Notebook    | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | Desktop     | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c88cba109a](https://linux-hardware.org/?probe=c88cba109a) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Shuttle       | DS20U                       | Desktop     | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| HP            | 845A                        | Desktop     | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | Notebook    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [868456ca5d](https://linux-hardware.org/?probe=868456ca5d) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a92b4a305f](https://linux-hardware.org/?probe=a92b4a305f) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| Dell          | Precision 3550              | Notebook    | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | Notebook    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| Shuttle       | FS81                        | Desktop     | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | Notebook    | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | Desktop     | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | Notebook    | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| sunxi         | Unknown                     | Soc         | [bb26b3803b](https://linux-hardware.org/?probe=bb26b3803b) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [213cd129cd](https://linux-hardware.org/?probe=213cd129cd) | Apr 18, 2023 |
| sunxi         | Unknown                     | Soc         | [586cbefdb3](https://linux-hardware.org/?probe=586cbefdb3) | Apr 18, 2023 |
| Lenovo        | 374B No DPK                 | All in one  | [c87417466c](https://linux-hardware.org/?probe=c87417466c) | Apr 18, 2023 |
| Lenovo        | 374B No DPK                 | All in one  | [4a7133799c](https://linux-hardware.org/?probe=4a7133799c) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | Notebook    | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [35c6970ec2](https://linux-hardware.org/?probe=35c6970ec2) | Apr 18, 2023 |
| Supermicro    | X9DRW                       | Server      | [6994c89077](https://linux-hardware.org/?probe=6994c89077) | Apr 17, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | Desktop     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | Notebook    | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9c885fa5cf](https://linux-hardware.org/?probe=9c885fa5cf) | Apr 16, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 966       | 13.01%  |
| 5.10.0-7-amd64         | 691       | 9.31%   |
| 5.10.0-10-amd64        | 575       | 7.74%   |
| 5.10.0-21-amd64        | 471       | 6.34%   |
| 5.10.0-16-amd64        | 372       | 5.01%   |
| 5.10.0-20-amd64        | 370       | 4.98%   |
| 5.10.0-9-amd64         | 327       | 4.4%    |
| 5.10.0-18-amd64        | 291       | 3.92%   |
| 5.10.0-19-amd64        | 290       | 3.91%   |
| 5.10.0-13-amd64        | 265       | 3.57%   |
| 5.10.0-23-amd64        | 210       | 2.83%   |
| 5.10.0-11-amd64        | 194       | 2.61%   |
| 5.10.0-2-amd64         | 158       | 2.13%   |
| 5.10.0-14-amd64        | 140       | 1.89%   |
| 5.10.0-17-amd64        | 126       | 1.7%    |
| 5.10.0-15-amd64        | 105       | 1.41%   |
| 5.10.0-22-amd64        | 104       | 1.4%    |
| 5.10.0-12-amd64        | 74        | 1%      |
| 5.10.0-6-amd64         | 46        | 0.62%   |
| 6.0.0-0.deb11.6-amd64  | 44        | 0.59%   |
| 5.18.0-0.deb11.4-amd64 | 42        | 0.57%   |
| 5.16.0-0.bpo.4-amd64   | 38        | 0.51%   |
| 5.15.0-2-amd64         | 38        | 0.51%   |
| 5.10.0-13-686-pae      | 30        | 0.4%    |
| 6.0.0-0.deb11.2-amd64  | 29        | 0.39%   |
| 5.10.0-25-amd64        | 29        | 0.39%   |
| 5.19.0-0.deb11.2-amd64 | 26        | 0.35%   |
| 5.15.74-1-pve          | 26        | 0.35%   |
| 5.18.0-0.bpo.1-amd64   | 25        | 0.34%   |
| 5.14.0-0.bpo.2-amd64   | 25        | 0.34%   |
| 5.13.19-6-pve          | 24        | 0.32%   |
| 6.1.0-0.deb11.7-amd64  | 21        | 0.28%   |
| 5.15.85-1-pve          | 21        | 0.28%   |
| 6.1.21-v8+             | 20        | 0.27%   |
| 5.15.107-2-pve         | 20        | 0.27%   |
| 5.15.102-1-pve         | 20        | 0.27%   |
| 5.15.84-v8+            | 19        | 0.26%   |
| 6.1.0-0.deb11.5-amd64  | 18        | 0.24%   |
| 5.15.83-1-pve          | 18        | 0.24%   |
| 5.10.0-8-arm64         | 18        | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 5536      | 80.85%  |
| 6.0.0    | 98        | 1.43%   |
| 5.18.0   | 96        | 1.4%    |
| 5.15.0   | 80        | 1.17%   |
| 5.16.0   | 69        | 1.01%   |
| 6.1.0    | 67        | 0.98%   |
| 5.19.0   | 61        | 0.89%   |
| 5.13.19  | 59        | 0.86%   |
| 5.14.0   | 43        | 0.63%   |
| 5.15.107 | 35        | 0.51%   |
| 5.15.74  | 30        | 0.44%   |
| 5.11.22  | 26        | 0.38%   |
| 5.17.0   | 24        | 0.35%   |
| 5.15.85  | 21        | 0.31%   |
| 6.1.21   | 20        | 0.29%   |
| 5.15.84  | 20        | 0.29%   |
| 5.15.102 | 20        | 0.29%   |
| 5.15.83  | 19        | 0.28%   |
| 5.15.39  | 18        | 0.26%   |
| 5.15.32  | 18        | 0.26%   |
| 5.15.30  | 18        | 0.26%   |
| 5.15.35  | 17        | 0.25%   |
| 5.15.76  | 15        | 0.22%   |
| 5.10.92  | 15        | 0.22%   |
| 5.15.53  | 14        | 0.2%    |
| 5.15.61  | 13        | 0.19%   |
| 5.15.108 | 12        | 0.18%   |
| 4.19.0   | 11        | 0.16%   |
| 5.15.104 | 10        | 0.15%   |
| 6.1.15   | 9         | 0.13%   |
| 5.15.60  | 8         | 0.12%   |
| 6.2.6    | 7         | 0.1%    |
| 5.13.0   | 7         | 0.1%    |
| 5.10.63  | 7         | 0.1%    |
| 6.2.9    | 6         | 0.09%   |
| 6.1.19   | 6         | 0.09%   |
| 5.19.17  | 6         | 0.09%   |
| 5.15.116 | 6         | 0.09%   |
| 5.10.60  | 6         | 0.09%   |
| 5.10.110 | 6         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10     | 5617      | 82.47%  |
| 5.15     | 401       | 5.89%   |
| 6.1      | 119       | 1.75%   |
| 6.0      | 113       | 1.66%   |
| 5.18     | 105       | 1.54%   |
| 5.19     | 81        | 1.19%   |
| 5.16     | 79        | 1.16%   |
| 5.13     | 78        | 1.15%   |
| 5.14     | 50        | 0.73%   |
| 5.11     | 35        | 0.51%   |
| 5.17     | 34        | 0.5%    |
| 6.2      | 27        | 0.4%    |
| 4.19     | 13        | 0.19%   |
| 5.4      | 11        | 0.16%   |
| 5.12     | 9         | 0.13%   |
| 6.3      | 7         | 0.1%    |
| 5        | 5         | 0.07%   |
| 6.4      | 4         | 0.06%   |
| 4.9      | 4         | 0.06%   |
| 4.4      | 4         | 0.06%   |
| 5.9      | 3         | 0.04%   |
| 5.1      | 3         | 0.04%   |
| 3.18     | 2         | 0.03%   |
| 5.8      | 1         | 0.01%   |
| 5.5      | 1         | 0.01%   |
| 5.15.6   | 1         | 0.01%   |
| 5.10.164 | 1         | 0.01%   |
| 4.14     | 1         | 0.01%   |
| 3.8      | 1         | 0.01%   |
| 3.10     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6232      | 93.49%  |
| aarch64 | 199       | 2.99%   |
| i686    | 196       | 2.94%   |
| armv7l  | 33        | 0.5%    |
| riscv64 | 5         | 0.08%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2507      | 37.03%  |
| GNOME             | 1501      | 22.17%  |
| XFCE              | 770       | 11.37%  |
| KDE5              | 748       | 11.05%  |
| MATE              | 256       | 3.78%   |
| LXDE              | 213       | 3.15%   |
| X-Cinnamon        | 206       | 3.04%   |
| Cinnamon          | 158       | 2.33%   |
| LXQt              | 87        | 1.29%   |
| i3                | 70        | 1.03%   |
| KDE               | 51        | 0.75%   |
| Openbox           | 42        | 0.62%   |
| GNOME Flashback   | 38        | 0.56%   |
| lightdm-xsession  | 28        | 0.41%   |
| Trinity           | 22        | 0.32%   |
| Budgie            | 15        | 0.22%   |
| GNOME Classic     | 14        | 0.21%   |
| sway              | 5         | 0.07%   |
| awesome           | 5         | 0.07%   |
| DWM               | 4         | 0.06%   |
| x-session-manager | 3         | 0.04%   |
| Enlightenment     | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| BunsenLabs        | 3         | 0.04%   |
| ICEWM             | 2         | 0.03%   |
| GNUstep           | 2         | 0.03%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| Phosh:GNOME       | 1         | 0.01%   |
| mwm               | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| gnome-xorg        | 1         | 0.01%   |
| fvwm              | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| e16-session       | 1         | 0.01%   |
| default           | 1         | 0.01%   |
| Deepin            | 1         | 0.01%   |
| /etc/X11/Xsession | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 3098      | 45.86%  |
| Unknown     | 1850      | 27.39%  |
| Wayland     | 973       | 14.4%   |
| Tty         | 825       | 12.21%  |
| Unspecified | 6         | 0.09%   |
| Web         | 3         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3222      | 47.79%  |
| LightDM | 1335      | 19.8%   |
| GDM     | 1195      | 17.72%  |
| SDDM    | 656       | 9.73%   |
| TDM     | 156       | 2.31%   |
| GDM3    | 125       | 1.85%   |
| XDM     | 16        | 0.24%   |
| SLiM    | 14        | 0.21%   |
| LXDM    | 11        | 0.16%   |
| NODM    | 6         | 0.09%   |
| SU      | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2238      | 33.24%  |
| ru_RU   | 947       | 14.07%  |
| Unknown | 940       | 13.96%  |
| de_DE   | 400       | 5.94%   |
| fr_FR   | 338       | 5.02%   |
| en_GB   | 329       | 4.89%   |
| es_ES   | 193       | 2.87%   |
| it_IT   | 149       | 2.21%   |
| pt_BR   | 145       | 2.15%   |
| pl_PL   | 105       | 1.56%   |
| C       | 81        | 1.2%    |
| en_AU   | 79        | 1.17%   |
| en_CA   | 77        | 1.14%   |
| es_MX   | 50        | 0.74%   |
| zh_CN   | 45        | 0.67%   |
| es_AR   | 41        | 0.61%   |
| es_VE   | 32        | 0.48%   |
| hu_HU   | 31        | 0.46%   |
| en_IN   | 30        | 0.45%   |
| en_IE   | 30        | 0.45%   |
| ja_JP   | 24        | 0.36%   |
| de_CH   | 24        | 0.36%   |
| de_AT   | 22        | 0.33%   |
| nl_NL   | 19        | 0.28%   |
| fi_FI   | 17        | 0.25%   |
| en_NZ   | 17        | 0.25%   |
| sv_SE   | 16        | 0.24%   |
| pt_PT   | 16        | 0.24%   |
| es_CO   | 13        | 0.19%   |
| es_CL   | 13        | 0.19%   |
| cs_CZ   | 13        | 0.19%   |
| nl_BE   | 12        | 0.18%   |
| fr_BE   | 12        | 0.18%   |
| en_ZA   | 12        | 0.18%   |
| tr_TR   | 11        | 0.16%   |
| fr_CH   | 10        | 0.15%   |
| zh_TW   | 9         | 0.13%   |
| nb_NO   | 9         | 0.13%   |
| en_SG   | 9         | 0.13%   |
| uk_UA   | 8         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3879      | 57.59%  |
| BIOS | 2857      | 42.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4379      | 65.37%  |
| Overlay | 1882      | 28.09%  |
| Btrfs   | 200       | 2.99%   |
| Zfs     | 111       | 1.66%   |
| Xfs     | 69        | 1.03%   |
| Tmpfs   | 20        | 0.3%    |
| Ext3    | 16        | 0.24%   |
| Ext2    | 10        | 0.15%   |
| Unknown | 8         | 0.12%   |
| Rootfs  | 2         | 0.03%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4035      | 59.88%  |
| MBR     | 1819      | 27%     |
| Unknown | 884       | 13.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5455      | 81.1%   |
| Yes       | 1271      | 18.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4707      | 70%     |
| Yes       | 2017      | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 955       | 14.33%  |
| Lenovo                  | 925       | 13.88%  |
| Hewlett-Packard         | 722       | 10.83%  |
| Apple                   | 687       | 10.31%  |
| Dell                    | 666       | 9.99%   |
| Gigabyte Technology     | 420       | 6.3%    |
| MSI                     | 308       | 4.62%   |
| Acer                    | 238       | 3.57%   |
| ASRock                  | 230       | 3.45%   |
| Intel                   | 159       | 2.39%   |
| Raspberry Pi Foundation | 145       | 2.18%   |
| Google                  | 141       | 2.12%   |
| Unknown                 | 105       | 1.58%   |
| Supermicro              | 66        | 0.99%   |
| Toshiba                 | 52        | 0.78%   |
| Fujitsu                 | 51        | 0.77%   |
| ECS                     | 49        | 0.74%   |
| Aquarius                | 47        | 0.71%   |
| Samsung Electronics     | 44        | 0.66%   |
| AZW                     | 33        | 0.5%    |
| ASRockRack              | 32        | 0.48%   |
| HUAWEI                  | 28        | 0.42%   |
| Foxconn                 | 28        | 0.42%   |
| Sony                    | 19        | 0.29%   |
| Notebook                | 19        | 0.29%   |
| Pegatron                | 17        | 0.26%   |
| Packard Bell            | 16        | 0.24%   |
| Medion                  | 16        | 0.24%   |
| AMI                     | 14        | 0.21%   |
| Inventec                | 13        | 0.2%    |
| Biostar                 | 13        | 0.2%    |
| Hardkernel              | 12        | 0.18%   |
| BESSTAR Tech            | 12        | 0.18%   |
| sunxi                   | 11        | 0.17%   |
| Positivo                | 11        | 0.17%   |
| Microsoft               | 11        | 0.17%   |
| Panasonic               | 10        | 0.15%   |
| IBM                     | 9         | 0.14%   |
| Clevo                   | 9         | 0.14%   |
| Xunlong                 | 8         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 353       | 5.3%    |
| Unknown                                   | 116       | 1.74%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.71%   |
| ASUS All Series                           | 80        | 1.2%    |
| Apple MacBookAir7,2                       | 77        | 1.16%   |
| Apple MacBookAir7,1                       | 77        | 1.16%   |
| Google Enguarde                           | 74        | 1.11%   |
| ASUS S20 K29                              | 55        | 0.83%   |
| Apple MacBook2,1                          | 55        | 0.83%   |
| Aquarius NS585                            | 44        | 0.66%   |
| MSI MS-7996                               | 38        | 0.57%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 31        | 0.47%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.36%   |
| Google Terra                              | 23        | 0.35%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 22        | 0.33%   |
| MSI MS-7817                               | 22        | 0.33%   |
| ECS G31T-M9                               | 22        | 0.33%   |
| Apple MacBook4,1                          | 21        | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 20        | 0.3%    |
| ASRock H470M-HVS                          | 20        | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 19        | 0.29%   |
| Supermicro Super Server                   | 18        | 0.27%   |
| HP Notebook                               | 18        | 0.27%   |
| Gigabyte H81M-S2V                         | 18        | 0.27%   |
| ASUS PRIME H510M-A                        | 17        | 0.26%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.24%   |
| Gigabyte H410M S2H                        | 16        | 0.24%   |
| ECS H61H2-M13                             | 16        | 0.24%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.23%   |
| Acer Aspire A315-23                       | 15        | 0.23%   |
| ASUS 1005HA                               | 14        | 0.21%   |
| Google Reks                               | 13        | 0.2%    |
| Dell OptiPlex 7010                        | 13        | 0.2%    |
| HP Pavilion g6                            | 12        | 0.18%   |
| Gigabyte B450M DS3H                       | 11        | 0.17%   |
| AZW U59                                   | 11        | 0.17%   |
| RPi Raspberry Pi 400 Rev 1.0              | 10        | 0.15%   |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 10        | 0.15%   |
| HP Laptop 15-db0xxx                       | 10        | 0.15%   |
| AZW MINI S                                | 10        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 583       | 8.75%   |
| Apple MacBook5     | 353       | 5.3%    |
| Dell Latitude      | 187       | 2.81%   |
| Apple MacBookAir7  | 154       | 2.31%   |
| Acer Aspire        | 152       | 2.28%   |
| RPi Raspberry      | 145       | 2.18%   |
| Dell Inspiron      | 142       | 2.13%   |
| ASUS PRIME         | 138       | 2.07%   |
| Unknown            | 116       | 1.74%   |
| Lenovo IdeaPad     | 110       | 1.65%   |
| HP EliteBook       | 107       | 1.61%   |
| Dell OptiPlex      | 97        | 1.46%   |
| HP Pavilion        | 89        | 1.34%   |
| ASUS All           | 80        | 1.2%    |
| Dell Precision     | 76        | 1.14%   |
| HP Compaq          | 75        | 1.13%   |
| Google Enguarde    | 74        | 1.11%   |
| HP Laptop          | 72        | 1.08%   |
| Lenovo ThinkCentre | 60        | 0.9%    |
| ASUS ROG           | 60        | 0.9%    |
| HP ProBook         | 58        | 0.87%   |
| ASUS S20           | 55        | 0.83%   |
| Apple MacBook2     | 55        | 0.83%   |
| Dell XPS           | 53        | 0.8%    |
| ASUS TUF           | 50        | 0.75%   |
| Aquarius NS585     | 44        | 0.66%   |
| ASUS VivoBook      | 43        | 0.65%   |
| Toshiba Satellite  | 42        | 0.63%   |
| Dell PowerEdge     | 42        | 0.63%   |
| Dell Vostro        | 40        | 0.6%    |
| MSI MS-7996        | 38        | 0.57%   |
| HP ProLiant        | 36        | 0.54%   |
| ASUS P8H61-M       | 31        | 0.47%   |
| HP ENVY            | 25        | 0.38%   |
| HP EliteDesk       | 25        | 0.38%   |
| Gigabyte B450M     | 25        | 0.38%   |
| ASUS ASUS          | 25        | 0.38%   |
| HP ZBook           | 23        | 0.35%   |
| Google Terra       | 23        | 0.35%   |
| ASUS ZenBook       | 23        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 761       | 11.42%  |
| 2021    | 617       | 9.26%   |
| 2009    | 561       | 8.42%   |
| 2019    | 499       | 7.49%   |
| 2012    | 462       | 6.93%   |
| 2018    | 457       | 6.86%   |
| 2013    | 384       | 5.76%   |
| 2015    | 353       | 5.3%    |
| 2011    | 346       | 5.19%   |
| 2017    | 342       | 5.13%   |
| 2016    | 336       | 5.04%   |
| 2014    | 307       | 4.61%   |
| 2022    | 300       | 4.5%    |
| 2010    | 233       | 3.5%    |
| Unknown | 209       | 3.14%   |
| 2008    | 187       | 2.81%   |
| 2007    | 166       | 2.49%   |
| 2006    | 52        | 0.78%   |
| 2005    | 36        | 0.54%   |
| 2023    | 26        | 0.39%   |
| 2003    | 15        | 0.23%   |
| 2004    | 10        | 0.15%   |
| 2001    | 3         | 0.05%   |
| 2002    | 1         | 0.02%   |
| 2000    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3369      | 50.56%  |
| Desktop        | 2479      | 37.2%   |
| System on chip | 221       | 3.32%   |
| Convertible    | 201       | 3.02%   |
| Mini pc        | 164       | 2.46%   |
| Server         | 138       | 2.07%   |
| All in one     | 55        | 0.83%   |
| Tablet         | 32        | 0.48%   |
| Phone          | 4         | 0.06%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6322      | 94.47%  |
| Enabled  | 370       | 5.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6511      | 97.69%  |
| Yes  | 154       | 2.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1523      | 22.65%  |
| 16.01-24.0      | 1206      | 17.93%  |
| 3.01-4.0        | 1199      | 17.83%  |
| 8.01-16.0       | 851       | 12.65%  |
| 1.01-2.0        | 657       | 9.77%   |
| 32.01-64.0      | 555       | 8.25%   |
| 64.01-256.0     | 323       | 4.8%    |
| 0.51-1.0        | 129       | 1.92%   |
| 2.01-3.0        | 127       | 1.89%   |
| 24.01-32.0      | 97        | 1.44%   |
| 0.01-0.5        | 31        | 0.46%   |
| More than 256.0 | 26        | 0.39%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2374      | 33.75%  |
| 0.51-1.0        | 1238      | 17.6%   |
| 2.01-3.0        | 1183      | 16.82%  |
| 4.01-8.0        | 793       | 11.27%  |
| 3.01-4.0        | 626       | 8.9%    |
| 0.01-0.5        | 347       | 4.93%   |
| 8.01-16.0       | 271       | 3.85%   |
| 16.01-24.0      | 81        | 1.15%   |
| 32.01-64.0      | 56        | 0.8%    |
| 24.01-32.0      | 37        | 0.53%   |
| 64.01-256.0     | 25        | 0.36%   |
| More than 256.0 | 2         | 0.03%   |
| Unknown         | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4545      | 67.03%  |
| 2      | 1236      | 18.23%  |
| 3      | 398       | 5.87%   |
| 4      | 231       | 3.41%   |
| 5      | 109       | 1.61%   |
| 6      | 66        | 0.97%   |
| 0      | 56        | 0.83%   |
| 7      | 40        | 0.59%   |
| 8      | 35        | 0.52%   |
| 9      | 15        | 0.22%   |
| 10     | 12        | 0.18%   |
| 13     | 10        | 0.15%   |
| 12     | 7         | 0.1%    |
| 14     | 4         | 0.06%   |
| 11     | 4         | 0.06%   |
| 28     | 2         | 0.03%   |
| 16     | 2         | 0.03%   |
| 79     | 1         | 0.01%   |
| 47     | 1         | 0.01%   |
| 29     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |
| 21     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 18     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4557      | 68.16%  |
| Yes       | 2129      | 31.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5764      | 86.36%  |
| No        | 910       | 13.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4482      | 67.1%   |
| No        | 2198      | 32.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3726      | 55.66%  |
| No        | 2968      | 44.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1735      | 25.98%  |
| Russia       | 1012      | 15.15%  |
| Germany      | 624       | 9.34%   |
| France       | 431       | 6.45%   |
| Spain        | 251       | 3.76%   |
| Italy        | 205       | 3.07%   |
| Brazil       | 200       | 2.99%   |
| UK           | 173       | 2.59%   |
| Poland       | 159       | 2.38%   |
| Canada       | 135       | 2.02%   |
| Australia    | 110       | 1.65%   |
| Netherlands  | 108       | 1.62%   |
| Switzerland  | 95        | 1.42%   |
| Mexico       | 79        | 1.18%   |
| China        | 79        | 1.18%   |
| Argentina    | 69        | 1.03%   |
| Sweden       | 56        | 0.84%   |
| Belgium      | 51        | 0.76%   |
| Austria      | 51        | 0.76%   |
| Ukraine      | 50        | 0.75%   |
| Hungary      | 50        | 0.75%   |
| India        | 43        | 0.64%   |
| Finland      | 43        | 0.64%   |
| Czechia      | 42        | 0.63%   |
| Norway       | 41        | 0.61%   |
| Portugal     | 39        | 0.58%   |
| Turkey       | 38        | 0.57%   |
| Venezuela    | 37        | 0.55%   |
| Bulgaria     | 35        | 0.52%   |
| Japan        | 33        | 0.49%   |
| Romania      | 30        | 0.45%   |
| Ireland      | 27        | 0.4%    |
| Taiwan       | 24        | 0.36%   |
| New Zealand  | 23        | 0.34%   |
| Greece       | 23        | 0.34%   |
| Denmark      | 23        | 0.34%   |
| Colombia     | 22        | 0.33%   |
| Croatia      | 20        | 0.3%    |
| South Africa | 19        | 0.28%   |
| Slovakia     | 19        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 757       | 10.87%  |
| Voronezh          | 715       | 10.26%  |
| Dover-Foxcroft    | 304       | 4.36%   |
| Paris             | 68        | 0.98%   |
| Moscow            | 68        | 0.98%   |
| St Petersburg     | 53        | 0.76%   |
| Seville           | 53        | 0.76%   |
| Berlin            | 43        | 0.62%   |
| Madrid            | 38        | 0.55%   |
| Warsaw            | 37        | 0.53%   |
| Vienna            | 37        | 0.53%   |
| Barcelona         | 32        | 0.46%   |
| Munich            | 31        | 0.45%   |
| Milan             | 31        | 0.45%   |
| Zurich            | 30        | 0.43%   |
| Amsterdam         | 29        | 0.42%   |
| Sao Paulo         | 27        | 0.39%   |
| Falkenstein       | 25        | 0.36%   |
| Toronto           | 24        | 0.34%   |
| Sydney            | 23        | 0.33%   |
| Frankfurt am Main | 23        | 0.33%   |
| Brisbane          | 23        | 0.33%   |
| Melbourne         | 21        | 0.3%    |
| Hamburg           | 21        | 0.3%    |
| Perm              | 20        | 0.29%   |
| London            | 20        | 0.29%   |
| Stuttgart         | 18        | 0.26%   |
| Helsinki          | 18        | 0.26%   |
| Dublin            | 18        | 0.26%   |
| Buenos Aires      | 18        | 0.26%   |
| Prague            | 17        | 0.24%   |
| Istanbul          | 17        | 0.24%   |
| Cologne           | 17        | 0.24%   |
| Chicago           | 16        | 0.23%   |
| San José         | 15        | 0.22%   |
| Lyon              | 15        | 0.22%   |
| Leipzig           | 15        | 0.22%   |
| Caracas           | 15        | 0.22%   |
| Budapest          | 15        | 0.22%   |
| Valencia          | 14        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1365      | 2004   | 14.84%  |
| WDC                 | 1222      | 1983   | 13.28%  |
| Seagate             | 1147      | 2110   | 12.47%  |
| Toshiba             | 636       | 921    | 6.91%   |
| Kingston            | 556       | 696    | 6.04%   |
| Unknown             | 520       | 666    | 5.65%   |
| Crucial             | 424       | 517    | 4.61%   |
| SanDisk             | 360       | 450    | 3.91%   |
| Fujitsu             | 284       | 294    | 3.09%   |
| Hitachi             | 264       | 347    | 2.87%   |
| Intel               | 210       | 293    | 2.28%   |
| Apple               | 198       | 237    | 2.15%   |
| SK hynix            | 183       | 226    | 1.99%   |
| A-DATA Technology   | 164       | 273    | 1.78%   |
| HGST                | 147       | 249    | 1.6%    |
| Micron Technology   | 125       | 152    | 1.36%   |
| China               | 105       | 120    | 1.14%   |
| Unknown             | 75        | 81     | 0.82%   |
| KIOXIA              | 64        | 70     | 0.7%    |
| SPCC                | 60        | 70     | 0.65%   |
| PNY                 | 58        | 100    | 0.63%   |
| Transcend           | 48        | 55     | 0.52%   |
| Phison              | 43        | 54     | 0.47%   |
| Intenso             | 41        | 52     | 0.45%   |
| JMicron Technology  | 37        | 40     | 0.4%    |
| Netac               | 36        | 96     | 0.39%   |
| LITEON              | 35        | 42     | 0.38%   |
| Patriot             | 33        | 39     | 0.36%   |
| Corsair             | 32        | 53     | 0.35%   |
| SABRENT             | 30        | 31     | 0.33%   |
| Hewlett-Packard     | 27        | 47     | 0.29%   |
| GOODRAM             | 26        | 43     | 0.28%   |
| Silicon Motion      | 24        | 30     | 0.26%   |
| Maxtor              | 24        | 29     | 0.26%   |
| OCZ                 | 23        | 27     | 0.25%   |
| Team                | 22        | 46     | 0.24%   |
| Gigabyte Technology | 22        | 24     | 0.24%   |
| LITEONIT            | 20        | 27     | 0.22%   |
| Apacer              | 20        | 20     | 0.22%   |
| ASMT                | 18        | 25     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 2.34%   |
| Kingston SA400S37240G 240GB SSD    | 131       | 1.29%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 122       | 1.2%    |
| Seagate ST500DM002-1BD142 500GB    | 83        | 0.82%   |
| Crucial CT480BX500SSD1 480GB       | 77        | 0.76%   |
| Apple SSD AP0128H 121GB            | 77        | 0.76%   |
| Unknown                            | 75        | 0.74%   |
| Apple SSD SM0128G 121GB            | 72        | 0.71%   |
| Kingston SA400S37120G 120GB SSD    | 65        | 0.64%   |
| Kingston SV300S37A120G 120GB SSD   | 64        | 0.63%   |
| Toshiba DT01ACA050 500GB           | 61        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 60        | 0.59%   |
| Kingston SA400S37480G 480GB SSD    | 60        | 0.59%   |
| Samsung SSD 860 EVO 250GB          | 58        | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB       | 56        | 0.55%   |
| Crucial CT500MX500SSD1 500GB       | 55        | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB     | 54        | 0.53%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB        | 52        | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB     | 49        | 0.48%   |
| A-DATA SU800 512GB SSD             | 48        | 0.47%   |
| Unknown MMC Card  32GB             | 45        | 0.44%   |
| Samsung SSD 860 EVO 1TB            | 44        | 0.43%   |
| Samsung SSD 850 EVO 250GB          | 44        | 0.43%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.42%   |
| Samsung SSD 850 EVO 500GB          | 40        | 0.39%   |
| Crucial CT240BX500SSD1 240GB       | 40        | 0.39%   |
| Unknown AGND3R  16GB               | 39        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB     | 39        | 0.38%   |
| Toshiba DT01ACA100 1TB             | 38        | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 37        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 37        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB     | 36        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 35        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB     | 34        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB           | 33        | 0.33%   |
| Hitachi HDS721050CLA362 500GB      | 32        | 0.32%   |
| Unknown HAG2e  16GB                | 30        | 0.3%    |
| Toshiba HDWD110 1TB                | 30        | 0.3%    |
| SABRENT Disk 752GB                 | 30        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1116      | 2042   | 31.83%  |
| WDC                 | 910       | 1535   | 25.96%  |
| Toshiba             | 531       | 789    | 15.15%  |
| Fujitsu             | 284       | 294    | 8.1%    |
| Hitachi             | 264       | 347    | 7.53%   |
| HGST                | 147       | 249    | 4.19%   |
| Samsung Electronics | 90        | 110    | 2.57%   |
| SABRENT             | 30        | 31     | 0.86%   |
| Unknown             | 29        | 38     | 0.83%   |
| Maxtor              | 22        | 24     | 0.63%   |
| Apple               | 14        | 17     | 0.4%    |
| Hewlett-Packard     | 7         | 17     | 0.2%    |
| External            | 6         | 7      | 0.17%   |
| Intenso             | 5         | 5      | 0.14%   |
| ASMedia             | 5         | 5      | 0.14%   |
| USB3.0              | 4         | 4      | 0.11%   |
| JMicron Technology  | 4         | 7      | 0.11%   |
| QNAP                | 3         | 4      | 0.09%   |
| HPE                 | 3         | 10     | 0.09%   |
| ASMT                | 3         | 4      | 0.09%   |
| IBM/Hitachi         | 2         | 2      | 0.06%   |
| IBM-ESXS            | 2         | 4      | 0.06%   |
| WD MediaMax         | 1         | 6      | 0.03%   |
| Unknown (CF)        | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SSK                 | 1         | 1      | 0.03%   |
| Space ke            | 1         | 1      | 0.03%   |
| SILICONMOTION       | 1         | 1      | 0.03%   |
| SD                  | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| pqi                 | 1         | 1      | 0.03%   |
| Pear 2TB            | 1         | 1      | 0.03%   |
| NAS                 | 1         | 5      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 4      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| Hajaan              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 637       | 862    | 20.48%  |
| Kingston            | 472       | 597    | 15.18%  |
| Crucial             | 370       | 446    | 11.9%   |
| SanDisk             | 239       | 300    | 7.68%   |
| WDC                 | 140       | 167    | 4.5%    |
| A-DATA Technology   | 122       | 203    | 3.92%   |
| China               | 103       | 118    | 3.31%   |
| Apple               | 98        | 108    | 3.15%   |
| Intel               | 90        | 132    | 2.89%   |
| Micron Technology   | 54        | 75     | 1.74%   |
| SPCC                | 49        | 56     | 1.58%   |
| PNY                 | 45        | 84     | 1.45%   |
| Transcend           | 43        | 50     | 1.38%   |
| Toshiba             | 41        | 50     | 1.32%   |
| SK hynix            | 38        | 48     | 1.22%   |
| Netac               | 35        | 95     | 1.13%   |
| Intenso             | 33        | 42     | 1.06%   |
| LITEON              | 29        | 34     | 0.93%   |
| Patriot             | 28        | 30     | 0.9%    |
| OCZ                 | 23        | 27     | 0.74%   |
| GOODRAM             | 21        | 29     | 0.68%   |
| Team                | 20        | 41     | 0.64%   |
| LITEONIT            | 20        | 27     | 0.64%   |
| JMicron Technology  | 19        | 19     | 0.61%   |
| Apacer              | 18        | 18     | 0.58%   |
| Unknown             | 16        | 18     | 0.51%   |
| ASMT                | 13        | 16     | 0.42%   |
| Seagate             | 12        | 15     | 0.39%   |
| Hewlett-Packard     | 12        | 18     | 0.39%   |
| Gigabyte Technology | 12        | 12     | 0.39%   |
| Corsair             | 11        | 15     | 0.35%   |
| KingDian            | 9         | 9      | 0.29%   |
| Plextor             | 8         | 11     | 0.26%   |
| Unknown             | 7         | 10     | 0.23%   |
| Mushkin             | 7         | 8      | 0.23%   |
| Lexar               | 7         | 9      | 0.23%   |
| Hajaan              | 7         | 8      | 0.23%   |
| LDLC                | 6         | 6      | 0.19%   |
| KIOXIA-EXCERIA      | 6         | 9      | 0.19%   |
| Xinhaike            | 5         | 8      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3005      | 5587   | 35.98%  |
| SSD     | 2735      | 4042   | 32.75%  |
| NVMe    | 1964      | 2757   | 23.52%  |
| MMC     | 545       | 674    | 6.53%   |
| Unknown | 102       | 158    | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4740      | 9089   | 62.29%  |
| NVMe | 1957      | 2744   | 25.72%  |
| MMC  | 545       | 674    | 7.16%   |
| SAS  | 367       | 711    | 4.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 3742      | 5260   | 61.4%   |
| 0.51-1.0    | 1405      | 2180   | 23.06%  |
| 1.01-2.0    | 424       | 751    | 6.96%   |
| 3.01-4.0    | 198       | 540    | 3.25%   |
| 4.01-10.0   | 176       | 479    | 2.89%   |
| 2.01-3.0    | 97        | 193    | 1.59%   |
| 10.01-20.0  | 50        | 221    | 0.82%   |
| 20.01-50.0  | 1         | 1      | 0.02%   |
| 50.01-100.0 | 1         | 4      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1502      | 21.96%  |
| 101-250        | 1482      | 21.67%  |
| 251-500        | 1146      | 16.75%  |
| 501-1000       | 749       | 10.95%  |
| 51-100         | 421       | 6.15%   |
| 1-20           | 385       | 5.63%   |
| 1001-2000      | 373       | 5.45%   |
| More than 3000 | 342       | 5%      |
| 21-50          | 291       | 4.25%   |
| 2001-3000      | 149       | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2538      | 36.34%  |
| Unknown        | 1502      | 21.51%  |
| 21-50          | 653       | 9.35%   |
| 101-250        | 635       | 9.09%   |
| 51-100         | 546       | 7.82%   |
| 251-500        | 398       | 5.7%    |
| 501-1000       | 301       | 4.31%   |
| 1001-2000      | 167       | 2.39%   |
| More than 3000 | 145       | 2.08%   |
| 2001-3000      | 77        | 1.1%    |
| 0              | 22        | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 25        | 25     | 2.53%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 21        | 25     | 2.13%   |
| Seagate ST500DM002-1BD142 500GB      | 21        | 36     | 2.13%   |
| Kingston SV300S37A120G 120GB SSD     | 21        | 21     | 2.13%   |
| Hitachi HTS543216L9SA02 160GB        | 11        | 11     | 1.11%   |
| Seagate ST9500325AS 500GB            | 10        | 12     | 1.01%   |
| Toshiba MK1655GSXF 160GB             | 9         | 9      | 0.91%   |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 0.91%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 8         | 8      | 0.81%   |
| Hitachi HDS721050CLA362 500GB        | 8         | 8      | 0.81%   |
| Toshiba DT01ACA050 500GB             | 7         | 8      | 0.71%   |
| Seagate ST9500420AS 500GB            | 7         | 7      | 0.71%   |
| Seagate ST3500418AS 500GB            | 7         | 9      | 0.71%   |
| Seagate ST3250318AS 250GB            | 7         | 7      | 0.71%   |
| Seagate ST250DM000-1BD141 250GB      | 7         | 7      | 0.71%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.61%   |
| Seagate ST31000528AS 1TB             | 6         | 7      | 0.61%   |
| Seagate ST1000DM003-9YN162 1TB       | 6         | 7      | 0.61%   |
| Hitachi HDS721050DLE630 500GB        | 6         | 11     | 0.61%   |
| HGST HTS541010A9E680 1TB             | 6         | 6      | 0.61%   |
| WDC WD20EARX-00PASB0 2TB             | 5         | 5      | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB             | 5         | 5      | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB             | 5         | 5      | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 0.51%   |
| Seagate ST31500341AS 1TB             | 5         | 7      | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 7      | 0.51%   |
| Hitachi HTS542512K9SA00 120GB        | 5         | 6      | 0.51%   |
| HGST HTS725050A7E630 500GB           | 5         | 6      | 0.51%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 4      | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 4         | 5      | 0.41%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 4         | 4      | 0.41%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.41%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.41%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 4      | 0.41%   |
| Seagate ST3500413AS 500GB            | 4         | 5      | 0.41%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.41%   |
| Seagate ST2000DL003-9VT166 2TB       | 4         | 4      | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 4      | 0.41%   |
| Samsung Electronics SSD 970 EVO 1TB  | 4         | 5      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 253       | 343    | 26.44%  |
| WDC                 | 204       | 255    | 21.32%  |
| Hitachi             | 95        | 114    | 9.93%   |
| Toshiba             | 74        | 79     | 7.73%   |
| Samsung Electronics | 56        | 61     | 5.85%   |
| Kingston            | 45        | 50     | 4.7%    |
| Fujitsu             | 35        | 36     | 3.66%   |
| Intel               | 34        | 41     | 3.55%   |
| HGST                | 24        | 26     | 2.51%   |
| SK hynix            | 20        | 24     | 2.09%   |
| Crucial             | 16        | 21     | 1.67%   |
| SanDisk             | 15        | 16     | 1.57%   |
| A-DATA Technology   | 15        | 18     | 1.57%   |
| Micron Technology   | 14        | 20     | 1.46%   |
| Maxtor              | 10        | 10     | 1.04%   |
| LITEONIT            | 4         | 5      | 0.42%   |
| LITEON              | 3         | 3      | 0.31%   |
| Hewlett-Packard     | 3         | 5      | 0.31%   |
| China               | 3         | 3      | 0.31%   |
| Apple               | 3         | 4      | 0.31%   |
| Transcend           | 2         | 2      | 0.21%   |
| SPCC                | 2         | 2      | 0.21%   |
| ShiJi               | 2         | 2      | 0.21%   |
| PNY                 | 2         | 7      | 0.21%   |
| OCZ                 | 2         | 2      | 0.21%   |
| JMicron Technology  | 2         | 3      | 0.21%   |
| Apacer              | 2         | 2      | 0.21%   |
| Unknown             | 2         | 2      | 0.21%   |
| Western Digital     | 1         | 2      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| Plextor             | 1         | 1      | 0.1%    |
| Patriot             | 1         | 1      | 0.1%    |
| Netac               | 1         | 1      | 0.1%    |
| Lenovo              | 1         | 1      | 0.1%    |
| KingSpec            | 1         | 1      | 0.1%    |
| KingDian            | 1         | 1      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |
| IBM                 | 1         | 1      | 0.1%    |
| GOODRAM             | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 253       | 343    | 34.99%  |
| WDC                 | 196       | 246    | 27.11%  |
| Hitachi             | 95        | 114    | 13.14%  |
| Toshiba             | 71        | 76     | 9.82%   |
| Fujitsu             | 35        | 36     | 4.84%   |
| Samsung Electronics | 27        | 27     | 3.73%   |
| HGST                | 24        | 26     | 3.32%   |
| Maxtor              | 10        | 10     | 1.38%   |
| Hewlett-Packard     | 3         | 5      | 0.41%   |
| Apple               | 3         | 4      | 0.41%   |
| JMicron Technology  | 2         | 3      | 0.28%   |
| USB3.0              | 1         | 1      | 0.14%   |
| IBM/Hitachi         | 1         | 1      | 0.14%   |
| IBM                 | 1         | 1      | 0.14%   |
| ASMedia             | 1         | 1      | 0.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 690       | 894    | 74.92%  |
| SSD  | 192       | 228    | 20.85%  |
| NVMe | 39        | 50     | 4.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 3.85%   |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 3.85%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 3.85%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 3.85%   |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 3.85%   |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 3.85%   |
| Seagate ST3500630A 500GB                        | 1         | 1      | 3.85%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB     | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 980 250GB               | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 3.85%   |
| Samsung Electronics SP0802N 80GB                | 1         | 1      | 3.85%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 3.85%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 3.85%   |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 3.85%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 1      | 3.85%   |
| KingDian S400 120GB                             | 1         | 1      | 3.85%   |
| Intel SSDSC2KW256G8 256GB                       | 1         | 1      | 3.85%   |
| Inland SATA SSD 128GB                           | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 3.85%   |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                      | 1         | 2      | 3.85%   |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 3.85%   |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 3.85%   |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 3.85%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 30.77%  |
| Seagate             | 6         | 7      | 23.08%  |
| HGST                | 3         | 4      | 11.54%  |
| WDC                 | 2         | 2      | 7.69%   |
| Toshiba             | 1         | 1      | 3.85%   |
| KingDian            | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Inland              | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 2      | 3.85%   |
| Hewlett-Packard     | 1         | 2      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4795      | 8840   | 65.24%  |
| Detected | 1630      | 3174   | 22.18%  |
| Malfunc  | 897       | 1172   | 12.2%   |
| Failed   | 26        | 30     | 0.35%   |
| Limited  | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3976      | 49.94%  |
| AMD                              | 1018      | 12.79%  |
| Samsung Electronics              | 803       | 10.09%  |
| Nvidia                           | 429       | 5.39%   |
| SanDisk                          | 323       | 4.06%   |
| SK hynix                         | 139       | 1.75%   |
| ASMedia Technology               | 130       | 1.63%   |
| Phison Electronics               | 112       | 1.41%   |
| Kingston Technology Company      | 98        | 1.23%   |
| Apple                            | 86        | 1.08%   |
| Marvell Technology Group         | 80        | 1%      |
| Toshiba America Info Systems     | 75        | 0.94%   |
| Micron Technology                | 72        | 0.9%    |
| JMicron Technology               | 72        | 0.9%    |
| Micron/Crucial Technology        | 69        | 0.87%   |
| LSI Logic / Symbios Logic        | 65        | 0.82%   |
| KIOXIA                           | 64        | 0.8%    |
| Broadcom / LSI                   | 57        | 0.72%   |
| ADATA Technology                 | 53        | 0.67%   |
| Silicon Motion                   | 49        | 0.62%   |
| VIA Technologies                 | 33        | 0.41%   |
| Hewlett-Packard                  | 16        | 0.2%    |
| Solid State Storage Technology   | 15        | 0.19%   |
| MAXIO Technology (Hangzhou)      | 15        | 0.19%   |
| Adaptec                          | 15        | 0.19%   |
| Realtek Semiconductor            | 14        | 0.18%   |
| Union Memory (Shenzhen)          | 10        | 0.13%   |
| Silicon Image                    | 9         | 0.11%   |
| Silicon Integrated Systems [SiS] | 8         | 0.1%    |
| Lite-On Technology               | 7         | 0.09%   |
| Seagate Technology               | 6         | 0.08%   |
| Shenzhen Longsys Electronics     | 5         | 0.06%   |
| Lenovo                           | 4         | 0.05%   |
| INNOGRIT                         | 4         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.04%   |
| ULi Electronics                  | 3         | 0.04%   |
| Jiangsu Huacun Elec.             | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| 3ware                            | 3         | 0.04%   |
| Integrated Technology Express    | 2         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 693       | 7.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 419       | 4.58%   |
| Nvidia MCP79 AHCI Controller                                                            | 366       | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 294       | 3.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 265       | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 222       | 2.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 178       | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 158       | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 157       | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 153       | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 152       | 1.66%   |
| AMD 400 Series Chipset SATA Controller                                                  | 147       | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 146       | 1.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 136       | 1.49%   |
| Samsung NVMe SSD Controller 980                                                         | 133       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 125       | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 118       | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 115       | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 114       | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 104       | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 101       | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 100       | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 99        | 1.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 93        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 87        | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 84        | 0.92%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 84        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 81        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 80        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 79        | 0.86%   |
| Apple S1X NVMe Controller                                                               | 79        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 78        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 74        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 70        | 0.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 69        | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 67        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 64        | 0.7%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 63        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 63        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 63        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4658      | 57.41%  |
| NVMe | 1954      | 24.08%  |
| IDE  | 903       | 11.13%  |
| RAID | 483       | 5.95%   |
| SAS  | 94        | 1.16%   |
| SCSI | 21        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5188      | 77.84%  |
| AMD                   | 1232      | 18.48%  |
| ARM                   | 225       | 3.38%   |
| CentaurHauls          | 8         | 0.12%   |
| Phytium               | 4         | 0.06%   |
| sifive,u74-mc         | 3         | 0.05%   |
| Unknown               | 2         | 0.03%   |
| Qualcomm              | 1         | 0.02%   |
| Marvell Semiconductor | 1         | 0.02%   |
| HISILICON             | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 5.32%   |
| ARM Processor                                 | 189       | 2.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 181       | 2.71%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 2.22%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 92        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 77        | 1.15%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 63        | 0.94%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 59        | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 50        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 50        | 0.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.7%    |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 43        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.54%   |
| AMD Ryzen 5 3600 6-Core Processor             | 36        | 0.54%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.52%   |
| Intel Celeron N5105 @ 2.00GHz                 | 35        | 0.52%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 32        | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 0.46%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 30        | 0.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 29        | 0.43%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.42%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 28        | 0.42%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 28        | 0.42%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 27        | 0.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 0.4%    |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 26        | 0.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.39%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 26        | 0.39%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 25        | 0.37%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 24        | 0.36%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1314      | 19.71%  |
| Intel Core i7           | 790       | 11.85%  |
| Other                   | 746       | 11.19%  |
| Intel Core 2 Duo        | 589       | 8.83%   |
| Intel Celeron           | 489       | 7.33%   |
| Intel Core i3           | 486       | 7.29%   |
| AMD Ryzen 5             | 309       | 4.63%   |
| Intel Xeon              | 253       | 3.79%   |
| Intel Pentium           | 232       | 3.48%   |
| AMD Ryzen 7             | 211       | 3.16%   |
| Intel Atom              | 132       | 1.98%   |
| AMD Ryzen 9             | 99        | 1.48%   |
| Intel Core 2            | 78        | 1.17%   |
| Intel Pentium Dual-Core | 75        | 1.12%   |
| AMD FX                  | 70        | 1.05%   |
| AMD Ryzen 3             | 50        | 0.75%   |
| Intel Core 2 Quad       | 39        | 0.58%   |
| AMD A6                  | 38        | 0.57%   |
| AMD Ryzen 7 PRO         | 32        | 0.48%   |
| Intel Core i9           | 31        | 0.46%   |
| AMD A10                 | 31        | 0.46%   |
| AMD Ryzen Threadripper  | 25        | 0.37%   |
| AMD Ryzen 5 PRO         | 25        | 0.37%   |
| AMD A4                  | 25        | 0.37%   |
| Intel Genuine           | 24        | 0.36%   |
| AMD Athlon              | 24        | 0.36%   |
| Intel Pentium M         | 22        | 0.33%   |
| Intel Pentium Gold      | 22        | 0.33%   |
| Intel Pentium 4         | 22        | 0.33%   |
| Intel Pentium Silver    | 21        | 0.31%   |
| AMD A8                  | 20        | 0.3%    |
| Intel Pentium Dual      | 19        | 0.28%   |
| AMD Athlon II X2        | 18        | 0.27%   |
| ARM Allwinner           | 17        | 0.25%   |
| AMD Phenom II X4        | 17        | 0.25%   |
| AMD Athlon 64 X2        | 17        | 0.25%   |
| AMD GX                  | 15        | 0.22%   |
| AMD G                   | 12        | 0.18%   |
| AMD E                   | 12        | 0.18%   |
| AMD Phenom II X6        | 11        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2850      | 42.71%  |
| 4       | 2230      | 33.42%  |
| 6       | 583       | 8.74%   |
| 8       | 441       | 6.61%   |
| 1       | 219       | 3.28%   |
| 12      | 94        | 1.41%   |
| 16      | 86        | 1.29%   |
| 10      | 44        | 0.66%   |
| 3       | 27        | 0.4%    |
| 24      | 19        | 0.28%   |
| Unknown | 19        | 0.28%   |
| 14      | 17        | 0.25%   |
| 32      | 16        | 0.24%   |
| 20      | 6         | 0.09%   |
| 28      | 5         | 0.07%   |
| 18      | 4         | 0.06%   |
| 48      | 3         | 0.04%   |
| 44      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 192     | 1         | 0.01%   |
| 96      | 1         | 0.01%   |
| 80      | 1         | 0.01%   |
| 64      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6512      | 97.66%  |
| 2       | 127       | 1.9%    |
| Unknown | 19        | 0.28%   |
| 3       | 5         | 0.07%   |
| 4       | 3         | 0.04%   |
| 8       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3810      | 57.1%   |
| 1       | 2842      | 42.6%   |
| Unknown | 19        | 0.28%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6478      | 97.17%  |
| 32-bit         | 118       | 1.77%   |
| Unknown        | 50        | 0.75%   |
| 64-bit         | 21        | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1294      | 19.08%  |
| 0x1067a    | 554       | 8.17%   |
| 0x306a9    | 302       | 4.45%   |
| 0x306c3    | 289       | 4.26%   |
| 0x206a7    | 284       | 4.19%   |
| 0x806c1    | 276       | 4.07%   |
| 0x306d4    | 227       | 3.35%   |
| 0x906ea    | 161       | 2.37%   |
| 0x506e3    | 143       | 2.11%   |
| 0x806ec    | 132       | 1.95%   |
| 0x806e9    | 124       | 1.83%   |
| 0x30678    | 120       | 1.77%   |
| 0x806ea    | 102       | 1.5%    |
| 0x406e3    | 93        | 1.37%   |
| 0x40651    | 88        | 1.3%    |
| 0x406c4    | 83        | 1.22%   |
| 0x08108109 | 83        | 1.22%   |
| 0x906e9    | 81        | 1.19%   |
| 0xa0653    | 79        | 1.17%   |
| 0x6f6      | 72        | 1.06%   |
| 0x906c0    | 70        | 1.03%   |
| 0x08701021 | 68        | 1%      |
| 0x0a50000c | 64        | 0.94%   |
| 0x906eb    | 63        | 0.93%   |
| 0x20655    | 61        | 0.9%    |
| 0x08600106 | 59        | 0.87%   |
| 0xa0652    | 58        | 0.86%   |
| 0x706a8    | 54        | 0.8%    |
| 0x10676    | 54        | 0.8%    |
| 0x506c9    | 50        | 0.74%   |
| 0x6fd      | 48        | 0.71%   |
| 0x0a201016 | 42        | 0.62%   |
| 0x08608103 | 41        | 0.6%    |
| 0xa0655    | 40        | 0.59%   |
| 0x706e5    | 40        | 0.59%   |
| 0x0600611a | 40        | 0.59%   |
| 0xa0671    | 38        | 0.56%   |
| 0x106c2    | 36        | 0.53%   |
| 0x0800820d | 35        | 0.52%   |
| 0x306f2    | 32        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 878       | 13.15%  |
| Penryn           | 645       | 9.66%   |
| Haswell          | 511       | 7.65%   |
| Unknown          | 429       | 6.42%   |
| IvyBridge        | 396       | 5.93%   |
| SandyBridge      | 389       | 5.83%   |
| TigerLake        | 320       | 4.79%   |
| Skylake          | 314       | 4.7%    |
| Broadwell        | 268       | 4.01%   |
| Silvermont       | 259       | 3.88%   |
| Zen 2            | 224       | 3.35%   |
| Zen 3            | 213       | 3.19%   |
| CometLake        | 212       | 3.17%   |
| Core             | 195       | 2.92%   |
| Zen+             | 192       | 2.88%   |
| Westmere         | 140       | 2.1%    |
| Excavator        | 93        | 1.39%   |
| Zen              | 89        | 1.33%   |
| Goldmont plus    | 89        | 1.33%   |
| K10              | 81        | 1.21%   |
| Piledriver       | 79        | 1.18%   |
| IceLake          | 79        | 1.18%   |
| Tremont          | 77        | 1.15%   |
| Bonnell          | 76        | 1.14%   |
| Goldmont         | 60        | 0.9%    |
| P6               | 55        | 0.82%   |
| Nehalem          | 43        | 0.64%   |
| Alderlake Hybrid | 42        | 0.63%   |
| NetBurst         | 40        | 0.6%    |
| Bobcat           | 38        | 0.57%   |
| K8 Hammer        | 35        | 0.52%   |
| Puma             | 30        | 0.45%   |
| Steamroller      | 23        | 0.34%   |
| Jaguar           | 23        | 0.34%   |
| Bulldozer        | 18        | 0.27%   |
| K10 Llano        | 11        | 0.16%   |
| K8 & K10 hybrid  | 6         | 0.09%   |
| K6               | 4         | 0.06%   |
| Gracemont        | 1         | 0.01%   |
| Geode            | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3888      | 53.75%  |
| Nvidia                                       | 1836      | 25.38%  |
| AMD                                          | 1298      | 17.94%  |
| ASPEED Technology                            | 99        | 1.37%   |
| Matrox Electronics Systems                   | 93        | 1.29%   |
| VIA Technologies                             | 8         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.08%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 4.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 295       | 3.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 264       | 3.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 199       | 2.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 167       | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 159       | 2.12%   |
| Intel HD Graphics 6000                                                                   | 155       | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 146       | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 134       | 1.79%   |
| Intel HD Graphics 620                                                                    | 121       | 1.62%   |
| Intel UHD Graphics 620                                                                   | 119       | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 112       | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 108       | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 106       | 1.42%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 105       | 1.4%    |
| AMD Renoir                                                                               | 104       | 1.39%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 99        | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 98        | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 98        | 1.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 89        | 1.19%   |
| Intel HD Graphics 530                                                                    | 84        | 1.12%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 84        | 1.12%   |
| Intel HD Graphics 5500                                                                   | 83        | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 81        | 1.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 76        | 1.01%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 75        | 1%      |
| Intel JasperLake [UHD Graphics]                                                          | 73        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 73        | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 71        | 0.95%   |
| Intel HD Graphics 630                                                                    | 69        | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 66        | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 59        | 0.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 59        | 0.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59        | 0.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 58        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 57        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 57        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 55        | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 53        | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 53        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3190      | 47.7%   |
| 1 x Nvidia                        | 1196      | 17.88%  |
| 1 x AMD                           | 1053      | 15.74%  |
| Intel + Nvidia                    | 529       | 7.91%   |
| Other                             | 259       | 3.87%   |
| Intel + AMD                       | 95        | 1.42%   |
| 1 x Matrox                        | 89        | 1.33%   |
| AMD + Nvidia                      | 81        | 1.21%   |
| 1 x ASPEED                        | 76        | 1.14%   |
| 2 x AMD                           | 59        | 0.88%   |
| Nvidia + ASPEED                   | 12        | 0.18%   |
| 2 x Nvidia                        | 8         | 0.12%   |
| 1 x VIA                           | 8         | 0.12%   |
| AMD + ASPEED                      | 8         | 0.12%   |
| 1 x SiS                           | 6         | 0.09%   |
| 2 x Intel                         | 3         | 0.04%   |
| 1 x Zhaoxin                       | 3         | 0.04%   |
| Nvidia + Matrox                   | 3         | 0.04%   |
| Intel + 2 x Nvidia                | 3         | 0.04%   |
| 2 x Nvidia + 1 x ASPEED           | 2         | 0.03%   |
| 3 x AMD                           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x S3 Graphics                   | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| AMD + Matrox                      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4754      | 70.88%  |
| Unknown     | 1413      | 21.07%  |
| Proprietary | 540       | 8.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 4832      | 71.77%  |
| 0.01-0.5       | 799       | 11.87%  |
| 1.01-2.0       | 358       | 5.32%   |
| 3.01-4.0       | 232       | 3.45%   |
| 0.51-1.0       | 230       | 3.42%   |
| 7.01-8.0       | 127       | 1.89%   |
| 5.01-6.0       | 78        | 1.16%   |
| 8.01-16.0      | 36        | 0.53%   |
| 2.01-3.0       | 26        | 0.39%   |
| 16.01-24.0     | 7         | 0.1%    |
| 4.01-5.0       | 5         | 0.07%   |
| More than 64.0 | 1         | 0.01%   |
| 32.01-64.0     | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 699       | 12.04%  |
| Apple                   | 660       | 11.37%  |
| Samsung Electronics     | 555       | 9.56%   |
| BOE                     | 480       | 8.27%   |
| LG Display              | 420       | 7.23%   |
| Chimei Innolux          | 408       | 7.03%   |
| Dell                    | 309       | 5.32%   |
| Goldstar                | 251       | 4.32%   |
| Hewlett-Packard         | 166       | 2.86%   |
| Acer                    | 149       | 2.57%   |
| BenQ                    | 137       | 2.36%   |
| AOC                     | 121       | 2.08%   |
| Lenovo                  | 119       | 2.05%   |
| Philips                 | 113       | 1.95%   |
| Ancor Communications    | 106       | 1.83%   |
| Sharp                   | 77        | 1.33%   |
| Unknown                 | 69        | 1.19%   |
| ViewSonic               | 67        | 1.15%   |
| Iiyama                  | 66        | 1.14%   |
| Chi Mei Optoelectronics | 64        | 1.1%    |
| InfoVision              | 59        | 1.02%   |
| Eizo                    | 40        | 0.69%   |
| PANDA                   | 38        | 0.65%   |
| ASUSTek Computer        | 37        | 0.64%   |
| HannStar                | 33        | 0.57%   |
| NEC Computers           | 32        | 0.55%   |
| Sony                    | 30        | 0.52%   |
| LG Philips              | 23        | 0.4%    |
| LG Electronics          | 23        | 0.4%    |
| MSI                     | 17        | 0.29%   |
| CSO                     | 17        | 0.29%   |
| Unknown                 | 16        | 0.28%   |
| Panasonic               | 15        | 0.26%   |
| Vestel Elektronik       | 14        | 0.24%   |
| Vizio                   | 11        | 0.19%   |
| Toshiba                 | 11        | 0.19%   |
| Medion                  | 10        | 0.17%   |
| Fujitsu Siemens         | 9         | 0.16%   |
| CPT                     | 8         | 0.14%   |
| AGO                     | 8         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 209       | 3.52%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 187       | 3.15%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 112       | 1.89%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 54        | 0.91%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 53        | 0.89%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 42        | 0.71%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 41        | 0.69%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.69%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.64%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 26        | 0.44%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 25        | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 25        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 22        | 0.37%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.37%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 21        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 21        | 0.35%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 18        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 18        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 18        | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 16        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 16        | 0.27%   |
| Unknown                                                              | 16        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 15        | 0.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 14        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 14        | 0.24%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 13        | 0.22%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                    | 13        | 0.22%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 13        | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 12        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 11        | 0.19%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 10        | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 10        | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 10        | 0.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 10        | 0.17%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 10        | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 10        | 0.17%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 10        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2233      | 40.05%  |
| 1366x768 (WXGA)    | 983       | 17.63%  |
| 1280x800 (WXGA)    | 532       | 9.54%   |
| 3840x2160 (4K)     | 300       | 5.38%   |
| 1280x1024 (SXGA)   | 212       | 3.8%    |
| 2560x1440 (QHD)    | 203       | 3.64%   |
| 1600x900 (HD+)     | 176       | 3.16%   |
| 1440x900 (WXGA+)   | 166       | 2.98%   |
| 1920x1200 (WUXGA)  | 119       | 2.13%   |
| 1680x1050 (WSXGA+) | 111       | 1.99%   |
| Unknown            | 63        | 1.13%   |
| 2288x1287          | 55        | 0.99%   |
| 1024x600           | 50        | 0.9%    |
| 1024x768 (XGA)     | 42        | 0.75%   |
| 3440x1440          | 39        | 0.7%    |
| 2560x1080          | 37        | 0.66%   |
| 1360x768           | 36        | 0.65%   |
| 2560x1600          | 27        | 0.48%   |
| 3840x1080          | 22        | 0.39%   |
| 1600x1200          | 22        | 0.39%   |
| 1920x540           | 14        | 0.25%   |
| 3840x2400          | 13        | 0.23%   |
| 2880x1800          | 10        | 0.18%   |
| 2160x1440          | 9         | 0.16%   |
| 1400x1050          | 7         | 0.13%   |
| 2736x1824          | 6         | 0.11%   |
| 1920x1280          | 6         | 0.11%   |
| 4480x1440          | 5         | 0.09%   |
| 5760x1080          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3200x1080          | 4         | 0.07%   |
| 2048x1152          | 4         | 0.07%   |
| 1280x720 (HD)      | 4         | 0.07%   |
| 5760x2160          | 3         | 0.05%   |
| 3840x1600          | 3         | 0.05%   |
| 3200x1800 (QHD+)   | 3         | 0.05%   |
| 1800x1200          | 3         | 0.05%   |
| 1024x576           | 3         | 0.05%   |
| 5360x1440          | 2         | 0.04%   |
| 3840x1100          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 1099      | 19.09%  |
| 15      | 1077      | 18.71%  |
| 14      | 432       | 7.51%   |
| 24      | 399       | 6.93%   |
| 27      | 338       | 5.87%   |
| 23      | 324       | 5.63%   |
| 17      | 278       | 4.83%   |
| 21      | 265       | 4.6%    |
| 11      | 262       | 4.55%   |
| Unknown | 191       | 3.32%   |
| 19      | 146       | 2.54%   |
| 12      | 131       | 2.28%   |
| 18      | 110       | 1.91%   |
| 31      | 99        | 1.72%   |
| 22      | 73        | 1.27%   |
| 20      | 73        | 1.27%   |
| 10      | 57        | 0.99%   |
| 34      | 55        | 0.96%   |
| 142     | 53        | 0.92%   |
| 84      | 34        | 0.59%   |
| 32      | 28        | 0.49%   |
| 16      | 26        | 0.45%   |
| 72      | 23        | 0.4%    |
| 54      | 22        | 0.38%   |
| 25      | 22        | 0.38%   |
| 40      | 16        | 0.28%   |
| 28      | 16        | 0.28%   |
| 29      | 12        | 0.21%   |
| 26      | 12        | 0.21%   |
| 65      | 9         | 0.16%   |
| 52      | 7         | 0.12%   |
| 48      | 6         | 0.1%    |
| 43      | 6         | 0.1%    |
| 33      | 6         | 0.1%    |
| 46      | 5         | 0.09%   |
| 42      | 5         | 0.09%   |
| 49      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 35      | 4         | 0.07%   |
| 8       | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1869      | 32.99%  |
| 201-300        | 1283      | 22.64%  |
| 501-600        | 977       | 17.24%  |
| 401-500        | 564       | 9.95%   |
| 351-400        | 300       | 5.29%   |
| Unknown        | 191       | 3.37%   |
| 601-700        | 172       | 3.04%   |
| 701-800        | 90        | 1.59%   |
| 1001-1500      | 63        | 1.11%   |
| 1501-2000      | 61        | 1.08%   |
| More than 2000 | 54        | 0.95%   |
| 801-900        | 28        | 0.49%   |
| 901-1000       | 9         | 0.16%   |
| 101-200        | 5         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3645      | 68.96%  |
| 16/10   | 994       | 18.8%   |
| 5/4     | 198       | 3.75%   |
| Unknown | 157       | 2.97%   |
| 4/3     | 85        | 1.61%   |
| 21/9    | 69        | 1.31%   |
| 1.00    | 55        | 1.04%   |
| 3/2     | 48        | 0.91%   |
| 6/5     | 13        | 0.25%   |
| 32/9    | 5         | 0.09%   |
| 2.65    | 5         | 0.09%   |
| 3.40    | 2         | 0.04%   |
| 3.20    | 2         | 0.04%   |
| 1.96    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1178      | 20.64%  |
| 101-110        | 1068      | 18.71%  |
| 201-250        | 837       | 14.66%  |
| 71-80          | 355       | 6.22%   |
| 301-350        | 347       | 6.08%   |
| 151-200        | 305       | 5.34%   |
| 51-60          | 265       | 4.64%   |
| 351-500        | 210       | 3.68%   |
| 141-150        | 194       | 3.4%    |
| Unknown        | 191       | 3.35%   |
| More than 1000 | 166       | 2.91%   |
| 251-300        | 152       | 2.66%   |
| 121-130        | 146       | 2.56%   |
| 61-70          | 119       | 2.08%   |
| 41-50          | 56        | 0.98%   |
| 501-1000       | 46        | 0.81%   |
| 131-140        | 31        | 0.54%   |
| 111-120        | 24        | 0.42%   |
| 91-100         | 13        | 0.23%   |
| 1-40           | 5         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1615      | 28.98%  |
| 121-160       | 1595      | 28.62%  |
| 101-120       | 1570      | 28.17%  |
| 161-240       | 385       | 6.91%   |
| Unknown       | 191       | 3.43%   |
| 1-50          | 145       | 2.6%    |
| More than 240 | 72        | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4417      | 65.24%  |
| 0     | 1507      | 22.26%  |
| 2     | 760       | 11.23%  |
| 3     | 83        | 1.23%   |
| 4     | 2         | 0.03%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3121      | 32.32%  |
| Intel                             | 2997      | 31.03%  |
| Qualcomm Atheros                  | 842       | 8.72%   |
| Broadcom                          | 816       | 8.45%   |
| Nvidia                            | 417       | 4.32%   |
| Broadcom Limited                  | 270       | 2.8%    |
| Marvell Technology Group          | 141       | 1.46%   |
| MediaTek                          | 101       | 1.05%   |
| Ralink Technology                 | 80        | 0.83%   |
| TP-Link                           | 74        | 0.77%   |
| ASIX Electronics                  | 61        | 0.63%   |
| Ralink                            | 57        | 0.59%   |
| Samsung Electronics               | 46        | 0.48%   |
| Microchip Technology              | 30        | 0.31%   |
| Dell                              | 30        | 0.31%   |
| Sierra Wireless                   | 29        | 0.3%    |
| Xiaomi                            | 28        | 0.29%   |
| Mellanox Technologies             | 26        | 0.27%   |
| Qualcomm Atheros Communications   | 22        | 0.23%   |
| Huawei Technologies               | 22        | 0.23%   |
| Qualcomm                          | 21        | 0.22%   |
| Aquantia                          | 19        | 0.2%    |
| DisplayLink                       | 18        | 0.19%   |
| NetGear                           | 17        | 0.18%   |
| American Megatrends               | 17        | 0.18%   |
| Lenovo                            | 16        | 0.17%   |
| D-Link System                     | 15        | 0.16%   |
| D-Link                            | 15        | 0.16%   |
| Ericsson Business Mobile Networks | 14        | 0.14%   |
| JMicron Technology                | 13        | 0.13%   |
| Dresden Elektronik                | 13        | 0.13%   |
| ASUSTek Computer                  | 13        | 0.13%   |
| Microsoft                         | 12        | 0.12%   |
| Hewlett-Packard                   | 12        | 0.12%   |
| Edimax Technology                 | 12        | 0.12%   |
| VIA Technologies                  | 11        | 0.11%   |
| Sigma Designs                     | 10        | 0.1%    |
| OPPO Electronics                  | 10        | 0.1%    |
| ICS Advent                        | 10        | 0.1%    |
| Standard Microsystems             | 8         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 2192      | 19.42%  |
| Nvidia MCP79 Ethernet                                                                 | 367       | 3.25%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 363       | 3.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 311       | 2.75%   |
| Intel Wi-Fi 6 AX201                                                                   | 262       | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 214       | 1.9%    |
| Intel Wi-Fi 6 AX200                                                                   | 198       | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 177       | 1.57%   |
| Intel Wireless 7260                                                                   | 169       | 1.5%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 165       | 1.46%   |
| Intel Wireless 8265 / 8275                                                            | 164       | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 159       | 1.41%   |
| Intel Wireless 7265                                                                   | 153       | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 139       | 1.23%   |
| Intel Ethernet Connection (13) I219-V                                                 | 136       | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 110       | 0.97%   |
| Intel I211 Gigabit Network Connection                                                 | 95        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 93        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 91        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 90        | 0.8%    |
| Intel Wireless 8260                                                                   | 90        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 86        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 85        | 0.75%   |
| Intel Wireless 3165                                                                   | 85        | 0.75%   |
| Intel Ethernet Controller I225-V                                                      | 85        | 0.75%   |
| Intel I210 Gigabit Network Connection                                                 | 84        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 83        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 81        | 0.72%   |
| Intel Ethernet Connection I217-LM                                                     | 77        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 71        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                                  | 62        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 61        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 59        | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.52%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                                  | 57        | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 54        | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 53        | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 51        | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 50        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2106      | 44.93%  |
| Qualcomm Atheros                      | 685       | 14.61%  |
| Realtek Semiconductor                 | 617       | 13.16%  |
| Broadcom                              | 588       | 12.55%  |
| Broadcom Limited                      | 214       | 4.57%   |
| MediaTek                              | 93        | 1.98%   |
| Ralink Technology                     | 80        | 1.71%   |
| Ralink                                | 57        | 1.22%   |
| TP-Link                               | 54        | 1.15%   |
| Sierra Wireless                       | 29        | 0.62%   |
| Qualcomm Atheros Communications       | 22        | 0.47%   |
| Dell                                  | 18        | 0.38%   |
| NetGear                               | 17        | 0.36%   |
| ASUSTek Computer                      | 13        | 0.28%   |
| Edimax Technology                     | 12        | 0.26%   |
| D-Link                                | 12        | 0.26%   |
| Microsoft                             | 8         | 0.17%   |
| D-Link System                         | 8         | 0.17%   |
| Marvell Technology Group              | 7         | 0.15%   |
| Fibocom                               | 7         | 0.15%   |
| Belkin Components                     | 7         | 0.15%   |
| Qualcomm                              | 6         | 0.13%   |
| Gemtek                                | 4         | 0.09%   |
| Wilocity                              | 3         | 0.06%   |
| IMC Networks                          | 3         | 0.06%   |
| AVM                                   | 3         | 0.06%   |
| Linksys                               | 2         | 0.04%   |
| Z-Com                                 | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Hewlett-Packard                       | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| CyberTAN Technology                   | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |
| 3Com                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 363       | 7.71%   |
| Intel Wi-Fi 6 AX201                                                                   | 262       | 5.57%   |
| Intel Wi-Fi 6 AX200                                                                   | 198       | 4.21%   |
| Intel Wireless 7260                                                                   | 169       | 3.59%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 165       | 3.51%   |
| Intel Wireless 8265 / 8275                                                            | 164       | 3.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 159       | 3.38%   |
| Intel Wireless 7265                                                                   | 153       | 3.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 110       | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 93        | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 91        | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 90        | 1.91%   |
| Intel Wireless 8260                                                                   | 90        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 86        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 85        | 1.81%   |
| Intel Wireless 3165                                                                   | 85        | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 83        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 81        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 71        | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 61        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 59        | 1.25%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 54        | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 53        | 1.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 51        | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 50        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 46        | 0.98%   |
| Intel Wireless-AC 9260                                                                | 43        | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 41        | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 40        | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 39        | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 35        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 35        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 35        | 0.74%   |
| Realtek 802.11ac NIC                                                                  | 31        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 31        | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 29        | 0.62%   |
| Intel Wireless 3160                                                                   | 28        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                                        | 27        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 26        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2871      | 46.14%  |
| Intel                            | 1767      | 28.39%  |
| Nvidia                           | 417       | 6.7%    |
| Broadcom                         | 278       | 4.47%   |
| Qualcomm Atheros                 | 234       | 3.76%   |
| Marvell Technology Group         | 135       | 2.17%   |
| ASIX Electronics                 | 61        | 0.98%   |
| Broadcom Limited                 | 59        | 0.95%   |
| Samsung Electronics              | 46        | 0.74%   |
| Microchip Technology             | 30        | 0.48%   |
| Xiaomi                           | 27        | 0.43%   |
| Mellanox Technologies            | 23        | 0.37%   |
| TP-Link                          | 20        | 0.32%   |
| Aquantia                         | 19        | 0.31%   |
| DisplayLink                      | 18        | 0.29%   |
| American Megatrends              | 17        | 0.27%   |
| Lenovo                           | 16        | 0.26%   |
| Qualcomm                         | 14        | 0.22%   |
| Huawei Technologies              | 14        | 0.22%   |
| JMicron Technology               | 13        | 0.21%   |
| VIA Technologies                 | 11        | 0.18%   |
| OPPO Electronics                 | 10        | 0.16%   |
| ICS Advent                       | 10        | 0.16%   |
| Standard Microsystems            | 8         | 0.13%   |
| Silicon Integrated Systems [SiS] | 7         | 0.11%   |
| MediaTek                         | 7         | 0.11%   |
| D-Link System                    | 7         | 0.11%   |
| Cypress Semiconductor            | 6         | 0.1%    |
| Motorola PCS                     | 5         | 0.08%   |
| IBM                              | 5         | 0.08%   |
| 3Com                             | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.06%   |
| NetXen Incorporated              | 4         | 0.06%   |
| Hewlett-Packard                  | 4         | 0.06%   |
| Emulex                           | 4         | 0.06%   |
| Attansic Technology              | 4         | 0.06%   |
| QLogic                           | 3         | 0.05%   |
| Microsoft                        | 3         | 0.05%   |
| Dell                             | 3         | 0.05%   |
| D-Link                           | 3         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2192      | 34.09%  |
| Nvidia MCP79 Ethernet                                             | 367       | 5.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 311       | 4.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 214       | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 177       | 2.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 139       | 2.16%   |
| Intel Ethernet Connection (13) I219-V                             | 136       | 2.12%   |
| Intel I211 Gigabit Network Connection                             | 95        | 1.48%   |
| Intel Ethernet Controller I225-V                                  | 85        | 1.32%   |
| Intel I210 Gigabit Network Connection                             | 84        | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 77        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 62        | 0.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 0.92%   |
| Intel Ethernet Connection (4) I219-V                              | 57        | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 49        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 49        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 48        | 0.75%   |
| Intel I350 Gigabit Network Connection                             | 45        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 45        | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 44        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 42        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 40        | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 40        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 38        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 37        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32        | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 31        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 30        | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 29        | 0.45%   |
| Nvidia MCP61 Ethernet                                             | 29        | 0.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 29        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 28        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 28        | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 28        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.4%    |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 26        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5761      | 55.45%  |
| WiFi     | 4478      | 43.1%   |
| Modem    | 137       | 1.32%   |
| Unknown  | 14        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3515      | 53.42%  |
| WiFi     | 3064      | 46.57%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3422      | 51.2%   |
| 1     | 2616      | 39.14%  |
| 0     | 287       | 4.29%   |
| 3     | 197       | 2.95%   |
| 4     | 83        | 1.24%   |
| 6     | 24        | 0.36%   |
| 5     | 23        | 0.34%   |
| 8     | 12        | 0.18%   |
| 7     | 8         | 0.12%   |
| 9     | 3         | 0.04%   |
| 20    | 2         | 0.03%   |
| 12    | 2         | 0.03%   |
| 17    | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 11    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5456      | 81.19%  |
| Yes  | 1264      | 18.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1706      | 45.24%  |
| Apple                           | 670       | 17.77%  |
| Realtek Semiconductor           | 303       | 8.04%   |
| Qualcomm Atheros Communications | 238       | 6.31%   |
| Cambridge Silicon Radio         | 179       | 4.75%   |
| Broadcom                        | 144       | 3.82%   |
| IMC Networks                    | 125       | 3.31%   |
| Lite-On Technology              | 107       | 2.84%   |
| Foxconn / Hon Hai               | 71        | 1.88%   |
| ASUSTek Computer                | 46        | 1.22%   |
| Dell                            | 39        | 1.03%   |
| Hewlett-Packard                 | 29        | 0.77%   |
| MediaTek                        | 26        | 0.69%   |
| Toshiba                         | 17        | 0.45%   |
| Realtek                         | 16        | 0.42%   |
| Ralink                          | 11        | 0.29%   |
| Ralink Technology               | 6         | 0.16%   |
| TP-Link                         | 4         | 0.11%   |
| Foxconn International           | 4         | 0.11%   |
| Alps Electric                   | 4         | 0.11%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Fujitsu                         | 3         | 0.08%   |
| Belkin Components               | 3         | 0.08%   |
| Marvell Semiconductor           | 2         | 0.05%   |
| Edimax Technology               | 2         | 0.05%   |
| Unknown                         | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 651       | 17.25%  |
| Intel AX201 Bluetooth                               | 423       | 11.21%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 365       | 9.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 224       | 5.94%   |
| Realtek Bluetooth Radio                             | 202       | 5.35%   |
| Intel AX200 Bluetooth                               | 190       | 5.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 179       | 4.74%   |
| Apple Bluetooth USB Host Controller                 | 173       | 4.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 145       | 3.84%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.01%   |
| Realtek  Bluetooth 4.2 Adapter                      | 67        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 52        | 1.38%   |
| Apple Bluetooth Host Controller                     | 46        | 1.22%   |
| Intel AX210 Bluetooth                               | 41        | 1.09%   |
| Intel Bluetooth Device                              | 40        | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 0.98%   |
| IMC Networks Bluetooth Radio                        | 37        | 0.98%   |
| IMC Networks Bluetooth Device                       | 33        | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 0.8%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 30        | 0.8%    |
| Lite-On Bluetooth Device                            | 28        | 0.74%   |
| MediaTek Wireless_Device                            | 25        | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.66%   |
| IMC Networks Wireless_Device                        | 24        | 0.64%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 18        | 0.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 17        | 0.45%   |
| Realtek Bluetooth Radio                             | 16        | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.34%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.34%   |
| Lite-On Wireless_Device                             | 12        | 0.32%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4499      | 56.03%  |
| Nvidia                                       | 1465      | 18.25%  |
| AMD                                          | 1374      | 17.11%  |
| C-Media Electronics                          | 106       | 1.32%   |
| Logitech                                     | 53        | 0.66%   |
| Creative Labs                                | 36        | 0.45%   |
| ASUSTek Computer                             | 28        | 0.35%   |
| Texas Instruments                            | 26        | 0.32%   |
| Generalplus Technology                       | 26        | 0.32%   |
| Realtek Semiconductor                        | 25        | 0.31%   |
| Plantronics                                  | 21        | 0.26%   |
| KTMicro                                      | 21        | 0.26%   |
| Lenovo                                       | 20        | 0.25%   |
| Creative Technology                          | 18        | 0.22%   |
| VIA Technologies                             | 16        | 0.2%    |
| GN Netcom                                    | 16        | 0.2%    |
| JMTek                                        | 15        | 0.19%   |
| Focusrite-Novation                           | 15        | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 12        | 0.15%   |
| Micro Star International                     | 11        | 0.14%   |
| Kingston Technology                          | 11        | 0.14%   |
| Hewlett-Packard                              | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.1%    |
| Sennheiser Communications                    | 8         | 0.1%    |
| RODE Microphones                             | 8         | 0.1%    |
| Razer USA                                    | 8         | 0.1%    |
| SteelSeries ApS                              | 7         | 0.09%   |
| GYROCOM C&C                                  | 7         | 0.09%   |
| Dell                                         | 7         | 0.09%   |
| BEHRINGER International                      | 7         | 0.09%   |
| Yamaha                                       | 5         | 0.06%   |
| Tenx Technology                              | 5         | 0.06%   |
| Microsoft                                    | 5         | 0.06%   |
| Giga-Byte Technology                         | 5         | 0.06%   |
| Cambridge Silicon Radio                      | 5         | 0.06%   |
| Ensoniq                                      | 4         | 0.05%   |
| Corsair                                      | 4         | 0.05%   |
| Apple                                        | 4         | 0.05%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XMOS                                         | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 464       | 4.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 395       | 4.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 370       | 3.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 350       | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 342       | 3.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 319       | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 310       | 3.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 277       | 2.92%   |
| Intel Broadwell-U Audio Controller                                                                | 248       | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 245       | 2.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 243       | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 231       | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 199       | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 180       | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 179       | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 173       | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 158       | 1.66%   |
| Intel 200 Series PCH HD Audio                                                                     | 157       | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 131       | 1.38%   |
| Intel Comet Lake PCH cAVS                                                                         | 124       | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 124       | 1.3%    |
| AMD FCH Azalia Controller                                                                         | 122       | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 116       | 1.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 116       | 1.22%   |
| Intel 8 Series HD Audio Controller                                                                | 116       | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 111       | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 103       | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 102       | 1.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 99        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 98        | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 95        | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 93        | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 88        | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 84        | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 83        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 74        | 0.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 73        | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 71        | 0.75%   |
| Intel Jasper Lake HD Audio                                                                        | 71        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 64        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1374      | 21.43%  |
| SK hynix            | 1322      | 20.62%  |
| Kingston            | 684       | 10.67%  |
| Unknown             | 607       | 9.47%   |
| Micron Technology   | 536       | 8.36%   |
| Crucial             | 519       | 8.09%   |
| Corsair             | 241       | 3.76%   |
| G.Skill             | 159       | 2.48%   |
| Elpida              | 120       | 1.87%   |
| A-DATA Technology   | 108       | 1.68%   |
| Ramaxel Technology  | 85        | 1.33%   |
| Patriot             | 75        | 1.17%   |
| Unknown (ABCD)      | 59        | 0.92%   |
| Nanya Technology    | 57        | 0.89%   |
| Unknown             | 56        | 0.87%   |
| Team                | 38        | 0.59%   |
| GOODRAM             | 34        | 0.53%   |
| Smart               | 30        | 0.47%   |
| Transcend           | 24        | 0.37%   |
| AMD                 | 22        | 0.34%   |
| Hikvision           | 21        | 0.33%   |
| Hewlett-Packard     | 14        | 0.22%   |
| Apacer              | 14        | 0.22%   |
| Timetec             | 12        | 0.19%   |
| Qimonda             | 9         | 0.14%   |
| Silicon Power       | 8         | 0.12%   |
| PNY                 | 7         | 0.11%   |
| Avant               | 7         | 0.11%   |
| Unknown (0x5846)    | 6         | 0.09%   |
| GeIL                | 6         | 0.09%   |
| ASint Technology    | 6         | 0.09%   |
| Wilk                | 5         | 0.08%   |
| Unifosa             | 5         | 0.08%   |
| Infineon            | 5         | 0.08%   |
| Goldkey             | 5         | 0.08%   |
| 48spaces            | 5         | 0.08%   |
| Toshiba             | 4         | 0.06%   |
| Kllisre             | 4         | 0.06%   |
| Kingmax             | 4         | 0.06%   |
| Unknown (AB)        | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 3.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 143       | 2.09%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 69        | 1.01%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.92%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 61        | 0.89%   |
| Unknown                                                          | 56        | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 45        | 0.66%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.64%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 41        | 0.6%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 40        | 0.58%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 36        | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 34        | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 34        | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 0.48%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 32        | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 31        | 0.45%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 30        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 29        | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 29        | 0.42%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.42%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 29        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 28        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 26        | 0.38%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 26        | 0.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.38%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 26        | 0.38%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.37%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 24        | 0.35%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.34%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.34%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 20        | 0.29%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 20        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2422      | 42.62%  |
| DDR3         | 1858      | 32.69%  |
| DDR2         | 652       | 11.47%  |
| SDRAM        | 190       | 3.34%   |
| Unknown      | 177       | 3.11%   |
| LPDDR4       | 157       | 2.76%   |
| LPDDR3       | 120       | 2.11%   |
| DDR          | 58        | 1.02%   |
| DDR5         | 28        | 0.49%   |
| DRAM         | 15        | 0.26%   |
| LPDDR5       | 5         | 0.09%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3259      | 57.56%  |
| DIMM         | 2095      | 37%     |
| Row Of Chips | 210       | 3.71%   |
| Unknown      | 54        | 0.95%   |
| Chip         | 28        | 0.49%   |
| RIMM         | 8         | 0.14%   |
| FB-DIMM      | 8         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1978      | 32.28%  |
| 4096    | 1428      | 23.31%  |
| 2048    | 950       | 15.51%  |
| 16384   | 774       | 12.63%  |
| 1024    | 629       | 10.27%  |
| 32768   | 272       | 4.44%   |
| 512     | 64        | 1.04%   |
| 256     | 17        | 0.28%   |
| 65536   | 10        | 0.16%   |
| 8072    | 1         | 0.02%   |
| 1536    | 1         | 0.02%   |
| 384     | 1         | 0.02%   |
| 128     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1249      | 20.55%  |
| 3200    | 889       | 14.63%  |
| 2667    | 740       | 12.18%  |
| 800     | 488       | 8.03%   |
| 1333    | 416       | 6.84%   |
| 2400    | 375       | 6.17%   |
| 2133    | 266       | 4.38%   |
| 667     | 203       | 3.34%   |
| Unknown | 166       | 2.73%   |
| 1334    | 132       | 2.17%   |
| 3600    | 112       | 1.84%   |
| 1867    | 91        | 1.5%    |
| 2666    | 80        | 1.32%   |
| 1866    | 79        | 1.3%    |
| 1067    | 73        | 1.2%    |
| 1066    | 59        | 0.97%   |
| 4267    | 46        | 0.76%   |
| 3266    | 46        | 0.76%   |
| 2933    | 40        | 0.66%   |
| 4800    | 36        | 0.59%   |
| 3733    | 32        | 0.53%   |
| 3000    | 32        | 0.53%   |
| 3400    | 31        | 0.51%   |
| 1800    | 29        | 0.48%   |
| 533     | 28        | 0.46%   |
| 2866    | 26        | 0.43%   |
| 4199    | 23        | 0.38%   |
| 2048    | 22        | 0.36%   |
| 3466    | 18        | 0.3%    |
| 3800    | 17        | 0.28%   |
| 400     | 17        | 0.28%   |
| 333     | 13        | 0.21%   |
| 8400    | 11        | 0.18%   |
| 3933    | 11        | 0.18%   |
| 3533    | 11        | 0.18%   |
| 266     | 11        | 0.18%   |
| 3866    | 10        | 0.16%   |
| 3534    | 10        | 0.16%   |
| 975     | 10        | 0.16%   |
| 4266    | 9         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 44        | 32.84%  |
| Brother Industries     | 25        | 18.66%  |
| Canon                  | 19        | 14.18%  |
| Samsung Electronics    | 9         | 6.72%   |
| Xerox                  | 8         | 5.97%   |
| Seiko Epson            | 7         | 5.22%   |
| Dymo-CoStar            | 4         | 2.99%   |
| Prolific Technology    | 3         | 2.24%   |
| Zebra                  | 2         | 1.49%   |
| Pantum                 | 2         | 1.49%   |
| Lexmark International  | 2         | 1.49%   |
| STMicroelectronics     | 1         | 0.75%   |
| QinHeng Electronics    | 1         | 0.75%   |
| Printer                | 1         | 0.75%   |
| Panasonic (Matsushita) | 1         | 0.75%   |
| Oki Data               | 1         | 0.75%   |
| Kyocera                | 1         | 0.75%   |
| Konica Minolta         | 1         | 0.75%   |
| GODEX INTERNATIONAL    | 1         | 0.75%   |
| Apple                  | 1         | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 5.22%   |
| HP LaserJet 1200                                                      | 5         | 3.73%   |
| Samsung ML-1660 Series                                                | 3         | 2.24%   |
| Prolific PL2305 Parallel Port                                         | 3         | 2.24%   |
| HP LaserJet P1005                                                     | 3         | 2.24%   |
| HP LaserJet M101-M106                                                 | 3         | 2.24%   |
| HP LaserJet 1020                                                      | 3         | 2.24%   |
| Canon PIXMA MG3600 Series                                             | 3         | 2.24%   |
| HP LaserJet 1150                                                      | 2         | 1.49%   |
| HP ENVY 4520 series                                                   | 2         | 1.49%   |
| HP DeskJet 2600 series                                                | 2         | 1.49%   |
| HP DeskJet 2130 series                                                | 2         | 1.49%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.49%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.49%   |
| Canon MF4410                                                          | 2         | 1.49%   |
| Canon LiDE 400                                                        | 2         | 1.49%   |
| Canon LiDE 300                                                        | 2         | 1.49%   |
| Canon G3010 series                                                    | 2         | 1.49%   |
| Brother PT-9500PC                                                     | 2         | 1.49%   |
| Brother MFC-7460DN                                                    | 2         | 1.49%   |
| Brother HL-L2395DW series                                             | 2         | 1.49%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.75%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.75%   |
| Xerox Phaser 3250                                                     | 1         | 0.75%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.75%   |
| Seiko Epson XP-200 Series                                             | 1         | 0.75%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.75%   |
| Seiko Epson M105 Series                                               | 1         | 0.75%   |
| Seiko Epson L120 Series                                               | 1         | 0.75%   |
| Seiko Epson ET-2850 Series                                            | 1         | 0.75%   |
| Seiko Epson ET-2710 Series                                            | 1         | 0.75%   |
| Seiko Epson ET-2700 Series                                            | 1         | 0.75%   |
| Samsung SCX-4x26 Series                                               | 1         | 0.75%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.75%   |
| Samsung SCX-3200 Series                                               | 1         | 0.75%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 0.75%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 0.75%   |
| Samsung ML-1520 Laser Printer                                         | 1         | 0.75%   |
| QinHeng CH340S                                                        | 1         | 0.75%   |
| Printer Printer                                                       | 1         | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 19        | 59.38%  |
| Seiko Epson     | 7         | 21.88%  |
| Hewlett-Packard | 3         | 9.38%   |
| AGFA-Gevaert NV | 2         | 6.25%   |
| Mustek Systems  | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 4         | 12.5%   |
| Canon CanoScan LiDE 220                                       | 4         | 12.5%   |
| Canon CanoScan LiDE 210                                       | 2         | 6.25%   |
| Canon CanoScan LiDE 120                                       | 2         | 6.25%   |
| Canon CanoScan LiDE 110                                       | 2         | 6.25%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 6.25%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 3.13%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 3.13%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 3.13%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 3.13%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 3.13%   |
| Mustek Systems BearPaw 2400 CU Plus                           | 1         | 3.13%   |
| HP ScanJet Pro 2500 f1                                        | 1         | 3.13%   |
| HP ScanJet 3970c                                              | 1         | 3.13%   |
| HP Scanjet 300                                                | 1         | 3.13%   |
| Canon CanoScan LiDE 60                                        | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                        | 1         | 3.13%   |
| Canon CanoScan 8800F                                          | 1         | 3.13%   |
| Canon CanoScan 5600F                                          | 1         | 3.13%   |
| Canon CanoScan 4400F                                          | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 714       | 22.57%  |
| IMC Networks                           | 283       | 8.95%   |
| Bison Electronics                      | 267       | 8.44%   |
| Quanta                                 | 238       | 7.52%   |
| Microdia                               | 222       | 7.02%   |
| Realtek Semiconductor                  | 194       | 6.13%   |
| Logitech                               | 182       | 5.75%   |
| Sunplus Innovation Technology          | 136       | 4.3%    |
| Acer                                   | 117       | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 94        | 2.97%   |
| Apple                                  | 92        | 2.91%   |
| Suyin                                  | 76        | 2.4%    |
| Lite-On Technology                     | 69        | 2.18%   |
| Syntek                                 | 59        | 1.87%   |
| Luxvisions Innotech Limited            | 55        | 1.74%   |
| Silicon Motion                         | 30        | 0.95%   |
| Alcor Micro                            | 26        | 0.82%   |
| Lenovo                                 | 23        | 0.73%   |
| Generalplus Technology                 | 19        | 0.6%    |
| Z-Star Microelectronics                | 15        | 0.47%   |
| Samsung Electronics                    | 15        | 0.47%   |
| Microsoft                              | 15        | 0.47%   |
| Sonix Technology                       | 14        | 0.44%   |
| Ricoh                                  | 12        | 0.38%   |
| Creative Technology                    | 12        | 0.38%   |
| ARC International                      | 10        | 0.32%   |
| Primax Electronics                     | 9         | 0.28%   |
| Jieli Technology                       | 9         | 0.28%   |
| Genesys Logic                          | 9         | 0.28%   |
| KYE Systems (Mouse Systems)            | 8         | 0.25%   |
| Importek                               | 8         | 0.25%   |
| GEMBIRD                                | 8         | 0.25%   |
| SunplusIT                              | 7         | 0.22%   |
| ALi                                    | 6         | 0.19%   |
| MacroSilicon                           | 5         | 0.16%   |
| Intel                                  | 5         | 0.16%   |
| icSpring                               | 5         | 0.16%   |
| Y Media                                | 4         | 0.13%   |
| OmniVision Technologies                | 4         | 0.13%   |
| Google                                 | 4         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 217       | 6.74%   |
| Bison Integrated Camera                             | 123       | 3.82%   |
| Microdia Integrated_Webcam_HD                       | 104       | 3.23%   |
| IMC Networks Integrated Camera                      | 87        | 2.7%    |
| Bison Integrated 5M Camera                          | 73        | 2.27%   |
| Realtek Integrated_Webcam_HD                        | 71        | 2.21%   |
| Quanta Chromebook HD Camera                         | 69        | 2.14%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 66        | 2.05%   |
| Logitech Webcam C270                                | 54        | 1.68%   |
| Sunplus Integrated_Webcam_HD                        | 49        | 1.52%   |
| Chicony HD WebCam                                   | 49        | 1.52%   |
| Acer BisonCam, NB Pro                               | 48        | 1.49%   |
| Chicony Integrated 5M Camera                        | 43        | 1.34%   |
| Chicony USB2.0 HD UVC WebCam                        | 36        | 1.12%   |
| Chicony HP HD Camera                                | 35        | 1.09%   |
| Apple Built-in iSight                               | 32        | 0.99%   |
| Quanta HP TrueVision HD Camera                      | 31        | 0.96%   |
| Syntek Integrated Camera                            | 30        | 0.93%   |
| Quanta HD User Facing                               | 30        | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 30        | 0.93%   |
| Logitech HD Pro Webcam C920                         | 28        | 0.87%   |
| Acer Integrated Camera                              | 26        | 0.81%   |
| Quanta VGA WebCam                                   | 24        | 0.75%   |
| Lite-On Integrated Camera                           | 24        | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 24        | 0.75%   |
| Microdia Integrated Webcam                          | 22        | 0.68%   |
| Bison SunplusIT Integrated Camera                   | 22        | 0.68%   |
| Quanta HP HD Camera                                 | 21        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.65%   |
| Lite-On HP HD Camera                                | 21        | 0.65%   |
| Apple FaceTime HD Camera (Built-in)                 | 20        | 0.62%   |
| Realtek USB Camera                                  | 18        | 0.56%   |
| Microdia USB 2.0 Camera                             | 18        | 0.56%   |
| Chicony Integrated Camera (1280x720@30)             | 18        | 0.56%   |
| Sunplus HD WebCam                                   | 17        | 0.53%   |
| Chicony HP Truevision HD camera                     | 17        | 0.53%   |
| Chicony HD User Facing                              | 17        | 0.53%   |
| Luxvisions Innotech Limited HP HD Camera            | 16        | 0.5%    |
| Chicony HP Webcam                                   | 16        | 0.5%    |
| Bison HD Webcam                                     | 16        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 284       | 42.97%  |
| Validity Sensors                   | 188       | 28.44%  |
| Shenzhen Goodix Technology         | 73        | 11.04%  |
| Upek                               | 30        | 4.54%   |
| AuthenTec                          | 28        | 4.24%   |
| Elan Microelectronics              | 27        | 4.08%   |
| LighTuning Technology              | 19        | 2.87%   |
| STMicroelectronics                 | 9         | 1.36%   |
| Samsung Electronics                | 1         | 0.15%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.15%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 179       | 27.08%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 6.35%   |
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 6.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 4.99%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 4.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 3.78%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 3.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 2.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 2.57%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 1.97%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 1.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 1.51%   |
| Elan ELAN:Fingerprint                                                      | 10        | 1.51%   |
| Validity Sensors VFS491                                                    | 9         | 1.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.36%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.21%   |
| Synaptics UWP WBDI                                                         | 8         | 1.21%   |
| Synaptics  WBDI                                                            | 8         | 1.21%   |
| AuthenTec AES2810                                                          | 8         | 1.21%   |
| Synaptics WBDI                                                             | 7         | 1.06%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.06%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 0.91%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.91%   |
| Elan WBF Fingerprint Sensor                                                | 5         | 0.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.61%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.45%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 111       | 36.88%  |
| Alcor Micro               | 97        | 32.23%  |
| Upek                      | 24        | 7.97%   |
| O2 Micro                  | 22        | 7.31%   |
| Lenovo                    | 17        | 5.65%   |
| Gemalto (was Gemplus)     | 6         | 1.99%   |
| SCM Microsystems          | 5         | 1.66%   |
| Yubico.com                | 3         | 1%      |
| Advanced Card Systems     | 3         | 1%      |
| Reiner SCT Kartensysteme  | 2         | 0.66%   |
| Clay Logic                | 2         | 0.66%   |
| Cherry                    | 2         | 0.66%   |
| Aladdin Knowledge Systems | 2         | 0.66%   |
| Realtek Semiconductor     | 1         | 0.33%   |
| OmniKey                   | 1         | 0.33%   |
| Feitian Technologies      | 1         | 0.33%   |
| Chicony Electronics       | 1         | 0.33%   |
| C3PO                      | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 95        | 31.56%  |
| Broadcom 58200                                                               | 37        | 12.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 9.63%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.97%   |
| Broadcom 5880                                                                | 23        | 7.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 6.64%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.98%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.66%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.66%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.66%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.66%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.66%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.66%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.66%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.66%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.66%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.33%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.33%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.33%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.33%   |
| OmniKey CardMan 4321                                                         | 1         | 0.33%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.33%   |
| Feitian Technologies SCR301                                                  | 1         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.33%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.33%   |
| C3PO LTC31v2                                                                 | 1         | 0.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3858      | 57.27%  |
| 1     | 2322      | 34.47%  |
| 2     | 438       | 6.5%    |
| 3     | 95        | 1.41%   |
| 4     | 17        | 0.25%   |
| 5     | 5         | 0.07%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1502      | 44.16%  |
| Fingerprint reader       | 658       | 19.35%  |
| Net/wireless             | 297       | 8.73%   |
| Chipcard                 | 274       | 8.06%   |
| Multimedia controller    | 237       | 6.97%   |
| Communication controller | 128       | 3.76%   |
| Unassigned class         | 84        | 2.47%   |
| Bluetooth                | 49        | 1.44%   |
| Sound                    | 32        | 0.94%   |
| Camera                   | 31        | 0.91%   |
| Card reader              | 28        | 0.82%   |
| Storage                  | 24        | 0.71%   |
| Net/ethernet             | 16        | 0.47%   |
| Network                  | 9         | 0.26%   |
| Modem                    | 8         | 0.24%   |
| Storage/raid             | 7         | 0.21%   |
| Tv card                  | 5         | 0.15%   |
| Flash memory             | 4         | 0.12%   |
| Dvb card                 | 4         | 0.12%   |
| Firewire controller      | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

