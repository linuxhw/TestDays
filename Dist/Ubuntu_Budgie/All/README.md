Ubuntu Budgie - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie/Notebook/README.md).

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

Total: 1056

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | N150CU                      | Notebook    | [348d0cab2d](https://linux-hardware.org/?probe=348d0cab2d) | May 07, 2024 |
| HP            | 83E1                        | Desktop     | [71a7fa85fb](https://linux-hardware.org/?probe=71a7fa85fb) | May 05, 2024 |
| Sony          | SVS13A25PBS                 | Notebook    | [32dc3304ac](https://linux-hardware.org/?probe=32dc3304ac) | May 02, 2024 |
| HP            | Spectre Pro x360 G1         | Notebook    | [39577e6ab0](https://linux-hardware.org/?probe=39577e6ab0) | May 01, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [190985f2da](https://linux-hardware.org/?probe=190985f2da) | Apr 22, 2024 |
| ASRock        | B650E Taichi Lite           | Desktop     | [b69958b86b](https://linux-hardware.org/?probe=b69958b86b) | Apr 14, 2024 |
| HP            | Pavilion dv8                | Notebook    | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Chuwi         | X312B                       | Notebook    | [3623330a1c](https://linux-hardware.org/?probe=3623330a1c) | Apr 09, 2024 |
| Chuwi         | X312B                       | Notebook    | [5aa107f741](https://linux-hardware.org/?probe=5aa107f741) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [7bb2773966](https://linux-hardware.org/?probe=7bb2773966) | Apr 05, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a3e56de041](https://linux-hardware.org/?probe=a3e56de041) | Apr 01, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [297eab2023](https://linux-hardware.org/?probe=297eab2023) | Mar 31, 2024 |
| Google        | Bobba                       | Notebook    | [d69b117fd0](https://linux-hardware.org/?probe=d69b117fd0) | Mar 30, 2024 |
| Lenovo        | 1059 SDK0T76530 WIN 3556... | Desktop     | [39db39fb8a](https://linux-hardware.org/?probe=39db39fb8a) | Mar 30, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [4b22ed6279](https://linux-hardware.org/?probe=4b22ed6279) | Mar 29, 2024 |
| Sony          | SVS13A25PBS                 | Notebook    | [6ee5930fa8](https://linux-hardware.org/?probe=6ee5930fa8) | Mar 27, 2024 |
| Packard Be... | EasyNote TM98               | Notebook    | [e6c48ef91f](https://linux-hardware.org/?probe=e6c48ef91f) | Mar 22, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [d337b27afc](https://linux-hardware.org/?probe=d337b27afc) | Mar 21, 2024 |
| HP            | 8058                        | All in one  | [2a0c07d92f](https://linux-hardware.org/?probe=2a0c07d92f) | Mar 18, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [3bfd1620fe](https://linux-hardware.org/?probe=3bfd1620fe) | Mar 12, 2024 |
| Winnovo       | TaBook                      | Convertible | [e98a415190](https://linux-hardware.org/?probe=e98a415190) | Mar 08, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4e1c5cafe7](https://linux-hardware.org/?probe=4e1c5cafe7) | Mar 03, 2024 |
| Dell          | Latitude 5480               | Notebook    | [5c3376ae97](https://linux-hardware.org/?probe=5c3376ae97) | Feb 29, 2024 |
| PCWare        | APM-A320G                   | Desktop     | [15ddb5b3fd](https://linux-hardware.org/?probe=15ddb5b3fd) | Feb 29, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [a3b8064ddf](https://linux-hardware.org/?probe=a3b8064ddf) | Feb 29, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [4963c40308](https://linux-hardware.org/?probe=4963c40308) | Feb 27, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [fd9e5de8cf](https://linux-hardware.org/?probe=fd9e5de8cf) | Feb 22, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [29aa21542a](https://linux-hardware.org/?probe=29aa21542a) | Feb 22, 2024 |
| Dell          | Vostro 5625                 | Notebook    | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | Notebook    | [4264042062](https://linux-hardware.org/?probe=4264042062) | Feb 18, 2024 |
| HP            | 8169                        | Desktop     | [8aadb502eb](https://linux-hardware.org/?probe=8aadb502eb) | Feb 13, 2024 |
| ASUSTek       | G750JW                      | Notebook    | [1ba5260b50](https://linux-hardware.org/?probe=1ba5260b50) | Feb 13, 2024 |
| HP            | 15                          | Notebook    | [ef0b519e9b](https://linux-hardware.org/?probe=ef0b519e9b) | Feb 12, 2024 |
| MSI           | B450M GAMING PLUS           | Desktop     | [093c937aa6](https://linux-hardware.org/?probe=093c937aa6) | Feb 07, 2024 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c80a1f64fc](https://linux-hardware.org/?probe=c80a1f64fc) | Jan 18, 2024 |
| Toshiba       | Satellite C855D-11X         | Notebook    | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | Notebook    | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [66efe29bec](https://linux-hardware.org/?probe=66efe29bec) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d041e87729](https://linux-hardware.org/?probe=d041e87729) | Jan 09, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [462cb61dd3](https://linux-hardware.org/?probe=462cb61dd3) | Jan 05, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [03e7ada99a](https://linux-hardware.org/?probe=03e7ada99a) | Jan 04, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [0961855530](https://linux-hardware.org/?probe=0961855530) | Dec 31, 2023 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [7efa5db123](https://linux-hardware.org/?probe=7efa5db123) | Dec 29, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| Sony          | VPCW216AG                   | Notebook    | [fb60613609](https://linux-hardware.org/?probe=fb60613609) | Dec 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [00756344be](https://linux-hardware.org/?probe=00756344be) | Nov 25, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [a293b54992](https://linux-hardware.org/?probe=a293b54992) | Nov 24, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [5f26bd4798](https://linux-hardware.org/?probe=5f26bd4798) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [ed1bde2ed6](https://linux-hardware.org/?probe=ed1bde2ed6) | Nov 20, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [9c0b7c2706](https://linux-hardware.org/?probe=9c0b7c2706) | Nov 15, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [c172f735d2](https://linux-hardware.org/?probe=c172f735d2) | Nov 15, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [5efa262121](https://linux-hardware.org/?probe=5efa262121) | Nov 14, 2023 |
| HP            | 8309                        | Desktop     | [88e1f5e70c](https://linux-hardware.org/?probe=88e1f5e70c) | Nov 13, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [64ce1a549b](https://linux-hardware.org/?probe=64ce1a549b) | Nov 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [143fa66e87](https://linux-hardware.org/?probe=143fa66e87) | Nov 08, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [c6d6619fd9](https://linux-hardware.org/?probe=c6d6619fd9) | Nov 06, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Dell          | Latitude E5470              | Notebook    | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Sony          | SVS13A25PBS                 | Notebook    | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [b3a6489f94](https://linux-hardware.org/?probe=b3a6489f94) | Oct 20, 2023 |
| IMUZ          | STORMBOOK14 APOLLO          | Notebook    | [6d8e8178b0](https://linux-hardware.org/?probe=6d8e8178b0) | Oct 19, 2023 |
| Google        | Kled                        | Notebook    | [4d546b71e7](https://linux-hardware.org/?probe=4d546b71e7) | Oct 17, 2023 |
| Gateway       | NV59C                       | Notebook    | [5a0c4e72d6](https://linux-hardware.org/?probe=5a0c4e72d6) | Oct 16, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [f4e2082297](https://linux-hardware.org/?probe=f4e2082297) | Oct 16, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [b09d2e33fd](https://linux-hardware.org/?probe=b09d2e33fd) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| HP            | 8054                        | Desktop     | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [c2205d1cf2](https://linux-hardware.org/?probe=c2205d1cf2) | Oct 10, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [5a440c873d](https://linux-hardware.org/?probe=5a440c873d) | Oct 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [73b5907f17](https://linux-hardware.org/?probe=73b5907f17) | Sep 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| Acer          | Aspire 7530G                | Notebook    | [37d34804dd](https://linux-hardware.org/?probe=37d34804dd) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Gateway       | NV59C                       | Notebook    | [0885dc9384](https://linux-hardware.org/?probe=0885dc9384) | Sep 16, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [312d4a06dc](https://linux-hardware.org/?probe=312d4a06dc) | Sep 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [4fe996e64f](https://linux-hardware.org/?probe=4fe996e64f) | Aug 29, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [921d699e5d](https://linux-hardware.org/?probe=921d699e5d) | Aug 19, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [1e39da3f6e](https://linux-hardware.org/?probe=1e39da3f6e) | Aug 18, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [934ab444f2](https://linux-hardware.org/?probe=934ab444f2) | Aug 07, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [3f8e9bffbd](https://linux-hardware.org/?probe=3f8e9bffbd) | Aug 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [73efa45f4f](https://linux-hardware.org/?probe=73efa45f4f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ce0e015b6e](https://linux-hardware.org/?probe=ce0e015b6e) | Aug 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e31d121593](https://linux-hardware.org/?probe=e31d121593) | Jul 15, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9c3135decf](https://linux-hardware.org/?probe=9c3135decf) | Jul 10, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [12561e59a4](https://linux-hardware.org/?probe=12561e59a4) | Jul 07, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [48526cd359](https://linux-hardware.org/?probe=48526cd359) | Jul 07, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [3e7598da34](https://linux-hardware.org/?probe=3e7598da34) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [c9a8bc63d4](https://linux-hardware.org/?probe=c9a8bc63d4) | Jun 27, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4428a36327](https://linux-hardware.org/?probe=4428a36327) | Jun 27, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [740bd03ee0](https://linux-hardware.org/?probe=740bd03ee0) | Jun 26, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [544b40258b](https://linux-hardware.org/?probe=544b40258b) | Jun 21, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [d003b60677](https://linux-hardware.org/?probe=d003b60677) | Jun 20, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [66607910c0](https://linux-hardware.org/?probe=66607910c0) | Jun 19, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | Desktop     | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| HP            | Notebook                    | Notebook    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [b63a3cbd7b](https://linux-hardware.org/?probe=b63a3cbd7b) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [3db7516231](https://linux-hardware.org/?probe=3db7516231) | May 25, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | Notebook    | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | Notebook    | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | 024JD7 A00                  | Desktop     | [904e4e2a0d](https://linux-hardware.org/?probe=904e4e2a0d) | May 15, 2023 |
| Dell          | Latitude E5420              | Notebook    | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [9ed744299a](https://linux-hardware.org/?probe=9ed744299a) | May 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7a26c45568](https://linux-hardware.org/?probe=7a26c45568) | May 04, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [a0b1299baa](https://linux-hardware.org/?probe=a0b1299baa) | May 02, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Dell          | Latitude E5420              | Notebook    | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Intel         | H61                         | Desktop     | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| ZOTAC         | ZBOX-ECM73070C/7307LH/53... | Mini pc     | [c3d1c96452](https://linux-hardware.org/?probe=c3d1c96452) | Apr 26, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c546b0771a](https://linux-hardware.org/?probe=c546b0771a) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [8f9e883980](https://linux-hardware.org/?probe=8f9e883980) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| ZOTAC         | ZBOX-ECM73070C/7307LH/53... | Mini pc     | [6bdb0611ac](https://linux-hardware.org/?probe=6bdb0611ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e8fc7722ef](https://linux-hardware.org/?probe=e8fc7722ef) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1c517ff300](https://linux-hardware.org/?probe=1c517ff300) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2536217d87](https://linux-hardware.org/?probe=2536217d87) | Mar 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1ade706194](https://linux-hardware.org/?probe=1ade706194) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [45537ae306](https://linux-hardware.org/?probe=45537ae306) | Mar 17, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| HP            | 83E1                        | Desktop     | [86061f121d](https://linux-hardware.org/?probe=86061f121d) | Mar 08, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [b78033fddd](https://linux-hardware.org/?probe=b78033fddd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [3c681075fb](https://linux-hardware.org/?probe=3c681075fb) | Mar 04, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [a5a54422a0](https://linux-hardware.org/?probe=a5a54422a0) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Google        | Boten                       | Notebook    | [5562b4af15](https://linux-hardware.org/?probe=5562b4af15) | Feb 11, 2023 |
| Google        | Boten                       | Notebook    | [d07e5295bb](https://linux-hardware.org/?probe=d07e5295bb) | Feb 11, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [3a9937a61b](https://linux-hardware.org/?probe=3a9937a61b) | Feb 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [866e97ab12](https://linux-hardware.org/?probe=866e97ab12) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [de3f21b51b](https://linux-hardware.org/?probe=de3f21b51b) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [329e7b7105](https://linux-hardware.org/?probe=329e7b7105) | Jan 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0c8a9895bd](https://linux-hardware.org/?probe=0c8a9895bd) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [b3bc8de731](https://linux-hardware.org/?probe=b3bc8de731) | Jan 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Google        | Banjo                       | Notebook    | [30a528ac6b](https://linux-hardware.org/?probe=30a528ac6b) | Jan 14, 2023 |
| Google        | Banjo                       | Notebook    | [66dc97b0de](https://linux-hardware.org/?probe=66dc97b0de) | Jan 14, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a5e1965b89](https://linux-hardware.org/?probe=a5e1965b89) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [f560abfd7f](https://linux-hardware.org/?probe=f560abfd7f) | Jan 03, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | Notebook    | [a14e00ab97](https://linux-hardware.org/?probe=a14e00ab97) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | Notebook    | [00e25b3232](https://linux-hardware.org/?probe=00e25b3232) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| Dell          | System XPS L502X            | Notebook    | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| MSI           | GL65 Leopard 10SDK          | Notebook    | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [1773b79334](https://linux-hardware.org/?probe=1773b79334) | Dec 17, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e95599a479](https://linux-hardware.org/?probe=e95599a479) | Dec 09, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c40fd27f39](https://linux-hardware.org/?probe=c40fd27f39) | Dec 05, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [3272263f3b](https://linux-hardware.org/?probe=3272263f3b) | Dec 04, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [42efe1dfdf](https://linux-hardware.org/?probe=42efe1dfdf) | Dec 02, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| Dell          | 0RW199                      | Desktop     | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| MSI           | GL65 Leopard 10SFKV         | Notebook    | [84668eb3a8](https://linux-hardware.org/?probe=84668eb3a8) | Nov 16, 2022 |
| MSI           | GL65 Leopard 10SFKV         | Notebook    | [316e275c13](https://linux-hardware.org/?probe=316e275c13) | Nov 16, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [fd97cf3ecb](https://linux-hardware.org/?probe=fd97cf3ecb) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | Notebook    | [3cb2ce5a02](https://linux-hardware.org/?probe=3cb2ce5a02) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| MSI           | H67MA-E35                   | Desktop     | [d4f5628033](https://linux-hardware.org/?probe=d4f5628033) | Oct 11, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [293e528545](https://linux-hardware.org/?probe=293e528545) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [cc583599ef](https://linux-hardware.org/?probe=cc583599ef) | Aug 28, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| HP            | 3397                        | Desktop     | [335f59c96f](https://linux-hardware.org/?probe=335f59c96f) | Aug 22, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| ASUSTek       | Berkeley                    | Desktop     | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2a95697c62](https://linux-hardware.org/?probe=2a95697c62) | Jul 25, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Alienware     | M11xR3                      | Notebook    | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [d2ed25b6e8](https://linux-hardware.org/?probe=d2ed25b6e8) | Jul 16, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | Notebook    | [f1dcf09169](https://linux-hardware.org/?probe=f1dcf09169) | Jul 14, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| Google        | Eve                         | Convertible | [be0c82653c](https://linux-hardware.org/?probe=be0c82653c) | Jul 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Dell          | Latitude E7450              | Notebook    | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Positivo      | Q232A                       | Notebook    | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | Notebook    | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3195007eb2](https://linux-hardware.org/?probe=3195007eb2) | May 30, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e97309bc05](https://linux-hardware.org/?probe=e97309bc05) | May 07, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [9505d0e8b7](https://linux-hardware.org/?probe=9505d0e8b7) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [96eae556f2](https://linux-hardware.org/?probe=96eae556f2) | Apr 15, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | Notebook    | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | Notebook    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | Notebook    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| HP            | 8158 A01                    | Mini pc     | [3ba669d072](https://linux-hardware.org/?probe=3ba669d072) | Mar 20, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [ca76b3a899](https://linux-hardware.org/?probe=ca76b3a899) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [f444e85d64](https://linux-hardware.org/?probe=f444e85d64) | Mar 18, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| HP            | Pavilion dm4                | Notebook    | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| Microsoft     | Surface Book                | Tablet      | [a94d46ec1d](https://linux-hardware.org/?probe=a94d46ec1d) | Feb 25, 2022 |
| Microsoft     | Surface Book                | Tablet      | [f62d16f3b1](https://linux-hardware.org/?probe=f62d16f3b1) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Dell          | 0RW199                      | Desktop     | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | Notebook    | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | Notebook    | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [d7414a7101](https://linux-hardware.org/?probe=d7414a7101) | Jan 15, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| Teclast       | X6 plus                     | Tablet      | [d476f875d2](https://linux-hardware.org/?probe=d476f875d2) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| HP            | Pavilion dm1                | Notebook    | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | Notebook    | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| HP            | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [8ecbd29abd](https://linux-hardware.org/?probe=8ecbd29abd) | Oct 29, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [feb38e948d](https://linux-hardware.org/?probe=feb38e948d) | Sep 13, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | Notebook    | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| Google        | Peppy                       | Notebook    | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| TUXEDO        | Book XP1511                 | Notebook    | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | Notebook    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| TUXEDO        | Book_XA1510                 | Notebook    | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | Notebook    | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP            | 1588h                       | Desktop     | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | Notebook    | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| AWOW          | AK41                        | Notebook    | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | Notebook    | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | Notebook    | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| Dell          | Latitude D531               | Notebook    | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | Notebook    | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | Notebook    | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9c8b7bc48a](https://linux-hardware.org/?probe=9c8b7bc48a) | Apr 06, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | Notebook    | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [104c966a1a](https://linux-hardware.org/?probe=104c966a1a) | Mar 30, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f769aaeedd](https://linux-hardware.org/?probe=f769aaeedd) | Mar 26, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP            | 3031h                       | Desktop     | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [d9cc78fcff](https://linux-hardware.org/?probe=d9cc78fcff) | Mar 07, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [bc79c52365](https://linux-hardware.org/?probe=bc79c52365) | Mar 04, 2021 |
| Timi          | TM1701                      | Notebook    | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| Dell          | 0KJCC5 A00                  | Desktop     | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d1866f15b4](https://linux-hardware.org/?probe=d1866f15b4) | Mar 02, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | Notebook    | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| BCM           | RX965Q                      | Desktop     | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [10e0380862](https://linux-hardware.org/?probe=10e0380862) | Feb 19, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek       | H61M-A                      | Desktop     | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Lenovo        | 36F2 SDK0J40700 WIN 3258... | All in one  | [f172b5b1ea](https://linux-hardware.org/?probe=f172b5b1ea) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | Notebook    | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [13979999ed](https://linux-hardware.org/?probe=13979999ed) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | Notebook    | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3d2867cd98](https://linux-hardware.org/?probe=3d2867cd98) | Jan 30, 2021 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Dell          | XPS L322X                   | Notebook    | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP            | 1589                        | Desktop     | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| MSI           | GE70 2PC\2PE                | Notebook    | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| eMachines     | EZ1600                      | All in one  | [2c5f74bdac](https://linux-hardware.org/?probe=2c5f74bdac) | Jan 01, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Toshiba       | Satellite P750              | Notebook    | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0d1e39a79a](https://linux-hardware.org/?probe=0d1e39a79a) | Dec 27, 2020 |
| HP            | Pavilion 17                 | Notebook    | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| eMachines     | EZ1600                      | All in one  | [2181178e2b](https://linux-hardware.org/?probe=2181178e2b) | Dec 25, 2020 |
| Dell          | 0PK096                      | Desktop     | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [6260a9fb0f](https://linux-hardware.org/?probe=6260a9fb0f) | Dec 22, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c671dc11ee](https://linux-hardware.org/?probe=c671dc11ee) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [05c93972e0](https://linux-hardware.org/?probe=05c93972e0) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | Notebook    | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | Notebook    | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| ASRock        | P67 Extreme4                | Desktop     | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda    | Alpha                       | Desktop     | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c620f65d2b](https://linux-hardware.org/?probe=c620f65d2b) | Nov 25, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| LattePanda    | Alpha                       | Desktop     | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [732043cc5f](https://linux-hardware.org/?probe=732043cc5f) | Nov 21, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | Notebook    | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | Notebook    | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Apple         | Mac-F2218FC8                | All in one  | [b72a5d9506](https://linux-hardware.org/?probe=b72a5d9506) | Oct 31, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | Notebook    | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| HP            | ZBook 14                    | Notebook    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| HP            | Stream 7 Tablet             | Tablet      | [1cb5fb4518](https://linux-hardware.org/?probe=1cb5fb4518) | Oct 25, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| Dell          | Latitude 5400               | Notebook    | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock        | Q1900B-ITX                  | Desktop     | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | Notebook    | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | Notebook    | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| Dell          | 0M9KCM A00                  | Desktop     | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| MSI           | Modern 14 A10RB             | Notebook    | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell          | Latitude 5400               | Notebook    | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| Dell          | 0RY007                      | Desktop     | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| HP            | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Radxa         | ROCK Pi 4A                  | Soc         | [b335776d4a](https://linux-hardware.org/?probe=b335776d4a) | Sep 14, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| HP            | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [bc9c588fd8](https://linux-hardware.org/?probe=bc9c588fd8) | Aug 30, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | Notebook    | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Sony          | VPCEK20AL                   | Notebook    | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | Notebook    | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | Notebook    | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| Standard      | MT40II                      | Notebook    | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | Notebook    | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP            | 82F2                        | Desktop     | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0479f5e75d](https://linux-hardware.org/?probe=0479f5e75d) | Jul 26, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | Notebook    | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | Notebook    | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| HP            | 3397                        | Desktop     | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP            | 3397                        | Desktop     | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | Notebook    | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | Notebook    | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | Notebook    | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [12a4926d36](https://linux-hardware.org/?probe=12a4926d36) | Jul 17, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell          | 0P301D A02                  | Desktop     | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| MSI           | GP72 7RE                    | Notebook    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | Notebook    | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | Notebook    | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | Notebook    | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | Notebook    | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | Notebook    | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | Notebook    | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | Notebook    | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | Notebook    | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | Notebook    | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Acer          | Aspire ZC-105               | All in one  | [42b2dbab31](https://linux-hardware.org/?probe=42b2dbab31) | Jun 01, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | Notebook    | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | Notebook    | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | Notebook    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | Notebook    | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | Notebook    | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Dell          | 0TNXNR A01                  | Desktop     | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | Notebook    | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | Notebook    | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [181868c1fe](https://linux-hardware.org/?probe=181868c1fe) | May 05, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | Notebook                    | Notebook    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [7db8dc0e44](https://linux-hardware.org/?probe=7db8dc0e44) | Apr 28, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | Notebook    | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| HP            | 0A80h                       | Desktop     | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | Notebook    | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c17da47049](https://linux-hardware.org/?probe=c17da47049) | Apr 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [18f447ca5d](https://linux-hardware.org/?probe=18f447ca5d) | Apr 03, 2020 |
| HP            | 8433 11                     | Desktop     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| HP            | 84EE 1100                   | All in one  | [870857c93c](https://linux-hardware.org/?probe=870857c93c) | Mar 30, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Budgie/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 259       | 34.72%  |
| Ubuntu Budgie 22.04 | 170       | 22.79%  |
| Ubuntu Budgie 20.10 | 61        | 8.18%   |
| Ubuntu Budgie 21.10 | 57        | 7.64%   |
| Ubuntu Budgie 18.04 | 41        | 5.5%    |
| Ubuntu Budgie 22.10 | 40        | 5.36%   |
| Ubuntu Budgie 21.04 | 37        | 4.96%   |
| Ubuntu Budgie 19.10 | 29        | 3.89%   |
| Ubuntu Budgie 23.04 | 25        | 3.35%   |
| Ubuntu Budgie 23.10 | 19        | 2.55%   |
| Ubuntu Budgie 24.04 | 3         | 0.4%    |
| Ubuntu Budgie       | 3         | 0.4%    |
| Ubuntu Budgie 16.04 | 2         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 710       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 27        | 3.29%   |
| 5.3.0-40-generic  | 15        | 1.83%   |
| 5.4.0-40-generic  | 13        | 1.58%   |
| 5.13.0-22-generic | 13        | 1.58%   |
| 5.15.0-27-generic | 11        | 1.34%   |
| 6.2.0-20-generic  | 10        | 1.22%   |
| 5.4.0-52-generic  | 10        | 1.22%   |
| 5.4.0-37-generic  | 10        | 1.22%   |
| 5.13.0-39-generic | 10        | 1.22%   |
| 5.13.0-19-generic | 10        | 1.22%   |
| 5.4.0-58-generic  | 9         | 1.1%    |
| 5.4.0-48-generic  | 9         | 1.1%    |
| 5.4.0-29-generic  | 9         | 1.1%    |
| 5.15.0-52-generic | 9         | 1.1%    |
| 5.8.0-48-generic  | 8         | 0.97%   |
| 5.8.0-44-generic  | 8         | 0.97%   |
| 5.8.0-41-generic  | 8         | 0.97%   |
| 5.13.0-40-generic | 8         | 0.97%   |
| 5.13.0-30-generic | 8         | 0.97%   |
| 5.13.0-28-generic | 8         | 0.97%   |
| 5.11.0-41-generic | 8         | 0.97%   |
| 6.2.0-26-generic  | 7         | 0.85%   |
| 5.8.0-43-generic  | 7         | 0.85%   |
| 5.4.0-47-generic  | 7         | 0.85%   |
| 5.4.0-33-generic  | 7         | 0.85%   |
| 5.4.0-31-generic  | 7         | 0.85%   |
| 5.19.0-46-generic | 7         | 0.85%   |
| 5.19.0-38-generic | 7         | 0.85%   |
| 5.19.0-35-generic | 7         | 0.85%   |
| 5.19.0-26-generic | 7         | 0.85%   |
| 5.15.0-50-generic | 7         | 0.85%   |
| 5.15.0-46-generic | 7         | 0.85%   |
| 5.13.0-35-generic | 7         | 0.85%   |
| 5.8.0-53-generic  | 6         | 0.73%   |
| 5.8.0-45-generic  | 6         | 0.73%   |
| 5.8.0-29-generic  | 6         | 0.73%   |
| 5.15.0-56-generic | 6         | 0.73%   |
| 5.15.0-48-generic | 6         | 0.73%   |
| 5.15.0-30-generic | 6         | 0.73%   |
| 6.5.0-9-generic   | 5         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 176       | 23.16%  |
| 5.15.0  | 118       | 15.53%  |
| 5.8.0   | 89        | 11.71%  |
| 5.13.0  | 81        | 10.66%  |
| 5.19.0  | 62        | 8.16%   |
| 5.11.0  | 55        | 7.24%   |
| 6.2.0   | 45        | 5.92%   |
| 5.3.0   | 42        | 5.53%   |
| 6.5.0   | 37        | 4.87%   |
| 4.15.0  | 14        | 1.84%   |
| 6.8.0   | 3         | 0.39%   |
| 5.6.0   | 3         | 0.39%   |
| 5.0.0   | 3         | 0.39%   |
| 5.6.7   | 2         | 0.26%   |
| 5.12.0  | 2         | 0.26%   |
| 5.10.0  | 2         | 0.26%   |
| 4.18.0  | 2         | 0.26%   |
| 6.6.0   | 1         | 0.13%   |
| 6.5.7   | 1         | 0.13%   |
| 6.5.5   | 1         | 0.13%   |
| 6.3.1   | 1         | 0.13%   |
| 6.1.0   | 1         | 0.13%   |
| 5.9.1   | 1         | 0.13%   |
| 5.9.0   | 1         | 0.13%   |
| 5.8.6   | 1         | 0.13%   |
| 5.8.11  | 1         | 0.13%   |
| 5.7.7   | 1         | 0.13%   |
| 5.5.8   | 1         | 0.13%   |
| 5.5.0   | 1         | 0.13%   |
| 5.18.8  | 1         | 0.13%   |
| 5.17.2  | 1         | 0.13%   |
| 5.17.1  | 1         | 0.13%   |
| 5.16.2  | 1         | 0.13%   |
| 5.16.14 | 1         | 0.13%   |
| 5.15.92 | 1         | 0.13%   |
| 5.15.11 | 1         | 0.13%   |
| 5.14.2  | 1         | 0.13%   |
| 5.14.1  | 1         | 0.13%   |
| 5.10.11 | 1         | 0.13%   |
| 4.4.178 | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 176       | 23.19%  |
| 5.15    | 120       | 15.81%  |
| 5.8     | 91        | 11.99%  |
| 5.13    | 81        | 10.67%  |
| 5.19    | 62        | 8.17%   |
| 5.11    | 55        | 7.25%   |
| 6.2     | 45        | 5.93%   |
| 5.3     | 42        | 5.53%   |
| 6.5     | 39        | 5.14%   |
| 4.15    | 14        | 1.84%   |
| 5.6     | 5         | 0.66%   |
| 6.8     | 3         | 0.4%    |
| 5.10    | 3         | 0.4%    |
| 5.0     | 3         | 0.4%    |
| 5.9     | 2         | 0.26%   |
| 5.5     | 2         | 0.26%   |
| 5.17    | 2         | 0.26%   |
| 5.16    | 2         | 0.26%   |
| 5.12    | 2         | 0.26%   |
| 4.4     | 2         | 0.26%   |
| 4.18    | 2         | 0.26%   |
| 6.6     | 1         | 0.13%   |
| 6.3     | 1         | 0.13%   |
| 6.1     | 1         | 0.13%   |
| 5.7     | 1         | 0.13%   |
| 5.18    | 1         | 0.13%   |
| 5.14    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 697       | 98.17%  |
| i686    | 9         | 1.27%   |
| aarch64 | 3         | 0.42%   |
| armv7l  | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Budgie     | 687       | 96.76%  |
| GNOME      | 17        | 2.39%   |
| KDE5       | 2         | 0.28%   |
| XFCE       | 1         | 0.14%   |
| X-Cinnamon | 1         | 0.14%   |
| MATE       | 1         | 0.14%   |
| KDE        | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 693       | 97.33%  |
| Wayland | 16        | 2.25%   |
| Tty     | 3         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 300       | 41.55%  |
| Unknown | 263       | 36.43%  |
| TDM     | 92        | 12.74%  |
| GDM     | 35        | 4.85%   |
| GDM3    | 27        | 3.74%   |
| SDDM    | 5         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 270       | 37.92%  |
| de_DE   | 85        | 11.94%  |
| fr_FR   | 49        | 6.88%   |
| pt_BR   | 43        | 6.04%   |
| en_GB   | 38        | 5.34%   |
| en_CA   | 25        | 3.51%   |
| it_IT   | 22        | 3.09%   |
| ru_RU   | 17        | 2.39%   |
| en_IN   | 15        | 2.11%   |
| es_ES   | 14        | 1.97%   |
| en_AU   | 14        | 1.97%   |
| es_AR   | 11        | 1.54%   |
| es_MX   | 9         | 1.26%   |
| C       | 7         | 0.98%   |
| pl_PL   | 6         | 0.84%   |
| Unknown | 6         | 0.84%   |
| pt_PT   | 5         | 0.7%    |
| hu_HU   | 5         | 0.7%    |
| es_CL   | 5         | 0.7%    |
| zh_TW   | 3         | 0.42%   |
| uk_UA   | 3         | 0.42%   |
| nl_NL   | 3         | 0.42%   |
| fr_BE   | 3         | 0.42%   |
| es_CO   | 3         | 0.42%   |
| en_ZA   | 3         | 0.42%   |
| en_SG   | 3         | 0.42%   |
| en_IE   | 3         | 0.42%   |
| de_AT   | 3         | 0.42%   |
| cs_CZ   | 3         | 0.42%   |
| ja_JP   | 2         | 0.28%   |
| fr_CH   | 2         | 0.28%   |
| fi_FI   | 2         | 0.28%   |
| eu_ES   | 2         | 0.28%   |
| en_IL   | 2         | 0.28%   |
| de_CH   | 2         | 0.28%   |
| bg_BG   | 2         | 0.28%   |
| zh_CN   | 1         | 0.14%   |
| tr_TR   | 1         | 0.14%   |
| sv_SE   | 1         | 0.14%   |
| ru_UA   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 375       | 51.44%  |
| BIOS | 354       | 48.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 623       | 87.01%  |
| Tmpfs   | 38        | 5.31%   |
| Zfs     | 22        | 3.07%   |
| Overlay | 19        | 2.65%   |
| Btrfs   | 10        | 1.4%    |
| Xfs     | 3         | 0.42%   |
| Jfs     | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 341       | 47.03%  |
| Unknown | 330       | 45.52%  |
| MBR     | 54        | 7.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 620       | 86.11%  |
| Yes       | 100       | 13.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 480       | 66.57%  |
| Yes       | 241       | 33.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 106       | 14.93%  |
| ASUSTek Computer                     | 104       | 14.65%  |
| Lenovo                               | 96        | 13.52%  |
| Dell                                 | 82        | 11.55%  |
| TUXEDO                               | 46        | 6.48%   |
| Gigabyte Technology                  | 39        | 5.49%   |
| MSI                                  | 38        | 5.35%   |
| Apple                                | 36        | 5.07%   |
| Acer                                 | 27        | 3.8%    |
| ASRock                               | 16        | 2.25%   |
| Intel                                | 10        | 1.41%   |
| Google                               | 8         | 1.13%   |
| Fujitsu                              | 8         | 1.13%   |
| Toshiba                              | 7         | 0.99%   |
| Sony                                 | 7         | 0.99%   |
| HUAWEI                               | 7         | 0.99%   |
| Unknown                              | 7         | 0.99%   |
| Samsung Electronics                  | 6         | 0.85%   |
| Packard Bell                         | 4         | 0.56%   |
| Raspberry Pi Foundation              | 3         | 0.42%   |
| Microsoft                            | 3         | 0.42%   |
| Timi                                 | 2         | 0.28%   |
| Standard                             | 2         | 0.28%   |
| Razer                                | 2         | 0.28%   |
| Positivo                             | 2         | 0.28%   |
| eMachines                            | 2         | 0.28%   |
| Chuwi                                | 2         | 0.28%   |
| Biostar                              | 2         | 0.28%   |
| BANGHO                               | 2         | 0.28%   |
| AZW                                  | 2         | 0.28%   |
| Alienware                            | 2         | 0.28%   |
| ZOTAC                                | 1         | 0.14%   |
| Winnovo                              | 1         | 0.14%   |
| Viglen                               | 1         | 0.14%   |
| THUNDEROBOT                          | 1         | 0.14%   |
| Thomson                              | 1         | 0.14%   |
| Teclast                              | 1         | 0.14%   |
| Supermicro                           | 1         | 0.14%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.14%   |
| Semp Toshiba                         | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 17        | 2.39%   |
| ASUS All Series                    | 8         | 1.13%   |
| TUXEDO Pulse 15 Gen1               | 4         | 0.56%   |
| TUXEDO InfinityBook S 15 Gen6      | 3         | 0.42%   |
| TUXEDO Aura 15 Gen1                | 3         | 0.42%   |
| HP Pavilion g6                     | 3         | 0.42%   |
| HP Notebook                        | 3         | 0.42%   |
| Dell OptiPlex 780                  | 3         | 0.42%   |
| Dell Latitude E6420                | 3         | 0.42%   |
| TUXEDO Polaris 15 AMD Gen1         | 2         | 0.28%   |
| TUXEDO InfinityBook S 14 Gen6      | 2         | 0.28%   |
| TUXEDO InfinityBook Pro 14 Gen6    | 2         | 0.28%   |
| TUXEDO Book XP1511                 | 2         | 0.28%   |
| Standard MT40II                    | 2         | 0.28%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 2         | 0.28%   |
| Packard Bell EasyNote TM98         | 2         | 0.28%   |
| MSI MS-7C84                        | 2         | 0.28%   |
| Microsoft Surface Pro 3            | 2         | 0.28%   |
| Lenovo ThinkPad E15 20RD003KHV     | 2         | 0.28%   |
| Lenovo ThinkBook 14-IML 20RV       | 2         | 0.28%   |
| Lenovo IdeaPad C340-14API 81N6     | 2         | 0.28%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 2         | 0.28%   |
| Lenovo IdeaPad 330S-15ARR 81FB     | 2         | 0.28%   |
| Lenovo IdeaPad 320-15IKB 80XL      | 2         | 0.28%   |
| Lenovo IdeaPad 110-15ISK 80UD      | 2         | 0.28%   |
| Lenovo G500 20236                  | 2         | 0.28%   |
| Lenovo G50-45 80E3                 | 2         | 0.28%   |
| Intel DP55WB AAE64798-206          | 2         | 0.28%   |
| HP ZBook Studio G3                 | 2         | 0.28%   |
| HP ZBook 15 G4                     | 2         | 0.28%   |
| HP Pavilion dv7                    | 2         | 0.28%   |
| HP ENVY 17                         | 2         | 0.28%   |
| HP ENVY 15                         | 2         | 0.28%   |
| HP EliteDesk 800 G1 SFF            | 2         | 0.28%   |
| HP EliteBook 840 G8 Notebook PC    | 2         | 0.28%   |
| HP EliteBook 840 G3                | 2         | 0.28%   |
| HP Compaq Elite 8300 SFF           | 2         | 0.28%   |
| HP 2000                            | 2         | 0.28%   |
| Gigabyte Z68M-D2H                  | 2         | 0.28%   |
| Gigabyte B550I AORUS PRO AX        | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 40        | 5.63%   |
| Dell Latitude         | 28        | 3.94%   |
| Lenovo IdeaPad        | 24        | 3.38%   |
| HP Pavilion           | 19        | 2.68%   |
| Dell Inspiron         | 19        | 2.68%   |
| Acer Aspire           | 17        | 2.39%   |
| Unknown               | 17        | 2.39%   |
| HP EliteBook          | 15        | 2.11%   |
| TUXEDO InfinityBook   | 11        | 1.55%   |
| Dell XPS              | 11        | 1.55%   |
| ASUS VivoBook         | 11        | 1.55%   |
| ASUS ROG              | 11        | 1.55%   |
| ASUS PRIME            | 11        | 1.55%   |
| Dell OptiPlex         | 10        | 1.41%   |
| HP ENVY               | 8         | 1.13%   |
| ASUS All              | 8         | 1.13%   |
| Toshiba Satellite     | 7         | 0.99%   |
| HP ZBook              | 7         | 0.99%   |
| HP ProBook            | 7         | 0.99%   |
| HP Compaq             | 7         | 0.99%   |
| TUXEDO Polaris        | 6         | 0.85%   |
| TUXEDO Book           | 6         | 0.85%   |
| HP Spectre            | 6         | 0.85%   |
| HP Laptop             | 6         | 0.85%   |
| HP EliteDesk          | 6         | 0.85%   |
| Dell Precision        | 6         | 0.85%   |
| TUXEDO Pulse          | 5         | 0.7%    |
| Dell Vostro           | 5         | 0.7%    |
| Acer Swift            | 5         | 0.7%    |
| Lenovo ThinkBook      | 4         | 0.56%   |
| ASUS ZenBook          | 4         | 0.56%   |
| ASUS TUF              | 4         | 0.56%   |
| ASUS ASUS             | 4         | 0.56%   |
| Apple MacBookPro8     | 4         | 0.56%   |
| TUXEDO Aura           | 3         | 0.42%   |
| RPi Raspberry         | 3         | 0.42%   |
| Packard Bell EasyNote | 3         | 0.42%   |
| Microsoft Surface     | 3         | 0.42%   |
| Lenovo Yoga           | 3         | 0.42%   |
| HP Notebook           | 3         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 80        | 11.27%  |
| 2018    | 80        | 11.27%  |
| 2019    | 76        | 10.7%   |
| 2021    | 58        | 8.17%   |
| 2017    | 50        | 7.04%   |
| 2011    | 46        | 6.48%   |
| 2013    | 45        | 6.34%   |
| 2014    | 43        | 6.06%   |
| 2012    | 43        | 6.06%   |
| 2016    | 41        | 5.77%   |
| 2015    | 31        | 4.37%   |
| 2010    | 31        | 4.37%   |
| 2009    | 21        | 2.96%   |
| 2008    | 21        | 2.96%   |
| 2007    | 16        | 2.25%   |
| 2022    | 15        | 2.11%   |
| 2023    | 10        | 1.41%   |
| Unknown | 2         | 0.28%   |
| 2024    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 446       | 62.82%  |
| Desktop        | 201       | 28.31%  |
| Convertible    | 19        | 2.68%   |
| All in one     | 18        | 2.54%   |
| Mini pc        | 12        | 1.69%   |
| Tablet         | 9         | 1.27%   |
| System on chip | 4         | 0.56%   |
| Server         | 1         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 655       | 91.99%  |
| Enabled  | 57        | 8.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 701       | 98.73%  |
| Yes  | 9         | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 177       | 24.62%  |
| 4.01-8.0        | 172       | 23.92%  |
| 8.01-16.0       | 124       | 17.25%  |
| 3.01-4.0        | 108       | 15.02%  |
| 32.01-64.0      | 70        | 9.74%   |
| 64.01-256.0     | 32        | 4.45%   |
| 24.01-32.0      | 14        | 1.95%   |
| 1.01-2.0        | 14        | 1.95%   |
| 2.01-3.0        | 5         | 0.7%    |
| 0.51-1.0        | 2         | 0.28%   |
| More than 256.0 | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 252       | 32.47%  |
| 1.01-2.0   | 205       | 26.42%  |
| 4.01-8.0   | 145       | 18.69%  |
| 3.01-4.0   | 114       | 14.69%  |
| 8.01-16.0  | 40        | 5.15%   |
| 0.51-1.0   | 10        | 1.29%   |
| 16.01-24.0 | 6         | 0.77%   |
| 24.01-32.0 | 2         | 0.26%   |
| 32.01-64.0 | 1         | 0.13%   |
| 0.01-0.5   | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 431       | 59.45%  |
| 2      | 182       | 25.1%   |
| 3      | 58        | 8%      |
| 4      | 24        | 3.31%   |
| 5      | 15        | 2.07%   |
| 8      | 5         | 0.69%   |
| 6      | 5         | 0.69%   |
| 0      | 2         | 0.28%   |
| 11     | 1         | 0.14%   |
| 9      | 1         | 0.14%   |
| 7      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 481       | 67.46%  |
| Yes       | 232       | 32.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 596       | 83.71%  |
| No        | 116       | 16.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 597       | 83.73%  |
| No        | 116       | 16.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 514       | 71.89%  |
| No        | 201       | 28.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 129       | 18.14%  |
| Germany            | 101       | 14.21%  |
| France             | 52        | 7.31%   |
| Brazil             | 50        | 7.03%   |
| Italy              | 26        | 3.66%   |
| UK                 | 25        | 3.52%   |
| Canada             | 24        | 3.38%   |
| Spain              | 19        | 2.67%   |
| Russia             | 18        | 2.53%   |
| India              | 18        | 2.53%   |
| Netherlands        | 16        | 2.25%   |
| Poland             | 14        | 1.97%   |
| Australia          | 14        | 1.97%   |
| Argentina          | 14        | 1.97%   |
| Mexico             | 12        | 1.69%   |
| Switzerland        | 10        | 1.41%   |
| Austria            | 9         | 1.27%   |
| Ukraine            | 8         | 1.13%   |
| Portugal           | 7         | 0.98%   |
| Hungary            | 7         | 0.98%   |
| Sweden             | 6         | 0.84%   |
| South Africa       | 6         | 0.84%   |
| Norway             | 6         | 0.84%   |
| Japan              | 6         | 0.84%   |
| Greece             | 6         | 0.84%   |
| Colombia           | 6         | 0.84%   |
| Belgium            | 6         | 0.84%   |
| Chile              | 5         | 0.7%    |
| Turkey             | 4         | 0.56%   |
| Romania            | 4         | 0.56%   |
| Ireland            | 4         | 0.56%   |
| Iran               | 4         | 0.56%   |
| Indonesia          | 4         | 0.56%   |
| Finland            | 4         | 0.56%   |
| Czechia            | 4         | 0.56%   |
| Croatia            | 4         | 0.56%   |
| Slovenia           | 3         | 0.42%   |
| Singapore          | 3         | 0.42%   |
| Saudi Arabia       | 3         | 0.42%   |
| Dominican Republic | 3         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 9         | 1.22%   |
| Berlin             | 8         | 1.08%   |
| Moscow             | 7         | 0.95%   |
| Budapest           | 6         | 0.81%   |
| Brasília          | 6         | 0.81%   |
| Ravensburg         | 5         | 0.68%   |
| Paris              | 5         | 0.68%   |
| Hamburg            | 5         | 0.68%   |
| Athens             | 5         | 0.68%   |
| Zurich             | 4         | 0.54%   |
| Vienna             | 4         | 0.54%   |
| Tehran             | 4         | 0.54%   |
| Sydney             | 4         | 0.54%   |
| Munich             | 4         | 0.54%   |
| Montreal           | 4         | 0.54%   |
| Los Angeles        | 4         | 0.54%   |
| Frankfurt am Main  | 4         | 0.54%   |
| Dublin             | 4         | 0.54%   |
| Barcelona          | 4         | 0.54%   |
| Zagreb             | 3         | 0.41%   |
| Warsaw             | 3         | 0.41%   |
| St Petersburg      | 3         | 0.41%   |
| Singapore          | 3         | 0.41%   |
| Santo Domingo Este | 3         | 0.41%   |
| San Francisco      | 3         | 0.41%   |
| Rio de Janeiro     | 3         | 0.41%   |
| Pune               | 3         | 0.41%   |
| Prague             | 3         | 0.41%   |
| Nuremberg          | 3         | 0.41%   |
| New York           | 3         | 0.41%   |
| Mumbai             | 3         | 0.41%   |
| Milan              | 3         | 0.41%   |
| Miami              | 3         | 0.41%   |
| Lisbon             | 3         | 0.41%   |
| Kyiv               | 3         | 0.41%   |
| Cologne            | 3         | 0.41%   |
| Cape Town          | 3         | 0.41%   |
| Bogotá            | 3         | 0.41%   |
| Belo Horizonte     | 3         | 0.41%   |
| Austin             | 3         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 201       | 294    | 19%     |
| WDC                         | 137       | 193    | 12.95%  |
| Seagate                     | 132       | 190    | 12.48%  |
| Toshiba                     | 74        | 85     | 6.99%   |
| Unknown                     | 56        | 67     | 5.29%   |
| SanDisk                     | 56        | 69     | 5.29%   |
| Kingston                    | 44        | 56     | 4.16%   |
| Crucial                     | 35        | 45     | 3.31%   |
| Intel                       | 30        | 47     | 2.84%   |
| SK hynix                    | 27        | 29     | 2.55%   |
| Hitachi                     | 25        | 33     | 2.36%   |
| Micron Technology           | 20        | 24     | 1.89%   |
| HGST                        | 17        | 21     | 1.61%   |
| A-DATA Technology           | 16        | 21     | 1.51%   |
| China                       | 15        | 21     | 1.42%   |
| Apple                       | 15        | 18     | 1.42%   |
| Phison                      | 14        | 19     | 1.32%   |
| SPCC                        | 11        | 14     | 1.04%   |
| PNY                         | 10        | 15     | 0.95%   |
| Micron/Crucial Technology   | 6         | 6      | 0.57%   |
| KIOXIA                      | 6         | 7      | 0.57%   |
| JMicron Technology          | 6         | 7      | 0.57%   |
| Transcend                   | 5         | 5      | 0.47%   |
| OCZ                         | 5         | 8      | 0.47%   |
| Silicon Motion              | 4         | 6      | 0.38%   |
| Patriot                     | 4         | 6      | 0.38%   |
| Intenso                     | 4         | 5      | 0.38%   |
| SABRENT                     | 3         | 4      | 0.28%   |
| Netac                       | 3         | 4      | 0.28%   |
| Maxtor                      | 3         | 6      | 0.28%   |
| LITEON                      | 3         | 3      | 0.28%   |
| Gigabyte Technology         | 3         | 3      | 0.28%   |
| Unknown                     | 3         | 3      | 0.28%   |
| Teclast                     | 2         | 3      | 0.19%   |
| Realtek Semiconductor       | 2         | 3      | 0.19%   |
| Phison Electronics          | 2         | 2      | 0.19%   |
| Lenovo                      | 2         | 2      | 0.19%   |
| LaCie                       | 2         | 2      | 0.19%   |
| Kingston Technology Company | 2         | 2      | 0.19%   |
| KingSpec                    | 2         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 11        | 0.93%   |
| Samsung SSD 860 EVO 500GB                         | 11        | 0.93%   |
| Kingston SA400S37240G 240GB SSD                   | 10        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 9         | 0.76%   |
| Samsung NVMe SSD Drive 512GB                      | 9         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 9         | 0.76%   |
| Unknown SD/MMC/MS PRO 128GB                       | 8         | 0.68%   |
| Unknown MMC Card  32GB                            | 8         | 0.68%   |
| Toshiba MQ04ABF100 1TB                            | 8         | 0.68%   |
| Toshiba MQ01ABD100 1TB                            | 8         | 0.68%   |
| Seagate ST9500325AS 500GB                         | 8         | 0.68%   |
| Samsung NVMe SSD Drive 500GB                      | 8         | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB                    | 7         | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                    | 7         | 0.59%   |
| Samsung SSD 860 QVO 1TB                           | 7         | 0.59%   |
| Samsung SSD 850 EVO 500GB                         | 7         | 0.59%   |
| Samsung NVMe SSD Drive 1TB                        | 7         | 0.59%   |
| Kingston SA400S37480G 480GB SSD                   | 7         | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                   | 6         | 0.51%   |
| Samsung SSD 860 EVO M.2 500GB                     | 6         | 0.51%   |
| Samsung SSD 840 EVO 250GB                         | 6         | 0.51%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 6         | 0.51%   |
| Crucial CT480BX500SSD1 480GB                      | 6         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 5         | 0.42%   |
| SK hynix NVMe SSD Drive 256GB                     | 5         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 0.42%   |
| SanDisk SDSSDA240G 240GB                          | 5         | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                    | 5         | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                      | 5         | 0.42%   |
| Samsung SSD 860 EVO M.2 250GB                     | 5         | 0.42%   |
| Crucial CT240BX500SSD1 240GB                      | 5         | 0.42%   |
| China SSD 256GB                                   | 5         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 4         | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 4         | 0.34%   |
| WDC WD5000AAKS-00UU3A0 500GB                      | 4         | 0.34%   |
| Unknown MMC Card  16GB                            | 4         | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                    | 4         | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB                    | 4         | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB                    | 4         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 129       | 186    | 35.05%  |
| WDC                 | 99        | 148    | 26.9%   |
| Toshiba             | 59        | 63     | 16.03%  |
| Hitachi             | 25        | 33     | 6.79%   |
| HGST                | 17        | 21     | 4.62%   |
| Samsung Electronics | 9         | 11     | 2.45%   |
| Unknown             | 8         | 8      | 2.17%   |
| Apple               | 6         | 6      | 1.63%   |
| JMicron Technology  | 4         | 4      | 1.09%   |
| SABRENT             | 3         | 4      | 0.82%   |
| Maxtor              | 3         | 6      | 0.82%   |
| WD MediaMax         | 1         | 1      | 0.27%   |
| USB3.0              | 1         | 1      | 0.27%   |
| TO Exter            | 1         | 1      | 0.27%   |
| TDAS                | 1         | 3      | 0.27%   |
| Fujitsu             | 1         | 1      | 0.27%   |
| ASMT109x            | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 99        | 145    | 27.35%  |
| Kingston            | 38        | 46     | 10.5%   |
| SanDisk             | 36        | 44     | 9.94%   |
| Crucial             | 30        | 40     | 8.29%   |
| WDC                 | 24        | 26     | 6.63%   |
| China               | 15        | 21     | 4.14%   |
| A-DATA Technology   | 11        | 15     | 3.04%   |
| SPCC                | 10        | 13     | 2.76%   |
| Intel               | 10        | 10     | 2.76%   |
| PNY                 | 9         | 14     | 2.49%   |
| Micron Technology   | 9         | 10     | 2.49%   |
| Apple               | 8         | 8      | 2.21%   |
| SK hynix            | 5         | 5      | 1.38%   |
| Patriot             | 4         | 6      | 1.1%    |
| OCZ                 | 4         | 4      | 1.1%    |
| Transcend           | 3         | 3      | 0.83%   |
| Toshiba             | 3         | 3      | 0.83%   |
| LITEON              | 3         | 3      | 0.83%   |
| Intenso             | 3         | 4      | 0.83%   |
| Gigabyte Technology | 3         | 3      | 0.83%   |
| Teclast             | 2         | 3      | 0.55%   |
| Seagate             | 2         | 2      | 0.55%   |
| Netac               | 2         | 2      | 0.55%   |
| KingSpec            | 2         | 2      | 0.55%   |
| Dogfish             | 2         | 2      | 0.55%   |
| Apacer              | 2         | 2      | 0.55%   |
| AMD                 | 2         | 17     | 0.55%   |
| Zheino              | 1         | 2      | 0.28%   |
| VISIPRO             | 1         | 1      | 0.28%   |
| Vaseky              | 1         | 1      | 0.28%   |
| USB30               | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |
| Union Memory        | 1         | 1      | 0.28%   |
| Plextor             | 1         | 1      | 0.28%   |
| OWC                 | 1         | 1      | 0.28%   |
| Mushkin             | 1         | 1      | 0.28%   |
| MicroFrom           | 1         | 1      | 0.28%   |
| LITEONIT            | 1         | 1      | 0.28%   |
| Lexar               | 1         | 1      | 0.28%   |
| KingDian            | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 314       | 476    | 33.09%  |
| HDD     | 301       | 498    | 31.72%  |
| NVMe    | 264       | 363    | 27.82%  |
| MMC     | 49        | 60     | 5.16%   |
| Unknown | 21        | 24     | 2.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 493       | 949    | 58.27%  |
| NVMe | 264       | 363    | 31.21%  |
| MMC  | 49        | 60     | 5.79%   |
| SAS  | 40        | 49     | 4.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 378       | 594    | 58.24%  |
| 0.51-1.0   | 180       | 246    | 27.73%  |
| 1.01-2.0   | 50        | 78     | 7.7%    |
| 3.01-4.0   | 26        | 36     | 4.01%   |
| 4.01-10.0  | 8         | 11     | 1.23%   |
| 2.01-3.0   | 7         | 9      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 220       | 30.14%  |
| 251-500        | 192       | 26.3%   |
| 501-1000       | 106       | 14.52%  |
| 51-100         | 49        | 6.71%   |
| 1001-2000      | 48        | 6.58%   |
| 1-20           | 32        | 4.38%   |
| More than 3000 | 30        | 4.11%   |
| 21-50          | 30        | 4.11%   |
| 2001-3000      | 16        | 2.19%   |
| Unknown        | 7         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 247       | 32.72%  |
| 21-50          | 149       | 19.74%  |
| 101-250        | 129       | 17.09%  |
| 51-100         | 91        | 12.05%  |
| 251-500        | 62        | 8.21%   |
| 501-1000       | 32        | 4.24%   |
| 1001-2000      | 24        | 3.18%   |
| More than 3000 | 11        | 1.46%   |
| Unknown        | 7         | 0.93%   |
| 2001-3000      | 3         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 4         | 4      | 7.41%   |
| Seagate ST9500325AS 500GB            | 3         | 3      | 5.56%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 2      | 3.7%    |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2      | 3.7%    |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 1.85%   |
| WDC WD6000HLHX-01JJPV0 600GB         | 1         | 1      | 1.85%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 2      | 1.85%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 1.85%   |
| WDC WD5000AVCS-632DY1 500GB          | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-329BA0 500GB          | 1         | 1      | 1.85%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 1      | 1.85%   |
| WDC WD2500BEKT-75PVMT1 250GB         | 1         | 1      | 1.85%   |
| WDC WD2500AAJS-60M0A0 250GB          | 1         | 1      | 1.85%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 2      | 1.85%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 1.85%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 1      | 1.85%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 1.85%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 1.85%   |
| Toshiba MK3265GSXN 320GB             | 1         | 1      | 1.85%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 1.85%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 1.85%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 1.85%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 1.85%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.85%   |
| Seagate ST5000DM000-1FK178 5TB       | 1         | 1      | 1.85%   |
| Seagate ST3500320AS 500GB            | 1         | 1      | 1.85%   |
| Seagate ST3320620AS 320GB            | 1         | 1      | 1.85%   |
| Seagate ST3160815AS 160GB            | 1         | 1      | 1.85%   |
| Seagate ST1000DX001-1NS162 1TB       | 1         | 1      | 1.85%   |
| Seagate ST1000DM003-1SB102 1TB       | 1         | 1      | 1.85%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 1.85%   |
| Patriot Pyro m3 240GB SSD            | 1         | 1      | 1.85%   |
| Maxtor STM3250310AS 250GB            | 1         | 1      | 1.85%   |
| Maxtor 6B200M0 208GB                 | 1         | 2      | 1.85%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 1.85%   |
| HP Phison PSSBN032GA27MC1 32GB       | 1         | 1      | 1.85%   |
| Hitachi HTS545025B9SA02 250GB        | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 19        | 19     | 35.19%  |
| WDC       | 14        | 16     | 25.93%  |
| Toshiba   | 8         | 8      | 14.81%  |
| HGST      | 3         | 4      | 5.56%   |
| Maxtor    | 2         | 3      | 3.7%    |
| Hitachi   | 2         | 2      | 3.7%    |
| PNY       | 1         | 1      | 1.85%   |
| Patriot   | 1         | 1      | 1.85%   |
| Kingston  | 1         | 1      | 1.85%   |
| HP Phison | 1         | 1      | 1.85%   |
| Crucial   | 1         | 1      | 1.85%   |
| China     | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 19        | 19     | 39.58%  |
| WDC     | 14        | 16     | 29.17%  |
| Toshiba | 8         | 8      | 16.67%  |
| HGST    | 3         | 4      | 6.25%   |
| Maxtor  | 2         | 3      | 4.17%   |
| Hitachi | 2         | 2      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 52     | 87.76%  |
| SSD  | 5         | 5      | 10.2%   |
| NVMe | 1         | 1      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 441       | 909    | 57.42%  |
| Works    | 278       | 453    | 36.2%   |
| Malfunc  | 48        | 58     | 6.25%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 481       | 54.11%  |
| Samsung Electronics            | 113       | 12.71%  |
| AMD                            | 107       | 12.04%  |
| SanDisk                        | 35        | 3.94%   |
| SK hynix                       | 20        | 2.25%   |
| Phison Electronics             | 17        | 1.91%   |
| Micron Technology              | 12        | 1.35%   |
| Marvell Technology Group       | 12        | 1.35%   |
| Toshiba America Info Systems   | 11        | 1.24%   |
| Micron/Crucial Technology      | 11        | 1.24%   |
| Kingston Technology Company    | 9         | 1.01%   |
| Silicon Motion                 | 7         | 0.79%   |
| Nvidia                         | 7         | 0.79%   |
| KIOXIA                         | 7         | 0.79%   |
| ASMedia Technology             | 7         | 0.79%   |
| JMicron Technology             | 6         | 0.67%   |
| ADATA Technology               | 6         | 0.67%   |
| Realtek Semiconductor          | 3         | 0.34%   |
| Solid State Storage Technology | 2         | 0.22%   |
| Lenovo                         | 2         | 0.22%   |
| Apple                          | 2         | 0.22%   |
| Yangtze Memory Technologies    | 1         | 0.11%   |
| Union Memory (Shenzhen)        | 1         | 0.11%   |
| Transcend                      | 1         | 0.11%   |
| Solidigm                       | 1         | 0.11%   |
| Silicon Image                  | 1         | 0.11%   |
| Shenzhen Longsys Electronics   | 1         | 0.11%   |
| Seagate Technology             | 1         | 0.11%   |
| OCZ Technology Group           | 1         | 0.11%   |
| Netac Technology               | 1         | 0.11%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.11%   |
| Integrated Technology Express  | 1         | 0.11%   |
| Adaptec                        | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 78        | 7.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 59        | 5.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 43        | 4.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 33        | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 29        | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 27        | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 2.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 19        | 1.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 16        | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16        | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 15        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 1.41%   |
| AMD 400 Series Chipset SATA Controller                                         | 14        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 13        | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13        | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 1.21%   |
| Intel SATA Controller [RAID mode]                                              | 12        | 1.21%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.11%   |
| Intel SSD 660P Series                                                          | 10        | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 10        | 1.01%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 0.91%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 0.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 0.91%   |
| Phison E12 NVMe Controller                                                     | 8         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.71%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 7         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 7         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 510       | 56.98%  |
| NVMe | 267       | 29.83%  |
| IDE  | 64        | 7.15%   |
| RAID | 52        | 5.81%   |
| SAS  | 2         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 568       | 80%     |
| AMD    | 138       | 19.44%  |
| ARM    | 4         | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 2.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 2.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 11        | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.98%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 0.98%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.84%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.7%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.7%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 4         | 0.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.56%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.56%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.56%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.56%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 4         | 0.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 3         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 199       | 27.99%  |
| Intel Core i5                  | 155       | 21.8%   |
| Other                          | 50        | 7.03%   |
| Intel Core i3                  | 41        | 5.77%   |
| AMD Ryzen 7                    | 38        | 5.34%   |
| AMD Ryzen 5                    | 38        | 5.34%   |
| Intel Celeron                  | 32        | 4.5%    |
| Intel Core 2 Duo               | 21        | 2.95%   |
| Intel Pentium                  | 16        | 2.25%   |
| Intel Xeon                     | 13        | 1.83%   |
| Intel Atom                     | 12        | 1.69%   |
| AMD Ryzen 9                    | 11        | 1.55%   |
| AMD Ryzen 3                    | 9         | 1.27%   |
| Intel Core i9                  | 7         | 0.98%   |
| Intel Pentium Silver           | 5         | 0.7%    |
| Intel Core 2                   | 5         | 0.7%    |
| AMD A6                         | 5         | 0.7%    |
| Intel Pentium Dual-Core        | 4         | 0.56%   |
| Intel Pentium Dual             | 4         | 0.56%   |
| AMD FX                         | 4         | 0.56%   |
| AMD A8                         | 4         | 0.56%   |
| Intel Genuine                  | 3         | 0.42%   |
| Intel Core 2 Quad              | 3         | 0.42%   |
| AMD E                          | 3         | 0.42%   |
| AMD A4                         | 3         | 0.42%   |
| AMD A10                        | 3         | 0.42%   |
| Intel Core m3                  | 2         | 0.28%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.28%   |
| AMD E1                         | 2         | 0.28%   |
| Intel Pentium 4                | 1         | 0.14%   |
| Intel Core m5                  | 1         | 0.14%   |
| ARM BCM                        | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.14%   |
| AMD Sempron                    | 1         | 0.14%   |
| AMD Ryzen Threadripper         | 1         | 0.14%   |
| AMD Ryzen 7 PRO                | 1         | 0.14%   |
| AMD Ryzen 5 PRO                | 1         | 0.14%   |
| AMD Quad-Core                  | 1         | 0.14%   |
| AMD Phenom II X6               | 1         | 0.14%   |
| AMD Phenom II X4               | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 295       | 41.55%  |
| 2      | 244       | 34.37%  |
| 8      | 69        | 9.72%   |
| 6      | 67        | 9.44%   |
| 12     | 10        | 1.41%   |
| 1      | 10        | 1.41%   |
| 16     | 6         | 0.85%   |
| 10     | 3         | 0.42%   |
| 3      | 3         | 0.42%   |
| 14     | 2         | 0.28%   |
| 24     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 702       | 98.87%  |
| 2      | 8         | 1.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 509       | 71.59%  |
| 1      | 202       | 28.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 704       | 99.15%  |
| 32-bit         | 3         | 0.42%   |
| Unknown        | 3         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 276       | 37.4%   |
| 0x206a7    | 37        | 5.01%   |
| 0x306a9    | 33        | 4.47%   |
| 0x806ec    | 26        | 3.52%   |
| 0x306c3    | 24        | 3.25%   |
| 0x806ea    | 18        | 2.44%   |
| 0x906ea    | 17        | 2.3%    |
| 0x806e9    | 16        | 2.17%   |
| 0x806c1    | 15        | 2.03%   |
| 0x1067a    | 14        | 1.9%    |
| 0x506e3    | 13        | 1.76%   |
| 0x406e3    | 12        | 1.63%   |
| 0x40651    | 12        | 1.63%   |
| 0x906e9    | 11        | 1.49%   |
| 0x806eb    | 9         | 1.22%   |
| 0x306d4    | 9         | 1.22%   |
| 0x20655    | 8         | 1.08%   |
| 0xa0652    | 7         | 0.95%   |
| 0x106e5    | 7         | 0.95%   |
| 0x0a50000c | 7         | 0.95%   |
| 0x08600103 | 7         | 0.95%   |
| 0x08600106 | 6         | 0.81%   |
| 0x08108109 | 6         | 0.81%   |
| 0x706a8    | 5         | 0.68%   |
| 0x30678    | 5         | 0.68%   |
| 0x08701021 | 5         | 0.68%   |
| 0x08600104 | 5         | 0.68%   |
| 0x906ec    | 4         | 0.54%   |
| 0x806d1    | 4         | 0.54%   |
| 0x706e5    | 4         | 0.54%   |
| 0x6fd      | 4         | 0.54%   |
| 0x406c4    | 4         | 0.54%   |
| 0x10676    | 4         | 0.54%   |
| 0x08608103 | 4         | 0.54%   |
| 0x0810100b | 4         | 0.54%   |
| 0x0800820d | 4         | 0.54%   |
| 0xa0671    | 3         | 0.41%   |
| 0xa0660    | 3         | 0.41%   |
| 0x906ed    | 3         | 0.41%   |
| 0x906a3    | 3         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 152       | 21.41%  |
| Haswell          | 59        | 8.31%   |
| SandyBridge      | 52        | 7.32%   |
| IvyBridge        | 50        | 7.04%   |
| Zen 2            | 41        | 5.77%   |
| Skylake          | 39        | 5.49%   |
| TigerLake        | 26        | 3.66%   |
| Penryn           | 26        | 3.66%   |
| Unknown          | 23        | 3.24%   |
| CometLake        | 22        | 3.1%    |
| Silvermont       | 21        | 2.96%   |
| Zen+             | 19        | 2.68%   |
| Broadwell        | 19        | 2.68%   |
| Westmere         | 18        | 2.54%   |
| Goldmont plus    | 17        | 2.39%   |
| Zen 3            | 15        | 2.11%   |
| Icelake          | 15        | 2.11%   |
| Core             | 15        | 2.11%   |
| Zen              | 13        | 1.83%   |
| Nehalem          | 11        | 1.55%   |
| Piledriver       | 7         | 0.99%   |
| Goldmont         | 7         | 0.99%   |
| Excavator        | 7         | 0.99%   |
| K10              | 6         | 0.85%   |
| Alderlake Hybrid | 6         | 0.85%   |
| Puma             | 4         | 0.56%   |
| Jaguar           | 4         | 0.56%   |
| Bonnell          | 3         | 0.42%   |
| Bobcat           | 3         | 0.42%   |
| Steamroller      | 2         | 0.28%   |
| K8 Hammer        | 2         | 0.28%   |
| Tremont          | 1         | 0.14%   |
| P6               | 1         | 0.14%   |
| NetBurst         | 1         | 0.14%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| K10 Llano        | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 457       | 53.64%  |
| Nvidia                     | 224       | 26.29%  |
| AMD                        | 169       | 19.84%  |
| Matrox Electronics Systems | 1         | 0.12%   |
| ASPEED Technology          | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 41        | 4.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 3.35%   |
| Intel UHD Graphics 620                                                                   | 27        | 3.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 3%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 2.89%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 25        | 2.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 2.31%   |
| Intel HD Graphics 620                                                                    | 19        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 1.62%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 1.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 1.15%   |
| Intel HD Graphics 530                                                                    | 10        | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.04%   |
| Intel HD Graphics 630                                                                    | 9         | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.81%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.69%   |
| AMD Lucienne                                                                             | 6         | 0.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.58%   |
| Intel HD Graphics 500                                                                    | 5         | 0.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 330       | 46.09%  |
| 1 x AMD         | 125       | 17.46%  |
| 1 x Nvidia      | 110       | 15.36%  |
| Intel + Nvidia  | 96        | 13.41%  |
| Intel + AMD     | 22        | 3.07%   |
| AMD + Nvidia    | 15        | 2.09%   |
| Other           | 6         | 0.84%   |
| 2 x AMD         | 6         | 0.84%   |
| 2 x Nvidia      | 2         | 0.28%   |
| 2 x Intel       | 2         | 0.28%   |
| Nvidia + Matrox | 1         | 0.14%   |
| 1 x ASPEED      | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 547       | 75.76%  |
| Proprietary | 153       | 21.19%  |
| Unknown     | 22        | 3.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 469       | 64.42%  |
| 1.01-2.0   | 67        | 9.2%    |
| 0.01-0.5   | 46        | 6.32%   |
| 3.01-4.0   | 45        | 6.18%   |
| 7.01-8.0   | 34        | 4.67%   |
| 0.51-1.0   | 33        | 4.53%   |
| 5.01-6.0   | 25        | 3.43%   |
| 2.01-3.0   | 4         | 0.55%   |
| 8.01-16.0  | 3         | 0.41%   |
| 16.01-24.0 | 2         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 99        | 12.15%  |
| Samsung Electronics     | 94        | 11.53%  |
| AU Optronics            | 93        | 11.41%  |
| BOE                     | 80        | 9.82%   |
| LG Display              | 62        | 7.61%   |
| Dell                    | 49        | 6.01%   |
| Goldstar                | 33        | 4.05%   |
| Apple                   | 29        | 3.56%   |
| Hewlett-Packard         | 24        | 2.94%   |
| AOC                     | 20        | 2.45%   |
| Acer                    | 19        | 2.33%   |
| BenQ                    | 17        | 2.09%   |
| Ancor Communications    | 17        | 2.09%   |
| Philips                 | 16        | 1.96%   |
| Sharp                   | 14        | 1.72%   |
| Chi Mei Optoelectronics | 13        | 1.6%    |
| Lenovo                  | 10        | 1.23%   |
| PANDA                   | 9         | 1.1%    |
| Unknown                 | 8         | 0.98%   |
| InfoVision              | 7         | 0.86%   |
| Fujitsu Siemens         | 6         | 0.74%   |
| ASUSTek Computer        | 6         | 0.74%   |
| Sony                    | 5         | 0.61%   |
| LG Electronics          | 5         | 0.61%   |
| Iiyama                  | 5         | 0.61%   |
| Idek Iiyama             | 4         | 0.49%   |
| MStar                   | 3         | 0.37%   |
| Medion                  | 3         | 0.37%   |
| LGD                     | 3         | 0.37%   |
| LG Philips              | 3         | 0.37%   |
| Eizo                    | 3         | 0.37%   |
| Vizio                   | 2         | 0.25%   |
| ViewSonic               | 2         | 0.25%   |
| Vestel Elektronik       | 2         | 0.25%   |
| Unknown (AAA)           | 2         | 0.25%   |
| Sceptre Tech            | 2         | 0.25%   |
| SANYO                   | 2         | 0.25%   |
| RTK                     | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| NEC Computers           | 2         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 6         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 6         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch        | 6         | 0.7%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 5         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 5         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 4         | 0.47%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 0.47%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 4         | 0.47%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 3         | 0.35%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 0.35%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 3         | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch        | 3         | 0.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 3         | 0.35%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch          | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch          | 3         | 0.35%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                           | 2         | 0.23%   |
| Unknown LCD Monitor SAMSUNG                                             | 2         | 0.23%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 0.23%   |
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch       | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 2         | 0.23%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                       | 2         | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2         | 0.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 2         | 0.23%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                          | 2         | 0.23%   |
| Medion MD20338 MED3943 1600x900 462x272mm 21.1-inch                     | 2         | 0.23%   |
| LGD LCD Monitor 1920x1080                                               | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 343       | 44.14%  |
| 1366x768 (WXGA)    | 142       | 18.28%  |
| 3840x2160 (4K)     | 45        | 5.79%   |
| 2560x1440 (QHD)    | 32        | 4.12%   |
| 1600x900 (HD+)     | 25        | 3.22%   |
| 1920x1200 (WUXGA)  | 21        | 2.7%    |
| 1280x1024 (SXGA)   | 18        | 2.32%   |
| 3440x1440          | 16        | 2.06%   |
| 1680x1050 (WSXGA+) | 15        | 1.93%   |
| 1280x800 (WXGA)    | 15        | 1.93%   |
| Unknown            | 15        | 1.93%   |
| 2560x1080          | 12        | 1.54%   |
| 1440x900 (WXGA+)   | 11        | 1.42%   |
| 3840x1080          | 7         | 0.9%    |
| 2880x1800          | 5         | 0.64%   |
| 2560x1600          | 5         | 0.64%   |
| 3200x1800 (QHD+)   | 4         | 0.51%   |
| 2160x1440          | 4         | 0.51%   |
| 1920x540           | 4         | 0.51%   |
| 3000x2000          | 3         | 0.39%   |
| 3520x1080          | 2         | 0.26%   |
| 2256x1504          | 2         | 0.26%   |
| 1920x1280          | 2         | 0.26%   |
| 1600x1200          | 2         | 0.26%   |
| 1360x768           | 2         | 0.26%   |
| 7680x2160          | 1         | 0.13%   |
| 5760x2160          | 1         | 0.13%   |
| 4480x1440          | 1         | 0.13%   |
| 4480x1080          | 1         | 0.13%   |
| 3840x2400          | 1         | 0.13%   |
| 3840x1440          | 1         | 0.13%   |
| 3840x1200          | 1         | 0.13%   |
| 3840x1100          | 1         | 0.13%   |
| 3600x1080          | 1         | 0.13%   |
| 3456x2160          | 1         | 0.13%   |
| 3280x1080          | 1         | 0.13%   |
| 2880x1920          | 1         | 0.13%   |
| 2736x1824          | 1         | 0.13%   |
| 2646x768           | 1         | 0.13%   |
| 2560x1024          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 209       | 25.64%  |
| 13      | 106       | 13.01%  |
| 14      | 68        | 8.34%   |
| 24      | 58        | 7.12%   |
| Unknown | 56        | 6.87%   |
| 27      | 55        | 6.75%   |
| 23      | 45        | 5.52%   |
| 17      | 40        | 4.91%   |
| 21      | 29        | 3.56%   |
| 34      | 22        | 2.7%    |
| 31      | 14        | 1.72%   |
| 19      | 14        | 1.72%   |
| 12      | 14        | 1.72%   |
| 11      | 12        | 1.47%   |
| 22      | 7         | 0.86%   |
| 20      | 7         | 0.86%   |
| 18      | 7         | 0.86%   |
| 84      | 6         | 0.74%   |
| 54      | 6         | 0.74%   |
| 16      | 5         | 0.61%   |
| 72      | 4         | 0.49%   |
| 40      | 4         | 0.49%   |
| 48      | 3         | 0.37%   |
| 32      | 3         | 0.37%   |
| 28      | 3         | 0.37%   |
| 52      | 2         | 0.25%   |
| 46      | 2         | 0.25%   |
| 33      | 2         | 0.25%   |
| 29      | 2         | 0.25%   |
| 142     | 1         | 0.12%   |
| 63      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 44      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 35      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 25      | 1         | 0.12%   |
| 10      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 333       | 41.16%  |
| 501-600        | 147       | 18.17%  |
| 201-300        | 81        | 10.01%  |
| Unknown        | 56        | 6.92%   |
| 401-500        | 55        | 6.8%    |
| 351-400        | 50        | 6.18%   |
| 701-800        | 27        | 3.34%   |
| 601-700        | 26        | 3.21%   |
| 1001-1500      | 15        | 1.85%   |
| 1501-2000      | 10        | 1.24%   |
| 801-900        | 6         | 0.74%   |
| 901-1000       | 2         | 0.25%   |
| More than 2000 | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 531       | 72.94%  |
| 16/10   | 79        | 10.85%  |
| Unknown | 49        | 6.73%   |
| 21/9    | 25        | 3.43%   |
| 5/4     | 15        | 2.06%   |
| 3/2     | 14        | 1.92%   |
| 4/3     | 7         | 0.96%   |
| 32/9    | 4         | 0.55%   |
| 1.00    | 2         | 0.27%   |
| 6/5     | 1         | 0.14%   |
| 3.40    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 208       | 25.74%  |
| 81-90          | 133       | 16.46%  |
| 201-250        | 101       | 12.5%   |
| Unknown        | 56        | 6.93%   |
| 301-350        | 55        | 6.81%   |
| 351-500        | 45        | 5.57%   |
| 71-80          | 41        | 5.07%   |
| 151-200        | 32        | 3.96%   |
| 121-130        | 28        | 3.47%   |
| 251-300        | 24        | 2.97%   |
| More than 1000 | 22        | 2.72%   |
| 51-60          | 13        | 1.61%   |
| 141-150        | 12        | 1.49%   |
| 61-70          | 11        | 1.36%   |
| 501-1000       | 11        | 1.36%   |
| 131-140        | 8         | 0.99%   |
| 91-100         | 4         | 0.5%    |
| 111-120        | 3         | 0.37%   |
| 41-50          | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 225       | 28.48%  |
| 51-100        | 213       | 26.96%  |
| 101-120       | 187       | 23.67%  |
| 161-240       | 60        | 7.59%   |
| Unknown       | 56        | 7.09%   |
| More than 240 | 27        | 3.42%   |
| 1-50          | 22        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 548       | 75.38%  |
| 2     | 142       | 19.53%  |
| 0     | 21        | 2.89%   |
| 3     | 15        | 2.06%   |
| 4     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 396       | 36.03%  |
| Realtek Semiconductor           | 369       | 33.58%  |
| Qualcomm Atheros                | 113       | 10.28%  |
| Broadcom                        | 69        | 6.28%   |
| Broadcom Limited                | 20        | 1.82%   |
| MediaTek                        | 15        | 1.36%   |
| Marvell Technology Group        | 11        | 1%      |
| Ralink Technology               | 10        | 0.91%   |
| Ralink                          | 8         | 0.73%   |
| Xiaomi                          | 6         | 0.55%   |
| Nvidia                          | 6         | 0.55%   |
| ASIX Electronics                | 6         | 0.55%   |
| NetGear                         | 5         | 0.45%   |
| Hewlett-Packard                 | 5         | 0.45%   |
| DisplayLink                     | 5         | 0.45%   |
| Microsoft                       | 4         | 0.36%   |
| Lenovo                          | 4         | 0.36%   |
| Sierra Wireless                 | 3         | 0.27%   |
| Qualcomm Atheros Communications | 3         | 0.27%   |
| JMicron Technology              | 3         | 0.27%   |
| Huawei Technologies             | 3         | 0.27%   |
| D-Link System                   | 3         | 0.27%   |
| D-Link                          | 3         | 0.27%   |
| TP-Link                         | 2         | 0.18%   |
| Samsung Electronics             | 2         | 0.18%   |
| OnePlus Technology (Shenzhen)   | 2         | 0.18%   |
| Linksys                         | 2         | 0.18%   |
| Belkin Components               | 2         | 0.18%   |
| ASUSTek Computer                | 2         | 0.18%   |
| Wacom                           | 1         | 0.09%   |
| T & A Mobile Phones             | 1         | 0.09%   |
| Raspberry Pi                    | 1         | 0.09%   |
| Novatek Microelectronics        | 1         | 0.09%   |
| Motorola PCS                    | 1         | 0.09%   |
| Microchip Technology            | 1         | 0.09%   |
| Mercucys                        | 1         | 0.09%   |
| Luminary Micro                  | 1         | 0.09%   |
| Google                          | 1         | 0.09%   |
| FIBOCOM                         | 1         | 0.09%   |
| Exar                            | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 233       | 17.96%  |
| Intel Wi-Fi 6 AX200                                                    | 62        | 4.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 3.01%   |
| Intel Wireless 8265 / 8275                                             | 33        | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 23        | 1.77%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 1.46%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 19        | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 18        | 1.39%   |
| Intel Wireless 8260                                                    | 17        | 1.31%   |
| Intel Wireless 7265                                                    | 17        | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 16        | 1.23%   |
| Intel Wi-Fi 6 AX201                                                    | 16        | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 15        | 1.16%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 13        | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 11        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 11        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 0.85%   |
| Intel Wireless 7260                                                    | 10        | 0.77%   |
| Intel I211 Gigabit Network Connection                                  | 10        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9         | 0.69%   |
| Intel Wireless 3165                                                    | 9         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                   | 9         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                          | 9         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 0.62%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 8         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 0.54%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 7         | 0.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 7         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 322       | 51.19%  |
| Qualcomm Atheros                      | 88        | 13.99%  |
| Realtek Semiconductor                 | 84        | 13.35%  |
| Broadcom                              | 50        | 7.95%   |
| MediaTek                              | 15        | 2.38%   |
| Broadcom Limited                      | 14        | 2.23%   |
| Ralink Technology                     | 10        | 1.59%   |
| Ralink                                | 8         | 1.27%   |
| NetGear                               | 5         | 0.79%   |
| Microsoft                             | 4         | 0.64%   |
| Sierra Wireless                       | 3         | 0.48%   |
| Qualcomm Atheros Communications       | 3         | 0.48%   |
| Marvell Technology Group              | 3         | 0.48%   |
| D-Link                                | 3         | 0.48%   |
| TP-Link                               | 2         | 0.32%   |
| Linksys                               | 2         | 0.32%   |
| D-Link System                         | 2         | 0.32%   |
| Belkin Components                     | 2         | 0.32%   |
| ASUSTek Computer                      | 2         | 0.32%   |
| Wacom                                 | 1         | 0.16%   |
| Mercucys                              | 1         | 0.16%   |
| Hewlett-Packard                       | 1         | 0.16%   |
| FIBOCOM                               | 1         | 0.16%   |
| Edimax Technology                     | 1         | 0.16%   |
| BUFFALO                               | 1         | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 62        | 9.78%   |
| Intel Wireless 8265 / 8275                                           | 33        | 5.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 23        | 3.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 19        | 3%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 18        | 2.84%   |
| Intel Wireless 8260                                                  | 17        | 2.68%   |
| Intel Wireless 7265                                                  | 17        | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 16        | 2.52%   |
| Intel Wi-Fi 6 AX201                                                  | 16        | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 15        | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 13        | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 13        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 12        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 11        | 1.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 11        | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 1.74%   |
| Intel Wireless 7260                                                  | 10        | 1.58%   |
| Intel Wireless 3165                                                  | 9         | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 9         | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 9         | 1.42%   |
| Broadcom BCM43142 802.11b/g/n                                        | 9         | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 8         | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 7         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 7         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 1.1%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 7         | 1.1%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 7         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 6         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 6         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 6         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 5         | 0.79%   |
| Realtek 802.11ac NIC                                                 | 5         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 0.79%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 0.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 5         | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                         | 4         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 4         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 332       | 52.7%   |
| Intel                         | 174       | 27.62%  |
| Broadcom                      | 36        | 5.71%   |
| Qualcomm Atheros              | 34        | 5.4%    |
| Marvell Technology Group      | 8         | 1.27%   |
| Xiaomi                        | 6         | 0.95%   |
| Nvidia                        | 6         | 0.95%   |
| Broadcom Limited              | 6         | 0.95%   |
| ASIX Electronics              | 6         | 0.95%   |
| DisplayLink                   | 5         | 0.79%   |
| Lenovo                        | 4         | 0.63%   |
| JMicron Technology            | 3         | 0.48%   |
| Samsung Electronics           | 2         | 0.32%   |
| OnePlus Technology (Shenzhen) | 2         | 0.32%   |
| Hewlett-Packard               | 2         | 0.32%   |
| T & A Mobile Phones           | 1         | 0.16%   |
| Google                        | 1         | 0.16%   |
| D-Link System                 | 1         | 0.16%   |
| Apple                         | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 233       | 35.85%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 6.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 4.15%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 2.92%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 2.15%   |
| Intel I211 Gigabit Network Connection                                  | 10        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9         | 1.38%   |
| Intel Ethernet Connection (7) I219-V                                   | 9         | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.38%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 1.23%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 8         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.92%   |
| Intel Ethernet Controller I225-V                                       | 6         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.77%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.77%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                   | 5         | 0.77%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.77%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.77%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.62%   |
| Intel Ethernet Connection I219-V                                       | 4         | 0.62%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.62%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 0.62%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 4         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.46%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.46%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 3         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 597       | 49.54%  |
| Ethernet | 595       | 49.38%  |
| Modem    | 12        | 1%      |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 478       | 63.65%  |
| Ethernet | 273       | 36.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 417       | 58.65%  |
| 1     | 262       | 36.85%  |
| 0     | 17        | 2.39%   |
| 3     | 15        | 2.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 573       | 79.47%  |
| Yes  | 148       | 20.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 272       | 52.51%  |
| Realtek Semiconductor           | 37        | 7.14%   |
| Qualcomm Atheros Communications | 37        | 7.14%   |
| Apple                           | 31        | 5.98%   |
| Cambridge Silicon Radio         | 26        | 5.02%   |
| Broadcom                        | 24        | 4.63%   |
| IMC Networks                    | 20        | 3.86%   |
| Foxconn / Hon Hai               | 15        | 2.9%    |
| Lite-On Technology              | 12        | 2.32%   |
| Dell                            | 10        | 1.93%   |
| Hewlett-Packard                 | 7         | 1.35%   |
| Realtek                         | 5         | 0.97%   |
| Ralink                          | 4         | 0.77%   |
| MediaTek                        | 3         | 0.58%   |
| Marvell Semiconductor           | 3         | 0.58%   |
| Belkin Components               | 3         | 0.58%   |
| ASUSTek Computer                | 3         | 0.58%   |
| Toshiba                         | 2         | 0.39%   |
| Foxconn International           | 2         | 0.39%   |
| Smart Modular Technologies      | 1         | 0.19%   |
| Integrated System Solution      | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 60        | 11.58%  |
| Intel Bluetooth Device                                                              | 47        | 9.07%   |
| Intel Bluetooth wireless interface                                                  | 42        | 8.11%   |
| Intel AX201 Bluetooth                                                               | 39        | 7.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 30        | 5.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 26        | 5.02%   |
| Realtek Bluetooth Radio                                                             | 20        | 3.86%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 20        | 3.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 19        | 3.67%   |
| Apple Bluetooth Host Controller                                                     | 12        | 2.32%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 11        | 2.12%   |
| Intel AX210 Bluetooth                                                               | 11        | 2.12%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 2.12%   |
| Dell DW375 Bluetooth Module                                                         | 9         | 1.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 1.54%   |
| Intel AX211 Bluetooth                                                               | 6         | 1.16%   |
| IMC Networks Wireless_Device                                                        | 6         | 1.16%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.97%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 0.97%   |
| Realtek Bluetooth Radio                                                             | 5         | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 0.97%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.97%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 5         | 0.97%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 0.77%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.77%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 4         | 0.77%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.58%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 0.58%   |
| MediaTek Wireless_Device                                                            | 3         | 0.58%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.58%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 3         | 0.58%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 549       | 54.95%  |
| AMD                        | 175       | 17.52%  |
| Nvidia                     | 165       | 16.52%  |
| Logitech                   | 11        | 1.1%    |
| C-Media Electronics        | 11        | 1.1%    |
| Realtek Semiconductor      | 9         | 0.9%    |
| GN Netcom                  | 9         | 0.9%    |
| Texas Instruments          | 5         | 0.5%    |
| JMTek                      | 5         | 0.5%    |
| Plantronics                | 4         | 0.4%    |
| DSEA A/S                   | 4         | 0.4%    |
| Creative Technology        | 4         | 0.4%    |
| Creative Labs              | 4         | 0.4%    |
| Kingston Technology        | 3         | 0.3%    |
| Apple                      | 3         | 0.3%    |
| Samson Technologies        | 2         | 0.2%    |
| Lenovo                     | 2         | 0.2%    |
| Blue Microphones           | 2         | 0.2%    |
| ASUSTek Computer           | 2         | 0.2%    |
| AKAI Professional M.I.     | 2         | 0.2%    |
| XMOS                       | 1         | 0.1%    |
| SteelSeries ApS            | 1         | 0.1%    |
| Shure                      | 1         | 0.1%    |
| Sennheiser Communications  | 1         | 0.1%    |
| Razer USA                  | 1         | 0.1%    |
| PreSonus Audio Electronics | 1         | 0.1%    |
| OPPO Electronics           | 1         | 0.1%    |
| No brand                   | 1         | 0.1%    |
| Native Instruments         | 1         | 0.1%    |
| Nam Tai E&E Products       | 1         | 0.1%    |
| Microsoft                  | 1         | 0.1%    |
| M-Audio                    | 1         | 0.1%    |
| LINE TECH INDUSTRIAL       | 1         | 0.1%    |
| Hewlett-Packard            | 1         | 0.1%    |
| GYROCOM C&C                | 1         | 0.1%    |
| Giga-Byte Technology       | 1         | 0.1%    |
| Generalplus Technology     | 1         | 0.1%    |
| Focusrite-Novation         | 1         | 0.1%    |
| Focusrite                  | 1         | 0.1%    |
| Conexant Systems           | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 71        | 6.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 67        | 5.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 48        | 4.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 36        | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33        | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 31        | 2.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 29        | 2.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 26        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25        | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 25        | 2.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 24        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21        | 1.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 20        | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 17        | 1.46%   |
| Intel Broadwell-U Audio Controller                                         | 17        | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 1.46%   |
| Nvidia GP106 High Definition Audio Controller                              | 15        | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15        | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 12        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 0.94%   |
| Intel CM238 HD Audio Controller                                            | 11        | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 0.86%   |
| Realtek Semiconductor USB Audio                                            | 9         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 133       | 28.18%  |
| SK hynix            | 90        | 19.07%  |
| Kingston            | 47        | 9.96%   |
| Micron Technology   | 46        | 9.75%   |
| Crucial             | 33        | 6.99%   |
| Unknown             | 27        | 5.72%   |
| Corsair             | 13        | 2.75%   |
| Ramaxel Technology  | 12        | 2.54%   |
| A-DATA Technology   | 9         | 1.91%   |
| G.Skill             | 8         | 1.69%   |
| Unknown (ABCD)      | 7         | 1.48%   |
| Team                | 5         | 1.06%   |
| Elpida              | 5         | 1.06%   |
| Nanya Technology    | 3         | 0.64%   |
| Unknown             | 3         | 0.64%   |
| Transcend           | 2         | 0.42%   |
| Timetec             | 2         | 0.42%   |
| Teikon              | 2         | 0.42%   |
| Smart               | 2         | 0.42%   |
| PNY                 | 2         | 0.42%   |
| Goodram             | 2         | 0.42%   |
| Unknown (F301)      | 1         | 0.21%   |
| Unknown (0x873E)    | 1         | 0.21%   |
| Smart Brazil        | 1         | 0.21%   |
| Sesame              | 1         | 0.21%   |
| Patriot             | 1         | 0.21%   |
| Magnum Tech         | 1         | 0.21%   |
| Lexar               | 1         | 0.21%   |
| Kingmax             | 1         | 0.21%   |
| Goldkey             | 1         | 0.21%   |
| ff                  | 1         | 0.21%   |
| fef5                | 1         | 0.21%   |
| Cors                | 1         | 0.21%   |
| ChangXin Memory     | 1         | 0.21%   |
| Avant               | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| Apacer              | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |
| 8945000080AD        | 1         | 0.21%   |
| 4ea5                | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 10        | 2.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.2%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.8%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 0.8%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.6%    |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.6%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Unknown                                                          | 3         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.4%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.4%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.4%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.4%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.4%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 198       | 49.13%  |
| DDR3    | 128       | 31.76%  |
| LPDDR4  | 24        | 5.96%   |
| LPDDR3  | 18        | 4.47%   |
| DDR2    | 12        | 2.98%   |
| SDRAM   | 9         | 2.23%   |
| Unknown | 6         | 1.49%   |
| DDR5    | 4         | 0.99%   |
| DDR     | 2         | 0.5%    |
| LPDDR5  | 1         | 0.25%   |
| DRAM    | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 267       | 66.92%  |
| DIMM         | 88        | 22.06%  |
| Row Of Chips | 35        | 8.77%   |
| Unknown      | 4         | 1%      |
| FB-DIMM      | 2         | 0.5%    |
| Chip         | 2         | 0.5%    |
| RIMM         | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 162       | 37.59%  |
| 4096  | 119       | 27.61%  |
| 16384 | 68        | 15.78%  |
| 2048  | 41        | 9.51%   |
| 32768 | 27        | 6.26%   |
| 1024  | 12        | 2.78%   |
| 512   | 2         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 91        | 20.5%   |
| 2667    | 81        | 18.24%  |
| 3200    | 65        | 14.64%  |
| 2400    | 36        | 8.11%   |
| 2133    | 29        | 6.53%   |
| 1333    | 25        | 5.63%   |
| 1334    | 12        | 2.7%    |
| 1867    | 10        | 2.25%   |
| 3266    | 9         | 2.03%   |
| Unknown | 9         | 2.03%   |
| 4267    | 7         | 1.58%   |
| 1067    | 7         | 1.58%   |
| 667     | 6         | 1.35%   |
| 4199    | 4         | 0.9%    |
| 3733    | 4         | 0.9%    |
| 3400    | 4         | 0.9%    |
| 1066    | 4         | 0.9%    |
| 800     | 4         | 0.9%    |
| 8400    | 3         | 0.68%   |
| 4800    | 3         | 0.68%   |
| 4266    | 3         | 0.68%   |
| 3000    | 3         | 0.68%   |
| 533     | 3         | 0.68%   |
| 3666    | 2         | 0.45%   |
| 3600    | 2         | 0.45%   |
| 2472    | 2         | 0.45%   |
| 1800    | 2         | 0.45%   |
| 6400    | 1         | 0.23%   |
| 6000    | 1         | 0.23%   |
| 3866    | 1         | 0.23%   |
| 3800    | 1         | 0.23%   |
| 3500    | 1         | 0.23%   |
| 3007    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 2666    | 1         | 0.23%   |
| 2134    | 1         | 0.23%   |
| 2048    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 1639    | 1         | 0.23%   |
| 1331    | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Canon               | 4         | 25%     |
| Samsung Electronics | 2         | 12.5%   |
| Brother Industries  | 2         | 12.5%   |
| Sharp               | 1         | 6.25%   |
| Fuji Xerox          | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Sharp AL-2030                 | 1         | 6.25%   |
| Samsung ML-1510 Laser Printer | 1         | 6.25%   |
| Samsung M2020 Series          | 1         | 6.25%   |
| HP LaserJet 1320              | 1         | 6.25%   |
| HP DeskJet 3700 series        | 1         | 6.25%   |
| HP Deskjet 3050 J610 series   | 1         | 6.25%   |
| HP Deskjet 2540 series        | 1         | 6.25%   |
| HP DeskJet 2130 series        | 1         | 6.25%   |
| Fuji Xerox DocuPrint CM305 df | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 450   | 1         | 6.25%   |
| Canon TR7500 series           | 1         | 6.25%   |
| Canon MF4010 series           | 1         | 6.25%   |
| Canon MF240 Series UFRII LT   | 1         | 6.25%   |
| Canon LiDE 400                | 1         | 6.25%   |
| Brother MFC-1810              | 1         | 6.25%   |
| Brother HL-2240 series        | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 116       | 23.67%  |
| IMC Networks                           | 42        | 8.57%   |
| Sunplus Innovation Technology          | 37        | 7.55%   |
| Realtek Semiconductor                  | 35        | 7.14%   |
| Microdia                               | 35        | 7.14%   |
| Bison Electronics                      | 32        | 6.53%   |
| Apple                                  | 25        | 5.1%    |
| Logitech                               | 22        | 4.49%   |
| Quanta                                 | 18        | 3.67%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.67%   |
| Syntek                                 | 12        | 2.45%   |
| Suyin                                  | 12        | 2.45%   |
| Luxvisions Innotech Limited            | 8         | 1.63%   |
| Acer                                   | 8         | 1.63%   |
| Silicon Motion                         | 7         | 1.43%   |
| Lite-On Technology                     | 7         | 1.43%   |
| Samsung Electronics                    | 5         | 1.02%   |
| Microsoft                              | 5         | 1.02%   |
| Generalplus Technology                 | 5         | 1.02%   |
| Alcor Micro                            | 4         | 0.82%   |
| Ricoh                                  | 3         | 0.61%   |
| Z-Star Microelectronics                | 2         | 0.41%   |
| LG Electronics                         | 2         | 0.41%   |
| Importek                               | 2         | 0.41%   |
| ARC International                      | 2         | 0.41%   |
| ALi                                    | 2         | 0.41%   |
| Unknown                                | 2         | 0.41%   |
| Y Media                                | 1         | 0.2%    |
| WaveRider Communications               | 1         | 0.2%    |
| ValueHD                                | 1         | 0.2%    |
| Unknown                                | 1         | 0.2%    |
| Tobii Technology AB                    | 1         | 0.2%    |
| Sonix Technology                       | 1         | 0.2%    |
| ShineTech                              | 1         | 0.2%    |
| Qtech                                  | 1         | 0.2%    |
| Primax Electronics                     | 1         | 0.2%    |
| Polycom                                | 1         | 0.2%    |
| Pixart Imaging                         | 1         | 0.2%    |
| OPPO Electronics                       | 1         | 0.2%    |
| Omnivision                             | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                   | 18        | 3.64%   |
| Chicony HD Webcam                                       | 16        | 3.24%   |
| Microdia Integrated_Webcam_HD                           | 14        | 2.83%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 14        | 2.83%   |
| Chicony Integrated Camera                               | 14        | 2.83%   |
| IMC Networks Integrated Camera                          | 12        | 2.43%   |
| Realtek Integrated_Webcam_HD                            | 11        | 2.23%   |
| Chicony HP HD Camera                                    | 9         | 1.82%   |
| Apple FaceTime HD Camera (Built-in)                     | 8         | 1.62%   |
| Logitech HD Pro Webcam C920                             | 7         | 1.42%   |
| Chicony Integrated IR Camera                            | 7         | 1.42%   |
| Bison BisonCam,NB Pro                                   | 7         | 1.42%   |
| Apple Built-in iSight                                   | 7         | 1.42%   |
| Syntek Integrated Camera                                | 6         | 1.21%   |
| Bison Integrated Camera                                 | 6         | 1.21%   |
| Bison HD Webcam                                         | 6         | 1.21%   |
| Apple FaceTime HD Camera                                | 6         | 1.21%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 1.01%   |
| Sunplus HD WebCam                                       | 5         | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 5         | 1.01%   |
| IMC Networks VGA UVC WebCam                             | 4         | 0.81%   |
| Chicony EasyCamera                                      | 4         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 0.81%   |
| Bison SunplusIT Integrated Camera                       | 4         | 0.81%   |
| Bison EasyCamera                                        | 4         | 0.81%   |
| Acer Integrated Camera                                  | 4         | 0.81%   |
| Suyin HP Truevision HD                                  | 3         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 3         | 0.61%   |
| Sunplus Integrated_Webcam_FHD                           | 3         | 0.61%   |
| Sunplus Asus Webcam                                     | 3         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                            | 3         | 0.61%   |
| Realtek Lenovo EasyCamera                               | 3         | 0.61%   |
| Realtek Integrated Webcam                               | 3         | 0.61%   |
| Realtek HD WebCam                                       | 3         | 0.61%   |
| Quanta USB2.0 HD UVC WebCam                             | 3         | 0.61%   |
| Quanta HD User Facing                                   | 3         | 0.61%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 0.61%   |
| Luxvisions Innotech Limited Integrated Camera           | 3         | 0.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 0.61%   |
| Generalplus CAMERA - UVC                                | 3         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 40        | 36.04%  |
| Validity Sensors           | 35        | 31.53%  |
| Shenzhen Goodix Technology | 18        | 16.22%  |
| LighTuning Technology      | 8         | 7.21%   |
| Elan Microelectronics      | 6         | 5.41%   |
| AuthenTec                  | 4         | 3.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 10.81%  |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 9.91%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 7.21%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 4.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4.5%    |
| Elan ELAN:Fingerprint                                                      | 5         | 4.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.6%    |
| Synaptics WBDI Device                                                      | 4         | 3.6%    |
| Synaptics TouchPad                                                         | 4         | 3.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.6%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 3.6%    |
| Unknown                                                                    | 4         | 3.6%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.7%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.8%    |
| Validity Sensors VFS491                                                    | 2         | 1.8%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.8%    |
| Synaptics UWP WBDI Device                                                  | 2         | 1.8%    |
| Synaptics UWP WBDI                                                         | 2         | 1.8%    |
| Synaptics  WBDI                                                            | 2         | 1.8%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.8%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.8%    |
| AuthenTec AES1600                                                          | 2         | 1.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.9%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.9%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.9%    |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.9%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.9%    |
| Elan ELAN:ARM-M4                                                           | 1         | 0.9%    |
| AuthenTec AES2810                                                          | 1         | 0.9%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 16        | 50%     |
| Alcor Micro           | 8         | 25%     |
| Upek                  | 5         | 15.63%  |
| Lenovo                | 2         | 6.25%   |
| Gemalto (was Gemplus) | 1         | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 21.88%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 21.88%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 15.63%  |
| Broadcom 5880                                                                | 5         | 15.63%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.25%   |
| Broadcom 58200                                                               | 2         | 6.25%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.13%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 472       | 65.28%  |
| 1     | 198       | 27.39%  |
| 2     | 42        | 5.81%   |
| 3     | 6         | 0.83%   |
| 4     | 2         | 0.28%   |
| 9     | 1         | 0.14%   |
| 7     | 1         | 0.14%   |
| 5     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 110       | 36.79%  |
| Graphics card            | 54        | 18.06%  |
| Chipcard                 | 31        | 10.37%  |
| Net/wireless             | 28        | 9.36%   |
| Communication controller | 20        | 6.69%   |
| Multimedia controller    | 11        | 3.68%   |
| Camera                   | 11        | 3.68%   |
| Sound                    | 8         | 2.68%   |
| Bluetooth                | 8         | 2.68%   |
| Card reader              | 7         | 2.34%   |
| Storage                  | 5         | 1.67%   |
| Unassigned class         | 4         | 1.34%   |
| Net/ethernet             | 2         | 0.67%   |

