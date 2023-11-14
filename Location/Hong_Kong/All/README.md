Linux in Hong Kong - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hong_Kong/Desktop/README.md) and [notebooks](/Location/Hong_Kong/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 636

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [f90d872043](https://linux-hardware.org/?probe=f90d872043) | Nov 05, 2023 |
| Intel         | X79 V1.0                    | Desktop     | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [b2c5bb3ed9](https://linux-hardware.org/?probe=b2c5bb3ed9) | Nov 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| Lenovo        | G770 20089                  | Notebook    | [8428ba05f5](https://linux-hardware.org/?probe=8428ba05f5) | Oct 28, 2023 |
| Orange Pi     | 5 Plus                      | Soc         | [45f5ee6292](https://linux-hardware.org/?probe=45f5ee6292) | Oct 28, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [6e87d140be](https://linux-hardware.org/?probe=6e87d140be) | Oct 25, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a3e8e996e](https://linux-hardware.org/?probe=6a3e8e996e) | Oct 20, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [23f0d88b97](https://linux-hardware.org/?probe=23f0d88b97) | Oct 20, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [422e2e497a](https://linux-hardware.org/?probe=422e2e497a) | Oct 15, 2023 |
| Lenovo        | G770 20089                  | Notebook    | [b8d4374337](https://linux-hardware.org/?probe=b8d4374337) | Oct 14, 2023 |
| Lenovo        | G770 20089                  | Notebook    | [eefc449148](https://linux-hardware.org/?probe=eefc449148) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| ASUSTek       | ROG Strix G732LWS_G732LW... | Notebook    | [cc1f103b33](https://linux-hardware.org/?probe=cc1f103b33) | Oct 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [ae56dcb316](https://linux-hardware.org/?probe=ae56dcb316) | Oct 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [3f4a876b18](https://linux-hardware.org/?probe=3f4a876b18) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [6f431b83bd](https://linux-hardware.org/?probe=6f431b83bd) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [e524ccbf1b](https://linux-hardware.org/?probe=e524ccbf1b) | Oct 07, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a716f2a182](https://linux-hardware.org/?probe=a716f2a182) | Oct 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [54eaf1a92d](https://linux-hardware.org/?probe=54eaf1a92d) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [f4f3555c2b](https://linux-hardware.org/?probe=f4f3555c2b) | Oct 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [b3a1f027db](https://linux-hardware.org/?probe=b3a1f027db) | Oct 03, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [beaf871c4c](https://linux-hardware.org/?probe=beaf871c4c) | Oct 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [9b86a89bf4](https://linux-hardware.org/?probe=9b86a89bf4) | Sep 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [539887ee9a](https://linux-hardware.org/?probe=539887ee9a) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [08989d4bba](https://linux-hardware.org/?probe=08989d4bba) | Sep 21, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6d0e6a863d](https://linux-hardware.org/?probe=6d0e6a863d) | Sep 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [07d34fd9b5](https://linux-hardware.org/?probe=07d34fd9b5) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | Desktop     | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [5e399c56a0](https://linux-hardware.org/?probe=5e399c56a0) | Sep 16, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [2e74e88e2f](https://linux-hardware.org/?probe=2e74e88e2f) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [f253067fa5](https://linux-hardware.org/?probe=f253067fa5) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [baf0966633](https://linux-hardware.org/?probe=baf0966633) | Aug 29, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | Notebook    | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Dell          | 0VNM11 A00                  | Desktop     | [e448e177d3](https://linux-hardware.org/?probe=e448e177d3) | Aug 21, 2023 |
| FriendlyEl... | NanoPi R2S                  | Soc         | [e8ae8c047f](https://linux-hardware.org/?probe=e8ae8c047f) | Aug 20, 2023 |
| FriendlyEl... | NanoPi R2S                  | Soc         | [992f8472ce](https://linux-hardware.org/?probe=992f8472ce) | Aug 20, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [eba93bad6a](https://linux-hardware.org/?probe=eba93bad6a) | Aug 17, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [2c60ec2f95](https://linux-hardware.org/?probe=2c60ec2f95) | Aug 17, 2023 |
| Unknown       | Unknown                     | Tablet      | [a087e3a82c](https://linux-hardware.org/?probe=a087e3a82c) | Aug 16, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [b4a64727f4](https://linux-hardware.org/?probe=b4a64727f4) | Aug 14, 2023 |
| Dell          | 0VNM11 A00                  | Desktop     | [71cd1ddbf5](https://linux-hardware.org/?probe=71cd1ddbf5) | Aug 13, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [cf233e5568](https://linux-hardware.org/?probe=cf233e5568) | Aug 13, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Fujitsu       | UH-X                        | Notebook    | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [a089f6ff62](https://linux-hardware.org/?probe=a089f6ff62) | Aug 05, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | Notebook    | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [dd11fc89fe](https://linux-hardware.org/?probe=dd11fc89fe) | Aug 02, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | Notebook    | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [e14cb2c24e](https://linux-hardware.org/?probe=e14cb2c24e) | Jul 25, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [bddace9995](https://linux-hardware.org/?probe=bddace9995) | Jul 25, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [edfa5090fc](https://linux-hardware.org/?probe=edfa5090fc) | Jul 21, 2023 |
| Dell          | 0WXD1Y A01                  | Server      | [477343a949](https://linux-hardware.org/?probe=477343a949) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | Notebook    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [c060069870](https://linux-hardware.org/?probe=c060069870) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [8a5ddbbafc](https://linux-hardware.org/?probe=8a5ddbbafc) | Jul 05, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| Google        | Nami                        | Notebook    | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [8a9a60ca4d](https://linux-hardware.org/?probe=8a9a60ca4d) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [eaca61c801](https://linux-hardware.org/?probe=eaca61c801) | Jun 19, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | Notebook    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c536181b6a](https://linux-hardware.org/?probe=c536181b6a) | Jun 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a67c1e25b2](https://linux-hardware.org/?probe=a67c1e25b2) | Jun 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [604f40e700](https://linux-hardware.org/?probe=604f40e700) | Jun 09, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d001c4cf1c](https://linux-hardware.org/?probe=d001c4cf1c) | Jun 09, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [25c1d47331](https://linux-hardware.org/?probe=25c1d47331) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| HP            | 83E2                        | Desktop     | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| GPD           | G1619-04                    | Notebook    | [49b9e4edd3](https://linux-hardware.org/?probe=49b9e4edd3) | May 28, 2023 |
| GPD           | G1619-04                    | Notebook    | [caa6b5459d](https://linux-hardware.org/?probe=caa6b5459d) | May 28, 2023 |
| HP            | 1632                        | Desktop     | [ed47689eec](https://linux-hardware.org/?probe=ed47689eec) | May 22, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [2bfe226026](https://linux-hardware.org/?probe=2bfe226026) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c2ccca0208](https://linux-hardware.org/?probe=c2ccca0208) | May 16, 2023 |
| Dell          | 0WXD1Y A01                  | Server      | [9d5a4b579e](https://linux-hardware.org/?probe=9d5a4b579e) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [df455b6f4b](https://linux-hardware.org/?probe=df455b6f4b) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Samsung       | 950QED                      | Convertible | [0135cc3aa4](https://linux-hardware.org/?probe=0135cc3aa4) | Apr 27, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VV_GZ3... | Tablet      | [679dc6cbc8](https://linux-hardware.org/?probe=679dc6cbc8) | Apr 25, 2023 |
| Dell          | 0N0992 A01                  | Desktop     | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [65cce76dc9](https://linux-hardware.org/?probe=65cce76dc9) | Apr 20, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [9feb6e0d59](https://linux-hardware.org/?probe=9feb6e0d59) | Apr 16, 2023 |
| Lenovo        | ThinkPad X201 33233QM       | Notebook    | [f84da542f6](https://linux-hardware.org/?probe=f84da542f6) | Apr 15, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0e074bebcf](https://linux-hardware.org/?probe=0e074bebcf) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [b4c155dc99](https://linux-hardware.org/?probe=b4c155dc99) | Apr 07, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| METAPHYUNI    | MetamechBook                | Notebook    | [7e4076cb61](https://linux-hardware.org/?probe=7e4076cb61) | Mar 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [79e1666c41](https://linux-hardware.org/?probe=79e1666c41) | Mar 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | Desktop     | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Intel         | W2600CR G21602-308          | Server      | [96cda648c2](https://linux-hardware.org/?probe=96cda648c2) | Mar 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | 06WXJT A02                  | Server      | [a4f3535e84](https://linux-hardware.org/?probe=a4f3535e84) | Mar 03, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [fc803f9205](https://linux-hardware.org/?probe=fc803f9205) | Feb 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [81cfc27f9e](https://linux-hardware.org/?probe=81cfc27f9e) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [ee4e2b3cde](https://linux-hardware.org/?probe=ee4e2b3cde) | Feb 19, 2023 |
| AOKZOE        | A1 AR07                     | Tablet      | [fe54acc90f](https://linux-hardware.org/?probe=fe54acc90f) | Feb 18, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [58bcb8bf04](https://linux-hardware.org/?probe=58bcb8bf04) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | Y430P 20435                 | Notebook    | [da3030daae](https://linux-hardware.org/?probe=da3030daae) | Feb 16, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | Notebook    | [6a223f0a71](https://linux-hardware.org/?probe=6a223f0a71) | Feb 15, 2023 |
| ASUSTek       | X705UA                      | Notebook    | [cc59e95283](https://linux-hardware.org/?probe=cc59e95283) | Feb 07, 2023 |
| ASUSTek       | X705UA                      | Notebook    | [25188e7cfa](https://linux-hardware.org/?probe=25188e7cfa) | Feb 07, 2023 |
| Timi          | TM1613                      | Notebook    | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [6d6a8e4be4](https://linux-hardware.org/?probe=6d6a8e4be4) | Jan 24, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Acer          | Swift SF314-57G             | Notebook    | [ae9de10584](https://linux-hardware.org/?probe=ae9de10584) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7cb08d37fb](https://linux-hardware.org/?probe=7cb08d37fb) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [dc81fac0f7](https://linux-hardware.org/?probe=dc81fac0f7) | Jan 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [641b77c3da](https://linux-hardware.org/?probe=641b77c3da) | Dec 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| GPD           | P2 MAX                      | Notebook    | [63c199f475](https://linux-hardware.org/?probe=63c199f475) | Dec 08, 2022 |
| Lenovo        | ThinkSystem SR358FV2 Res... | Server      | [3702b80721](https://linux-hardware.org/?probe=3702b80721) | Dec 07, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Dell          | Latitude 7390               | Notebook    | [7214cac96d](https://linux-hardware.org/?probe=7214cac96d) | Nov 30, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [7b0cf2fa20](https://linux-hardware.org/?probe=7b0cf2fa20) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20A... | Convertible | [341287988f](https://linux-hardware.org/?probe=341287988f) | Nov 17, 2022 |
| GPD           | G1619-04                    | Notebook    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [468f8df590](https://linux-hardware.org/?probe=468f8df590) | Nov 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| ASRock        | H470M-STX                   | Desktop     | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [a9c49ccd5d](https://linux-hardware.org/?probe=a9c49ccd5d) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | Notebook    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| HP            | 8956 010                    | Mini pc     | [d959cdb332](https://linux-hardware.org/?probe=d959cdb332) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8ebbbf93e4](https://linux-hardware.org/?probe=8ebbbf93e4) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| HP            | ZHAN 66 Pro A 14 inch G5... | Notebook    | [c5587dbec5](https://linux-hardware.org/?probe=c5587dbec5) | Oct 04, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [2163cddbe4](https://linux-hardware.org/?probe=2163cddbe4) | Oct 04, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Dell          | Latitude E5250              | Notebook    | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| ASRock        | Z490 PG Velocita            | Desktop     | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Huanan        | X99-TF                      | Desktop     | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| HUAWEI        | PGU-WBY0                    | Soc         | [3f3d475864](https://linux-hardware.org/?probe=3f3d475864) | Sep 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [5160feeaf2](https://linux-hardware.org/?probe=5160feeaf2) | Sep 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [876e87c7b6](https://linux-hardware.org/?probe=876e87c7b6) | Sep 13, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [d0ddfb5815](https://linux-hardware.org/?probe=d0ddfb5815) | Sep 07, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [302c3f11ec](https://linux-hardware.org/?probe=302c3f11ec) | Aug 29, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [9a83e7ee58](https://linux-hardware.org/?probe=9a83e7ee58) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [638f08fc43](https://linux-hardware.org/?probe=638f08fc43) | Aug 27, 2022 |
| Dell          | 0427JK A00                  | Desktop     | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | Notebook    | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | Notebook    | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [353168b909](https://linux-hardware.org/?probe=353168b909) | Jul 18, 2022 |
| Huanan        | X99-TF                      | Desktop     | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| IBM           | 260921H                     | Notebook    | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | Notebook    | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e9adf47b7a](https://linux-hardware.org/?probe=e9adf47b7a) | Jul 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Soyo          | SY-A68M FS V2.0             | Desktop     | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Huanan        | X99-TF                      | Desktop     | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| Huanan        | X99-TF                      | Desktop     | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | Desktop     | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [99e0958898](https://linux-hardware.org/?probe=99e0958898) | May 01, 2022 |
| Dell          | Precision 7520              | Notebook    | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| MSI           | H87I                        | Desktop     | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a3aa6e30b9](https://linux-hardware.org/?probe=a3aa6e30b9) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [d359794b2f](https://linux-hardware.org/?probe=d359794b2f) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7ea786c89b](https://linux-hardware.org/?probe=7ea786c89b) | Apr 18, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0ac1f4daf9](https://linux-hardware.org/?probe=0ac1f4daf9) | Apr 12, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | VM62                        | Desktop     | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | 0Y3R3K A03                  | Desktop     | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e7fb180535](https://linux-hardware.org/?probe=e7fb180535) | Mar 16, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6c00869d7b](https://linux-hardware.org/?probe=6c00869d7b) | Feb 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [2a66f4b578](https://linux-hardware.org/?probe=2a66f4b578) | Jan 24, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | Desktop     | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | Desktop     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | Notebook    | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Intel X79                   | Desktop     | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Unknown       | Intel X79                   | Desktop     | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | Desktop     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Jumper        | EZbook                      | Notebook    | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [c7fc01bd49](https://linux-hardware.org/?probe=c7fc01bd49) | Oct 27, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aee062d6e5](https://linux-hardware.org/?probe=aee062d6e5) | Oct 04, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | Notebook    | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| GPD           | G1618-03                    | Notebook    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | Notebook    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Dell          | Precision 7550              | Notebook    | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | Notebook    | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Lenovo        | IdeaCentre B305 10052       | All in one  | [8399296d51](https://linux-hardware.org/?probe=8399296d51) | Jun 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| HP            | 18E7                        | Desktop     | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| ASUSTek       | VM62                        | Desktop     | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| Fujitsu       | UH-X                        | Notebook    | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | Desktop     | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Nvidia        | Tegra                       | Soc         | [54592ec1a2](https://linux-hardware.org/?probe=54592ec1a2) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| HP            | 1632                        | Desktop     | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [280785b873](https://linux-hardware.org/?probe=280785b873) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [20d78f0b3a](https://linux-hardware.org/?probe=20d78f0b3a) | Mar 22, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | Notebook    | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| ASUSTek       | VM45                        | Desktop     | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | Desktop     | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | Notebook    | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | Notebook    | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1d0000672d](https://linux-hardware.org/?probe=1d0000672d) | Jan 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b8f5d6f1e4](https://linux-hardware.org/?probe=b8f5d6f1e4) | Jan 16, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Intel         | NUC6CAYB J23203-406         | Mini pc     | [038dce10fa](https://linux-hardware.org/?probe=038dce10fa) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | Notebook    | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | Notebook    | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69fb29494b](https://linux-hardware.org/?probe=69fb29494b) | Nov 07, 2020 |
| HP            | 2000                        | Notebook    | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [fbba9f6a3b](https://linux-hardware.org/?probe=fbba9f6a3b) | Nov 02, 2020 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [e970e25954](https://linux-hardware.org/?probe=e970e25954) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| HP            | 2140                        | Notebook    | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | Notebook    | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| Samsung       | 930XBE                      | Notebook    | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| HP            | 802E                        | Desktop     | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | Desktop     | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Dell          | Inspiron 5580               | Notebook    | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | Desktop     | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | Notebook    | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | Desktop     | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Fujitsu       | LIFEBOOK AH556              | Notebook    | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Biostar       | H110MHC                     | Desktop     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | Desktop     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | Notebook    | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | Desktop     | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | Notebook    | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| Google        | Eve                         | Notebook    | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | Desktop     | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| MSI           | GS73VR 7RG                  | Notebook    | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | Notebook    | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| CompuLab      | Airtop                      | Mini pc     | [ff3ce414e4](https://linux-hardware.org/?probe=ff3ce414e4) | Oct 16, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Unknown       | Unknown                     | Notebook    | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | Notebook    | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | Notebook    | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | Desktop     | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | Notebook    | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | Notebook    | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | Notebook    | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | Notebook    | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| ASRock        | Z270 Killer SLI             | Desktop     | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| HP            | ProBook 4540s               | Notebook    | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | Notebook    | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hong_Kong/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 53        | 11.65%  |
| Ubuntu 22.04        | 44        | 9.67%   |
| Arch Rolling        | 25        | 5.49%   |
| Ubuntu 18.04        | 23        | 5.05%   |
| Debian 11           | 14        | 3.08%   |
| OpenMandriva 4.2    | 13        | 2.86%   |
| Pop!_OS 22.04       | 12        | 2.64%   |
| Arch                | 11        | 2.42%   |
| Fedora 37           | 10        | 2.2%    |
| ArcoLinux Rolling   | 10        | 2.2%    |
| antiX 21            | 10        | 2.2%    |
| Ubuntu 19.10        | 8         | 1.76%   |
| OpenMandriva 4.3    | 7         | 1.54%   |
| KDE neon 20.04      | 7         | 1.54%   |
| Debian 12           | 7         | 1.54%   |
| Ubuntu 20.10        | 6         | 1.32%   |
| Gentoo 2.7          | 6         | 1.32%   |
| Fedora 35           | 6         | 1.32%   |
| Fedora 32           | 6         | 1.32%   |
| EndeavourOS Rolling | 6         | 1.32%   |
| Ubuntu 23.04        | 5         | 1.1%    |
| OpenMandriva 23.03  | 5         | 1.1%    |
| Fedora 36           | 5         | 1.1%    |
| Ubuntu 22.10        | 4         | 0.88%   |
| Ubuntu 21.10        | 4         | 0.88%   |
| Ubuntu 21.04        | 4         | 0.88%   |
| Ubuntu 19.04        | 4         | 0.88%   |
| Pop!_OS 20.10       | 4         | 0.88%   |
| OpenMandriva 23.01  | 4         | 0.88%   |
| Linux Mint 20       | 4         | 0.88%   |
| Fedora 38           | 4         | 0.88%   |
| Fedora 33           | 4         | 0.88%   |
| Ubuntu 16.04        | 3         | 0.66%   |
| OpenMandriva 4.50   | 3         | 0.66%   |
| Linux Mint 20.3     | 3         | 0.66%   |
| Kylin V10           | 3         | 0.66%   |
| Gentoo 2.8          | 3         | 0.66%   |
| Elementary 5.1.7    | 3         | 0.66%   |
| Chrome OS           | 3         | 0.66%   |
| Zorin 15            | 2         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 149       | 34.17%  |
| Fedora        | 38        | 8.72%   |
| Arch          | 36        | 8.26%   |
| OpenMandriva  | 32        | 7.34%   |
| Debian        | 22        | 5.05%   |
| Pop!_OS       | 21        | 4.82%   |
| Manjaro       | 11        | 2.52%   |
| Linux Mint    | 11        | 2.52%   |
| ArcoLinux     | 10        | 2.29%   |
| antiX         | 10        | 2.29%   |
| Gentoo        | 9         | 2.06%   |
| SteamOS       | 7         | 1.61%   |
| KDE neon      | 7         | 1.61%   |
| EndeavourOS   | 7         | 1.61%   |
| Clear Linux   | 6         | 1.38%   |
| Kubuntu       | 5         | 1.15%   |
| Elementary    | 5         | 1.15%   |
| Zorin         | 3         | 0.69%   |
| Ubuntu Unity  | 3         | 0.69%   |
| Ubuntu MATE   | 3         | 0.69%   |
| Slackware     | 3         | 0.69%   |
| ROSA          | 3         | 0.69%   |
| openSUSE      | 3         | 0.69%   |
| Kylin         | 3         | 0.69%   |
| Kali          | 3         | 0.69%   |
| Chrome OS     | 3         | 0.69%   |
| CentOS        | 3         | 0.69%   |
| Xubuntu       | 2         | 0.46%   |
| PostmarketOS  | 2         | 0.46%   |
| Parrot        | 2         | 0.46%   |
| Ultramarine   | 1         | 0.23%   |
| UbuntuDDE     | 1         | 0.23%   |
| Ubuntu Budgie | 1         | 0.23%   |
| Rocky Linux   | 1         | 0.23%   |
| Raspbian      | 1         | 0.23%   |
| PCLinuxOS     | 1         | 0.23%   |
| Oracle Linux  | 1         | 0.23%   |
| Nobara        | 1         | 0.23%   |
| NixOS         | 1         | 0.23%   |
| Lubuntu       | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002   | 12        | 2.41%   |
| 5.4.0-42-generic           | 9         | 1.81%   |
| 4.9.0-279-antix.1-486-smp  | 9         | 1.81%   |
| 5.16.7-desktop-1omv4003    | 7         | 1.41%   |
| 5.15.0-46-generic          | 6         | 1.2%    |
| 6.2.6-desktop-1omv2390     | 5         | 1%      |
| 6.2.0-20-generic           | 4         | 0.8%    |
| 6.1.1-desktop-1omv2290     | 4         | 0.8%    |
| 5.15.0-58-generic          | 4         | 0.8%    |
| 5.15.0-52-generic          | 4         | 0.8%    |
| 5.13.0-39-generic          | 4         | 0.8%    |
| 5.13.0-35-generic          | 4         | 0.8%    |
| 6.3.6-arch1-1              | 3         | 0.6%    |
| 6.2.0-33-generic           | 3         | 0.6%    |
| 6.2.0-26-generic           | 3         | 0.6%    |
| 5.8.0-7630-generic         | 3         | 0.6%    |
| 5.8.0-55-generic           | 3         | 0.6%    |
| 5.8.0-43-generic           | 3         | 0.6%    |
| 5.4.0-48-generic           | 3         | 0.6%    |
| 5.4.0-33-generic           | 3         | 0.6%    |
| 5.4.0-28-generic           | 3         | 0.6%    |
| 5.4.0-26-generic           | 3         | 0.6%    |
| 5.3.0-46-generic           | 3         | 0.6%    |
| 5.19.0-32-generic          | 3         | 0.6%    |
| 5.15.0-47-generic          | 3         | 0.6%    |
| 5.11.0-37-generic          | 3         | 0.6%    |
| 4.19.49+                   | 3         | 0.6%    |
| 6.5.5-arch1-1              | 2         | 0.4%    |
| 6.2.8-200.fc37.x86_64      | 2         | 0.4%    |
| 6.2.0-34-generic           | 2         | 0.4%    |
| 6.1.39-1-lts               | 2         | 0.4%    |
| 6.1.21-valve1-3-neptune-61 | 2         | 0.4%    |
| 6.1.1-arch1-1              | 2         | 0.4%    |
| 6.1.0-9-amd64              | 2         | 0.4%    |
| 6.1.0-11-amd64             | 2         | 0.4%    |
| 6.0.12-300.fc37.x86_64     | 2         | 0.4%    |
| 5.9.2-arch1-1              | 2         | 0.4%    |
| 5.5.0-1parrot1-amd64       | 2         | 0.4%    |
| 5.4.0-58-generic           | 2         | 0.4%    |
| 5.4.0-56-generic           | 2         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 8.67%   |
| 5.15.0  | 33        | 6.98%   |
| 5.13.0  | 23        | 4.86%   |
| 5.8.0   | 22        | 4.65%   |
| 5.19.0  | 22        | 4.65%   |
| 6.2.0   | 19        | 4.02%   |
| 5.11.0  | 15        | 3.17%   |
| 4.15.0  | 14        | 2.96%   |
| 5.3.0   | 12        | 2.54%   |
| 5.10.14 | 12        | 2.54%   |
| 5.0.0   | 10        | 2.11%   |
| 4.9.0   | 10        | 2.11%   |
| 5.10.0  | 9         | 1.9%    |
| 6.2.6   | 7         | 1.48%   |
| 6.1.1   | 7         | 1.48%   |
| 6.1.0   | 7         | 1.48%   |
| 5.16.7  | 7         | 1.48%   |
| 6.0.0   | 5         | 1.06%   |
| 4.18.0  | 5         | 1.06%   |
| 5.17.5  | 4         | 0.85%   |
| 6.5.6   | 3         | 0.63%   |
| 6.4.2   | 3         | 0.63%   |
| 6.3.6   | 3         | 0.63%   |
| 6.2.8   | 3         | 0.63%   |
| 6.0.12  | 3         | 0.63%   |
| 5.14.0  | 3         | 0.63%   |
| 4.19.49 | 3         | 0.63%   |
| 6.5.5   | 2         | 0.42%   |
| 6.5.3   | 2         | 0.42%   |
| 6.4.7   | 2         | 0.42%   |
| 6.4.3   | 2         | 0.42%   |
| 6.4.0   | 2         | 0.42%   |
| 6.3.8   | 2         | 0.42%   |
| 6.2.9   | 2         | 0.42%   |
| 6.1.39  | 2         | 0.42%   |
| 6.1.21  | 2         | 0.42%   |
| 6.1.14  | 2         | 0.42%   |
| 6.1.11  | 2         | 0.42%   |
| 5.9.2   | 2         | 0.42%   |
| 5.5.0   | 2         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 46        | 9.96%   |
| 5.4     | 41        | 8.87%   |
| 6.2     | 33        | 7.14%   |
| 5.10    | 33        | 7.14%   |
| 5.19    | 32        | 6.93%   |
| 6.1     | 28        | 6.06%   |
| 5.8     | 28        | 6.06%   |
| 5.13    | 27        | 5.84%   |
| 5.11    | 22        | 4.76%   |
| 5.3     | 15        | 3.25%   |
| 5.16    | 14        | 3.03%   |
| 4.9     | 14        | 3.03%   |
| 4.15    | 14        | 3.03%   |
| 5.17    | 13        | 2.81%   |
| 6.4     | 12        | 2.6%    |
| 6.0     | 11        | 2.38%   |
| 5.9     | 10        | 2.16%   |
| 5.0     | 10        | 2.16%   |
| 5.14    | 9         | 1.95%   |
| 6.5     | 8         | 1.73%   |
| 6.3     | 7         | 1.52%   |
| 5.18    | 7         | 1.52%   |
| 5.7     | 6         | 1.3%    |
| 4.18    | 6         | 1.3%    |
| 5.6     | 3         | 0.65%   |
| 5.5     | 3         | 0.65%   |
| 5.12    | 3         | 0.65%   |
| 4.19    | 3         | 0.65%   |
| 4.4     | 2         | 0.43%   |
| 4.17    | 1         | 0.22%   |
| 3.10    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 397       | 93.85%  |
| i686    | 13        | 3.07%   |
| aarch64 | 11        | 2.6%    |
| i586    | 1         | 0.24%   |
| armv7l  | 1         | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 209       | 47.61%  |
| KDE5          | 92        | 20.96%  |
| Unknown       | 63        | 14.35%  |
| XFCE          | 18        | 4.1%    |
| KDE           | 10        | 2.28%   |
| X-Cinnamon    | 8         | 1.82%   |
| i3            | 6         | 1.37%   |
| MATE          | 5         | 1.14%   |
| Pantheon      | 4         | 0.91%   |
| Deepin        | 3         | 0.68%   |
| Unity         | 2         | 0.46%   |
| sway          | 2         | 0.46%   |
| openbox       | 2         | 0.46%   |
| LXQt          | 2         | 0.46%   |
| LXDE          | 2         | 0.46%   |
| Hyprland      | 2         | 0.46%   |
| dwm           | 2         | 0.46%   |
| KDE4          | 1         | 0.23%   |
| icewm         | 1         | 0.23%   |
| GNOME Classic | 1         | 0.23%   |
| fvwm          | 1         | 0.23%   |
| Cinnamon      | 1         | 0.23%   |
| Budgie        | 1         | 0.23%   |
| awesome       | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 306       | 70.02%  |
| Wayland | 92        | 21.05%  |
| Unknown | 21        | 4.81%   |
| Tty     | 18        | 4.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 175       | 40.05%  |
| SDDM    | 84        | 19.22%  |
| GDM3    | 73        | 16.7%   |
| GDM     | 61        | 13.96%  |
| LightDM | 31        | 7.09%   |
| TDM     | 7         | 1.6%    |
| Ly      | 2         | 0.46%   |
| XDM     | 1         | 0.23%   |
| LXDM    | 1         | 0.23%   |
| KDM     | 1         | 0.23%   |
| GREETD  | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 175       | 39.5%   |
| en_HK   | 110       | 24.83%  |
| zh_CN   | 59        | 13.32%  |
| Unknown | 34        | 7.67%   |
| zh_TW   | 22        | 4.97%   |
| zh_HK   | 16        | 3.61%   |
| en_GB   | 10        | 2.26%   |
| C       | 10        | 2.26%   |
| en_AU   | 3         | 0.68%   |
| zh_SG   | 1         | 0.23%   |
| it_IT   | 1         | 0.23%   |
| en_ZA   | 1         | 0.23%   |
| de_DE   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 274       | 63.87%  |
| BIOS | 155       | 36.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 301       | 69.04%  |
| Btrfs   | 62        | 14.22%  |
| Overlay | 29        | 6.65%   |
| Tmpfs   | 13        | 2.98%   |
| Xfs     | 10        | 2.29%   |
| Unknown | 8         | 1.83%   |
| Zfs     | 7         | 1.61%   |
| Ext2    | 3         | 0.69%   |
| Ext3    | 2         | 0.46%   |
| F2fs    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 237       | 54.99%  |
| Unknown | 157       | 36.43%  |
| MBR     | 37        | 8.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 369       | 85.02%  |
| Yes       | 65        | 14.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 273       | 62.9%   |
| Yes       | 161       | 37.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 90        | 21.28%  |
| ASUSTek Computer                     | 66        | 15.6%   |
| Dell                                 | 38        | 8.98%   |
| Hewlett-Packard                      | 32        | 7.57%   |
| MSI                                  | 30        | 7.09%   |
| Gigabyte Technology                  | 29        | 6.86%   |
| ASRock                               | 17        | 4.02%   |
| Unknown                              | 14        | 3.31%   |
| Fujitsu                              | 13        | 3.07%   |
| Acer                                 | 10        | 2.36%   |
| Apple                                | 9         | 2.13%   |
| HUAWEI                               | 8         | 1.89%   |
| Intel                                | 6         | 1.42%   |
| Samsung Electronics                  | 5         | 1.18%   |
| Raspberry Pi Foundation              | 4         | 0.95%   |
| GPD                                  | 4         | 0.95%   |
| Chuwi                                | 4         | 0.95%   |
| Supermicro                           | 3         | 0.71%   |
| AMI                                  | 3         | 0.71%   |
| Valve                                | 2         | 0.47%   |
| Toshiba                              | 2         | 0.47%   |
| Timi                                 | 2         | 0.47%   |
| KOHJINSHA                            | 2         | 0.47%   |
| IBM                                  | 2         | 0.47%   |
| AOKZOE                               | 2         | 0.47%   |
| ZOTAC                                | 1         | 0.24%   |
| Soyo                                 | 1         | 0.24%   |
| Sony                                 | 1         | 0.24%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.24%   |
| Seco                                 | 1         | 0.24%   |
| Schenker                             | 1         | 0.24%   |
| Panasonic                            | 1         | 0.24%   |
| Orange Pi                            | 1         | 0.24%   |
| ONE-NETBOOK                          | 1         | 0.24%   |
| Nvidia                               | 1         | 0.24%   |
| METAPHYUNI                           | 1         | 0.24%   |
| MeLE                                 | 1         | 0.24%   |
| MECHREVO                             | 1         | 0.24%   |
| MACHENIKE                            | 1         | 0.24%   |
| LG Electronics                       | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 15        | 3.55%   |
| ASUS All Series                     | 4         | 0.95%   |
| MSI MS-7C94                         | 3         | 0.71%   |
| Lenovo Legion R7000 2020 82B6       | 3         | 0.71%   |
| Chuwi HeroBook Pro                  | 3         | 0.71%   |
| ASUS H110I-PLUS                     | 3         | 0.71%   |
| Valve Jupiter                       | 2         | 0.47%   |
| RPi Raspberry Pi                    | 2         | 0.47%   |
| MSI MS-7D42                         | 2         | 0.47%   |
| MSI MS-7C02                         | 2         | 0.47%   |
| MSI MS-7B93                         | 2         | 0.47%   |
| Lenovo XiaoXinPro 14ITL 2021 82GH   | 2         | 0.47%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0    | 2         | 0.47%   |
| Lenovo G770 20089                   | 2         | 0.47%   |
| IBM 260921H                         | 2         | 0.47%   |
| HUAWEI KPRC-WX0                     | 2         | 0.47%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC    | 2         | 0.47%   |
| HP ProDesk 600 G1 SFF               | 2         | 0.47%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.47%   |
| HP OMEN by Gaming Laptop 16-wf0xxx  | 2         | 0.47%   |
| HP EliteBook 2540p                  | 2         | 0.47%   |
| GPD G1619-04                        | 2         | 0.47%   |
| Gigabyte X570 AORUS ELITE           | 2         | 0.47%   |
| Fujitsu UH-X                        | 2         | 0.47%   |
| Fujitsu LIFEBOOK AH544              | 2         | 0.47%   |
| Fujitsu FMVNU6G1C                   | 2         | 0.47%   |
| Dell XPS 13 9310                    | 2         | 0.47%   |
| Dell Inspiron 5580                  | 2         | 0.47%   |
| ASUS Z8NA-D6                        | 2         | 0.47%   |
| ASUS VM65                           | 2         | 0.47%   |
| ASUS VM62                           | 2         | 0.47%   |
| ASUS TUF Gaming FA506IU_FA506IU     | 2         | 0.47%   |
| ASRock H410M-ITX/ac                 | 2         | 0.47%   |
| ASRock H410M-HDV                    | 2         | 0.47%   |
| Apple MacBookAir6,2                 | 2         | 0.47%   |
| AOKZOE A1 AR07                      | 2         | 0.47%   |
| AMI Aptio CRB                       | 2         | 0.47%   |
| ZOTAC ZBOX-ID92/ZBOX-IQ01           | 1         | 0.24%   |
| Toshiba PORTEGE R830                | 1         | 0.24%   |
| Toshiba dynabook R731/E             | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 37        | 8.75%   |
| Unknown            | 15        | 3.55%   |
| ASUS ROG           | 13        | 3.07%   |
| Lenovo Legion      | 12        | 2.84%   |
| Dell XPS           | 10        | 2.36%   |
| Dell Inspiron      | 10        | 2.36%   |
| ASUS PRIME         | 9         | 2.13%   |
| Lenovo IdeaPad     | 8         | 1.89%   |
| Fujitsu LIFEBOOK   | 8         | 1.89%   |
| Dell Precision     | 7         | 1.65%   |
| ASUS TUF           | 7         | 1.65%   |
| Lenovo ThinkCentre | 5         | 1.18%   |
| Dell OptiPlex      | 5         | 1.18%   |
| RPi Raspberry      | 4         | 0.95%   |
| Lenovo Yoga        | 4         | 0.95%   |
| Lenovo ThinkBook   | 4         | 0.95%   |
| HP Pavilion        | 4         | 0.95%   |
| Dell Latitude      | 4         | 0.95%   |
| ASUS All           | 4         | 0.95%   |
| Acer Swift         | 4         | 0.95%   |
| Acer Aspire        | 4         | 0.95%   |
| MSI MS-7C94        | 3         | 0.71%   |
| HP ZHAN            | 3         | 0.71%   |
| HP ProDesk         | 3         | 0.71%   |
| HP OMEN            | 3         | 0.71%   |
| HP EliteBook       | 3         | 0.71%   |
| Gigabyte X570      | 3         | 0.71%   |
| Chuwi HeroBook     | 3         | 0.71%   |
| ASUS H110I-PLUS    | 3         | 0.71%   |
| Valve Jupiter      | 2         | 0.47%   |
| MSI MS-7D42        | 2         | 0.47%   |
| MSI MS-7C02        | 2         | 0.47%   |
| MSI MS-7B93        | 2         | 0.47%   |
| Lenovo XiaoXinPro  | 2         | 0.47%   |
| Lenovo IdeaPadFlex | 2         | 0.47%   |
| Lenovo IdeaCentre  | 2         | 0.47%   |
| Lenovo G770        | 2         | 0.47%   |
| IBM 260921H        | 2         | 0.47%   |
| HUAWEI KPRC-WX0    | 2         | 0.47%   |
| HP EliteDesk       | 2         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 55        | 13%     |
| 2020    | 53        | 12.53%  |
| 2021    | 44        | 10.4%   |
| 2022    | 35        | 8.27%   |
| 2019    | 34        | 8.04%   |
| 2014    | 25        | 5.91%   |
| 2013    | 20        | 4.73%   |
| 2017    | 19        | 4.49%   |
| 2016    | 19        | 4.49%   |
| 2011    | 19        | 4.49%   |
| 2010    | 18        | 4.26%   |
| 2015    | 17        | 4.02%   |
| 2012    | 16        | 3.78%   |
| 2023    | 14        | 3.31%   |
| 2008    | 10        | 2.36%   |
| Unknown | 10        | 2.36%   |
| 2007    | 6         | 1.42%   |
| 2009    | 5         | 1.18%   |
| 1999    | 2         | 0.47%   |
| 2005    | 1         | 0.24%   |
| 2003    | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 219       | 51.77%  |
| Desktop        | 162       | 38.3%   |
| Convertible    | 11        | 2.6%    |
| Mini pc        | 11        | 2.6%    |
| System on chip | 8         | 1.89%   |
| Tablet         | 5         | 1.18%   |
| Server         | 5         | 1.18%   |
| All in one     | 2         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 388       | 91.73%  |
| Enabled  | 35        | 8.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 422       | 99.76%  |
| Yes  | 1         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 96        | 22.43%  |
| 8.01-16.0   | 86        | 20.09%  |
| 4.01-8.0    | 69        | 16.12%  |
| 32.01-64.0  | 68        | 15.89%  |
| 3.01-4.0    | 43        | 10.05%  |
| 64.01-256.0 | 33        | 7.71%   |
| 24.01-32.0  | 11        | 2.57%   |
| 1.01-2.0    | 7         | 1.64%   |
| 2.01-3.0    | 6         | 1.4%    |
| 0.51-1.0    | 6         | 1.4%    |
| 0.01-0.5    | 3         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 117       | 25.32%  |
| 2.01-3.0   | 108       | 23.38%  |
| 4.01-8.0   | 87        | 18.83%  |
| 3.01-4.0   | 66        | 14.29%  |
| 8.01-16.0  | 35        | 7.58%   |
| 0.01-0.5   | 20        | 4.33%   |
| 0.51-1.0   | 15        | 3.25%   |
| 16.01-24.0 | 10        | 2.16%   |
| 32.01-64.0 | 2         | 0.43%   |
| 24.01-32.0 | 2         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 232       | 52.73%  |
| 2      | 131       | 29.77%  |
| 3      | 45        | 10.23%  |
| 5      | 10        | 2.27%   |
| 4      | 9         | 2.05%   |
| 0      | 6         | 1.36%   |
| 6      | 3         | 0.68%   |
| 9      | 2         | 0.45%   |
| 11     | 1         | 0.23%   |
| 7      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 338       | 79.34%  |
| Yes       | 88        | 20.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 336       | 78.87%  |
| No        | 90        | 21.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 339       | 79.21%  |
| No        | 89        | 20.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 287       | 66.74%  |
| No        | 143       | 33.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hong Kong | 423       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Central           | 238       | 53.13%  |
| Kowloon           | 26        | 5.8%    |
| Wanchai           | 18        | 4.02%   |
| Shatin            | 16        | 3.57%   |
| Tuen Mun          | 13        | 2.9%    |
| Hong Kong         | 13        | 2.9%    |
| Tseung Kwan O     | 11        | 2.46%   |
| Tsuen Wan         | 7         | 1.56%   |
| Tai Po            | 7         | 1.56%   |
| Hung Hom          | 7         | 1.56%   |
| Yuen Long         | 6         | 1.34%   |
| Tung Chung        | 6         | 1.34%   |
| Ngau Wu Tok       | 6         | 1.34%   |
| Sai Kung          | 5         | 1.12%   |
| To Kwa Wan        | 4         | 0.89%   |
| Tsimshatsui       | 3         | 0.67%   |
| Quarry Bay        | 3         | 0.67%   |
| Mong Kok          | 3         | 0.67%   |
| Ma On Shan Tsuen  | 3         | 0.67%   |
| Kwai Chung        | 3         | 0.67%   |
| Kowloon Bay       | 3         | 0.67%   |
| Ho Man Tin        | 3         | 0.67%   |
| Fanling           | 3         | 0.67%   |
| Yuen Long San Hui | 2         | 0.45%   |
| Wong Tai Sin      | 2         | 0.45%   |
| Tai Wan To        | 2         | 0.45%   |
| Sheung Shui       | 2         | 0.45%   |
| Sha Tin Wai       | 2         | 0.45%   |
| North Point       | 2         | 0.45%   |
| Man Kok           | 2         | 0.45%   |
| Ma On Shan        | 2         | 0.45%   |
| Kwun Hang         | 2         | 0.45%   |
| Kwu Tung          | 2         | 0.45%   |
| Discovery Bay     | 2         | 0.45%   |
| Cheung Sha Lan    | 2         | 0.45%   |
| Chai Wan          | 2         | 0.45%   |
| Yau Tsim Mong     | 1         | 0.22%   |
| Tuen Mun San Hui  | 1         | 0.22%   |
| Tin Shui Wai      | 1         | 0.22%   |
| Tai Wan           | 1         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 106       | 134    | 15.96%  |
| WDC                         | 79        | 111    | 11.9%   |
| Seagate                     | 65        | 90     | 9.79%   |
| Sandisk                     | 40        | 45     | 6.02%   |
| Toshiba                     | 34        | 47     | 5.12%   |
| Kingston                    | 28        | 34     | 4.22%   |
| Unknown                     | 27        | 31     | 4.07%   |
| Intel                       | 20        | 34     | 3.01%   |
| Hitachi                     | 19        | 27     | 2.86%   |
| SK hynix                    | 18        | 24     | 2.71%   |
| Crucial                     | 17        | 30     | 2.56%   |
| A-DATA Technology           | 16        | 22     | 2.41%   |
| HGST                        | 12        | 14     | 1.81%   |
| Micron Technology           | 10        | 11     | 1.51%   |
| Silicon Motion              | 9         | 12     | 1.36%   |
| KIOXIA                      | 8         | 9      | 1.2%    |
| Fujitsu                     | 8         | 15     | 1.2%    |
| Apple                       | 8         | 20     | 1.2%    |
| Phison                      | 7         | 10     | 1.05%   |
| Transcend                   | 6         | 7      | 0.9%    |
| LITEON                      | 6         | 6      | 0.9%    |
| JMicron Technology          | 6         | 10     | 0.9%    |
| ZHITAI                      | 5         | 7      | 0.75%   |
| Plextor                     | 5         | 6      | 0.75%   |
| Hikvision                   | 5         | 5      | 0.75%   |
| Netac                       | 4         | 4      | 0.6%    |
| HS-SSD-C100                 | 4         | 5      | 0.6%    |
| China                       | 4         | 6      | 0.6%    |
| BIWIN                       | 4         | 4      | 0.6%    |
| Unknown                     | 4         | 4      | 0.6%    |
| Yangtze Memory Technologies | 3         | 3      | 0.45%   |
| Team                        | 3         | 3      | 0.45%   |
| MAXIO Technology (Hangzhou) | 3         | 3      | 0.45%   |
| Gigabyte Technology         | 3         | 6      | 0.45%   |
| DOGGO                       | 3         | 3      | 0.45%   |
| Biwin Storage Technology    | 3         | 3      | 0.45%   |
| Yangtze Memory              | 2         | 2      | 0.3%    |
| TO Exter                    | 2         | 2      | 0.3%    |
| SPCC                        | 2         | 2      | 0.3%    |
| Micron/Crucial Technology   | 2         | 2      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 9         | 1.26%   |
| Toshiba DT01ACA100 1TB                             | 6         | 0.84%   |
| Samsung SSD 860 EVO 1TB                            | 6         | 0.84%   |
| Samsung NVMe SSD Drive 512GB                       | 6         | 0.84%   |
| Unknown MMC Card  64GB                             | 5         | 0.7%    |
| SanDisk NVMe SSD Drive 1TB                         | 5         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 0.7%    |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.7%    |
| JMicron Generic 256GB                              | 5         | 0.7%    |
| Fujitsu F300 480GB                                 | 5         | 0.7%    |
| Crucial CT500MX500SSD1 500GB                       | 5         | 0.7%    |
| A-DATA SP550 240GB SSD                             | 5         | 0.7%    |
| WDC WDS100T2B0C-00PXH0 1TB                         | 4         | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 4         | 0.56%   |
| Unknown MMC Card  32GB                             | 4         | 0.56%   |
| Unknown MMC Card  128GB                            | 4         | 0.56%   |
| Toshiba DT01ACA050 500GB                           | 4         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                    | 4         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 0.56%   |
| Samsung SSD 980 1TB                                | 4         | 0.56%   |
| Samsung NVMe SSD Drive 1024GB                      | 4         | 0.56%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                   | 4         | 0.56%   |
| Kingston SA400S37120G 120GB SSD                    | 4         | 0.56%   |
| Unknown                                            | 4         | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 3         | 0.42%   |
| WDC WD30EZRX-00D8PB0 3TB                           | 3         | 0.42%   |
| Unknown SD32G  32GB                                | 3         | 0.42%   |
| Toshiba DT01ACA300 3TB                             | 3         | 0.42%   |
| Toshiba DT01ACA200 2TB                             | 3         | 0.42%   |
| Seagate ST3500418AS 500GB                          | 3         | 0.42%   |
| Seagate ST3500413AS 500GB                          | 3         | 0.42%   |
| Seagate ST2000LM007-1R8174 2TB                     | 3         | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                     | 3         | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                       | 3         | 0.42%   |
| Samsung SSD 970 EVO Plus 2TB                       | 3         | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 0.42%   |
| Samsung SSD 860 EVO 250GB                          | 3         | 0.42%   |
| Samsung NVMe SSD Drive 1TB                         | 3         | 0.42%   |
| Samsung MZVL2512HCJQ-00BL2 512GB                   | 3         | 0.42%   |
| DOGGO DQ-60G SSD                                   | 3         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 90     | 34.95%  |
| WDC                 | 50        | 75     | 26.88%  |
| Toshiba             | 29        | 42     | 15.59%  |
| Hitachi             | 19        | 27     | 10.22%  |
| HGST                | 12        | 14     | 6.45%   |
| Fujitsu             | 2         | 2      | 1.08%   |
| External            | 2         | 2      | 1.08%   |
| USB3.0              | 1         | 1      | 0.54%   |
| Unknown             | 1         | 1      | 0.54%   |
| Samsung Electronics | 1         | 1      | 0.54%   |
| Maxtor              | 1         | 1      | 0.54%   |
| JMicron Technology  | 1         | 2      | 0.54%   |
| HGST HTS            | 1         | 1      | 0.54%   |
| Apple               | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 46     | 17.68%  |
| Kingston            | 19        | 24     | 10.5%   |
| Crucial             | 14        | 27     | 7.73%   |
| A-DATA Technology   | 13        | 19     | 7.18%   |
| WDC                 | 12        | 12     | 6.63%   |
| SanDisk             | 8         | 8      | 4.42%   |
| Transcend           | 6         | 7      | 3.31%   |
| Intel               | 6         | 11     | 3.31%   |
| LITEON              | 5         | 5      | 2.76%   |
| Fujitsu             | 5         | 12     | 2.76%   |
| Plextor             | 4         | 5      | 2.21%   |
| Netac               | 4         | 4      | 2.21%   |
| China               | 4         | 6      | 2.21%   |
| Apple               | 4         | 4      | 2.21%   |
| Team                | 3         | 3      | 1.66%   |
| SK hynix            | 3         | 7      | 1.66%   |
| DOGGO               | 3         | 3      | 1.66%   |
| ZHITAI              | 2         | 2      | 1.1%    |
| TO Exter            | 2         | 2      | 1.1%    |
| Micron Technology   | 2         | 3      | 1.1%    |
| Lexar               | 2         | 2      | 1.1%    |
| HS-SSD-C100         | 2         | 2      | 1.1%    |
| Hikvision           | 2         | 2      | 1.1%    |
| BIWIN               | 2         | 2      | 1.1%    |
| Apacer              | 2         | 7      | 1.1%    |
| AGI                 | 2         | 2      | 1.1%    |
| Verbatim            | 1         | 2      | 0.55%   |
| Unknown (CF)        | 1         | 1      | 0.55%   |
| tigo                | 1         | 1      | 0.55%   |
| SPCC                | 1         | 1      | 0.55%   |
| ShiJi               | 1         | 6      | 0.55%   |
| RECADATA            | 1         | 1      | 0.55%   |
| Ramsta              | 1         | 1      | 0.55%   |
| PNY                 | 1         | 1      | 0.55%   |
| OCZ                 | 1         | 1      | 0.55%   |
| NGFF                | 1         | 1      | 0.55%   |
| MAXSUN              | 1         | 1      | 0.55%   |
| KLEVV               | 1         | 1      | 0.55%   |
| Dogfish             | 1         | 1      | 0.55%   |
| DGM                 | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 218       | 324    | 37.46%  |
| HDD     | 162       | 260    | 27.84%  |
| SSD     | 159       | 251    | 27.32%  |
| MMC     | 25        | 29     | 4.3%    |
| Unknown | 18        | 21     | 3.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 252       | 497    | 47.73%  |
| NVMe | 215       | 313    | 40.72%  |
| SAS  | 36        | 46     | 6.82%   |
| MMC  | 25        | 29     | 4.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 178       | 282    | 54.77%  |
| 0.51-1.0   | 82        | 113    | 25.23%  |
| 1.01-2.0   | 33        | 45     | 10.15%  |
| 3.01-4.0   | 11        | 33     | 3.38%   |
| 2.01-3.0   | 11        | 18     | 3.38%   |
| 4.01-10.0  | 9         | 17     | 2.77%   |
| 10.01-20.0 | 1         | 3      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 108       | 23.79%  |
| 251-500        | 84        | 18.5%   |
| 501-1000       | 64        | 14.1%   |
| 1001-2000      | 45        | 9.91%   |
| 51-100         | 39        | 8.59%   |
| 1-20           | 35        | 7.71%   |
| More than 3000 | 31        | 6.83%   |
| 2001-3000      | 19        | 4.19%   |
| 21-50          | 16        | 3.52%   |
| Unknown        | 13        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 184       | 39.15%  |
| 21-50          | 57        | 12.13%  |
| 101-250        | 54        | 11.49%  |
| 251-500        | 52        | 11.06%  |
| 51-100         | 48        | 10.21%  |
| 501-1000       | 28        | 5.96%   |
| 1001-2000      | 19        | 4.04%   |
| Unknown        | 13        | 2.77%   |
| 2001-3000      | 9         | 1.91%   |
| More than 3000 | 6         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 2         | 2      | 5.13%   |
| LITEON CV8-8E128-HP 128GB SSD                | 2         | 2      | 5.13%   |
| ZHITAI TiPlus5000 512GB                      | 1         | 1      | 2.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1      | 2.56%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 1      | 2.56%   |
| WDC WD10EZEX-60WN4A1 1TB                     | 1         | 1      | 2.56%   |
| WDC WD10EZEX-00RKKA0 1TB                     | 1         | 1      | 2.56%   |
| WDC WD10EALS-00Z8A0 1TB                      | 1         | 2      | 2.56%   |
| Toshiba MK1655GSX 160GB                      | 1         | 1      | 2.56%   |
| Toshiba MK1252GSX 120GB                      | 1         | 1      | 2.56%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1      | 2.56%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 2.56%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.56%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 2.56%   |
| Seagate ST3250310AS 250GB                    | 1         | 1      | 2.56%   |
| Seagate ST3160815AS 160GB                    | 1         | 1      | 2.56%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB          | 1         | 1      | 2.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 860 EVO 1TB          | 1         | 1      | 2.56%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB | 1         | 1      | 2.56%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD    | 1         | 1      | 2.56%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.56%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 1      | 2.56%   |
| Intel SSDPEKKW128G7 128GB                    | 1         | 1      | 2.56%   |
| Intel SSD 600P Series 256GB                  | 1         | 3      | 2.56%   |
| Hitachi HTS725050A7E630 500GB                | 1         | 1      | 2.56%   |
| Hitachi HTS723216L9A360 160GB                | 1         | 1      | 2.56%   |
| Hitachi HTS542512K9SA00 120GB                | 1         | 1      | 2.56%   |
| Hitachi HTC426040G8CE00 40GB                 | 1         | 1      | 2.56%   |
| HGST TOURO Mobile 1TB                        | 1         | 1      | 2.56%   |
| HGST HTS 541010A9E680 1TB                    | 1         | 1      | 2.56%   |
| DGM SSD 120GB S3-120A                        | 1         | 1      | 2.56%   |
| Crucial CT500MX500SSD1 500GB                 | 1         | 2      | 2.56%   |
| Crucial CT240M500SSD1 240GB                  | 1         | 1      | 2.56%   |
| BIWIN SSD 32GB                               | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 21.05%  |
| WDC                 | 4         | 6      | 10.53%  |
| Hitachi             | 4         | 4      | 10.53%  |
| Toshiba             | 3         | 3      | 7.89%   |
| Samsung Electronics | 3         | 3      | 7.89%   |
| LITEON              | 3         | 3      | 7.89%   |
| Kingston            | 2         | 2      | 5.26%   |
| Intel               | 2         | 4      | 5.26%   |
| Crucial             | 2         | 3      | 5.26%   |
| ZHITAI              | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| HGST HTS            | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| DGM                 | 1         | 1      | 2.63%   |
| BIWIN               | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 8         | 8      | 40%     |
| Hitachi  | 4         | 4      | 20%     |
| WDC      | 3         | 5      | 15%     |
| Toshiba  | 3         | 3      | 15%     |
| HGST HTS | 1         | 1      | 5%      |
| HGST     | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 22     | 51.35%  |
| SSD  | 13        | 14     | 35.14%  |
| NVMe | 5         | 7      | 13.51%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 221       | 432    | 47.53%  |
| Detected | 207       | 410    | 44.52%  |
| Malfunc  | 37        | 43     | 7.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 265       | 44.84%  |
| Samsung Electronics              | 81        | 13.71%  |
| AMD                              | 58        | 9.81%   |
| SanDisk                          | 49        | 8.29%   |
| SK hynix                         | 15        | 2.54%   |
| Silicon Motion                   | 13        | 2.2%    |
| ASMedia Technology               | 13        | 2.2%    |
| Phison Electronics               | 11        | 1.86%   |
| Kingston Technology Company      | 10        | 1.69%   |
| Yangtze Memory Technologies      | 8         | 1.35%   |
| Micron Technology                | 8         | 1.35%   |
| Toshiba America Info Systems     | 7         | 1.18%   |
| KIOXIA                           | 7         | 1.18%   |
| Marvell Technology Group         | 6         | 1.02%   |
| Micron/Crucial Technology        | 5         | 0.85%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.85%   |
| ADATA Technology                 | 5         | 0.85%   |
| Biwin Storage Technology         | 4         | 0.68%   |
| VIA Technologies                 | 2         | 0.34%   |
| Nvidia                           | 2         | 0.34%   |
| LSI Logic / Symbios Logic        | 2         | 0.34%   |
| Lite-On Technology               | 2         | 0.34%   |
| JMicron Technology               | 2         | 0.34%   |
| Broadcom / LSI                   | 2         | 0.34%   |
| Apple                            | 2         | 0.34%   |
| Solid State Storage Technology   | 1         | 0.17%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.17%   |
| Realtek Semiconductor            | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| Integrated Technology Express    | 1         | 0.17%   |
| INNOGRIT                         | 1         | 0.17%   |
| Huawei Technologies              | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 41        | 6.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 39        | 5.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 3.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 2.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 17        | 2.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 2.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 1.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 13        | 1.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 1.99%   |
| AMD 400 Series Chipset SATA Controller                                         | 13        | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 12        | 1.83%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11        | 1.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 1.53%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 9         | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 1.22%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 8         | 1.22%   |
| Intel SSD 660P Series                                                          | 8         | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 1.22%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 1.07%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 7         | 1.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 0.76%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 280       | 49.38%  |
| NVMe | 215       | 37.92%  |
| RAID | 34        | 6%      |
| IDE  | 34        | 6%      |
| SAS  | 4         | 0.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 318       | 75.18%  |
| AMD          | 92        | 21.75%  |
| ARM          | 7         | 1.65%   |
| Unknown      | 3         | 0.71%   |
| Phytium      | 1         | 0.24%   |
| HISILICON    | 1         | 0.24%   |
| GenuineTMx86 | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz       | 7         | 1.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 1.42%   |
| ARM Processor                           | 6         | 1.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 6         | 1.42%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 1.18%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 5         | 1.18%   |
| AMD Ryzen 7 6800U with Radeon Graphics  | 5         | 1.18%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 5         | 1.18%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 5         | 1.18%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 4         | 0.94%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 4         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 0.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 0.94%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 4         | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor       | 4         | 0.94%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 3         | 0.71%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3         | 0.71%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 0.71%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 3         | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 3         | 0.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 0.71%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 3         | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 0.71%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3         | 0.71%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 3         | 0.71%   |
| Intel 12th Gen Core i7-12700H           | 3         | 0.71%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 3         | 0.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 0.71%   |
| AMD Ryzen 9 7950X 16-Core Processor     | 3         | 0.71%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 3         | 0.71%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 3         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 80        | 18.87%  |
| Intel Core i5           | 78        | 18.4%   |
| Other                   | 69        | 16.27%  |
| AMD Ryzen 7             | 34        | 8.02%   |
| Intel Celeron           | 29        | 6.84%   |
| Intel Core i3           | 26        | 6.13%   |
| AMD Ryzen 5             | 22        | 5.19%   |
| AMD Ryzen 9             | 18        | 4.25%   |
| Intel Xeon              | 14        | 3.3%    |
| Intel Pentium           | 6         | 1.42%   |
| Intel Core 2 Duo        | 5         | 1.18%   |
| Intel Atom              | 5         | 1.18%   |
| Intel Core m3           | 3         | 0.71%   |
| AMD Phenom II X4        | 3         | 0.71%   |
| Intel Pentium Gold      | 2         | 0.47%   |
| Intel Pentium Dual-Core | 2         | 0.47%   |
| Intel Pentium Dual      | 2         | 0.47%   |
| Intel Genuine           | 2         | 0.47%   |
| Intel Core i9           | 2         | 0.47%   |
| AMD Ryzen 7 PRO         | 2         | 0.47%   |
| AMD Phenom II X6        | 2         | 0.47%   |
| AMD FX                  | 2         | 0.47%   |
| Intel Xeon Silver       | 1         | 0.24%   |
| Intel Xeon Gold         | 1         | 0.24%   |
| Intel Pentium Silver    | 1         | 0.24%   |
| Intel Pentium M         | 1         | 0.24%   |
| Intel Core 2 Quad       | 1         | 0.24%   |
| Intel Core 2 Extreme    | 1         | 0.24%   |
| Intel Core 2            | 1         | 0.24%   |
| ARM BCM                 | 1         | 0.24%   |
| AMD Ryzen Threadripper  | 1         | 0.24%   |
| AMD Ryzen Embedded      | 1         | 0.24%   |
| AMD Quad-Core           | 1         | 0.24%   |
| AMD Athlon II X4        | 1         | 0.24%   |
| AMD Athlon II X3        | 1         | 0.24%   |
| AMD Athlon 64 X2        | 1         | 0.24%   |
| AMD A8                  | 1         | 0.24%   |
| AMD A10                 | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 148       | 34.91%  |
| 2       | 107       | 25.24%  |
| 8       | 60        | 14.15%  |
| 6       | 42        | 9.91%   |
| 12      | 20        | 4.72%   |
| 16      | 10        | 2.36%   |
| 1       | 10        | 2.36%   |
| 14      | 8         | 1.89%   |
| 10      | 7         | 1.65%   |
| 24      | 4         | 0.94%   |
| 3       | 3         | 0.71%   |
| Unknown | 3         | 0.71%   |
| 64      | 1         | 0.24%   |
| 32      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 413       | 97.64%  |
| 2       | 7         | 1.65%   |
| Unknown | 3         | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 307       | 72.24%  |
| 1       | 115       | 27.06%  |
| Unknown | 3         | 0.71%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 400       | 94.56%  |
| 32-bit         | 10        | 2.36%   |
| Unknown        | 9         | 2.13%   |
| 64-bit         | 4         | 0.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 29.89%  |
| 0x306c3    | 17        | 3.91%   |
| 0x206a7    | 17        | 3.91%   |
| 0x906ea    | 14        | 3.22%   |
| 0x806e9    | 13        | 2.99%   |
| 0x306a9    | 13        | 2.99%   |
| 0x806ea    | 11        | 2.53%   |
| 0x90672    | 10        | 2.3%    |
| 0x806c1    | 9         | 2.07%   |
| 0x506e3    | 8         | 1.84%   |
| 0x40651    | 8         | 1.84%   |
| 0x0a50000c | 8         | 1.84%   |
| 0x806eb    | 7         | 1.61%   |
| 0x806ec    | 6         | 1.38%   |
| 0x406e3    | 6         | 1.38%   |
| 0x0a404102 | 6         | 1.38%   |
| 0x08600106 | 6         | 1.38%   |
| 0xa0652    | 5         | 1.15%   |
| 0x906ed    | 5         | 1.15%   |
| 0x906e9    | 5         | 1.15%   |
| 0x706e5    | 5         | 1.15%   |
| 0x506c9    | 5         | 1.15%   |
| 0x706a8    | 4         | 0.92%   |
| 0x306e4    | 4         | 0.92%   |
| 0x20655    | 4         | 0.92%   |
| 0x20652    | 4         | 0.92%   |
| 0x106c2    | 4         | 0.92%   |
| 0x1067a    | 4         | 0.92%   |
| 0x0a601203 | 4         | 0.92%   |
| 0x0a50000d | 4         | 0.92%   |
| 0x08701013 | 4         | 0.92%   |
| 0x0800820d | 4         | 0.92%   |
| 0xb0671    | 3         | 0.69%   |
| 0xa0653    | 3         | 0.69%   |
| 0x906a3    | 3         | 0.69%   |
| 0x6fd      | 3         | 0.69%   |
| 0x30678    | 3         | 0.69%   |
| 0x0a201009 | 3         | 0.69%   |
| 0x08701021 | 3         | 0.69%   |
| 0x08600104 | 3         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 18.35%  |
| Unknown          | 47        | 11.06%  |
| Haswell          | 36        | 8.47%   |
| Zen 3            | 24        | 5.65%   |
| Zen 2            | 24        | 5.65%   |
| IvyBridge        | 24        | 5.65%   |
| Skylake          | 22        | 5.18%   |
| SandyBridge      | 22        | 5.18%   |
| Alderlake Hybrid | 22        | 5.18%   |
| TigerLake        | 18        | 4.24%   |
| CometLake        | 13        | 3.06%   |
| Westmere         | 12        | 2.82%   |
| IceLake          | 12        | 2.82%   |
| Zen+             | 10        | 2.35%   |
| Goldmont plus    | 10        | 2.35%   |
| K10              | 7         | 1.65%   |
| Penryn           | 6         | 1.41%   |
| Goldmont         | 6         | 1.41%   |
| Core             | 6         | 1.41%   |
| Silvermont       | 5         | 1.18%   |
| Broadwell        | 4         | 0.94%   |
| Bonnell          | 4         | 0.94%   |
| P6               | 3         | 0.71%   |
| Zen              | 2         | 0.47%   |
| Steamroller      | 2         | 0.47%   |
| Piledriver       | 2         | 0.47%   |
| Tremont          | 1         | 0.24%   |
| Nehalem          | 1         | 0.24%   |
| K8 Hammer        | 1         | 0.24%   |
| Jaguar           | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 253       | 49.51%  |
| Nvidia                     | 154       | 30.14%  |
| AMD                        | 96        | 18.79%  |
| Matrox Electronics Systems | 3         | 0.59%   |
| Neomagic                   | 2         | 0.39%   |
| ASPEED Technology          | 2         | 0.39%   |
| S3 Graphics                | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 17        | 3.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 17        | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 16        | 3.04%   |
| Intel UHD Graphics 620                                                        | 14        | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 13        | 2.47%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 2.09%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 11        | 2.09%   |
| AMD Rembrandt [Radeon 680M]                                                   | 11        | 2.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 10        | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 1.9%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 10        | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 1.71%   |
| Intel HD Graphics 620                                                         | 8         | 1.52%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 8         | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 1.33%   |
| Intel HD Graphics 530                                                         | 7         | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 7         | 1.33%   |
| Nvidia GP108M [GeForce MX150]                                                 | 6         | 1.14%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 6         | 1.14%   |
| Intel HD Graphics 500                                                         | 6         | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 1.14%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 5         | 0.95%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 5         | 0.95%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 5         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 5         | 0.95%   |
| Intel AlderLake-S GT1                                                         | 5         | 0.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 5         | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 0.95%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 5         | 0.95%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 4         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 4         | 0.76%   |
| Nvidia GM107 [GeForce GTX 750]                                                | 4         | 0.76%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 4         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 0.76%   |
| Intel HD Graphics 615                                                         | 4         | 0.76%   |
| Intel HD Graphics 610                                                         | 4         | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 179       | 42.12%  |
| 1 x Nvidia      | 74        | 17.41%  |
| 1 x AMD         | 63        | 14.82%  |
| Intel + Nvidia  | 59        | 13.88%  |
| AMD + Nvidia    | 18        | 4.24%   |
| Other           | 10        | 2.35%   |
| Intel + AMD     | 8         | 1.88%   |
| 2 x AMD         | 5         | 1.18%   |
| Nvidia + Matrox | 2         | 0.47%   |
| 1 x Neomagic    | 2         | 0.47%   |
| 1 x ASPEED      | 2         | 0.47%   |
| 3 x AMD         | 1         | 0.24%   |
| 1 x S3 Graphics | 1         | 0.24%   |
| 1 x Matrox      | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 314       | 73.54%  |
| Proprietary | 88        | 20.61%  |
| Unknown     | 25        | 5.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 60.93%  |
| 1.01-2.0   | 36        | 8.37%   |
| 0.01-0.5   | 31        | 7.21%   |
| 7.01-8.0   | 30        | 6.98%   |
| 0.51-1.0   | 25        | 5.81%   |
| 3.01-4.0   | 22        | 5.12%   |
| 5.01-6.0   | 14        | 3.26%   |
| 8.01-16.0  | 5         | 1.16%   |
| 2.01-3.0   | 3         | 0.7%    |
| 4.01-5.0   | 1         | 0.23%   |
| 16.01-24.0 | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 52        | 11.5%   |
| AU Optronics            | 44        | 9.73%   |
| Samsung Electronics     | 36        | 7.96%   |
| Dell                    | 29        | 6.42%   |
| LG Display              | 28        | 6.19%   |
| AOC                     | 26        | 5.75%   |
| Chimei Innolux          | 25        | 5.53%   |
| Goldstar                | 21        | 4.65%   |
| Philips                 | 16        | 3.54%   |
| Sharp                   | 13        | 2.88%   |
| BenQ                    | 10        | 2.21%   |
| Ancor Communications    | 10        | 2.21%   |
| Acer                    | 9         | 1.99%   |
| Lenovo                  | 8         | 1.77%   |
| Unknown                 | 7         | 1.55%   |
| Apple                   | 7         | 1.55%   |
| IPS                     | 6         | 1.33%   |
| ASUSTek Computer        | 6         | 1.33%   |
| AMO                     | 6         | 1.33%   |
| ViewSonic               | 5         | 1.11%   |
| RTK                     | 5         | 1.11%   |
| Hewlett-Packard         | 5         | 1.11%   |
| JDI                     | 4         | 0.88%   |
| CSO                     | 4         | 0.88%   |
| PANDA                   | 3         | 0.66%   |
| Mi                      | 3         | 0.66%   |
| InfoVision              | 3         | 0.66%   |
| Valve                   | 2         | 0.44%   |
| TMX                     | 2         | 0.44%   |
| Sony                    | 2         | 0.44%   |
| SKY                     | 2         | 0.44%   |
| SAC                     | 2         | 0.44%   |
| LG Philips              | 2         | 0.44%   |
| LDR                     | 2         | 0.44%   |
| Intehill                | 2         | 0.44%   |
| HSO                     | 2         | 0.44%   |
| Eizo                    | 2         | 0.44%   |
| CPT                     | 2         | 0.44%   |
| Chi Mei Optoelectronics | 2         | 0.44%   |
| AUS                     | 2         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 5         | 1.08%   |
| IPS T270LG IPS2700 3840x2160 608x355mm 27.7-inch                      | 4         | 0.86%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 4         | 0.86%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4         | 0.86%   |
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4         | 0.86%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3         | 0.65%   |
| RTK FHD HDR RTK2A3B 1920x1080 344x195mm 15.6-inch                     | 3         | 0.65%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 3         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.65%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 0.65%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.65%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.43%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 0.43%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.43%   |
| SAC HDMI SAC2400 1920x1080 530x300mm 24.0-inch                        | 2         | 0.43%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 2         | 0.43%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 0.43%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.43%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2         | 0.43%   |
| LDR CFORCE LDR1560 1920x1080 300x260mm 15.6-inch                      | 2         | 0.43%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.43%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 2         | 0.43%   |
| Intehill HS156PE HSJ0156 1920x1080 345x194mm 15.6-inch                | 2         | 0.43%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2         | 0.43%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.43%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2         | 0.43%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 2         | 0.43%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 2         | 0.43%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 2         | 0.43%   |
| Dell P2416D DELA0C3 2560x1440 527x296mm 23.8-inch                     | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 2         | 0.43%   |
| BOE LCD Monitor BOE0B7D 2560x1440 355x200mm 16.0-inch                 | 2         | 0.43%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.43%   |
| AU Optronics LCD Monitor AUOC391 2880x1800 301x188mm 14.0-inch        | 2         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 189       | 44.47%  |
| 3840x2160 (4K)     | 53        | 12.47%  |
| 1366x768 (WXGA)    | 36        | 8.47%   |
| 2560x1440 (QHD)    | 32        | 7.53%   |
| 2560x1600          | 14        | 3.29%   |
| 1440x900 (WXGA+)   | 12        | 2.82%   |
| 1600x900 (HD+)     | 9         | 2.12%   |
| Unknown            | 7         | 1.65%   |
| 1280x800 (WXGA)    | 6         | 1.41%   |
| 3840x2400          | 5         | 1.18%   |
| 2880x1800          | 5         | 1.18%   |
| 1920x1200 (WUXGA)  | 5         | 1.18%   |
| 1680x1050 (WSXGA+) | 5         | 1.18%   |
| 3440x1440          | 4         | 0.94%   |
| 3000x2000          | 4         | 0.94%   |
| 2240x1400          | 4         | 0.94%   |
| 1280x1024 (SXGA)   | 4         | 0.94%   |
| 3840x1080          | 3         | 0.71%   |
| 1360x768           | 3         | 0.71%   |
| 800x1280           | 2         | 0.47%   |
| 2560x1080          | 2         | 0.47%   |
| 1024x768 (XGA)     | 2         | 0.47%   |
| 5120x1440          | 1         | 0.24%   |
| 4480x1440          | 1         | 0.24%   |
| 3840x1600          | 1         | 0.24%   |
| 3840x1100          | 1         | 0.24%   |
| 3520x1080          | 1         | 0.24%   |
| 3456x2160          | 1         | 0.24%   |
| 3200x2000          | 1         | 0.24%   |
| 3200x1800 (QHD+)   | 1         | 0.24%   |
| 3200x1080          | 1         | 0.24%   |
| 2880x1920          | 1         | 0.24%   |
| 2880x1620          | 1         | 0.24%   |
| 2400x1600          | 1         | 0.24%   |
| 2304x1440          | 1         | 0.24%   |
| 2256x1504          | 1         | 0.24%   |
| 2160x1440          | 1         | 0.24%   |
| 2160x1350          | 1         | 0.24%   |
| 1600x2560          | 1         | 0.24%   |
| 1024x600           | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 16.37%  |
| 13      | 52        | 11.66%  |
| 14      | 43        | 9.64%   |
| 24      | 35        | 7.85%   |
| 27      | 34        | 7.62%   |
| 23      | 33        | 7.4%    |
| 21      | 33        | 7.4%    |
| Unknown | 24        | 5.38%   |
| 12      | 15        | 3.36%   |
| 31      | 14        | 3.14%   |
| 16      | 13        | 2.91%   |
| 18      | 10        | 2.24%   |
| 17      | 10        | 2.24%   |
| 40      | 8         | 1.79%   |
| 19      | 6         | 1.35%   |
| 34      | 5         | 1.12%   |
| 28      | 5         | 1.12%   |
| 84      | 3         | 0.67%   |
| 57      | 3         | 0.67%   |
| 22      | 3         | 0.67%   |
| 10      | 3         | 0.67%   |
| 32      | 2         | 0.45%   |
| 26      | 2         | 0.45%   |
| 25      | 2         | 0.45%   |
| 8       | 2         | 0.45%   |
| 7       | 2         | 0.45%   |
| 72      | 1         | 0.22%   |
| 65      | 1         | 0.22%   |
| 58      | 1         | 0.22%   |
| 54      | 1         | 0.22%   |
| 52      | 1         | 0.22%   |
| 50      | 1         | 0.22%   |
| 48      | 1         | 0.22%   |
| 43      | 1         | 0.22%   |
| 37      | 1         | 0.22%   |
| 20      | 1         | 0.22%   |
| 11      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 143       | 32.8%   |
| 501-600     | 99        | 22.71%  |
| 201-300     | 53        | 12.16%  |
| 401-500     | 49        | 11.24%  |
| Unknown     | 24        | 5.5%    |
| 601-700     | 20        | 4.59%   |
| 351-400     | 14        | 3.21%   |
| 701-800     | 10        | 2.29%   |
| 801-900     | 9         | 2.06%   |
| 1001-1500   | 6         | 1.38%   |
| 1501-2000   | 4         | 0.92%   |
| 101-200     | 2         | 0.46%   |
| 1-100       | 2         | 0.46%   |
| 901-1000    | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 297       | 72.97%  |
| 16/10   | 60        | 14.74%  |
| Unknown | 21        | 5.16%   |
| 3/2     | 9         | 2.21%   |
| 21/9    | 6         | 1.47%   |
| 0.56    | 3         | 0.74%   |
| 6/5     | 2         | 0.49%   |
| 4/3     | 2         | 0.49%   |
| 0.67    | 2         | 0.49%   |
| 0.62    | 2         | 0.49%   |
| 5/4     | 1         | 0.25%   |
| 32/9    | 1         | 0.25%   |
| 3.40    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 84        | 18.92%  |
| 101-110        | 75        | 16.89%  |
| 81-90          | 72        | 16.22%  |
| 301-350        | 41        | 9.23%   |
| 71-80          | 24        | 5.41%   |
| Unknown        | 24        | 5.41%   |
| 351-500        | 22        | 4.95%   |
| 151-200        | 20        | 4.5%    |
| 61-70          | 14        | 3.15%   |
| More than 1000 | 12        | 2.7%    |
| 251-300        | 10        | 2.25%   |
| 501-1000       | 10        | 2.25%   |
| 121-130        | 9         | 2.03%   |
| 111-120        | 9         | 2.03%   |
| 141-150        | 6         | 1.35%   |
| 1-40           | 4         | 0.9%    |
| 41-50          | 3         | 0.68%   |
| 51-60          | 2         | 0.45%   |
| 91-100         | 2         | 0.45%   |
| 131-140        | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 114       | 26.45%  |
| 121-160       | 113       | 26.22%  |
| 101-120       | 82        | 19.03%  |
| 161-240       | 58        | 13.46%  |
| More than 240 | 28        | 6.5%    |
| Unknown       | 24        | 5.57%   |
| 1-50          | 12        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 333       | 77.44%  |
| 2     | 70        | 16.28%  |
| 0     | 24        | 5.58%   |
| 3     | 3         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 250       | 40.58%  |
| Realtek Semiconductor                  | 203       | 32.95%  |
| Qualcomm Atheros                       | 42        | 6.82%   |
| Broadcom                               | 25        | 4.06%   |
| MediaTek                               | 23        | 3.73%   |
| TP-Link                                | 10        | 1.62%   |
| ASIX Electronics                       | 10        | 1.62%   |
| Ralink Technology                      | 9         | 1.46%   |
| Broadcom Limited                       | 5         | 0.81%   |
| Qualcomm                               | 3         | 0.49%   |
| Microsoft                              | 3         | 0.49%   |
| Marvell Technology Group               | 3         | 0.49%   |
| Xiaomi                                 | 2         | 0.32%   |
| SEGGER                                 | 2         | 0.32%   |
| Lenovo                                 | 2         | 0.32%   |
| Huawei Technologies                    | 2         | 0.32%   |
| Texas Instruments                      | 1         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.16%   |
| Samsung Electronics                    | 1         | 0.16%   |
| Ralink                                 | 1         | 0.16%   |
| Quectel Wireless Solutions             | 1         | 0.16%   |
| PEAK-System Technik                    | 1         | 0.16%   |
| OPPO Electronics                       | 1         | 0.16%   |
| Nvidia                                 | 1         | 0.16%   |
| NetGear                                | 1         | 0.16%   |
| National Semiconductor                 | 1         | 0.16%   |
| Kinesis                                | 1         | 0.16%   |
| ICS Advent                             | 1         | 0.16%   |
| Google                                 | 1         | 0.16%   |
| Fitbit                                 | 1         | 0.16%   |
| DisplayLink                            | 1         | 0.16%   |
| D-Link System                          | 1         | 0.16%   |
| D-Link                                 | 1         | 0.16%   |
| Belkin Components                      | 1         | 0.16%   |
| ASUSTek Computer                       | 1         | 0.16%   |
| Arduino SA                             | 1         | 0.16%   |
| Aquantia                               | 1         | 0.16%   |
| Apple                                  | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 132       | 17.89%  |
| Intel Wi-Fi 6 AX200                                               | 33        | 4.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 2.71%   |
| Intel Wireless 8265 / 8275                                        | 16        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 2.03%   |
| Intel I211 Gigabit Network Connection                             | 14        | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 13        | 1.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 1.63%   |
| Intel Ethernet Controller I225-V                                  | 12        | 1.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 10        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 8         | 1.08%   |
| Intel Wireless 7265                                               | 8         | 1.08%   |
| Intel Wireless 7260                                               | 8         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 8         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.95%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 7         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 0.95%   |
| Intel Wireless 8260                                               | 7         | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 0.68%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 5         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.68%   |
| Intel I350 Gigabit Network Connection                             | 5         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 201       | 56.46%  |
| Realtek Semiconductor      | 44        | 12.36%  |
| Qualcomm Atheros           | 34        | 9.55%   |
| MediaTek                   | 23        | 6.46%   |
| Broadcom                   | 19        | 5.34%   |
| TP-Link                    | 10        | 2.81%   |
| Ralink Technology          | 9         | 2.53%   |
| Qualcomm                   | 3         | 0.84%   |
| Microsoft                  | 3         | 0.84%   |
| Broadcom Limited           | 3         | 0.84%   |
| Texas Instruments          | 1         | 0.28%   |
| Ralink                     | 1         | 0.28%   |
| Quectel Wireless Solutions | 1         | 0.28%   |
| NetGear                    | 1         | 0.28%   |
| D-Link System              | 1         | 0.28%   |
| Belkin Components          | 1         | 0.28%   |
| ASUSTek Computer           | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 33        | 9.24%   |
| Intel Wireless 8265 / 8275                                              | 16        | 4.48%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 3.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 2.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 8         | 2.24%   |
| Intel Wireless 7265                                                     | 8         | 2.24%   |
| Intel Wireless 7260                                                     | 8         | 2.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.24%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 8         | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.96%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.96%   |
| Intel Wireless 8260                                                     | 7         | 1.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 1.96%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.4%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 5         | 1.4%    |
| Intel Raptor Lake PCH CNVi WiFi                                         | 5         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 0.84%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 3         | 0.84%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.84%   |
| Intel 700 Series Chipset Family Wi-Fi                                   | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 186       | 51.24%  |
| Intel                                  | 123       | 33.88%  |
| Qualcomm Atheros                       | 13        | 3.58%   |
| ASIX Electronics                       | 10        | 2.75%   |
| Broadcom                               | 9         | 2.48%   |
| Marvell Technology Group               | 3         | 0.83%   |
| Xiaomi                                 | 2         | 0.55%   |
| Lenovo                                 | 2         | 0.55%   |
| Huawei Technologies                    | 2         | 0.55%   |
| Broadcom Limited                       | 2         | 0.55%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.28%   |
| Samsung Electronics                    | 1         | 0.28%   |
| OPPO Electronics                       | 1         | 0.28%   |
| Nvidia                                 | 1         | 0.28%   |
| National Semiconductor                 | 1         | 0.28%   |
| ICS Advent                             | 1         | 0.28%   |
| Google                                 | 1         | 0.28%   |
| DisplayLink                            | 1         | 0.28%   |
| D-Link                                 | 1         | 0.28%   |
| Aquantia                               | 1         | 0.28%   |
| Apple                                  | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 132       | 35.39%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 5.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 4.02%   |
| Intel I211 Gigabit Network Connection                             | 14        | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.22%   |
| Intel Ethernet Controller I225-V                                  | 12        | 3.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 2.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 2.14%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.88%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.61%   |
| Intel I350 Gigabit Network Connection                             | 5         | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.34%   |
| Intel Ethernet Connection (11) I219-V                             | 4         | 1.07%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.07%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.07%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.54%   |
| Lenovo ThinkPad Lan                                               | 2         | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 0.54%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.54%   |
| Sony Ericsson Mobile AB XQ-CC54                                   | 1         | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.27%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 339       | 49.78%  |
| Ethernet | 334       | 49.05%  |
| Modem    | 5         | 0.73%   |
| Unknown  | 3         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 56.89%  |
| Ethernet | 194       | 43.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 213       | 49.88%  |
| 1     | 181       | 42.39%  |
| 0     | 18        | 4.22%   |
| 3     | 8         | 1.87%   |
| 4     | 5         | 1.17%   |
| 8     | 1         | 0.23%   |
| 7     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 410       | 96.47%  |
| Yes  | 15        | 3.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 176       | 60.48%  |
| Cambridge Silicon Radio         | 16        | 5.5%    |
| Foxconn / Hon Hai               | 15        | 5.15%   |
| Realtek Semiconductor           | 14        | 4.81%   |
| Broadcom                        | 13        | 4.47%   |
| Qualcomm Atheros Communications | 10        | 3.44%   |
| IMC Networks                    | 9         | 3.09%   |
| Apple                           | 8         | 2.75%   |
| MediaTek                        | 5         | 1.72%   |
| Lite-On Technology              | 5         | 1.72%   |
| Realtek                         | 3         | 1.03%   |
| Hewlett-Packard                 | 3         | 1.03%   |
| Foxconn International           | 3         | 1.03%   |
| Taiyo Yuden                     | 2         | 0.69%   |
| Dell                            | 2         | 0.69%   |
| ASUSTek Computer                | 2         | 0.69%   |
| TP-Link                         | 1         | 0.34%   |
| SINO WEALTH                     | 1         | 0.34%   |
| Micro Star International        | 1         | 0.34%   |
| Fujitsu                         | 1         | 0.34%   |
| Askey Computer                  | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 41        | 14.09%  |
| Intel AX201 Bluetooth                               | 38        | 13.06%  |
| Intel AX200 Bluetooth                               | 32        | 11%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 7.22%   |
| Intel Bluetooth Device                              | 19        | 6.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 5.5%    |
| Realtek Bluetooth Radio                             | 14        | 4.81%   |
| Intel AX210 Bluetooth                               | 11        | 3.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 3.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 3.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.06%   |
| MediaTek Wireless_Device                            | 5         | 1.72%   |
| IMC Networks Wireless_Device                        | 4         | 1.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.37%   |
| Realtek Bluetooth Radio                             | 3         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.03%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.03%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.03%   |
| Apple Bluetooth Host Controller                     | 3         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.69%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.69%   |
| IMC Networks Bluetooth Device                       | 2         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.69%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 2         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.69%   |
| ASUS Bluetooth Radio                                | 2         | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.69%   |
| TP-Link UB500 Adapter                               | 1         | 0.34%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.34%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.34%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.34%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.34%   |
| Micro Star International Bluetooth Dongle           | 1         | 0.34%   |
| Lite-On Bluetooth Radio                             | 1         | 0.34%   |
| Lite-On Bluetooth Device                            | 1         | 0.34%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.34%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 309       | 53.83%  |
| Nvidia                               | 113       | 19.69%  |
| AMD                                  | 106       | 18.47%  |
| C-Media Electronics                  | 12        | 2.09%   |
| Logitech                             | 3         | 0.52%   |
| FiiO Electronics Technology          | 3         | 0.52%   |
| ASUSTek Computer                     | 3         | 0.52%   |
| Generalplus Technology               | 2         | 0.35%   |
| Focusrite-Novation                   | 2         | 0.35%   |
| ESS Technology                       | 2         | 0.35%   |
| Creative Labs                        | 2         | 0.35%   |
| AudioQuest                           | 2         | 0.35%   |
| XMOS                                 | 1         | 0.17%   |
| Winbond Electronics                  | 1         | 0.17%   |
| VIA Technologies                     | 1         | 0.17%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.17%   |
| Texas Instruments                    | 1         | 0.17%   |
| Sony                                 | 1         | 0.17%   |
| SAVITECH                             | 1         | 0.17%   |
| Realtek Semiconductor                | 1         | 0.17%   |
| Micro Star International             | 1         | 0.17%   |
| Lynx                                 | 1         | 0.17%   |
| JMTek                                | 1         | 0.17%   |
| iCreate Technologies                 | 1         | 0.17%   |
| HECATE G4 TE GAMING HEADSET          | 1         | 0.17%   |
| Apple                                | 1         | 0.17%   |
| Anlya.cn                             | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 52        | 7.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 37        | 5.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 22        | 3.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 2.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 2.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 2.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 2.52%   |
| Intel Alder Lake-S HD Audio Controller                                     | 13        | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 1.93%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 1.48%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 1.48%   |
| Nvidia Audio device                                                        | 10        | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.48%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 1.48%   |
| Intel 200 Series PCH HD Audio                                              | 10        | 1.48%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10        | 1.48%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.19%   |
| Nvidia GM206 High Definition Audio Controller                              | 8         | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 8         | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 69        | 23.15%  |
| SK hynix                   | 56        | 18.79%  |
| Kingston                   | 38        | 12.75%  |
| Micron Technology          | 31        | 10.4%   |
| Unknown                    | 19        | 6.38%   |
| A-DATA Technology          | 14        | 4.7%    |
| Corsair                    | 13        | 4.36%   |
| Crucial                    | 12        | 4.03%   |
| Unknown                    | 8         | 2.68%   |
| Unknown (ABCD)             | 6         | 2.01%   |
| G.Skill                    | 5         | 1.68%   |
| Team                       | 4         | 1.34%   |
| Elpida                     | 4         | 1.34%   |
| Ramaxel Technology         | 3         | 1.01%   |
| Nanya Technology           | 2         | 0.67%   |
| Kingmax                    | 2         | 0.67%   |
| Unknown (0x0AFD)           | 1         | 0.34%   |
| Unknown (08C8)             | 1         | 0.34%   |
| Transcend                  | 1         | 0.34%   |
| tigo                       | 1         | 0.34%   |
| Shenzhen Jinge Information | 1         | 0.34%   |
| Lenovo                     | 1         | 0.34%   |
| Juhor                      | 1         | 0.34%   |
| GLOWAY                     | 1         | 0.34%   |
| Essencore Limited          | 1         | 0.34%   |
| CUSO                       | 1         | 0.34%   |
| ChangXin Memory            | 1         | 0.34%   |
| Apacer                     | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 8         | 2.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.27%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 3         | 0.95%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.95%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 3         | 0.95%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.63%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 2         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 2         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.63%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.63%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.63%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.63%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 2         | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.63%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 2         | 0.63%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.63%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.63%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.63%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 2         | 0.63%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 0.63%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.63%   |
| Crucial RAM CT16G4SFS832A.C8FB 16GB SODIMM DDR4 3200MT/s         | 2         | 0.63%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s            | 2         | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 2         | 0.63%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s           | 2         | 0.63%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 0.63%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.32%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.32%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.32%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 132       | 50%     |
| DDR3    | 48        | 18.18%  |
| LPDDR4  | 19        | 7.2%    |
| DDR5    | 16        | 6.06%   |
| LPDDR3  | 14        | 5.3%    |
| LPDDR5  | 10        | 3.79%   |
| DDR2    | 10        | 3.79%   |
| Unknown | 6         | 2.27%   |
| SDRAM   | 5         | 1.89%   |
| DRAM    | 3         | 1.14%   |
| DDR     | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 124       | 46.79%  |
| DIMM         | 96        | 36.23%  |
| Row Of Chips | 43        | 16.23%  |
| Unknown      | 2         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 98        | 34.51%  |
| 16384 | 63        | 22.18%  |
| 4096  | 58        | 20.42%  |
| 32768 | 28        | 9.86%   |
| 2048  | 24        | 8.45%   |
| 1024  | 7         | 2.46%   |
| 256   | 2         | 0.7%    |
| 64    | 2         | 0.7%    |
| 512   | 1         | 0.35%   |
| 232   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 49        | 17.69%  |
| 2667    | 42        | 15.16%  |
| 1600    | 37        | 13.36%  |
| 2400    | 19        | 6.86%   |
| 2133    | 18        | 6.5%    |
| 4800    | 11        | 3.97%   |
| 1333    | 10        | 3.61%   |
| 6400    | 9         | 3.25%   |
| 4267    | 8         | 2.89%   |
| 3600    | 8         | 2.89%   |
| 2666    | 7         | 2.53%   |
| Unknown | 6         | 2.17%   |
| 5600    | 5         | 1.81%   |
| 1867    | 5         | 1.81%   |
| 3266    | 4         | 1.44%   |
| 3000    | 4         | 1.44%   |
| 667     | 4         | 1.44%   |
| 800     | 3         | 1.08%   |
| 3733    | 2         | 0.72%   |
| 3533    | 2         | 0.72%   |
| 1334    | 2         | 0.72%   |
| 533     | 2         | 0.72%   |
| 200     | 2         | 0.72%   |
| 8400    | 1         | 0.36%   |
| 7467    | 1         | 0.36%   |
| 7000    | 1         | 0.36%   |
| 5808    | 1         | 0.36%   |
| 4266    | 1         | 0.36%   |
| 4199    | 1         | 0.36%   |
| 3933    | 1         | 0.36%   |
| 3866    | 1         | 0.36%   |
| 3800    | 1         | 0.36%   |
| 3466    | 1         | 0.36%   |
| 3007    | 1         | 0.36%   |
| 2933    | 1         | 0.36%   |
| 1866    | 1         | 0.36%   |
| 1800    | 1         | 0.36%   |
| 1067    | 1         | 0.36%   |
| 1066    | 1         | 0.36%   |
| 975     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xiaomi             | 1         | 20%     |
| Hewlett-Packard    | 1         | 20%     |
| Fuji Xerox         | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Xiaomi MiMouse 2            | 1         | 20%     |
| HP LaserJet P2035           | 1         | 20%     |
| Fuji Xerox DocuPrint P158 b | 1         | 20%     |
| Canon MP160                 | 1         | 20%     |
| Brother HL-L2320D series    | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 20.55%  |
| IMC Networks                           | 20        | 9.13%   |
| Microdia                               | 16        | 7.31%   |
| Bison Electronics                      | 16        | 7.31%   |
| Realtek Semiconductor                  | 11        | 5.02%   |
| Luxvisions Innotech Limited            | 11        | 5.02%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 5.02%   |
| Logitech                               | 10        | 4.57%   |
| Sunplus Innovation Technology          | 8         | 3.65%   |
| Syntek                                 | 7         | 3.2%    |
| Apple                                  | 7         | 3.2%    |
| Quanta                                 | 6         | 2.74%   |
| Acer                                   | 5         | 2.28%   |
| Silicon Motion                         | 4         | 1.83%   |
| Suyin                                  | 3         | 1.37%   |
| Sonix Technology                       | 3         | 1.37%   |
| Alcor Micro                            | 3         | 1.37%   |
| Tripath Technology                     | 2         | 0.91%   |
| SN0002                                 | 2         | 0.91%   |
| Lite-On Technology                     | 2         | 0.91%   |
| Importek                               | 2         | 0.91%   |
| eMPIA Technology                       | 2         | 0.91%   |
| Cubeternet                             | 2         | 0.91%   |
| Z-Star Microelectronics                | 1         | 0.46%   |
| Xiaomi                                 | 1         | 0.46%   |
| WaveRider Communications               | 1         | 0.46%   |
| Shinetech                              | 1         | 0.46%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.46%   |
| Ricoh                                  | 1         | 0.46%   |
| Primax Electronics                     | 1         | 0.46%   |
| Nokia Mobile Phones                    | 1         | 0.46%   |
| Nebraska Furniture Mart                | 1         | 0.46%   |
| Microsoft                              | 1         | 0.46%   |
| lihappe8                               | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| kingcome                               | 1         | 0.46%   |
| icSpring                               | 1         | 0.46%   |
| Hopewin Electronic Material            | 1         | 0.46%   |
| Google                                 | 1         | 0.46%   |
| Genesys Logic                          | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 18        | 8.11%   |
| IMC Networks Integrated Camera                                             | 10        | 4.5%    |
| Microdia Integrated_Webcam_HD                                              | 9         | 4.05%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 6         | 2.7%    |
| Syntek Integrated Camera                                                   | 5         | 2.25%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.25%   |
| Chicony HD WebCam                                                          | 5         | 2.25%   |
| Chicony FJ Camera                                                          | 5         | 2.25%   |
| Bison Integrated Camera                                                    | 5         | 2.25%   |
| Logitech Webcam C270                                                       | 4         | 1.8%    |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 1.8%    |
| Acer Integrated Camera                                                     | 4         | 1.8%    |
| Luxvisions Innotech Limited HP HD Camera                                   | 3         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 3         | 1.35%   |
| Bison Lenovo EasyCamera                                                    | 3         | 1.35%   |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 1.35%   |
| Tripath PC Camera                                                          | 2         | 0.9%    |
| Sonix USB2.0 FHD UVC WebCam                                                | 2         | 0.9%    |
| SN0002 2K USB Camera                                                       | 2         | 0.9%    |
| Realtek USB Camera                                                         | 2         | 0.9%    |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 2         | 0.9%    |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.9%    |
| Logitech B525 HD Webcam                                                    | 2         | 0.9%    |
| Lite-On Integrated Camera                                                  | 2         | 0.9%    |
| Importek FJ Camera                                                         | 2         | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 0.9%    |
| Chicony Integrated IR Camera                                               | 2         | 0.9%    |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 0.9%    |
| Bison SunplusIT Integrated Camera                                          | 2         | 0.9%    |
| Bison BisonCam,NB Pro                                                      | 2         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 0.9%    |
| Z-Star Sirius USB2.0 Camera                                                | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                                         | 1         | 0.45%   |
| WaveRider USB 2.0 Camera                                                   | 1         | 0.45%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.45%   |
| Syntek EasyCamera                                                          | 1         | 0.45%   |
| Suyin Integrated Webcam                                                    | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 20        | 40.82%  |
| Validity Sensors           | 9         | 18.37%  |
| Shenzhen Goodix Technology | 9         | 18.37%  |
| AuthenTec                  | 4         | 8.16%   |
| Upek                       | 3         | 6.12%   |
| Samsung Electronics        | 2         | 4.08%   |
| LighTuning Technology      | 2         | 4.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader       | 8         | 16.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 10.2%   |
| Validity Sensors Synaptics WBDI                        | 4         | 8.16%   |
| Shenzhen Goodix  Fingerprint Device                    | 4         | 8.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 6.12%   |
| Shenzhen Goodix FingerPrint                            | 3         | 6.12%   |
| Synaptics WBDI                                         | 2         | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 4.08%   |
| AuthenTec Fingerprint Sensor                           | 2         | 4.08%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.04%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.04%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.04%   |
| Synaptics UWP WBDI Device                              | 1         | 2.04%   |
| Synaptics UWP WBDI                                     | 1         | 2.04%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1         | 2.04%   |
| Synaptics  WBDI                                        | 1         | 2.04%   |
| Samsung Fingerprint Sensor Device - 730B               | 1         | 2.04%   |
| Samsung Fingerprint Device                             | 1         | 2.04%   |
| Unknown                                                | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 27.78%  |
| Upek                  | 4         | 22.22%  |
| Advanced Card Systems | 3         | 16.67%  |
| Lenovo                | 2         | 11.11%  |
| Alcor Micro           | 2         | 11.11%  |
| Yubico.com            | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 22.22%  |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 3         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 11.11%  |
| Broadcom 5880                                                                | 2         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 11.11%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 288       | 66.21%  |
| 1     | 112       | 25.75%  |
| 2     | 23        | 5.29%   |
| 3     | 6         | 1.38%   |
| 4     | 4         | 0.92%   |
| 5     | 2         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 45        | 23.32%  |
| Fingerprint reader       | 45        | 23.32%  |
| Net/wireless             | 25        | 12.95%  |
| Multimedia controller    | 18        | 9.33%   |
| Communication controller | 16        | 8.29%   |
| Chipcard                 | 16        | 8.29%   |
| Camera                   | 6         | 3.11%   |
| Unassigned class         | 5         | 2.59%   |
| Sound                    | 4         | 2.07%   |
| Bluetooth                | 4         | 2.07%   |
| Storage                  | 2         | 1.04%   |
| Net/ethernet             | 2         | 1.04%   |
| Card reader              | 2         | 1.04%   |
| Storage/raid             | 1         | 0.52%   |
| Storage/ata              | 1         | 0.52%   |
| Network                  | 1         | 0.52%   |

