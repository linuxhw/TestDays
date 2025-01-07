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

Total: 150

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Sparky 6    | 16        | 13.22%  |
| Sparky 7.5  | 15        | 12.4%   |
| Sparky 8    | 14        | 11.57%  |
| Sparky 7    | 12        | 9.92%   |
| Sparky 6.7  | 6         | 4.96%   |
| Sparky 6.1  | 6         | 4.96%   |
| Sparky 7.1  | 5         | 4.13%   |
| Sparky 6.5  | 5         | 4.13%   |
| Sparky 5.12 | 5         | 4.13%   |
| Sparky 7.3  | 4         | 3.31%   |
| Sparky 7.2  | 4         | 3.31%   |
| Sparky 7.0  | 4         | 3.31%   |
| Sparky 6.6  | 4         | 3.31%   |
| Sparky 6.3  | 4         | 3.31%   |
| Sparky 7.4  | 3         | 2.48%   |
| Sparky 6.0  | 3         | 2.48%   |
| Sparky 5.14 | 3         | 2.48%   |
| Sparky 5.10 | 3         | 2.48%   |
| Sparky 6.2  | 2         | 1.65%   |
| Sparky 5.13 | 2         | 1.65%   |
| Sparky 7.6  | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Sparky | 114       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.1.0-25-amd64         | 9         | 7.03%   |
| 6.1.0-18-amd64         | 4         | 3.13%   |
| 5.10.0-21-amd64        | 4         | 3.13%   |
| 5.10.0-11-686          | 4         | 3.13%   |
| 6.1.0-21-amd64         | 3         | 2.34%   |
| 6.1.0-17-amd64         | 3         | 2.34%   |
| 6.1.0-13-amd64         | 3         | 2.34%   |
| 5.10.0-9-amd64         | 3         | 2.34%   |
| 5.10.0-8-amd64         | 3         | 2.34%   |
| 5.10.0-6-amd64         | 3         | 2.34%   |
| 4.19.0-8-amd64         | 3         | 2.34%   |
| 4.19.0-12-amd64        | 3         | 2.34%   |
| 6.7.12-amd64           | 2         | 1.56%   |
| 6.5.0-5-amd64          | 2         | 1.56%   |
| 6.4.0-2-amd64          | 2         | 1.56%   |
| 6.3.0-1-amd64          | 2         | 1.56%   |
| 6.1.0-27-amd64         | 2         | 1.56%   |
| 6.1.0-26-amd64         | 2         | 1.56%   |
| 6.1.0-23-amd64         | 2         | 1.56%   |
| 6.1.0-12-amd64         | 2         | 1.56%   |
| 5.18.0-4-amd64         | 2         | 1.56%   |
| 5.18.0-2-amd64         | 2         | 1.56%   |
| 5.17.0-1-amd64         | 2         | 1.56%   |
| 5.10.0-3-amd64         | 2         | 1.56%   |
| 5.10.0-23-amd64        | 2         | 1.56%   |
| 5.10.0-14-amd64        | 2         | 1.56%   |
| 4.19.0-13-686          | 2         | 1.56%   |
| 4.19.0-10-686          | 2         | 1.56%   |
| 6.6.68-x64v3-xanmod1   | 1         | 0.78%   |
| 6.6.15-amd64           | 1         | 0.78%   |
| 6.6.13-amd64           | 1         | 0.78%   |
| 6.5.9-x64v3-xanmod1    | 1         | 0.78%   |
| 6.4.4-sparky8-amd64    | 1         | 0.78%   |
| 6.4.12-x64v3-xanmod1   | 1         | 0.78%   |
| 6.4.0-3-amd64          | 1         | 0.78%   |
| 6.4.0-1-amd64          | 1         | 0.78%   |
| 6.3.3-1-liquorix-amd64 | 1         | 0.78%   |
| 6.2.0-sparky-amd64     | 1         | 0.78%   |
| 6.12.1-sparky-amd64    | 1         | 0.78%   |
| 6.11.6-sparky-amd64    | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 34        | 28.1%   |
| 5.10.0  | 32        | 26.45%  |
| 4.19.0  | 10        | 8.26%   |
| 5.18.0  | 4         | 3.31%   |
| 6.4.0   | 3         | 2.48%   |
| 6.7.12  | 2         | 1.65%   |
| 6.5.0   | 2         | 1.65%   |
| 6.3.0   | 2         | 1.65%   |
| 5.17.0  | 2         | 1.65%   |
| 6.6.68  | 1         | 0.83%   |
| 6.6.15  | 1         | 0.83%   |
| 6.6.13  | 1         | 0.83%   |
| 6.5.9   | 1         | 0.83%   |
| 6.4.4   | 1         | 0.83%   |
| 6.4.12  | 1         | 0.83%   |
| 6.3.3   | 1         | 0.83%   |
| 6.2.0   | 1         | 0.83%   |
| 6.12.1  | 1         | 0.83%   |
| 6.11.6  | 1         | 0.83%   |
| 6.11.3  | 1         | 0.83%   |
| 6.11.10 | 1         | 0.83%   |
| 6.0.11  | 1         | 0.83%   |
| 6.0.0   | 1         | 0.83%   |
| 5.9.13  | 1         | 0.83%   |
| 5.9.0   | 1         | 0.83%   |
| 5.8.13  | 1         | 0.83%   |
| 5.8.0   | 1         | 0.83%   |
| 5.7.2   | 1         | 0.83%   |
| 5.6.0   | 1         | 0.83%   |
| 5.5.0   | 1         | 0.83%   |
| 5.4.7   | 1         | 0.83%   |
| 5.2.0   | 1         | 0.83%   |
| 5.18.3  | 1         | 0.83%   |
| 5.17.3  | 1         | 0.83%   |
| 5.16.5  | 1         | 0.83%   |
| 5.16.0  | 1         | 0.83%   |
| 5.15.0  | 1         | 0.83%   |
| 5.14.0  | 1         | 0.83%   |
| 5.10.4  | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 34        | 28.33%  |
| 5.10    | 33        | 27.5%   |
| 4.19    | 10        | 8.33%   |
| 6.4     | 5         | 4.17%   |
| 5.18    | 5         | 4.17%   |
| 6.6     | 3         | 2.5%    |
| 6.5     | 3         | 2.5%    |
| 6.3     | 3         | 2.5%    |
| 6.11    | 3         | 2.5%    |
| 5.17    | 3         | 2.5%    |
| 6.7     | 2         | 1.67%   |
| 5.9     | 2         | 1.67%   |
| 5.8     | 2         | 1.67%   |
| 5.16    | 2         | 1.67%   |
| 6.2     | 1         | 0.83%   |
| 6.12    | 1         | 0.83%   |
| 6.0     | 1         | 0.83%   |
| 5.7     | 1         | 0.83%   |
| 5.6     | 1         | 0.83%   |
| 5.5     | 1         | 0.83%   |
| 5.4     | 1         | 0.83%   |
| 5.2     | 1         | 0.83%   |
| 5.15    | 1         | 0.83%   |
| 5.14    | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 93.86%  |
| i686   | 7         | 6.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 40        | 34.48%  |
| LXQt             | 24        | 20.69%  |
| X-Cinnamon       | 13        | 11.21%  |
| KDE5             | 12        | 10.34%  |
| Unknown          | 8         | 6.9%    |
| MATE             | 4         | 3.45%   |
| openbox          | 3         | 2.59%   |
| lightdm-xsession | 2         | 1.72%   |
| GNOME            | 2         | 1.72%   |
| Budgie           | 2         | 1.72%   |
| LXDE             | 1         | 0.86%   |
| ICEWM            | 1         | 0.86%   |
| GNOME Flashback  | 1         | 0.86%   |
| GNOME Classic    | 1         | 0.86%   |
| Draco            | 1         | 0.86%   |
| Cinnamon         | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 110       | 94.83%  |
| Tty  | 6         | 5.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 36.52%  |
| LightDM | 35        | 30.43%  |
| SDDM    | 22        | 19.13%  |
| TDM     | 13        | 11.3%   |
| GDM     | 2         | 1.74%   |
| XDM     | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 45        | 39.47%  |
| pl_PL   | 8         | 7.02%   |
| es_ES   | 8         | 7.02%   |
| pt_BR   | 7         | 6.14%   |
| en_GB   | 7         | 6.14%   |
| de_DE   | 7         | 6.14%   |
| fr_FR   | 5         | 4.39%   |
| ru_RU   | 3         | 2.63%   |
| it_IT   | 3         | 2.63%   |
| en_CA   | 2         | 1.75%   |
| Unknown | 2         | 1.75%   |
| sv_SE   | 1         | 0.88%   |
| lt_LT   | 1         | 0.88%   |
| ja_JP   | 1         | 0.88%   |
| gl_ES   | 1         | 0.88%   |
| es_US   | 1         | 0.88%   |
| es_MX   | 1         | 0.88%   |
| es_CO   | 1         | 0.88%   |
| es_CL   | 1         | 0.88%   |
| es_AR   | 1         | 0.88%   |
| en_ZA   | 1         | 0.88%   |
| en_PH   | 1         | 0.88%   |
| en_IN   | 1         | 0.88%   |
| en_DK   | 1         | 0.88%   |
| en_AU   | 1         | 0.88%   |
| de_CH   | 1         | 0.88%   |
| cs_CZ   | 1         | 0.88%   |
| ar_EG   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 74        | 64.35%  |
| EFI  | 41        | 35.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 89.47%  |
| Overlay | 5         | 4.39%   |
| Btrfs   | 5         | 4.39%   |
| Zfs     | 1         | 0.88%   |
| Ext2    | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 43        | 37.39%  |
| Unknown | 42        | 36.52%  |
| MBR     | 30        | 26.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 84.21%  |
| Yes       | 18        | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 71.93%  |
| Yes       | 32        | 28.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 28        | 24.56%  |
| ASUSTek Computer    | 12        | 10.53%  |
| Dell                | 11        | 9.65%   |
| Acer                | 9         | 7.89%   |
| Lenovo              | 8         | 7.02%   |
| Gigabyte Technology | 8         | 7.02%   |
| Intel               | 6         | 5.26%   |
| Google              | 6         | 5.26%   |
| MSI                 | 5         | 4.39%   |
| Samsung Electronics | 3         | 2.63%   |
| Medion              | 2         | 1.75%   |
| Apple               | 2         | 1.75%   |
| Toshiba             | 1         | 0.88%   |
| Sony                | 1         | 0.88%   |
| Shuttle             | 1         | 0.88%   |
| Positivo            | 1         | 0.88%   |
| Panasonic           | 1         | 0.88%   |
| Microsoft           | 1         | 0.88%   |
| Mediacom            | 1         | 0.88%   |
| HUAWEI              | 1         | 0.88%   |
| Fujitsu Siemens     | 1         | 0.88%   |
| Foxconn             | 1         | 0.88%   |
| eMachines           | 1         | 0.88%   |
| Beelink             | 1         | 0.88%   |
| ASRock              | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7B86                           | 2         | 1.75%   |
| Dell OptiPlex 7010                    | 2         | 1.75%   |
| Toshiba Satellite L505D               | 1         | 0.88%   |
| Sony SVE1513Q1ESI                     | 1         | 0.88%   |
| Shuttle NC03U                         | 1         | 0.88%   |
| Samsung NC10                          | 1         | 0.88%   |
| Samsung N150P/N210P/N220P             | 1         | 0.88%   |
| Samsung N150/N210/N220                | 1         | 0.88%   |
| Positivo CHT14B                       | 1         | 0.88%   |
| Panasonic CFSZ5-2                     | 1         | 0.88%   |
| MSI MS-7C09                           | 1         | 0.88%   |
| MSI MS-7721                           | 1         | 0.88%   |
| MSI Alpha 15 A3DDK                    | 1         | 0.88%   |
| Microsoft Surface Pro 4               | 1         | 0.88%   |
| Medion P961x                          | 1         | 0.88%   |
| Medion E15415                         | 1         | 0.88%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 0.88%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 0.88%   |
| Lenovo ThinkPad T60 2007FUG           | 1         | 0.88%   |
| Lenovo ThinkPad T430 2349FC4          | 1         | 0.88%   |
| Lenovo ThinkPad E15 20RES0GF00        | 1         | 0.88%   |
| Lenovo ThinkCentre M90s 11D2CTO1WW    | 1         | 0.88%   |
| Lenovo IdeaPad S206 20154             | 1         | 0.88%   |
| Lenovo IdeaPad 3 15IML05 81WB         | 1         | 0.88%   |
| Lenovo G50-30 80G0                    | 1         | 0.88%   |
| Intel NUC8i5BEH                       | 1         | 0.88%   |
| Intel NUC5CPYB H61145-408             | 1         | 0.88%   |
| Intel H61                             | 1         | 0.88%   |
| Intel H55                             | 1         | 0.88%   |
| Intel DG43RK AAE78175-402             | 1         | 0.88%   |
| Intel DG41TY AAE47335-300             | 1         | 0.88%   |
| HUAWEI HVY-WXX9                       | 1         | 0.88%   |
| HP Z440 Workstation                   | 1         | 0.88%   |
| HP Z420 Workstation                   | 1         | 0.88%   |
| HP t5740                              | 1         | 0.88%   |
| HP Stream Notebook PC 13              | 1         | 0.88%   |
| HP rp5700 Business System             | 1         | 0.88%   |
| HP Pavilion x360 Convertible 14-ba0xx | 1         | 0.88%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 1         | 0.88%   |
| HP Pavilion g7                        | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 9         | 7.89%   |
| HP Pavilion        | 6         | 5.26%   |
| HP EliteDesk       | 6         | 5.26%   |
| Dell OptiPlex      | 6         | 5.26%   |
| Lenovo ThinkPad    | 4         | 3.51%   |
| HP EliteBook       | 4         | 3.51%   |
| HP Compaq          | 4         | 3.51%   |
| Dell Inspiron      | 4         | 3.51%   |
| MSI MS-7B86        | 2         | 1.75%   |
| Lenovo IdeaPad     | 2         | 1.75%   |
| HP Laptop          | 2         | 1.75%   |
| Toshiba Satellite  | 1         | 0.88%   |
| Sony SVE1513Q1ESI  | 1         | 0.88%   |
| Shuttle NC03U      | 1         | 0.88%   |
| Samsung NC10       | 1         | 0.88%   |
| Samsung N150P      | 1         | 0.88%   |
| Samsung N150       | 1         | 0.88%   |
| Positivo CHT14B    | 1         | 0.88%   |
| Panasonic CFSZ5-2  | 1         | 0.88%   |
| MSI MS-7C09        | 1         | 0.88%   |
| MSI MS-7721        | 1         | 0.88%   |
| MSI Alpha          | 1         | 0.88%   |
| Microsoft Surface  | 1         | 0.88%   |
| Medion P961x       | 1         | 0.88%   |
| Medion E15415      | 1         | 0.88%   |
| Mediacom SmartBook | 1         | 0.88%   |
| Lenovo ThinkCentre | 1         | 0.88%   |
| Lenovo G50-30      | 1         | 0.88%   |
| Intel NUC8i5BEH    | 1         | 0.88%   |
| Intel NUC5CPYB     | 1         | 0.88%   |
| Intel H61          | 1         | 0.88%   |
| Intel H55          | 1         | 0.88%   |
| Intel DG43RK       | 1         | 0.88%   |
| Intel DG41TY       | 1         | 0.88%   |
| HUAWEI HVY-WXX9    | 1         | 0.88%   |
| HP Z440            | 1         | 0.88%   |
| HP Z420            | 1         | 0.88%   |
| HP t5740           | 1         | 0.88%   |
| HP Stream          | 1         | 0.88%   |
| HP rp5700          | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 13        | 11.4%   |
| 2010 | 12        | 10.53%  |
| 2017 | 11        | 9.65%   |
| 2009 | 10        | 8.77%   |
| 2021 | 8         | 7.02%   |
| 2011 | 8         | 7.02%   |
| 2014 | 7         | 6.14%   |
| 2019 | 5         | 4.39%   |
| 2018 | 5         | 4.39%   |
| 2016 | 5         | 4.39%   |
| 2015 | 5         | 4.39%   |
| 2008 | 5         | 4.39%   |
| 2007 | 5         | 4.39%   |
| 2020 | 4         | 3.51%   |
| 2024 | 3         | 2.63%   |
| 2013 | 3         | 2.63%   |
| 2022 | 2         | 1.75%   |
| 2006 | 2         | 1.75%   |
| 2023 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 57        | 50%     |
| Desktop     | 51        | 44.74%  |
| Mini pc     | 3         | 2.63%   |
| Tablet      | 1         | 0.88%   |
| Convertible | 1         | 0.88%   |
| All in one  | 1         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 112       | 98.25%  |
| Enabled  | 2         | 1.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 108       | 94.74%  |
| Yes  | 6         | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 32        | 28.07%  |
| 4.01-8.0    | 16        | 14.04%  |
| 8.01-16.0   | 14        | 12.28%  |
| 16.01-24.0  | 13        | 11.4%   |
| 32.01-64.0  | 12        | 10.53%  |
| 1.01-2.0    | 11        | 9.65%   |
| 24.01-32.0  | 7         | 6.14%   |
| 2.01-3.0    | 7         | 6.14%   |
| 64.01-256.0 | 1         | 0.88%   |
| 0.51-1.0    | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 41        | 34.45%  |
| 2.01-3.0   | 29        | 24.37%  |
| 0.51-1.0   | 16        | 13.45%  |
| 4.01-8.0   | 10        | 8.4%    |
| 3.01-4.0   | 10        | 8.4%    |
| 8.01-16.0  | 6         | 5.04%   |
| 16.01-24.0 | 4         | 3.36%   |
| 0.01-0.5   | 3         | 2.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 59.83%  |
| 2      | 27        | 23.08%  |
| 4      | 6         | 5.13%   |
| 3      | 5         | 4.27%   |
| 6      | 4         | 3.42%   |
| 5      | 3         | 2.56%   |
| 7      | 2         | 1.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 61.74%  |
| Yes       | 44        | 38.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 83.33%  |
| No        | 19        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 70.18%  |
| No        | 34        | 29.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 50.88%  |
| No        | 56        | 49.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 27        | 23.68%  |
| Germany      | 10        | 8.77%   |
| Spain        | 8         | 7.02%   |
| Poland       | 8         | 7.02%   |
| France       | 7         | 6.14%   |
| Brazil       | 7         | 6.14%   |
| UK           | 6         | 5.26%   |
| Italy        | 5         | 4.39%   |
| Canada       | 4         | 3.51%   |
| Sweden       | 3         | 2.63%   |
| Indonesia    | 3         | 2.63%   |
| Russia       | 2         | 1.75%   |
| Mexico       | 2         | 1.75%   |
| Argentina    | 2         | 1.75%   |
| Venezuela    | 1         | 0.88%   |
| Uzbekistan   | 1         | 0.88%   |
| UAE          | 1         | 0.88%   |
| Switzerland  | 1         | 0.88%   |
| South Africa | 1         | 0.88%   |
| Philippines  | 1         | 0.88%   |
| New Zealand  | 1         | 0.88%   |
| Netherlands  | 1         | 0.88%   |
| Malaysia     | 1         | 0.88%   |
| Lithuania    | 1         | 0.88%   |
| Lebanon      | 1         | 0.88%   |
| Japan        | 1         | 0.88%   |
| India        | 1         | 0.88%   |
| Hungary      | 1         | 0.88%   |
| Czechia      | 1         | 0.88%   |
| Colombia     | 1         | 0.88%   |
| Chile        | 1         | 0.88%   |
| Bulgaria     | 1         | 0.88%   |
| Belgium      | 1         | 0.88%   |
| Australia    | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Echelon             | 11        | 9.24%   |
| Vigo                | 2         | 1.68%   |
| Rio de Janeiro      | 2         | 1.68%   |
| Montreuil           | 2         | 1.68%   |
| Montreal            | 2         | 1.68%   |
| Leipzig             | 2         | 1.68%   |
| Barcelona           | 2         | 1.68%   |
| Zephyrhills         | 1         | 0.84%   |
| Wrzesnia            | 1         | 0.84%   |
| Woking              | 1         | 0.84%   |
| West Palm Beach     | 1         | 0.84%   |
| Wenatchee           | 1         | 0.84%   |
| Vilnius             | 1         | 0.84%   |
| Uppsala             | 1         | 0.84%   |
| Tucson              | 1         | 0.84%   |
| Trieste             | 1         | 0.84%   |
| Trelaze             | 1         | 0.84%   |
| Tauranga            | 1         | 0.84%   |
| Takahama            | 1         | 0.84%   |
| Surabaya            | 1         | 0.84%   |
| Spokane             | 1         | 0.84%   |
| Sofia               | 1         | 0.84%   |
| Sin el Fil          | 1         | 0.84%   |
| Santo André        | 1         | 0.84%   |
| San Cristóbal      | 1         | 0.84%   |
| San Antonio         | 1         | 0.84%   |
| Salina Cruz         | 1         | 0.84%   |
| Sainte-Julie        | 1         | 0.84%   |
| Rudnik              | 1         | 0.84%   |
| Rudersberg          | 1         | 0.84%   |
| Rosario             | 1         | 0.84%   |
| Rio Claro           | 1         | 0.84%   |
| Rheinbach           | 1         | 0.84%   |
| Quezon City         | 1         | 0.84%   |
| Pujaudran           | 1         | 0.84%   |
| Puente Alto         | 1         | 0.84%   |
| Presidente Prudente | 1         | 0.84%   |
| Posadas             | 1         | 0.84%   |
| Pompano Beach       | 1         | 0.84%   |
| Norrköping         | 1         | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 25        | 28     | 13.51%  |
| Seagate                      | 25        | 34     | 13.51%  |
| Samsung Electronics          | 23        | 37     | 12.43%  |
| Hitachi                      | 12        | 15     | 6.49%   |
| Unknown                      | 10        | 10     | 5.41%   |
| Toshiba                      | 8         | 8      | 4.32%   |
| External                     | 8         | 15     | 4.32%   |
| TO Exter                     | 7         | 13     | 3.78%   |
| SanDisk                      | 6         | 8      | 3.24%   |
| Kingston                     | 6         | 7      | 3.24%   |
| JMicron Technology           | 5         | 8      | 2.7%    |
| Crucial                      | 5         | 5      | 2.7%    |
| SPCC                         | 3         | 4      | 1.62%   |
| SK hynix                     | 3         | 3      | 1.62%   |
| Silicon Motion               | 3         | 4      | 1.62%   |
| Intel                        | 3         | 3      | 1.62%   |
| HGST                         | 3         | 3      | 1.62%   |
| GOODRAM                      | 3         | 6      | 1.62%   |
| ASMedia                      | 3         | 3      | 1.62%   |
| A-DATA Technology            | 3         | 5      | 1.62%   |
| Team                         | 2         | 2      | 1.08%   |
| Phison Electronics           | 2         | 2      | 1.08%   |
| Patriot                      | 2         | 2      | 1.08%   |
| Unknown                      | 2         | 2      | 1.08%   |
| XPG                          | 1         | 1      | 0.54%   |
| Shenzhen Longsys Electronics | 1         | 2      | 0.54%   |
| PNY                          | 1         | 1      | 0.54%   |
| ORICO                        | 1         | 1      | 0.54%   |
| OCZ                          | 1         | 1      | 0.54%   |
| Netac                        | 1         | 1      | 0.54%   |
| Micron Technology            | 1         | 1      | 0.54%   |
| KingDian                     | 1         | 1      | 0.54%   |
| Gigabyte Technology          | 1         | 1      | 0.54%   |
| Fujitsu                      | 1         | 2      | 0.54%   |
| China                        | 1         | 1      | 0.54%   |
| ASUS-JM                      | 1         | 1      | 0.54%   |
| Apple                        | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| TO Exter nal USB 3.0 1024GB                           | 7         | 3.57%   |
| JMicron Generic 500GB                                 | 5         | 2.55%   |
| External USB3.0 1TB                                   | 5         | 2.55%   |
| External USB 3.0 500GB                                | 4         | 2.04%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 1.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 3         | 1.53%   |
| WDC WD3200AAKS-75L9A0 320GB                           | 2         | 1.02%   |
| WDC WD1600BEVT-22ZCT0 160GB                           | 2         | 1.02%   |
| Unknown MMC Card  32GB                                | 2         | 1.02%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 1.02%   |
| Toshiba MQ01ACF032 320GB                              | 2         | 1.02%   |
| Toshiba DT01ACA100 1TB                                | 2         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 1.02%   |
| Seagate ST500LT012-1DG142 500GB                       | 2         | 1.02%   |
| Seagate ST500DM002-1BD142 500GB                       | 2         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 2         | 1.02%   |
| Seagate Backup+ Hub BK 4TB                            | 2         | 1.02%   |
| Samsung HD161GJ 160GB                                 | 2         | 1.02%   |
| Kingston SA400S37120G 120GB SSD                       | 2         | 1.02%   |
| Hitachi HTS545025B9A300 250GB                         | 2         | 1.02%   |
| Hitachi HDS721050CLA 500GB                            | 2         | 1.02%   |
| Unknown                                               | 2         | 1.02%   |
| XPG GAMMIX S11 Pro 512GB                              | 1         | 0.51%   |
| WDC WD800JD-08MSA1 80GB                               | 1         | 0.51%   |
| WDC WD7500BPVX-22JC3T0 752GB                          | 1         | 0.51%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 1         | 0.51%   |
| WDC WD5000BEVT-22ZAT0 500GB                           | 1         | 0.51%   |
| WDC WD5000AVVS-63ZWB0 500GB                           | 1         | 0.51%   |
| WDC WD5000AAKS-75V0A0 500GB                           | 1         | 0.51%   |
| WDC WD50 00LPLX-08ZNTT0 500GB                         | 1         | 0.51%   |
| WDC WD50 00LPCX-21VHAT0 500GB                         | 1         | 0.51%   |
| WDC WD3200BPVT-75ZEST0 320GB                          | 1         | 0.51%   |
| WDC WD2500AAKX-07U6AA0 250GB                          | 1         | 0.51%   |
| WDC WD2500AAJS-00L7A0 250GB                           | 1         | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 1         | 0.51%   |
| WDC WD1600BEVS-00VAT0 160GB                           | 1         | 0.51%   |
| WDC WD1600AAJS-08L7A0 160GB                           | 1         | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 1         | 0.51%   |
| WDC WD10SPCX-16KHST0 1TB                              | 1         | 0.51%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 32     | 25%     |
| WDC                 | 22        | 25     | 22%     |
| Hitachi             | 12        | 15     | 12%     |
| Toshiba             | 8         | 8      | 8%      |
| External            | 8         | 15     | 8%      |
| TO Exter            | 7         | 13     | 7%      |
| Samsung Electronics | 6         | 13     | 6%      |
| JMicron Technology  | 5         | 8      | 5%      |
| HGST                | 3         | 3      | 3%      |
| ASMedia             | 2         | 2      | 2%      |
| Fujitsu             | 1         | 2      | 1%      |
| Apple               | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 15     | 19.57%  |
| Kingston            | 5         | 6      | 10.87%  |
| Crucial             | 4         | 4      | 8.7%    |
| Intel               | 3         | 3      | 6.52%   |
| GOODRAM             | 3         | 6      | 6.52%   |
| Team                | 2         | 2      | 4.35%   |
| SPCC                | 2         | 3      | 4.35%   |
| SanDisk             | 2         | 2      | 4.35%   |
| Patriot             | 2         | 2      | 4.35%   |
| A-DATA Technology   | 2         | 4      | 4.35%   |
| WDC                 | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| ORICO               | 1         | 1      | 2.17%   |
| OCZ                 | 1         | 1      | 2.17%   |
| Netac               | 1         | 1      | 2.17%   |
| Micron Technology   | 1         | 1      | 2.17%   |
| KingDian            | 1         | 1      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |
| ASUS-JM             | 1         | 1      | 2.17%   |
| ASMedia             | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 70        | 137    | 47.3%   |
| SSD     | 40        | 59     | 27.03%  |
| NVMe    | 24        | 32     | 16.22%  |
| MMC     | 13        | 13     | 8.78%   |
| Unknown | 1         | 1      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 143    | 61.81%  |
| NVMe | 24        | 32     | 16.67%  |
| SAS  | 18        | 54     | 12.5%   |
| MMC  | 13        | 13     | 9.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 119    | 59.84%  |
| 0.51-1.0   | 32        | 50     | 26.23%  |
| 1.01-2.0   | 14        | 22     | 11.48%  |
| 3.01-4.0   | 2         | 4      | 1.64%   |
| 2.01-3.0   | 1         | 1      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 24.35%  |
| 501-1000       | 20        | 17.39%  |
| 251-500        | 18        | 15.65%  |
| More than 3000 | 11        | 9.57%   |
| 1-20           | 10        | 8.7%    |
| 21-50          | 9         | 7.83%   |
| 2001-3000      | 7         | 6.09%   |
| 1001-2000      | 5         | 4.35%   |
| 51-100         | 5         | 4.35%   |
| Unknown        | 2         | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 39.83%  |
| 21-50          | 19        | 16.1%   |
| 501-1000       | 11        | 9.32%   |
| 251-500        | 10        | 8.47%   |
| 101-250        | 7         | 5.93%   |
| 1001-2000      | 7         | 5.93%   |
| 51-100         | 7         | 5.93%   |
| 2001-3000      | 5         | 4.24%   |
| More than 3000 | 3         | 2.54%   |
| Unknown        | 2         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 5.56%   |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1         | 1      | 5.56%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 5.56%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 5.56%   |
| WDC WD10SPCX-16KHST0 1TB                            | 1         | 1      | 5.56%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 5.56%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 5.56%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 5.56%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 5.56%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 5.56%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1         | 1      | 5.56%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 5.56%   |
| Intel SSDSC2CW060A3 64GB                            | 1         | 1      | 5.56%   |
| ASMedia ASMT1153E 320GB                             | 1         | 1      | 5.56%   |
| Unknown                                             | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 33.33%  |
| Seagate             | 6         | 6      | 33.33%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| ASMedia             | 1         | 1      | 5.56%   |
| Unknown             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 40%     |
| Seagate             | 6         | 6      | 40%     |
| Toshiba             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| ASMedia             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 83.33%  |
| SSD  | 3         | 3      | 16.67%  |

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
| Detected | 56        | 146    | 44.09%  |
| Works    | 53        | 78     | 41.73%  |
| Malfunc  | 18        | 18     | 14.17%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 77        | 59.69%  |
| AMD                          | 17        | 13.18%  |
| Samsung Electronics          | 9         | 6.98%   |
| Silicon Motion               | 4         | 3.1%    |
| SanDisk                      | 4         | 3.1%    |
| Nvidia                       | 3         | 2.33%   |
| SK hynix                     | 2         | 1.55%   |
| Phison Electronics           | 2         | 1.55%   |
| VIA Technologies             | 1         | 0.78%   |
| Shenzhen Longsys Electronics | 1         | 0.78%   |
| Seagate Technology           | 1         | 0.78%   |
| Promise Technology           | 1         | 0.78%   |
| Micron/Crucial Technology    | 1         | 0.78%   |
| Marvell Technology Group     | 1         | 0.78%   |
| LSI Logic / Symbios Logic    | 1         | 0.78%   |
| Kingston Technology Company  | 1         | 0.78%   |
| JMicron Technology           | 1         | 0.78%   |
| ASMedia Technology           | 1         | 0.78%   |
| ADATA Technology             | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 12        | 7.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 6         | 3.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5         | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 5         | 3.25%   |
| Intel Comet Lake SATA AHCI Controller                                         | 5         | 3.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 5         | 3.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 5         | 3.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 4         | 2.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 4         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 4         | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 4         | 2.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 3         | 1.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 3         | 1.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 3         | 1.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 3         | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3         | 1.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.3%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 1.3%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 2         | 1.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                       | 2         | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 1.3%    |
| Nvidia MCP61 SATA Controller                                                  | 2         | 1.3%    |
| Nvidia MCP61 IDE                                                              | 2         | 1.3%    |
| Intel SATA Controller [RAID Mode]                                             | 2         | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.3%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 2         | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 2         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 2         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 1.3%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 2         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 2         | 1.3%    |
| AMD 400 Series Chipset SATA Controller                                        | 2         | 1.3%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 0.65%   |
| VIA VT8237A SATA 2-Port Controller                                            | 1         | 0.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.65%   |
| Silicon Motion Non-Volatile memory controller                                 | 1         | 0.65%   |
| Shenzhen Longsys Lexar NM610 PRO NVME SSD (DRAM-less)                         | 1         | 0.65%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 79        | 58.09%  |
| IDE  | 28        | 20.59%  |
| NVMe | 23        | 16.91%  |
| RAID | 4         | 2.94%   |
| SAS  | 1         | 0.74%   |
| SCSI | 1         | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 90        | 78.95%  |
| AMD    | 24        | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 3.51%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.75%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 2         | 1.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.75%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.75%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 2         | 1.75%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 1.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 1.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.75%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.75%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.75%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 1.75%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.75%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1         | 0.88%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 0.88%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.88%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.88%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.88%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 0.88%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.88%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.88%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 1         | 0.88%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 0.88%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.88%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.88%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 0.88%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 0.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.88%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.88%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 30        | 26.32%  |
| Intel Celeron           | 13        | 11.4%   |
| Intel Atom              | 10        | 8.77%   |
| Intel Core i7           | 8         | 7.02%   |
| Intel Core 2 Duo        | 7         | 6.14%   |
| Intel Core i3           | 6         | 5.26%   |
| Intel Pentium Dual-Core | 3         | 2.63%   |
| Intel Core 2            | 3         | 2.63%   |
| AMD Ryzen 7             | 3         | 2.63%   |
| Other                   | 2         | 1.75%   |
| Intel Xeon              | 2         | 1.75%   |
| Intel Pentium           | 2         | 1.75%   |
| Intel Core 2 Quad       | 2         | 1.75%   |
| AMD Ryzen 5             | 2         | 1.75%   |
| AMD Ryzen 3             | 2         | 1.75%   |
| AMD A6                  | 2         | 1.75%   |
| AMD A4                  | 2         | 1.75%   |
| Intel Pentium Gold      | 1         | 0.88%   |
| Intel Genuine           | 1         | 0.88%   |
| AMD Turion 64 X2 Mobile | 1         | 0.88%   |
| AMD Sempron             | 1         | 0.88%   |
| AMD Ryzen 9             | 1         | 0.88%   |
| AMD Ryzen 5 PRO         | 1         | 0.88%   |
| AMD PRO A8              | 1         | 0.88%   |
| AMD PRO A10             | 1         | 0.88%   |
| AMD Phenom II X6        | 1         | 0.88%   |
| AMD Phenom II X4        | 1         | 0.88%   |
| AMD C-50                | 1         | 0.88%   |
| AMD Athlon X2           | 1         | 0.88%   |
| AMD Athlon II X3        | 1         | 0.88%   |
| AMD Athlon II X2        | 1         | 0.88%   |
| AMD A8                  | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 45.61%  |
| 4      | 42        | 36.84%  |
| 1      | 9         | 7.89%   |
| 8      | 5         | 4.39%   |
| 6      | 4         | 3.51%   |
| 12     | 1         | 0.88%   |
| 3      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 114       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 52.63%  |
| 2      | 54        | 47.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 95.61%  |
| 32-bit         | 5         | 4.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 34.78%  |
| 0x406c4    | 5         | 4.35%   |
| 0x306a9    | 5         | 4.35%   |
| 0x1067a    | 5         | 4.35%   |
| 0x206a7    | 4         | 3.48%   |
| 0x6f2      | 3         | 2.61%   |
| 0x30678    | 3         | 2.61%   |
| 0x20655    | 3         | 2.61%   |
| 0x20652    | 3         | 2.61%   |
| 0x0600611a | 3         | 2.61%   |
| 0x806ec    | 2         | 1.74%   |
| 0x506e3    | 2         | 1.74%   |
| 0x406c3    | 2         | 1.74%   |
| 0x306c3    | 2         | 1.74%   |
| 0x106ca    | 2         | 1.74%   |
| 0x106c2    | 2         | 1.74%   |
| 0x10676    | 2         | 1.74%   |
| 0x08108109 | 2         | 1.74%   |
| 0xa0653    | 1         | 0.87%   |
| 0x806ea    | 1         | 0.87%   |
| 0x806e9    | 1         | 0.87%   |
| 0x706a8    | 1         | 0.87%   |
| 0x706a1    | 1         | 0.87%   |
| 0x6fd      | 1         | 0.87%   |
| 0x6fb      | 1         | 0.87%   |
| 0x406f1    | 1         | 0.87%   |
| 0x40651    | 1         | 0.87%   |
| 0x206d7    | 1         | 0.87%   |
| 0x106e5    | 1         | 0.87%   |
| 0x0a50000d | 1         | 0.87%   |
| 0x0a201016 | 1         | 0.87%   |
| 0x08701021 | 1         | 0.87%   |
| 0x08608103 | 1         | 0.87%   |
| 0x08600106 | 1         | 0.87%   |
| 0x08001138 | 1         | 0.87%   |
| 0x0700010f | 1         | 0.87%   |
| 0x06006705 | 1         | 0.87%   |
| 0x06001119 | 1         | 0.87%   |
| 0x05000029 | 1         | 0.87%   |
| 0x03000027 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 13        | 11.4%   |
| Silvermont      | 11        | 9.65%   |
| IvyBridge       | 11        | 9.65%   |
| Penryn          | 9         | 7.89%   |
| SandyBridge     | 7         | 6.14%   |
| Core            | 7         | 6.14%   |
| Westmere        | 6         | 5.26%   |
| Skylake         | 6         | 5.26%   |
| Bonnell         | 6         | 5.26%   |
| K10             | 5         | 4.39%   |
| Goldmont plus   | 4         | 3.51%   |
| Excavator       | 4         | 3.51%   |
| Haswell         | 3         | 2.63%   |
| Zen+            | 2         | 1.75%   |
| Zen 3           | 2         | 1.75%   |
| Zen 2           | 2         | 1.75%   |
| Zen             | 2         | 1.75%   |
| CometLake       | 2         | 1.75%   |
| Unknown         | 2         | 1.75%   |
| TigerLake       | 1         | 0.88%   |
| Piledriver      | 1         | 0.88%   |
| P6              | 1         | 0.88%   |
| Nehalem         | 1         | 0.88%   |
| K8 Hammer       | 1         | 0.88%   |
| K8 & K10 hybrid | 1         | 0.88%   |
| K10 Llano       | 1         | 0.88%   |
| Jaguar          | 1         | 0.88%   |
| Broadwell       | 1         | 0.88%   |
| Bobcat          | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 72        | 61.02%  |
| AMD              | 27        | 22.88%  |
| Nvidia           | 18        | 15.25%  |
| VIA Technologies | 1         | 0.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 5.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 3.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 3.13%   |
| Intel HD Graphics 530                                                                    | 4         | 3.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 3.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.34%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 2.34%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.56%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.56%   |
| Intel HD Graphics 630                                                                    | 2         | 1.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.56%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.56%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.56%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.78%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.78%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.78%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.78%   |
| Nvidia GM107GL [Quadro K1200]                                                            | 1         | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.78%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 0.78%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.78%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.78%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1         | 0.78%   |
| Nvidia G96CM [GeForce 9650M GT]                                                          | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 57.02%  |
| 1 x AMD        | 24        | 21.05%  |
| 1 x Nvidia     | 16        | 14.04%  |
| 2 x Intel      | 4         | 3.51%   |
| 2 x AMD        | 2         | 1.75%   |
| Intel + Nvidia | 2         | 1.75%   |
| 1 x VIA        | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 106       | 92.98%  |
| Proprietary | 4         | 3.51%   |
| Unknown     | 4         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 71.55%  |
| 0.01-0.5   | 15        | 12.93%  |
| 0.51-1.0   | 8         | 6.9%    |
| 1.01-2.0   | 5         | 4.31%   |
| 3.01-4.0   | 3         | 2.59%   |
| 7.01-8.0   | 2         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 14.55%  |
| LG Display              | 11        | 10%     |
| AU Optronics            | 11        | 10%     |
| Sceptre Tech            | 10        | 9.09%   |
| Chimei Innolux          | 8         | 7.27%   |
| BOE                     | 7         | 6.36%   |
| Dell                    | 6         | 5.45%   |
| Goldstar                | 5         | 4.55%   |
| AOC                     | 4         | 3.64%   |
| Acer                    | 4         | 3.64%   |
| CPT                     | 3         | 2.73%   |
| BenQ                    | 3         | 2.73%   |
| Medion                  | 2         | 1.82%   |
| Lenovo                  | 2         | 1.82%   |
| Hewlett-Packard         | 2         | 1.82%   |
| Apple                   | 2         | 1.82%   |
| Unknown                 | 1         | 0.91%   |
| Toshiba                 | 1         | 0.91%   |
| Sony                    | 1         | 0.91%   |
| RTK                     | 1         | 0.91%   |
| Philips                 | 1         | 0.91%   |
| PANDA                   | 1         | 0.91%   |
| LG Philips              | 1         | 0.91%   |
| JCH                     | 1         | 0.91%   |
| Insignia                | 1         | 0.91%   |
| Hitachi                 | 1         | 0.91%   |
| HannStar                | 1         | 0.91%   |
| Chi Mei Optoelectronics | 1         | 0.91%   |
| ASUSTek Computer        | 1         | 0.91%   |
| Ancor Communications    | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch        | 7         | 6.14%   |
| Sceptre Tech Sceptre H43 SPT1104 1920x1080 575x323mm 26.0-inch        | 3         | 2.63%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.88%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 0.88%   |
| Sony TV SNY2A03 1920x1080                                             | 1         | 0.88%   |
| Samsung Electronics T22C350 SAM0AB7 1920x1080 477x268mm 21.5-inch     | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 0.88%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1         | 0.88%   |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1         | 0.88%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch     | 1         | 0.88%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch     | 1         | 0.88%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 0.88%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 0.88%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.88%   |
| RTK CPL AIO PC RTK2482 1920x1080 509x286mm 23.0-inch                  | 1         | 0.88%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.88%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 0.88%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1         | 0.88%   |
| Medion MD 20310 MED3645 1920x1080 521x293mm 23.5-inch                 | 1         | 0.88%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 0.88%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.88%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0555 2880x1920 274x183mm 13.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch           | 1         | 0.88%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch               | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 39.64%  |
| 1366x768 (WXGA)    | 24        | 21.62%  |
| 3840x2160 (4K)     | 8         | 7.21%   |
| 1920x1200 (WUXGA)  | 4         | 3.6%    |
| 1600x900 (HD+)     | 4         | 3.6%    |
| 1280x800 (WXGA)    | 4         | 3.6%    |
| 1024x600           | 4         | 3.6%    |
| 1680x1050 (WSXGA+) | 3         | 2.7%    |
| 1440x900 (WXGA+)   | 3         | 2.7%    |
| 1280x1024 (SXGA)   | 3         | 2.7%    |
| 1920x540           | 2         | 1.8%    |
| 3840x1080          | 1         | 0.9%    |
| 2880x1920          | 1         | 0.9%    |
| 2288x1287          | 1         | 0.9%    |
| 1400x1050          | 1         | 0.9%    |
| 1360x768           | 1         | 0.9%    |
| 1280x960           | 1         | 0.9%    |
| 1024x768 (XGA)     | 1         | 0.9%    |
| Unknown            | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 19.64%  |
| 13      | 12        | 10.71%  |
| 23      | 9         | 8.04%   |
| 17      | 9         | 8.04%   |
| 32      | 8         | 7.14%   |
| 24      | 7         | 6.25%   |
| 21      | 5         | 4.46%   |
| 14      | 5         | 4.46%   |
| 27      | 4         | 3.57%   |
| 11      | 4         | 3.57%   |
| 10      | 4         | 3.57%   |
| 26      | 3         | 2.68%   |
| 20      | 3         | 2.68%   |
| 72      | 2         | 1.79%   |
| 48      | 2         | 1.79%   |
| 18      | 2         | 1.79%   |
| 16      | 2         | 1.79%   |
| 142     | 1         | 0.89%   |
| 74      | 1         | 0.89%   |
| 54      | 1         | 0.89%   |
| 39      | 1         | 0.89%   |
| 31      | 1         | 0.89%   |
| 22      | 1         | 0.89%   |
| 19      | 1         | 0.89%   |
| 12      | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 35        | 31.25%  |
| 501-600        | 22        | 19.64%  |
| 201-300        | 17        | 15.18%  |
| 401-500        | 12        | 10.71%  |
| 701-800        | 8         | 7.14%   |
| 351-400        | 7         | 6.25%   |
| 1501-2000      | 3         | 2.68%   |
| 1001-1500      | 3         | 2.68%   |
| 601-700        | 2         | 1.79%   |
| More than 2000 | 1         | 0.89%   |
| 801-900        | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 81        | 75%     |
| 16/10   | 16        | 14.81%  |
| 5/4     | 3         | 2.78%   |
| 4/3     | 3         | 2.78%   |
| 1.96    | 2         | 1.85%   |
| 3/2     | 1         | 0.93%   |
| 1.00    | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 20.54%  |
| 201-250        | 15        | 13.39%  |
| 81-90          | 11        | 9.82%   |
| 351-500        | 9         | 8.04%   |
| 251-300        | 7         | 6.25%   |
| 151-200        | 7         | 6.25%   |
| 121-130        | 6         | 5.36%   |
| More than 1000 | 5         | 4.46%   |
| 71-80          | 5         | 4.46%   |
| 141-150        | 5         | 4.46%   |
| 51-60          | 4         | 3.57%   |
| 41-50          | 4         | 3.57%   |
| 301-350        | 4         | 3.57%   |
| 501-1000       | 3         | 2.68%   |
| 61-70          | 1         | 0.89%   |
| 131-140        | 1         | 0.89%   |
| 91-100         | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 39        | 35.45%  |
| 121-160       | 31        | 28.18%  |
| 101-120       | 30        | 27.27%  |
| 1-50          | 7         | 6.36%   |
| More than 240 | 1         | 0.91%   |
| 161-240       | 1         | 0.91%   |
| Unknown       | 1         | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 90.35%  |
| 2     | 8         | 7.02%   |
| 0     | 3         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 53        | 33.97%  |
| Realtek Semiconductor    | 46        | 29.49%  |
| Qualcomm Atheros         | 15        | 9.62%   |
| Broadcom                 | 9         | 5.77%   |
| Marvell Technology Group | 6         | 3.85%   |
| TP-Link                  | 4         | 2.56%   |
| Ralink Technology        | 4         | 2.56%   |
| Broadcom Limited         | 4         | 2.56%   |
| Nvidia                   | 3         | 1.92%   |
| Ralink                   | 2         | 1.28%   |
| VIA Technologies         | 1         | 0.64%   |
| Samsung Electronics      | 1         | 0.64%   |
| Qualcomm                 | 1         | 0.64%   |
| OPPO Electronics         | 1         | 0.64%   |
| NetGear                  | 1         | 0.64%   |
| MediaTek                 | 1         | 0.64%   |
| Edimax Technology        | 1         | 0.64%   |
| D-Link System            | 1         | 0.64%   |
| D-Link                   | 1         | 0.64%   |
| ASUSTek Computer         | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 30        | 16.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 4.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 4.35%   |
| Intel Wireless 7265                                                     | 4         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 3         | 1.63%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.63%   |
| Intel Wireless 8260                                                     | 3         | 1.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.63%   |
| Intel Ethernet Connection (5) I219-LM                                   | 3         | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.09%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 1.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.09%   |
| Nvidia MCP61 Ethernet                                                   | 2         | 1.09%   |
| Intel Wireless 7260                                                     | 2         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.09%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.09%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 2         | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.54%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.54%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 43.02%  |
| Realtek Semiconductor    | 15        | 17.44%  |
| Qualcomm Atheros         | 12        | 13.95%  |
| TP-Link                  | 4         | 4.65%   |
| Ralink Technology        | 4         | 4.65%   |
| Broadcom                 | 3         | 3.49%   |
| Ralink                   | 2         | 2.33%   |
| Broadcom Limited         | 2         | 2.33%   |
| NetGear                  | 1         | 1.16%   |
| MediaTek                 | 1         | 1.16%   |
| Marvell Technology Group | 1         | 1.16%   |
| Edimax Technology        | 1         | 1.16%   |
| D-Link System            | 1         | 1.16%   |
| D-Link                   | 1         | 1.16%   |
| ASUSTek Computer         | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 4         | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 3.49%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 3.49%   |
| Intel Wireless 8260                                                           | 3         | 3.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 3.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 3.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 2.33%   |
| Intel Wireless 7260                                                           | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 2.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 1.16%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 1.16%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.16%   |
| Ralink RT3072 Wireless Adapter                                                | 1         | 1.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.16%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 1.16%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.16%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                             | 1         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 39.8%   |
| Intel                    | 32        | 32.65%  |
| Broadcom                 | 7         | 7.14%   |
| Qualcomm Atheros         | 6         | 6.12%   |
| Marvell Technology Group | 5         | 5.1%    |
| Nvidia                   | 3         | 3.06%   |
| Broadcom Limited         | 2         | 2.04%   |
| VIA Technologies         | 1         | 1.02%   |
| Samsung Electronics      | 1         | 1.02%   |
| Qualcomm                 | 1         | 1.02%   |
| OPPO Electronics         | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30        | 30.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 9.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 8.16%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 3.06%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 3.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 2.04%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 2.04%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 2.04%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.04%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2         | 2.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.02%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.02%   |
| Qualcomm Airtel 4G                                                     | 1         | 1.02%   |
| OPPO OnePlus Nord 4                                                    | 1         | 1.02%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 1.02%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.02%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.02%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.02%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.02%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 1.02%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.02%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 1.02%   |
| Intel 82578DC Gigabit Network Connection                               | 1         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.02%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.02%   |
| Intel 82566DM Gigabit Network Connection                               | 1         | 1.02%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.02%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 1         | 1.02%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 95        | 53.98%  |
| WiFi     | 81        | 46.02%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 52.1%   |
| Ethernet | 57        | 47.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 56        | 49.12%  |
| 2     | 54        | 47.37%  |
| 0     | 3         | 2.63%   |
| 3     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 75.86%  |
| Yes  | 28        | 24.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 44.83%  |
| Broadcom                        | 8         | 13.79%  |
| Realtek Semiconductor           | 4         | 6.9%    |
| IMC Networks                    | 4         | 6.9%    |
| Qualcomm Atheros Communications | 2         | 3.45%   |
| Foxconn / Hon Hai               | 2         | 3.45%   |
| Cambridge Silicon Radio         | 2         | 3.45%   |
| Apple                           | 2         | 3.45%   |
| Taiyo Yuden                     | 1         | 1.72%   |
| Realtek                         | 1         | 1.72%   |
| Ralink                          | 1         | 1.72%   |
| Marvell Semiconductor           | 1         | 1.72%   |
| Hewlett-Packard                 | 1         | 1.72%   |
| Dynex                           | 1         | 1.72%   |
| Dell                            | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 13        | 22.41%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 6         | 10.34%  |
| Realtek  Bluetooth 4.2 Adapter                           | 3         | 5.17%   |
| IMC Networks Bluetooth Radio                             | 3         | 5.17%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 3.45%   |
| Intel AX201 Bluetooth                                    | 2         | 3.45%   |
| Intel AX200 Bluetooth                                    | 2         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 3.45%   |
| Broadcom BCM2045 Bluetooth                               | 2         | 3.45%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 1.72%   |
| Realtek RTL8723B Bluetooth                               | 1         | 1.72%   |
| Realtek Bluetooth Radio                                  | 1         | 1.72%   |
| Ralink RT3290 Bluetooth                                  | 1         | 1.72%   |
| Qualcomm Atheros  Bluetooth Device                       | 1         | 1.72%   |
| Qualcomm Atheros Bluetooth                               | 1         | 1.72%   |
| Marvell Bluetooth and Wireless LAN Composite             | 1         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1         | 1.72%   |
| IMC Networks Bluetooth Module                            | 1         | 1.72%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller          | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1         | 1.72%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 1.72%   |
| Dell Wireless 365 Bluetooth                              | 1         | 1.72%   |
| Broadcom HP Portable SoftSailing                         | 1         | 1.72%   |
| Broadcom Bluetooth 2.1 Device                            | 1         | 1.72%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1         | 1.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 1.72%   |
| Broadcom BCM2070 Bluetooth Device                        | 1         | 1.72%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 1         | 1.72%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                      | 1         | 1.72%   |
| Apple Bluetooth HCI                                      | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 82        | 57.34%  |
| AMD                 | 28        | 19.58%  |
| Nvidia              | 15        | 10.49%  |
| Tenx Technology     | 9         | 6.29%   |
| Focusrite-Novation  | 2         | 1.4%    |
| C-Media Electronics | 2         | 1.4%    |
| VIA Technologies    | 1         | 0.7%    |
| Plantronics         | 1         | 0.7%    |
| Native Instruments  | 1         | 0.7%    |
| Creative Labs       | 1         | 0.7%    |
| ASUSTek Computer    | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.21%   |
| Tenx Technology USB AUDIO                                                                         | 9         | 5.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 3.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.11%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 5         | 3.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.48%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.86%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.24%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.24%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 1.24%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.24%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.24%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.24%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 1.24%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.62%   |
| Plantronics USB DSP v4 Audio Interface                                                            | 1         | 0.62%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 21.11%  |
| Unknown             | 17        | 18.89%  |
| SK hynix            | 12        | 13.33%  |
| Micron Technology   | 7         | 7.78%   |
| Kingston            | 7         | 7.78%   |
| G.Skill             | 3         | 3.33%   |
| Crucial             | 3         | 3.33%   |
| Corsair             | 3         | 3.33%   |
| Nanya Technology    | 2         | 2.22%   |
| GOODRAM             | 2         | 2.22%   |
| ff                  | 2         | 2.22%   |
| Elpida              | 2         | 2.22%   |
| 4ea5                | 2         | 2.22%   |
| 48spaces            | 2         | 2.22%   |
| Unifosa             | 1         | 1.11%   |
| Toshiba             | 1         | 1.11%   |
| Team                | 1         | 1.11%   |
| Ramaxel Technology  | 1         | 1.11%   |
| High Bridge         | 1         | 1.11%   |
| Avant               | 1         | 1.11%   |
| Unknown             | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                               | 2         | 2.08%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                    | 2         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 2         | 2.08%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s                     | 2         | 2.08%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                           | 2         | 2.08%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 2.08%   |
| Unknown RAM Module 8GB SODIMM DDR3                                        | 1         | 1.04%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                      | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                               | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 266MT/s                                | 1         | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                                 | 1         | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 1.04%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                       | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                                | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                                  | 1         | 1.04%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 1         | 1.04%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                         | 1         | 1.04%   |
| Toshiba RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s                      | 1         | 1.04%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.04%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.04%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s                      | 1         | 1.04%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                      | 1         | 1.04%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM 1067MT/s                         | 1         | 1.04%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.04%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                                  | 1         | 1.04%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s                       | 1         | 1.04%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 1.04%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 1         | 1.04%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.04%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1333MT/s                     | 1         | 1.04%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 36        | 47.37%  |
| DDR4    | 18        | 23.68%  |
| DDR2    | 6         | 7.89%   |
| Unknown | 5         | 6.58%   |
| SDRAM   | 4         | 5.26%   |
| LPDDR3  | 3         | 3.95%   |
| LPDDR4  | 2         | 2.63%   |
| DRAM    | 1         | 1.32%   |
| DDR     | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 55.41%  |
| DIMM         | 26        | 35.14%  |
| Unknown      | 5         | 6.76%   |
| Row Of Chips | 2         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 28        | 32.18%  |
| 8192  | 20        | 22.99%  |
| 4096  | 20        | 22.99%  |
| 1024  | 9         | 10.34%  |
| 16384 | 8         | 9.2%    |
| 32768 | 1         | 1.15%   |
| 256   | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 15        | 18.29%  |
| 1333    | 12        | 14.63%  |
| 3200    | 7         | 8.54%   |
| 2667    | 7         | 8.54%   |
| 800     | 6         | 7.32%   |
| 2400    | 5         | 6.1%    |
| Unknown | 4         | 4.88%   |
| 1867    | 3         | 3.66%   |
| 1334    | 3         | 3.66%   |
| 1066    | 3         | 3.66%   |
| 667     | 3         | 3.66%   |
| 2133    | 2         | 2.44%   |
| 4199    | 1         | 1.22%   |
| 3800    | 1         | 1.22%   |
| 3666    | 1         | 1.22%   |
| 2666    | 1         | 1.22%   |
| 2048    | 1         | 1.22%   |
| 1866    | 1         | 1.22%   |
| 1800    | 1         | 1.22%   |
| 1639    | 1         | 1.22%   |
| 1067    | 1         | 1.22%   |
| 533     | 1         | 1.22%   |
| 400     | 1         | 1.22%   |
| 266     | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 23.21%  |
| Microdia                               | 6         | 10.71%  |
| Suyin                                  | 4         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.14%   |
| Bison Electronics                      | 4         | 7.14%   |
| Alcor Micro                            | 4         | 7.14%   |
| Z-Star Microelectronics                | 3         | 5.36%   |
| Quanta                                 | 3         | 5.36%   |
| Sunplus Innovation Technology          | 2         | 3.57%   |
| Realtek Semiconductor                  | 2         | 3.57%   |
| Logitech                               | 2         | 3.57%   |
| Syntek                                 | 1         | 1.79%   |
| Sonix Technology                       | 1         | 1.79%   |
| Samsung Electronics                    | 1         | 1.79%   |
| Ricoh                                  | 1         | 1.79%   |
| Microsoft                              | 1         | 1.79%   |
| JOURIST-DC80                           | 1         | 1.79%   |
| IMC Networks                           | 1         | 1.79%   |
| Guillemot                              | 1         | 1.79%   |
| Apple                                  | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 2         | 3.51%   |
| Quanta HP TrueVision HD Camera                              | 2         | 3.51%   |
| Chicony HD WebCam                                           | 2         | 3.51%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 3.51%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.75%   |
| Syntek Integrated Camera                                    | 1         | 1.75%   |
| Suyin USB2.0 UVC 1.3M WebCam                                | 1         | 1.75%   |
| Suyin HP Truevision HD                                      | 1         | 1.75%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 1.75%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.75%   |
| Sunplus Integrated Webcam                                   | 1         | 1.75%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.75%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 1.75%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 1.75%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.75%   |
| Realtek Integrated Webcam                                   | 1         | 1.75%   |
| Realtek HP Truevision HD                                    | 1         | 1.75%   |
| Quanta HP 5M Camera                                         | 1         | 1.75%   |
| Quanta HD User Facing                                       | 1         | 1.75%   |
| Microsoft LifeCam Cinema                                    | 1         | 1.75%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.75%   |
| Microdia Lenovo EasyCamera                                  | 1         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.75%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.75%   |
| Microdia ASUS USB2.0 Camera                                 | 1         | 1.75%   |
| Logitech Webcam C270                                        | 1         | 1.75%   |
| Logitech QuickCam Notebook Pro                              | 1         | 1.75%   |
| JOURIST-DC80 JOURIST-DC80                                   | 1         | 1.75%   |
| IMC Networks VGA UVC WebCam                                 | 1         | 1.75%   |
| Guillemot Hercules Dualpix Exchange                         | 1         | 1.75%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.75%   |
| Chicony thinkpad t430s camera                               | 1         | 1.75%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.75%   |
| Chicony HP Wide Vision HD Camera                            | 1         | 1.75%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 1.75%   |
| Chicony HP TrueVision HD Camera                             | 1         | 1.75%   |
| Chicony HP Truevision HD                                    | 1         | 1.75%   |
| Chicony HP Integrated Webcam                                | 1         | 1.75%   |
| Chicony HP HD Webcam                                        | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| AuthenTec                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 14.29%  |
| Validity Sensors VFS491                    | 1         | 14.29%  |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader      | 1         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device        | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 14.29%  |
| AuthenTec AES1600                          | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader                                          | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 81        | 71.05%  |
| 1     | 27        | 23.68%  |
| 2     | 5         | 4.39%   |
| 3     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 12        | 29.27%  |
| Net/wireless          | 8         | 19.51%  |
| Fingerprint reader    | 7         | 17.07%  |
| Multimedia controller | 6         | 14.63%  |
| Chipcard              | 2         | 4.88%   |
| Bluetooth             | 2         | 4.88%   |
| Unassigned class      | 1         | 2.44%   |
| Net/ethernet          | 1         | 2.44%   |
| Card reader           | 1         | 2.44%   |
| Camera                | 1         | 2.44%   |

