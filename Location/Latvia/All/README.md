Linux in Latvia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Latvia/Desktop/README.md) and [notebooks](/Location/Latvia/Notebook/README.md).

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

Total: 746

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 5750G                | Notebook    | [9c51173486](https://linux-hardware.org/?probe=9c51173486) | Jan 02, 2026 |
| Acer          | Aspire 5750G                | Notebook    | [118f3a1d96](https://linux-hardware.org/?probe=118f3a1d96) | Jan 02, 2026 |
| Gigabyte      | B85M-D3H                    | Desktop     | [14b591528c](https://linux-hardware.org/?probe=14b591528c) | Dec 29, 2025 |
| Acer          | Aspire 5750G                | Notebook    | [7e26321ea2](https://linux-hardware.org/?probe=7e26321ea2) | Dec 28, 2025 |
| ASRock        | B650M-H/M.2+ WiFi           | Desktop     | [cc16ae3bde](https://linux-hardware.org/?probe=cc16ae3bde) | Dec 24, 2025 |
| HP            | 15                          | Notebook    | [3e11bcc056](https://linux-hardware.org/?probe=3e11bcc056) | Dec 23, 2025 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [0796e298e6](https://linux-hardware.org/?probe=0796e298e6) | Dec 19, 2025 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | Notebook    | [305cba68c0](https://linux-hardware.org/?probe=305cba68c0) | Dec 12, 2025 |
| ASRock        | B450M/ac R2.0               | Desktop     | [6f49fcddc4](https://linux-hardware.org/?probe=6f49fcddc4) | Dec 07, 2025 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [51c2f99db8](https://linux-hardware.org/?probe=51c2f99db8) | Dec 06, 2025 |
| GMKtec        | NucBox K8                   | Mini pc     | [2f44a60ba7](https://linux-hardware.org/?probe=2f44a60ba7) | Dec 01, 2025 |
| Gigabyte      | H610M H DDR4                | Desktop     | [bd47172ed6](https://linux-hardware.org/?probe=bd47172ed6) | Nov 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b750fafd03](https://linux-hardware.org/?probe=b750fafd03) | Nov 28, 2025 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [367cf5b828](https://linux-hardware.org/?probe=367cf5b828) | Nov 23, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c94445cd5c](https://linux-hardware.org/?probe=c94445cd5c) | Nov 19, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7e8b87ad3e](https://linux-hardware.org/?probe=7e8b87ad3e) | Nov 13, 2025 |
| Dell          | 0DR845                      | Desktop     | [28c91f5307](https://linux-hardware.org/?probe=28c91f5307) | Nov 10, 2025 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [17dc001954](https://linux-hardware.org/?probe=17dc001954) | Nov 08, 2025 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [33099b6a91](https://linux-hardware.org/?probe=33099b6a91) | Nov 05, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [885235042c](https://linux-hardware.org/?probe=885235042c) | Oct 31, 2025 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [669bfef40a](https://linux-hardware.org/?probe=669bfef40a) | Oct 25, 2025 |
| Lenovo        | B50-30 80ES                 | Notebook    | [c4440ffc20](https://linux-hardware.org/?probe=c4440ffc20) | Oct 22, 2025 |
| eMachines     | eME732ZG                    | Notebook    | [9bf289be10](https://linux-hardware.org/?probe=9bf289be10) | Oct 21, 2025 |
| Hardkernel    | ODROID-N2                   | Soc         | [97183c7cfd](https://linux-hardware.org/?probe=97183c7cfd) | Oct 11, 2025 |
| Wortmann      | CR700                       | Notebook    | [a5334d477f](https://linux-hardware.org/?probe=a5334d477f) | Oct 09, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [093709474e](https://linux-hardware.org/?probe=093709474e) | Oct 07, 2025 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [9899d172db](https://linux-hardware.org/?probe=9899d172db) | Oct 05, 2025 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [dec122256d](https://linux-hardware.org/?probe=dec122256d) | Oct 02, 2025 |
| ASUSTek       | Q302LAB                     | Notebook    | [38491c798c](https://linux-hardware.org/?probe=38491c798c) | Sep 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e300266057](https://linux-hardware.org/?probe=e300266057) | Sep 15, 2025 |
| Gigabyte      | Z87-HD3                     | Desktop     | [42956eee0f](https://linux-hardware.org/?probe=42956eee0f) | Sep 01, 2025 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c73f420fda](https://linux-hardware.org/?probe=c73f420fda) | Aug 31, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [0316bf2081](https://linux-hardware.org/?probe=0316bf2081) | Aug 30, 2025 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [5c018c4f36](https://linux-hardware.org/?probe=5c018c4f36) | Aug 29, 2025 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [3c6021fdb6](https://linux-hardware.org/?probe=3c6021fdb6) | Aug 26, 2025 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [ee4d76641e](https://linux-hardware.org/?probe=ee4d76641e) | Aug 21, 2025 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [5d8f6578ef](https://linux-hardware.org/?probe=5d8f6578ef) | Aug 18, 2025 |
| MSI           | MS-B1831                    | Desktop     | [bde9c9eb55](https://linux-hardware.org/?probe=bde9c9eb55) | Aug 07, 2025 |
| Toshiba       | Satellite C660              | Notebook    | [018c620eaf](https://linux-hardware.org/?probe=018c620eaf) | Aug 04, 2025 |
| ASUSTek       | K55A                        | Notebook    | [2d0252f673](https://linux-hardware.org/?probe=2d0252f673) | Aug 01, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f31f866db9](https://linux-hardware.org/?probe=f31f866db9) | Jul 27, 2025 |
| MSI           | PRO B650-S WIFI             | Desktop     | [d65bae84e5](https://linux-hardware.org/?probe=d65bae84e5) | Jul 21, 2025 |
| Wortmann      | CR700                       | Notebook    | [bfcf41b931](https://linux-hardware.org/?probe=bfcf41b931) | Jul 20, 2025 |
| Gigabyte      | Z87-HD3                     | Desktop     | [fd3c126462](https://linux-hardware.org/?probe=fd3c126462) | Jul 16, 2025 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [c51eb911e6](https://linux-hardware.org/?probe=c51eb911e6) | Jul 08, 2025 |
| Gigabyte      | G33M-S2                     | Desktop     | [52ba2940e8](https://linux-hardware.org/?probe=52ba2940e8) | Jul 02, 2025 |
| Lenovo        | ThinkPad X280 20KES9Y100    | Notebook    | [38c8a6b24b](https://linux-hardware.org/?probe=38c8a6b24b) | Jul 01, 2025 |
| Dell          | Pro 13 Premium PA13250      | Notebook    | [b50588b911](https://linux-hardware.org/?probe=b50588b911) | Jul 01, 2025 |
| MSI           | MS-AE111 100                | All in one  | [5274877461](https://linux-hardware.org/?probe=5274877461) | Jun 30, 2025 |
| MSI           | MS-AE111 100                | All in one  | [a1ad0dcaf0](https://linux-hardware.org/?probe=a1ad0dcaf0) | Jun 30, 2025 |
| Gigabyte      | Z87-HD3                     | Desktop     | [eb9d8cc1af](https://linux-hardware.org/?probe=eb9d8cc1af) | Jun 24, 2025 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [e024f2b9bf](https://linux-hardware.org/?probe=e024f2b9bf) | Jun 18, 2025 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [a18c0863f9](https://linux-hardware.org/?probe=a18c0863f9) | Jun 17, 2025 |
| Gigabyte      | Z87-HD3                     | Desktop     | [b98c194131](https://linux-hardware.org/?probe=b98c194131) | Jun 17, 2025 |
| Amentmen      | X99-A4-B V6.1               | Desktop     | [2196799925](https://linux-hardware.org/?probe=2196799925) | Jun 17, 2025 |
| Gigabyte      | G33M-S2                     | Desktop     | [6652eebf6e](https://linux-hardware.org/?probe=6652eebf6e) | Jun 17, 2025 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [0a28426cb5](https://linux-hardware.org/?probe=0a28426cb5) | Jun 17, 2025 |
| Gigabyte      | PA65-UD3-B3                 | Desktop     | [cabd8fffc7](https://linux-hardware.org/?probe=cabd8fffc7) | Jun 15, 2025 |
| Dell          | Pro 13 Premium PA13250      | Notebook    | [d5a629d5fe](https://linux-hardware.org/?probe=d5a629d5fe) | Jun 12, 2025 |
| Gigabyte      | H97M-HD3                    | Desktop     | [fbb6ccee12](https://linux-hardware.org/?probe=fbb6ccee12) | Jun 10, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M30... | Notebook    | [d589daa890](https://linux-hardware.org/?probe=d589daa890) | Jun 03, 2025 |
| Gigabyte      | H97M-HD3                    | Desktop     | [e50a3f02d8](https://linux-hardware.org/?probe=e50a3f02d8) | May 29, 2025 |
| Gigabyte      | H97M-HD3                    | Desktop     | [cebf0e792a](https://linux-hardware.org/?probe=cebf0e792a) | May 25, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [dd5cd37d09](https://linux-hardware.org/?probe=dd5cd37d09) | May 17, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [88e89b6853](https://linux-hardware.org/?probe=88e89b6853) | May 17, 2025 |
| Wortmann      | CR700                       | Notebook    | [0bf87a4a34](https://linux-hardware.org/?probe=0bf87a4a34) | May 15, 2025 |
| Apple         | MacBookPro10,2              | Notebook    | [a5c84e68ed](https://linux-hardware.org/?probe=a5c84e68ed) | May 03, 2025 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [a90e40e113](https://linux-hardware.org/?probe=a90e40e113) | May 02, 2025 |
| HP            | Pavilion g6                 | Notebook    | [69d4a56750](https://linux-hardware.org/?probe=69d4a56750) | May 02, 2025 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [acf76d2820](https://linux-hardware.org/?probe=acf76d2820) | Apr 28, 2025 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [83d3076e92](https://linux-hardware.org/?probe=83d3076e92) | Apr 26, 2025 |
| Unknown       | Unknown                     | Soc         | [c33ba95153](https://linux-hardware.org/?probe=c33ba95153) | Apr 23, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0cc3bd3408](https://linux-hardware.org/?probe=0cc3bd3408) | Apr 20, 2025 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [3e8feff1c3](https://linux-hardware.org/?probe=3e8feff1c3) | Apr 20, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [bca325fe54](https://linux-hardware.org/?probe=bca325fe54) | Apr 19, 2025 |
| ASRock        | B450M Pro4                  | Desktop     | [f24f404ff7](https://linux-hardware.org/?probe=f24f404ff7) | Apr 19, 2025 |
| Dell          | Latitude 7450               | Notebook    | [b776729c52](https://linux-hardware.org/?probe=b776729c52) | Apr 14, 2025 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [ae517862d8](https://linux-hardware.org/?probe=ae517862d8) | Apr 13, 2025 |
| Dell          | Precision 5520              | Notebook    | [02d34a0c00](https://linux-hardware.org/?probe=02d34a0c00) | Apr 11, 2025 |
| Dell          | Precision 5520              | Notebook    | [473a105ac5](https://linux-hardware.org/?probe=473a105ac5) | Apr 11, 2025 |
| Lenovo        | ThinkPad T480 20L6S23900    | Notebook    | [59d403bbc9](https://linux-hardware.org/?probe=59d403bbc9) | Mar 27, 2025 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d3e5417e61](https://linux-hardware.org/?probe=d3e5417e61) | Mar 23, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [50da8df3b4](https://linux-hardware.org/?probe=50da8df3b4) | Mar 17, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [e8f8d2379d](https://linux-hardware.org/?probe=e8f8d2379d) | Mar 17, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [7365fabcc5](https://linux-hardware.org/?probe=7365fabcc5) | Mar 14, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [9024dae4cc](https://linux-hardware.org/?probe=9024dae4cc) | Mar 14, 2025 |
| Lenovo        | ThinkPad L450 20DT0003MH    | Notebook    | [c5b3a3935b](https://linux-hardware.org/?probe=c5b3a3935b) | Mar 13, 2025 |
| Gigabyte      | H97M-HD3                    | Desktop     | [74513aa704](https://linux-hardware.org/?probe=74513aa704) | Mar 12, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [49bbb4dce0](https://linux-hardware.org/?probe=49bbb4dce0) | Mar 11, 2025 |
| ASRock        | D1800B-ITX                  | Desktop     | [9848b27e2e](https://linux-hardware.org/?probe=9848b27e2e) | Mar 09, 2025 |
| ASRock        | D1800B-ITX                  | Desktop     | [2365183934](https://linux-hardware.org/?probe=2365183934) | Mar 09, 2025 |
| Wortmann      | CR700                       | Notebook    | [e616fb7387](https://linux-hardware.org/?probe=e616fb7387) | Mar 08, 2025 |
| ASUSTek       | H97M-E                      | Desktop     | [c9c4b49789](https://linux-hardware.org/?probe=c9c4b49789) | Feb 27, 2025 |
| Lenovo        | ThinkPad T480 20L6S23900    | Notebook    | [f177b856bc](https://linux-hardware.org/?probe=f177b856bc) | Feb 25, 2025 |
| Dell          | Vostro 3525                 | Notebook    | [40f9e4d2fa](https://linux-hardware.org/?probe=40f9e4d2fa) | Feb 14, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [a425dfd97b](https://linux-hardware.org/?probe=a425dfd97b) | Feb 05, 2025 |
| Dell          | Latitude 7450               | Notebook    | [77f7d60121](https://linux-hardware.org/?probe=77f7d60121) | Feb 05, 2025 |
| ASRock        | Z97M Pro4                   | Desktop     | [2f3c0a3f43](https://linux-hardware.org/?probe=2f3c0a3f43) | Feb 01, 2025 |
| Dell          | Latitude 7450               | Notebook    | [803349d056](https://linux-hardware.org/?probe=803349d056) | Jan 15, 2025 |
| Apple         | MacBookPro9,1               | Notebook    | [061cbd2eda](https://linux-hardware.org/?probe=061cbd2eda) | Jan 12, 2025 |
| Dell          | Latitude E6320              | Notebook    | [3baff0aea1](https://linux-hardware.org/?probe=3baff0aea1) | Jan 11, 2025 |
| Dell          | Latitude E6320              | Notebook    | [01561cb356](https://linux-hardware.org/?probe=01561cb356) | Jan 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [2be9a5ca1c](https://linux-hardware.org/?probe=2be9a5ca1c) | Jan 05, 2025 |
| HP            | Compaq Presario CQ56        | Notebook    | [3365fbb5bc](https://linux-hardware.org/?probe=3365fbb5bc) | Jan 04, 2025 |
| Dell          | 02C2CP A03                  | Server      | [44126f8d86](https://linux-hardware.org/?probe=44126f8d86) | Dec 31, 2024 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f2bb2bd6da](https://linux-hardware.org/?probe=f2bb2bd6da) | Dec 30, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [d824794995](https://linux-hardware.org/?probe=d824794995) | Dec 23, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [9e9a469284](https://linux-hardware.org/?probe=9e9a469284) | Dec 20, 2024 |
| MSI           | MPG X870E CARBON WIFI       | Desktop     | [5a55b1482a](https://linux-hardware.org/?probe=5a55b1482a) | Dec 17, 2024 |
| Biostar       | B550MX/E PRO                | Desktop     | [30e7b6d1fa](https://linux-hardware.org/?probe=30e7b6d1fa) | Dec 12, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [3f5e65f8fc](https://linux-hardware.org/?probe=3f5e65f8fc) | Dec 08, 2024 |
| Dell          | Vostro 3525                 | Notebook    | [ca69855de4](https://linux-hardware.org/?probe=ca69855de4) | Dec 06, 2024 |
| Sony          | VPCEE4E1E                   | Notebook    | [a859b089fd](https://linux-hardware.org/?probe=a859b089fd) | Dec 02, 2024 |
| Dell          | Vostro 3525                 | Notebook    | [e4ebed04a3](https://linux-hardware.org/?probe=e4ebed04a3) | Nov 30, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [8e09c4ddbe](https://linux-hardware.org/?probe=8e09c4ddbe) | Nov 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [45fd5080cc](https://linux-hardware.org/?probe=45fd5080cc) | Nov 26, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6a961e6e3e](https://linux-hardware.org/?probe=6a961e6e3e) | Nov 23, 2024 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [107d02aac0](https://linux-hardware.org/?probe=107d02aac0) | Nov 12, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [616f53f4b7](https://linux-hardware.org/?probe=616f53f4b7) | Nov 01, 2024 |
| Gigabyte      | B360M-D3P-WG-CF             | Desktop     | [221fc17cd6](https://linux-hardware.org/?probe=221fc17cd6) | Oct 29, 2024 |
| Wortmann      | CR700                       | Notebook    | [0e6bd50e12](https://linux-hardware.org/?probe=0e6bd50e12) | Oct 27, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [855f0534c1](https://linux-hardware.org/?probe=855f0534c1) | Oct 22, 2024 |
| Valve         | Galileo                     | Notebook    | [df3b9380db](https://linux-hardware.org/?probe=df3b9380db) | Oct 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [1e9a7618df](https://linux-hardware.org/?probe=1e9a7618df) | Oct 01, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [39053cddd2](https://linux-hardware.org/?probe=39053cddd2) | Sep 29, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [037b72296e](https://linux-hardware.org/?probe=037b72296e) | Sep 29, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [e3ebc39bd6](https://linux-hardware.org/?probe=e3ebc39bd6) | Sep 26, 2024 |
| Wortmann      | CR700                       | Notebook    | [3fade1540e](https://linux-hardware.org/?probe=3fade1540e) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [a6b9e47c58](https://linux-hardware.org/?probe=a6b9e47c58) | Sep 13, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [032a7cae6f](https://linux-hardware.org/?probe=032a7cae6f) | Sep 09, 2024 |
| Dell          | System XPS L502X            | Notebook    | [7d1efcbe6a](https://linux-hardware.org/?probe=7d1efcbe6a) | Sep 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [472ba394b6](https://linux-hardware.org/?probe=472ba394b6) | Sep 02, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [f44ffefe98](https://linux-hardware.org/?probe=f44ffefe98) | Aug 24, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [a5f30f105b](https://linux-hardware.org/?probe=a5f30f105b) | Aug 20, 2024 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [7f7717743d](https://linux-hardware.org/?probe=7f7717743d) | Aug 08, 2024 |
| MSI           | Stealth 16 AI Studio A1V... | Notebook    | [3a5fc2d641](https://linux-hardware.org/?probe=3a5fc2d641) | Aug 07, 2024 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [356a623cc0](https://linux-hardware.org/?probe=356a623cc0) | Aug 05, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [f994ec5854](https://linux-hardware.org/?probe=f994ec5854) | Aug 01, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bce7bed769](https://linux-hardware.org/?probe=bce7bed769) | Jul 31, 2024 |
| Valve         | Galileo                     | Notebook    | [c62dd4aca9](https://linux-hardware.org/?probe=c62dd4aca9) | Jul 29, 2024 |
| Valve         | Galileo                     | Notebook    | [f4a8db2e5f](https://linux-hardware.org/?probe=f4a8db2e5f) | Jul 29, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [ad50fcf9b4](https://linux-hardware.org/?probe=ad50fcf9b4) | Jul 25, 2024 |
| Gigabyte      | H410M S2                    | Desktop     | [41aa39c9f1](https://linux-hardware.org/?probe=41aa39c9f1) | Jul 15, 2024 |
| Lenovo        | Unknown                     | Notebook    | [556b32d378](https://linux-hardware.org/?probe=556b32d378) | Jul 15, 2024 |
| Gigabyte      | Z87-HD3                     | Desktop     | [fb68936c67](https://linux-hardware.org/?probe=fb68936c67) | Jul 12, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [f381bc43a0](https://linux-hardware.org/?probe=f381bc43a0) | Jul 05, 2024 |
| Gigabyte      | G33M-S2                     | Desktop     | [56fa3abc84](https://linux-hardware.org/?probe=56fa3abc84) | Jul 04, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [e70a20fd46](https://linux-hardware.org/?probe=e70a20fd46) | Jul 01, 2024 |
| Wortmann      | CR700                       | Notebook    | [638b1918fb](https://linux-hardware.org/?probe=638b1918fb) | Jul 01, 2024 |
| Biostar       | H81MHV3                     | Desktop     | [f4fbb470c2](https://linux-hardware.org/?probe=f4fbb470c2) | Jun 22, 2024 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [b01bbdb3a1](https://linux-hardware.org/?probe=b01bbdb3a1) | Jun 22, 2024 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [1db6414aba](https://linux-hardware.org/?probe=1db6414aba) | Jun 16, 2024 |
| HP            | 873E MVB                    | Server      | [b77ecb9d84](https://linux-hardware.org/?probe=b77ecb9d84) | Jun 12, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c957fc0c93](https://linux-hardware.org/?probe=c957fc0c93) | Jun 03, 2024 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [a0d3b25d66](https://linux-hardware.org/?probe=a0d3b25d66) | Jun 01, 2024 |
| Lenovo        | ThinkPad T500 20827MG       | Notebook    | [812523cb5e](https://linux-hardware.org/?probe=812523cb5e) | May 29, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1e579e7bc9](https://linux-hardware.org/?probe=1e579e7bc9) | May 22, 2024 |
| Wortmann      | CR700                       | Notebook    | [695f76d8f3](https://linux-hardware.org/?probe=695f76d8f3) | May 12, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [24cf77eb91](https://linux-hardware.org/?probe=24cf77eb91) | May 07, 2024 |
| ASRock        | X79 Extreme9                | Desktop     | [a65acf43f1](https://linux-hardware.org/?probe=a65acf43f1) | May 06, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [c445ea85c4](https://linux-hardware.org/?probe=c445ea85c4) | May 02, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [9318ac5f47](https://linux-hardware.org/?probe=9318ac5f47) | Apr 30, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [8ae1401a90](https://linux-hardware.org/?probe=8ae1401a90) | Apr 14, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [23ea4a0287](https://linux-hardware.org/?probe=23ea4a0287) | Apr 09, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [0f5bd53c6f](https://linux-hardware.org/?probe=0f5bd53c6f) | Apr 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [a2dd90b9c9](https://linux-hardware.org/?probe=a2dd90b9c9) | Apr 07, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [b3f083db5c](https://linux-hardware.org/?probe=b3f083db5c) | Apr 06, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [0855016a44](https://linux-hardware.org/?probe=0855016a44) | Apr 01, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [79c408e0e7](https://linux-hardware.org/?probe=79c408e0e7) | Mar 30, 2024 |
| Wortmann      | CR700                       | Notebook    | [e8bf0a5a61](https://linux-hardware.org/?probe=e8bf0a5a61) | Mar 27, 2024 |
| ASUSTek       | X55A                        | Notebook    | [9631a046b9](https://linux-hardware.org/?probe=9631a046b9) | Mar 19, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [5912d4041d](https://linux-hardware.org/?probe=5912d4041d) | Mar 16, 2024 |
| ASUSTek       | X55A                        | Notebook    | [c37422f48f](https://linux-hardware.org/?probe=c37422f48f) | Mar 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [e655e5c1da](https://linux-hardware.org/?probe=e655e5c1da) | Mar 11, 2024 |
| Dell          | Latitude E6500              | Notebook    | [0c10bab3da](https://linux-hardware.org/?probe=0c10bab3da) | Mar 10, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [0c55a3dc95](https://linux-hardware.org/?probe=0c55a3dc95) | Mar 10, 2024 |
| Acer          | Aspire 5730                 | Notebook    | [cba983dfb3](https://linux-hardware.org/?probe=cba983dfb3) | Mar 08, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [856ce9544e](https://linux-hardware.org/?probe=856ce9544e) | Mar 07, 2024 |
| Wortmann      | CR700                       | Notebook    | [faed1b3618](https://linux-hardware.org/?probe=faed1b3618) | Mar 06, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [606e8cea6a](https://linux-hardware.org/?probe=606e8cea6a) | Mar 02, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [88ca3f1029](https://linux-hardware.org/?probe=88ca3f1029) | Feb 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [8b5831baf8](https://linux-hardware.org/?probe=8b5831baf8) | Feb 15, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [833f48af30](https://linux-hardware.org/?probe=833f48af30) | Feb 12, 2024 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [b30121b1f1](https://linux-hardware.org/?probe=b30121b1f1) | Feb 11, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [bc1e6e90c1](https://linux-hardware.org/?probe=bc1e6e90c1) | Feb 10, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [0c1b63b275](https://linux-hardware.org/?probe=0c1b63b275) | Feb 10, 2024 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [49efdd6436](https://linux-hardware.org/?probe=49efdd6436) | Feb 08, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [12e32cbc19](https://linux-hardware.org/?probe=12e32cbc19) | Jan 19, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| HP            | 8055                        | Desktop     | [ee3ece9007](https://linux-hardware.org/?probe=ee3ece9007) | Jan 05, 2024 |
| Dell          | Precision M4800             | Notebook    | [47508330f1](https://linux-hardware.org/?probe=47508330f1) | Dec 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [552bc11608](https://linux-hardware.org/?probe=552bc11608) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [84d4572994](https://linux-hardware.org/?probe=84d4572994) | Dec 12, 2023 |
| MSI           | H61M-E33                    | Desktop     | [ed1dc1d923](https://linux-hardware.org/?probe=ed1dc1d923) | Dec 09, 2023 |
| MSI           | Katana GF76 12UC            | Notebook    | [6667f9e88d](https://linux-hardware.org/?probe=6667f9e88d) | Dec 08, 2023 |
| HP            | ProBook 450 G0              | Notebook    | [80f6017066](https://linux-hardware.org/?probe=80f6017066) | Dec 04, 2023 |
| Biostar       | B450MH                      | Desktop     | [e490dfb129](https://linux-hardware.org/?probe=e490dfb129) | Dec 02, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [68c7c96b9b](https://linux-hardware.org/?probe=68c7c96b9b) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ce86d3d6](https://linux-hardware.org/?probe=76ce86d3d6) | Nov 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [43d1c51e23](https://linux-hardware.org/?probe=43d1c51e23) | Nov 17, 2023 |
| Wortmann      | CR700                       | Notebook    | [0c5f9ff4c6](https://linux-hardware.org/?probe=0c5f9ff4c6) | Nov 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [dc40a2bbb1](https://linux-hardware.org/?probe=dc40a2bbb1) | Nov 10, 2023 |
| Wortmann      | CR700                       | Notebook    | [45ed4d1320](https://linux-hardware.org/?probe=45ed4d1320) | Nov 07, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS2... | Convertible | [04a6b532f4](https://linux-hardware.org/?probe=04a6b532f4) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| Wortmann      | CR700                       | Notebook    | [916c9bceda](https://linux-hardware.org/?probe=916c9bceda) | Oct 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [75cbcab213](https://linux-hardware.org/?probe=75cbcab213) | Oct 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| MSI           | Katana GF76 11UE            | Notebook    | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [feffc725af](https://linux-hardware.org/?probe=feffc725af) | Sep 23, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [0d897e53cf](https://linux-hardware.org/?probe=0d897e53cf) | Sep 21, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | Notebook    | [432c1d0b94](https://linux-hardware.org/?probe=432c1d0b94) | Sep 18, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [7f55f1b615](https://linux-hardware.org/?probe=7f55f1b615) | Sep 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| HP            | 0A9Ch                       | Desktop     | [f5d07e235d](https://linux-hardware.org/?probe=f5d07e235d) | Aug 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1d9653f23a](https://linux-hardware.org/?probe=1d9653f23a) | Aug 13, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [d552e1a450](https://linux-hardware.org/?probe=d552e1a450) | Aug 08, 2023 |
| Wortmann      | CR700                       | Notebook    | [2f3379e14e](https://linux-hardware.org/?probe=2f3379e14e) | Jul 31, 2023 |
| HP            | ProBook 4530s               | Notebook    | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| Gigabyte      | GA-A55M-S2HP                | Other       | [5b1e00b374](https://linux-hardware.org/?probe=5b1e00b374) | Jul 26, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [cf3b586958](https://linux-hardware.org/?probe=cf3b586958) | Jul 22, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [ce4d4f4137](https://linux-hardware.org/?probe=ce4d4f4137) | Jul 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | Notebook    | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | Notebook    | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [9b40832f50](https://linux-hardware.org/?probe=9b40832f50) | Jul 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [cc05c0d021](https://linux-hardware.org/?probe=cc05c0d021) | Jul 09, 2023 |
| Sony          | VPCCW2S8E                   | Notebook    | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| Wortmann      | CR700                       | Notebook    | [b198dccb29](https://linux-hardware.org/?probe=b198dccb29) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | Notebook    | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| Gigabyte      | P55V6                       | Notebook    | [63d0cd064b](https://linux-hardware.org/?probe=63d0cd064b) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [228a46e465](https://linux-hardware.org/?probe=228a46e465) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [17ed1704c5](https://linux-hardware.org/?probe=17ed1704c5) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | Desktop     | [82bab4dd6d](https://linux-hardware.org/?probe=82bab4dd6d) | Jun 04, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [e3dca941cf](https://linux-hardware.org/?probe=e3dca941cf) | May 28, 2023 |
| Wortmann      | CR700                       | Notebook    | [189f1ae92b](https://linux-hardware.org/?probe=189f1ae92b) | May 27, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9327ef1887](https://linux-hardware.org/?probe=9327ef1887) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [bf551b2767](https://linux-hardware.org/?probe=bf551b2767) | May 14, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | Notebook    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | Notebook    | [66b49186cb](https://linux-hardware.org/?probe=66b49186cb) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1909a7f824](https://linux-hardware.org/?probe=1909a7f824) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [6e0d5c7f28](https://linux-hardware.org/?probe=6e0d5c7f28) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [136fd4098d](https://linux-hardware.org/?probe=136fd4098d) | May 01, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| Dell          | Latitude 5400               | Notebook    | [70899bc374](https://linux-hardware.org/?probe=70899bc374) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [d65df3295e](https://linux-hardware.org/?probe=d65df3295e) | Apr 11, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [52b4a5a0f0](https://linux-hardware.org/?probe=52b4a5a0f0) | Apr 08, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [5a1cd8556c](https://linux-hardware.org/?probe=5a1cd8556c) | Apr 01, 2023 |
| Biostar       | B550MX/E PRO                | Desktop     | [cffcb0a2a6](https://linux-hardware.org/?probe=cffcb0a2a6) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA8h                       | Desktop     | [fecbec6708](https://linux-hardware.org/?probe=fecbec6708) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | Notebook    | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| Acer          | Extensa 5630                | Notebook    | [e78d4a3c28](https://linux-hardware.org/?probe=e78d4a3c28) | Mar 14, 2023 |
| Wortmann      | CR700                       | Notebook    | [a48e22ffc5](https://linux-hardware.org/?probe=a48e22ffc5) | Mar 07, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [3574e6c0f8](https://linux-hardware.org/?probe=3574e6c0f8) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3e3368d913](https://linux-hardware.org/?probe=3e3368d913) | Feb 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [455b0e1401](https://linux-hardware.org/?probe=455b0e1401) | Feb 23, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1a50084a52](https://linux-hardware.org/?probe=1a50084a52) | Feb 19, 2023 |
| MSI           | B75A-G43                    | Desktop     | [bf426ce3c3](https://linux-hardware.org/?probe=bf426ce3c3) | Feb 18, 2023 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [9d36ad089c](https://linux-hardware.org/?probe=9d36ad089c) | Feb 18, 2023 |
| Dell          | Latitude 5330               | Notebook    | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| Dell          | Latitude 5330               | Notebook    | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| HP            | ProLiant DL320 G6           | Server      | [0d3689fed9](https://linux-hardware.org/?probe=0d3689fed9) | Feb 09, 2023 |
| Gigabyte      | H55M-D2H                    | Desktop     | [652695efb0](https://linux-hardware.org/?probe=652695efb0) | Feb 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Chuwi         | Hi10 Go                     | Notebook    | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [8f81628b59](https://linux-hardware.org/?probe=8f81628b59) | Jan 27, 2023 |
| Acer          | Aspire 5532                 | Notebook    | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [e98a955b1a](https://linux-hardware.org/?probe=e98a955b1a) | Jan 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [40719006ae](https://linux-hardware.org/?probe=40719006ae) | Jan 23, 2023 |
| Wortmann      | CR700                       | Notebook    | [0d40cf0690](https://linux-hardware.org/?probe=0d40cf0690) | Jan 22, 2023 |
| MSI           | CR500                       | Notebook    | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9cb7b18b35](https://linux-hardware.org/?probe=9cb7b18b35) | Jan 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [95e7b7d833](https://linux-hardware.org/?probe=95e7b7d833) | Jan 20, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [8026c0d5b2](https://linux-hardware.org/?probe=8026c0d5b2) | Jan 17, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [4f28b4be44](https://linux-hardware.org/?probe=4f28b4be44) | Jan 15, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [4884803279](https://linux-hardware.org/?probe=4884803279) | Jan 10, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [49b7bb70f3](https://linux-hardware.org/?probe=49b7bb70f3) | Jan 10, 2023 |
| HP            | 2AED                        | All in one  | [9a324c230d](https://linux-hardware.org/?probe=9a324c230d) | Jan 09, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [625bf5665f](https://linux-hardware.org/?probe=625bf5665f) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Dell          | 0HY9JP A01                  | Desktop     | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [68bd2484a1](https://linux-hardware.org/?probe=68bd2484a1) | Jan 04, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| HP            | G62                         | Notebook    | [4d80c95e73](https://linux-hardware.org/?probe=4d80c95e73) | Dec 18, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [cc139ec3a3](https://linux-hardware.org/?probe=cc139ec3a3) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [b3c750c720](https://linux-hardware.org/?probe=b3c750c720) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [1168ac14f5](https://linux-hardware.org/?probe=1168ac14f5) | Dec 09, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| ASUSTek       | F3Sg                        | Notebook    | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d9a78cb529](https://linux-hardware.org/?probe=d9a78cb529) | Nov 30, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [3d6a965dd4](https://linux-hardware.org/?probe=3d6a965dd4) | Nov 30, 2022 |
| ASUSTek       | G751JL                      | Notebook    | [1bfbfafe68](https://linux-hardware.org/?probe=1bfbfafe68) | Nov 29, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [6c97b310fb](https://linux-hardware.org/?probe=6c97b310fb) | Nov 29, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [f30a5c4808](https://linux-hardware.org/?probe=f30a5c4808) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [585b6910fa](https://linux-hardware.org/?probe=585b6910fa) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [138231da75](https://linux-hardware.org/?probe=138231da75) | Nov 26, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [4768ab429e](https://linux-hardware.org/?probe=4768ab429e) | Nov 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [7d576ac245](https://linux-hardware.org/?probe=7d576ac245) | Oct 29, 2022 |
| Wortmann      | CR700                       | Notebook    | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | Notebook    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e267cad212](https://linux-hardware.org/?probe=e267cad212) | Oct 20, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [69adb866e0](https://linux-hardware.org/?probe=69adb866e0) | Oct 20, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [491d0c69ca](https://linux-hardware.org/?probe=491d0c69ca) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [09ee887f3a](https://linux-hardware.org/?probe=09ee887f3a) | Oct 12, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [734baf54fa](https://linux-hardware.org/?probe=734baf54fa) | Oct 04, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [5bd6c356cd](https://linux-hardware.org/?probe=5bd6c356cd) | Aug 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [0a96778f7c](https://linux-hardware.org/?probe=0a96778f7c) | Jul 30, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [b4877f21ad](https://linux-hardware.org/?probe=b4877f21ad) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [3aa2d086b9](https://linux-hardware.org/?probe=3aa2d086b9) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [27d04b5577](https://linux-hardware.org/?probe=27d04b5577) | Jul 23, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [c6c4a561e1](https://linux-hardware.org/?probe=c6c4a561e1) | Jul 17, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9aa6d6be1](https://linux-hardware.org/?probe=e9aa6d6be1) | Jul 06, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [1acedf0aa3](https://linux-hardware.org/?probe=1acedf0aa3) | Jun 26, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [949fb9a5e7](https://linux-hardware.org/?probe=949fb9a5e7) | Jun 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [fab553a2b2](https://linux-hardware.org/?probe=fab553a2b2) | Jun 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [1242ad2894](https://linux-hardware.org/?probe=1242ad2894) | Jun 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e75d068a21](https://linux-hardware.org/?probe=e75d068a21) | Jun 02, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | Notebook    | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e854926e0](https://linux-hardware.org/?probe=8e854926e0) | May 12, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [3a940a3394](https://linux-hardware.org/?probe=3a940a3394) | May 11, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| HP            | 2AAC                        | Desktop     | [1f6b08507e](https://linux-hardware.org/?probe=1f6b08507e) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [e483a6e634](https://linux-hardware.org/?probe=e483a6e634) | Apr 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| Dell          | Latitude 5590               | Notebook    | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ABIT          | IP35-E                      | Desktop     | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | Notebook    | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [83df25aace](https://linux-hardware.org/?probe=83df25aace) | Feb 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [9dfc1ac601](https://linux-hardware.org/?probe=9dfc1ac601) | Feb 12, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [0848fdb73f](https://linux-hardware.org/?probe=0848fdb73f) | Feb 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [36f709712b](https://linux-hardware.org/?probe=36f709712b) | Feb 08, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [834bc65728](https://linux-hardware.org/?probe=834bc65728) | Feb 04, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [887e40e6c7](https://linux-hardware.org/?probe=887e40e6c7) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| MSI           | P55-GD65                    | Desktop     | [37da95512b](https://linux-hardware.org/?probe=37da95512b) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [a864c07042](https://linux-hardware.org/?probe=a864c07042) | Dec 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | Notebook    | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | Notebook    | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| HP            | 304Bh                       | Desktop     | [643a84ae14](https://linux-hardware.org/?probe=643a84ae14) | Oct 26, 2021 |
| HP            | 304Bh                       | Desktop     | [b7bd300808](https://linux-hardware.org/?probe=b7bd300808) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | Notebook    | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [7e44f2ff81](https://linux-hardware.org/?probe=7e44f2ff81) | Sep 06, 2021 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [071ad478e7](https://linux-hardware.org/?probe=071ad478e7) | Aug 30, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [5b32c9197c](https://linux-hardware.org/?probe=5b32c9197c) | Aug 28, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [8cd8b7faa5](https://linux-hardware.org/?probe=8cd8b7faa5) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | Notebook    | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | Notebook    | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | Notebook    | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [13fb44b235](https://linux-hardware.org/?probe=13fb44b235) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bc618727f4](https://linux-hardware.org/?probe=bc618727f4) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | Notebook    | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | Notebook    | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [6aa52c9eb8](https://linux-hardware.org/?probe=6aa52c9eb8) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | Notebook    | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | Notebook    | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | Notebook    | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | Notebook    | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | Notebook    | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| MSI           | H310M PRO-VD                | Desktop     | [42ade7f952](https://linux-hardware.org/?probe=42ade7f952) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| Dell          | Latitude 5520               | Notebook    | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [25a9c64af7](https://linux-hardware.org/?probe=25a9c64af7) | May 29, 2021 |
| Acer          | AO725                       | Notebook    | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [2d479e2946](https://linux-hardware.org/?probe=2d479e2946) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [621d19b1f1](https://linux-hardware.org/?probe=621d19b1f1) | May 15, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [796bb8e1b8](https://linux-hardware.org/?probe=796bb8e1b8) | May 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4d87fd7e46](https://linux-hardware.org/?probe=4d87fd7e46) | Apr 13, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d2a175100f](https://linux-hardware.org/?probe=d2a175100f) | Mar 22, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | Notebook    | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [344b4339b4](https://linux-hardware.org/?probe=344b4339b4) | Mar 17, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1194a50093](https://linux-hardware.org/?probe=1194a50093) | Mar 16, 2021 |
| HP            | 18E7                        | Desktop     | [d0fb912292](https://linux-hardware.org/?probe=d0fb912292) | Mar 09, 2021 |
| Acer          | F671CR R01-C0               | Desktop     | [7a4637f10b](https://linux-hardware.org/?probe=7a4637f10b) | Mar 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [0ac539b524](https://linux-hardware.org/?probe=0ac539b524) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [dbde42fa23](https://linux-hardware.org/?probe=dbde42fa23) | Mar 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a49a1ff054](https://linux-hardware.org/?probe=a49a1ff054) | Feb 27, 2021 |
| HP            | 304Bh                       | Desktop     | [92c6653702](https://linux-hardware.org/?probe=92c6653702) | Feb 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3bc6f280d8](https://linux-hardware.org/?probe=3bc6f280d8) | Feb 19, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [0cfdd76052](https://linux-hardware.org/?probe=0cfdd76052) | Feb 08, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | Notebook    | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| ASUSTek       | P5GD1-VM                    | Desktop     | [863b2fd0bf](https://linux-hardware.org/?probe=863b2fd0bf) | Jan 22, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb2b38d97f](https://linux-hardware.org/?probe=cb2b38d97f) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5b1abefa3c](https://linux-hardware.org/?probe=5b1abefa3c) | Jan 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [e734d18206](https://linux-hardware.org/?probe=e734d18206) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [b85445cf41](https://linux-hardware.org/?probe=b85445cf41) | Jan 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [81b3dbf5fd](https://linux-hardware.org/?probe=81b3dbf5fd) | Jan 02, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c3b94fff22](https://linux-hardware.org/?probe=c3b94fff22) | Dec 31, 2020 |
| ASUSTek       | N56VM                       | Notebook    | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e50d894b93](https://linux-hardware.org/?probe=e50d894b93) | Dec 28, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [2eede62ff5](https://linux-hardware.org/?probe=2eede62ff5) | Dec 26, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8cf512e3a9](https://linux-hardware.org/?probe=8cf512e3a9) | Dec 26, 2020 |
| ASUSTek       | P5K PRO                     | Desktop     | [0e58a56cfb](https://linux-hardware.org/?probe=0e58a56cfb) | Dec 26, 2020 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [bb01071f16](https://linux-hardware.org/?probe=bb01071f16) | Dec 15, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| Acer          | Aspire E5-774G              | Notebook    | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| MSI           | B75A-G43                    | Desktop     | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| MSI           | B75A-G43                    | Desktop     | [5f68cce112](https://linux-hardware.org/?probe=5f68cce112) | Nov 16, 2020 |
| ASUSTek       | F9S                         | Notebook    | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | Notebook    | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f2ff00472b](https://linux-hardware.org/?probe=f2ff00472b) | Nov 07, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [bdb367a3b2](https://linux-hardware.org/?probe=bdb367a3b2) | Nov 03, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f36ffb293](https://linux-hardware.org/?probe=4f36ffb293) | Nov 01, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [5139c9e029](https://linux-hardware.org/?probe=5139c9e029) | Nov 01, 2020 |
| Acer          | Aspire E1-570               | Notebook    | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7ac6a6dab5](https://linux-hardware.org/?probe=7ac6a6dab5) | Oct 27, 2020 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [3ea3e1a644](https://linux-hardware.org/?probe=3ea3e1a644) | Oct 26, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [c9a44de2e0](https://linux-hardware.org/?probe=c9a44de2e0) | Oct 26, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [4e526c6262](https://linux-hardware.org/?probe=4e526c6262) | Oct 14, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [a37fe628b4](https://linux-hardware.org/?probe=a37fe628b4) | Oct 04, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [c6cf49892e](https://linux-hardware.org/?probe=c6cf49892e) | Oct 04, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [a6c2ba4977](https://linux-hardware.org/?probe=a6c2ba4977) | Oct 04, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ebefa289ab](https://linux-hardware.org/?probe=ebefa289ab) | Sep 30, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [2702ecbebe](https://linux-hardware.org/?probe=2702ecbebe) | Sep 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a53b5a24b](https://linux-hardware.org/?probe=1a53b5a24b) | Sep 21, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [177f17803c](https://linux-hardware.org/?probe=177f17803c) | Aug 24, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | Notebook    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b68bc64592](https://linux-hardware.org/?probe=b68bc64592) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d5429ba62e](https://linux-hardware.org/?probe=d5429ba62e) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | Notebook    | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [625d32881c](https://linux-hardware.org/?probe=625d32881c) | May 29, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | Notebook    | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6d6cb669e](https://linux-hardware.org/?probe=d6d6cb669e) | Apr 29, 2020 |
| Acer          | Aspire ES1-512              | Notebook    | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [31631f3ea5](https://linux-hardware.org/?probe=31631f3ea5) | Apr 23, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [8f1f828d49](https://linux-hardware.org/?probe=8f1f828d49) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [95e2b82808](https://linux-hardware.org/?probe=95e2b82808) | Mar 26, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [9fcf5501fb](https://linux-hardware.org/?probe=9fcf5501fb) | Mar 26, 2020 |
| IBM           | 8215ZCL                     | Desktop     | [8f44ceaa1e](https://linux-hardware.org/?probe=8f44ceaa1e) | Mar 26, 2020 |
| Dell          | Latitude E6230              | Notebook    | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | Notebook    | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | Notebook    | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [2d568b2e9d](https://linux-hardware.org/?probe=2d568b2e9d) | Feb 19, 2020 |
| ASUSTek       | BU401LAV                    | Notebook    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| MSI           | Z370 SLI PLUS               | Desktop     | [c76ba1a6d0](https://linux-hardware.org/?probe=c76ba1a6d0) | Feb 08, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | Notebook    | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | Notebook    | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [9deccd0d74](https://linux-hardware.org/?probe=9deccd0d74) | Jan 24, 2020 |
| Dell          | Inspiron 1720               | Notebook    | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [e005197c6c](https://linux-hardware.org/?probe=e005197c6c) | Jan 09, 2020 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5af3a0243a](https://linux-hardware.org/?probe=5af3a0243a) | Jan 06, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [70297101fe](https://linux-hardware.org/?probe=70297101fe) | Dec 31, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Dell          | 0RJ290                      | Desktop     | [21ae6dbdf0](https://linux-hardware.org/?probe=21ae6dbdf0) | Dec 16, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | Notebook    | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bab2716ff6](https://linux-hardware.org/?probe=bab2716ff6) | Dec 02, 2019 |
| Dell          | Latitude D630               | Notebook    | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | Notebook    | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | Notebook    | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | Notebook    | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | Notebook    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Dell          | Latitude E5510              | Notebook    | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | Notebook    | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a6d137277e](https://linux-hardware.org/?probe=a6d137277e) | Sep 18, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [2fc2bdd742](https://linux-hardware.org/?probe=2fc2bdd742) | Sep 14, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5110001e92](https://linux-hardware.org/?probe=5110001e92) | Sep 14, 2019 |
| Gigabyte      | Z87P-D3                     | Desktop     | [a7e732af2a](https://linux-hardware.org/?probe=a7e732af2a) | Aug 26, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [5c290c18c9](https://linux-hardware.org/?probe=5c290c18c9) | Aug 18, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | 0A60h                       | Desktop     | [b031cf2f9c](https://linux-hardware.org/?probe=b031cf2f9c) | Jul 30, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | Notebook    | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| MSI           | FM2-A55M-E33                | Desktop     | [426ae68b93](https://linux-hardware.org/?probe=426ae68b93) | Jun 29, 2019 |
| MSI           | B85-G41 PC Mate             | Desktop     | [0f3dccfe4e](https://linux-hardware.org/?probe=0f3dccfe4e) | Jun 26, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | Notebook    | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | Notebook    | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | Notebook    | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | Notebook    | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [5e414bc536](https://linux-hardware.org/?probe=5e414bc536) | Mar 14, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | Notebook    | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [3437fc1ab6](https://linux-hardware.org/?probe=3437fc1ab6) | Feb 12, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [f08ce9bd47](https://linux-hardware.org/?probe=f08ce9bd47) | Jan 09, 2019 |
| Dell          | Inspiron 1720               | Notebook    | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | Notebook    | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | Notebook    | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | Notebook    | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | Notebook    | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Dell          | 0WK833                      | Desktop     | [17e742f811](https://linux-hardware.org/?probe=17e742f811) | Jul 11, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Dell          | 0WK833                      | Desktop     | [d118bf168b](https://linux-hardware.org/?probe=d118bf168b) | Jun 28, 2018 |
| Dell          | 0WK833                      | Desktop     | [0e39368786](https://linux-hardware.org/?probe=0e39368786) | Jun 28, 2018 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [c401108ba6](https://linux-hardware.org/?probe=c401108ba6) | Jun 20, 2018 |
| Acer          | Aspire V5-552G              | Notebook    | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Gigabyte      | H55M-D2H                    | Desktop     | [e4e92393a0](https://linux-hardware.org/?probe=e4e92393a0) | Mar 08, 2018 |
| Dell          | XPS MXC062                  | Notebook    | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | Notebook    | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [f4d998043d](https://linux-hardware.org/?probe=f4d998043d) | Jan 29, 2018 |
| ASUSTek       | K73BE                       | Notebook    | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| ASUSTek       | A88XM-A                     | Desktop     | [f7b8e36550](https://linux-hardware.org/?probe=f7b8e36550) | Jan 21, 2018 |
| Acer          | F671CR R01-C0               | Desktop     | [a5b92562b9](https://linux-hardware.org/?probe=a5b92562b9) | Dec 26, 2017 |
| MSI           | MS-7519                     | Desktop     | [81563b0ef8](https://linux-hardware.org/?probe=81563b0ef8) | Nov 18, 2017 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | Notebook    | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| MSI           | MS-7519                     | Desktop     | [5e4728fda0](https://linux-hardware.org/?probe=5e4728fda0) | Sep 17, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | Notebook    | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | Notebook    | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| ASRock        | G31M-GS                     | Desktop     | [7a4eee4480](https://linux-hardware.org/?probe=7a4eee4480) | May 31, 2017 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [bfab333807](https://linux-hardware.org/?probe=bfab333807) | May 03, 2017 |
| Acer          | EG31M R01-A2                | Desktop     | [018dafc2d0](https://linux-hardware.org/?probe=018dafc2d0) | Apr 27, 2017 |
| eMachines     | Unknown                     | Notebook    | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | Notebook    | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | F9S                         | Notebook    | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | P5Q                         | Desktop     | [26e2520232](https://linux-hardware.org/?probe=26e2520232) | Nov 11, 2016 |
| ASUSTek       | K53SD                       | Notebook    | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | Notebook    | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | Notebook    | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Latvia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 5.93%   |
| Arch Rolling                 | 23        | 4.26%   |
| ROSA R11                     | 19        | 3.52%   |
| Ubuntu 22.04                 | 18        | 3.33%   |
| Ubuntu 18.04                 | 16        | 2.96%   |
| Pop!_OS 22.04                | 13        | 2.41%   |
| ROSA R10                     | 12        | 2.22%   |
| Debian 12                    | 11        | 2.04%   |
| ROSA R9                      | 10        | 1.85%   |
| Debian 11                    | 10        | 1.85%   |
| KDE neon 20.04               | 9         | 1.67%   |
| Linux Mint 22.1              | 8         | 1.48%   |
| Arch                         | 8         | 1.48%   |
| ROSA R8.1                    | 7         | 1.3%    |
| OpenMandriva 4.3             | 7         | 1.3%    |
| Manjaro                      | 7         | 1.3%    |
| Linux Mint 20.3              | 7         | 1.3%    |
| ROSA R11.1                   | 6         | 1.11%   |
| OpenMandriva 23.01           | 6         | 1.11%   |
| Linux Mint 20.1              | 6         | 1.11%   |
| KDE neon 22.04               | 6         | 1.11%   |
| Fedora 42                    | 6         | 1.11%   |
| Fedora 37                    | 6         | 1.11%   |
| ArcoLinux Rolling            | 6         | 1.11%   |
| Xubuntu 20.04                | 5         | 0.93%   |
| ROSA R8                      | 5         | 0.93%   |
| Pop!_OS 21.04                | 5         | 0.93%   |
| Pop!_OS 20.10                | 5         | 0.93%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.93%   |
| OpenMandriva 23.08           | 5         | 0.93%   |
| Linux Mint 21.1              | 5         | 0.93%   |
| Linux Mint 21                | 5         | 0.93%   |
| Zorin 16                     | 4         | 0.74%   |
| Ubuntu 19.10                 | 4         | 0.74%   |
| ROSA 12.3                    | 4         | 0.74%   |
| ROSA 12.2                    | 4         | 0.74%   |
| OpenMandriva 4.50            | 4         | 0.74%   |
| OpenMandriva 25.90           | 4         | 0.74%   |
| OpenMandriva 24.12           | 4         | 0.74%   |
| Linux Mint 21.3              | 4         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 91        | 18.65%  |
| ROSA          | 59        | 12.09%  |
| Linux Mint    | 49        | 10.04%  |
| Fedora        | 40        | 8.2%    |
| OpenMandriva  | 37        | 7.58%   |
| Arch          | 31        | 6.35%   |
| Debian        | 27        | 5.53%   |
| Pop!_OS       | 25        | 5.12%   |
| KDE neon      | 17        | 3.48%   |
| Manjaro       | 13        | 2.66%   |
| Zorin         | 9         | 1.84%   |
| Kubuntu       | 9         | 1.84%   |
| Xubuntu       | 8         | 1.64%   |
| openSUSE      | 7         | 1.43%   |
| ArcoLinux     | 7         | 1.43%   |
| Elementary    | 5         | 1.02%   |
| SteamOS       | 4         | 0.82%   |
| Kali          | 4         | 0.82%   |
| Garuda Linux  | 4         | 0.82%   |
| Ubuntu Unity  | 3         | 0.61%   |
| Gentoo        | 3         | 0.61%   |
| Endless       | 3         | 0.61%   |
| EndeavourOS   | 3         | 0.61%   |
| Bazzite       | 3         | 0.61%   |
| ALT Linux     | 3         | 0.61%   |
| Void Linux    | 2         | 0.41%   |
| Oracle Linux  | 2         | 0.41%   |
| Nobara        | 2         | 0.41%   |
| Lubuntu       | 2         | 0.41%   |
| Clear Linux   | 2         | 0.41%   |
| CachyOS       | 2         | 0.41%   |
| Ubuntu MATE   | 1         | 0.2%    |
| Ubuntu Budgie | 1         | 0.2%    |
| TUXEDO OS     | 1         | 0.2%    |
| Solus         | 1         | 0.2%    |
| Puppy         | 1         | 0.2%    |
| Peppermint    | 1         | 0.2%    |
| Parrot        | 1         | 0.2%    |
| NixOS         | 1         | 0.2%    |
| MX            | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64     | 10        | 1.65%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 9         | 1.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 8         | 1.32%   |
| 5.16.7-desktop-1omv4003             | 7         | 1.16%   |
| 6.1.1-desktop-1omv2290              | 6         | 0.99%   |
| 5.4.0-42-generic                    | 6         | 0.99%   |
| 6.14.2-desktop-3omv2590             | 5         | 0.83%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 5         | 0.83%   |
| 6.12.1-desktop-1omv2490             | 4         | 0.66%   |
| 5.4.0-58-generic                    | 4         | 0.66%   |
| 5.4.0-132-generic                   | 4         | 0.66%   |
| 5.4.0-122-generic                   | 4         | 0.66%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 4         | 0.66%   |
| 6.8.0-60-generic                    | 3         | 0.5%    |
| 6.5.7-200.fc38.x86_64               | 3         | 0.5%    |
| 6.4.11-desktop-1omv2390             | 3         | 0.5%    |
| 6.2.6-76060206-generic              | 3         | 0.5%    |
| 5.8.0-7630-generic                  | 3         | 0.5%    |
| 5.4.83-generic-2rosa-x86_64         | 3         | 0.5%    |
| 5.4.0-80-generic                    | 3         | 0.5%    |
| 5.4.0-66-generic                    | 3         | 0.5%    |
| 5.4.0-54-generic                    | 3         | 0.5%    |
| 5.4.0-52-generic                    | 3         | 0.5%    |
| 5.15.0-86-generic                   | 3         | 0.5%    |
| 5.15.0-67-generic                   | 3         | 0.5%    |
| 5.15.0-58-generic                   | 3         | 0.5%    |
| 5.13.0-25-generic                   | 3         | 0.5%    |
| 5.12.4-desktop-1omv4050             | 3         | 0.5%    |
| 5.10.14-desktop-1omv4002            | 3         | 0.5%    |
| 5.0.0-37-generic                    | 3         | 0.5%    |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 3         | 0.5%    |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 3         | 0.5%    |
| 4.15.0-desktop-60.7rosa-x86_64      | 3         | 0.5%    |
| 6.8.7-300.fc40.x86_64               | 2         | 0.33%   |
| 6.8.0-76060800daily20240311-generic | 2         | 0.33%   |
| 6.8.0-55-generic                    | 2         | 0.33%   |
| 6.8.0-51-generic                    | 2         | 0.33%   |
| 6.8.0-49-generic                    | 2         | 0.33%   |
| 6.8.0-40-generic                    | 2         | 0.33%   |
| 6.5.0-35-generic                    | 2         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 56        | 9.95%   |
| 5.15.0  | 35        | 6.22%   |
| 4.15.0  | 32        | 5.68%   |
| 6.8.0   | 20        | 3.55%   |
| 5.13.0  | 15        | 2.66%   |
| 5.8.0   | 14        | 2.49%   |
| 5.11.0  | 14        | 2.49%   |
| 6.5.0   | 11        | 1.95%   |
| 5.10.0  | 11        | 1.95%   |
| 4.9.20  | 11        | 1.95%   |
| 5.3.0   | 10        | 1.78%   |
| 6.2.0   | 9         | 1.6%    |
| 6.1.0   | 8         | 1.42%   |
| 5.19.0  | 8         | 1.42%   |
| 4.9.60  | 8         | 1.42%   |
| 6.14.0  | 7         | 1.24%   |
| 6.11.0  | 7         | 1.24%   |
| 6.1.1   | 7         | 1.24%   |
| 5.16.7  | 7         | 1.24%   |
| 6.14.2  | 6         | 1.07%   |
| 5.0.0   | 6         | 1.07%   |
| 6.2.6   | 5         | 0.89%   |
| 6.12.1  | 5         | 0.89%   |
| 5.10.74 | 5         | 0.89%   |
| 4.18.0  | 5         | 0.89%   |
| 6.17.7  | 4         | 0.71%   |
| 4.9.155 | 4         | 0.71%   |
| 4.1.34  | 4         | 0.71%   |
| 6.5.7   | 3         | 0.53%   |
| 6.4.11  | 3         | 0.53%   |
| 6.16.3  | 3         | 0.53%   |
| 5.4.83  | 3         | 0.53%   |
| 5.17.1  | 3         | 0.53%   |
| 5.14.0  | 3         | 0.53%   |
| 5.12.4  | 3         | 0.53%   |
| 5.10.14 | 3         | 0.53%   |
| 4.9.41  | 3         | 0.53%   |
| 6.9.9   | 2         | 0.36%   |
| 6.9.7   | 2         | 0.36%   |
| 6.9.3   | 2         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 64        | 11.59%  |
| 5.15    | 48        | 8.7%    |
| 4.15    | 32        | 5.8%    |
| 6.1     | 27        | 4.89%   |
| 4.9     | 27        | 4.89%   |
| 6.8     | 26        | 4.71%   |
| 5.10    | 25        | 4.53%   |
| 5.13    | 21        | 3.8%    |
| 5.11    | 19        | 3.44%   |
| 6.12    | 18        | 3.26%   |
| 5.8     | 18        | 3.26%   |
| 6.14    | 17        | 3.08%   |
| 6.5     | 15        | 2.72%   |
| 6.2     | 14        | 2.54%   |
| 6.6     | 12        | 2.17%   |
| 5.19    | 12        | 2.17%   |
| 5.16    | 12        | 2.17%   |
| 6.11    | 11        | 1.99%   |
| 6.0     | 11        | 1.99%   |
| 6.17    | 10        | 1.81%   |
| 5.3     | 10        | 1.81%   |
| 6.16    | 9         | 1.63%   |
| 5.12    | 8         | 1.45%   |
| 6.9     | 7         | 1.27%   |
| 6.4     | 7         | 1.27%   |
| 6.13    | 6         | 1.09%   |
| 5.17    | 6         | 1.09%   |
| 5.0     | 6         | 1.09%   |
| 5.18    | 5         | 0.91%   |
| 5.14    | 5         | 0.91%   |
| 4.18    | 5         | 0.91%   |
| 4.1     | 5         | 0.91%   |
| 6.7     | 4         | 0.72%   |
| 5.9     | 4         | 0.72%   |
| 6.3     | 3         | 0.54%   |
| 6.15    | 3         | 0.54%   |
| 5.5     | 3         | 0.54%   |
| 5.2     | 3         | 0.54%   |
| 5.6     | 2         | 0.36%   |
| 4.4     | 2         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 450       | 96.15%  |
| i686    | 13        | 2.78%   |
| aarch64 | 5         | 1.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 174       | 34.73%  |
| KDE5              | 97        | 19.36%  |
| Unknown           | 38        | 7.58%   |
| KDE4              | 35        | 6.99%   |
| XFCE              | 33        | 6.59%   |
| KDE6              | 33        | 6.59%   |
| X-Cinnamon        | 28        | 5.59%   |
| MATE              | 17        | 3.39%   |
| KDE               | 12        | 2.4%    |
| LXQt              | 6         | 1.2%    |
| Cinnamon          | 6         | 1.2%    |
| Pantheon          | 5         | 1%      |
| Budgie            | 4         | 0.8%    |
| Unity             | 3         | 0.6%    |
| i3                | 3         | 0.6%    |
| Deepin            | 2         | 0.4%    |
| COSMIC            | 2         | 0.4%    |
| x-session-manager | 1         | 0.2%    |
| sway              | 1         | 0.2%    |
| LXDE              | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 330       | 67.76%  |
| Wayland | 127       | 26.08%  |
| Unknown | 16        | 3.29%   |
| Tty     | 14        | 2.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 211       | 42.71%  |
| SDDM    | 99        | 20.04%  |
| GDM     | 53        | 10.73%  |
| LightDM | 40        | 8.1%    |
| GDM3    | 39        | 7.89%   |
| KDM     | 34        | 6.88%   |
| TDM     | 15        | 3.04%   |
| SLiM    | 1         | 0.2%    |
| MDM     | 1         | 0.2%    |
| LDM     | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 254       | 51.84%  |
| ru_RU       | 68        | 13.88%  |
| Unknown     | 66        | 13.47%  |
| lv_LV       | 52        | 10.61%  |
| en_GB       | 23        | 4.69%   |
| C           | 14        | 2.86%   |
| de_DE       | 3         | 0.61%   |
| ru_RU.UTF_8 | 2         | 0.41%   |
| en_AG       | 2         | 0.41%   |
| ru_UA       | 1         | 0.2%    |
| POSIX       | 1         | 0.2%    |
| pl_PL       | 1         | 0.2%    |
| osa_US      | 1         | 0.2%    |
| fr_FR       | 1         | 0.2%    |
| cv_RU       | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 270       | 56.49%  |
| EFI  | 208       | 43.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 324       | 66.12%  |
| Btrfs   | 73        | 14.9%   |
| Overlay | 32        | 6.53%   |
| Unknown | 28        | 5.71%   |
| Tmpfs   | 22        | 4.49%   |
| Xfs     | 6         | 1.22%   |
| Zfs     | 2         | 0.41%   |
| F2fs    | 1         | 0.2%    |
| Ext3    | 1         | 0.2%    |
| Aufs    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 217       | 44.02%  |
| GPT     | 194       | 39.35%  |
| MBR     | 82        | 16.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 414       | 85.19%  |
| Yes       | 72        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 352       | 72.88%  |
| Yes       | 131       | 27.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 90        | 19.23%  |
| Lenovo                               | 76        | 16.24%  |
| Hewlett-Packard                      | 54        | 11.54%  |
| Dell                                 | 48        | 10.26%  |
| Gigabyte Technology                  | 38        | 8.12%   |
| MSI                                  | 33        | 7.05%   |
| Acer                                 | 30        | 6.41%   |
| ASRock                               | 21        | 4.49%   |
| Apple                                | 9         | 1.92%   |
| Intel                                | 8         | 1.71%   |
| Toshiba                              | 7         | 1.5%    |
| Fujitsu Siemens                      | 6         | 1.28%   |
| Samsung Electronics                  | 5         | 1.07%   |
| Biostar                              | 4         | 0.85%   |
| Unknown                              | 4         | 0.85%   |
| Valve                                | 3         | 0.64%   |
| Packard Bell                         | 3         | 0.64%   |
| HUAWEI                               | 3         | 0.64%   |
| TUXEDO                               | 2         | 0.43%   |
| Sony                                 | 2         | 0.43%   |
| Raspberry Pi Foundation              | 2         | 0.43%   |
| Hardkernel                           | 2         | 0.43%   |
| eMachines                            | 2         | 0.43%   |
| Wortmann AG                          | 1         | 0.21%   |
| Timi                                 | 1         | 0.21%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.21%   |
| Rockchip                             | 1         | 0.21%   |
| Razer                                | 1         | 0.21%   |
| Quanta                               | 1         | 0.21%   |
| mPTech                               | 1         | 0.21%   |
| IBM                                  | 1         | 0.21%   |
| GMKtec                               | 1         | 0.21%   |
| Fujitsu                              | 1         | 0.21%   |
| Foxconn                              | 1         | 0.21%   |
| Chuwi                                | 1         | 0.21%   |
| Amentmen                             | 1         | 0.21%   |
| Advent                               | 1         | 0.21%   |
| Acidanthera                          | 1         | 0.21%   |
| ABIT                                 | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 7         | 1.5%    |
| Unknown                                    | 7         | 1.5%    |
| Toshiba Satellite C660                     | 3         | 0.64%   |
| Intel DH77EB AAG39073-304                  | 3         | 0.64%   |
| HP EliteBook 840 G3                        | 3         | 0.64%   |
| HP 250 G6 Notebook PC                      | 3         | 0.64%   |
| ASUS X553MA                                | 3         | 0.64%   |
| Apple MacBookPro8,1                        | 3         | 0.64%   |
| Valve Galileo                              | 2         | 0.43%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 2         | 0.43%   |
| MSI MS-7721                                | 2         | 0.43%   |
| Lenovo Legion 5 15ACH6H 82JU               | 2         | 0.43%   |
| Lenovo IdeaPad 300-15ISK 80Q7              | 2         | 0.43%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 2         | 0.43%   |
| HP G62                                     | 2         | 0.43%   |
| HP EliteBook 8440p                         | 2         | 0.43%   |
| Gigabyte G33M-S2                           | 2         | 0.43%   |
| Gigabyte B550 AORUS PRO V2                 | 2         | 0.43%   |
| Gigabyte 946GMX-S2                         | 2         | 0.43%   |
| Fujitsu Siemens LIFEBOOK S6420             | 2         | 0.43%   |
| Dell OptiPlex 7020                         | 2         | 0.43%   |
| ASUS ZenBook UX431DA_UM431DA               | 2         | 0.43%   |
| ASUS X551MA                                | 2         | 0.43%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA   | 2         | 0.43%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.43%   |
| ASUS TUF Gaming B650-PLUS WIFI             | 2         | 0.43%   |
| ASRock FM2A68M-HD+                         | 2         | 0.43%   |
| Wortmann AG CR700                          | 1         | 0.21%   |
| Valve Jupiter                              | 1         | 0.21%   |
| TUXEDO Gemini Gen2                         | 1         | 0.21%   |
| Toshiba Satellite L850-1LK                 | 1         | 0.21%   |
| Toshiba Satellite L750                     | 1         | 0.21%   |
| Toshiba Satellite L350                     | 1         | 0.21%   |
| Toshiba Satellite C50D-B                   | 1         | 0.21%   |
| Timi A35S                                  | 1         | 0.21%   |
| Sony VPCEE4E1E                             | 1         | 0.21%   |
| Sony VPCCW2S8E                             | 1         | 0.21%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1         | 0.21%   |
| Samsung RV410/RV510/S3510/E3510            | 1         | 0.21%   |
| Samsung R528/R728                          | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 39        | 8.33%   |
| Acer Aspire              | 19        | 4.06%   |
| Lenovo IdeaPad           | 16        | 3.42%   |
| Dell Inspiron            | 14        | 2.99%   |
| HP EliteBook             | 13        | 2.78%   |
| Dell Latitude            | 13        | 2.78%   |
| ASUS VivoBook            | 10        | 2.14%   |
| HP Pavilion              | 8         | 1.71%   |
| Dell OptiPlex            | 8         | 1.71%   |
| ASUS TUF                 | 8         | 1.71%   |
| ASUS PRIME               | 8         | 1.71%   |
| Toshiba Satellite        | 7         | 1.5%    |
| ASUS ROG                 | 7         | 1.5%    |
| ASUS All                 | 7         | 1.5%    |
| Unknown                  | 7         | 1.5%    |
| Lenovo Legion            | 6         | 1.28%   |
| HP ProBook               | 5         | 1.07%   |
| HP Laptop                | 5         | 1.07%   |
| HP Compaq                | 4         | 0.85%   |
| HP 250                   | 4         | 0.85%   |
| Dell Vostro              | 4         | 0.85%   |
| ASUS ZenBook             | 4         | 0.85%   |
| Packard Bell EasyNote    | 3         | 0.64%   |
| Lenovo ThinkBook         | 3         | 0.64%   |
| Intel DH77EB             | 3         | 0.64%   |
| Fujitsu Siemens LIFEBOOK | 3         | 0.64%   |
| Dell Precision           | 3         | 0.64%   |
| ASUS X553MA              | 3         | 0.64%   |
| ASRock B450M             | 3         | 0.64%   |
| Apple MacBookPro8        | 3         | 0.64%   |
| Acer Nitro               | 3         | 0.64%   |
| Valve Galileo            | 2         | 0.43%   |
| RPi Raspberry            | 2         | 0.43%   |
| MSI MS-7721              | 2         | 0.43%   |
| MSI Katana               | 2         | 0.43%   |
| Lenovo Yoga              | 2         | 0.43%   |
| HP G62                   | 2         | 0.43%   |
| Gigabyte G33M-S2         | 2         | 0.43%   |
| Gigabyte B550            | 2         | 0.43%   |
| Gigabyte B450            | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 38        | 8.12%   |
| 2012    | 36        | 7.69%   |
| 2013    | 34        | 7.26%   |
| 2014    | 33        | 7.05%   |
| 2021    | 31        | 6.62%   |
| 2011    | 31        | 6.62%   |
| 2020    | 28        | 5.98%   |
| 2018    | 28        | 5.98%   |
| 2015    | 26        | 5.56%   |
| 2017    | 24        | 5.13%   |
| 2008    | 24        | 5.13%   |
| 2010    | 23        | 4.91%   |
| 2007    | 23        | 4.91%   |
| 2009    | 19        | 4.06%   |
| 2022    | 18        | 3.85%   |
| 2023    | 15        | 3.21%   |
| 2016    | 14        | 2.99%   |
| 2024    | 8         | 1.71%   |
| 2006    | 7         | 1.5%    |
| Unknown | 5         | 1.07%   |
| 2025    | 2         | 0.43%   |
| 2004    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 287       | 61.32%  |
| Desktop        | 158       | 33.76%  |
| Convertible    | 7         | 1.5%    |
| System on chip | 5         | 1.07%   |
| Mini pc        | 5         | 1.07%   |
| Server         | 3         | 0.64%   |
| All in one     | 2         | 0.43%   |
| Other          | 1         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 439       | 93.01%  |
| Enabled  | 33        | 6.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 467       | 99.79%  |
| Yes  | 1         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 107       | 22.43%  |
| 4.01-8.0        | 102       | 21.38%  |
| 8.01-16.0       | 82        | 17.19%  |
| 16.01-24.0      | 78        | 16.35%  |
| 32.01-64.0      | 53        | 11.11%  |
| 2.01-3.0        | 15        | 3.14%   |
| 1.01-2.0        | 15        | 3.14%   |
| 24.01-32.0      | 12        | 2.52%   |
| 64.01-256.0     | 10        | 2.1%    |
| 0.51-1.0        | 2         | 0.42%   |
| More than 256.0 | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 153       | 28.76%  |
| 2.01-3.0   | 122       | 22.93%  |
| 4.01-8.0   | 95        | 17.86%  |
| 3.01-4.0   | 67        | 12.59%  |
| 0.51-1.0   | 58        | 10.9%   |
| 8.01-16.0  | 28        | 5.26%   |
| 16.01-24.0 | 6         | 1.13%   |
| 32.01-64.0 | 1         | 0.19%   |
| 24.01-32.0 | 1         | 0.19%   |
| 0.01-0.5   | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 290       | 60.04%  |
| 2      | 116       | 24.02%  |
| 3      | 43        | 8.9%    |
| 4      | 19        | 3.93%   |
| 5      | 7         | 1.45%   |
| 6      | 3         | 0.62%   |
| 7      | 2         | 0.41%   |
| 0      | 2         | 0.41%   |
| 8      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 306       | 64.15%  |
| Yes       | 171       | 35.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 415       | 88.3%   |
| No        | 55        | 11.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 355       | 75.53%  |
| No        | 115       | 24.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 282       | 59.12%  |
| No        | 195       | 40.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Latvia  | 468       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Riga          | 357       | 71.54%  |
| Liepāja      | 16        | 3.21%   |
| Jelgava       | 14        | 2.81%   |
| Daugavpils    | 9         | 1.8%    |
| Salaspils     | 7         | 1.4%    |
| Ventspils     | 6         | 1.2%    |
| Jaunolaine    | 6         | 1.2%    |
| Jūrmala      | 5         | 1%      |
| Adazi         | 5         | 1%      |
| Ogre          | 4         | 0.8%    |
| Kuldīga      | 4         | 0.8%    |
| Jēkabpils    | 4         | 0.8%    |
| Jaunmarupe    | 4         | 0.8%    |
| Iecava        | 4         | 0.8%    |
| Valmiera      | 3         | 0.6%    |
| Limbaži      | 3         | 0.6%    |
| Talsi         | 2         | 0.4%    |
| Saulkrasti    | 2         | 0.4%    |
| Rēzekne      | 2         | 0.4%    |
| Pļaviņas    | 2         | 0.4%    |
| Malpils       | 2         | 0.4%    |
| Ķekava       | 2         | 0.4%    |
| Cēsis        | 2         | 0.4%    |
| Aizkraukle    | 2         | 0.4%    |
| Zvejniekciems | 1         | 0.2%    |
| Ulbroka       | 1         | 0.2%    |
| Tukums        | 1         | 0.2%    |
| Tiraine       | 1         | 0.2%    |
| Smiltene      | 1         | 0.2%    |
| Saulkalne     | 1         | 0.2%    |
| Saldus        | 1         | 0.2%    |
| Roya          | 1         | 0.2%    |
| Ragana        | 1         | 0.2%    |
| Preiļi       | 1         | 0.2%    |
| Pinki         | 1         | 0.2%    |
| Ozolnieki     | 1         | 0.2%    |
| Nereta        | 1         | 0.2%    |
| Mirnijs       | 1         | 0.2%    |
| Lizums        | 1         | 0.2%    |
| Lielvārde    | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 105       | 152    | 15.15%  |
| Samsung Electronics          | 105       | 169    | 15.15%  |
| WDC                          | 101       | 152    | 14.57%  |
| Kingston                     | 64        | 103    | 9.24%   |
| Toshiba                      | 39        | 52     | 5.63%   |
| Hitachi                      | 21        | 27     | 3.03%   |
| Crucial                      | 20        | 38     | 2.89%   |
| Intel                        | 18        | 27     | 2.6%    |
| Unknown                      | 17        | 23     | 2.45%   |
| Sandisk                      | 15        | 28     | 2.16%   |
| Micron Technology            | 14        | 16     | 2.02%   |
| HGST                         | 14        | 23     | 2.02%   |
| A-DATA Technology            | 14        | 16     | 2.02%   |
| SK hynix                     | 12        | 14     | 1.73%   |
| Phison Electronics           | 8         | 10     | 1.15%   |
| Patriot                      | 8         | 15     | 1.15%   |
| KIOXIA                       | 8         | 11     | 1.15%   |
| GOODRAM                      | 8         | 17     | 1.15%   |
| SPCC                         | 7         | 9      | 1.01%   |
| Kingston Technology Company  | 7         | 8      | 1.01%   |
| OCZ                          | 5         | 7      | 0.72%   |
| China                        | 5         | 5      | 0.72%   |
| Apple                        | 5         | 5      | 0.72%   |
| Shenzhen Longsys Electronics | 4         | 4      | 0.58%   |
| Lexar                        | 4         | 4      | 0.58%   |
| Unknown                      | 4         | 7      | 0.58%   |
| Transcend                    | 3         | 5      | 0.43%   |
| Silicon Motion               | 3         | 4      | 0.43%   |
| Phison                       | 3         | 3      | 0.43%   |
| KingSpec                     | 3         | 3      | 0.43%   |
| Intenso                      | 3         | 3      | 0.43%   |
| ADATA Technology             | 3         | 4      | 0.43%   |
| XPG                          | 2         | 2      | 0.29%   |
| Realtek Semiconductor        | 2         | 2      | 0.29%   |
| Netac                        | 2         | 2      | 0.29%   |
| MAXIO Technology (Hangzhou)  | 2         | 2      | 0.29%   |
| LITEON                       | 2         | 2      | 0.29%   |
| Integral                     | 2         | 2      | 0.29%   |
| Hewlett-Packard              | 2         | 3      | 0.29%   |
| Verbatim                     | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 18        | 2.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 10        | 1.31%   |
| Kingston SV300S37A120G 120GB SSD                  | 9         | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB                    | 8         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB                   | 7         | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB                    | 7         | 0.92%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 0.79%   |
| Samsung SSD 850 EVO 500GB                         | 6         | 0.79%   |
| Kingston SA400S37480G 480GB SSD                   | 6         | 0.79%   |
| Samsung SSD 860 EVO 500GB                         | 5         | 0.66%   |
| Samsung SSD 850 EVO 250GB                         | 5         | 0.66%   |
| Crucial CT500MX500SSD1 500GB                      | 5         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                       | 5         | 0.66%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 0.53%   |
| Seagate ST1000LM048-2E7172 1TB                    | 4         | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 4         | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB                    | 4         | 0.53%   |
| Phison PS5013 E13 NVMe Controller 500GB           | 4         | 0.53%   |
| Patriot Burst 120GB SSD                           | 4         | 0.53%   |
| Kingston SV300S37A60G 64GB SSD                    | 4         | 0.53%   |
| Kingston SV300S37A240G 240GB SSD                  | 4         | 0.53%   |
| Kingston SA400S37120G 120GB SSD                   | 4         | 0.53%   |
| Hitachi HTS545050B9A300 500GB                     | 4         | 0.53%   |
| HGST HTS545050A7E680 500GB                        | 4         | 0.53%   |
| Unknown                                           | 4         | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 3         | 0.39%   |
| WDC WD2000JD-00HBB0 200GB                         | 3         | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 3         | 0.39%   |
| Unknown MMC Card  128GB                           | 3         | 0.39%   |
| Toshiba MQ04ABF100 1TB                            | 3         | 0.39%   |
| SPCC Solid State Disk 2TB                         | 3         | 0.39%   |
| Seagate ST9500325AS 500GB                         | 3         | 0.39%   |
| Seagate ST9160821AS 160GB                         | 3         | 0.39%   |
| Seagate ST500LT012-9WS142 500GB                   | 3         | 0.39%   |
| Seagate ST500DM005 HD502HJ 500GB                  | 3         | 0.39%   |
| Seagate ST500DM002-1BD142 500GB                   | 3         | 0.39%   |
| Seagate ST3500418AS 500GB                         | 3         | 0.39%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD               | 3         | 0.39%   |
| Samsung SSD 870 QVO 1TB                           | 3         | 0.39%   |
| Samsung SSD 860 PRO 256GB                         | 3         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 105       | 151    | 37.5%   |
| WDC                 | 82        | 123    | 29.29%  |
| Toshiba             | 33        | 46     | 11.79%  |
| Hitachi             | 21        | 27     | 7.5%    |
| Samsung Electronics | 17        | 30     | 6.07%   |
| HGST                | 14        | 23     | 5%      |
| USB                 | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |
| Maxtor              | 1         | 1      | 0.36%   |
| JMicron Technology  | 1         | 2      | 0.36%   |
| IBM/Hitachi         | 1         | 1      | 0.36%   |
| Hewlett-Packard     | 1         | 2      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 57        | 93     | 24.36%  |
| Samsung Electronics | 45        | 69     | 19.23%  |
| Crucial             | 20        | 38     | 8.55%   |
| WDC                 | 15        | 18     | 6.41%   |
| A-DATA Technology   | 14        | 16     | 5.98%   |
| Patriot             | 8         | 15     | 3.42%   |
| GOODRAM             | 8         | 17     | 3.42%   |
| SPCC                | 7         | 9      | 2.99%   |
| SanDisk             | 5         | 8      | 2.14%   |
| OCZ                 | 5         | 7      | 2.14%   |
| Intel               | 5         | 11     | 2.14%   |
| China               | 5         | 5      | 2.14%   |
| Apple               | 4         | 4      | 1.71%   |
| Micron Technology   | 3         | 3      | 1.28%   |
| Lexar               | 3         | 3      | 1.28%   |
| KingSpec            | 3         | 3      | 1.28%   |
| Intenso             | 3         | 3      | 1.28%   |
| Transcend           | 2         | 4      | 0.85%   |
| LITEON              | 2         | 2      | 0.85%   |
| Integral            | 2         | 2      | 0.85%   |
| Unknown             | 2         | 4      | 0.85%   |
| Verbatim            | 1         | 1      | 0.43%   |
| Toshiba             | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| Seagate             | 1         | 1      | 0.43%   |
| PNY                 | 1         | 1      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| Platinet            | 1         | 1      | 0.43%   |
| Mushkin             | 1         | 3      | 0.43%   |
| LuminouTek          | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| LITEON C            | 1         | 1      | 0.43%   |
| Lite-On             | 1         | 1      | 0.43%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.43%   |
| KingFast            | 1         | 4      | 0.43%   |
| GLOWAY              | 1         | 2      | 0.43%   |
| CHN25SATAS1         | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 237       | 410    | 38.66%  |
| SSD     | 198       | 356    | 32.3%   |
| NVMe    | 160       | 225    | 26.1%   |
| MMC     | 13        | 20     | 2.12%   |
| Unknown | 5         | 31     | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 352       | 770    | 64.83%  |
| NVMe | 160       | 223    | 29.47%  |
| SAS  | 18        | 29     | 3.31%   |
| MMC  | 13        | 20     | 2.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 282       | 499    | 63.37%  |
| 0.51-1.0   | 123       | 204    | 27.64%  |
| 1.01-2.0   | 27        | 41     | 6.07%   |
| 2.01-3.0   | 5         | 11     | 1.12%   |
| 4.01-10.0  | 5         | 6      | 1.12%   |
| 3.01-4.0   | 3         | 5      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 155       | 30.33%  |
| 251-500        | 100       | 19.57%  |
| 501-1000       | 66        | 12.92%  |
| 1001-2000      | 48        | 9.39%   |
| 1-20           | 36        | 7.05%   |
| 51-100         | 36        | 7.05%   |
| More than 3000 | 24        | 4.7%    |
| 21-50          | 19        | 3.72%   |
| 2001-3000      | 14        | 2.74%   |
| Unknown        | 13        | 2.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 201       | 37.85%  |
| 21-50          | 83        | 15.63%  |
| 101-250        | 66        | 12.43%  |
| 51-100         | 59        | 11.11%  |
| 251-500        | 46        | 8.66%   |
| 501-1000       | 34        | 6.4%    |
| 1001-2000      | 17        | 3.2%    |
| Unknown        | 13        | 2.45%   |
| 2001-3000      | 9         | 1.69%   |
| More than 3000 | 3         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 4.17%   |
| WDC WD20EARX-00PASB0 2TB              | 2         | 4      | 2.78%   |
| WDC WD2000JD-00HBB0 200GB             | 2         | 4      | 2.78%   |
| Seagate ST9500325AS 500GB             | 2         | 4      | 2.78%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 8      | 2.78%   |
| Samsung Electronics SP2504C 250GB     | 2         | 2      | 2.78%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 8      | 2.78%   |
| Kingston SV300S37A60G 64GB SSD        | 2         | 2      | 2.78%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 2.78%   |
| A-DATA Technology SU800NS38 512GB SSD | 2         | 3      | 2.78%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1         | 1      | 1.39%   |
| WDC WD800JD-60MSA1 80GB               | 1         | 1      | 1.39%   |
| WDC WD5002AALX-00J37A0 500GB          | 1         | 1      | 1.39%   |
| WDC WD5001AALS-00L3B2 500GB           | 1         | 1      | 1.39%   |
| WDC WD5001AALS-00E3A0 500GB           | 1         | 1      | 1.39%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 1.39%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 1.39%   |
| WDC WD3200BEVT-75ZCT0 320GB           | 1         | 4      | 1.39%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1         | 1      | 1.39%   |
| WDC WD1600BEVS-60RST0 160GB           | 1         | 1      | 1.39%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1         | 1      | 1.39%   |
| WDC WD Green 2.5 1000GB               | 1         | 1      | 1.39%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.39%   |
| Toshiba MK8034GSX 80GB                | 1         | 1      | 1.39%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.39%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 1.39%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.39%   |
| SSSTC CL4-4D256-Q79 256GB             | 1         | 1      | 1.39%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.39%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.39%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.39%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.39%   |
| Seagate ST3500820AS 500GB             | 1         | 1      | 1.39%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 1.39%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 1.39%   |
| Seagate ST340016A 40GB                | 1         | 1      | 1.39%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 1.39%   |
| Seagate ST3250312AS 250GB             | 1         | 1      | 1.39%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.39%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 31     | 31.88%  |
| WDC                 | 14        | 23     | 20.29%  |
| Samsung Electronics | 8         | 14     | 11.59%  |
| HGST                | 8         | 11     | 11.59%  |
| Toshiba             | 5         | 5      | 7.25%   |
| Kingston            | 4         | 5      | 5.8%    |
| Hitachi             | 4         | 4      | 5.8%    |
| A-DATA Technology   | 2         | 3      | 2.9%    |
| SSSTC               | 1         | 1      | 1.45%   |
| CHN25SATAS1         | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 31     | 37.93%  |
| WDC                 | 13        | 21     | 22.41%  |
| HGST                | 8         | 11     | 13.79%  |
| Samsung Electronics | 6         | 12     | 10.34%  |
| Toshiba             | 5         | 5      | 8.62%   |
| Hitachi             | 4         | 4      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 84     | 80.33%  |
| SSD  | 8         | 10     | 13.11%  |
| NVMe | 4         | 4      | 6.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB                                   | 1         | 1      | 33.33%  |
| Seagate ST500LT012-1DG142 500GB                               | 1         | 1      | 33.33%  |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 243       | 538    | 47.37%  |
| Works    | 208       | 403    | 40.55%  |
| Malfunc  | 59        | 98     | 11.5%   |
| Failed   | 3         | 3      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 318       | 53.36%  |
| AMD                              | 85        | 14.26%  |
| Samsung Electronics              | 54        | 9.06%   |
| SanDisk                          | 19        | 3.19%   |
| Kingston Technology Company      | 15        | 2.52%   |
| SK hynix                         | 12        | 2.01%   |
| Phison Electronics               | 11        | 1.85%   |
| Micron Technology                | 11        | 1.85%   |
| KIOXIA                           | 9         | 1.51%   |
| Nvidia                           | 8         | 1.34%   |
| Marvell Technology Group         | 8         | 1.34%   |
| JMicron Technology               | 8         | 1.34%   |
| ADATA Technology                 | 6         | 1.01%   |
| Toshiba America Info Systems     | 4         | 0.67%   |
| Silicon Motion                   | 4         | 0.67%   |
| Shenzhen Longsys Electronics     | 4         | 0.67%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.67%   |
| ASMedia Technology               | 4         | 0.67%   |
| Union Memory (Shenzhen)          | 2         | 0.34%   |
| Realtek Semiconductor            | 2         | 0.34%   |
| Transcend                        | 1         | 0.17%   |
| Solidigm                         | 1         | 0.17%   |
| Solid State Storage Technology   | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Silicon Image                    | 1         | 0.17%   |
| Micron/Crucial Technology        | 1         | 0.17%   |
| LSI Logic / Symbios Logic        | 1         | 0.17%   |
| Lite-On Technology               | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 53        | 7.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 4.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 3.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 2.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 2.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 18        | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 12        | 1.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 12        | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 1.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                         | 10        | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 1.45%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 7         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.01%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.87%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 6         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 0.87%   |
| Intel SSD 660P Series                                                          | 6         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 0.87%   |
| AMD 600 Series Chipset SATA Controller                                         | 6         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 0.72%   |
| Nvidia MCP61 SATA Controller                                                   | 5         | 0.72%   |
| Nvidia MCP61 IDE                                                               | 5         | 0.72%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 5         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 343       | 56.23%  |
| NVMe | 163       | 26.72%  |
| IDE  | 72        | 11.8%   |
| RAID | 32        | 5.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 345       | 73.72%  |
| AMD    | 118       | 25.21%  |
| ARM    | 5         | 1.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.28%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 6         | 1.28%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 1.28%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.07%   |
| ARM Processor                                 | 5         | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.07%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.64%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 0.64%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.64%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.64%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.64%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 0.64%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.64%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 0.64%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 0.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.64%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 0.64%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.64%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 3         | 0.64%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.64%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3         | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 97        | 20.73%  |
| Intel Core i7           | 63        | 13.46%  |
| Other                   | 42        | 8.97%   |
| Intel Core i3           | 42        | 8.97%   |
| AMD Ryzen 5             | 34        | 7.26%   |
| Intel Core 2 Duo        | 28        | 5.98%   |
| AMD Ryzen 7             | 24        | 5.13%   |
| Intel Celeron           | 22        | 4.7%    |
| Intel Pentium           | 12        | 2.56%   |
| Intel Pentium Dual-Core | 9         | 1.92%   |
| AMD Ryzen 9             | 7         | 1.5%    |
| AMD A8                  | 7         | 1.5%    |
| Intel Xeon              | 6         | 1.28%   |
| Intel Pentium Dual      | 6         | 1.28%   |
| AMD FX                  | 6         | 1.28%   |
| Intel Pentium D         | 5         | 1.07%   |
| Intel Core 2 Quad       | 5         | 1.07%   |
| Intel Core 2            | 5         | 1.07%   |
| Intel Core              | 4         | 0.85%   |
| AMD Ryzen 7 PRO         | 4         | 0.85%   |
| Intel Genuine           | 3         | 0.64%   |
| AMD Ryzen 3             | 3         | 0.64%   |
| AMD Athlon II X2        | 3         | 0.64%   |
| AMD Athlon 64 X2        | 3         | 0.64%   |
| AMD A10                 | 3         | 0.64%   |
| Intel Core i9           | 2         | 0.43%   |
| AMD Turion 64 X2 Mobile | 2         | 0.43%   |
| AMD Ryzen Threadripper  | 2         | 0.43%   |
| AMD Ryzen 5 PRO         | 2         | 0.43%   |
| AMD E1                  | 2         | 0.43%   |
| AMD A4                  | 2         | 0.43%   |
| Intel Pentium Gold      | 1         | 0.21%   |
| Intel Pentium 4         | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| Intel Atom              | 1         | 0.21%   |
| AMD Sempron             | 1         | 0.21%   |
| AMD E2                  | 1         | 0.21%   |
| AMD E                   | 1         | 0.21%   |
| AMD C-70                | 1         | 0.21%   |
| AMD Athlon II X4        | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 211       | 44.89%  |
| 4       | 138       | 29.36%  |
| 6       | 45        | 9.57%   |
| 8       | 38        | 8.09%   |
| 12      | 8         | 1.7%    |
| 16      | 7         | 1.49%   |
| 1       | 7         | 1.49%   |
| 3       | 5         | 1.06%   |
| 10      | 4         | 0.85%   |
| 24      | 3         | 0.64%   |
| 14      | 2         | 0.43%   |
| Unknown | 2         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 464       | 99.15%  |
| 2       | 3         | 0.64%   |
| Unknown | 1         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 302       | 64.26%  |
| 1       | 166       | 35.32%  |
| Unknown | 2         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 464       | 99.15%  |
| Unknown        | 3         | 0.64%   |
| 32-bit         | 1         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 198       | 41.08%  |
| 0x306a9    | 18        | 3.73%   |
| 0x1067a    | 18        | 3.73%   |
| 0x306c3    | 17        | 3.53%   |
| 0x206a7    | 17        | 3.53%   |
| 0x906ea    | 12        | 2.49%   |
| 0x6fd      | 12        | 2.49%   |
| 0x406e3    | 12        | 2.49%   |
| 0x30678    | 9         | 1.87%   |
| 0x20655    | 8         | 1.66%   |
| 0x806c1    | 7         | 1.45%   |
| 0x306d4    | 7         | 1.45%   |
| 0x10676    | 7         | 1.45%   |
| 0x06001119 | 7         | 1.45%   |
| 0x806ec    | 6         | 1.24%   |
| 0x506e3    | 6         | 1.24%   |
| 0x40651    | 5         | 1.04%   |
| 0x08701021 | 5         | 1.04%   |
| 0x906e9    | 4         | 0.83%   |
| 0x806ea    | 4         | 0.83%   |
| 0x806e9    | 4         | 0.83%   |
| 0x6fb      | 4         | 0.83%   |
| 0x08108102 | 4         | 0.83%   |
| 0xa0652    | 3         | 0.62%   |
| 0x6f6      | 3         | 0.62%   |
| 0x20652    | 3         | 0.62%   |
| 0x0a50000d | 3         | 0.62%   |
| 0x0a404102 | 3         | 0.62%   |
| 0x06000852 | 3         | 0.62%   |
| 0x05000119 | 3         | 0.62%   |
| 0xf65      | 2         | 0.41%   |
| 0xf47      | 2         | 0.41%   |
| 0x906ed    | 2         | 0.41%   |
| 0x906ec    | 2         | 0.41%   |
| 0x906a3    | 2         | 0.41%   |
| 0x706a8    | 2         | 0.41%   |
| 0x706a1    | 2         | 0.41%   |
| 0x6fa      | 2         | 0.41%   |
| 0x6f2      | 2         | 0.41%   |
| 0x406c3    | 2         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 54        | 11.54%  |
| Haswell           | 36        | 7.69%   |
| SandyBridge       | 34        | 7.26%   |
| Penryn            | 32        | 6.84%   |
| Unknown           | 31        | 6.62%   |
| IvyBridge         | 28        | 5.98%   |
| Core              | 26        | 5.56%   |
| Zen 2             | 25        | 5.34%   |
| Skylake           | 24        | 5.13%   |
| Zen 3             | 20        | 4.27%   |
| Westmere          | 17        | 3.63%   |
| TigerLake         | 17        | 3.63%   |
| Silvermont        | 17        | 3.63%   |
| Piledriver        | 14        | 2.99%   |
| Broadwell         | 13        | 2.78%   |
| Zen+              | 10        | 2.14%   |
| Alderlake Hybrid  | 9         | 1.92%   |
| CometLake         | 8         | 1.71%   |
| NetBurst          | 6         | 1.28%   |
| K8 Hammer         | 6         | 1.28%   |
| Zen               | 5         | 1.07%   |
| K10               | 5         | 1.07%   |
| Nehalem           | 4         | 0.85%   |
| Goldmont plus     | 4         | 0.85%   |
| Meteorlake Hybrid | 3         | 0.64%   |
| Jaguar            | 3         | 0.64%   |
| Icelake           | 3         | 0.64%   |
| Bobcat            | 3         | 0.64%   |
| Steamroller       | 2         | 0.43%   |
| Puma              | 2         | 0.43%   |
| Excavator         | 2         | 0.43%   |
| P6                | 1         | 0.21%   |
| Lunarlake Hybrid  | 1         | 0.21%   |
| K10 Llano         | 1         | 0.21%   |
| Goldmont          | 1         | 0.21%   |
| Bulldozer         | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 257       | 47.16%  |
| Nvidia                     | 159       | 29.17%  |
| AMD                        | 128       | 23.49%  |
| Matrox Electronics Systems | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 3.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 3.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 2.47%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 14        | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 2.3%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 13        | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.41%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 8         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.24%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 6         | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.06%   |
| AMD Raphael                                                                              | 6         | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 5         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.88%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 5         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.71%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.71%   |
| AMD Rembrandt [Radeon 680M]                                                              | 4         | 0.71%   |
| AMD Barcelo                                                                              | 4         | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.53%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 179       | 38%     |
| 1 x AMD        | 100       | 21.23%  |
| 1 x Nvidia     | 90        | 19.11%  |
| Intel + Nvidia | 61        | 12.95%  |
| 2 x AMD        | 12        | 2.55%   |
| Intel + AMD    | 10        | 2.12%   |
| AMD + Nvidia   | 7         | 1.49%   |
| Other          | 5         | 1.06%   |
| 2 x Intel      | 5         | 1.06%   |
| 2 x Nvidia     | 1         | 0.21%   |
| 1 x Matrox     | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 371       | 77.13%  |
| Proprietary | 83        | 17.26%  |
| Unknown     | 27        | 5.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 266       | 55.07%  |
| 1.01-2.0   | 58        | 12.01%  |
| 0.01-0.5   | 57        | 11.8%   |
| 0.51-1.0   | 35        | 7.25%   |
| 3.01-4.0   | 28        | 5.8%    |
| 7.01-8.0   | 16        | 3.31%   |
| 5.01-6.0   | 13        | 2.69%   |
| 16.01-24.0 | 4         | 0.83%   |
| 8.01-16.0  | 4         | 0.83%   |
| 2.01-3.0   | 2         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 76        | 14.96%  |
| AU Optronics            | 72        | 14.17%  |
| LG Display              | 48        | 9.45%   |
| BOE                     | 42        | 8.27%   |
| Dell                    | 38        | 7.48%   |
| Chimei Innolux          | 37        | 7.28%   |
| Goldstar                | 33        | 6.5%    |
| Philips                 | 19        | 3.74%   |
| BenQ                    | 17        | 3.35%   |
| AOC                     | 13        | 2.56%   |
| Hewlett-Packard         | 12        | 2.36%   |
| Lenovo                  | 10        | 1.97%   |
| Chi Mei Optoelectronics | 8         | 1.57%   |
| Apple                   | 8         | 1.57%   |
| Ancor Communications    | 7         | 1.38%   |
| PANDA                   | 6         | 1.18%   |
| Unknown                 | 4         | 0.79%   |
| LG Electronics          | 4         | 0.79%   |
| ASUSTek Computer        | 4         | 0.79%   |
| Acer                    | 4         | 0.79%   |
| Sharp                   | 3         | 0.59%   |
| NEC Computers           | 3         | 0.59%   |
| MSI                     | 3         | 0.59%   |
| LG Philips              | 3         | 0.59%   |
| InfoVision              | 3         | 0.59%   |
| ViewSonic               | 2         | 0.39%   |
| Valve                   | 2         | 0.39%   |
| Sony                    | 2         | 0.39%   |
| Seiko/Epson             | 2         | 0.39%   |
| Mi                      | 2         | 0.39%   |
| IBM                     | 2         | 0.39%   |
| Hitachi                 | 2         | 0.39%   |
| Arnos Instruments       | 2         | 0.39%   |
| Xiaomi                  | 1         | 0.2%    |
| Wacom                   | 1         | 0.2%    |
| Tianma XM               | 1         | 0.2%    |
| SKG                     | 1         | 0.2%    |
| Quanta Display          | 1         | 0.2%    |
| Plain Tree Systems      | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 1.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.75%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.57%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                 | 3         | 0.57%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 3         | 0.57%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.57%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.57%   |
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                     | 3         | 0.57%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                       | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.57%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.57%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                      | 2         | 0.38%   |
| Samsung Electronics SyncMaster SAM0059 2048x1536 320x240mm 15.7-inch     | 2         | 0.38%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch        | 2         | 0.38%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.38%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch       | 2         | 0.38%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.38%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 2         | 0.38%   |
| LG Electronics LCD Monitor LG TV 1920x1080                               | 2         | 0.38%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                     | 2         | 0.38%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.38%   |
| Hewlett-Packard w19b/w19e HWP26A1 1440x900 410x256mm 19.0-inch           | 2         | 0.38%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 677x290mm 29.0-inch                 | 2         | 0.38%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 2         | 0.38%   |
| Dell S2721D DELA19A 2560x1440 597x336mm 27.0-inch                        | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 185       | 38.14%  |
| 1366x768 (WXGA)    | 97        | 20%     |
| 2560x1440 (QHD)    | 33        | 6.8%    |
| 3840x2160 (4K)     | 25        | 5.15%   |
| 1600x900 (HD+)     | 20        | 4.12%   |
| 1280x1024 (SXGA)   | 20        | 4.12%   |
| 1440x900 (WXGA+)   | 16        | 3.3%    |
| 1280x800 (WXGA)    | 16        | 3.3%    |
| 1920x1200 (WUXGA)  | 15        | 3.09%   |
| 1680x1050 (WSXGA+) | 12        | 2.47%   |
| 2560x1080          | 6         | 1.24%   |
| 2560x1600          | 5         | 1.03%   |
| Unknown            | 5         | 1.03%   |
| 3440x1440          | 4         | 0.82%   |
| 2880x1800          | 3         | 0.62%   |
| 1360x768           | 3         | 0.62%   |
| 800x1280           | 2         | 0.41%   |
| 4480x1440          | 2         | 0.41%   |
| 3840x1080          | 2         | 0.41%   |
| 2048x1536          | 2         | 0.41%   |
| 1024x768 (XGA)     | 2         | 0.41%   |
| 7680x2160          | 1         | 0.21%   |
| 3840x2400          | 1         | 0.21%   |
| 3520x1200          | 1         | 0.21%   |
| 3456x2160          | 1         | 0.21%   |
| 3000x2000          | 1         | 0.21%   |
| 2960x1050          | 1         | 0.21%   |
| 2288x1287          | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 1280x960           | 1         | 0.21%   |
| 1280x720 (HD)      | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 159       | 31.18%  |
| 24      | 47        | 9.22%   |
| 14      | 37        | 7.25%   |
| 13      | 35        | 6.86%   |
| 27      | 32        | 6.27%   |
| 17      | 30        | 5.88%   |
| Unknown | 23        | 4.51%   |
| 23      | 21        | 4.12%   |
| 21      | 17        | 3.33%   |
| 19      | 17        | 3.33%   |
| 12      | 13        | 2.55%   |
| 31      | 11        | 2.16%   |
| 18      | 10        | 1.96%   |
| 34      | 8         | 1.57%   |
| 22      | 7         | 1.37%   |
| 40      | 6         | 1.18%   |
| 20      | 6         | 1.18%   |
| 16      | 6         | 1.18%   |
| 25      | 5         | 0.98%   |
| 11      | 4         | 0.78%   |
| 84      | 2         | 0.39%   |
| 65      | 2         | 0.39%   |
| 35      | 2         | 0.39%   |
| 28      | 2         | 0.39%   |
| 26      | 2         | 0.39%   |
| 7       | 2         | 0.39%   |
| 142     | 1         | 0.2%    |
| 48      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 33      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 220       | 44.18%  |
| 501-600        | 94        | 18.88%  |
| 401-500        | 43        | 8.63%   |
| 351-400        | 39        | 7.83%   |
| 201-300        | 37        | 7.43%   |
| Unknown        | 23        | 4.62%   |
| 601-700        | 16        | 3.21%   |
| 701-800        | 9         | 1.81%   |
| 801-900        | 8         | 1.61%   |
| 1001-1500      | 3         | 0.6%    |
| 1501-2000      | 2         | 0.4%    |
| 1-100          | 2         | 0.4%    |
| More than 2000 | 1         | 0.2%    |
| 901-1000       | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 325       | 70.19%  |
| 16/10   | 73        | 15.77%  |
| 5/4     | 21        | 4.54%   |
| Unknown | 21        | 4.54%   |
| 21/9    | 10        | 2.16%   |
| 4/3     | 5         | 1.08%   |
| 3/2     | 4         | 0.86%   |
| 0.62    | 2         | 0.43%   |
| 32/9    | 1         | 0.22%   |
| 1.00    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 156       | 30.83%  |
| 201-250        | 72        | 14.23%  |
| 81-90          | 58        | 11.46%  |
| 301-350        | 33        | 6.52%   |
| 151-200        | 31        | 6.13%   |
| 351-500        | 24        | 4.74%   |
| Unknown        | 23        | 4.55%   |
| 121-130        | 21        | 4.15%   |
| 251-300        | 19        | 3.75%   |
| 141-150        | 14        | 2.77%   |
| 71-80          | 13        | 2.57%   |
| 61-70          | 13        | 2.57%   |
| 501-1000       | 8         | 1.58%   |
| 111-120        | 6         | 1.19%   |
| More than 1000 | 4         | 0.79%   |
| 51-60          | 4         | 0.79%   |
| 91-100         | 3         | 0.59%   |
| 1-40           | 2         | 0.4%    |
| 131-140        | 2         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 160       | 32.26%  |
| 121-160       | 142       | 28.63%  |
| 101-120       | 131       | 26.41%  |
| 161-240       | 29        | 5.85%   |
| Unknown       | 23        | 4.64%   |
| More than 240 | 6         | 1.21%   |
| 1-50          | 5         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 389       | 81.55%  |
| 2     | 62        | 13%     |
| 0     | 17        | 3.56%   |
| 3     | 8         | 1.68%   |
| 4     | 1         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 252       | 36%     |
| Intel                             | 204       | 29.14%  |
| Qualcomm Atheros                  | 75        | 10.71%  |
| Broadcom                          | 40        | 5.71%   |
| TP-Link                           | 14        | 2%      |
| MediaTek                          | 14        | 2%      |
| Broadcom Limited                  | 13        | 1.86%   |
| Ralink Technology                 | 11        | 1.57%   |
| Ralink                            | 11        | 1.57%   |
| Marvell Technology Group          | 10        | 1.43%   |
| Samsung Electronics               | 9         | 1.29%   |
| Nvidia                            | 6         | 0.86%   |
| Xiaomi                            | 5         | 0.71%   |
| Lenovo                            | 4         | 0.57%   |
| vivo                              | 3         | 0.43%   |
| Qualcomm Atheros Communications   | 3         | 0.43%   |
| Qualcomm                          | 3         | 0.43%   |
| Huawei Technologies               | 3         | 0.43%   |
| U-Blox                            | 2         | 0.29%   |
| Qualcomm Technologies             | 2         | 0.29%   |
| Hewlett-Packard                   | 2         | 0.29%   |
| ASIX Electronics                  | 2         | 0.29%   |
| Aquantia                          | 2         | 0.29%   |
| Wilocity                          | 1         | 0.14%   |
| Sundance Technology Inc / IC Plus | 1         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.14%   |
| Shenzhen Goodix Technology        | 1         | 0.14%   |
| Google                            | 1         | 0.14%   |
| DisplayLink                       | 1         | 0.14%   |
| Dell                              | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| ASUSTek Computer                  | 1         | 0.14%   |
| 3Com                              | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 171       | 20.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 4.59%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 1.45%   |
| Intel Wireless 8260                                                    | 12        | 1.45%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.21%   |
| Intel Wireless 8265 / 8275                                             | 10        | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                         | 7         | 0.85%   |
| Intel Wireless 7265                                                    | 7         | 0.85%   |
| Intel Wireless 3160                                                    | 7         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 6         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 6         | 0.72%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 5         | 0.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.6%    |
| Intel Wireless 7260                                                    | 5         | 0.6%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 0.6%    |
| Intel Ethernet Controller I225-V                                       | 5         | 0.6%    |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.6%    |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                               | 5         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 164       | 44.57%  |
| Qualcomm Atheros                | 60        | 16.3%   |
| Realtek Semiconductor           | 54        | 14.67%  |
| Broadcom                        | 25        | 6.79%   |
| TP-Link                         | 14        | 3.8%    |
| MediaTek                        | 13        | 3.53%   |
| Ralink Technology               | 11        | 2.99%   |
| Ralink                          | 11        | 2.99%   |
| Broadcom Limited                | 7         | 1.9%    |
| Qualcomm Atheros Communications | 3         | 0.82%   |
| Qualcomm                        | 3         | 0.82%   |
| Wilocity                        | 1         | 0.27%   |
| D-Link System                   | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 3.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 3.23%   |
| Intel Wireless 8260                                            | 12        | 3.23%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 2.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.7%    |
| Intel Wireless 8265 / 8275                                     | 10        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 2.16%   |
| Ralink RT5370 Wireless Adapter                                 | 7         | 1.89%   |
| Intel Wireless 7265                                            | 7         | 1.89%   |
| Intel Wireless 3160                                            | 7         | 1.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 6         | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 6         | 1.62%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.35%   |
| Intel Wireless 7260                                            | 5         | 1.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 5         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 1.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 1.08%   |
| Intel WiFi Link 5100                                           | 4         | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4         | 1.08%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.81%   |
| Realtek 802.11ac NIC                                           | 3         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.81%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 3         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 236       | 53.27%  |
| Intel                             | 102       | 23.02%  |
| Broadcom                          | 24        | 5.42%   |
| Qualcomm Atheros                  | 22        | 4.97%   |
| Marvell Technology Group          | 10        | 2.26%   |
| Samsung Electronics               | 9         | 2.03%   |
| Nvidia                            | 6         | 1.35%   |
| Broadcom Limited                  | 6         | 1.35%   |
| Xiaomi                            | 5         | 1.13%   |
| Lenovo                            | 4         | 0.9%    |
| vivo                              | 3         | 0.68%   |
| Qualcomm Technologies             | 2         | 0.45%   |
| Huawei Technologies               | 2         | 0.45%   |
| ASIX Electronics                  | 2         | 0.45%   |
| Aquantia                          | 2         | 0.45%   |
| Sundance Technology Inc / IC Plus | 1         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.23%   |
| MediaTek                          | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Google                            | 1         | 0.23%   |
| DisplayLink                       | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| 3Com                              | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 171       | 37.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 8.41%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 2.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 1.99%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 1.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5         | 1.11%   |
| Intel Ethernet Controller I225-V                                       | 5         | 1.11%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.11%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.66%   |
| vivo 1820                                                              | 3         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.66%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 0.66%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.66%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.66%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 0.44%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 2         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 411       | 53.38%  |
| WiFi     | 354       | 45.97%  |
| Modem    | 5         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 283       | 59.7%   |
| Ethernet | 191       | 40.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 276       | 58.97%  |
| 1     | 174       | 37.18%  |
| 0     | 10        | 2.14%   |
| 3     | 7         | 1.5%    |
| 4     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 439       | 93.4%   |
| Yes  | 31        | 6.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 42.2%   |
| Realtek Semiconductor           | 35        | 12.41%  |
| IMC Networks                    | 21        | 7.45%   |
| Qualcomm Atheros Communications | 16        | 5.67%   |
| Cambridge Silicon Radio         | 14        | 4.96%   |
| Lite-On Technology              | 13        | 4.61%   |
| Broadcom                        | 13        | 4.61%   |
| Apple                           | 10        | 3.55%   |
| Foxconn / Hon Hai               | 7         | 2.48%   |
| Dell                            | 6         | 2.13%   |
| TP-Link                         | 5         | 1.77%   |
| ASUSTek Computer                | 5         | 1.77%   |
| Hewlett-Packard                 | 4         | 1.42%   |
| Toshiba                         | 3         | 1.06%   |
| MediaTek                        | 3         | 1.06%   |
| Ralink                          | 2         | 0.71%   |
| USI                             | 1         | 0.35%   |
| Taiyo Yuden                     | 1         | 0.35%   |
| Ralink Technology               | 1         | 0.35%   |
| Qcom                            | 1         | 0.35%   |
| Fujitsu                         | 1         | 0.35%   |
| Edimax Technology               | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 13.83%  |
| Intel AX201 Bluetooth                               | 21        | 7.45%   |
| Realtek Bluetooth Radio                             | 19        | 6.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 6.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14        | 4.96%   |
| Intel AX200 Bluetooth                               | 13        | 4.61%   |
| IMC Networks Bluetooth Radio                        | 9         | 3.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 2.84%   |
| Intel Bluetooth Device                              | 8         | 2.84%   |
| Apple Bluetooth Host Controller                     | 8         | 2.84%   |
| TP-Link TP-T@- UB500 Adapter                        | 5         | 1.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.77%   |
| Intel AX210 Bluetooth                               | 5         | 1.77%   |
| IMC Networks Wireless_Device                        | 5         | 1.77%   |
| Realtek RTL8723B Bluetooth                          | 4         | 1.42%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.06%   |
| MediaTek Wireless_Device                            | 3         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.06%   |
| Lite-On Bluetooth Device                            | 3         | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.06%   |
| IMC Networks Bluetooth Device                       | 3         | 1.06%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.06%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 1.06%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.71%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.71%   |
| Realtek Bluetooth 5.3 Radio                         | 2         | 0.71%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.71%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.71%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.71%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 339       | 51.36%  |
| AMD                                          | 136       | 20.61%  |
| Nvidia                                       | 115       | 17.42%  |
| C-Media Electronics                          | 13        | 1.97%   |
| Logitech                                     | 8         | 1.21%   |
| Creative Technology                          | 4         | 0.61%   |
| Realtek Semiconductor                        | 3         | 0.45%   |
| Lenovo                                       | 3         | 0.45%   |
| Yamaha                                       | 2         | 0.3%    |
| Texas Instruments                            | 2         | 0.3%    |
| Razer USA                                    | 2         | 0.3%    |
| MV-SILICON                                   | 2         | 0.3%    |
| Micro Star International                     | 2         | 0.3%    |
| KTMicro                                      | 2         | 0.3%    |
| Hewlett-Packard                              | 2         | 0.3%    |
| Focusrite-Novation                           | 2         | 0.3%    |
| Creative Labs                                | 2         | 0.3%    |
| Unknown                                      | 2         | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.15%   |
| Trust                                        | 1         | 0.15%   |
| Syntek                                       | 1         | 0.15%   |
| SteelSeries ApS                              | 1         | 0.15%   |
| Sony                                         | 1         | 0.15%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.15%   |
| RODE Microphones                             | 1         | 0.15%   |
| Patriot Memory                               | 1         | 0.15%   |
| Microsoft                                    | 1         | 0.15%   |
| Kingston Technology                          | 1         | 0.15%   |
| JMTek                                        | 1         | 0.15%   |
| GYROCOM C&C                                  | 1         | 0.15%   |
| GN Netcom                                    | 1         | 0.15%   |
| FIFINE 683 Microphone                        | 1         | 0.15%   |
| BTD 600                                      | 1         | 0.15%   |
| AudioQuest                                   | 1         | 0.15%   |
| ASUSTek Computer                             | 1         | 0.15%   |
| ASRock                                       | 1         | 0.15%   |
| Apple                                        | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 50        | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31        | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29        | 3.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 28        | 3.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 27        | 3.46%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 25        | 3.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 2.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18        | 2.31%   |
| AMD FCH Azalia Controller                                                  | 18        | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.18%   |
| AMD Radeon High Definition Audio Controller                                | 16        | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 1.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 12        | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 1.54%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12        | 1.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 11        | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                              | 9         | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.03%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 0.77%   |
| AMD Trinity HDMI Audio Controller                                          | 6         | 0.77%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 6         | 0.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 0.77%   |
| Nvidia MCP61 High Definition Audio                                         | 5         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 61        | 19%     |
| Kingston                                | 54        | 16.82%  |
| SK hynix                                | 52        | 16.2%   |
| Unknown                                 | 50        | 15.58%  |
| Micron Technology                       | 21        | 6.54%   |
| Crucial                                 | 21        | 6.54%   |
| G.Skill                                 | 15        | 4.67%   |
| Corsair                                 | 11        | 3.43%   |
| Ramaxel Technology                      | 5         | 1.56%   |
| A-DATA Technology                       | 5         | 1.56%   |
| GOODRAM                                 | 4         | 1.25%   |
| Elpida                                  | 3         | 0.93%   |
| Unknown                                 | 3         | 0.93%   |
| Nanya Technology                        | 2         | 0.62%   |
| Unknown (ABCD)                          | 1         | 0.31%   |
| Toshiba                                 | 1         | 0.31%   |
| Team                                    | 1         | 0.31%   |
| Silicon Power Computer & Communications | 1         | 0.31%   |
| Silicon Power                           | 1         | 0.31%   |
| Ramos Technology                        | 1         | 0.31%   |
| PNY                                     | 1         | 0.31%   |
| Patriot Memory (PDP Systems)            | 1         | 0.31%   |
| Patriot                                 | 1         | 0.31%   |
| Lexar                                   | 1         | 0.31%   |
| INNOVATION PC                           | 1         | 0.31%   |
| Heoriady                                | 1         | 0.31%   |
| ASint Technology                        | 1         | 0.31%   |
| Apacer                                  | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 4         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 4         | 1.15%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 4         | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 1.15%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 4         | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s    | 4         | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 3         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s    | 3         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 0.86%   |
| Unknown                                                  | 3         | 0.86%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s               | 2         | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2         | 0.58%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 2         | 0.58%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                    | 2         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 2         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 2         | 0.58%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2         | 0.58%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 2         | 0.58%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 2         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.58%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 2         | 0.58%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 0.58%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 2         | 0.58%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 2         | 0.58%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s    | 2         | 0.58%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s   | 2         | 0.58%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s  | 2         | 0.58%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 2         | 0.58%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s      | 2         | 0.58%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s      | 2         | 0.58%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 2         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 102       | 38.35%  |
| DDR3    | 91        | 34.21%  |
| DDR2    | 23        | 8.65%   |
| Unknown | 12        | 4.51%   |
| SDRAM   | 10        | 3.76%   |
| DDR5    | 10        | 3.76%   |
| LPDDR5  | 7         | 2.63%   |
| LPDDR4  | 6         | 2.26%   |
| DDR     | 3         | 1.13%   |
| LPDDR3  | 1         | 0.38%   |
| DRAM    | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 167       | 63.5%   |
| DIMM         | 83        | 31.56%  |
| Row Of Chips | 11        | 4.18%   |
| Chip         | 1         | 0.38%   |
| Unknown      | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 89        | 29.67%  |
| 8192  | 86        | 28.67%  |
| 2048  | 49        | 16.33%  |
| 16384 | 43        | 14.33%  |
| 32768 | 16        | 5.33%   |
| 1024  | 14        | 4.67%   |
| 512   | 2         | 0.67%   |
| 49152 | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 61        | 20.13%  |
| 2667    | 38        | 12.54%  |
| 3200    | 36        | 11.88%  |
| 1333    | 22        | 7.26%   |
| 667     | 22        | 7.26%   |
| 2133    | 16        | 5.28%   |
| 2400    | 14        | 4.62%   |
| 1334    | 8         | 2.64%   |
| 800     | 8         | 2.64%   |
| 3600    | 7         | 2.31%   |
| Unknown | 7         | 2.31%   |
| 5600    | 5         | 1.65%   |
| 1066    | 5         | 1.65%   |
| 6400    | 4         | 1.32%   |
| 533     | 4         | 1.32%   |
| 4267    | 3         | 0.99%   |
| 3466    | 3         | 0.99%   |
| 1867    | 3         | 0.99%   |
| 8400    | 2         | 0.66%   |
| 4800    | 2         | 0.66%   |
| 4333    | 2         | 0.66%   |
| 3266    | 2         | 0.66%   |
| 2048    | 2         | 0.66%   |
| 1800    | 2         | 0.66%   |
| 1639    | 2         | 0.66%   |
| 1067    | 2         | 0.66%   |
| 8533    | 1         | 0.33%   |
| 7500    | 1         | 0.33%   |
| 7467    | 1         | 0.33%   |
| 6200    | 1         | 0.33%   |
| 6000    | 1         | 0.33%   |
| 5200    | 1         | 0.33%   |
| 4199    | 1         | 0.33%   |
| 3866    | 1         | 0.33%   |
| 3800    | 1         | 0.33%   |
| 3733    | 1         | 0.33%   |
| 3666    | 1         | 0.33%   |
| 3400    | 1         | 0.33%   |
| 3100    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 42.86%  |
| Samsung Electronics | 4         | 28.57%  |
| Canon               | 2         | 14.29%  |
| Seiko Epson         | 1         | 7.14%   |
| Brother Industries  | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP LaserJet 1018          | 2         | 14.29%  |
| Seiko Epson L3110 Series  | 1         | 7.14%   |
| Samsung SCX-4216F Scanner | 1         | 7.14%   |
| Samsung SCX-4100 Scanner  | 1         | 7.14%   |
| Samsung SCX-3200 Series   | 1         | 7.14%   |
| Samsung Composite Device  | 1         | 7.14%   |
| HP Officejet 4500 G510g-m | 1         | 7.14%   |
| HP LaserJet P1102         | 1         | 7.14%   |
| HP LaserJet 1010          | 1         | 7.14%   |
| HP DeskJet 5940           | 1         | 7.14%   |
| Canon PIXMA MG3000 series | 1         | 7.14%   |
| Canon MP140 ser           | 1         | 7.14%   |
| Brother DCP-L2510D series | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Seiko Epson    | 2         | 40%     |
| Mustek Systems | 2         | 40%     |
| Canon          | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB                | 2         | 40%     |
| Seiko Epson Perfection V37/V370                   | 1         | 20%     |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 23.1%   |
| IMC Networks                           | 28        | 9.66%   |
| Realtek Semiconductor                  | 23        | 7.93%   |
| Microdia                               | 20        | 6.9%    |
| Bison Electronics                      | 16        | 5.52%   |
| Logitech                               | 15        | 5.17%   |
| Suyin                                  | 12        | 4.14%   |
| Sunplus Innovation Technology          | 12        | 4.14%   |
| Quanta                                 | 12        | 4.14%   |
| Apple                                  | 10        | 3.45%   |
| Lite-On Technology                     | 9         | 3.1%    |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.1%    |
| Syntek                                 | 7         | 2.41%   |
| Luxvisions Innotech Limited            | 6         | 2.07%   |
| Z-Star Microelectronics                | 5         | 1.72%   |
| Shinetech                              | 4         | 1.38%   |
| Silicon Motion                         | 3         | 1.03%   |
| Ricoh                                  | 3         | 1.03%   |
| Lenovo                                 | 3         | 1.03%   |
| Samsung Electronics                    | 2         | 0.69%   |
| Microsoft                              | 2         | 0.69%   |
| Genesys Logic                          | 2         | 0.69%   |
| Acer                                   | 2         | 0.69%   |
| Tobii Technology AB                    | 1         | 0.34%   |
| SunplusIT                              | 1         | 0.34%   |
| Sonix Technology                       | 1         | 0.34%   |
| Razer USA                              | 1         | 0.34%   |
| Primax Electronics                     | 1         | 0.34%   |
| Pixart Imaging                         | 1         | 0.34%   |
| Philips (or NXP)                       | 1         | 0.34%   |
| OmniVision Technologies                | 1         | 0.34%   |
| KYE Systems (Mouse Systems)            | 1         | 0.34%   |
| Jieli Technology                       | 1         | 0.34%   |
| icSpring                               | 1         | 0.34%   |
| GEMBIRD                                | 1         | 0.34%   |
| DigiTech                               | 1         | 0.34%   |
| Cubeternet                             | 1         | 0.34%   |
| Arkmicro Technologies                  | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |
| Alcor Micro                            | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 13        | 4.42%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 9         | 3.06%   |
| IMC Networks Integrated Camera                              | 8         | 2.72%   |
| Realtek Integrated_Webcam_HD                                | 6         | 2.04%   |
| Lite-On Integrated Camera                                   | 6         | 2.04%   |
| Microdia Integrated_Webcam_HD                               | 5         | 1.7%    |
| Chicony Integrated Camera (1280x720@30)                     | 5         | 1.7%    |
| Chicony HD WebCam                                           | 5         | 1.7%    |
| Bison Lenovo EasyCamera                                     | 5         | 1.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                             | 5         | 1.7%    |
| Sunplus Asus Webcam                                         | 4         | 1.36%   |
| Realtek USB Camera                                          | 4         | 1.36%   |
| Microdia Integrated Webcam                                  | 4         | 1.36%   |
| Chicony USB2.0 VGA UVC WebCam                               | 4         | 1.36%   |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 1.36%   |
| Chicony HP Truevision HD camera                             | 4         | 1.36%   |
| Chicony HP HD Camera                                        | 4         | 1.36%   |
| Chicony HD User Facing                                      | 4         | 1.36%   |
| Syntek Integrated Camera                                    | 3         | 1.02%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.02%   |
| ShineTech USB2.0 HD UVC WebCam                              | 3         | 1.02%   |
| Realtek Integrated Webcam                                   | 3         | 1.02%   |
| Realtek HP Webcam                                           | 3         | 1.02%   |
| Logitech Webcam C270                                        | 3         | 1.02%   |
| Logitech Webcam C170                                        | 3         | 1.02%   |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 1.02%   |
| Apple FaceTime HD Camera                                    | 3         | 1.02%   |
| Z-Star Full HD 1080P PC Camera                              | 2         | 0.68%   |
| Suyin HD WebCam                                             | 2         | 0.68%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.68%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 2         | 0.68%   |
| Ricoh Integrated Webcam                                     | 2         | 0.68%   |
| Quanta Laptop_Integrated_Webcam_2HDM                        | 2         | 0.68%   |
| Quanta HD Webcam                                            | 2         | 0.68%   |
| Microdia Lenovo EasyCamera                                  | 2         | 0.68%   |
| Luxvisions Innotech Limited Integrated RGB Camera           | 2         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 0.68%   |
| Lenovo Integrated Webcam                                    | 2         | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 21        | 38.18%  |
| Synaptics                  | 17        | 30.91%  |
| AuthenTec                  | 5         | 9.09%   |
| Upek                       | 4         | 7.27%   |
| Shenzhen Goodix Technology | 3         | 5.45%   |
| STMicroelectronics         | 2         | 3.64%   |
| Elan Microelectronics      | 2         | 3.64%   |
| LighTuning Technology      | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 7.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 7.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 7.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 5.45%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 5.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 5.45%   |
| Validity Sensors VFS491                                                    | 2         | 3.64%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.64%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.64%   |
| Synaptics UWP WBDI Device                                                  | 2         | 3.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.64%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.64%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 3.64%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.82%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.82%   |
| Synaptics WBDI                                                             | 1         | 1.82%   |
| Synaptics UWP WBDI                                                         | 1         | 1.82%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.82%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.82%   |
| Synaptics Fingerprint scanner                                              | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.82%   |
| AuthenTec AES1600                                                          | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 24        | 61.54%  |
| Broadcom         | 10        | 25.64%  |
| Lenovo           | 2         | 5.13%   |
| Upek             | 1         | 2.56%   |
| SCM Microsystems | 1         | 2.56%   |
| O2 Micro         | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                         | 24        | 61.54%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 4         | 10.26%  |
| Broadcom BCM5880 Secure Applications Processor                              | 3         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                         | 2         | 5.13%   |
| Broadcom 58200                                                              | 2         | 5.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                  | 1         | 2.56%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                      | 1         | 2.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                        | 1         | 2.56%   |
| Broadcom 5880                                                               | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 324       | 67.36%  |
| 1     | 120       | 24.95%  |
| 2     | 32        | 6.65%   |
| 3     | 4         | 0.83%   |
| 4     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 54        | 28.27%  |
| Graphics card            | 49        | 25.65%  |
| Chipcard                 | 31        | 16.23%  |
| Net/wireless             | 17        | 8.9%    |
| Multimedia controller    | 12        | 6.28%   |
| Communication controller | 7         | 3.66%   |
| Camera                   | 6         | 3.14%   |
| Unassigned class         | 2         | 1.05%   |
| Storage                  | 2         | 1.05%   |
| Network                  | 2         | 1.05%   |
| Net/ethernet             | 2         | 1.05%   |
| Card reader              | 2         | 1.05%   |
| Bluetooth                | 2         | 1.05%   |
| Storage/raid             | 1         | 0.52%   |
| Sound                    | 1         | 0.52%   |
| Dvb card                 | 1         | 0.52%   |

