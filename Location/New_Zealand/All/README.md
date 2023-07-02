Linux in New Zealand - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/New_Zealand/Desktop/README.md) and [notebooks](/Location/New_Zealand/Notebook/README.md).

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

Total: 1133

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [8086d33203](https://linux-hardware.org/?probe=8086d33203) | Jun 29, 2023 |
| Acer          | EG43M                       | Desktop     | [e6d28dd1e5](https://linux-hardware.org/?probe=e6d28dd1e5) | Jun 28, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [15e9b561e3](https://linux-hardware.org/?probe=15e9b561e3) | Jun 27, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [34cf8e17a2](https://linux-hardware.org/?probe=34cf8e17a2) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [ef8876640e](https://linux-hardware.org/?probe=ef8876640e) | Jun 22, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [ea1fabfdc3](https://linux-hardware.org/?probe=ea1fabfdc3) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [207d5f5dbd](https://linux-hardware.org/?probe=207d5f5dbd) | Jun 17, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [744c44deca](https://linux-hardware.org/?probe=744c44deca) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [267010517a](https://linux-hardware.org/?probe=267010517a) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [c0f64d3436](https://linux-hardware.org/?probe=c0f64d3436) | Jun 03, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7a83a98e37](https://linux-hardware.org/?probe=7a83a98e37) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a78aee5f7f](https://linux-hardware.org/?probe=a78aee5f7f) | Jun 02, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [19043cab25](https://linux-hardware.org/?probe=19043cab25) | Jun 01, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [acc54fe70f](https://linux-hardware.org/?probe=acc54fe70f) | Jun 01, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcb29a1ec2](https://linux-hardware.org/?probe=dcb29a1ec2) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| Unknown       | T100                        | Desktop     | [c4a7218b7b](https://linux-hardware.org/?probe=c4a7218b7b) | May 18, 2023 |
| HP            | 8055                        | Desktop     | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| HP            | 8055                        | Desktop     | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [1b444989b5](https://linux-hardware.org/?probe=1b444989b5) | May 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Unknown       | T100                        | Desktop     | [977cdddeb1](https://linux-hardware.org/?probe=977cdddeb1) | May 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| Acer          | Aspire E1-521               | Notebook    | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [80b16a8567](https://linux-hardware.org/?probe=80b16a8567) | May 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| HP            | 81BB                        | All in one  | [8c50716d55](https://linux-hardware.org/?probe=8c50716d55) | May 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [c7308f11ce](https://linux-hardware.org/?probe=c7308f11ce) | May 06, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [088deaf386](https://linux-hardware.org/?probe=088deaf386) | May 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [057eeed322](https://linux-hardware.org/?probe=057eeed322) | May 03, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [69d95c7c30](https://linux-hardware.org/?probe=69d95c7c30) | May 02, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [864b1a4325](https://linux-hardware.org/?probe=864b1a4325) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | Notebook    | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| HP            | 1489                        | All in one  | [ebd3760355](https://linux-hardware.org/?probe=ebd3760355) | Apr 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| HP            | 1489                        | All in one  | [1058adaefd](https://linux-hardware.org/?probe=1058adaefd) | Apr 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [eeed9900b0](https://linux-hardware.org/?probe=eeed9900b0) | Apr 23, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [9896e8b804](https://linux-hardware.org/?probe=9896e8b804) | Apr 22, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [78c8b8578f](https://linux-hardware.org/?probe=78c8b8578f) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [41e83eedd0](https://linux-hardware.org/?probe=41e83eedd0) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ec36fe087a](https://linux-hardware.org/?probe=ec36fe087a) | Apr 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [094563419e](https://linux-hardware.org/?probe=094563419e) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [488dc3a686](https://linux-hardware.org/?probe=488dc3a686) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [bf1af4af46](https://linux-hardware.org/?probe=bf1af4af46) | Mar 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c239e06998](https://linux-hardware.org/?probe=c239e06998) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| Pegatron      | Maureen                     | Desktop     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Google        | Swanky                      | Notebook    | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [7f46837f94](https://linux-hardware.org/?probe=7f46837f94) | Mar 28, 2023 |
| HP            | ProBook 6550b               | Notebook    | [4629264a10](https://linux-hardware.org/?probe=4629264a10) | Mar 27, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ddc916615](https://linux-hardware.org/?probe=8ddc916615) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [7dc2dc172d](https://linux-hardware.org/?probe=7dc2dc172d) | Mar 18, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [67d6333f85](https://linux-hardware.org/?probe=67d6333f85) | Mar 15, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [a1fd7807c6](https://linux-hardware.org/?probe=a1fd7807c6) | Mar 15, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [0185de4fa6](https://linux-hardware.org/?probe=0185de4fa6) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7e668b89fa](https://linux-hardware.org/?probe=7e668b89fa) | Mar 07, 2023 |
| HP            | Notebook                    | Notebook    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [b2b79c4b50](https://linux-hardware.org/?probe=b2b79c4b50) | Mar 06, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [b0b2b55298](https://linux-hardware.org/?probe=b0b2b55298) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [da5eea6a75](https://linux-hardware.org/?probe=da5eea6a75) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [64b2c8d5b9](https://linux-hardware.org/?probe=64b2c8d5b9) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ce2bc0c00d](https://linux-hardware.org/?probe=ce2bc0c00d) | Feb 27, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [69288a8011](https://linux-hardware.org/?probe=69288a8011) | Feb 24, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8ce6b54b09](https://linux-hardware.org/?probe=8ce6b54b09) | Feb 24, 2023 |
| MSI           | GE63VR 7RF                  | Notebook    | [b9aeb1ce18](https://linux-hardware.org/?probe=b9aeb1ce18) | Feb 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a6ebba79c9](https://linux-hardware.org/?probe=a6ebba79c9) | Feb 17, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [f9cfe6d485](https://linux-hardware.org/?probe=f9cfe6d485) | Feb 13, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [23a79acb25](https://linux-hardware.org/?probe=23a79acb25) | Feb 13, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [d1c4626fd3](https://linux-hardware.org/?probe=d1c4626fd3) | Feb 13, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [dfb8064df6](https://linux-hardware.org/?probe=dfb8064df6) | Feb 12, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [deff8d7055](https://linux-hardware.org/?probe=deff8d7055) | Feb 11, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [b11ab46e6e](https://linux-hardware.org/?probe=b11ab46e6e) | Feb 10, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [f0b972d056](https://linux-hardware.org/?probe=f0b972d056) | Feb 10, 2023 |
| Dell          | System XPS L702X            | Notebook    | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [0677b143ac](https://linux-hardware.org/?probe=0677b143ac) | Feb 07, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| Lenovo        | ThinkPad T480 20L5001KAU    | Notebook    | [4b7046e26c](https://linux-hardware.org/?probe=4b7046e26c) | Jan 30, 2023 |
| Acer          | E1-510                      | Notebook    | [659bb96537](https://linux-hardware.org/?probe=659bb96537) | Jan 29, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [93020dd688](https://linux-hardware.org/?probe=93020dd688) | Jan 28, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [9d0f65f90f](https://linux-hardware.org/?probe=9d0f65f90f) | Jan 24, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [3e7a2dabb5](https://linux-hardware.org/?probe=3e7a2dabb5) | Jan 24, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d27e517254](https://linux-hardware.org/?probe=d27e517254) | Jan 21, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [567ae7f5ba](https://linux-hardware.org/?probe=567ae7f5ba) | Jan 21, 2023 |
| DFI           | CR101-CST                   | Desktop     | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [e8d037a152](https://linux-hardware.org/?probe=e8d037a152) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dae35d1c18](https://linux-hardware.org/?probe=dae35d1c18) | Jan 19, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [983230429d](https://linux-hardware.org/?probe=983230429d) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | Notebook    | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [bcb3fca0a2](https://linux-hardware.org/?probe=bcb3fca0a2) | Jan 10, 2023 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [20bfe72df5](https://linux-hardware.org/?probe=20bfe72df5) | Jan 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | Notebook    | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [aaf51b3c3b](https://linux-hardware.org/?probe=aaf51b3c3b) | Jan 09, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [a5638d3bf2](https://linux-hardware.org/?probe=a5638d3bf2) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [ad72a0fad1](https://linux-hardware.org/?probe=ad72a0fad1) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | Notebook    | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [45c8b096c5](https://linux-hardware.org/?probe=45c8b096c5) | Jan 08, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [aa8715fc5c](https://linux-hardware.org/?probe=aa8715fc5c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| Dell          | Precision 7740              | Notebook    | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| HP            | 81BB                        | All in one  | [151d8bcaf3](https://linux-hardware.org/?probe=151d8bcaf3) | Jan 02, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [3f2b642eb0](https://linux-hardware.org/?probe=3f2b642eb0) | Jan 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | 17E2                        | Mini pc     | [8460664f2a](https://linux-hardware.org/?probe=8460664f2a) | Dec 28, 2022 |
| HP            | 3648h                       | Desktop     | [5b3a2d7e48](https://linux-hardware.org/?probe=5b3a2d7e48) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [03c35b7588](https://linux-hardware.org/?probe=03c35b7588) | Dec 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b88840bfdf](https://linux-hardware.org/?probe=b88840bfdf) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [534f769938](https://linux-hardware.org/?probe=534f769938) | Dec 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [56781f9824](https://linux-hardware.org/?probe=56781f9824) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [39bac65c16](https://linux-hardware.org/?probe=39bac65c16) | Dec 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Google        | Laser14                     | Notebook    | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [b333e1030f](https://linux-hardware.org/?probe=b333e1030f) | Dec 16, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d6d4bd4dcd](https://linux-hardware.org/?probe=d6d4bd4dcd) | Dec 14, 2022 |
| HP            | Pavilion dv6                | Notebook    | [2472ce95cb](https://linux-hardware.org/?probe=2472ce95cb) | Dec 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [e2ecbddf15](https://linux-hardware.org/?probe=e2ecbddf15) | Dec 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d9cc4844ac](https://linux-hardware.org/?probe=d9cc4844ac) | Dec 12, 2022 |
| HP            | 81BB                        | All in one  | [7efed40466](https://linux-hardware.org/?probe=7efed40466) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [967204fede](https://linux-hardware.org/?probe=967204fede) | Dec 09, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [5a6ebebd51](https://linux-hardware.org/?probe=5a6ebebd51) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [68004f52cd](https://linux-hardware.org/?probe=68004f52cd) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3912675c64](https://linux-hardware.org/?probe=3912675c64) | Dec 06, 2022 |
| HP            | 81BB                        | All in one  | [0cc2f0b745](https://linux-hardware.org/?probe=0cc2f0b745) | Dec 06, 2022 |
| HP            | 81BB                        | All in one  | [7d64b102e1](https://linux-hardware.org/?probe=7d64b102e1) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| HP            | 1495                        | Desktop     | [138b5bb823](https://linux-hardware.org/?probe=138b5bb823) | Dec 01, 2022 |
| Acer          | E1-510                      | Notebook    | [8aadf699f9](https://linux-hardware.org/?probe=8aadf699f9) | Nov 30, 2022 |
| Dell          | G7 7700                     | Notebook    | [16407c6485](https://linux-hardware.org/?probe=16407c6485) | Nov 27, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [dd85fb5c80](https://linux-hardware.org/?probe=dd85fb5c80) | Nov 22, 2022 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [462cb0ce56](https://linux-hardware.org/?probe=462cb0ce56) | Nov 21, 2022 |
| Google        | Swanky                      | Notebook    | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| HP            | 339A                        | Desktop     | [c995f831b8](https://linux-hardware.org/?probe=c995f831b8) | Nov 13, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2382574dbd](https://linux-hardware.org/?probe=2382574dbd) | Nov 12, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a41cabb3d6](https://linux-hardware.org/?probe=a41cabb3d6) | Nov 04, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a9a5e01e23](https://linux-hardware.org/?probe=a9a5e01e23) | Nov 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6702cb2ca7](https://linux-hardware.org/?probe=6702cb2ca7) | Oct 25, 2022 |
| Dell          | 0GXH08 A01                  | Server      | [f3c7a026b6](https://linux-hardware.org/?probe=f3c7a026b6) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [d5b2d74cd8](https://linux-hardware.org/?probe=d5b2d74cd8) | Oct 21, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [e39bc1af0b](https://linux-hardware.org/?probe=e39bc1af0b) | Oct 20, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [e939a5f236](https://linux-hardware.org/?probe=e939a5f236) | Oct 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [9998a32d98](https://linux-hardware.org/?probe=9998a32d98) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Dell          | Precision 3570              | Notebook    | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | Notebook    | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | Notebook    | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| Dell          | 0UW816 A00                  | Server      | [bd29b42f73](https://linux-hardware.org/?probe=bd29b42f73) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [9959a5f63d](https://linux-hardware.org/?probe=9959a5f63d) | Sep 17, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Google        | Snappy                      | Notebook    | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | MS-98H3                     | Desktop     | [41ad960dd6](https://linux-hardware.org/?probe=41ad960dd6) | Sep 06, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0e3f950f3f](https://linux-hardware.org/?probe=0e3f950f3f) | Sep 02, 2022 |
| The Wareho... | E2037                       | Notebook    | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | Notebook    | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [b41e0fcad5](https://linux-hardware.org/?probe=b41e0fcad5) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | Notebook    | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | Notebook    | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | Notebook    | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [92525ee03c](https://linux-hardware.org/?probe=92525ee03c) | Aug 17, 2022 |
| Lenovo        | 3190 SDK0T76530 WIN 3556... | Mini pc     | [766a8b38a6](https://linux-hardware.org/?probe=766a8b38a6) | Aug 16, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [4ff9f1893d](https://linux-hardware.org/?probe=4ff9f1893d) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [c9e9691195](https://linux-hardware.org/?probe=c9e9691195) | Aug 10, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [91438d7bdd](https://linux-hardware.org/?probe=91438d7bdd) | Aug 06, 2022 |
| Acer          | Spin SP513-51               | Convertible | [7531ebdab5](https://linux-hardware.org/?probe=7531ebdab5) | Aug 05, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [827883d38c](https://linux-hardware.org/?probe=827883d38c) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [773e4afb47](https://linux-hardware.org/?probe=773e4afb47) | Jul 30, 2022 |
| HP            | 2000                        | Notebook    | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | 8054                        | Desktop     | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| HP            | Notebook                    | Notebook    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| Intel         | STK1AW32SC H91596-307       | Desktop     | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| HP            | 3397                        | Desktop     | [83bdaea8fc](https://linux-hardware.org/?probe=83bdaea8fc) | Jul 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | Notebook    | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Intel         | NUC8i5INB K29935-402        | Mini pc     | [27d189d77f](https://linux-hardware.org/?probe=27d189d77f) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Lenovo        | 14w 81MQ0013AU              | Notebook    | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6d6b4c9d06](https://linux-hardware.org/?probe=6d6b4c9d06) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Gigabyte      | B460M D3H                   | Desktop     | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [3c8656100a](https://linux-hardware.org/?probe=3c8656100a) | Jun 29, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [97b8d855bd](https://linux-hardware.org/?probe=97b8d855bd) | Jun 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [9d9ae107c9](https://linux-hardware.org/?probe=9d9ae107c9) | Jun 25, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [788acf13f2](https://linux-hardware.org/?probe=788acf13f2) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [656f558626](https://linux-hardware.org/?probe=656f558626) | Jun 23, 2022 |
| HP            | 18E7                        | Desktop     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | Notebook    | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | Notebook    | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [874c85b694](https://linux-hardware.org/?probe=874c85b694) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bee7f3506c](https://linux-hardware.org/?probe=bee7f3506c) | May 29, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [512d3f18ce](https://linux-hardware.org/?probe=512d3f18ce) | May 28, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [af7e6249f0](https://linux-hardware.org/?probe=af7e6249f0) | May 27, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [44ceac3592](https://linux-hardware.org/?probe=44ceac3592) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | Notebook    | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | Notebook    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Alienware     | x17 R2                      | Notebook    | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| HP            | 1998                        | Desktop     | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6693954f79](https://linux-hardware.org/?probe=6693954f79) | May 07, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [c994128afd](https://linux-hardware.org/?probe=c994128afd) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [8888cb88d3](https://linux-hardware.org/?probe=8888cb88d3) | Apr 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5ec598483e](https://linux-hardware.org/?probe=5ec598483e) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| Dell          | Inspiron 7405 2n1           | Convertible | [9fa115228c](https://linux-hardware.org/?probe=9fa115228c) | Apr 11, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [1a7b7179f7](https://linux-hardware.org/?probe=1a7b7179f7) | Apr 10, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| HP            | 1790                        | Desktop     | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [a7ee814f3a](https://linux-hardware.org/?probe=a7ee814f3a) | Apr 02, 2022 |
| Dell          | Latitude 7480               | Notebook    | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | Notebook    | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [cf9c727b0d](https://linux-hardware.org/?probe=cf9c727b0d) | Mar 24, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| ASUSTek       | P5E                         | Desktop     | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [08dc6f6fe3](https://linux-hardware.org/?probe=08dc6f6fe3) | Mar 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [64f278889f](https://linux-hardware.org/?probe=64f278889f) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [5c169a1d32](https://linux-hardware.org/?probe=5c169a1d32) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [dfebbb508b](https://linux-hardware.org/?probe=dfebbb508b) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [26729d3227](https://linux-hardware.org/?probe=26729d3227) | Feb 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [c7a12417f1](https://linux-hardware.org/?probe=c7a12417f1) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cc2c71140b](https://linux-hardware.org/?probe=cc2c71140b) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [4d1d42c8cc](https://linux-hardware.org/?probe=4d1d42c8cc) | Feb 20, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [024513d4a8](https://linux-hardware.org/?probe=024513d4a8) | Feb 18, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9bc33ce91e](https://linux-hardware.org/?probe=9bc33ce91e) | Feb 16, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc420f69ce](https://linux-hardware.org/?probe=cc420f69ce) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [bf684bced7](https://linux-hardware.org/?probe=bf684bced7) | Feb 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [caf1721ebe](https://linux-hardware.org/?probe=caf1721ebe) | Feb 12, 2022 |
| ASUSTek       | K55A                        | Notebook    | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | Notebook    | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | Notebook    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [24bd4956b6](https://linux-hardware.org/?probe=24bd4956b6) | Feb 05, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | Notebook    | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d8ec503f66](https://linux-hardware.org/?probe=d8ec503f66) | Jan 21, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [b714fa4c7f](https://linux-hardware.org/?probe=b714fa4c7f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | Notebook    | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| MediaVue      | MV-890GX V1.2               | Desktop     | [201163da2f](https://linux-hardware.org/?probe=201163da2f) | Jan 16, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [11bf29bdd1](https://linux-hardware.org/?probe=11bf29bdd1) | Jan 16, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | Notebook    | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b05f843820](https://linux-hardware.org/?probe=b05f843820) | Jan 06, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [7f5484cd91](https://linux-hardware.org/?probe=7f5484cd91) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [51f97b7e46](https://linux-hardware.org/?probe=51f97b7e46) | Dec 25, 2021 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Google        | Kip                         | Notebook    | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3962478b0f](https://linux-hardware.org/?probe=3962478b0f) | Dec 19, 2021 |
| Colorful T... | BATTLE-AX B450M-G DELUXE... | Desktop     | [52614e9f8d](https://linux-hardware.org/?probe=52614e9f8d) | Dec 19, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [8421d8ab8c](https://linux-hardware.org/?probe=8421d8ab8c) | Dec 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [71f69762fe](https://linux-hardware.org/?probe=71f69762fe) | Dec 08, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [572b9da8d1](https://linux-hardware.org/?probe=572b9da8d1) | Dec 06, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [01a565720c](https://linux-hardware.org/?probe=01a565720c) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | Notebook    | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Intel         | NUC7i5DNB J57626-504        | Mini pc     | [d2625c256e](https://linux-hardware.org/?probe=d2625c256e) | Nov 22, 2021 |
| Intel         | NUC7i5DNB J57626-504        | Mini pc     | [12c79d3e71](https://linux-hardware.org/?probe=12c79d3e71) | Nov 21, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2bb3dc142](https://linux-hardware.org/?probe=e2bb3dc142) | Nov 21, 2021 |
| HP            | 3396                        | Desktop     | [db69ec8696](https://linux-hardware.org/?probe=db69ec8696) | Nov 17, 2021 |
| HP            | 3396                        | Desktop     | [70fc3e699a](https://linux-hardware.org/?probe=70fc3e699a) | Nov 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [0c64127bf0](https://linux-hardware.org/?probe=0c64127bf0) | Nov 13, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | Notebook    | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | Notebook    | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | Notebook    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [95e40c6343](https://linux-hardware.org/?probe=95e40c6343) | Oct 30, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [f2ce1a8260](https://linux-hardware.org/?probe=f2ce1a8260) | Oct 26, 2021 |
| HP            | Spectre x2 Detachable       | Notebook    | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [97bd114229](https://linux-hardware.org/?probe=97bd114229) | Oct 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [cfffe6aa63](https://linux-hardware.org/?probe=cfffe6aa63) | Oct 18, 2021 |
| Dell          | Latitude 7490               | Notebook    | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| IBM           | 81Y7071 SVT-R               | Desktop     | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | Notebook    | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | Notebook    | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [8e878489d3](https://linux-hardware.org/?probe=8e878489d3) | Oct 15, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | Latitude 7285               | Notebook    | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [530994c225](https://linux-hardware.org/?probe=530994c225) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| Acer          | Aspire VN7-593G             | Notebook    | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| MSI           | 2AE0                        | Desktop     | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7b579629bb](https://linux-hardware.org/?probe=7b579629bb) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [55620348e7](https://linux-hardware.org/?probe=55620348e7) | Oct 08, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [636ef76e1e](https://linux-hardware.org/?probe=636ef76e1e) | Oct 05, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [ca8c02f319](https://linux-hardware.org/?probe=ca8c02f319) | Sep 29, 2021 |
| JGINYUE       | H97I PLUS V2.0              | Desktop     | [2e66de23a2](https://linux-hardware.org/?probe=2e66de23a2) | Sep 28, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | Notebook    | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [fb59bae064](https://linux-hardware.org/?probe=fb59bae064) | Sep 23, 2021 |
| Lenovo        | Aptio CRB SDK0J40700 WIN... | Mini pc     | [9fc0fe4a5f](https://linux-hardware.org/?probe=9fc0fe4a5f) | Sep 22, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [85b5f14102](https://linux-hardware.org/?probe=85b5f14102) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [2b8efc01ba](https://linux-hardware.org/?probe=2b8efc01ba) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [18b064d0d6](https://linux-hardware.org/?probe=18b064d0d6) | Sep 22, 2021 |
| HP            | 1905                        | Desktop     | [56945cef9c](https://linux-hardware.org/?probe=56945cef9c) | Sep 19, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a7e1713e87](https://linux-hardware.org/?probe=a7e1713e87) | Sep 11, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba       | Satellite C50D-C            | Notebook    | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion        | P6815                       | Notebook    | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion        | P6815                       | Notebook    | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf4c0a5a4d](https://linux-hardware.org/?probe=cf4c0a5a4d) | Aug 28, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| ASRock        | 990FX Killer                | Desktop     | [6dd735449b](https://linux-hardware.org/?probe=6dd735449b) | Aug 27, 2021 |
| Sony          | VPCEB43FG                   | Notebook    | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| HP            | 304Ah                       | Desktop     | [0898c11493](https://linux-hardware.org/?probe=0898c11493) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| TWG           | E2017                       | Notebook    | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| HP            | 3397                        | Desktop     | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| MSI           | MS-7028 10B                 | Desktop     | [d9d570cae6](https://linux-hardware.org/?probe=d9d570cae6) | Aug 12, 2021 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [8e107590a6](https://linux-hardware.org/?probe=8e107590a6) | Aug 09, 2021 |
| Toshiba       | Satellite C50D-C            | Notebook    | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [6f97e49163](https://linux-hardware.org/?probe=6f97e49163) | Aug 08, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP            | Pavilion g6                 | Notebook    | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | Notebook    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP            | Spectre x2 Detachable       | Notebook    | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [bd3b6b4f35](https://linux-hardware.org/?probe=bd3b6b4f35) | Jul 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [744ab63b06](https://linux-hardware.org/?probe=744ab63b06) | Jul 28, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [cd88f96d38](https://linux-hardware.org/?probe=cd88f96d38) | Jul 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [215f44bec5](https://linux-hardware.org/?probe=215f44bec5) | Jul 24, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [120f3a158c](https://linux-hardware.org/?probe=120f3a158c) | Jul 21, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [72cf6d1ac2](https://linux-hardware.org/?probe=72cf6d1ac2) | Jul 20, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f410d6449b](https://linux-hardware.org/?probe=f410d6449b) | Jul 19, 2021 |
| MSI           | MS-7028 10B                 | Desktop     | [2c536a7e90](https://linux-hardware.org/?probe=2c536a7e90) | Jul 18, 2021 |
| MSI           | MS-7028 10B                 | Desktop     | [4077783ab8](https://linux-hardware.org/?probe=4077783ab8) | Jul 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9339298035](https://linux-hardware.org/?probe=9339298035) | Jul 14, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| Gigabyte      | P55-UD3                     | Desktop     | [6431c6f93c](https://linux-hardware.org/?probe=6431c6f93c) | Jul 12, 2021 |
| Gigabyte      | P55-UD3                     | Desktop     | [ac267d27d6](https://linux-hardware.org/?probe=ac267d27d6) | Jul 12, 2021 |
| HP            | 1497                        | Desktop     | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e3ee4893c9](https://linux-hardware.org/?probe=e3ee4893c9) | Jul 07, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [841fb32f2d](https://linux-hardware.org/?probe=841fb32f2d) | Jul 05, 2021 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [9b30ecd00d](https://linux-hardware.org/?probe=9b30ecd00d) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | Notebook    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | Notebook    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | Notebook    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7926c787f0](https://linux-hardware.org/?probe=7926c787f0) | Jun 28, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| Lenovo        | ThinkCentre M58p 7479RS2    | Desktop     | [0a417745c3](https://linux-hardware.org/?probe=0a417745c3) | Jun 20, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [79b90a017a](https://linux-hardware.org/?probe=79b90a017a) | Jun 15, 2021 |
| Sony          | SVE14A15FGS                 | Notebook    | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [259f649837](https://linux-hardware.org/?probe=259f649837) | Jun 13, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [b8540739ff](https://linux-hardware.org/?probe=b8540739ff) | Jun 12, 2021 |
| ASRock        | X370 Taichi                 | Desktop     | [15b3d9a238](https://linux-hardware.org/?probe=15b3d9a238) | Jun 10, 2021 |
| ASRock        | X370 Taichi                 | Desktop     | [1ad5e88410](https://linux-hardware.org/?probe=1ad5e88410) | Jun 10, 2021 |
| Qualcomm T... | SM8150 V2 PM8150 CEPHEUS... | Soc         | [d8411dfab2](https://linux-hardware.org/?probe=d8411dfab2) | Jun 09, 2021 |
| ASRock        | N68-S UCC                   | Desktop     | [155ac9e15e](https://linux-hardware.org/?probe=155ac9e15e) | Jun 09, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [4e107618ab](https://linux-hardware.org/?probe=4e107618ab) | Jun 08, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [90c9163323](https://linux-hardware.org/?probe=90c9163323) | Jun 07, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bebce06283](https://linux-hardware.org/?probe=bebce06283) | Jun 07, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c8d175865c](https://linux-hardware.org/?probe=c8d175865c) | Jun 04, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [c78fc3bdf3](https://linux-hardware.org/?probe=c78fc3bdf3) | Jun 04, 2021 |
| MSI           | MS-7125                     | Desktop     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [78d3325aeb](https://linux-hardware.org/?probe=78d3325aeb) | Jun 04, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [f3ffbcfa47](https://linux-hardware.org/?probe=f3ffbcfa47) | Jun 04, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [7bc9fd5174](https://linux-hardware.org/?probe=7bc9fd5174) | Jun 04, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony          | SVE11126CGB                 | Notebook    | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [9ed34e6d16](https://linux-hardware.org/?probe=9ed34e6d16) | May 27, 2021 |
| Toshiba       | Satellite S70t-B            | Notebook    | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba       | Satellite S70t-B            | Notebook    | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| Dell          | 0RCPW3 A03                  | Desktop     | [536202a82c](https://linux-hardware.org/?probe=536202a82c) | May 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| Dell          | 0RCPW3 A03                  | Desktop     | [ea6ed65a9e](https://linux-hardware.org/?probe=ea6ed65a9e) | May 20, 2021 |
| HP            | ENVY 15                     | Notebook    | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [363912f531](https://linux-hardware.org/?probe=363912f531) | May 14, 2021 |
| Gigabyte      | H470 HD3                    | Desktop     | [fb5a619781](https://linux-hardware.org/?probe=fb5a619781) | May 10, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [16e2e1cd8a](https://linux-hardware.org/?probe=16e2e1cd8a) | May 08, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [dcd72d6f14](https://linux-hardware.org/?probe=dcd72d6f14) | May 08, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [a0c689d79b](https://linux-hardware.org/?probe=a0c689d79b) | May 05, 2021 |
| Acer          | E5-571-551U                 | Notebook    | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | Notebook    | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f409c90490](https://linux-hardware.org/?probe=f409c90490) | May 01, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fbb7ce2f8b](https://linux-hardware.org/?probe=fbb7ce2f8b) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [04a24d00e5](https://linux-hardware.org/?probe=04a24d00e5) | Apr 30, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [088ae8b87b](https://linux-hardware.org/?probe=088ae8b87b) | Apr 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3193d396aa](https://linux-hardware.org/?probe=3193d396aa) | Apr 22, 2021 |
| MSI           | GS63VR 7RF                  | Notebook    | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI           | GS63VR 7RF                  | Notebook    | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [190824abc9](https://linux-hardware.org/?probe=190824abc9) | Apr 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c114a5942](https://linux-hardware.org/?probe=9c114a5942) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e23906e5f0](https://linux-hardware.org/?probe=e23906e5f0) | Apr 15, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [d998403a6d](https://linux-hardware.org/?probe=d998403a6d) | Apr 14, 2021 |
| Toshiba       | PORTEGE M930                | Notebook    | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| HP            | 304Ah                       | Desktop     | [92d8929cdf](https://linux-hardware.org/?probe=92d8929cdf) | Apr 10, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| Lenovo        | ThinkCentre A57 9704A36     | Desktop     | [cdde4de4ea](https://linux-hardware.org/?probe=cdde4de4ea) | Apr 05, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [1343705e98](https://linux-hardware.org/?probe=1343705e98) | Apr 05, 2021 |
| Microsoft     | Surface with Windows RT     | Tablet      | [2eb16ad318](https://linux-hardware.org/?probe=2eb16ad318) | Apr 04, 2021 |
| Lenovo        | YB1-X91F                    | Convertible | [78ca0e0334](https://linux-hardware.org/?probe=78ca0e0334) | Apr 03, 2021 |
| Lenovo        | YB1-X91F                    | Convertible | [2b48d2f3e3](https://linux-hardware.org/?probe=2b48d2f3e3) | Apr 03, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [724ea441e9](https://linux-hardware.org/?probe=724ea441e9) | Apr 03, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [4fdca0857b](https://linux-hardware.org/?probe=4fdca0857b) | Apr 03, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [aaa8a98fce](https://linux-hardware.org/?probe=aaa8a98fce) | Apr 02, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| ASRock        | N68-S UCC                   | Desktop     | [e566e1d5a2](https://linux-hardware.org/?probe=e566e1d5a2) | Mar 31, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6ae91d7edf](https://linux-hardware.org/?probe=6ae91d7edf) | Mar 29, 2021 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [7f8e7a4f95](https://linux-hardware.org/?probe=7f8e7a4f95) | Mar 28, 2021 |
| Metabox       | X170SM                      | Notebook    | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | Notebook    | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| ASUSTek       | KCMA-D8                     | Desktop     | [df17b4ced6](https://linux-hardware.org/?probe=df17b4ced6) | Mar 20, 2021 |
| ASRock        | N68-S UCC                   | Desktop     | [15e00c5d4a](https://linux-hardware.org/?probe=15e00c5d4a) | Mar 20, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [5f378abca9](https://linux-hardware.org/?probe=5f378abca9) | Mar 16, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| HP            | 3399                        | Desktop     | [ca3f4aa75a](https://linux-hardware.org/?probe=ca3f4aa75a) | Mar 15, 2021 |
| HP            | 3399                        | Desktop     | [08dbcb0c9c](https://linux-hardware.org/?probe=08dbcb0c9c) | Mar 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [e4dca1478e](https://linux-hardware.org/?probe=e4dca1478e) | Mar 14, 2021 |
| HP            | ProBook 4540s               | Notebook    | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cf36728751](https://linux-hardware.org/?probe=cf36728751) | Mar 08, 2021 |
| Dell          | 002KVM A00                  | Desktop     | [84dbce50b0](https://linux-hardware.org/?probe=84dbce50b0) | Mar 06, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [ed941773ff](https://linux-hardware.org/?probe=ed941773ff) | Mar 05, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [57d8b65b84](https://linux-hardware.org/?probe=57d8b65b84) | Mar 04, 2021 |
| Toshiba       | Satellite U920t             | Notebook    | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ff15fd93df](https://linux-hardware.org/?probe=ff15fd93df) | Mar 01, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP            | ZBook 14                    | Notebook    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| MSI           | MS-7125                     | Desktop     | [3bab98fcf2](https://linux-hardware.org/?probe=3bab98fcf2) | Feb 25, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3ffa3067b0](https://linux-hardware.org/?probe=3ffa3067b0) | Feb 24, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [0b85af69c2](https://linux-hardware.org/?probe=0b85af69c2) | Feb 23, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [5d129c6417](https://linux-hardware.org/?probe=5d129c6417) | Feb 23, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [446f49d2d6](https://linux-hardware.org/?probe=446f49d2d6) | Feb 22, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [97b32c8185](https://linux-hardware.org/?probe=97b32c8185) | Feb 22, 2021 |
| Dell          | Latitude 7285               | Notebook    | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| HP            | 1495                        | Desktop     | [7e0c673361](https://linux-hardware.org/?probe=7e0c673361) | Feb 17, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d7508c8abc](https://linux-hardware.org/?probe=d7508c8abc) | Feb 16, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [b7ead0e2d5](https://linux-hardware.org/?probe=b7ead0e2d5) | Feb 16, 2021 |
| MSI           | MS-7125                     | Desktop     | [104c9a719f](https://linux-hardware.org/?probe=104c9a719f) | Feb 16, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [bfeecd13dd](https://linux-hardware.org/?probe=bfeecd13dd) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [ced39cce40](https://linux-hardware.org/?probe=ced39cce40) | Feb 15, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [eded5967ea](https://linux-hardware.org/?probe=eded5967ea) | Feb 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [4db8ac896d](https://linux-hardware.org/?probe=4db8ac896d) | Feb 15, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell          | Latitude E4300              | Notebook    | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [edd27d5de6](https://linux-hardware.org/?probe=edd27d5de6) | Feb 13, 2021 |
| HP            | Notebook                    | Notebook    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [308dadd545](https://linux-hardware.org/?probe=308dadd545) | Feb 12, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| Supermicro    | X8DAH                       | Server      | [c83dc07b7c](https://linux-hardware.org/?probe=c83dc07b7c) | Feb 09, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6bee16fdd6](https://linux-hardware.org/?probe=6bee16fdd6) | Feb 08, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [65ca4b3fd8](https://linux-hardware.org/?probe=65ca4b3fd8) | Feb 08, 2021 |
| HP            | 355 G2                      | Notebook    | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| IBM           | 94Y7718 SIT                 | Desktop     | [f45bb4d28d](https://linux-hardware.org/?probe=f45bb4d28d) | Feb 02, 2021 |
| IBM           | 94Y7718 SIT                 | Desktop     | [4eda682182](https://linux-hardware.org/?probe=4eda682182) | Feb 01, 2021 |
| HP            | 82FE 11                     | Desktop     | [e0890897e2](https://linux-hardware.org/?probe=e0890897e2) | Jan 24, 2021 |
| Acer          | ES1-512-P8NA                | Notebook    | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP            | 82FE 11                     | Desktop     | [f11621cd76](https://linux-hardware.org/?probe=f11621cd76) | Jan 24, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba       | Satellite U920t             | Notebook    | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | Notebook    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [47437c1fbe](https://linux-hardware.org/?probe=47437c1fbe) | Jan 07, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [e6bc960206](https://linux-hardware.org/?probe=e6bc960206) | Jan 05, 2021 |
| HP            | 304Ah                       | Desktop     | [484bc076eb](https://linux-hardware.org/?probe=484bc076eb) | Jan 03, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [cff3edf070](https://linux-hardware.org/?probe=cff3edf070) | Dec 22, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [da31ffedd3](https://linux-hardware.org/?probe=da31ffedd3) | Dec 19, 2020 |
| Lenovo        | ThinkPad P52 20M9000KUS     | Notebook    | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [365cef4ed3](https://linux-hardware.org/?probe=365cef4ed3) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [da5b8f33d0](https://linux-hardware.org/?probe=da5b8f33d0) | Dec 14, 2020 |
| HP            | ZBook Studio G5             | Notebook    | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [59bb1dc077](https://linux-hardware.org/?probe=59bb1dc077) | Dec 09, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [d98dd8c58b](https://linux-hardware.org/?probe=d98dd8c58b) | Dec 06, 2020 |
| Dell          | Precision 7530              | Notebook    | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | Desktop     | [9fed57ace1](https://linux-hardware.org/?probe=9fed57ace1) | Dec 03, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | Desktop     | [1e4de9cf24](https://linux-hardware.org/?probe=1e4de9cf24) | Dec 03, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6c7616d830](https://linux-hardware.org/?probe=6c7616d830) | Nov 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [f420bcff80](https://linux-hardware.org/?probe=f420bcff80) | Nov 29, 2020 |
| eMachines     | eM350                       | Notebook    | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| HP            | Elite Dragonfly             | Convertible | [ce851e2475](https://linux-hardware.org/?probe=ce851e2475) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [879eecaa2c](https://linux-hardware.org/?probe=879eecaa2c) | Nov 24, 2020 |
| HP            | 304Ah                       | Desktop     | [8822926229](https://linux-hardware.org/?probe=8822926229) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [b861a3897c](https://linux-hardware.org/?probe=b861a3897c) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [6693dd023e](https://linux-hardware.org/?probe=6693dd023e) | Nov 23, 2020 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [74a9003367](https://linux-hardware.org/?probe=74a9003367) | Nov 20, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0343088b2c](https://linux-hardware.org/?probe=0343088b2c) | Nov 20, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9fb23cbe75](https://linux-hardware.org/?probe=9fb23cbe75) | Nov 17, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b32b7c28e2](https://linux-hardware.org/?probe=b32b7c28e2) | Nov 17, 2020 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [163ddf8d0b](https://linux-hardware.org/?probe=163ddf8d0b) | Nov 16, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [e88a5663df](https://linux-hardware.org/?probe=e88a5663df) | Nov 15, 2020 |
| Dell          | Latitude D630               | Notebook    | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | Notebook    | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | Notebook    | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T520 424229U       | Notebook    | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| HP            | 304Ah                       | Desktop     | [b306a58bbe](https://linux-hardware.org/?probe=b306a58bbe) | Nov 09, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | Notebook    | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | Notebook    | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Gigabyte      | H55M-USB3                   | Desktop     | [d8003cd392](https://linux-hardware.org/?probe=d8003cd392) | Nov 01, 2020 |
| Gigabyte      | H55M-USB3                   | Desktop     | [eeca2887d3](https://linux-hardware.org/?probe=eeca2887d3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [66e528143c](https://linux-hardware.org/?probe=66e528143c) | Oct 31, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | Notebook    | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | Notebook    | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d5717bdb1](https://linux-hardware.org/?probe=4d5717bdb1) | Oct 26, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| Gigabyte      | H87M-D3H                    | Desktop     | [50cdb98356](https://linux-hardware.org/?probe=50cdb98356) | Oct 26, 2020 |
| HP            | ProLiant ML350 G6           | Desktop     | [862c82ee17](https://linux-hardware.org/?probe=862c82ee17) | Oct 26, 2020 |
| HP            | ProBook 6550b               | Notebook    | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [7851a0c8a4](https://linux-hardware.org/?probe=7851a0c8a4) | Oct 21, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| HP            | 3396                        | Desktop     | [df383be5cf](https://linux-hardware.org/?probe=df383be5cf) | Oct 20, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| HP            | 8055                        | Desktop     | [9cabb3c0e9](https://linux-hardware.org/?probe=9cabb3c0e9) | Oct 18, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | X550EP                      | Notebook    | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f5fdcbbf41](https://linux-hardware.org/?probe=f5fdcbbf41) | Oct 15, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP            | Compaq Presario A900        | Notebook    | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [222313e9d4](https://linux-hardware.org/?probe=222313e9d4) | Oct 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [d8f8b18b1f](https://linux-hardware.org/?probe=d8f8b18b1f) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | Notebook    | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| ASRock        | B450M Steel Legend          | Desktop     | [a01b2e0545](https://linux-hardware.org/?probe=a01b2e0545) | Sep 30, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [42e057fc77](https://linux-hardware.org/?probe=42e057fc77) | Sep 29, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [e1e06a60de](https://linux-hardware.org/?probe=e1e06a60de) | Sep 24, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [4737809a8c](https://linux-hardware.org/?probe=4737809a8c) | Sep 16, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP            | ProBook 6560b               | Notebook    | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [c5f5fd0a14](https://linux-hardware.org/?probe=c5f5fd0a14) | Sep 12, 2020 |
| Dell          | Latitude E6430s             | Notebook    | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell          | Latitude E7440              | Notebook    | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [9b05cf5c03](https://linux-hardware.org/?probe=9b05cf5c03) | Sep 04, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |
| MSI           | GT80S 6QD                   | Notebook    | [e14f86e038](https://linux-hardware.org/?probe=e14f86e038) | Sep 03, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8d61937bc](https://linux-hardware.org/?probe=b8d61937bc) | Sep 03, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [3b6586255c](https://linux-hardware.org/?probe=3b6586255c) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | Notebook    | [c9cf3aef22](https://linux-hardware.org/?probe=c9cf3aef22) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | Notebook    | [65612b9b8f](https://linux-hardware.org/?probe=65612b9b8f) | Sep 03, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c5c33f3570](https://linux-hardware.org/?probe=c5c33f3570) | Aug 31, 2020 |
| HP            | 8055                        | Desktop     | [55806cdf5c](https://linux-hardware.org/?probe=55806cdf5c) | Aug 30, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | Notebook    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [8cf31213d6](https://linux-hardware.org/?probe=8cf31213d6) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | Notebook    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| HP            | 339A                        | Desktop     | [8b33d851ce](https://linux-hardware.org/?probe=8b33d851ce) | Aug 20, 2020 |
| HP            | Pavilion dv6                | Notebook    | [65033f4392](https://linux-hardware.org/?probe=65033f4392) | Aug 19, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [3bcf471b04](https://linux-hardware.org/?probe=3bcf471b04) | Aug 15, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| System76      | Lemur Pro                   | Notebook    | [c2619f1014](https://linux-hardware.org/?probe=c2619f1014) | Aug 14, 2020 |
| HP            | 3398                        | Desktop     | [ab1609f338](https://linux-hardware.org/?probe=ab1609f338) | Aug 13, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [bdee911e92](https://linux-hardware.org/?probe=bdee911e92) | Aug 12, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89f99d81f3](https://linux-hardware.org/?probe=89f99d81f3) | Aug 12, 2020 |
| MSI           | GT72 2PC                    | Notebook    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [fb69c1f324](https://linux-hardware.org/?probe=fb69c1f324) | Aug 10, 2020 |
| Supermicro    | X8DTH                       | Server      | [75223203bd](https://linux-hardware.org/?probe=75223203bd) | Aug 08, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9902d7243c](https://linux-hardware.org/?probe=9902d7243c) | Aug 07, 2020 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [b895b895f3](https://linux-hardware.org/?probe=b895b895f3) | Aug 04, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [37d32b3bac](https://linux-hardware.org/?probe=37d32b3bac) | Aug 03, 2020 |
| HP            | 1998                        | Desktop     | [f9df3fb967](https://linux-hardware.org/?probe=f9df3fb967) | Jul 31, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [6aee03b649](https://linux-hardware.org/?probe=6aee03b649) | Jul 31, 2020 |
| HP            | 18E7                        | Desktop     | [6c1c183fc6](https://linux-hardware.org/?probe=6c1c183fc6) | Jul 31, 2020 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [0355090a1c](https://linux-hardware.org/?probe=0355090a1c) | Jul 31, 2020 |
| Gigabyte      | H81M-HD3                    | Desktop     | [4b574045ce](https://linux-hardware.org/?probe=4b574045ce) | Jul 30, 2020 |
| Gigabyte      | H81M-HD3                    | Desktop     | [8b5a82ed70](https://linux-hardware.org/?probe=8b5a82ed70) | Jul 29, 2020 |
| Dell          | 00HDP0 A03                  | Server      | [88204d1bfa](https://linux-hardware.org/?probe=88204d1bfa) | Jul 26, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [ba999e7825](https://linux-hardware.org/?probe=ba999e7825) | Jul 25, 2020 |
| HP            | Pavilion dv4                | Notebook    | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [b17cece7fd](https://linux-hardware.org/?probe=b17cece7fd) | Jul 24, 2020 |
| HP            | 1998                        | Desktop     | [aa54cd9e2c](https://linux-hardware.org/?probe=aa54cd9e2c) | Jul 22, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell          | Latitude E5570              | Notebook    | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [cce7e31dc6](https://linux-hardware.org/?probe=cce7e31dc6) | Jul 15, 2020 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [db6c2584ca](https://linux-hardware.org/?probe=db6c2584ca) | Jul 15, 2020 |
| Unknown       | MNIC8PI                     | Desktop     | [0f24f7650f](https://linux-hardware.org/?probe=0f24f7650f) | Jul 13, 2020 |
| HP            | 212B                        | Desktop     | [9b5c44d526](https://linux-hardware.org/?probe=9b5c44d526) | Jul 10, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [4a4c813642](https://linux-hardware.org/?probe=4a4c813642) | Jul 08, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [67339ac7fd](https://linux-hardware.org/?probe=67339ac7fd) | Jul 05, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [61948190fd](https://linux-hardware.org/?probe=61948190fd) | Jul 01, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [803ec85b14](https://linux-hardware.org/?probe=803ec85b14) | Jun 30, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [55e71afa91](https://linux-hardware.org/?probe=55e71afa91) | Jun 29, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [e83d7e33f2](https://linux-hardware.org/?probe=e83d7e33f2) | Jun 29, 2020 |
| Biostar       | A68N-5000                   | Desktop     | [33f0f081e9](https://linux-hardware.org/?probe=33f0f081e9) | Jun 27, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [d8e10f56ec](https://linux-hardware.org/?probe=d8e10f56ec) | Jun 24, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [8f67a7b83f](https://linux-hardware.org/?probe=8f67a7b83f) | Jun 18, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [ca5d80f8f9](https://linux-hardware.org/?probe=ca5d80f8f9) | Jun 16, 2020 |
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [fb0f558097](https://linux-hardware.org/?probe=fb0f558097) | Jun 16, 2020 |
| ZOTAC         | ZBOXSD-ID12/ID13            | Mini pc     | [90f8e7b807](https://linux-hardware.org/?probe=90f8e7b807) | Jun 15, 2020 |
| Acer          | Aspire XC-704G              | Desktop     | [3a13e1d14a](https://linux-hardware.org/?probe=3a13e1d14a) | Jun 12, 2020 |
| Acer          | Aspire XC-704G              | Desktop     | [3fd600b32c](https://linux-hardware.org/?probe=3fd600b32c) | Jun 12, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [220b2a94c8](https://linux-hardware.org/?probe=220b2a94c8) | Jun 10, 2020 |
| ASRock        | Z87 Killer                  | Desktop     | [edb30202da](https://linux-hardware.org/?probe=edb30202da) | Jun 10, 2020 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [e311fb0391](https://linux-hardware.org/?probe=e311fb0391) | Jun 07, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [cd7ee5a475](https://linux-hardware.org/?probe=cd7ee5a475) | Jun 06, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [4e7221a789](https://linux-hardware.org/?probe=4e7221a789) | Jun 06, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [4d45a85cae](https://linux-hardware.org/?probe=4d45a85cae) | Jun 06, 2020 |
| HP            | ProBook 4540s               | Notebook    | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | Notebook    | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| Gigabyte      | X58A-UD7                    | Desktop     | [2e81a03c85](https://linux-hardware.org/?probe=2e81a03c85) | Jun 01, 2020 |
| Gigabyte      | X58A-UD7                    | Desktop     | [004ae34d21](https://linux-hardware.org/?probe=004ae34d21) | Jun 01, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [83ba796d11](https://linux-hardware.org/?probe=83ba796d11) | Jun 01, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [8c0b76c629](https://linux-hardware.org/?probe=8c0b76c629) | Jun 01, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2892347213](https://linux-hardware.org/?probe=2892347213) | May 25, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [1cb7bb7ad9](https://linux-hardware.org/?probe=1cb7bb7ad9) | May 23, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [afec91ff4d](https://linux-hardware.org/?probe=afec91ff4d) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [5439d2f06b](https://linux-hardware.org/?probe=5439d2f06b) | May 22, 2020 |
| ASUSTek       | M2N68-AM                    | Desktop     | [dbaf375be0](https://linux-hardware.org/?probe=dbaf375be0) | May 22, 2020 |
| Dell          | Latitude E6430s             | Notebook    | [891fd84ed1](https://linux-hardware.org/?probe=891fd84ed1) | May 21, 2020 |
| Dell          | Latitude E6430s             | Notebook    | [b2f67f2744](https://linux-hardware.org/?probe=b2f67f2744) | May 20, 2020 |
| HP            | 3396                        | Desktop     | [6ac1ff7341](https://linux-hardware.org/?probe=6ac1ff7341) | May 19, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | 3396                        | Desktop     | [236a304cab](https://linux-hardware.org/?probe=236a304cab) | May 19, 2020 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [df2b313ce9](https://linux-hardware.org/?probe=df2b313ce9) | May 17, 2020 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [01e35cb482](https://linux-hardware.org/?probe=01e35cb482) | May 17, 2020 |
| Sony          | VPCEH28FG                   | Notebook    | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [973e075347](https://linux-hardware.org/?probe=973e075347) | May 15, 2020 |
| Lenovo        | ThinkPad E590 20NBS0SC00    | Notebook    | [50ca962181](https://linux-hardware.org/?probe=50ca962181) | May 14, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Intel         | DG31PR AAD97573-202         | Desktop     | [5558e7aa8c](https://linux-hardware.org/?probe=5558e7aa8c) | May 14, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [b865ea9cea](https://linux-hardware.org/?probe=b865ea9cea) | May 12, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [e8880c2c12](https://linux-hardware.org/?probe=e8880c2c12) | May 12, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [605660fceb](https://linux-hardware.org/?probe=605660fceb) | May 11, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | Notebook    | [d1258905c6](https://linux-hardware.org/?probe=d1258905c6) | May 10, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | Notebook    | [51adfc765c](https://linux-hardware.org/?probe=51adfc765c) | May 10, 2020 |
| Lenovo        | ThinkCentre M58p 7479RS2    | Desktop     | [569705d7d7](https://linux-hardware.org/?probe=569705d7d7) | May 10, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [050a2216f8](https://linux-hardware.org/?probe=050a2216f8) | May 10, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [8ca322cd11](https://linux-hardware.org/?probe=8ca322cd11) | May 06, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| Lenovo        | ThinkCentre M58p 7483AC4    | Desktop     | [65dc50f256](https://linux-hardware.org/?probe=65dc50f256) | May 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3c0cbfbf66](https://linux-hardware.org/?probe=3c0cbfbf66) | May 04, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c1760ffe1b](https://linux-hardware.org/?probe=c1760ffe1b) | Apr 30, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [5d4f28e58b](https://linux-hardware.org/?probe=5d4f28e58b) | Apr 29, 2020 |
| HP            | Presario CQ57               | Notebook    | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| HP            | 1495                        | Desktop     | [a1f532749d](https://linux-hardware.org/?probe=a1f532749d) | Apr 25, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [ab309746a3](https://linux-hardware.org/?probe=ab309746a3) | Apr 23, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [ae8010c021](https://linux-hardware.org/?probe=ae8010c021) | Apr 21, 2020 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer          | Aspire A315-21G             | Notebook    | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer          | Aspire A315-21G             | Notebook    | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b67554882d](https://linux-hardware.org/?probe=b67554882d) | Apr 19, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3a29b79970](https://linux-hardware.org/?probe=3a29b79970) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [15ad84ee0f](https://linux-hardware.org/?probe=15ad84ee0f) | Apr 15, 2020 |
| Pegatron      | 2A99                        | Desktop     | [23eb1431c9](https://linux-hardware.org/?probe=23eb1431c9) | Apr 13, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [89cce1b8b6](https://linux-hardware.org/?probe=89cce1b8b6) | Apr 06, 2020 |
| ASUSTek       | M2N68-AM                    | Desktop     | [60aac968a5](https://linux-hardware.org/?probe=60aac968a5) | Apr 06, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3005d3d129](https://linux-hardware.org/?probe=3005d3d129) | Apr 05, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e4ed30a655](https://linux-hardware.org/?probe=e4ed30a655) | Apr 04, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [391a50ded4](https://linux-hardware.org/?probe=391a50ded4) | Apr 03, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [04666ab26e](https://linux-hardware.org/?probe=04666ab26e) | Apr 01, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7ec6fbac2b](https://linux-hardware.org/?probe=7ec6fbac2b) | Mar 29, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [8805131c92](https://linux-hardware.org/?probe=8805131c92) | Mar 27, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [a39b2c1a02](https://linux-hardware.org/?probe=a39b2c1a02) | Mar 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0c505fcd69](https://linux-hardware.org/?probe=0c505fcd69) | Mar 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [fc12fa3a4d](https://linux-hardware.org/?probe=fc12fa3a4d) | Mar 25, 2020 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [19a5953c79](https://linux-hardware.org/?probe=19a5953c79) | Mar 24, 2020 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [8c8d4642d3](https://linux-hardware.org/?probe=8c8d4642d3) | Mar 24, 2020 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [f4f823b37e](https://linux-hardware.org/?probe=f4f823b37e) | Mar 24, 2020 |
| Dell          | Precision M6800             | Notebook    | [adb3b768f7](https://linux-hardware.org/?probe=adb3b768f7) | Mar 24, 2020 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [20fcc93972](https://linux-hardware.org/?probe=20fcc93972) | Mar 22, 2020 |
| ASUSTek       | M2N68-AM                    | Desktop     | [0d0cb38926](https://linux-hardware.org/?probe=0d0cb38926) | Mar 15, 2020 |
| ASUSTek       | TAICHI21                    | Notebook    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [de4392a815](https://linux-hardware.org/?probe=de4392a815) | Mar 08, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [76a4b4dc8c](https://linux-hardware.org/?probe=76a4b4dc8c) | Mar 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [a26150e202](https://linux-hardware.org/?probe=a26150e202) | Mar 07, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [0d6d26562c](https://linux-hardware.org/?probe=0d6d26562c) | Mar 07, 2020 |
| Lenovo        | ThinkPad T520 424229U       | Notebook    | [f49a66ef1e](https://linux-hardware.org/?probe=f49a66ef1e) | Feb 25, 2020 |
| HP            | Pavilion 15                 | Notebook    | [72784962fe](https://linux-hardware.org/?probe=72784962fe) | Feb 25, 2020 |
| HP            | Pavilion 15                 | Notebook    | [a1e89aa309](https://linux-hardware.org/?probe=a1e89aa309) | Feb 25, 2020 |
| Dell          | Latitude E4300              | Notebook    | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| HP            | 1998                        | Desktop     | [4976d49be8](https://linux-hardware.org/?probe=4976d49be8) | Feb 13, 2020 |
| HP            | EliteBook x360 1040 G6      | Notebook    | [a838427772](https://linux-hardware.org/?probe=a838427772) | Feb 12, 2020 |
| Lenovo        | ThinkPad T520 424229U       | Notebook    | [5f61d3d553](https://linux-hardware.org/?probe=5f61d3d553) | Feb 09, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| Kogan         | KAL11C250SA                 | Convertible | [0a599057c4](https://linux-hardware.org/?probe=0a599057c4) | Feb 04, 2020 |
| HP            | 1496                        | Desktop     | [d031f2ddb3](https://linux-hardware.org/?probe=d031f2ddb3) | Feb 02, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [b5d441afe1](https://linux-hardware.org/?probe=b5d441afe1) | Feb 01, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [85b3202273](https://linux-hardware.org/?probe=85b3202273) | Jan 30, 2020 |
| Gigabyte      | P67A-UD3R-B3                | Desktop     | [56653049b3](https://linux-hardware.org/?probe=56653049b3) | Jan 25, 2020 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [9829bf7442](https://linux-hardware.org/?probe=9829bf7442) | Jan 25, 2020 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [7d5c355cec](https://linux-hardware.org/?probe=7d5c355cec) | Jan 25, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [c770de6326](https://linux-hardware.org/?probe=c770de6326) | Jan 25, 2020 |
| Lenovo        | ThinkPad X131e 33691A4      | Notebook    | [a30712cd7d](https://linux-hardware.org/?probe=a30712cd7d) | Jan 22, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| HP            | 1998                        | Desktop     | [d3cafd611f](https://linux-hardware.org/?probe=d3cafd611f) | Jan 17, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a766080680](https://linux-hardware.org/?probe=a766080680) | Jan 11, 2020 |
| Dell          | 0TCYKM A00                  | Desktop     | [dc961a7541](https://linux-hardware.org/?probe=dc961a7541) | Jan 11, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 83        | 10.41%  |
| Ubuntu 18.04                 | 49        | 6.15%   |
| Ubuntu 22.04                 | 37        | 4.64%   |
| Arch Rolling                 | 23        | 2.89%   |
| Debian 11                    | 22        | 2.76%   |
| Zorin 16                     | 20        | 2.51%   |
| Pop!_OS 22.04                | 20        | 2.51%   |
| Pop!_OS 20.04                | 17        | 2.13%   |
| OpenMandriva 4.3             | 16        | 2.01%   |
| Ubuntu 20.10                 | 14        | 1.76%   |
| Pop!_OS 20.10                | 14        | 1.76%   |
| Zorin 15                     | 13        | 1.63%   |
| OpenMandriva 4.2             | 12        | 1.51%   |
| Linux Mint 21.1              | 12        | 1.51%   |
| Linux Mint 20.3              | 12        | 1.51%   |
| Fedora 36                    | 12        | 1.51%   |
| Arch                         | 12        | 1.51%   |
| Ubuntu 21.04                 | 11        | 1.38%   |
| Manjaro                      | 11        | 1.38%   |
| Fedora 34                    | 11        | 1.38%   |
| Fedora 33                    | 11        | 1.38%   |
| Pop!_OS 21.04                | 10        | 1.25%   |
| Linux Mint 20.2              | 10        | 1.25%   |
| Linux Mint 20.1              | 10        | 1.25%   |
| Fedora 31                    | 10        | 1.25%   |
| Debian 10                    | 10        | 1.25%   |
| Ubuntu 21.10                 | 9         | 1.13%   |
| OpenMandriva 23.01           | 9         | 1.13%   |
| Fedora 37                    | 9         | 1.13%   |
| Pop!_OS 21.10                | 8         | 1%      |
| Linux Mint 21                | 8         | 1%      |
| Ubuntu 18.10                 | 7         | 0.88%   |
| Linux Mint 20                | 7         | 0.88%   |
| Kubuntu 22.04                | 7         | 0.88%   |
| Kubuntu 20.04                | 7         | 0.88%   |
| KDE neon 20.04               | 7         | 0.88%   |
| Fedora 35                    | 7         | 0.88%   |
| Ubuntu 19.10                 | 6         | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.75%   |
| Linux Mint 19.3              | 6         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 223       | 30.09%  |
| Linux Mint    | 70        | 9.45%   |
| Pop!_OS       | 64        | 8.64%   |
| Fedora        | 61        | 8.23%   |
| OpenMandriva  | 43        | 5.8%    |
| Debian        | 39        | 5.26%   |
| Arch          | 35        | 4.72%   |
| Zorin         | 33        | 4.45%   |
| Manjaro       | 23        | 3.1%    |
| Kubuntu       | 18        | 2.43%   |
| Endless       | 15        | 2.02%   |
| KDE neon      | 13        | 1.75%   |
| Xubuntu       | 9         | 1.21%   |
| Elementary    | 8         | 1.08%   |
| Nobara        | 7         | 0.94%   |
| openSUSE      | 6         | 0.81%   |
| EndeavourOS   | 6         | 0.81%   |
| Ubuntu Unity  | 5         | 0.67%   |
| ROSA          | 5         | 0.67%   |
| Lubuntu       | 5         | 0.67%   |
| Gentoo        | 5         | 0.67%   |
| Peppermint    | 4         | 0.54%   |
| MX            | 4         | 0.54%   |
| Kali          | 4         | 0.54%   |
| Ubuntu MATE   | 3         | 0.4%    |
| Solus         | 3         | 0.4%    |
| LMDE          | 3         | 0.4%    |
| Clear Linux   | 3         | 0.4%    |
| ArcoLinux     | 3         | 0.4%    |
| SteamOS       | 2         | 0.27%   |
| RHEL          | 2         | 0.27%   |
| NixOS         | 2         | 0.27%   |
| Devuan        | 2         | 0.27%   |
| Void Linux    | 1         | 0.13%   |
| Ubuntu Budgie | 1         | 0.13%   |
| Sparky        | 1         | 0.13%   |
| Regata OS     | 1         | 0.13%   |
| Redcore       | 1         | 0.13%   |
| Raspbian      | 1         | 0.13%   |
| Parrot        | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 22        | 2.46%   |
| 5.16.7-desktop-1omv4003  | 14        | 1.56%   |
| 5.15.0-46-generic        | 13        | 1.45%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.34%   |
| 6.1.1-desktop-1omv2290   | 9         | 1%      |
| 5.15.0-60-generic        | 8         | 0.89%   |
| 5.15.0-56-generic        | 8         | 0.89%   |
| 5.4.0-7634-generic       | 7         | 0.78%   |
| 5.4.0-65-generic         | 7         | 0.78%   |
| 5.15.0-58-generic        | 7         | 0.78%   |
| 6.0.12-76060006-generic  | 6         | 0.67%   |
| 5.4.0-48-generic         | 6         | 0.67%   |
| 5.3.0-46-generic         | 6         | 0.67%   |
| 5.3.0-40-generic         | 6         | 0.67%   |
| 5.13.0-30-generic        | 6         | 0.67%   |
| 5.11.0-7620-generic      | 6         | 0.67%   |
| 5.11.0-37-generic        | 6         | 0.67%   |
| 5.10.0-16-amd64          | 6         | 0.67%   |
| 5.0.0-37-generic         | 6         | 0.67%   |
| 6.2.0-20-generic         | 5         | 0.56%   |
| 5.8.0-43-generic         | 5         | 0.56%   |
| 5.4.0-7642-generic       | 5         | 0.56%   |
| 5.4.0-74-generic         | 5         | 0.56%   |
| 5.4.0-52-generic         | 5         | 0.56%   |
| 5.4.0-45-generic         | 5         | 0.56%   |
| 5.3.16-300.fc31.x86_64   | 5         | 0.56%   |
| 5.3.0-28-generic         | 5         | 0.56%   |
| 5.19.0-35-generic        | 5         | 0.56%   |
| 5.15.0-52-generic        | 5         | 0.56%   |
| 5.13.0-7614-generic      | 5         | 0.56%   |
| 5.13.0-39-generic        | 5         | 0.56%   |
| 5.11.0-27-generic        | 5         | 0.56%   |
| 5.10.0-18-amd64          | 5         | 0.56%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.45%   |
| 5.8.0-7630-generic       | 4         | 0.45%   |
| 5.8.0-53-generic         | 4         | 0.45%   |
| 5.8.0-50-generic         | 4         | 0.45%   |
| 5.8.0-48-generic         | 4         | 0.45%   |
| 5.8.0-44-generic         | 4         | 0.45%   |
| 5.4.0-91-generic         | 4         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 122       | 14.66%  |
| 5.15.0  | 74        | 8.89%   |
| 5.13.0  | 44        | 5.29%   |
| 5.11.0  | 44        | 5.29%   |
| 5.8.0   | 43        | 5.17%   |
| 4.15.0  | 41        | 4.93%   |
| 5.3.0   | 36        | 4.33%   |
| 5.19.0  | 24        | 2.88%   |
| 5.10.0  | 24        | 2.88%   |
| 5.0.0   | 20        | 2.4%    |
| 4.18.0  | 20        | 2.4%    |
| 5.16.7  | 14        | 1.68%   |
| 5.10.14 | 13        | 1.56%   |
| 6.1.1   | 11        | 1.32%   |
| 4.19.0  | 8         | 0.96%   |
| 6.2.6   | 7         | 0.84%   |
| 6.0.12  | 7         | 0.84%   |
| 6.2.0   | 5         | 0.6%    |
| 6.1.0   | 5         | 0.6%    |
| 5.3.16  | 5         | 0.6%    |
| 5.17.5  | 5         | 0.6%    |
| 6.0.0   | 4         | 0.48%   |
| 5.9.16  | 4         | 0.48%   |
| 5.7.0   | 4         | 0.48%   |
| 5.15.15 | 4         | 0.48%   |
| 6.2.12  | 3         | 0.36%   |
| 6.1.7   | 3         | 0.36%   |
| 5.9.8   | 3         | 0.36%   |
| 5.6.8   | 3         | 0.36%   |
| 5.6.19  | 3         | 0.36%   |
| 5.6.11  | 3         | 0.36%   |
| 5.3.8   | 3         | 0.36%   |
| 5.18.5  | 3         | 0.36%   |
| 5.18.13 | 3         | 0.36%   |
| 5.18.10 | 3         | 0.36%   |
| 5.17.9  | 3         | 0.36%   |
| 5.16.13 | 3         | 0.36%   |
| 5.16.11 | 3         | 0.36%   |
| 5.15.4  | 3         | 0.36%   |
| 5.15.12 | 3         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 130       | 15.89%  |
| 5.15    | 101       | 12.35%  |
| 5.11    | 56        | 6.85%   |
| 5.8     | 53        | 6.48%   |
| 5.13    | 52        | 6.36%   |
| 5.10    | 48        | 5.87%   |
| 5.3     | 43        | 5.26%   |
| 4.15    | 41        | 5.01%   |
| 6.1     | 33        | 4.03%   |
| 5.19    | 32        | 3.91%   |
| 5.16    | 26        | 3.18%   |
| 6.2     | 21        | 2.57%   |
| 5.0     | 21        | 2.57%   |
| 4.18    | 21        | 2.57%   |
| 6.0     | 20        | 2.44%   |
| 5.18    | 17        | 2.08%   |
| 5.17    | 14        | 1.71%   |
| 5.9     | 12        | 1.47%   |
| 5.6     | 12        | 1.47%   |
| 5.14    | 12        | 1.47%   |
| 5.7     | 11        | 1.34%   |
| 6.3     | 10        | 1.22%   |
| 4.19    | 9         | 1.1%    |
| 5.12    | 7         | 0.86%   |
| 5.5     | 4         | 0.49%   |
| 4.9     | 4         | 0.49%   |
| 5.2     | 2         | 0.24%   |
| 4.20    | 2         | 0.24%   |
| 4.4     | 1         | 0.12%   |
| 4.14    | 1         | 0.12%   |
| 4.13    | 1         | 0.12%   |
| 4.11    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 690       | 97.87%  |
| i686    | 10        | 1.42%   |
| aarch64 | 4         | 0.57%   |
| armv7l  | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 354       | 47.58%  |
| KDE5             | 106       | 14.25%  |
| Unknown          | 90        | 12.1%   |
| X-Cinnamon       | 58        | 7.8%    |
| XFCE             | 44        | 5.91%   |
| KDE              | 22        | 2.96%   |
| MATE             | 19        | 2.55%   |
| Pantheon         | 8         | 1.08%   |
| Cinnamon         | 7         | 0.94%   |
| LXQt             | 6         | 0.81%   |
| Unity            | 5         | 0.67%   |
| LXDE             | 5         | 0.67%   |
| i3               | 5         | 0.67%   |
| Deepin           | 4         | 0.54%   |
| Budgie           | 3         | 0.4%    |
| Hyprland         | 2         | 0.27%   |
| xsession         | 1         | 0.13%   |
| Openbox          | 1         | 0.13%   |
| lightdm-xsession | 1         | 0.13%   |
| KDE4             | 1         | 0.13%   |
| icewm            | 1         | 0.13%   |
| i3-with-shmlog   | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 546       | 75%     |
| Wayland | 119       | 16.35%  |
| Unknown | 46        | 6.32%   |
| Tty     | 17        | 2.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 396       | 53.37%  |
| SDDM    | 95        | 12.8%   |
| GDM     | 75        | 10.11%  |
| LightDM | 74        | 9.97%   |
| GDM3    | 68        | 9.16%   |
| TDM     | 25        | 3.37%   |
| SLiM    | 3         | 0.4%    |
| Ly      | 2         | 0.27%   |
| LXDM    | 2         | 0.27%   |
| XDM     | 1         | 0.13%   |
| KDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_NZ   | 439       | 59.01%  |
| en_US   | 150       | 20.16%  |
| Unknown | 78        | 10.48%  |
| en_GB   | 29        | 3.9%    |
| C       | 21        | 2.82%   |
| en_AU   | 19        | 2.55%   |
| zh_CN   | 4         | 0.54%   |
| mi_NZ   | 2         | 0.27%   |
| pt_BR   | 1         | 0.13%   |
| de_DE   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 364       | 50.35%  |
| BIOS | 359       | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 560       | 76.71%  |
| Btrfs   | 64        | 8.77%   |
| Overlay | 52        | 7.12%   |
| Unknown | 29        | 3.97%   |
| Zfs     | 7         | 0.96%   |
| Tmpfs   | 6         | 0.82%   |
| Xfs     | 5         | 0.68%   |
| Ext2    | 4         | 0.55%   |
| Ext3    | 2         | 0.27%   |
| F2fs    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 402       | 55.37%  |
| GPT     | 260       | 35.81%  |
| MBR     | 64        | 8.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 623       | 85.93%  |
| Yes       | 102       | 14.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 531       | 73.75%  |
| Yes       | 189       | 26.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 160       | 22.7%   |
| ASUSTek Computer                     | 110       | 15.6%   |
| Gigabyte Technology                  | 81        | 11.49%  |
| Lenovo                               | 75        | 10.64%  |
| Dell                                 | 72        | 10.21%  |
| Acer                                 | 33        | 4.68%   |
| MSI                                  | 27        | 3.83%   |
| Intel                                | 24        | 3.4%    |
| ASRock                               | 20        | 2.84%   |
| Toshiba                              | 18        | 2.55%   |
| Apple                                | 18        | 2.55%   |
| Supermicro                           | 6         | 0.85%   |
| Sony                                 | 6         | 0.85%   |
| Google                               | 6         | 0.85%   |
| Unknown                              | 6         | 0.85%   |
| Samsung Electronics                  | 4         | 0.57%   |
| IBM                                  | 4         | 0.57%   |
| Raspberry Pi Foundation              | 3         | 0.43%   |
| Valve                                | 2         | 0.28%   |
| System76                             | 2         | 0.28%   |
| Pegatron                             | 2         | 0.28%   |
| Kogan                                | 2         | 0.28%   |
| HUAWEI                               | 2         | 0.28%   |
| Alienware                            | 2         | 0.28%   |
| YJKC                                 | 1         | 0.14%   |
| TWG                                  | 1         | 0.14%   |
| Timi                                 | 1         | 0.14%   |
| The Warehouse Group                  | 1         | 0.14%   |
| Star Labs                            | 1         | 0.14%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.14%   |
| Qualcomm Technologies                | 1         | 0.14%   |
| OEM                                  | 1         | 0.14%   |
| Microsoft                            | 1         | 0.14%   |
| Metabox                              | 1         | 0.14%   |
| Medion                               | 1         | 0.14%   |
| MediaVue                             | 1         | 0.14%   |
| JGINYUE                              | 1         | 0.14%   |
| Huanan                               | 1         | 0.14%   |
| eMachines                            | 1         | 0.14%   |
| DFI                                  | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 7         | 0.99%   |
| Gigabyte H77M-D3H                         | 6         | 0.85%   |
| Dell XPS 13 9360                          | 5         | 0.71%   |
| ASUS All Series                           | 5         | 0.71%   |
| HP ProBook 6550b                          | 4         | 0.57%   |
| HP Pavilion dv6                           | 4         | 0.57%   |
| HP Pavilion 15                            | 4         | 0.57%   |
| HP Notebook                               | 4         | 0.57%   |
| ASUS TUF Gaming X570-PLUS                 | 4         | 0.57%   |
| MSI MS-7B89                               | 3         | 0.43%   |
| HP ProBook 4540s                          | 3         | 0.43%   |
| HP EliteDesk 800 G1 SFF                   | 3         | 0.43%   |
| HP EliteBook 8560p                        | 3         | 0.43%   |
| HP Compaq 8200 Elite SFF PC               | 3         | 0.43%   |
| Gigabyte B75M-D3H                         | 3         | 0.43%   |
| Gigabyte B450M S2H                        | 3         | 0.43%   |
| Gigabyte 970A-D3P                         | 3         | 0.43%   |
| ASRock B450M Steel Legend                 | 3         | 0.43%   |
| Acer Aspire F5-573G                       | 3         | 0.43%   |
| Valve Jupiter                             | 2         | 0.28%   |
| Toshiba Satellite L750                    | 2         | 0.28%   |
| MSI MS-7C91                               | 2         | 0.28%   |
| MSI MS-7C02                               | 2         | 0.28%   |
| MSI GE66 Raider 10SF                      | 2         | 0.28%   |
| Lenovo ThinkPad T460 20FMS2FR00           | 2         | 0.28%   |
| Lenovo ThinkPad T420 4180AQ3              | 2         | 0.28%   |
| Lenovo ThinkCentre M58p 7479RS2           | 2         | 0.28%   |
| Intel NUC8i7HVK                           | 2         | 0.28%   |
| HUAWEI BOHK-WAX9X                         | 2         | 0.28%   |
| HP ZBook Firefly 15 G7 Mobile Workstation | 2         | 0.28%   |
| HP ProDesk 600 G1 SFF                     | 2         | 0.28%   |
| HP ProBook 6570b                          | 2         | 0.28%   |
| HP ProBook 450 G5                         | 2         | 0.28%   |
| HP ProBook 450 G3                         | 2         | 0.28%   |
| HP EliteDesk 800 G2 DM 35W                | 2         | 0.28%   |
| HP EliteBook 8570p                        | 2         | 0.28%   |
| HP EliteBook 850 G5                       | 2         | 0.28%   |
| HP EliteBook 840 G6                       | 2         | 0.28%   |
| HP EliteBook 840 G5                       | 2         | 0.28%   |
| HP EliteBook 830 G5                       | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 39        | 5.53%   |
| HP EliteBook           | 29        | 4.11%   |
| ASUS ROG               | 25        | 3.55%   |
| HP ProBook             | 24        | 3.4%    |
| Acer Aspire            | 22        | 3.12%   |
| HP Pavilion            | 21        | 2.98%   |
| HP Compaq              | 21        | 2.98%   |
| Dell Latitude          | 18        | 2.55%   |
| ASUS PRIME             | 15        | 2.13%   |
| Toshiba Satellite      | 13        | 1.84%   |
| Dell XPS               | 12        | 1.7%    |
| Dell Precision         | 11        | 1.56%   |
| Dell Inspiron          | 11        | 1.56%   |
| Lenovo ThinkCentre     | 9         | 1.28%   |
| Dell OptiPlex          | 9         | 1.28%   |
| ASUS TUF               | 9         | 1.28%   |
| HP ZBook               | 8         | 1.13%   |
| HP Laptop              | 7         | 0.99%   |
| HP EliteDesk           | 7         | 0.99%   |
| Unknown                | 7         | 0.99%   |
| Lenovo Yoga            | 6         | 0.85%   |
| Gigabyte H77M-D3H      | 6         | 0.85%   |
| HP ProLiant            | 5         | 0.71%   |
| ASUS ASUS              | 5         | 0.71%   |
| ASUS All               | 5         | 0.71%   |
| Toshiba PORTEGE        | 4         | 0.57%   |
| HP Spectre             | 4         | 0.57%   |
| HP Notebook            | 4         | 0.57%   |
| Gigabyte B550M         | 4         | 0.57%   |
| ASUS VivoBook          | 4         | 0.57%   |
| Acer TravelMate        | 4         | 0.57%   |
| RPi Raspberry          | 3         | 0.43%   |
| MSI MS-7B89            | 3         | 0.43%   |
| Lenovo IdeaPad         | 3         | 0.43%   |
| IBM System             | 3         | 0.43%   |
| HP ENVY                | 3         | 0.43%   |
| Gigabyte GA-78LMT-USB3 | 3         | 0.43%   |
| Gigabyte B75M-D3H      | 3         | 0.43%   |
| Gigabyte B550          | 3         | 0.43%   |
| Gigabyte B450M         | 3         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 92        | 13.05%  |
| 2019    | 63        | 8.94%   |
| 2018    | 63        | 8.94%   |
| 2011    | 59        | 8.37%   |
| 2020    | 58        | 8.23%   |
| 2017    | 51        | 7.23%   |
| 2013    | 43        | 6.1%    |
| 2021    | 38        | 5.39%   |
| 2016    | 35        | 4.96%   |
| 2022    | 34        | 4.82%   |
| 2010    | 33        | 4.68%   |
| 2014    | 32        | 4.54%   |
| 2015    | 30        | 4.26%   |
| 2008    | 29        | 4.11%   |
| 2009    | 25        | 3.55%   |
| 2007    | 6         | 0.85%   |
| Unknown | 5         | 0.71%   |
| 2023    | 3         | 0.43%   |
| 2005    | 3         | 0.43%   |
| 2006    | 2         | 0.28%   |
| 2004    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 346       | 49.08%  |
| Desktop        | 285       | 40.43%  |
| Mini pc        | 25        | 3.55%   |
| Convertible    | 22        | 3.12%   |
| Server         | 11        | 1.56%   |
| All in one     | 10        | 1.42%   |
| System on chip | 4         | 0.57%   |
| Tablet         | 2         | 0.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 649       | 91.41%  |
| Enabled  | 61        | 8.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 696       | 98.72%  |
| Yes  | 9         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 167       | 23.1%   |
| 4.01-8.0        | 154       | 21.3%   |
| 8.01-16.0       | 132       | 18.26%  |
| 3.01-4.0        | 108       | 14.94%  |
| 32.01-64.0      | 95        | 13.14%  |
| 64.01-256.0     | 28        | 3.87%   |
| 1.01-2.0        | 15        | 2.07%   |
| 24.01-32.0      | 14        | 1.94%   |
| 2.01-3.0        | 6         | 0.83%   |
| 0.51-1.0        | 3         | 0.41%   |
| More than 256.0 | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 258       | 32.25%  |
| 2.01-3.0   | 220       | 27.5%   |
| 4.01-8.0   | 115       | 14.38%  |
| 3.01-4.0   | 112       | 14%     |
| 0.51-1.0   | 40        | 5%      |
| 8.01-16.0  | 37        | 4.63%   |
| 16.01-24.0 | 9         | 1.13%   |
| 0.01-0.5   | 6         | 0.75%   |
| 24.01-32.0 | 2         | 0.25%   |
| 32.01-64.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 422       | 57.18%  |
| 2       | 184       | 24.93%  |
| 3       | 68        | 9.21%   |
| 4       | 33        | 4.47%   |
| 5       | 10        | 1.36%   |
| 6       | 9         | 1.22%   |
| 7       | 3         | 0.41%   |
| 0       | 3         | 0.41%   |
| 8       | 2         | 0.27%   |
| Unknown | 2         | 0.27%   |
| 20      | 1         | 0.14%   |
| 9       | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 427       | 59.89%  |
| Yes       | 286       | 40.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 622       | 87.85%  |
| No        | 86        | 12.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 538       | 75.88%  |
| No        | 171       | 24.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 427       | 59.72%  |
| No        | 288       | 40.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| New Zealand | 705       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Auckland         | 344       | 46.3%   |
| Wellington       | 92        | 12.38%  |
| Christchurch     | 87        | 11.71%  |
| Hamilton         | 43        | 5.79%   |
| Tauranga         | 25        | 3.36%   |
| Dunedin          | 21        | 2.83%   |
| Palmerston North | 15        | 2.02%   |
| Nelson           | 12        | 1.62%   |
| Whangarei        | 11        | 1.48%   |
| Cambridge        | 10        | 1.35%   |
| New Plymouth     | 9         | 1.21%   |
| Napier City      | 9         | 1.21%   |
| Whanganui        | 7         | 0.94%   |
| Lower Hutt       | 7         | 0.94%   |
| Invercargill     | 6         | 0.81%   |
| Hastings         | 6         | 0.81%   |
| Masterton        | 3         | 0.4%    |
| Grafton          | 3         | 0.4%    |
| Rotorua          | 2         | 0.27%   |
| Otaki            | 2         | 0.27%   |
| Ashburton        | 2         | 0.27%   |
| Whatawhata       | 1         | 0.13%   |
| Westport         | 1         | 0.13%   |
| Wellsford        | 1         | 0.13%   |
| Waihi            | 1         | 0.13%   |
| Tutukaka         | 1         | 0.13%   |
| Stratford        | 1         | 0.13%   |
| Saint Andrews    | 1         | 0.13%   |
| Queenstown       | 1         | 0.13%   |
| Paraparaumu      | 1         | 0.13%   |
| Pakuranga        | 1         | 0.13%   |
| Onekawa          | 1         | 0.13%   |
| Mount Maunganui  | 1         | 0.13%   |
| Mount Eden       | 1         | 0.13%   |
| Milton           | 1         | 0.13%   |
| Levin            | 1         | 0.13%   |
| Kerikeri         | 1         | 0.13%   |
| Katikati         | 1         | 0.13%   |
| Inglewood        | 1         | 0.13%   |
| Hunterville      | 1         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 192       | 343    | 18.6%   |
| Seagate                   | 185       | 320    | 17.93%  |
| WDC                       | 166       | 280    | 16.09%  |
| Crucial                   | 61        | 99     | 5.91%   |
| Toshiba                   | 57        | 73     | 5.52%   |
| Kingston                  | 42        | 61     | 4.07%   |
| Sandisk                   | 40        | 47     | 3.88%   |
| Intel                     | 39        | 54     | 3.78%   |
| Unknown                   | 33        | 46     | 3.2%    |
| Hitachi                   | 28        | 38     | 2.71%   |
| SK hynix                  | 23        | 31     | 2.23%   |
| A-DATA Technology         | 19        | 22     | 1.84%   |
| HGST                      | 17        | 19     | 1.65%   |
| Micron Technology         | 15        | 20     | 1.45%   |
| China                     | 8         | 9      | 0.78%   |
| Team                      | 7         | 8      | 0.68%   |
| Apple                     | 7         | 8      | 0.68%   |
| Micron/Crucial Technology | 6         | 6      | 0.58%   |
| KIOXIA                    | 6         | 7      | 0.58%   |
| ASMT                      | 6         | 6      | 0.58%   |
| TO Exter                  | 5         | 5      | 0.48%   |
| KingSpec                  | 5         | 5      | 0.48%   |
| Transcend                 | 4         | 4      | 0.39%   |
| Silicon Motion            | 4         | 6      | 0.39%   |
| LITEON                    | 4         | 4      | 0.39%   |
| External                  | 4         | 5      | 0.39%   |
| Apacer                    | 4         | 4      | 0.39%   |
| XPG                       | 3         | 3      | 0.29%   |
| Lexar                     | 3         | 3      | 0.29%   |
| JMicron Technology        | 3         | 3      | 0.29%   |
| Hewlett-Packard           | 3         | 6      | 0.29%   |
| Gigabyte Technology       | 3         | 3      | 0.29%   |
| ShiJi                     | 2         | 2      | 0.19%   |
| ROG                       | 2         | 2      | 0.19%   |
| Phison                    | 2         | 2      | 0.19%   |
| OCZ                       | 2         | 2      | 0.19%   |
| O2 Micro                  | 2         | 2      | 0.19%   |
| Corsair                   | 2         | 3      | 0.19%   |
| USB3.0                    | 1         | 1      | 0.1%    |
| USB                       | 1         | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 14        | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB                      | 12        | 1.01%   |
| Seagate Expansion Desk 5TB                          | 11        | 0.93%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.93%   |
| Crucial CT240BX500SSD1 240GB                        | 11        | 0.93%   |
| Seagate Expansion 1TB                               | 10        | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 10        | 0.84%   |
| Samsung SSD 850 EVO 250GB                           | 9         | 0.76%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.76%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                     | 8         | 0.67%   |
| Samsung SSD 980 1TB                                 | 8         | 0.67%   |
| Samsung SSD 870 EVO 1TB                             | 8         | 0.67%   |
| Samsung NVMe SSD Drive 512GB                        | 8         | 0.67%   |
| Crucial CT500MX500SSD1 500GB                        | 8         | 0.67%   |
| Seagate ST31000528AS 1TB                            | 7         | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB                      | 7         | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7         | 0.59%   |
| Kingston SV300S37A240G 240GB SSD                    | 7         | 0.59%   |
| Intel NVMe SSD Drive 512GB                          | 7         | 0.59%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 6         | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6         | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.51%   |
| Samsung NVMe SSD Drive 1TB                          | 6         | 0.51%   |
| Kingston SV300S37A120G 120GB SSD                    | 6         | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 5         | 0.42%   |
| Unknown SD/MMC/MS PRO 250GB                         | 5         | 0.42%   |
| Unknown MMC Card  64GB                              | 5         | 0.42%   |
| Toshiba THNS128GG4BBAA 128GB SSD                    | 5         | 0.42%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.42%   |
| TO Exter nal USB 3.0 1TB                            | 5         | 0.42%   |
| Seagate ST9500325AS 500GB                           | 5         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.42%   |
| SanDisk SDSSDA240G 240GB                            | 5         | 0.42%   |
| Samsung SSD 980 PRO 1TB                             | 5         | 0.42%   |
| Samsung SSD 870 EVO 500GB                           | 5         | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 5         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 178       | 305    | 42.38%  |
| WDC                 | 143       | 237    | 34.05%  |
| Toshiba             | 28        | 40     | 6.67%   |
| Hitachi             | 28        | 38     | 6.67%   |
| HGST                | 17        | 19     | 4.05%   |
| Unknown             | 5         | 9      | 1.19%   |
| Samsung Electronics | 5         | 7      | 1.19%   |
| ASMT                | 4         | 4      | 0.95%   |
| Apple               | 4         | 4      | 0.95%   |
| External            | 2         | 2      | 0.48%   |
| USB3.0              | 1         | 1      | 0.24%   |
| USB                 | 1         | 2      | 0.24%   |
| QUANTUM             | 1         | 1      | 0.24%   |
| HGST HTS            | 1         | 1      | 0.24%   |
| Fujitsu             | 1         | 1      | 0.24%   |
| Ext Hard            | 1         | 2      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 97        | 148    | 28.28%  |
| Crucial             | 54        | 88     | 15.74%  |
| Kingston            | 31        | 46     | 9.04%   |
| SanDisk             | 26        | 31     | 7.58%   |
| Intel               | 20        | 28     | 5.83%   |
| WDC                 | 15        | 26     | 4.37%   |
| A-DATA Technology   | 15        | 17     | 4.37%   |
| Micron Technology   | 10        | 14     | 2.92%   |
| Toshiba             | 8         | 9      | 2.33%   |
| China               | 8         | 8      | 2.33%   |
| Team                | 7         | 8      | 2.04%   |
| Seagate             | 6         | 9      | 1.75%   |
| TO Exter            | 5         | 5      | 1.46%   |
| KingSpec            | 5         | 5      | 1.46%   |
| SK hynix            | 4         | 4      | 1.17%   |
| Apacer              | 4         | 4      | 1.17%   |
| Transcend           | 3         | 3      | 0.87%   |
| LITEON              | 3         | 3      | 0.87%   |
| Lexar               | 3         | 3      | 0.87%   |
| Apple               | 3         | 4      | 0.87%   |
| OCZ                 | 2         | 2      | 0.58%   |
| Hewlett-Packard     | 2         | 5      | 0.58%   |
| Gigabyte Technology | 2         | 2      | 0.58%   |
| External            | 2         | 3      | 0.58%   |
| Corsair             | 2         | 3      | 0.58%   |
| OASDX               | 1         | 1      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 3      | 0.29%   |
| Innodisk            | 1         | 1      | 0.29%   |
| GAMER               | 1         | 1      | 0.29%   |
| ASMT                | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 348       | 673    | 37.42%  |
| SSD     | 306       | 486    | 32.9%   |
| NVMe    | 237       | 377    | 25.48%  |
| MMC     | 29        | 37     | 3.12%   |
| Unknown | 10        | 11     | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 520       | 1084   | 61.68%  |
| NVMe | 236       | 373    | 28%     |
| SAS  | 58        | 90     | 6.88%   |
| MMC  | 29        | 37     | 3.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 391       | 631    | 53.86%  |
| 0.51-1.0   | 205       | 323    | 28.24%  |
| 1.01-2.0   | 70        | 112    | 9.64%   |
| 3.01-4.0   | 23        | 43     | 3.17%   |
| 4.01-10.0  | 22        | 28     | 3.03%   |
| 2.01-3.0   | 13        | 15     | 1.79%   |
| 10.01-20.0 | 2         | 7      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 181       | 23.85%  |
| 251-500        | 158       | 20.82%  |
| 501-1000       | 117       | 15.42%  |
| 1001-2000      | 71        | 9.35%   |
| 1-20           | 65        | 8.56%   |
| More than 3000 | 56        | 7.38%   |
| 2001-3000      | 41        | 5.4%    |
| 51-100         | 36        | 4.74%   |
| Unknown        | 18        | 2.37%   |
| 21-50          | 16        | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 290       | 36.43%  |
| 21-50          | 138       | 17.34%  |
| 101-250        | 86        | 10.8%   |
| 51-100         | 76        | 9.55%   |
| 251-500        | 60        | 7.54%   |
| 501-1000       | 60        | 7.54%   |
| 1001-2000      | 32        | 4.02%   |
| More than 3000 | 18        | 2.26%   |
| 2001-3000      | 18        | 2.26%   |
| Unknown        | 18        | 2.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKX-00HPJT0 752GB                | 2         | 2      | 2.67%   |
| WDC WD5000AAKX-001CA0 500GB                 | 2         | 3      | 2.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 2         | 2      | 2.67%   |
| Seagate ST3500418AS 500GB                   | 2         | 2      | 2.67%   |
| Samsung Electronics SSD 980 1TB             | 2         | 2      | 2.67%   |
| Samsung Electronics SSD 870 EVO 1TB         | 2         | 2      | 2.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD            | 1         | 1      | 1.33%   |
| WDC WD3200AAKS-00UU3A0 320GB                | 1         | 1      | 1.33%   |
| WDC WD2003FZEX-00Z4SA0 2TB                  | 1         | 1      | 1.33%   |
| WDC WD15EARS-00S0XB0 1TB                    | 1         | 1      | 1.33%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 1.33%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1      | 1.33%   |
| WDC WD10EFRX-68FYTN0 1TB                    | 1         | 3      | 1.33%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 2      | 1.33%   |
| USB3.0 Extemal HDD 2TB                      | 1         | 1      | 1.33%   |
| Toshiba MQ01ABD075 752GB                    | 1         | 1      | 1.33%   |
| Toshiba MQ01ABD050 500GB                    | 1         | 1      | 1.33%   |
| Toshiba MK5076GSX 500GB                     | 1         | 1      | 1.33%   |
| Toshiba MK3261GSYN 320GB                    | 1         | 1      | 1.33%   |
| Toshiba MK3256GSY 320GB                     | 1         | 1      | 1.33%   |
| SK hynix SC308 SATA 128GB SSD               | 1         | 1      | 1.33%   |
| SK hynix HFS256G32MND-2900A 256GB SSD       | 1         | 1      | 1.33%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 2      | 1.33%   |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB     | 1         | 1      | 1.33%   |
| ShiJi 512GB M.2-NVMe                        | 1         | 1      | 1.33%   |
| Seagate ST9500420ASG 500GB                  | 1         | 1      | 1.33%   |
| Seagate ST9500420AS 500GB                   | 1         | 1      | 1.33%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 1.33%   |
| Seagate ST8000VN0022-2EL112 8TB             | 1         | 3      | 1.33%   |
| Seagate ST500NM0011 500GB                   | 1         | 2      | 1.33%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.33%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 1.33%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.33%   |
| Seagate ST3200822A 200GB                    | 1         | 1      | 1.33%   |
| Seagate ST31000528AS 1TB                    | 1         | 1      | 1.33%   |
| Seagate ST31000524AS 1TB                    | 1         | 1      | 1.33%   |
| Seagate ST3000DM001-9YN166 3TB              | 1         | 1      | 1.33%   |
| Seagate ST2000DX002-2DV164 2TB              | 1         | 1      | 1.33%   |
| Seagate ST2000DX001-1CM164 2TB              | 1         | 1      | 1.33%   |
| Seagate ST2000DM001-1ER164 2TB              | 1         | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 23     | 23.94%  |
| WDC                 | 14        | 18     | 19.72%  |
| Samsung Electronics | 6         | 6      | 8.45%   |
| Toshiba             | 5         | 5      | 7.04%   |
| HGST                | 5         | 5      | 7.04%   |
| Crucial             | 5         | 6      | 7.04%   |
| SK hynix            | 3         | 5      | 4.23%   |
| Hitachi             | 3         | 3      | 4.23%   |
| SanDisk             | 2         | 2      | 2.82%   |
| Micron Technology   | 2         | 2      | 2.82%   |
| Intel               | 2         | 2      | 2.82%   |
| ASMT                | 2         | 2      | 2.82%   |
| USB3.0              | 1         | 1      | 1.41%   |
| ShiJi               | 1         | 1      | 1.41%   |
| Innodisk            | 1         | 1      | 1.41%   |
| HGST HTS            | 1         | 1      | 1.41%   |
| Apple               | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 17        | 23     | 36.17%  |
| WDC      | 13        | 17     | 27.66%  |
| Toshiba  | 5         | 5      | 10.64%  |
| HGST     | 5         | 5      | 10.64%  |
| Hitachi  | 3         | 3      | 6.38%   |
| USB3.0   | 1         | 1      | 2.13%   |
| HGST HTS | 1         | 1      | 2.13%   |
| ASMT     | 1         | 1      | 2.13%   |
| Apple    | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 57     | 65.71%  |
| SSD  | 17        | 18     | 24.29%  |
| NVMe | 7         | 9      | 10%     |

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
| Detected | 440       | 962    | 56.48%  |
| Works    | 272       | 538    | 34.92%  |
| Malfunc  | 67        | 84     | 8.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 448       | 49.61%  |
| AMD                          | 151       | 16.72%  |
| Samsung Electronics          | 114       | 12.62%  |
| Toshiba America Info Systems | 22        | 2.44%   |
| SanDisk                      | 22        | 2.44%   |
| SK hynix                     | 19        | 2.1%    |
| Nvidia                       | 15        | 1.66%   |
| JMicron Technology           | 15        | 1.66%   |
| Micron/Crucial Technology    | 13        | 1.44%   |
| Kingston Technology Company  | 13        | 1.44%   |
| Marvell Technology Group     | 11        | 1.22%   |
| ASMedia Technology           | 10        | 1.11%   |
| LSI Logic / Symbios Logic    | 7         | 0.78%   |
| Silicon Motion               | 6         | 0.66%   |
| Micron Technology            | 6         | 0.66%   |
| KIOXIA                       | 6         | 0.66%   |
| Phison Electronics           | 5         | 0.55%   |
| ADATA Technology             | 4         | 0.44%   |
| Seagate Technology           | 3         | 0.33%   |
| Hewlett-Packard              | 3         | 0.33%   |
| Realtek Semiconductor        | 2         | 0.22%   |
| O2 Micro                     | 2         | 0.22%   |
| Broadcom / LSI               | 2         | 0.22%   |
| VIA Technologies             | 1         | 0.11%   |
| Union Memory (Shenzhen)      | 1         | 0.11%   |
| Silicon Image                | 1         | 0.11%   |
| Lite-On Technology           | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 99        | 9.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 55        | 5.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 3.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 29        | 2.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 27        | 2.54%   |
| AMD 400 Series Chipset SATA Controller                                           | 24        | 2.25%   |
| Samsung NVMe SSD Controller 980                                                  | 23        | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 20        | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 20        | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 20        | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 16        | 1.5%    |
| AMD 500 Series Chipset SATA Controller                                           | 16        | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 1.41%   |
| Intel SATA Controller [RAID mode]                                                | 14        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 14        | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                              | 12        | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 12        | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 10        | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 0.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 9         | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 9         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 8         | 0.75%   |
| AMD 300 Series Chipset SATA Controller                                           | 8         | 0.75%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 7         | 0.66%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 7         | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                               | 7         | 0.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 0.66%   |
| Intel SSD 660P Series                                                            | 7         | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 7         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 512       | 55.96%  |
| NVMe | 239       | 26.12%  |
| IDE  | 103       | 11.26%  |
| RAID | 56        | 6.12%   |
| SAS  | 4         | 0.44%   |
| SCSI | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 520       | 73.76%  |
| AMD      | 180       | 25.53%  |
| ARM      | 4         | 0.57%   |
| QUALCOMM | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 1.13%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 1.13%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 6         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.85%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 0.71%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 0.71%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 0.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 5         | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 4         | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.57%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.57%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.57%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 4         | 0.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.57%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 4         | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.57%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 4         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 173       | 24.54%  |
| Intel Core i7           | 149       | 21.13%  |
| Other                   | 41        | 5.82%   |
| AMD Ryzen 5             | 36        | 5.11%   |
| Intel Core i3           | 35        | 4.96%   |
| AMD Ryzen 7             | 35        | 4.96%   |
| Intel Core 2 Duo        | 33        | 4.68%   |
| Intel Xeon              | 27        | 3.83%   |
| Intel Celeron           | 26        | 3.69%   |
| AMD Ryzen 9             | 17        | 2.41%   |
| AMD FX                  | 17        | 2.41%   |
| Intel Pentium           | 11        | 1.56%   |
| Intel Core 2 Quad       | 11        | 1.56%   |
| AMD A6                  | 9         | 1.28%   |
| Intel Atom              | 8         | 1.13%   |
| AMD Ryzen 3             | 8         | 1.13%   |
| AMD A8                  | 6         | 0.85%   |
| AMD Ryzen Threadripper  | 5         | 0.71%   |
| AMD E2                  | 5         | 0.71%   |
| AMD Athlon 64 X2        | 5         | 0.71%   |
| AMD A4                  | 5         | 0.71%   |
| Intel Core i9           | 4         | 0.57%   |
| AMD Ryzen 5 PRO         | 4         | 0.57%   |
| AMD Athlon II X2        | 4         | 0.57%   |
| Intel Pentium M         | 2         | 0.28%   |
| Intel Pentium Dual-Core | 2         | 0.28%   |
| AMD Ryzen 7 PRO         | 2         | 0.28%   |
| AMD Phenom II X4        | 2         | 0.28%   |
| AMD Opteron             | 2         | 0.28%   |
| AMD E1                  | 2         | 0.28%   |
| AMD E                   | 2         | 0.28%   |
| AMD A10                 | 2         | 0.28%   |
| QUALCOMM AArch64        | 1         | 0.14%   |
| Intel Xeon Silver       | 1         | 0.14%   |
| Intel Pentium Silver    | 1         | 0.14%   |
| Intel Pentium Dual      | 1         | 0.14%   |
| Intel Pentium 4         | 1         | 0.14%   |
| Intel Genuine           | 1         | 0.14%   |
| Intel Core m7           | 1         | 0.14%   |
| Intel Celeron Dual-Core | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 265       | 37.54%  |
| 2      | 250       | 35.41%  |
| 6      | 72        | 10.2%   |
| 8      | 59        | 8.36%   |
| 12     | 18        | 2.55%   |
| 1      | 10        | 1.42%   |
| 10     | 8         | 1.13%   |
| 14     | 7         | 0.99%   |
| 16     | 6         | 0.85%   |
| 3      | 6         | 0.85%   |
| 20     | 3         | 0.42%   |
| 64     | 1         | 0.14%   |
| 24     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 692       | 98.16%  |
| 2      | 12        | 1.7%    |
| 3      | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 488       | 69.12%  |
| 1      | 217       | 30.74%  |
| 8      | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 692       | 97.05%  |
| Unknown        | 18        | 2.52%   |
| 32-bit         | 3         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 26.67%  |
| 0x306a9    | 47        | 6.39%   |
| 0x206a7    | 47        | 6.39%   |
| 0x306c3    | 27        | 3.67%   |
| 0x1067a    | 22        | 2.99%   |
| 0x806ea    | 19        | 2.59%   |
| 0x806ec    | 15        | 2.04%   |
| 0x806e9    | 15        | 2.04%   |
| 0x08701021 | 15        | 2.04%   |
| 0x406e3    | 14        | 1.9%    |
| 0x906e9    | 12        | 1.63%   |
| 0x20655    | 12        | 1.63%   |
| 0x506e3    | 11        | 1.5%    |
| 0x40651    | 11        | 1.5%    |
| 0x0a50000c | 9         | 1.22%   |
| 0x06000852 | 9         | 1.22%   |
| 0xa0652    | 8         | 1.09%   |
| 0x30678    | 8         | 1.09%   |
| 0x106e5    | 8         | 1.09%   |
| 0x10676    | 8         | 1.09%   |
| 0x906ea    | 7         | 0.95%   |
| 0x506c9    | 7         | 0.95%   |
| 0x0800820d | 7         | 0.95%   |
| 0x07030105 | 7         | 0.95%   |
| 0xa0655    | 6         | 0.82%   |
| 0x806c1    | 6         | 0.82%   |
| 0x08108109 | 6         | 0.82%   |
| 0x906a4    | 5         | 0.68%   |
| 0x906a3    | 5         | 0.68%   |
| 0x806eb    | 5         | 0.68%   |
| 0x6fb      | 5         | 0.68%   |
| 0x306d4    | 5         | 0.68%   |
| 0x106a5    | 5         | 0.68%   |
| 0x0a50000d | 5         | 0.68%   |
| 0x08600106 | 5         | 0.68%   |
| 0x08001137 | 5         | 0.68%   |
| 0x06001119 | 5         | 0.68%   |
| 0x6fd      | 4         | 0.54%   |
| 0x406c4    | 4         | 0.54%   |
| 0x406c3    | 4         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 106       | 15.04%  |
| IvyBridge        | 65        | 9.22%   |
| SandyBridge      | 61        | 8.65%   |
| Haswell          | 53        | 7.52%   |
| Penryn           | 42        | 5.96%   |
| Skylake          | 38        | 5.39%   |
| Zen 2            | 32        | 4.54%   |
| Zen 3            | 29        | 4.11%   |
| Unknown          | 24        | 3.4%    |
| Zen+             | 22        | 3.12%   |
| CometLake        | 22        | 3.12%   |
| Silvermont       | 21        | 2.98%   |
| Piledriver       | 21        | 2.98%   |
| Westmere         | 20        | 2.84%   |
| Nehalem          | 16        | 2.27%   |
| Zen              | 13        | 1.84%   |
| TigerLake        | 11        | 1.56%   |
| Puma             | 11        | 1.56%   |
| Alderlake Hybrid | 11        | 1.56%   |
| Core             | 10        | 1.42%   |
| K10              | 9         | 1.28%   |
| Excavator        | 9         | 1.28%   |
| Broadwell        | 9         | 1.28%   |
| IceLake          | 8         | 1.13%   |
| Goldmont         | 8         | 1.13%   |
| K8 Hammer        | 6         | 0.85%   |
| Jaguar           | 5         | 0.71%   |
| Goldmont plus    | 4         | 0.57%   |
| Bulldozer        | 4         | 0.57%   |
| Bonnell          | 4         | 0.57%   |
| Bobcat           | 4         | 0.57%   |
| Tremont          | 2         | 0.28%   |
| P6               | 2         | 0.28%   |
| NetBurst         | 1         | 0.14%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| K10 Llano        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 386       | 46.62%  |
| Nvidia                     | 214       | 25.85%  |
| AMD                        | 214       | 25.85%  |
| Matrox Electronics Systems | 10        | 1.21%   |
| ASPEED Technology          | 4         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 5.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 3.37%   |
| Intel UHD Graphics 620                                                                   | 19        | 2.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 1.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 1.97%   |
| Intel HD Graphics 630                                                                    | 15        | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.51%   |
| Intel HD Graphics 620                                                                    | 12        | 1.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.28%   |
| Intel HD Graphics 530                                                                    | 11        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.93%   |
| AMD Renoir                                                                               | 8         | 0.93%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 7         | 0.81%   |
| Intel HD Graphics 500                                                                    | 7         | 0.81%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 7         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.7%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.58%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.58%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5         | 0.58%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.58%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 5         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 278       | 38.99%  |
| 1 x AMD                 | 156       | 21.88%  |
| 1 x Nvidia              | 127       | 17.81%  |
| Intel + Nvidia          | 70        | 9.82%   |
| Intel + AMD             | 27        | 3.79%   |
| 2 x AMD                 | 20        | 2.81%   |
| AMD + Nvidia            | 11        | 1.54%   |
| 1 x Matrox              | 9         | 1.26%   |
| Other                   | 6         | 0.84%   |
| 2 x Nvidia              | 3         | 0.42%   |
| Nvidia + ASPEED         | 2         | 0.28%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.14%   |
| 2 x Intel               | 1         | 0.14%   |
| AMD + Matrox            | 1         | 0.14%   |
| AMD + ASPEED            | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 565       | 79.13%  |
| Proprietary | 124       | 17.37%  |
| Unknown     | 25        | 3.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 407       | 55.91%  |
| 1.01-2.0   | 79        | 10.85%  |
| 0.01-0.5   | 73        | 10.03%  |
| 0.51-1.0   | 56        | 7.69%   |
| 3.01-4.0   | 36        | 4.95%   |
| 7.01-8.0   | 34        | 4.67%   |
| 5.01-6.0   | 19        | 2.61%   |
| 8.01-16.0  | 16        | 2.2%    |
| 2.01-3.0   | 6         | 0.82%   |
| 32.01-64.0 | 1         | 0.14%   |
| 16.01-24.0 | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 106       | 13.07%  |
| AU Optronics            | 74        | 9.12%   |
| Dell                    | 68        | 8.38%   |
| AOC                     | 62        | 7.64%   |
| LG Display              | 61        | 7.52%   |
| Chimei Innolux          | 57        | 7.03%   |
| Goldstar                | 56        | 6.91%   |
| BOE                     | 41        | 5.06%   |
| Philips                 | 34        | 4.19%   |
| ViewSonic               | 26        | 3.21%   |
| Hewlett-Packard         | 23        | 2.84%   |
| Chi Mei Optoelectronics | 18        | 2.22%   |
| Sharp                   | 17        | 2.1%    |
| Sony                    | 14        | 1.73%   |
| Lenovo                  | 13        | 1.6%    |
| Apple                   | 13        | 1.6%    |
| Ancor Communications    | 12        | 1.48%   |
| Panasonic               | 11        | 1.36%   |
| Acer                    | 11        | 1.36%   |
| Denver                  | 9         | 1.11%   |
| BenQ                    | 9         | 1.11%   |
| MiTAC                   | 8         | 0.99%   |
| PANDA                   | 7         | 0.86%   |
| InfoVision              | 7         | 0.86%   |
| LG Electronics          | 4         | 0.49%   |
| InnoLux Display         | 3         | 0.37%   |
| ASUSTek Computer        | 3         | 0.37%   |
| Yamaha                  | 2         | 0.25%   |
| Valve                   | 2         | 0.25%   |
| Unknown                 | 2         | 0.25%   |
| SANYO                   | 2         | 0.25%   |
| Quanta Display          | 2         | 0.25%   |
| PRISM+                  | 2         | 0.25%   |
| Konka                   | 2         | 0.25%   |
| HannStar                | 2         | 0.25%   |
| Wacom                   | 1         | 0.12%   |
| Unknown (AAA)           | 1         | 0.12%   |
| Toshiba                 | 1         | 0.12%   |
| TMX                     | 1         | 0.12%   |
| QCM                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 7         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 0.69%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 6         | 0.69%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.58%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch            | 4         | 0.46%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 4         | 0.46%   |
| MiTAC Smart TV SZM0030 1920x1080 708x398mm 32.0-inch                     | 4         | 0.46%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.46%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.35%   |
| Samsung Electronics LS27AG32x SAM71DC 1920x1080 597x336mm 27.0-inch      | 3         | 0.35%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 3         | 0.35%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.35%   |
| Denver UWQHD-100-C LHC3400 3440x1440 795x334mm 33.9-inch                 | 3         | 0.35%   |
| Denver PGM270 LHC2700 2560x1440 597x336mm 27.0-inch                      | 3         | 0.35%   |
| Dell P2416D DELA0C3 2560x1440 527x296mm 23.8-inch                        | 3         | 0.35%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                        | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.35%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                           | 3         | 0.35%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 3         | 0.35%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                          | 3         | 0.35%   |
| AOC 2367 AOC2367 1920x1080 509x286mm 23.0-inch                           | 3         | 0.35%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 3         | 0.35%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 3         | 0.35%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch            | 2         | 0.23%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch                 | 2         | 0.23%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch            | 2         | 0.23%   |
| ViewSonic LCD Monitor VSCB51D 1280x1024 340x270mm 17.1-inch              | 2         | 0.23%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 2         | 0.23%   |
| Sony TV SNYEE01 1920x1080                                                | 2         | 0.23%   |
| Sony TV SNYA401 1920x1080                                                | 2         | 0.23%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.23%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 323       | 41.2%   |
| 1366x768 (WXGA)    | 116       | 14.8%   |
| 3840x2160 (4K)     | 78        | 9.95%   |
| 2560x1440 (QHD)    | 41        | 5.23%   |
| 1600x900 (HD+)     | 35        | 4.46%   |
| 1680x1050 (WSXGA+) | 29        | 3.7%    |
| 1280x1024 (SXGA)   | 22        | 2.81%   |
| 1440x900 (WXGA+)   | 20        | 2.55%   |
| 3440x1440          | 18        | 2.3%    |
| 1280x800 (WXGA)    | 16        | 2.04%   |
| Unknown            | 13        | 1.66%   |
| 1920x1200 (WUXGA)  | 12        | 1.53%   |
| 3840x1080          | 7         | 0.89%   |
| 1360x768           | 6         | 0.77%   |
| 2880x1800          | 5         | 0.64%   |
| 2560x1080          | 5         | 0.64%   |
| 3200x1800 (QHD+)   | 4         | 0.51%   |
| 1024x600           | 4         | 0.51%   |
| 3840x1600          | 3         | 0.38%   |
| 2560x1600          | 3         | 0.38%   |
| 800x1280           | 2         | 0.26%   |
| 3456x2160          | 2         | 0.26%   |
| 1920x540           | 2         | 0.26%   |
| 1600x1200          | 2         | 0.26%   |
| 1024x768 (XGA)     | 2         | 0.26%   |
| 7680x1080          | 1         | 0.13%   |
| 6720x1080          | 1         | 0.13%   |
| 5760x1080          | 1         | 0.13%   |
| 3840x2400          | 1         | 0.13%   |
| 3840x1200          | 1         | 0.13%   |
| 3360x1080          | 1         | 0.13%   |
| 2960x1050          | 1         | 0.13%   |
| 2880x1920          | 1         | 0.13%   |
| 2800x1752          | 1         | 0.13%   |
| 2560x1024          | 1         | 0.13%   |
| 2288x1287          | 1         | 0.13%   |
| 2048x1152          | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1280x960           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 169       | 20.74%  |
| 27      | 73        | 8.96%   |
| 21      | 61        | 7.48%   |
| 13      | 61        | 7.48%   |
| 14      | 59        | 7.24%   |
| 23      | 58        | 7.12%   |
| 24      | 55        | 6.75%   |
| 17      | 45        | 5.52%   |
| Unknown | 38        | 4.66%   |
| 31      | 24        | 2.94%   |
| 22      | 21        | 2.58%   |
| 19      | 20        | 2.45%   |
| 20      | 16        | 1.96%   |
| 84      | 14        | 1.72%   |
| 34      | 14        | 1.72%   |
| 72      | 10        | 1.23%   |
| 18      | 9         | 1.1%    |
| 12      | 7         | 0.86%   |
| 35      | 6         | 0.74%   |
| 32      | 6         | 0.74%   |
| 11      | 6         | 0.74%   |
| 10      | 6         | 0.74%   |
| 16      | 5         | 0.61%   |
| 37      | 4         | 0.49%   |
| 52      | 3         | 0.37%   |
| 46      | 3         | 0.37%   |
| 40      | 3         | 0.37%   |
| 26      | 3         | 0.37%   |
| 25      | 2         | 0.25%   |
| 7       | 2         | 0.25%   |
| 142     | 1         | 0.12%   |
| 66      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 55      | 1         | 0.12%   |
| 54      | 1         | 0.12%   |
| 39      | 1         | 0.12%   |
| 36      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 30      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 272       | 34.21%  |
| 501-600        | 165       | 20.75%  |
| 401-500        | 116       | 14.59%  |
| 201-300        | 48        | 6.04%   |
| 351-400        | 45        | 5.66%   |
| 601-700        | 40        | 5.03%   |
| Unknown        | 38        | 4.78%   |
| 701-800        | 22        | 2.77%   |
| 1501-2000      | 22        | 2.77%   |
| 801-900        | 14        | 1.76%   |
| 1001-1500      | 10        | 1.26%   |
| 1-100          | 2         | 0.25%   |
| More than 2000 | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 526       | 74.08%  |
| 16/10   | 89        | 12.54%  |
| Unknown | 31        | 4.37%   |
| 21/9    | 25        | 3.52%   |
| 5/4     | 22        | 3.1%    |
| 4/3     | 6         | 0.85%   |
| 3/2     | 4         | 0.56%   |
| 32/9    | 2         | 0.28%   |
| 0.67    | 2         | 0.28%   |
| 6/5     | 1         | 0.14%   |
| 1.00    | 1         | 0.14%   |
| 0.45    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 166       | 20.75%  |
| 201-250        | 160       | 20%     |
| 81-90          | 94        | 11.75%  |
| 301-350        | 74        | 9.25%   |
| 351-500        | 53        | 6.63%   |
| 151-200        | 52        | 6.5%    |
| Unknown        | 38        | 4.75%   |
| More than 1000 | 30        | 3.75%   |
| 121-130        | 30        | 3.75%   |
| 71-80          | 26        | 3.25%   |
| 141-150        | 19        | 2.38%   |
| 251-300        | 15        | 1.88%   |
| 501-1000       | 12        | 1.5%    |
| 61-70          | 7         | 0.88%   |
| 111-120        | 7         | 0.88%   |
| 51-60          | 6         | 0.75%   |
| 41-50          | 6         | 0.75%   |
| 1-40           | 2         | 0.25%   |
| 131-140        | 2         | 0.25%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 258       | 32.99%  |
| 101-120       | 220       | 28.13%  |
| 121-160       | 177       | 22.63%  |
| 161-240       | 43        | 5.5%    |
| Unknown       | 38        | 4.86%   |
| 1-50          | 26        | 3.32%   |
| More than 240 | 20        | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 532       | 72.68%  |
| 2     | 149       | 20.36%  |
| 0     | 28        | 3.83%   |
| 3     | 19        | 2.6%    |
| 4     | 4         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 384       | 35.59%  |
| Realtek Semiconductor           | 346       | 32.07%  |
| Qualcomm Atheros                | 99        | 9.18%   |
| Broadcom                        | 63        | 5.84%   |
| TP-Link                         | 20        | 1.85%   |
| Ralink                          | 17        | 1.58%   |
| MediaTek                        | 17        | 1.58%   |
| Nvidia                          | 15        | 1.39%   |
| Ralink Technology               | 13        | 1.2%    |
| Broadcom Limited                | 12        | 1.11%   |
| Marvell Technology Group        | 10        | 0.93%   |
| Hewlett-Packard                 | 6         | 0.56%   |
| Samsung Electronics             | 5         | 0.46%   |
| Qualcomm Atheros Communications | 5         | 0.46%   |
| DisplayLink                     | 5         | 0.46%   |
| ASIX Electronics                | 5         | 0.46%   |
| NetGear                         | 4         | 0.37%   |
| Microsoft                       | 4         | 0.37%   |
| Aquantia                        | 4         | 0.37%   |
| OPPO Electronics                | 3         | 0.28%   |
| Lenovo                          | 3         | 0.28%   |
| IBM                             | 3         | 0.28%   |
| Edimax Technology               | 3         | 0.28%   |
| Sierra Wireless                 | 2         | 0.19%   |
| Microchip Technology            | 2         | 0.19%   |
| Mellanox Technologies           | 2         | 0.19%   |
| JMicron Technology              | 2         | 0.19%   |
| Dell                            | 2         | 0.19%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.09%   |
| Wilocity                        | 1         | 0.09%   |
| Wacom                           | 1         | 0.09%   |
| STMicroelectronics              | 1         | 0.09%   |
| Raspberry Pi                    | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| QinHeng Electronics             | 1         | 0.09%   |
| MCS                             | 1         | 0.09%   |
| Lite-On Technology              | 1         | 0.09%   |
| Insyde Software                 | 1         | 0.09%   |
| ICS Advent                      | 1         | 0.09%   |
| Huawei Technologies             | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 238       | 18.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 35        | 2.74%   |
| Intel Wireless 8265 / 8275                                        | 30        | 2.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 1.57%   |
| Intel I211 Gigabit Network Connection                             | 18        | 1.41%   |
| Intel Wireless 8260                                               | 17        | 1.33%   |
| Intel Wireless 7260                                               | 16        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 0.94%   |
| Intel Wireless-AC 9260                                            | 12        | 0.94%   |
| Intel Wireless 3165                                               | 12        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.86%   |
| Intel Wireless 7265                                               | 11        | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 11        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 10        | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 9         | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 8         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.63%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 8         | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 8         | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 278       | 48.6%   |
| Qualcomm Atheros                      | 76        | 13.29%  |
| Realtek Semiconductor                 | 72        | 12.59%  |
| Broadcom                              | 41        | 7.17%   |
| TP-Link                               | 19        | 3.32%   |
| Ralink                                | 17        | 2.97%   |
| MediaTek                              | 16        | 2.8%    |
| Ralink Technology                     | 13        | 2.27%   |
| Broadcom Limited                      | 10        | 1.75%   |
| Qualcomm Atheros Communications       | 5         | 0.87%   |
| NetGear                               | 4         | 0.7%    |
| Microsoft                             | 3         | 0.52%   |
| Hewlett-Packard                       | 3         | 0.52%   |
| Edimax Technology                     | 3         | 0.52%   |
| Sierra Wireless                       | 2         | 0.35%   |
| Dell                                  | 2         | 0.35%   |
| Wilocity                              | 1         | 0.17%   |
| Wacom                                 | 1         | 0.17%   |
| Qualcomm                              | 1         | 0.17%   |
| Lite-On Technology                    | 1         | 0.17%   |
| D-Link                                | 1         | 0.17%   |
| Belkin Components                     | 1         | 0.17%   |
| ASUSTek Computer                      | 1         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 35        | 6.06%   |
| Intel Wireless 8265 / 8275                                     | 30        | 5.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 21        | 3.63%   |
| Intel Wireless 8260                                            | 17        | 2.94%   |
| Intel Wireless 7260                                            | 16        | 2.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 2.08%   |
| Intel Wireless-AC 9260                                         | 12        | 2.08%   |
| Intel Wireless 3165                                            | 12        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 1.9%    |
| Intel Wireless 7265                                            | 11        | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 10        | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 8         | 1.38%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 1.38%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 8         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 1.21%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.21%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.04%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 1.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 1.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 5         | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 0.87%   |
| Intel WiFi Link 5100                                           | 5         | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 315       | 47.23%  |
| Intel                      | 221       | 33.13%  |
| Qualcomm Atheros           | 37        | 5.55%   |
| Broadcom                   | 29        | 4.35%   |
| Nvidia                     | 15        | 2.25%   |
| Marvell Technology Group   | 10        | 1.5%    |
| DisplayLink                | 5         | 0.75%   |
| ASIX Electronics           | 5         | 0.75%   |
| Aquantia                   | 4         | 0.6%    |
| Samsung Electronics        | 3         | 0.45%   |
| OPPO Electronics           | 3         | 0.45%   |
| Lenovo                     | 3         | 0.45%   |
| IBM                        | 3         | 0.45%   |
| JMicron Technology         | 2         | 0.3%    |
| Broadcom Limited           | 2         | 0.3%    |
| ZTE WCDMA Technologies MSM | 1         | 0.15%   |
| TP-Link                    | 1         | 0.15%   |
| Microsoft                  | 1         | 0.15%   |
| Mellanox Technologies      | 1         | 0.15%   |
| MediaTek                   | 1         | 0.15%   |
| Insyde Software            | 1         | 0.15%   |
| ICS Advent                 | 1         | 0.15%   |
| Huawei Technologies        | 1         | 0.15%   |
| Attansic Technology        | 1         | 0.15%   |
| Apple                      | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 238       | 35%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 3.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 3.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 18        | 2.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 2.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 1.76%   |
| Intel Ethernet Controller I225-V                                  | 11        | 1.62%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 1.32%   |
| Nvidia MCP79 Ethernet                                             | 8         | 1.18%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 1.03%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.88%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.74%   |
| Intel 82577LC Gigabit Network Connection                          | 5         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 0.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.44%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 621       | 52.81%  |
| WiFi     | 537       | 45.66%  |
| Modem    | 16        | 1.36%   |
| Unknown  | 2         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 408       | 54.11%  |
| Ethernet | 345       | 45.76%  |
| Modem    | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 397       | 56.07%  |
| 1     | 276       | 38.98%  |
| 3     | 22        | 3.11%   |
| 0     | 8         | 1.13%   |
| 6     | 2         | 0.28%   |
| 4     | 2         | 0.28%   |
| 8     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 610       | 84.49%  |
| Yes  | 112       | 15.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 224       | 52.09%  |
| Qualcomm Atheros Communications | 28        | 6.51%   |
| Cambridge Silicon Radio         | 24        | 5.58%   |
| Broadcom                        | 23        | 5.35%   |
| Realtek Semiconductor           | 22        | 5.12%   |
| Foxconn / Hon Hai               | 17        | 3.95%   |
| IMC Networks                    | 16        | 3.72%   |
| Apple                           | 16        | 3.72%   |
| Lite-On Technology              | 15        | 3.49%   |
| Hewlett-Packard                 | 12        | 2.79%   |
| ASUSTek Computer                | 6         | 1.4%    |
| Toshiba                         | 5         | 1.16%   |
| Ralink                          | 4         | 0.93%   |
| Ralink Technology               | 3         | 0.7%    |
| MediaTek                        | 3         | 0.7%    |
| Edimax Technology               | 3         | 0.7%    |
| Dell                            | 3         | 0.7%    |
| Realtek                         | 2         | 0.47%   |
| Alps Electric                   | 2         | 0.47%   |
| Integrated System Solution      | 1         | 0.23%   |
| HTC (High Tech Computer)        | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 86        | 19.86%  |
| Intel AX201 Bluetooth                               | 31        | 7.16%   |
| Intel AX200 Bluetooth                               | 31        | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 25        | 5.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24        | 5.54%   |
| Realtek Bluetooth Radio                             | 14        | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 2.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 2.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 2.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.85%   |
| Intel Bluetooth Device                              | 8         | 1.85%   |
| IMC Networks Wireless_Device                        | 8         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.85%   |
| Apple Bluetooth Host Controller                     | 8         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.62%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.39%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 1.15%   |
| Intel AX210 Bluetooth                               | 5         | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.15%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.92%   |
| Lite-On Bluetooth Device                            | 4         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.92%   |
| MediaTek Wireless_Device                            | 3         | 0.69%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.69%   |
| Foxconn / Hon Hai Acer Module                       | 3         | 0.69%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.69%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.69%   |
| ASUS Bluetooth Radio                                | 3         | 0.69%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.46%   |
| Toshiba Bluetooth Radio                             | 2         | 0.46%   |
| Realtek Bluetooth Radio                             | 2         | 0.46%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 2         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 494       | 48.24%  |
| AMD                         | 234       | 22.85%  |
| Nvidia                      | 171       | 16.7%   |
| Logitech                    | 19        | 1.86%   |
| C-Media Electronics         | 16        | 1.56%   |
| Hewlett-Packard             | 8         | 0.78%   |
| Kingston Technology         | 6         | 0.59%   |
| SteelSeries ApS             | 5         | 0.49%   |
| Realtek Semiconductor       | 5         | 0.49%   |
| Lenovo                      | 5         | 0.49%   |
| Generalplus Technology      | 5         | 0.49%   |
| Plantronics                 | 4         | 0.39%   |
| Dell                        | 4         | 0.39%   |
| GYROCOM C&C                 | 3         | 0.29%   |
| GN Netcom                   | 3         | 0.29%   |
| Texas Instruments           | 2         | 0.2%    |
| Razer USA                   | 2         | 0.2%    |
| Microsoft                   | 2         | 0.2%    |
| JMTek                       | 2         | 0.2%    |
| FiiO Electronics Technology | 2         | 0.2%    |
| Creative Technology         | 2         | 0.2%    |
| Creative Labs               | 2         | 0.2%    |
| ASUSTek Computer            | 2         | 0.2%    |
| AKAI Professional M.I.      | 2         | 0.2%    |
| XMOS                        | 1         | 0.1%    |
| Trust International         | 1         | 0.1%    |
| RODE Microphones            | 1         | 0.1%    |
| RME                         | 1         | 0.1%    |
| No brand                    | 1         | 0.1%    |
| Micro Star International    | 1         | 0.1%    |
| Jieli Technology            | 1         | 0.1%    |
| Harman                      | 1         | 0.1%    |
| Google                      | 1         | 0.1%    |
| Giga-Byte Technology        | 1         | 0.1%    |
| DSEA A/S                    | 1         | 0.1%    |
| DCMT Technology             | 1         | 0.1%    |
| CMX Systems                 | 1         | 0.1%    |
| ClearOne Communications     | 1         | 0.1%    |
| Cambridge Silicon Radio     | 1         | 0.1%    |
| Blue Microphones            | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 66        | 5.49%   |
| Intel Sunrise Point-LP HD Audio                                            | 54        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 52        | 4.32%   |
| AMD Family 17h/19h HD Audio Controller                                     | 45        | 3.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 36        | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 28        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26        | 2.16%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26        | 2.16%   |
| AMD FCH Azalia Controller                                                  | 26        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23        | 1.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 23        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                   | 17        | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17        | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.33%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15        | 1.25%   |
| Intel 200 Series PCH HD Audio                                              | 14        | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12        | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 11        | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 10        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 0.83%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 10        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9         | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 9         | 0.75%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 90        | 20.69%  |
| SK hynix            | 87        | 20%     |
| Micron Technology   | 49        | 11.26%  |
| Kingston            | 45        | 10.34%  |
| Crucial             | 36        | 8.28%   |
| G.Skill             | 33        | 7.59%   |
| Unknown             | 22        | 5.06%   |
| A-DATA Technology   | 17        | 3.91%   |
| Corsair             | 13        | 2.99%   |
| Team                | 10        | 2.3%    |
| Elpida              | 6         | 1.38%   |
| Strontium           | 5         | 1.15%   |
| Ramaxel Technology  | 4         | 0.92%   |
| Transcend           | 3         | 0.69%   |
| Unknown (ABCD)      | 2         | 0.46%   |
| Shenzhen Mic        | 2         | 0.46%   |
| Nanya Technology    | 2         | 0.46%   |
| Hewlett-Packard     | 2         | 0.46%   |
| Unknown (0x8783)    | 1         | 0.23%   |
| pqi                 | 1         | 0.23%   |
| PNY                 | 1         | 0.23%   |
| Neo Forza           | 1         | 0.23%   |
| Innodisk            | 1         | 0.23%   |
| fef5                | 1         | 0.23%   |
| Apacer              | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 1.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 1.09%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 4         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 4         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.87%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 4         | 0.87%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s           | 3         | 0.66%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 3         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 3         | 0.66%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                 | 3         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 3         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.66%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.66%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 3         | 0.66%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 3         | 0.66%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s      | 3         | 0.66%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 2         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 2         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 2         | 0.44%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s        | 2         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 0.44%   |
| SK hynix RAM Module 16GB SODIMM DDR5 4800MT/s                | 2         | 0.44%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s        | 2         | 0.44%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s         | 2         | 0.44%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.44%   |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 2         | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.44%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 0.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 2         | 0.44%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s  | 2         | 0.44%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                 | 2         | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.44%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 170       | 47.09%  |
| DDR3    | 124       | 34.35%  |
| DDR2    | 12        | 3.32%   |
| Unknown | 12        | 3.32%   |
| SDRAM   | 11        | 3.05%   |
| DDR5    | 11        | 3.05%   |
| LPDDR3  | 10        | 2.77%   |
| LPDDR4  | 9         | 2.49%   |
| LPDDR5  | 2         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 205       | 57.42%  |
| DIMM         | 126       | 35.29%  |
| Row Of Chips | 19        | 5.32%   |
| Chip         | 3         | 0.84%   |
| Unknown      | 3         | 0.84%   |
| FB-DIMM      | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 135       | 35.62%  |
| 4096  | 102       | 26.91%  |
| 16384 | 73        | 19.26%  |
| 2048  | 43        | 11.35%  |
| 32768 | 21        | 5.54%   |
| 1024  | 4         | 1.06%   |
| 65536 | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 82        | 20.97%  |
| 3200    | 64        | 16.37%  |
| 2667    | 39        | 9.97%   |
| 1333    | 28        | 7.16%   |
| 2400    | 24        | 6.14%   |
| 3600    | 23        | 5.88%   |
| 2133    | 19        | 4.86%   |
| 1334    | 16        | 4.09%   |
| 1867    | 10        | 2.56%   |
| 1067    | 9         | 2.3%    |
| 667     | 8         | 2.05%   |
| 4800    | 7         | 1.79%   |
| 3733    | 6         | 1.53%   |
| 800     | 5         | 1.28%   |
| Unknown | 5         | 1.28%   |
| 2666    | 4         | 1.02%   |
| 8400    | 3         | 0.77%   |
| 6400    | 3         | 0.77%   |
| 5600    | 3         | 0.77%   |
| 4267    | 3         | 0.77%   |
| 4199    | 3         | 0.77%   |
| 2048    | 3         | 0.77%   |
| 1066    | 3         | 0.77%   |
| 3800    | 2         | 0.51%   |
| 3466    | 2         | 0.51%   |
| 3400    | 2         | 0.51%   |
| 2800    | 2         | 0.51%   |
| 1800    | 2         | 0.51%   |
| 975     | 2         | 0.51%   |
| 3534    | 1         | 0.26%   |
| 3333    | 1         | 0.26%   |
| 3151    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |
| 2465    | 1         | 0.26%   |
| 2448    | 1         | 0.26%   |
| 2000    | 1         | 0.26%   |
| 1866    | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 33.33%  |
| Brother Industries  | 8         | 33.33%  |
| Canon               | 4         | 16.67%  |
| Samsung Electronics | 1         | 4.17%   |
| Prolific Technology | 1         | 4.17%   |
| Fuji Xerox          | 1         | 4.17%   |
| Dymo-CoStar         | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| HP Officejet 4630 series         | 2         | 8.33%   |
| Brother Printer                  | 2         | 8.33%   |
| Samsung SCX-4100 Scanner         | 1         | 4.17%   |
| Prolific PL2305 Parallel Port    | 1         | 4.17%   |
| HP OfficeJet Pro 9010 series     | 1         | 4.17%   |
| HP OfficeJet 8010 series         | 1         | 4.17%   |
| HP LaserJet Professional P1102w  | 1         | 4.17%   |
| HP ENVY 4520 series              | 1         | 4.17%   |
| HP DeskJet 2300 series           | 1         | 4.17%   |
| HP DeskJet 2130 series           | 1         | 4.17%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 4.17%   |
| Dymo-CoStar LabelWriter 450      | 1         | 4.17%   |
| Canon TS3100 series              | 1         | 4.17%   |
| Canon MB5300 series              | 1         | 4.17%   |
| Canon LBP6000                    | 1         | 4.17%   |
| Canon i950                       | 1         | 4.17%   |
| Brother MFC-J430W                | 1         | 4.17%   |
| Brother MFC-9140CDN              | 1         | 4.17%   |
| Brother MFC-7340                 | 1         | 4.17%   |
| Brother HL-L3230CDW series       | 1         | 4.17%   |
| Brother HL-2270DW Laser Printer  | 1         | 4.17%   |
| Brother HL-1430 Laser Printer    | 1         | 4.17%   |

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


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 500F           | 1         | 33.33%  |
| Canon CanoScan LIDE 25             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 100       | 25.25%  |
| Logitech                               | 32        | 8.08%   |
| IMC Networks                           | 32        | 8.08%   |
| Microdia                               | 31        | 7.83%   |
| Realtek Semiconductor                  | 26        | 6.57%   |
| Sunplus Innovation Technology          | 23        | 5.81%   |
| Quanta                                 | 19        | 4.8%    |
| Bison Electronics                      | 17        | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.28%   |
| Apple                                  | 13        | 3.28%   |
| Suyin                                  | 12        | 3.03%   |
| Luxvisions Innotech Limited            | 10        | 2.53%   |
| Lite-On Technology                     | 10        | 2.53%   |
| Syntek                                 | 6         | 1.52%   |
| Samsung Electronics                    | 5         | 1.26%   |
| Acer                                   | 5         | 1.26%   |
| Ricoh                                  | 4         | 1.01%   |
| Primax Electronics                     | 4         | 1.01%   |
| Alcor Micro                            | 4         | 1.01%   |
| Z-Star Microelectronics                | 3         | 0.76%   |
| Silicon Motion                         | 3         | 0.76%   |
| GEMBIRD                                | 3         | 0.76%   |
| ARC International                      | 3         | 0.76%   |
| Importek                               | 2         | 0.51%   |
| Yealink Network Technology             | 1         | 0.25%   |
| Xiongmai                               | 1         | 0.25%   |
| Sonix Technology                       | 1         | 0.25%   |
| Novatek Microelectronics               | 1         | 0.25%   |
| Microsoft                              | 1         | 0.25%   |
| Lenovo                                 | 1         | 0.25%   |
| KYE Systems (Mouse Systems)            | 1         | 0.25%   |
| Intel                                  | 1         | 0.25%   |
| Google                                 | 1         | 0.25%   |
| Generalplus Technology                 | 1         | 0.25%   |
| EVGA                                   | 1         | 0.25%   |
| DigiTech                               | 1         | 0.25%   |
| AVer Information                       | 1         | 0.25%   |
| Asuscom Network                        | 1         | 0.25%   |
| Arkmicro Technologies                  | 1         | 0.25%   |
| ALi                                    | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 16        | 4.02%   |
| IMC Networks USB2.0 HD UVC WebCam             | 14        | 3.52%   |
| Chicony HP HD Camera                          | 13        | 3.27%   |
| Chicony HD WebCam                             | 12        | 3.02%   |
| Realtek Integrated_Webcam_HD                  | 11        | 2.76%   |
| IMC Networks Integrated Camera                | 10        | 2.51%   |
| Sunplus HP HD Webcam [Fixed]                  | 7         | 1.76%   |
| Microdia Integrated_Webcam_HD                 | 7         | 1.76%   |
| Logitech Webcam C270                          | 7         | 1.76%   |
| Apple Built-in iSight                         | 7         | 1.76%   |
| Sunplus Integrated_Webcam_HD                  | 6         | 1.51%   |
| Microdia Integrated Webcam HD                 | 6         | 1.51%   |
| Chicony HP HD Webcam                          | 6         | 1.51%   |
| Bison Integrated Camera                       | 6         | 1.51%   |
| Samsung Galaxy A5 (MTP)                       | 5         | 1.26%   |
| Chicony TOSHIBA Web Camera - HD               | 5         | 1.26%   |
| Realtek HP Truevision HD                      | 4         | 1.01%   |
| Quanta HP TrueVision HD Camera                | 4         | 1.01%   |
| Quanta HP HD Camera                           | 4         | 1.01%   |
| Luxvisions Innotech Limited HP HD Camera      | 4         | 1.01%   |
| Logitech Webcam C170                          | 4         | 1.01%   |
| Logitech HD Pro Webcam C920                   | 4         | 1.01%   |
| Chicony HP Wide Vision HD Camera              | 4         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 4         | 1.01%   |
| Luxvisions Innotech Limited HP 5MP Camera     | 3         | 0.75%   |
| Logitech QuickCam Pro 9000                    | 3         | 0.75%   |
| Lite-On Integrated Camera                     | 3         | 0.75%   |
| Lite-On HP HD Camera                          | 3         | 0.75%   |
| Chicony VGA Webcam                            | 3         | 0.75%   |
| Chicony USB2.0 Camera                         | 3         | 0.75%   |
| Chicony Integrated HP HD Webcam               | 3         | 0.75%   |
| Bison SunplusIT Integrated Camera             | 3         | 0.75%   |
| ARC International Camera                      | 3         | 0.75%   |
| Apple FaceTime HD Camera (Built-in)           | 3         | 0.75%   |
| Syntek Integrated Camera                      | 2         | 0.5%    |
| Syntek EasyCamera                             | 2         | 0.5%    |
| Suyin HP Webcam                               | 2         | 0.5%    |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 0.5%    |
| Suyin HP Truevision HD                        | 2         | 0.5%    |
| Suyin 1.3M HD WebCam                          | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 54        | 48.65%  |
| Synaptics                  | 33        | 29.73%  |
| Shenzhen Goodix Technology | 7         | 6.31%   |
| AuthenTec                  | 6         | 5.41%   |
| Upek                       | 4         | 3.6%    |
| Elan Microelectronics      | 4         | 3.6%    |
| LighTuning Technology      | 2         | 1.8%    |
| STMicroelectronics         | 1         | 0.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 10.81%  |
| Validity Sensors VFS491                                                    | 7         | 6.31%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 5.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 5.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 5.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 4.5%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 4.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 3.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.6%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 3.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.6%    |
| Synaptics UWP WBDI                                                         | 3         | 2.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.7%    |
| Elan ELAN:Fingerprint                                                      | 3         | 2.7%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.8%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.8%    |
| Synaptics WBDI                                                             | 2         | 1.8%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.8%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.8%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.9%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.9%    |
| Synaptics  WBDI                                                            | 1         | 0.9%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.9%    |
| Elan ELAN:ARM-M4                                                           | 1         | 0.9%    |
| AuthenTec AES2810                                                          | 1         | 0.9%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.9%    |
| AuthenTec AES1600                                                          | 1         | 0.9%    |
| Unknown                                                                    | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 14        | 63.64%  |
| Lenovo      | 3         | 13.64%  |
| Alcor Micro | 3         | 13.64%  |
| Upek        | 1         | 4.55%   |
| O2 Micro    | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 7         | 31.82%  |
| Broadcom 58200                                             | 4         | 18.18%  |
| Lenovo Integrated Smart Card Reader                        | 3         | 13.64%  |
| Broadcom 5880                                              | 3         | 13.64%  |
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 485       | 66.35%  |
| 1     | 206       | 28.18%  |
| 2     | 32        | 4.38%   |
| 3     | 3         | 0.41%   |
| 6     | 2         | 0.27%   |
| 5     | 2         | 0.27%   |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 109       | 37.59%  |
| Graphics card            | 52        | 17.93%  |
| Net/wireless             | 41        | 14.14%  |
| Chipcard                 | 20        | 6.9%    |
| Multimedia controller    | 16        | 5.52%   |
| Bluetooth                | 9         | 3.1%    |
| Communication controller | 7         | 2.41%   |
| Sound                    | 6         | 2.07%   |
| Camera                   | 6         | 2.07%   |
| Unassigned class         | 5         | 1.72%   |
| Net/ethernet             | 4         | 1.38%   |
| Modem                    | 3         | 1.03%   |
| Dvb card                 | 3         | 1.03%   |
| Storage/ide              | 2         | 0.69%   |
| Network                  | 2         | 0.69%   |
| Card reader              | 2         | 0.69%   |
| Storage/raid             | 1         | 0.34%   |
| Storage                  | 1         | 0.34%   |
| Flash memory             | 1         | 0.34%   |

