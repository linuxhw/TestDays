Sparky - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Sparky.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Sparky/Desktop/README.md) and [notebooks](/Dist/Sparky/Notebook/README.md).

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

Total: 168

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [17bae1fed1](https://linux-hardware.org/?probe=17bae1fed1) | Jan 03, 2026 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fe9e88163a](https://linux-hardware.org/?probe=fe9e88163a) | Jan 03, 2026 |
| HP            | ProBook 6560b               | Notebook    | [182da91655](https://linux-hardware.org/?probe=182da91655) | Jan 03, 2026 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [8ba69eb230](https://linux-hardware.org/?probe=8ba69eb230) | Dec 23, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | Notebook    | [d2908fddcd](https://linux-hardware.org/?probe=d2908fddcd) | Dec 22, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b797292408](https://linux-hardware.org/?probe=b797292408) | Dec 21, 2025 |
| Dell          | Inspiron 5535               | Notebook    | [063482a1f5](https://linux-hardware.org/?probe=063482a1f5) | Nov 19, 2025 |
| Apple         | MacBookPro5,1               | Notebook    | [7443e73d63](https://linux-hardware.org/?probe=7443e73d63) | Nov 14, 2025 |
| Acer          | Aspire XC-330               | Desktop     | [bb8249dd5e](https://linux-hardware.org/?probe=bb8249dd5e) | Jul 18, 2025 |
| ASUSTek       | X450CA                      | Notebook    | [ebf7b86f8b](https://linux-hardware.org/?probe=ebf7b86f8b) | Jul 07, 2025 |
| Medion        | MS-7800                     | Desktop     | [375a79e448](https://linux-hardware.org/?probe=375a79e448) | Jun 23, 2025 |
| Dell          | 02P9X9 A04                  | Server      | [7d395c48fc](https://linux-hardware.org/?probe=7d395c48fc) | Jun 14, 2025 |
| HP            | Compaq CQ45                 | Notebook    | [22c2ab9efc](https://linux-hardware.org/?probe=22c2ab9efc) | May 28, 2025 |
| Toshiba       | Satellite P755              | Notebook    | [114d7f3084](https://linux-hardware.org/?probe=114d7f3084) | May 13, 2025 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [9f416ad681](https://linux-hardware.org/?probe=9f416ad681) | Mar 27, 2025 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [ee7d28d410](https://linux-hardware.org/?probe=ee7d28d410) | Mar 13, 2025 |
| Medion        | MS-7800                     | Desktop     | [c70e12352a](https://linux-hardware.org/?probe=c70e12352a) | Mar 04, 2025 |
| ASUSTek       | Z97-PRO                     | Desktop     | [831832b4b7](https://linux-hardware.org/?probe=831832b4b7) | Feb 20, 2025 |
| MSI           | B450-A PRO                  | Desktop     | [fa8374d09c](https://linux-hardware.org/?probe=fa8374d09c) | Jan 01, 2025 |
| ASUSTek       | X510UAR                     | Notebook    | [758c2eb717](https://linux-hardware.org/?probe=758c2eb717) | Dec 17, 2024 |
| Medion        | Cattle24 -1M                | Desktop     | [61c76bd6c0](https://linux-hardware.org/?probe=61c76bd6c0) | Dec 12, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [cd9edd2505](https://linux-hardware.org/?probe=cd9edd2505) | Dec 01, 2024 |
| Gigabyte      | MCMLUCB-00                  | Desktop     | [399b34534b](https://linux-hardware.org/?probe=399b34534b) | Nov 30, 2024 |
| Shuttle       | NC03U                       | Notebook    | [b21ed9ceef](https://linux-hardware.org/?probe=b21ed9ceef) | Nov 15, 2024 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [03b66cc4a0](https://linux-hardware.org/?probe=03b66cc4a0) | Nov 11, 2024 |
| Acer          | Aspire XC-330               | Desktop     | [7edd74c7bc](https://linux-hardware.org/?probe=7edd74c7bc) | Nov 02, 2024 |
| HP            | 83E9                        | Desktop     | [a8c7212eec](https://linux-hardware.org/?probe=a8c7212eec) | Oct 26, 2024 |
| ASRock        | 880G Extreme3               | Desktop     | [a11c4a176b](https://linux-hardware.org/?probe=a11c4a176b) | Oct 16, 2024 |
| HP            | 83E9                        | Desktop     | [a26f6b9e1d](https://linux-hardware.org/?probe=a26f6b9e1d) | Oct 09, 2024 |
| Dell          | 0782GW A01                  | Desktop     | [d1ed50314a](https://linux-hardware.org/?probe=d1ed50314a) | Oct 03, 2024 |
| HP            | 1497                        | Desktop     | [e347f83774](https://linux-hardware.org/?probe=e347f83774) | Sep 30, 2024 |
| Dell          | 03NVJ6 A02                  | Desktop     | [42eb12cacb](https://linux-hardware.org/?probe=42eb12cacb) | Sep 29, 2024 |
| HP            | 829A                        | Mini pc     | [fae3df78a0](https://linux-hardware.org/?probe=fae3df78a0) | Sep 26, 2024 |
| HP            | 3396                        | Desktop     | [82e508aef8](https://linux-hardware.org/?probe=82e508aef8) | Sep 25, 2024 |
| HP            | 8055                        | Desktop     | [556b046357](https://linux-hardware.org/?probe=556b046357) | Sep 25, 2024 |
| HP            | 339A                        | Desktop     | [21dd06c3ca](https://linux-hardware.org/?probe=21dd06c3ca) | Sep 23, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [c5244dca84](https://linux-hardware.org/?probe=c5244dca84) | Sep 23, 2024 |
| HP            | 829A                        | Mini pc     | [d8ce88a642](https://linux-hardware.org/?probe=d8ce88a642) | Sep 23, 2024 |
| Gigabyte      | MCMLUCB-00                  | Desktop     | [1ffefdd590](https://linux-hardware.org/?probe=1ffefdd590) | Sep 23, 2024 |
| Dell          | 0782GW A01                  | Desktop     | [a37ebb47f3](https://linux-hardware.org/?probe=a37ebb47f3) | Sep 23, 2024 |
| Dell          | 0YXT71 A03                  | Desktop     | [f102a6007a](https://linux-hardware.org/?probe=f102a6007a) | Sep 23, 2024 |
| HP            | 8298                        | Desktop     | [4c6705e4c4](https://linux-hardware.org/?probe=4c6705e4c4) | Sep 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595b48d6f](https://linux-hardware.org/?probe=3595b48d6f) | Jun 17, 2024 |
| Toshiba       | Satellite L505D             | Notebook    | [a6d35efbaa](https://linux-hardware.org/?probe=a6d35efbaa) | Jun 11, 2024 |
| Google        | Fleex                       | Notebook    | [281114687b](https://linux-hardware.org/?probe=281114687b) | May 29, 2024 |
| Google        | Setzer                      | Notebook    | [a62ca31dce](https://linux-hardware.org/?probe=a62ca31dce) | May 25, 2024 |
| Google        | Meep                        | Notebook    | [8c7de68350](https://linux-hardware.org/?probe=8c7de68350) | May 13, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c03d3e0508](https://linux-hardware.org/?probe=c03d3e0508) | May 03, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [1b0129f0b0](https://linux-hardware.org/?probe=1b0129f0b0) | Apr 06, 2024 |
| Sony          | SVE1513Q1ESI                | Notebook    | [9362c14552](https://linux-hardware.org/?probe=9362c14552) | Mar 25, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [fc06ed6b10](https://linux-hardware.org/?probe=fc06ed6b10) | Feb 20, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b861f48e1b](https://linux-hardware.org/?probe=b861f48e1b) | Feb 18, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [cf3126113e](https://linux-hardware.org/?probe=cf3126113e) | Feb 15, 2024 |
| Lenovo        | 315F NOK                    | Desktop     | [620272c63f](https://linux-hardware.org/?probe=620272c63f) | Feb 13, 2024 |
| Google        | Kefka                       | Notebook    | [810d5a47f7](https://linux-hardware.org/?probe=810d5a47f7) | Jan 27, 2024 |
| HP            | 212B                        | Desktop     | [cb5e65ba08](https://linux-hardware.org/?probe=cb5e65ba08) | Jan 21, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [655eb2734a](https://linux-hardware.org/?probe=655eb2734a) | Jan 11, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [ea07a49b87](https://linux-hardware.org/?probe=ea07a49b87) | Jan 07, 2024 |
| Acer          | Aspire X3950                | Desktop     | [09dfa7ff4b](https://linux-hardware.org/?probe=09dfa7ff4b) | Jan 04, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [689d3295aa](https://linux-hardware.org/?probe=689d3295aa) | Dec 30, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [4efea61fa3](https://linux-hardware.org/?probe=4efea61fa3) | Dec 29, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [6e6573e5fe](https://linux-hardware.org/?probe=6e6573e5fe) | Dec 29, 2023 |
| Acer          | FIH57                       | Desktop     | [0edb232edf](https://linux-hardware.org/?probe=0edb232edf) | Dec 16, 2023 |
| HP            | 0A80h                       | Desktop     | [5e6a479e17](https://linux-hardware.org/?probe=5e6a479e17) | Dec 01, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [80d1578d90](https://linux-hardware.org/?probe=80d1578d90) | Oct 30, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [ad3f143871](https://linux-hardware.org/?probe=ad3f143871) | Oct 20, 2023 |
| Medion        | E15415                      | Notebook    | [b9a4ecdc97](https://linux-hardware.org/?probe=b9a4ecdc97) | Oct 14, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6cbfa96139](https://linux-hardware.org/?probe=6cbfa96139) | Sep 07, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b0dbfa8a76](https://linux-hardware.org/?probe=b0dbfa8a76) | Aug 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [da3f894af1](https://linux-hardware.org/?probe=da3f894af1) | Aug 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4006007a76](https://linux-hardware.org/?probe=4006007a76) | Aug 20, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6a155984af](https://linux-hardware.org/?probe=6a155984af) | Aug 19, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [d7383d2980](https://linux-hardware.org/?probe=d7383d2980) | Jul 20, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f7a66609af](https://linux-hardware.org/?probe=f7a66609af) | Jul 13, 2023 |
| ASUSTek       | ET2411_W8                   | All in one  | [27d0310272](https://linux-hardware.org/?probe=27d0310272) | Jul 13, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| ASUSTek       | M4N68T-M                    | Desktop     | [f0b58c9f4e](https://linux-hardware.org/?probe=f0b58c9f4e) | Jun 12, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| Panasonic     | CFSZ5-2                     | Notebook    | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [37dab045c7](https://linux-hardware.org/?probe=37dab045c7) | May 21, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | 1589                        | Desktop     | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| HP            | 1589                        | Desktop     | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| HP            | 0A5Ch                       | Desktop     | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Apple         | MacBook1,1                  | Notebook    | [002929e495](https://linux-hardware.org/?probe=002929e495) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [097be8dd03](https://linux-hardware.org/?probe=097be8dd03) | Mar 08, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Acer          | Aspire X3470                | Desktop     | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| Positivo      | CHT14B                      | Notebook    | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [c343cec0c8](https://linux-hardware.org/?probe=c343cec0c8) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| Apple         | MacBook1,1                  | Notebook    | [6945006338](https://linux-hardware.org/?probe=6945006338) | Nov 15, 2022 |
| Google        | Swanky                      | Notebook    | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [236d8cb74e](https://linux-hardware.org/?probe=236d8cb74e) | Aug 29, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b4006730ce](https://linux-hardware.org/?probe=b4006730ce) | Jul 17, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel         | H61                         | Desktop     | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| HP            | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| Intel         | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek       | S101                        | Notebook    | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP            | Pavilion g7                 | Notebook    | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google        | Banon                       | Notebook    | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP            | 805B                        | Desktop     | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [7243895ae4](https://linux-hardware.org/?probe=7243895ae4) | Apr 20, 2021 |
| Apple         | MacBook1,1                  | Notebook    | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung       | NC10                        | Notebook    | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung       | NC10                        | Notebook    | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Gigabyte      | H410M H                     | Desktop     | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Beelink       | BT3 PRO                     | Notebook    | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink       | BT3 PRO                     | Notebook    | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung       | NC10                        | Notebook    | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP            | 8056                        | Desktop     | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines     | E525                        | Notebook    | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo        | IdeaPad S206 20154          | Notebook    | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| Gigabyte      | M68M-S2P                    | Desktop     | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| HP            | Laptop 17z-ca100            | Notebook    | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP            | Laptop 17z-ca100            | Notebook    | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Apple         | MacBook1,1                  | Notebook    | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell          | 039VR8 A00                  | Desktop     | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Vorke         | V1 Plus                     | Desktop     | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel         | DG43RK AAE78175-402         | Desktop     | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| Lenovo        | ThinkPad T60 2007FUG        | Notebook    | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell          | Latitude XT3                | Notebook    | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP            | Pavilion dv9000 (GA359UA... | Notebook    | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP            | Pavilion dv9000 (GA359UA... | Notebook    | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |
| ASRock        | H61M-VG4                    | Desktop     | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 8    | 17        | 12.59%  |
| Sparky 6    | 16        | 11.85%  |
| Sparky 7.5  | 15        | 11.11%  |
| Sparky 7    | 12        | 8.89%   |
| Sparky 6.7  | 6         | 4.44%   |
| Sparky 6.1  | 6         | 4.44%   |
| Sparky 7.1  | 5         | 3.7%    |
| Sparky 6.5  | 5         | 3.7%    |
| Sparky 5.12 | 5         | 3.7%    |
| Sparky 7.7  | 4         | 2.96%   |
| Sparky 7.3  | 4         | 2.96%   |
| Sparky 7.2  | 4         | 2.96%   |
| Sparky 7.0  | 4         | 2.96%   |
| Sparky 6.6  | 4         | 2.96%   |
| Sparky 6.3  | 4         | 2.96%   |
| Sparky 7.4  | 3         | 2.22%   |
| Sparky 6.0  | 3         | 2.22%   |
| Sparky 5.14 | 3         | 2.22%   |
| Sparky 5.10 | 3         | 2.22%   |
| Sparky 9    | 2         | 1.48%   |
| Sparky 8.1  | 2         | 1.48%   |
| Sparky 7.6  | 2         | 1.48%   |
| Sparky 6.2  | 2         | 1.48%   |
| Sparky 5.13 | 2         | 1.48%   |
| Sparky 8.0  | 1         | 0.74%   |
| Sparky 7.8  | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 126       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.1.0-25-amd64         | 9         | 6.34%   |
| 6.1.0-18-amd64         | 4         | 2.82%   |
| 5.10.0-21-amd64        | 4         | 2.82%   |
| 5.10.0-11-686          | 4         | 2.82%   |
| 6.1.0-37-amd64         | 3         | 2.11%   |
| 6.1.0-21-amd64         | 3         | 2.11%   |
| 6.1.0-17-amd64         | 3         | 2.11%   |
| 6.1.0-13-amd64         | 3         | 2.11%   |
| 5.10.0-9-amd64         | 3         | 2.11%   |
| 5.10.0-8-amd64         | 3         | 2.11%   |
| 5.10.0-6-amd64         | 3         | 2.11%   |
| 4.19.0-8-amd64         | 3         | 2.11%   |
| 4.19.0-12-amd64        | 3         | 2.11%   |
| 6.7.12-amd64           | 2         | 1.41%   |
| 6.5.0-5-amd64          | 2         | 1.41%   |
| 6.4.0-2-amd64          | 2         | 1.41%   |
| 6.3.0-1-amd64          | 2         | 1.41%   |
| 6.12.48+deb13-amd64    | 2         | 1.41%   |
| 6.11.10-amd64          | 2         | 1.41%   |
| 6.1.0-27-amd64         | 2         | 1.41%   |
| 6.1.0-26-amd64         | 2         | 1.41%   |
| 6.1.0-23-amd64         | 2         | 1.41%   |
| 6.1.0-12-amd64         | 2         | 1.41%   |
| 5.18.0-4-amd64         | 2         | 1.41%   |
| 5.18.0-2-amd64         | 2         | 1.41%   |
| 5.17.0-1-amd64         | 2         | 1.41%   |
| 5.10.0-3-amd64         | 2         | 1.41%   |
| 5.10.0-23-amd64        | 2         | 1.41%   |
| 5.10.0-14-amd64        | 2         | 1.41%   |
| 4.19.0-13-686          | 2         | 1.41%   |
| 4.19.0-10-686          | 2         | 1.41%   |
| 6.6.68-x64v3-xanmod1   | 1         | 0.7%    |
| 6.6.15-amd64           | 1         | 0.7%    |
| 6.6.13-amd64           | 1         | 0.7%    |
| 6.5.9-x64v3-xanmod1    | 1         | 0.7%    |
| 6.4.4-sparky8-amd64    | 1         | 0.7%    |
| 6.4.12-x64v3-xanmod1   | 1         | 0.7%    |
| 6.4.0-3-amd64          | 1         | 0.7%    |
| 6.4.0-1-amd64          | 1         | 0.7%    |
| 6.3.3-1-liquorix-amd64 | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 37        | 27.61%  |
| 5.10.0  | 32        | 23.88%  |
| 4.19.0  | 10        | 7.46%   |
| 5.18.0  | 4         | 2.99%   |
| 6.4.0   | 3         | 2.24%   |
| 6.7.12  | 2         | 1.49%   |
| 6.5.0   | 2         | 1.49%   |
| 6.3.0   | 2         | 1.49%   |
| 6.12.48 | 2         | 1.49%   |
| 6.11.10 | 2         | 1.49%   |
| 5.17.0  | 2         | 1.49%   |
| 6.6.68  | 1         | 0.75%   |
| 6.6.15  | 1         | 0.75%   |
| 6.6.13  | 1         | 0.75%   |
| 6.5.9   | 1         | 0.75%   |
| 6.4.4   | 1         | 0.75%   |
| 6.4.12  | 1         | 0.75%   |
| 6.3.3   | 1         | 0.75%   |
| 6.2.0   | 1         | 0.75%   |
| 6.17.13 | 1         | 0.75%   |
| 6.16.12 | 1         | 0.75%   |
| 6.15.1  | 1         | 0.75%   |
| 6.13.5  | 1         | 0.75%   |
| 6.12.57 | 1         | 0.75%   |
| 6.12.30 | 1         | 0.75%   |
| 6.12.17 | 1         | 0.75%   |
| 6.12.1  | 1         | 0.75%   |
| 6.11.6  | 1         | 0.75%   |
| 6.11.3  | 1         | 0.75%   |
| 6.0.11  | 1         | 0.75%   |
| 6.0.0   | 1         | 0.75%   |
| 5.9.13  | 1         | 0.75%   |
| 5.9.0   | 1         | 0.75%   |
| 5.8.13  | 1         | 0.75%   |
| 5.8.0   | 1         | 0.75%   |
| 5.7.2   | 1         | 0.75%   |
| 5.6.0   | 1         | 0.75%   |
| 5.5.0   | 1         | 0.75%   |
| 5.4.7   | 1         | 0.75%   |
| 5.2.0   | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 37        | 27.82%  |
| 5.10    | 33        | 24.81%  |
| 4.19    | 10        | 7.52%   |
| 6.12    | 6         | 4.51%   |
| 6.4     | 5         | 3.76%   |
| 5.18    | 5         | 3.76%   |
| 6.11    | 4         | 3.01%   |
| 6.6     | 3         | 2.26%   |
| 6.5     | 3         | 2.26%   |
| 6.3     | 3         | 2.26%   |
| 5.17    | 3         | 2.26%   |
| 6.7     | 2         | 1.5%    |
| 5.9     | 2         | 1.5%    |
| 5.8     | 2         | 1.5%    |
| 5.16    | 2         | 1.5%    |
| 6.2     | 1         | 0.75%   |
| 6.17    | 1         | 0.75%   |
| 6.16    | 1         | 0.75%   |
| 6.15    | 1         | 0.75%   |
| 6.13    | 1         | 0.75%   |
| 6.0     | 1         | 0.75%   |
| 5.7     | 1         | 0.75%   |
| 5.6     | 1         | 0.75%   |
| 5.5     | 1         | 0.75%   |
| 5.4     | 1         | 0.75%   |
| 5.2     | 1         | 0.75%   |
| 5.15    | 1         | 0.75%   |
| 5.14    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 119       | 94.44%  |
| i686   | 7         | 5.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 46        | 35.94%  |
| LXQt             | 24        | 18.75%  |
| X-Cinnamon       | 14        | 10.94%  |
| KDE5             | 12        | 9.38%   |
| Unknown          | 9         | 7.03%   |
| MATE             | 4         | 3.13%   |
| openbox          | 3         | 2.34%   |
| KDE6             | 3         | 2.34%   |
| lightdm-xsession | 2         | 1.56%   |
| GNOME            | 2         | 1.56%   |
| Budgie           | 2         | 1.56%   |
| LXDE             | 1         | 0.78%   |
| KDE              | 1         | 0.78%   |
| ICEWM            | 1         | 0.78%   |
| GNOME Flashback  | 1         | 0.78%   |
| GNOME Classic    | 1         | 0.78%   |
| Draco            | 1         | 0.78%   |
| Cinnamon         | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 119       | 92.97%  |
| Tty     | 7         | 5.47%   |
| Wayland | 2         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 37.8%   |
| LightDM | 39        | 30.71%  |
| SDDM    | 24        | 18.9%   |
| TDM     | 13        | 10.24%  |
| GDM     | 2         | 1.57%   |
| XDM     | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 48        | 38.1%   |
| pl_PL   | 10        | 7.94%   |
| es_ES   | 8         | 6.35%   |
| en_GB   | 8         | 6.35%   |
| de_DE   | 8         | 6.35%   |
| pt_BR   | 7         | 5.56%   |
| fr_FR   | 5         | 3.97%   |
| it_IT   | 4         | 3.17%   |
| ru_RU   | 3         | 2.38%   |
| es_MX   | 3         | 2.38%   |
| en_CA   | 2         | 1.59%   |
| Unknown | 2         | 1.59%   |
| sv_SE   | 1         | 0.79%   |
| pt_PT   | 1         | 0.79%   |
| lt_LT   | 1         | 0.79%   |
| ja_JP   | 1         | 0.79%   |
| gl_ES   | 1         | 0.79%   |
| fr_BE   | 1         | 0.79%   |
| es_US   | 1         | 0.79%   |
| es_CO   | 1         | 0.79%   |
| es_CL   | 1         | 0.79%   |
| es_AR   | 1         | 0.79%   |
| en_ZA   | 1         | 0.79%   |
| en_PH   | 1         | 0.79%   |
| en_IN   | 1         | 0.79%   |
| en_DK   | 1         | 0.79%   |
| en_AU   | 1         | 0.79%   |
| de_CH   | 1         | 0.79%   |
| cs_CZ   | 1         | 0.79%   |
| ar_EG   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 83        | 65.35%  |
| EFI  | 44        | 34.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 110       | 87.3%   |
| Btrfs   | 8         | 6.35%   |
| Overlay | 5         | 3.97%   |
| Zfs     | 1         | 0.79%   |
| Tmpfs   | 1         | 0.79%   |
| Ext2    | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 37.8%   |
| GPT     | 47        | 37.01%  |
| MBR     | 32        | 25.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 84.13%  |
| Yes       | 20        | 15.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 71.65%  |
| Yes       | 36        | 28.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 30        | 23.81%  |
| ASUSTek Computer    | 14        | 11.11%  |
| Dell                | 13        | 10.32%  |
| Lenovo              | 11        | 8.73%   |
| Acer                | 9         | 7.14%   |
| Gigabyte Technology | 8         | 6.35%   |
| Intel               | 6         | 4.76%   |
| Google              | 6         | 4.76%   |
| MSI                 | 5         | 3.97%   |
| Samsung Electronics | 3         | 2.38%   |
| Medion              | 3         | 2.38%   |
| Apple               | 3         | 2.38%   |
| Toshiba             | 2         | 1.59%   |
| Sony                | 1         | 0.79%   |
| Shuttle             | 1         | 0.79%   |
| Positivo            | 1         | 0.79%   |
| Panasonic           | 1         | 0.79%   |
| Microsoft           | 1         | 0.79%   |
| Mediacom            | 1         | 0.79%   |
| HUAWEI              | 1         | 0.79%   |
| Fujitsu Siemens     | 1         | 0.79%   |
| Foxconn             | 1         | 0.79%   |
| eMachines           | 1         | 0.79%   |
| Beelink             | 1         | 0.79%   |
| ASRock              | 1         | 0.79%   |
| Unknown             | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7B86                           | 2         | 1.59%   |
| Dell OptiPlex 7010                    | 2         | 1.59%   |
| Toshiba Satellite P755                | 1         | 0.79%   |
| Toshiba Satellite L505D               | 1         | 0.79%   |
| Sony SVE1513Q1ESI                     | 1         | 0.79%   |
| Shuttle NC03U                         | 1         | 0.79%   |
| Samsung NC10                          | 1         | 0.79%   |
| Samsung N150P/N210P/N220P             | 1         | 0.79%   |
| Samsung N150/N210/N220                | 1         | 0.79%   |
| Positivo CHT14B                       | 1         | 0.79%   |
| Panasonic CFSZ5-2                     | 1         | 0.79%   |
| MSI MS-7C09                           | 1         | 0.79%   |
| MSI MS-7721                           | 1         | 0.79%   |
| MSI Alpha 15 A3DDK                    | 1         | 0.79%   |
| Microsoft Surface Pro 4               | 1         | 0.79%   |
| Medion P961x                          | 1         | 0.79%   |
| Medion MS-7800                        | 1         | 0.79%   |
| Medion E15415                         | 1         | 0.79%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 0.79%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 0.79%   |
| Lenovo ThinkPad T60 2007FUG           | 1         | 0.79%   |
| Lenovo ThinkPad T430 2349FC4          | 1         | 0.79%   |
| Lenovo ThinkPad T14 Gen 2i 20W1S29800 | 1         | 0.79%   |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 0.79%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S20R00 | 1         | 0.79%   |
| Lenovo ThinkCentre M90s 11D2CTO1WW    | 1         | 0.79%   |
| Lenovo IdeaPad S340-15IIL 81VW        | 1         | 0.79%   |
| Lenovo IdeaPad S206 20154             | 1         | 0.79%   |
| Lenovo IdeaPad 3 15IML05 81WB         | 1         | 0.79%   |
| Lenovo G50-30 80G0                    | 1         | 0.79%   |
| Intel NUC8i5BEH                       | 1         | 0.79%   |
| Intel NUC5CPYB H61145-408             | 1         | 0.79%   |
| Intel H61                             | 1         | 0.79%   |
| Intel H55                             | 1         | 0.79%   |
| Intel DG43RK AAE78175-402             | 1         | 0.79%   |
| Intel DG41TY AAE47335-300             | 1         | 0.79%   |
| HUAWEI HVY-WXX9                       | 1         | 0.79%   |
| HP Z440 Workstation                   | 1         | 0.79%   |
| HP Z420 Workstation                   | 1         | 0.79%   |
| HP t5740                              | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 9         | 7.14%   |
| Lenovo ThinkPad    | 6         | 4.76%   |
| HP Pavilion        | 6         | 4.76%   |
| HP EliteDesk       | 6         | 4.76%   |
| Dell OptiPlex      | 6         | 4.76%   |
| HP Compaq          | 5         | 3.97%   |
| Dell Inspiron      | 5         | 3.97%   |
| HP EliteBook       | 4         | 3.17%   |
| Lenovo IdeaPad     | 3         | 2.38%   |
| Toshiba Satellite  | 2         | 1.59%   |
| MSI MS-7B86        | 2         | 1.59%   |
| HP Laptop          | 2         | 1.59%   |
| Sony SVE1513Q1ESI  | 1         | 0.79%   |
| Shuttle NC03U      | 1         | 0.79%   |
| Samsung NC10       | 1         | 0.79%   |
| Samsung N150P      | 1         | 0.79%   |
| Samsung N150       | 1         | 0.79%   |
| Positivo CHT14B    | 1         | 0.79%   |
| Panasonic CFSZ5-2  | 1         | 0.79%   |
| MSI MS-7C09        | 1         | 0.79%   |
| MSI MS-7721        | 1         | 0.79%   |
| MSI Alpha          | 1         | 0.79%   |
| Microsoft Surface  | 1         | 0.79%   |
| Medion P961x       | 1         | 0.79%   |
| Medion MS-7800     | 1         | 0.79%   |
| Medion E15415      | 1         | 0.79%   |
| Mediacom SmartBook | 1         | 0.79%   |
| Lenovo ThinkCentre | 1         | 0.79%   |
| Lenovo G50-30      | 1         | 0.79%   |
| Intel NUC8i5BEH    | 1         | 0.79%   |
| Intel NUC5CPYB     | 1         | 0.79%   |
| Intel H61          | 1         | 0.79%   |
| Intel H55          | 1         | 0.79%   |
| Intel DG43RK       | 1         | 0.79%   |
| Intel DG41TY       | 1         | 0.79%   |
| HUAWEI HVY-WXX9    | 1         | 0.79%   |
| HP Z440            | 1         | 0.79%   |
| HP Z420            | 1         | 0.79%   |
| HP t5740           | 1         | 0.79%   |
| HP Stream          | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 16        | 12.7%   |
| 2009 | 12        | 9.52%   |
| 2017 | 11        | 8.73%   |
| 2010 | 11        | 8.73%   |
| 2011 | 10        | 7.94%   |
| 2021 | 9         | 7.14%   |
| 2014 | 8         | 6.35%   |
| 2019 | 6         | 4.76%   |
| 2018 | 6         | 4.76%   |
| 2016 | 5         | 3.97%   |
| 2015 | 5         | 3.97%   |
| 2013 | 5         | 3.97%   |
| 2008 | 5         | 3.97%   |
| 2007 | 5         | 3.97%   |
| 2020 | 4         | 3.17%   |
| 2024 | 3         | 2.38%   |
| 2022 | 2         | 1.59%   |
| 2006 | 2         | 1.59%   |
| 2023 | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 66        | 52.38%  |
| Desktop     | 53        | 42.06%  |
| Mini pc     | 3         | 2.38%   |
| Tablet      | 1         | 0.79%   |
| Convertible | 1         | 0.79%   |
| All in one  | 1         | 0.79%   |
| Server      | 1         | 0.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 123       | 97.62%  |
| Enabled  | 3         | 2.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 120       | 95.24%  |
| Yes  | 6         | 4.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 35        | 27.56%  |
| 4.01-8.0    | 18        | 14.17%  |
| 16.01-24.0  | 17        | 13.39%  |
| 8.01-16.0   | 16        | 12.6%   |
| 32.01-64.0  | 13        | 10.24%  |
| 1.01-2.0    | 12        | 9.45%   |
| 24.01-32.0  | 7         | 5.51%   |
| 2.01-3.0    | 7         | 5.51%   |
| 64.01-256.0 | 1         | 0.79%   |
| 0.51-1.0    | 1         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 49        | 37.12%  |
| 2.01-3.0   | 32        | 24.24%  |
| 0.51-1.0   | 16        | 12.12%  |
| 4.01-8.0   | 11        | 8.33%   |
| 3.01-4.0   | 11        | 8.33%   |
| 8.01-16.0  | 6         | 4.55%   |
| 16.01-24.0 | 4         | 3.03%   |
| 0.01-0.5   | 3         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 60.47%  |
| 2      | 30        | 23.26%  |
| 4      | 6         | 4.65%   |
| 3      | 6         | 4.65%   |
| 6      | 4         | 3.1%    |
| 5      | 3         | 2.33%   |
| 7      | 2         | 1.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 59.06%  |
| Yes       | 52        | 40.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 84.13%  |
| No        | 20        | 15.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 72.22%  |
| No        | 35        | 27.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 51.59%  |
| No        | 61        | 48.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 29        | 23.02%  |
| Germany      | 11        | 8.73%   |
| Poland       | 10        | 7.94%   |
| Spain        | 8         | 6.35%   |
| UK           | 7         | 5.56%   |
| Italy        | 7         | 5.56%   |
| France       | 7         | 5.56%   |
| Brazil       | 7         | 5.56%   |
| Canada       | 4         | 3.17%   |
| Sweden       | 3         | 2.38%   |
| Mexico       | 3         | 2.38%   |
| Indonesia    | 3         | 2.38%   |
| Russia       | 2         | 1.59%   |
| Chile        | 2         | 1.59%   |
| Belgium      | 2         | 1.59%   |
| Argentina    | 2         | 1.59%   |
| Venezuela    | 1         | 0.79%   |
| Uzbekistan   | 1         | 0.79%   |
| UAE          | 1         | 0.79%   |
| Switzerland  | 1         | 0.79%   |
| South Africa | 1         | 0.79%   |
| Portugal     | 1         | 0.79%   |
| Philippines  | 1         | 0.79%   |
| New Zealand  | 1         | 0.79%   |
| Netherlands  | 1         | 0.79%   |
| Malaysia     | 1         | 0.79%   |
| Lithuania    | 1         | 0.79%   |
| Lebanon      | 1         | 0.79%   |
| Japan        | 1         | 0.79%   |
| India        | 1         | 0.79%   |
| Hungary      | 1         | 0.79%   |
| Czechia      | 1         | 0.79%   |
| Colombia     | 1         | 0.79%   |
| Bulgaria     | 1         | 0.79%   |
| Australia    | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Echelon         | 11        | 8.4%    |
| Vigo            | 2         | 1.53%   |
| Rio de Janeiro  | 2         | 1.53%   |
| Montreuil       | 2         | 1.53%   |
| Montreal        | 2         | 1.53%   |
| Leipzig         | 2         | 1.53%   |
| Brussels        | 2         | 1.53%   |
| Barcelona       | 2         | 1.53%   |
| Zephyrhills     | 1         | 0.76%   |
| Wrzesnia        | 1         | 0.76%   |
| Woking          | 1         | 0.76%   |
| West Palm Beach | 1         | 0.76%   |
| Wenatchee       | 1         | 0.76%   |
| Warsaw          | 1         | 0.76%   |
| Vilnius         | 1         | 0.76%   |
| Uppsala         | 1         | 0.76%   |
| Tucson          | 1         | 0.76%   |
| Trieste         | 1         | 0.76%   |
| Trelaze         | 1         | 0.76%   |
| Tauranga        | 1         | 0.76%   |
| Takahama        | 1         | 0.76%   |
| Surabaya        | 1         | 0.76%   |
| Spokane         | 1         | 0.76%   |
| Sofia           | 1         | 0.76%   |
| Sin el Fil      | 1         | 0.76%   |
| Silver Spring   | 1         | 0.76%   |
| Santo André    | 1         | 0.76%   |
| Santiago        | 1         | 0.76%   |
| San Cristóbal  | 1         | 0.76%   |
| San Antonio     | 1         | 0.76%   |
| Salina Cruz     | 1         | 0.76%   |
| Sainte-Julie    | 1         | 0.76%   |
| Rudnik          | 1         | 0.76%   |
| Rudersberg      | 1         | 0.76%   |
| Rosario         | 1         | 0.76%   |
| Rio Claro       | 1         | 0.76%   |
| Rheinbach       | 1         | 0.76%   |
| Quezon City     | 1         | 0.76%   |
| Pujaudran       | 1         | 0.76%   |
| Puente Alto     | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 28        | 32     | 13.93%  |
| Seagate                      | 27        | 36     | 13.43%  |
| Samsung Electronics          | 25        | 40     | 12.44%  |
| Hitachi                      | 12        | 15     | 5.97%   |
| Unknown                      | 11        | 11     | 5.47%   |
| Toshiba                      | 9         | 10     | 4.48%   |
| External                     | 8         | 15     | 3.98%   |
| TO Exter                     | 7         | 13     | 3.48%   |
| Crucial                      | 7         | 7      | 3.48%   |
| Sandisk                      | 6         | 8      | 2.99%   |
| Kingston                     | 6         | 7      | 2.99%   |
| JMicron Technology           | 5         | 8      | 2.49%   |
| HGST                         | 4         | 4      | 1.99%   |
| SPCC                         | 3         | 4      | 1.49%   |
| SK hynix                     | 3         | 3      | 1.49%   |
| Silicon Motion               | 3         | 4      | 1.49%   |
| Patriot                      | 3         | 4      | 1.49%   |
| Intel                        | 3         | 3      | 1.49%   |
| GOODRAM                      | 3         | 6      | 1.49%   |
| ASMedia                      | 3         | 3      | 1.49%   |
| A-DATA Technology            | 3         | 5      | 1.49%   |
| Team                         | 2         | 2      | 1%      |
| Phison Electronics           | 2         | 2      | 1%      |
| Unknown                      | 2         | 2      | 1%      |
| XPG                          | 1         | 1      | 0.5%    |
| Shenzhen Longsys Electronics | 1         | 2      | 0.5%    |
| PNY                          | 1         | 1      | 0.5%    |
| ORICO                        | 1         | 1      | 0.5%    |
| OCZ                          | 1         | 1      | 0.5%    |
| Netac                        | 1         | 1      | 0.5%    |
| Micron/Crucial Technology    | 1         | 1      | 0.5%    |
| Micron Technology            | 1         | 1      | 0.5%    |
| Kingston Technology Company  | 1         | 1      | 0.5%    |
| KingDian                     | 1         | 1      | 0.5%    |
| Intenso                      | 1         | 1      | 0.5%    |
| Gigabyte Technology          | 1         | 1      | 0.5%    |
| Fujitsu                      | 1         | 2      | 0.5%    |
| China                        | 1         | 1      | 0.5%    |
| ASUS-JM                      | 1         | 1      | 0.5%    |
| Apple                        | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| TO Exter nal USB 3.0 250GB                            | 7         | 3.29%   |
| JMicron Generic 320GB                                 | 5         | 2.35%   |
| External USB3.0 250GB                                 | 5         | 2.35%   |
| External USB 3.0 320GB                                | 4         | 1.88%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 3         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 3         | 1.41%   |
| WDC WD3200AAKS-75L9A0 320GB                           | 2         | 0.94%   |
| WDC WD1600BEVT-22ZCT0 160GB                           | 2         | 0.94%   |
| Unknown MMC Card  32GB                                | 2         | 0.94%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.94%   |
| Toshiba MQ01ACF032 320GB                              | 2         | 0.94%   |
| Toshiba DT01ACA100 1TB                                | 2         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2         | 0.94%   |
| Seagate ST500LT012-1DG142 500GB                       | 2         | 0.94%   |
| Seagate ST500DM002-1BD142 500GB                       | 2         | 0.94%   |
| Seagate Backup+ Hub BK 6TB                            | 2         | 0.94%   |
| Samsung SSD 850 EVO 250GB                             | 2         | 0.94%   |
| Samsung HD161GJ 160GB                                 | 2         | 0.94%   |
| Patriot P210 256GB SSD                                | 2         | 0.94%   |
| Kingston SA400S37120G 120GB SSD                       | 2         | 0.94%   |
| Hitachi HTS545025B9A300 250GB                         | 2         | 0.94%   |
| Hitachi HDS721050CLA 500GB                            | 2         | 0.94%   |
| Crucial CT500MX500SSD1 500GB                          | 2         | 0.94%   |
| Unknown                                               | 2         | 0.94%   |
| XPG GAMMIX S11 Pro 1TB                                | 1         | 0.47%   |
| WDC WD800JD-08MSA1 80GB                               | 1         | 0.47%   |
| WDC WD7500BPVX-22JC3T0 752GB                          | 1         | 0.47%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 1         | 0.47%   |
| WDC WD5000BEVT-22ZAT0 500GB                           | 1         | 0.47%   |
| WDC WD5000AVVS-63ZWB0 500GB                           | 1         | 0.47%   |
| WDC WD5000AAKS-75V0A0 500GB                           | 1         | 0.47%   |
| WDC WD50 00LPLX-08ZNTT0 500GB                         | 1         | 0.47%   |
| WDC WD50 00LPCX-21VHAT0 500GB                         | 1         | 0.47%   |
| WDC WD3200BPVT-75ZEST0 320GB                          | 1         | 0.47%   |
| WDC WD2500AAKX-07U6AA0 250GB                          | 1         | 0.47%   |
| WDC WD2500AAJS-00L7A0 250GB                           | 1         | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 1         | 0.47%   |
| WDC WD1600BEVS-00VAT0 160GB                           | 1         | 0.47%   |
| WDC WD1600AAJS-22L7A0 160GB                           | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 34     | 25.47%  |
| WDC                 | 24        | 28     | 22.64%  |
| Hitachi             | 12        | 15     | 11.32%  |
| Toshiba             | 9         | 10     | 8.49%   |
| External            | 8         | 15     | 7.55%   |
| TO Exter            | 7         | 13     | 6.6%    |
| Samsung Electronics | 6         | 13     | 5.66%   |
| JMicron Technology  | 5         | 8      | 4.72%   |
| HGST                | 4         | 4      | 3.77%   |
| ASMedia             | 2         | 2      | 1.89%   |
| Fujitsu             | 1         | 2      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 16     | 19.61%  |
| Crucial             | 6         | 6      | 11.76%  |
| Kingston            | 5         | 6      | 9.8%    |
| Patriot             | 3         | 4      | 5.88%   |
| Intel               | 3         | 3      | 5.88%   |
| GOODRAM             | 3         | 6      | 5.88%   |
| Team                | 2         | 2      | 3.92%   |
| SPCC                | 2         | 3      | 3.92%   |
| SanDisk             | 2         | 2      | 3.92%   |
| A-DATA Technology   | 2         | 4      | 3.92%   |
| WDC                 | 1         | 1      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| ORICO               | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| KingDian            | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| Gigabyte Technology | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| ASUS-JM             | 1         | 1      | 1.96%   |
| ASMedia             | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 76        | 145    | 46.34%  |
| SSD     | 45        | 65     | 27.44%  |
| NVMe    | 28        | 37     | 17.07%  |
| MMC     | 13        | 13     | 7.93%   |
| Unknown | 2         | 2      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 157    | 62.26%  |
| NVMe | 28        | 37     | 17.61%  |
| SAS  | 19        | 55     | 11.95%  |
| MMC  | 13        | 13     | 8.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 152    | 67.21%  |
| 0.51-1.0   | 30        | 45     | 24.59%  |
| 1.01-2.0   | 7         | 8      | 5.74%   |
| 4.01-10.0  | 2         | 4      | 1.64%   |
| 2.01-3.0   | 1         | 1      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 27.34%  |
| 501-1000       | 21        | 16.41%  |
| 251-500        | 19        | 14.84%  |
| More than 3000 | 11        | 8.59%   |
| 1-20           | 11        | 8.59%   |
| 21-50          | 9         | 7.03%   |
| 2001-3000      | 7         | 5.47%   |
| 1001-2000      | 7         | 5.47%   |
| 51-100         | 6         | 4.69%   |
| Unknown        | 2         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 50        | 38.46%  |
| 21-50          | 23        | 17.69%  |
| 501-1000       | 13        | 10%     |
| 251-500        | 11        | 8.46%   |
| 51-100         | 9         | 6.92%   |
| 101-250        | 7         | 5.38%   |
| 1001-2000      | 7         | 5.38%   |
| 2001-3000      | 5         | 3.85%   |
| More than 3000 | 3         | 2.31%   |
| Unknown        | 2         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 5.26%   |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 5.26%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 5.26%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 5.26%   |
| WDC WD10SPCX-16KHST0 1TB                            | 1         | 1      | 5.26%   |
| WDC WD10EFRX-68PJCN0 1TB                            | 1         | 2      | 5.26%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 5.26%   |
| Toshiba DT01ACA100 1TB                              | 1         | 2      | 5.26%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 5.26%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1         | 1      | 5.26%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 5.26%   |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 5.26%   |
| ASMedia ASMT1153e 64GB                              | 1         | 1      | 5.26%   |
| Unknown                                             | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 36.84%  |
| Seagate             | 6         | 6      | 31.58%  |
| Toshiba             | 1         | 2      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| ASMedia             | 1         | 1      | 5.26%   |
| Unknown             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 43.75%  |
| Seagate             | 6         | 6      | 37.5%   |
| Toshiba             | 1         | 2      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| ASMedia             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 84.21%  |
| SSD  | 3         | 3      | 15.79%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 64        | 157    | 45.39%  |
| Works    | 58        | 84     | 41.13%  |
| Malfunc  | 19        | 21     | 13.48%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 57.93%  |
| AMD                             | 19        | 13.1%   |
| Samsung Electronics             | 10        | 6.9%    |
| Silicon Motion                  | 4         | 2.76%   |
| SanDisk                         | 4         | 2.76%   |
| Nvidia                          | 4         | 2.76%   |
| SK hynix                        | 2         | 1.38%   |
| Phison Electronics              | 2         | 1.38%   |
| Micron/Crucial Technology       | 2         | 1.38%   |
| LSI Logic / Symbios Logic       | 2         | 1.38%   |
| Kingston Technology Company     | 2         | 1.38%   |
| ASMedia Technology              | 2         | 1.38%   |
| VIA Technologies                | 1         | 0.69%   |
| Shenzhen Techwinsemi Technology | 1         | 0.69%   |
| Shenzhen Longsys Electronics    | 1         | 0.69%   |
| Seagate Technology              | 1         | 0.69%   |
| Promise Technology              | 1         | 0.69%   |
| Marvell Technology Group        | 1         | 0.69%   |
| JMicron Technology              | 1         | 0.69%   |
| ADATA Technology                | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 14        | 8.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 4.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 6         | 3.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5         | 2.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 5         | 2.92%   |
| Intel Comet Lake SATA AHCI Controller                                         | 5         | 2.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 5         | 2.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 4         | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 4         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 4         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 4         | 2.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 4         | 2.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 3         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 3         | 1.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 3         | 1.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 3         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3         | 1.75%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 1.17%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 2         | 1.17%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 2         | 1.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 1.17%   |
| Nvidia MCP61 SATA Controller                                                  | 2         | 1.17%   |
| Nvidia MCP61 IDE                                                              | 2         | 1.17%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 2         | 1.17%   |
| Intel SATA Controller [RAID Mode]                                             | 2         | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 2         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 2         | 1.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 2         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 2         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 1.17%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 2         | 1.17%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 2         | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 2         | 1.17%   |
| AMD 400 Series Chipset SATA Controller                                        | 2         | 1.17%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 0.58%   |
| VIA VT8237A Integrated SATA RAID Controller                                   | 1         | 0.58%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 87        | 57.62%  |
| IDE  | 29        | 19.21%  |
| NVMe | 27        | 17.88%  |
| RAID | 6         | 3.97%   |
| SAS  | 1         | 0.66%   |
| SCSI | 1         | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 100       | 79.37%  |
| AMD    | 26        | 20.63%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 3.17%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 2.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.59%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 2         | 1.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 1.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.59%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.59%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 2         | 1.59%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 1.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 1.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.59%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.59%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 1.59%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.59%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.79%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 0.79%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 0.79%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 0.79%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.79%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.79%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.79%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.79%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.79%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.79%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.79%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.79%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.79%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 0.79%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 0.79%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.79%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.79%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 0.79%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 25.4%   |
| Intel Celeron           | 15        | 11.9%   |
| Intel Core i7           | 10        | 7.94%   |
| Intel Atom              | 10        | 7.94%   |
| Intel Core 2 Duo        | 8         | 6.35%   |
| Intel Core i3           | 6         | 4.76%   |
| Other                   | 3         | 2.38%   |
| Intel Xeon              | 3         | 2.38%   |
| Intel Pentium Dual-Core | 3         | 2.38%   |
| Intel Pentium           | 3         | 2.38%   |
| Intel Core 2            | 3         | 2.38%   |
| AMD Ryzen 7             | 3         | 2.38%   |
| AMD A8                  | 3         | 2.38%   |
| Intel Core 2 Quad       | 2         | 1.59%   |
| AMD Ryzen 5             | 2         | 1.59%   |
| AMD Ryzen 3             | 2         | 1.59%   |
| AMD A6                  | 2         | 1.59%   |
| AMD A4                  | 2         | 1.59%   |
| Intel Pentium Gold      | 1         | 0.79%   |
| Intel Genuine           | 1         | 0.79%   |
| AMD Turion 64 X2 Mobile | 1         | 0.79%   |
| AMD Sempron             | 1         | 0.79%   |
| AMD Ryzen 9             | 1         | 0.79%   |
| AMD Ryzen 5 PRO         | 1         | 0.79%   |
| AMD PRO A8              | 1         | 0.79%   |
| AMD PRO A10             | 1         | 0.79%   |
| AMD Phenom II X6        | 1         | 0.79%   |
| AMD Phenom II X4        | 1         | 0.79%   |
| AMD C-50                | 1         | 0.79%   |
| AMD Athlon X2           | 1         | 0.79%   |
| AMD Athlon II X3        | 1         | 0.79%   |
| AMD Athlon II X2        | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 46.03%  |
| 4      | 48        | 38.1%   |
| 1      | 9         | 7.14%   |
| 8      | 5         | 3.97%   |
| 6      | 4         | 3.17%   |
| 12     | 1         | 0.79%   |
| 3      | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 126       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 53.17%  |
| 2      | 59        | 46.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 121       | 96.03%  |
| 32-bit         | 5         | 3.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 40.94%  |
| 0x406c4    | 5         | 3.94%   |
| 0x306a9    | 5         | 3.94%   |
| 0x1067a    | 5         | 3.94%   |
| 0x206a7    | 4         | 3.15%   |
| 0x6f2      | 3         | 2.36%   |
| 0x30678    | 3         | 2.36%   |
| 0x20655    | 3         | 2.36%   |
| 0x20652    | 3         | 2.36%   |
| 0x0600611a | 3         | 2.36%   |
| 0x806ec    | 2         | 1.57%   |
| 0x506e3    | 2         | 1.57%   |
| 0x406c3    | 2         | 1.57%   |
| 0x306c3    | 2         | 1.57%   |
| 0x106ca    | 2         | 1.57%   |
| 0x106c2    | 2         | 1.57%   |
| 0x10676    | 2         | 1.57%   |
| 0x08108109 | 2         | 1.57%   |
| 0xa0653    | 1         | 0.79%   |
| 0x806ea    | 1         | 0.79%   |
| 0x806e9    | 1         | 0.79%   |
| 0x706a8    | 1         | 0.79%   |
| 0x706a1    | 1         | 0.79%   |
| 0x6fd      | 1         | 0.79%   |
| 0x6fb      | 1         | 0.79%   |
| 0x406f1    | 1         | 0.79%   |
| 0x40651    | 1         | 0.79%   |
| 0x206d7    | 1         | 0.79%   |
| 0x106e5    | 1         | 0.79%   |
| 0x0a50000d | 1         | 0.79%   |
| 0x0a201016 | 1         | 0.79%   |
| 0x08701021 | 1         | 0.79%   |
| 0x08608103 | 1         | 0.79%   |
| 0x08600106 | 1         | 0.79%   |
| 0x08001138 | 1         | 0.79%   |
| 0x0700010f | 1         | 0.79%   |
| 0x06006705 | 1         | 0.79%   |
| 0x06001119 | 1         | 0.79%   |
| 0x05000029 | 1         | 0.79%   |
| 0x03000027 | 1         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 14        | 11.11%  |
| IvyBridge       | 12        | 9.52%   |
| Silvermont      | 11        | 8.73%   |
| SandyBridge     | 10        | 7.94%   |
| Penryn          | 10        | 7.94%   |
| Core            | 7         | 5.56%   |
| Westmere        | 6         | 4.76%   |
| Skylake         | 6         | 4.76%   |
| Bonnell         | 6         | 4.76%   |
| K10             | 5         | 3.97%   |
| Haswell         | 4         | 3.17%   |
| Goldmont plus   | 4         | 3.17%   |
| Excavator       | 4         | 3.17%   |
| Piledriver      | 3         | 2.38%   |
| Zen+            | 2         | 1.59%   |
| Zen 3           | 2         | 1.59%   |
| Zen 2           | 2         | 1.59%   |
| Zen             | 2         | 1.59%   |
| TigerLake       | 2         | 1.59%   |
| Nehalem         | 2         | 1.59%   |
| CometLake       | 2         | 1.59%   |
| Unknown         | 2         | 1.59%   |
| P6              | 1         | 0.79%   |
| K8 Hammer       | 1         | 0.79%   |
| K8 & K10 hybrid | 1         | 0.79%   |
| K10 Llano       | 1         | 0.79%   |
| Jaguar          | 1         | 0.79%   |
| IceLake         | 1         | 0.79%   |
| Broadwell       | 1         | 0.79%   |
| Bobcat          | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 79        | 59.85%  |
| AMD                        | 30        | 22.73%  |
| Nvidia                     | 21        | 15.91%  |
| VIA Technologies           | 1         | 0.76%   |
| Matrox Electronics Systems | 1         | 0.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 3.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 3.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.8%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 4         | 2.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 2.8%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 2.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.1%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 2.1%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 1.4%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.4%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.4%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2         | 1.4%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 2         | 1.4%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 1.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.4%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.4%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.4%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.7%    |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.7%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.7%    |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.7%    |
| Nvidia GM107GL [Quadro K1200]                                                            | 1         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.7%    |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 0.7%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.7%    |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 55.91%  |
| 1 x AMD        | 27        | 21.26%  |
| 1 x Nvidia     | 17        | 13.39%  |
| 2 x Intel      | 4         | 3.15%   |
| Intel + Nvidia | 3         | 2.36%   |
| 2 x AMD        | 2         | 1.57%   |
| 2 x Nvidia     | 1         | 0.79%   |
| 1 x VIA        | 1         | 0.79%   |
| 1 x Matrox     | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 92.86%  |
| Unknown     | 5         | 3.97%   |
| Proprietary | 4         | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 72.87%  |
| 0.01-0.5   | 16        | 12.4%   |
| 0.51-1.0   | 9         | 6.98%   |
| 1.01-2.0   | 5         | 3.88%   |
| 3.01-4.0   | 3         | 2.33%   |
| 7.01-8.0   | 2         | 1.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 13.6%   |
| LG Display              | 14        | 11.2%   |
| AU Optronics            | 13        | 10.4%   |
| Sceptre Tech            | 10        | 8%      |
| Chimei Innolux          | 10        | 8%      |
| Goldstar                | 7         | 5.6%    |
| BOE                     | 7         | 5.6%    |
| Dell                    | 6         | 4.8%    |
| Acer                    | 5         | 4%      |
| BenQ                    | 4         | 3.2%    |
| AOC                     | 4         | 3.2%    |
| Lenovo                  | 3         | 2.4%    |
| CPT                     | 3         | 2.4%    |
| Apple                   | 3         | 2.4%    |
| Medion                  | 2         | 1.6%    |
| Hewlett-Packard         | 2         | 1.6%    |
| Chi Mei Optoelectronics | 2         | 1.6%    |
| Unknown                 | 1         | 0.8%    |
| Toshiba                 | 1         | 0.8%    |
| Sony                    | 1         | 0.8%    |
| RTK                     | 1         | 0.8%    |
| Philips                 | 1         | 0.8%    |
| PANDA                   | 1         | 0.8%    |
| LG Philips              | 1         | 0.8%    |
| JCH                     | 1         | 0.8%    |
| Insignia                | 1         | 0.8%    |
| Hitachi                 | 1         | 0.8%    |
| HannStar                | 1         | 0.8%    |
| ASUSTek Computer        | 1         | 0.8%    |
| Ancor Communications    | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch        | 7         | 5.43%   |
| Sceptre Tech Sceptre H43 SPT1104 1920x1080 575x323mm 26.0-inch        | 3         | 2.33%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 2         | 1.55%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.78%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 0.78%   |
| Sony TV SNY2A03 1920x1080                                             | 1         | 0.78%   |
| Samsung Electronics T22C350 SAM0AB7 1920x1080 477x268mm 21.5-inch     | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM009D 1024x768 304x228mm 15.0-inch   | 1         | 0.78%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1         | 0.78%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1         | 0.78%   |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1         | 0.78%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch     | 1         | 0.78%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 0.78%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1         | 0.78%   |
| Samsung Electronics LS27C36x SAM7315 1920x1080 598x336mm 27.0-inch    | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 0.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.78%   |
| RTK CPL AIO PC RTK2482 1920x1080 509x286mm 23.0-inch                  | 1         | 0.78%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.78%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1         | 0.78%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                 | 1         | 0.78%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 0.78%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 37.3%   |
| 1366x768 (WXGA)    | 29        | 23.02%  |
| 3840x2160 (4K)     | 9         | 7.14%   |
| 1920x1200 (WUXGA)  | 5         | 3.97%   |
| 1600x900 (HD+)     | 5         | 3.97%   |
| 1680x1050 (WSXGA+) | 4         | 3.17%   |
| 1440x900 (WXGA+)   | 4         | 3.17%   |
| 1280x800 (WXGA)    | 4         | 3.17%   |
| 1024x600           | 4         | 3.17%   |
| 1280x1024 (SXGA)   | 3         | 2.38%   |
| 1920x540           | 2         | 1.59%   |
| 1024x768 (XGA)     | 2         | 1.59%   |
| 3840x1080          | 1         | 0.79%   |
| 2880x1920          | 1         | 0.79%   |
| 2560x1080          | 1         | 0.79%   |
| 2288x1287          | 1         | 0.79%   |
| 1400x1050          | 1         | 0.79%   |
| 1360x768           | 1         | 0.79%   |
| 1280x960           | 1         | 0.79%   |
| Unknown            | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 22.05%  |
| 13      | 13        | 10.24%  |
| 23      | 9         | 7.09%   |
| 17      | 9         | 7.09%   |
| 32      | 8         | 6.3%    |
| 14      | 8         | 6.3%    |
| 24      | 7         | 5.51%   |
| 21      | 6         | 4.72%   |
| 27      | 5         | 3.94%   |
| 20      | 4         | 3.15%   |
| 11      | 4         | 3.15%   |
| 10      | 4         | 3.15%   |
| 26      | 3         | 2.36%   |
| 72      | 2         | 1.57%   |
| 48      | 2         | 1.57%   |
| 19      | 2         | 1.57%   |
| 18      | 2         | 1.57%   |
| 16      | 2         | 1.57%   |
| 142     | 1         | 0.79%   |
| 74      | 1         | 0.79%   |
| 54      | 1         | 0.79%   |
| 39      | 1         | 0.79%   |
| 31      | 1         | 0.79%   |
| 28      | 1         | 0.79%   |
| 22      | 1         | 0.79%   |
| 12      | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 44        | 34.92%  |
| 501-600        | 23        | 18.25%  |
| 201-300        | 18        | 14.29%  |
| 401-500        | 14        | 11.11%  |
| 701-800        | 8         | 6.35%   |
| 351-400        | 7         | 5.56%   |
| 601-700        | 3         | 2.38%   |
| 1501-2000      | 3         | 2.38%   |
| 1001-1500      | 3         | 2.38%   |
| More than 2000 | 1         | 0.79%   |
| 801-900        | 1         | 0.79%   |
| Unknown        | 1         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 74.38%  |
| 16/10   | 18        | 14.88%  |
| 4/3     | 4         | 3.31%   |
| 5/4     | 3         | 2.48%   |
| 1.96    | 2         | 1.65%   |
| 3/2     | 1         | 0.83%   |
| 21/9    | 1         | 0.83%   |
| 1.00    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 22.83%  |
| 201-250        | 16        | 12.6%   |
| 81-90          | 14        | 11.02%  |
| 351-500        | 9         | 7.09%   |
| 151-200        | 9         | 7.09%   |
| 251-300        | 8         | 6.3%    |
| 71-80          | 6         | 4.72%   |
| 121-130        | 6         | 4.72%   |
| More than 1000 | 5         | 3.94%   |
| 301-350        | 5         | 3.94%   |
| 141-150        | 5         | 3.94%   |
| 51-60          | 4         | 3.15%   |
| 41-50          | 4         | 3.15%   |
| 501-1000       | 3         | 2.36%   |
| 61-70          | 1         | 0.79%   |
| 131-140        | 1         | 0.79%   |
| 91-100         | 1         | 0.79%   |
| Unknown        | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 44        | 35.48%  |
| 101-120       | 36        | 29.03%  |
| 121-160       | 32        | 25.81%  |
| 1-50          | 7         | 5.65%   |
| 161-240       | 3         | 2.42%   |
| More than 240 | 1         | 0.81%   |
| Unknown       | 1         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 113       | 89.68%  |
| 2     | 10        | 7.94%   |
| 0     | 3         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 58        | 32.77%  |
| Realtek Semiconductor      | 52        | 29.38%  |
| Qualcomm Atheros           | 17        | 9.6%    |
| Broadcom                   | 13        | 7.34%   |
| Marvell Technology Group   | 6         | 3.39%   |
| TP-Link                    | 4         | 2.26%   |
| Ralink Technology          | 4         | 2.26%   |
| Nvidia                     | 4         | 2.26%   |
| Broadcom Limited           | 4         | 2.26%   |
| Ralink                     | 3         | 1.69%   |
| D-Link System              | 2         | 1.13%   |
| VIA Technologies           | 1         | 0.56%   |
| Shenzhen Goodix Technology | 1         | 0.56%   |
| Samsung Electronics        | 1         | 0.56%   |
| Qualcomm                   | 1         | 0.56%   |
| OPPO Electronics           | 1         | 0.56%   |
| NetGear                    | 1         | 0.56%   |
| MediaTek                   | 1         | 0.56%   |
| Edimax Technology          | 1         | 0.56%   |
| D-Link                     | 1         | 0.56%   |
| ASUSTek Computer           | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 33        | 15.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 4.35%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.93%   |
| Intel Wireless 7265                                                     | 4         | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 3         | 1.45%   |
| Intel Wireless 8260                                                     | 3         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.45%   |
| Intel Ethernet Connection (5) I219-LM                                   | 3         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.97%   |
| Nvidia MCP61 Ethernet                                                   | 2         | 0.97%   |
| Intel Wireless 7260                                                     | 2         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.97%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.97%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                    | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.97%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 2         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.97%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.48%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.48%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.48%   |
| Shenzhen Goodix Fingerprint Reader                                      | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 40        | 41.24%  |
| Realtek Semiconductor    | 16        | 16.49%  |
| Qualcomm Atheros         | 14        | 14.43%  |
| Broadcom                 | 6         | 6.19%   |
| TP-Link                  | 4         | 4.12%   |
| Ralink Technology        | 4         | 4.12%   |
| Ralink                   | 3         | 3.09%   |
| D-Link System            | 2         | 2.06%   |
| Broadcom Limited         | 2         | 2.06%   |
| NetGear                  | 1         | 1.03%   |
| MediaTek                 | 1         | 1.03%   |
| Marvell Technology Group | 1         | 1.03%   |
| Edimax Technology        | 1         | 1.03%   |
| D-Link                   | 1         | 1.03%   |
| ASUSTek Computer         | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 4         | 4.12%   |
| Intel Wireless 7265                                                     | 4         | 4.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.09%   |
| Intel Wireless 8260                                                     | 3         | 3.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 3.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.06%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.06%   |
| Intel Wireless 7260                                                     | 2         | 2.06%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.06%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 1.03%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.03%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.03%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.03%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.03%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 41.28%  |
| Intel                    | 35        | 32.11%  |
| Broadcom                 | 8         | 7.34%   |
| Qualcomm Atheros         | 6         | 5.5%    |
| Marvell Technology Group | 5         | 4.59%   |
| Nvidia                   | 4         | 3.67%   |
| Broadcom Limited         | 2         | 1.83%   |
| VIA Technologies         | 1         | 0.92%   |
| Samsung Electronics      | 1         | 0.92%   |
| Qualcomm                 | 1         | 0.92%   |
| OPPO Electronics         | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 30.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 9.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 8.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 2.75%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 2.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 1.83%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 1.83%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.83%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.83%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 1.83%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2         | 1.83%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.92%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.92%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.92%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.92%   |
| OPPO Ace 3V                                                            | 1         | 0.92%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.92%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 0.92%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.92%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.92%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.92%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.92%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.92%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.92%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 0.92%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.92%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.92%   |
| Intel 82578DC Gigabit Network Connection                               | 1         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.92%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 0.92%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.92%   |
| Intel 82566DM Gigabit Network Connection                               | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 53.27%  |
| WiFi     | 92        | 46.23%  |
| Modem    | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 52.27%  |
| Ethernet | 63        | 47.73%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 50%     |
| 1     | 59        | 46.83%  |
| 0     | 3         | 2.38%   |
| 3     | 1         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 75.78%  |
| Yes  | 31        | 24.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 44.62%  |
| Broadcom                        | 8         | 12.31%  |
| Realtek Semiconductor           | 4         | 6.15%   |
| IMC Networks                    | 4         | 6.15%   |
| Qualcomm Atheros Communications | 3         | 4.62%   |
| Apple                           | 3         | 4.62%   |
| Hewlett-Packard                 | 2         | 3.08%   |
| Foxconn / Hon Hai               | 2         | 3.08%   |
| Cambridge Silicon Radio         | 2         | 3.08%   |
| ASUSTek Computer                | 2         | 3.08%   |
| Taiyo Yuden                     | 1         | 1.54%   |
| Realtek                         | 1         | 1.54%   |
| Ralink                          | 1         | 1.54%   |
| Marvell Semiconductor           | 1         | 1.54%   |
| Dynex                           | 1         | 1.54%   |
| Dell                            | 1         | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 14        | 21.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 7         | 10.77%  |
| Realtek  Bluetooth 4.2 Adapter                           | 3         | 4.62%   |
| Intel AX201 Bluetooth                                    | 3         | 4.62%   |
| IMC Networks Bluetooth Radio                             | 3         | 4.62%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 3.08%   |
| Intel AX200 Bluetooth                                    | 2         | 3.08%   |
| HP Broadcom 2070 Bluetooth Combo                         | 2         | 3.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 3.08%   |
| Broadcom BCM2045 Bluetooth                               | 2         | 3.08%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 1.54%   |
| Realtek RTL8723B Bluetooth                               | 1         | 1.54%   |
| Realtek Bluetooth Radio                                  | 1         | 1.54%   |
| Ralink RT3290 Bluetooth                                  | 1         | 1.54%   |
| Qualcomm Atheros  Bluetooth Device                       | 1         | 1.54%   |
| Qualcomm Atheros Bluetooth                               | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 1.54%   |
| Marvell Bluetooth and Wireless LAN Composite             | 1         | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1         | 1.54%   |
| IMC Networks Bluetooth Module                            | 1         | 1.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller          | 1         | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1         | 1.54%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 1.54%   |
| Dell Wireless 365 Bluetooth                              | 1         | 1.54%   |
| Broadcom HP Portable SoftSailing                         | 1         | 1.54%   |
| Broadcom Bluetooth 2.1 Device                            | 1         | 1.54%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1         | 1.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 1.54%   |
| Broadcom BCM2070 Bluetooth Device                        | 1         | 1.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 1         | 1.54%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 1.54%   |
| ASUS BCM20702A0                                          | 1         | 1.54%   |
| Apple Bluetooth USB Host Controller                      | 1         | 1.54%   |
| Apple Bluetooth Host Controller                          | 1         | 1.54%   |
| Apple Bluetooth HCI                                      | 1         | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 90        | 57.32%  |
| AMD                 | 31        | 19.75%  |
| Nvidia              | 18        | 11.46%  |
| Tenx Technology     | 9         | 5.73%   |
| Focusrite-Novation  | 2         | 1.27%   |
| C-Media Electronics | 2         | 1.27%   |
| VIA Technologies    | 1         | 0.64%   |
| Plantronics         | 1         | 0.64%   |
| Native Instruments  | 1         | 0.64%   |
| Creative Labs       | 1         | 0.64%   |
| ASUSTek Computer    | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 5.65%   |
| Tenx Technology USB AUDIO                                                                         | 9         | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.39%   |
| AMD FCH Azalia Controller                                                                         | 6         | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 2.82%   |
| AMD Ryzen HD Audio Controller                                                                     | 5         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.26%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.69%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.69%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3         | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.69%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.13%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.13%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 1.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.13%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.13%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 1.13%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.56%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.56%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 22.68%  |
| Unknown             | 17        | 17.53%  |
| SK hynix            | 14        | 14.43%  |
| Micron Technology   | 8         | 8.25%   |
| Kingston            | 7         | 7.22%   |
| G.Skill             | 3         | 3.09%   |
| Crucial             | 3         | 3.09%   |
| Corsair             | 3         | 3.09%   |
| Nanya Technology    | 2         | 2.06%   |
| GOODRAM             | 2         | 2.06%   |
| ff                  | 2         | 2.06%   |
| Elpida              | 2         | 2.06%   |
| 4ea5                | 2         | 2.06%   |
| 48spaces            | 2         | 2.06%   |
| Unknown             | 2         | 2.06%   |
| Unifosa             | 1         | 1.03%   |
| Toshiba             | 1         | 1.03%   |
| Team                | 1         | 1.03%   |
| Ramaxel Technology  | 1         | 1.03%   |
| High Bridge         | 1         | 1.03%   |
| Avant               | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                               | 2         | 1.94%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                    | 2         | 1.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.94%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 2         | 1.94%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s                     | 2         | 1.94%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                           | 2         | 1.94%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 1.94%   |
| Unknown                                                                   | 2         | 1.94%   |
| Unknown RAM Module 8GB SODIMM DDR3                                        | 1         | 0.97%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                      | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                               | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                                | 1         | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                                 | 1         | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.97%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                       | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 1         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                                | 1         | 0.97%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 1         | 0.97%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                                  | 1         | 0.97%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 1         | 0.97%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                         | 1         | 0.97%   |
| Toshiba RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s                      | 1         | 0.97%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.97%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.97%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s                      | 1         | 0.97%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                      | 1         | 0.97%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.97%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.97%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM 1067MT/s                         | 1         | 0.97%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.97%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                                  | 1         | 0.97%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s                       | 1         | 0.97%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.97%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 0.97%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.97%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 48.78%  |
| DDR4    | 20        | 24.39%  |
| DDR2    | 6         | 7.32%   |
| Unknown | 5         | 6.1%    |
| SDRAM   | 4         | 4.88%   |
| LPDDR3  | 3         | 3.66%   |
| LPDDR4  | 2         | 2.44%   |
| DRAM    | 1         | 1.22%   |
| DDR     | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 57.5%   |
| DIMM         | 27        | 33.75%  |
| Unknown      | 5         | 6.25%   |
| Row Of Chips | 2         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 30        | 31.91%  |
| 8192  | 22        | 23.4%   |
| 4096  | 21        | 22.34%  |
| 16384 | 9         | 9.57%   |
| 1024  | 9         | 9.57%   |
| 32768 | 2         | 2.13%   |
| 256   | 1         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 21.59%  |
| 1333    | 11        | 12.5%   |
| 3200    | 8         | 9.09%   |
| 2667    | 6         | 6.82%   |
| 800     | 6         | 6.82%   |
| 2400    | 5         | 5.68%   |
| Unknown | 4         | 4.55%   |
| 1867    | 3         | 3.41%   |
| 1334    | 3         | 3.41%   |
| 1066    | 3         | 3.41%   |
| 667     | 3         | 3.41%   |
| 2133    | 2         | 2.27%   |
| 1067    | 2         | 2.27%   |
| 8400    | 1         | 1.14%   |
| 4199    | 1         | 1.14%   |
| 4000    | 1         | 1.14%   |
| 3800    | 1         | 1.14%   |
| 3600    | 1         | 1.14%   |
| 2666    | 1         | 1.14%   |
| 2048    | 1         | 1.14%   |
| 1866    | 1         | 1.14%   |
| 1800    | 1         | 1.14%   |
| 1639    | 1         | 1.14%   |
| 533     | 1         | 1.14%   |
| 400     | 1         | 1.14%   |
| 266     | 1         | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung CLP-325 Color Laser Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 16        | 25.4%   |
| Microdia                               | 6         | 9.52%   |
| Suyin                                  | 4         | 6.35%   |
| Realtek Semiconductor                  | 4         | 6.35%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.35%   |
| Bison Electronics                      | 4         | 6.35%   |
| Alcor Micro                            | 4         | 6.35%   |
| Z-Star Microelectronics                | 3         | 4.76%   |
| Quanta                                 | 3         | 4.76%   |
| Sunplus Innovation Technology          | 2         | 3.17%   |
| Logitech                               | 2         | 3.17%   |
| IMC Networks                           | 2         | 3.17%   |
| Apple                                  | 2         | 3.17%   |
| Syntek                                 | 1         | 1.59%   |
| Sonix Technology                       | 1         | 1.59%   |
| Samsung Electronics                    | 1         | 1.59%   |
| Ricoh                                  | 1         | 1.59%   |
| Microsoft                              | 1         | 1.59%   |
| JOURIST-DC80                           | 1         | 1.59%   |
| Guillemot                              | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                                  | 3         | 4.69%   |
| Z-Star Webcam                                               | 2         | 3.13%   |
| Quanta HP TrueVision HD Camera                              | 2         | 3.13%   |
| Chicony Integrated Camera                                   | 2         | 3.13%   |
| Chicony HP Truevision HD                                    | 2         | 3.13%   |
| Chicony HD WebCam                                           | 2         | 3.13%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.56%   |
| Syntek Integrated Camera                                    | 1         | 1.56%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 1.56%   |
| Suyin HP Truevision HD                                      | 1         | 1.56%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 1.56%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.56%   |
| Sunplus Integrated Webcam                                   | 1         | 1.56%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.56%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 1.56%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 1.56%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.56%   |
| Realtek USB Camera                                          | 1         | 1.56%   |
| Realtek Integrated Webcam HD                                | 1         | 1.56%   |
| Realtek Integrated Webcam                                   | 1         | 1.56%   |
| Realtek HP Truevision HD                                    | 1         | 1.56%   |
| Quanta HP 5M Camera                                         | 1         | 1.56%   |
| Quanta HD User Facing                                       | 1         | 1.56%   |
| Microsoft LifeCam Cinema                                    | 1         | 1.56%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.56%   |
| Microdia Lenovo EasyCamera                                  | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.56%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.56%   |
| Microdia ASUS USB2.0 Camera                                 | 1         | 1.56%   |
| Logitech Webcam C270                                        | 1         | 1.56%   |
| Logitech QuickCam Notebook Pro                              | 1         | 1.56%   |
| JOURIST-DC80 JOURIST-DC80                                   | 1         | 1.56%   |
| IMC Networks VGA UVC WebCam                                 | 1         | 1.56%   |
| IMC Networks Integrated Camera                              | 1         | 1.56%   |
| Guillemot Hercules Dualpix Exchange                         | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.56%   |
| Chicony thinkpad t430s camera                               | 1         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.56%   |
| Chicony HP Wide Vision HD Camera                            | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| AuthenTec                  | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| STMicroelectronics         | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 12.5%   |
| Validity Sensors VFS491                           | 1         | 12.5%   |
| Validity Sensors VFS101 Fingerprint Reader        | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader             | 1         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 12.5%   |
| AuthenTec AES1600                                 | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader                                          | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 73.02%  |
| 1     | 27        | 21.43%  |
| 2     | 6         | 4.76%   |
| 3     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 13        | 30.23%  |
| Net/wireless          | 8         | 18.6%   |
| Fingerprint reader    | 8         | 18.6%   |
| Multimedia controller | 6         | 13.95%  |
| Chipcard              | 2         | 4.65%   |
| Bluetooth             | 2         | 4.65%   |
| Unassigned class      | 1         | 2.33%   |
| Net/ethernet          | 1         | 2.33%   |
| Card reader           | 1         | 2.33%   |
| Camera                | 1         | 2.33%   |

