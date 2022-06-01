Linux in Uruguay - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Uruguay/Desktop/README.md) and [notebooks](/Location/Uruguay/Notebook/README.md).

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

Total: 255

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 7590                 | Notebook    | [482ed9f535](https://linux-hardware.org/?probe=482ed9f535) | May 29, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [fa6da4906f](https://linux-hardware.org/?probe=fa6da4906f) | May 07, 2022 |
| Toshiba       | Satellite C645D             | Notebook    | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [7ad45f257f](https://linux-hardware.org/?probe=7ad45f257f) | Apr 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d2e2811388](https://linux-hardware.org/?probe=d2e2811388) | Apr 20, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2c6e96d91f](https://linux-hardware.org/?probe=2c6e96d91f) | Apr 18, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [73be944f6c](https://linux-hardware.org/?probe=73be944f6c) | Apr 14, 2022 |
| Dell          | Precision 7550              | Notebook    | [4619da9502](https://linux-hardware.org/?probe=4619da9502) | Apr 14, 2022 |
| Lenovo        | G405 20239                  | Notebook    | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7d203f8bc0](https://linux-hardware.org/?probe=7d203f8bc0) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [9bf7ed495b](https://linux-hardware.org/?probe=9bf7ed495b) | Mar 28, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [d9afd858b4](https://linux-hardware.org/?probe=d9afd858b4) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | Desktop     | [911987151a](https://linux-hardware.org/?probe=911987151a) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | Desktop     | [7d9cc6ac07](https://linux-hardware.org/?probe=7d9cc6ac07) | Mar 22, 2022 |
| HP            | ZBook 14u G4                | Notebook    | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| HP            | Pavilion dv5                | Notebook    | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| GPU Compan... | GWTN156-4                   | Notebook    | [89e7b9fa39](https://linux-hardware.org/?probe=89e7b9fa39) | Mar 02, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [9699b8889c](https://linux-hardware.org/?probe=9699b8889c) | Feb 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [37231251ed](https://linux-hardware.org/?probe=37231251ed) | Feb 21, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [52ca8c0d7c](https://linux-hardware.org/?probe=52ca8c0d7c) | Feb 13, 2022 |
| ECS           | SF20PA2                     | Notebook    | [3bddc7e08a](https://linux-hardware.org/?probe=3bddc7e08a) | Feb 11, 2022 |
| HP            | 3047h                       | Desktop     | [ee6260c5f4](https://linux-hardware.org/?probe=ee6260c5f4) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP            | 0AA8h                       | Desktop     | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Biostar       | Z490A-SILVER                | Desktop     | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [90f509fc24](https://linux-hardware.org/?probe=90f509fc24) | Dec 09, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [44b341f68d](https://linux-hardware.org/?probe=44b341f68d) | Nov 10, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [4e606c817f](https://linux-hardware.org/?probe=4e606c817f) | Nov 04, 2021 |
| ASRock        | N68-S                       | Desktop     | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [174875a3d4](https://linux-hardware.org/?probe=174875a3d4) | Oct 25, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [357ea9ab5d](https://linux-hardware.org/?probe=357ea9ab5d) | Oct 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [c04d448530](https://linux-hardware.org/?probe=c04d448530) | Oct 21, 2021 |
| ASUSTek       | Q324UAK                     | Convertible | [a8334894c5](https://linux-hardware.org/?probe=a8334894c5) | Oct 19, 2021 |
| Lenovo        | B51-30 80LK                 | Notebook    | [dea10156c6](https://linux-hardware.org/?probe=dea10156c6) | Sep 20, 2021 |
| Haitech       | H7141A                      | Notebook    | [496c0eb316](https://linux-hardware.org/?probe=496c0eb316) | Sep 18, 2021 |
| ECS           | SF20PA2                     | Notebook    | [6d17cf08ad](https://linux-hardware.org/?probe=6d17cf08ad) | Sep 12, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [fea193c839](https://linux-hardware.org/?probe=fea193c839) | Sep 10, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [dbeb8785e6](https://linux-hardware.org/?probe=dbeb8785e6) | Sep 01, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [fef0710fbd](https://linux-hardware.org/?probe=fef0710fbd) | Aug 24, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| Lenovo        | ThinkPad L490 20Q6S0NF00    | Notebook    | [a8f222614b](https://linux-hardware.org/?probe=a8f222614b) | Aug 11, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | Notebook    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | Notebook    | [4781e962e7](https://linux-hardware.org/?probe=4781e962e7) | Aug 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| HP            | Pavilion 15                 | Notebook    | [ec0019224a](https://linux-hardware.org/?probe=ec0019224a) | Jul 28, 2021 |
| ECS           | SF20PA2                     | Notebook    | [2016dfe42c](https://linux-hardware.org/?probe=2016dfe42c) | Jul 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b6c401b55e](https://linux-hardware.org/?probe=b6c401b55e) | Jul 15, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [27582e9e17](https://linux-hardware.org/?probe=27582e9e17) | Jun 21, 2021 |
| Acer          | TravelMate 5730             | Notebook    | [4a21735ce1](https://linux-hardware.org/?probe=4a21735ce1) | Jun 17, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [38ee95b416](https://linux-hardware.org/?probe=38ee95b416) | Jun 02, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [9357025bc9](https://linux-hardware.org/?probe=9357025bc9) | Jun 01, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ab4b1b7a15](https://linux-hardware.org/?probe=ab4b1b7a15) | May 31, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| HP            | Pavilion 17                 | Notebook    | [f12450cc62](https://linux-hardware.org/?probe=f12450cc62) | May 28, 2021 |
| Lenovo        | ThinkPad T590 20N5S2GP05    | Notebook    | [2444839350](https://linux-hardware.org/?probe=2444839350) | May 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [212d434e24](https://linux-hardware.org/?probe=212d434e24) | May 25, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [cb57bbefd0](https://linux-hardware.org/?probe=cb57bbefd0) | May 22, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [297e5b458a](https://linux-hardware.org/?probe=297e5b458a) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [0ed78505e8](https://linux-hardware.org/?probe=0ed78505e8) | May 19, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [321e5159ac](https://linux-hardware.org/?probe=321e5159ac) | May 15, 2021 |
| ECS           | SF20PA2                     | Notebook    | [f3cc58b0e4](https://linux-hardware.org/?probe=f3cc58b0e4) | May 13, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [6f67fbb9d4](https://linux-hardware.org/?probe=6f67fbb9d4) | May 08, 2021 |
| ECS           | SF20PA2                     | Notebook    | [cfbd36f40b](https://linux-hardware.org/?probe=cfbd36f40b) | May 07, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d1c6c7309a](https://linux-hardware.org/?probe=d1c6c7309a) | May 03, 2021 |
| ASUSTek       | N46VJ                       | Notebook    | [0d6e007969](https://linux-hardware.org/?probe=0d6e007969) | Apr 28, 2021 |
| Standard      | SF20BA2                     | Notebook    | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [bcee870f79](https://linux-hardware.org/?probe=bcee870f79) | Apr 24, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7d28bb0ba2](https://linux-hardware.org/?probe=7d28bb0ba2) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [5042e6d421](https://linux-hardware.org/?probe=5042e6d421) | Apr 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Dell          | Inspiron 5565               | Notebook    | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | 240 G7                      | Notebook    | [721c4c3dbd](https://linux-hardware.org/?probe=721c4c3dbd) | Apr 14, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2296b37506](https://linux-hardware.org/?probe=2296b37506) | Apr 12, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [9a7aa83895](https://linux-hardware.org/?probe=9a7aa83895) | Apr 07, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [9b0d9c1623](https://linux-hardware.org/?probe=9b0d9c1623) | Apr 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [118abf533e](https://linux-hardware.org/?probe=118abf533e) | Mar 28, 2021 |
| Supermicro    | P4DMS                       | Desktop     | [34867ad122](https://linux-hardware.org/?probe=34867ad122) | Mar 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Supermicro    | P4DMS                       | Desktop     | [9de21bc6ec](https://linux-hardware.org/?probe=9de21bc6ec) | Mar 14, 2021 |
| MSI           | GL65 Leopard 10SCXR         | Notebook    | [8497db47ab](https://linux-hardware.org/?probe=8497db47ab) | Mar 09, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [c1d21b6940](https://linux-hardware.org/?probe=c1d21b6940) | Mar 01, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [901fd74eaa](https://linux-hardware.org/?probe=901fd74eaa) | Feb 20, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7f1fc20897](https://linux-hardware.org/?probe=7f1fc20897) | Feb 19, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [9527a6802e](https://linux-hardware.org/?probe=9527a6802e) | Feb 19, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f51dac04a1](https://linux-hardware.org/?probe=f51dac04a1) | Feb 17, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [bea8cc11d5](https://linux-hardware.org/?probe=bea8cc11d5) | Feb 17, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9473725930](https://linux-hardware.org/?probe=9473725930) | Feb 15, 2021 |
| Unknown       | Unknown                     | Phone       | [d561348222](https://linux-hardware.org/?probe=d561348222) | Feb 14, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [0b52890aaf](https://linux-hardware.org/?probe=0b52890aaf) | Jan 29, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [3a777180a1](https://linux-hardware.org/?probe=3a777180a1) | Jan 29, 2021 |
| Intel         | H61M-DS2                    | Desktop     | [930418d2da](https://linux-hardware.org/?probe=930418d2da) | Jan 23, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [4b7df9598e](https://linux-hardware.org/?probe=4b7df9598e) | Jan 20, 2021 |
| MSI           | GL65 Leopard 10SCXR         | Notebook    | [ac71737361](https://linux-hardware.org/?probe=ac71737361) | Jan 16, 2021 |
| Intel         | H61M-DS2                    | Desktop     | [53bde98202](https://linux-hardware.org/?probe=53bde98202) | Jan 09, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Toshiba       | Satellite L55t-B            | Notebook    | [ab3b576bd1](https://linux-hardware.org/?probe=ab3b576bd1) | Jan 07, 2021 |
| Toshiba       | Satellite L55t-B            | Notebook    | [6fc9533a15](https://linux-hardware.org/?probe=6fc9533a15) | Jan 06, 2021 |
| ECS           | SF20PA2                     | Notebook    | [f26e0bf23f](https://linux-hardware.org/?probe=f26e0bf23f) | Jan 04, 2021 |
| HP            | 2000                        | Notebook    | [99481f08e3](https://linux-hardware.org/?probe=99481f08e3) | Dec 31, 2020 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | Notebook                    | Notebook    | [213a94eab7](https://linux-hardware.org/?probe=213a94eab7) | Dec 28, 2020 |
| HP            | Notebook                    | Notebook    | [bb3749dd61](https://linux-hardware.org/?probe=bb3749dd61) | Dec 28, 2020 |
| MSI           | A55M-P33                    | Desktop     | [43267cc6f4](https://linux-hardware.org/?probe=43267cc6f4) | Dec 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f55e2642ef](https://linux-hardware.org/?probe=f55e2642ef) | Dec 15, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [729161e56a](https://linux-hardware.org/?probe=729161e56a) | Dec 08, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [37f7b460d4](https://linux-hardware.org/?probe=37f7b460d4) | Dec 08, 2020 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f158fc821a](https://linux-hardware.org/?probe=f158fc821a) | Nov 10, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [19081a3c58](https://linux-hardware.org/?probe=19081a3c58) | Oct 27, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8ea63ec090](https://linux-hardware.org/?probe=8ea63ec090) | Oct 23, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [912852805f](https://linux-hardware.org/?probe=912852805f) | Oct 22, 2020 |
| HP            | Pavilion dm4                | Notebook    | [21a3ef42e0](https://linux-hardware.org/?probe=21a3ef42e0) | Oct 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [64e95b4174](https://linux-hardware.org/?probe=64e95b4174) | Oct 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0ffffb855b](https://linux-hardware.org/?probe=0ffffb855b) | Oct 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7ddfb80220](https://linux-hardware.org/?probe=7ddfb80220) | Oct 04, 2020 |
| Dell          | 0C27VV A00                  | Desktop     | [fd9547e219](https://linux-hardware.org/?probe=fd9547e219) | Oct 01, 2020 |
| Toshiba       | Satellite C75D-C            | Notebook    | [12c65e3222](https://linux-hardware.org/?probe=12c65e3222) | Sep 25, 2020 |
| Unknown       | Unknown                     | Phone       | [6ff556bf54](https://linux-hardware.org/?probe=6ff556bf54) | Sep 06, 2020 |
| MSI           | GE62 6QD                    | Notebook    | [cf444064fc](https://linux-hardware.org/?probe=cf444064fc) | Sep 03, 2020 |
| Acer          | One S1003                   | Tablet      | [c89be38d5c](https://linux-hardware.org/?probe=c89be38d5c) | Aug 29, 2020 |
| HP            | Casablanca H710             | Notebook    | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | Notebook    | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [f425b1dc48](https://linux-hardware.org/?probe=f425b1dc48) | Aug 17, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [759ee832fb](https://linux-hardware.org/?probe=759ee832fb) | Aug 17, 2020 |
| Gigabyte      | H310M A-CF                  | Desktop     | [ff30e910c4](https://linux-hardware.org/?probe=ff30e910c4) | Aug 12, 2020 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [0009968f3b](https://linux-hardware.org/?probe=0009968f3b) | Aug 05, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3c55f58986](https://linux-hardware.org/?probe=3c55f58986) | Jul 03, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d4c35c226e](https://linux-hardware.org/?probe=d4c35c226e) | Jul 01, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [178da315d2](https://linux-hardware.org/?probe=178da315d2) | Jul 01, 2020 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [6a4b069ed8](https://linux-hardware.org/?probe=6a4b069ed8) | Jun 30, 2020 |
| HP            | Presario CQ43               | Notebook    | [bba4f49ed1](https://linux-hardware.org/?probe=bba4f49ed1) | Jun 23, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [70acf4ea22](https://linux-hardware.org/?probe=70acf4ea22) | Jun 18, 2020 |
| HP            | Presario CQ43               | Notebook    | [3af51e5df2](https://linux-hardware.org/?probe=3af51e5df2) | Jun 13, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9f2577531a](https://linux-hardware.org/?probe=9f2577531a) | Jun 10, 2020 |
| ECS           | SF20PA2                     | Notebook    | [fc1653c118](https://linux-hardware.org/?probe=fc1653c118) | Jun 10, 2020 |
| Dell          | Inspiron 5748               | Notebook    | [d7010adabe](https://linux-hardware.org/?probe=d7010adabe) | Jun 09, 2020 |
| OEM           | V40SI2                      | Notebook    | [e2ad8d9479](https://linux-hardware.org/?probe=e2ad8d9479) | Jun 06, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [13b3a46069](https://linux-hardware.org/?probe=13b3a46069) | May 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [7e4107b1b4](https://linux-hardware.org/?probe=7e4107b1b4) | May 26, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [0a5437ade3](https://linux-hardware.org/?probe=0a5437ade3) | May 22, 2020 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [7e4e3c078f](https://linux-hardware.org/?probe=7e4e3c078f) | May 20, 2020 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [627fed813d](https://linux-hardware.org/?probe=627fed813d) | May 18, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [493ce118d1](https://linux-hardware.org/?probe=493ce118d1) | May 16, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [154224ff78](https://linux-hardware.org/?probe=154224ff78) | May 16, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [173008c9ff](https://linux-hardware.org/?probe=173008c9ff) | May 16, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [98a86c1397](https://linux-hardware.org/?probe=98a86c1397) | May 15, 2020 |
| MSI           | GL63 8RD                    | Notebook    | [7e41ab8d71](https://linux-hardware.org/?probe=7e41ab8d71) | May 15, 2020 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [1beb748dc0](https://linux-hardware.org/?probe=1beb748dc0) | May 12, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3b397b64f7](https://linux-hardware.org/?probe=3b397b64f7) | May 06, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a9832cd92e](https://linux-hardware.org/?probe=a9832cd92e) | May 05, 2020 |
| HP            | 090Ch                       | Desktop     | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | Desktop     | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a8857822b2](https://linux-hardware.org/?probe=a8857822b2) | May 03, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [8609a3503d](https://linux-hardware.org/?probe=8609a3503d) | May 02, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7fdc3c7af9](https://linux-hardware.org/?probe=7fdc3c7af9) | May 02, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [1532d55ba0](https://linux-hardware.org/?probe=1532d55ba0) | May 01, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [c931341a8c](https://linux-hardware.org/?probe=c931341a8c) | May 01, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [e52c07ce77](https://linux-hardware.org/?probe=e52c07ce77) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS72901    | Notebook    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Gateway       | DX4375                      | Desktop     | [1470b063f3](https://linux-hardware.org/?probe=1470b063f3) | Apr 28, 2020 |
| Standard      | EF20EA                      | Notebook    | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| ECS           | H310H5-M2                   | Desktop     | [b1aaebf57b](https://linux-hardware.org/?probe=b1aaebf57b) | Apr 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [3be039900b](https://linux-hardware.org/?probe=3be039900b) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [cf6e400de0](https://linux-hardware.org/?probe=cf6e400de0) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [bb8bd669f6](https://linux-hardware.org/?probe=bb8bd669f6) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [f1caefcea5](https://linux-hardware.org/?probe=f1caefcea5) | Apr 17, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [3036b319ab](https://linux-hardware.org/?probe=3036b319ab) | Apr 16, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [ebd210c2af](https://linux-hardware.org/?probe=ebd210c2af) | Apr 16, 2020 |
| HP            | 620                         | Notebook    | [812b274fd4](https://linux-hardware.org/?probe=812b274fd4) | Apr 13, 2020 |
| HP            | 620                         | Notebook    | [ca26b96168](https://linux-hardware.org/?probe=ca26b96168) | Apr 13, 2020 |
| Acer          | One S1003                   | Tablet      | [f1cf80584b](https://linux-hardware.org/?probe=f1cf80584b) | Apr 07, 2020 |
| MSI           | G31M2                       | Desktop     | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| HP            | 1497                        | Desktop     | [973b170ac6](https://linux-hardware.org/?probe=973b170ac6) | Mar 23, 2020 |
| Lenovo        | 312D NOK                    | Mini pc     | [36cb7c6a75](https://linux-hardware.org/?probe=36cb7c6a75) | Mar 23, 2020 |
| HP            | 1497                        | Desktop     | [26d8104c5e](https://linux-hardware.org/?probe=26d8104c5e) | Mar 02, 2020 |
| ECS           | SF20PA2                     | Notebook    | [d685560200](https://linux-hardware.org/?probe=d685560200) | Feb 01, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [743f3ff81c](https://linux-hardware.org/?probe=743f3ff81c) | Dec 22, 2019 |
| MSI           | A68HM-E33 V2                | Desktop     | [1d3a9ef0d2](https://linux-hardware.org/?probe=1d3a9ef0d2) | Dec 22, 2019 |
| MSI           | A68HM-E33 V2                | Desktop     | [806c1e6d78](https://linux-hardware.org/?probe=806c1e6d78) | Dec 22, 2019 |
| ECS           | SF20PA2                     | Notebook    | [e6212ece14](https://linux-hardware.org/?probe=e6212ece14) | Nov 27, 2019 |
| ECS           | SF20PA2                     | Notebook    | [1d4a07f181](https://linux-hardware.org/?probe=1d4a07f181) | Nov 19, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [1fab0cb871](https://linux-hardware.org/?probe=1fab0cb871) | Nov 16, 2019 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [c28821415f](https://linux-hardware.org/?probe=c28821415f) | Nov 15, 2019 |
| ECS           | SF20PA2                     | Notebook    | [063490d972](https://linux-hardware.org/?probe=063490d972) | Nov 03, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [273463747b](https://linux-hardware.org/?probe=273463747b) | Oct 29, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [dfda14135d](https://linux-hardware.org/?probe=dfda14135d) | Oct 28, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [3418011c79](https://linux-hardware.org/?probe=3418011c79) | Oct 27, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [cb622d3902](https://linux-hardware.org/?probe=cb622d3902) | Oct 27, 2019 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [623c96ec6e](https://linux-hardware.org/?probe=623c96ec6e) | Oct 07, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [0925f5642c](https://linux-hardware.org/?probe=0925f5642c) | Sep 24, 2019 |
| ECS           | SF20PA2                     | Notebook    | [3c9b29c0c7](https://linux-hardware.org/?probe=3c9b29c0c7) | Sep 20, 2019 |
| ECS           | SF20PA2                     | Notebook    | [6d35e092fa](https://linux-hardware.org/?probe=6d35e092fa) | Sep 16, 2019 |
| Dell          | Inspiron 13-5368            | Notebook    | [0dab5b3510](https://linux-hardware.org/?probe=0dab5b3510) | Sep 15, 2019 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [00a1738003](https://linux-hardware.org/?probe=00a1738003) | Aug 14, 2019 |
| ECS           | SF20PA2                     | Notebook    | [80d3b6b8cf](https://linux-hardware.org/?probe=80d3b6b8cf) | Aug 04, 2019 |
| ECS           | SF20PA2                     | Notebook    | [a7b095e2f0](https://linux-hardware.org/?probe=a7b095e2f0) | Jul 30, 2019 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [001551b002](https://linux-hardware.org/?probe=001551b002) | Jul 22, 2019 |
| ECS           | SF20PA2                     | Notebook    | [01cad0b14a](https://linux-hardware.org/?probe=01cad0b14a) | Jul 10, 2019 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [0e1338db33](https://linux-hardware.org/?probe=0e1338db33) | Jul 01, 2019 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [30ff6dab9f](https://linux-hardware.org/?probe=30ff6dab9f) | Jun 13, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [08c0f291e9](https://linux-hardware.org/?probe=08c0f291e9) | Jun 13, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [5619d594fa](https://linux-hardware.org/?probe=5619d594fa) | Jun 10, 2019 |
| ASUSTek       | M5A87                       | Desktop     | [cead36d312](https://linux-hardware.org/?probe=cead36d312) | May 18, 2019 |
| ASUSTek       | M5A87                       | Desktop     | [6dfdec0635](https://linux-hardware.org/?probe=6dfdec0635) | May 18, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [b8f0a4691d](https://linux-hardware.org/?probe=b8f0a4691d) | May 17, 2019 |
| HP            | 1998                        | Desktop     | [0ae1b2ac01](https://linux-hardware.org/?probe=0ae1b2ac01) | May 13, 2019 |
| Samsung       | 700T                        | Notebook    | [dcf693f16f](https://linux-hardware.org/?probe=dcf693f16f) | May 11, 2019 |
| HP            | Pavilion dv6                | Notebook    | [36299cef92](https://linux-hardware.org/?probe=36299cef92) | Apr 17, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b26531074c](https://linux-hardware.org/?probe=b26531074c) | Apr 16, 2019 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [547801f07c](https://linux-hardware.org/?probe=547801f07c) | Apr 15, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [7d9905cfe7](https://linux-hardware.org/?probe=7d9905cfe7) | Mar 27, 2019 |
| ASUSTek       | TP300LAB                    | Notebook    | [538b5e5d24](https://linux-hardware.org/?probe=538b5e5d24) | Mar 26, 2019 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [859c76fdf7](https://linux-hardware.org/?probe=859c76fdf7) | Mar 17, 2019 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [4684e2d239](https://linux-hardware.org/?probe=4684e2d239) | Dec 04, 2018 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [a26c805e14](https://linux-hardware.org/?probe=a26c805e14) | Dec 04, 2018 |
| MSI           | G41M-P26                    | Desktop     | [59c7d54670](https://linux-hardware.org/?probe=59c7d54670) | Nov 10, 2018 |
| HP            | Pavilion 15                 | Notebook    | [7376903dca](https://linux-hardware.org/?probe=7376903dca) | May 13, 2018 |
| HP            | Pavilion 15                 | Notebook    | [2cc0124d5d](https://linux-hardware.org/?probe=2cc0124d5d) | May 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 33        | 17.84%  |
| Ubuntu 18.04                 | 28        | 15.14%  |
| KDE neon 20.04               | 7         | 3.78%   |
| OpenMandriva 4.2             | 6         | 3.24%   |
| Linux Mint 19.3              | 6         | 3.24%   |
| Ubuntu 19.04                 | 5         | 2.7%    |
| OpenMandriva 4.3             | 5         | 2.7%    |
| Xubuntu 20.04                | 4         | 2.16%   |
| Ubuntu 21.10                 | 4         | 2.16%   |
| Ubuntu 18.10                 | 4         | 2.16%   |
| Manjaro                      | 4         | 2.16%   |
| Xubuntu 18.04                | 3         | 1.62%   |
| ROSA R11.1                   | 3         | 1.62%   |
| Linux Mint 20                | 3         | 1.62%   |
| Linux Mint 19.1              | 3         | 1.62%   |
| BlackPanther 18.1            | 3         | 1.62%   |
| Arch Rolling                 | 3         | 1.62%   |
| Arch                         | 3         | 1.62%   |
| Zorin 15                     | 2         | 1.08%   |
| Ubuntu 21.04                 | 2         | 1.08%   |
| Ubuntu 19.10                 | 2         | 1.08%   |
| Pop!_OS 20.04                | 2         | 1.08%   |
| Linux Mint 20.2              | 2         | 1.08%   |
| Linux Mint 20.1              | 2         | 1.08%   |
| Linux Mint 19.2              | 2         | 1.08%   |
| Kubuntu 18.04                | 2         | 1.08%   |
| Fedora 34                    | 2         | 1.08%   |
| Android                      | 2         | 1.08%   |
| Zorin 16                     | 1         | 0.54%   |
| Xubuntu 21.04                | 1         | 0.54%   |
| Ubuntu MATE 20.04            | 1         | 0.54%   |
| Ubuntu 22.04                 | 1         | 0.54%   |
| Ubuntu 20.10                 | 1         | 0.54%   |
| Ubuntu 17.10                 | 1         | 0.54%   |
| Pop!_OS 21.10                | 1         | 0.54%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.54%   |
| openSUSE Leap-15.1           | 1         | 0.54%   |
| OpenMandriva 4.50            | 1         | 0.54%   |
| NixOS 21.05.4384.4f37689c8a2 | 1         | 0.54%   |
| Manjaro 21.2.0               | 1         | 0.54%   |
| Lubuntu 20.04                | 1         | 0.54%   |
| Lubuntu 19.10                | 1         | 0.54%   |
| Lubuntu 18.04                | 1         | 0.54%   |
| Lubuntu 16.10                | 1         | 0.54%   |
| LMDE 4                       | 1         | 0.54%   |
| Linux Mint 19                | 1         | 0.54%   |
| Kubuntu 20.10                | 1         | 0.54%   |
| Kubuntu 20.04                | 1         | 0.54%   |
| KDE neon 18.04               | 1         | 0.54%   |
| Gentoo 2.8                   | 1         | 0.54%   |
| Feren OS 18.04               | 1         | 0.54%   |
| Fedora 35                    | 1         | 0.54%   |
| Fedora 33                    | 1         | 0.54%   |
| Fedora 31                    | 1         | 0.54%   |
| Fedora 30                    | 1         | 0.54%   |
| Endless 3.8.7                | 1         | 0.54%   |
| Endless 3.8.6                | 1         | 0.54%   |
| Endless 3.7.8                | 1         | 0.54%   |
| Endless 3.6.2                | 1         | 0.54%   |
| Endless 3.4.2-nexthw1        | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 78        | 42.86%  |
| Linux Mint   | 19        | 10.44%  |
| OpenMandriva | 12        | 6.59%   |
| Xubuntu      | 8         | 4.4%    |
| KDE neon     | 8         | 4.4%    |
| Fedora       | 6         | 3.3%    |
| Arch         | 6         | 3.3%    |
| Manjaro      | 5         | 2.75%   |
| Endless      | 5         | 2.75%   |
| Lubuntu      | 4         | 2.2%    |
| Kubuntu      | 4         | 2.2%    |
| Zorin        | 3         | 1.65%   |
| ROSA         | 3         | 1.65%   |
| Pop!_OS      | 3         | 1.65%   |
| BlackPanther | 3         | 1.65%   |
| openSUSE     | 2         | 1.1%    |
| Elementary   | 2         | 1.1%    |
| Debian       | 2         | 1.1%    |
| Android      | 2         | 1.1%    |
| Ubuntu MATE  | 1         | 0.55%   |
| NixOS        | 1         | 0.55%   |
| LMDE         | 1         | 0.55%   |
| Gentoo       | 1         | 0.55%   |
| Feren OS     | 1         | 0.55%   |
| EndeavourOS  | 1         | 0.55%   |
| ArcoLinux    | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 6         | 3.08%   |
| 5.10.14-desktop-1omv4002    | 6         | 3.08%   |
| 4.16.18-pa2-2bp1            | 6         | 3.08%   |
| 5.11.0-38-generic           | 5         | 2.56%   |
| 4.16.18-pa2-1bp5            | 5         | 2.56%   |
| 5.8.0-53-generic            | 4         | 2.05%   |
| 5.4.0-52-generic            | 4         | 2.05%   |
| 5.3.0-46-generic            | 4         | 2.05%   |
| 5.16.7-desktop-1omv4003     | 4         | 2.05%   |
| 5.13.0-39-generic           | 4         | 2.05%   |
| 5.4.0-73-generic            | 3         | 1.54%   |
| 5.4.0-72-generic            | 3         | 1.54%   |
| 5.4.0-65-generic            | 3         | 1.54%   |
| 5.4.0-58-generic            | 3         | 1.54%   |
| 5.0.0-32-generic            | 3         | 1.54%   |
| 4.18.16-desktop-1bP         | 3         | 1.54%   |
| 5.8.0-50-generic            | 2         | 1.03%   |
| 5.8.0-43-generic            | 2         | 1.03%   |
| 5.5.19-bp0                  | 2         | 1.03%   |
| 5.4.83-generic-2rosa-x86_64 | 2         | 1.03%   |
| 5.4.0-62-generic            | 2         | 1.03%   |
| 5.4.0-39-generic            | 2         | 1.03%   |
| 5.3.0-51-generic            | 2         | 1.03%   |
| 5.3.0-28-generic            | 2         | 1.03%   |
| 5.13.0-40-generic           | 2         | 1.03%   |
| 5.13.0-37-generic           | 2         | 1.03%   |
| 5.13.0-30-generic           | 2         | 1.03%   |
| 5.13.0-22-generic           | 2         | 1.03%   |
| 5.11.12-desktop-1omv4002    | 2         | 1.03%   |
| 5.0.0-13-generic            | 2         | 1.03%   |
| 4.18.0-17-generic           | 2         | 1.03%   |
| 4.18.0-15-generic           | 2         | 1.03%   |
| 4.15.0-99-generic           | 2         | 1.03%   |
| 4.15.0-51-generic           | 2         | 1.03%   |
| 4.15.0-20-generic           | 2         | 1.03%   |
| 4.15.0-101-generic          | 2         | 1.03%   |
| 5.8.11-1-MANJARO            | 1         | 0.51%   |
| 5.8.1-3-MANJARO             | 1         | 0.51%   |
| 5.8.0-49-generic            | 1         | 0.51%   |
| 5.8.0-48-generic            | 1         | 0.51%   |
| 5.8.0-44-generic            | 1         | 0.51%   |
| 5.8.0-34-generic            | 1         | 0.51%   |
| 5.6.8-1-MANJARO             | 1         | 0.51%   |
| 5.6.0-2-amd64               | 1         | 0.51%   |
| 5.4.60-1-lts                | 1         | 0.51%   |
| 5.4.32-generic-2rosa-x86_64 | 1         | 0.51%   |
| 5.4.0-92-lowlatency         | 1         | 0.51%   |
| 5.4.0-91-generic            | 1         | 0.51%   |
| 5.4.0-80-generic            | 1         | 0.51%   |
| 5.4.0-70-generic            | 1         | 0.51%   |
| 5.4.0-59-generic            | 1         | 0.51%   |
| 5.4.0-56-generic            | 1         | 0.51%   |
| 5.4.0-37-generic            | 1         | 0.51%   |
| 5.4.0-33-generic            | 1         | 0.51%   |
| 5.4.0-29-generic            | 1         | 0.51%   |
| 5.4.0-28-generic            | 1         | 0.51%   |
| 5.4.0-26-generic            | 1         | 0.51%   |
| 5.4.0-0.bpo.4-amd64         | 1         | 0.51%   |
| 5.3.7-301.fc31.x86_64       | 1         | 0.51%   |
| 5.3.0-40-generic            | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 37        | 19.37%  |
| 4.15.0  | 19        | 9.95%   |
| 5.13.0  | 13        | 6.81%   |
| 5.8.0   | 12        | 6.28%   |
| 5.11.0  | 12        | 6.28%   |
| 5.3.0   | 11        | 5.76%   |
| 4.16.18 | 11        | 5.76%   |
| 5.0.0   | 10        | 5.24%   |
| 4.18.0  | 8         | 4.19%   |
| 5.10.14 | 6         | 3.14%   |
| 5.16.7  | 4         | 2.09%   |
| 4.18.16 | 3         | 1.57%   |
| 5.5.19  | 2         | 1.05%   |
| 5.4.83  | 2         | 1.05%   |
| 5.11.12 | 2         | 1.05%   |
| 5.8.11  | 1         | 0.52%   |
| 5.8.1   | 1         | 0.52%   |
| 5.6.8   | 1         | 0.52%   |
| 5.6.0   | 1         | 0.52%   |
| 5.4.60  | 1         | 0.52%   |
| 5.4.32  | 1         | 0.52%   |
| 5.3.7   | 1         | 0.52%   |
| 5.2.13  | 1         | 0.52%   |
| 5.17.4  | 1         | 0.52%   |
| 5.16.16 | 1         | 0.52%   |
| 5.16.13 | 1         | 0.52%   |
| 5.16.12 | 1         | 0.52%   |
| 5.16.0  | 1         | 0.52%   |
| 5.15.3  | 1         | 0.52%   |
| 5.15.23 | 1         | 0.52%   |
| 5.15.0  | 1         | 0.52%   |
| 5.14.18 | 1         | 0.52%   |
| 5.14.11 | 1         | 0.52%   |
| 5.13.12 | 1         | 0.52%   |
| 5.12.8  | 1         | 0.52%   |
| 5.12.4  | 1         | 0.52%   |
| 5.12.3  | 1         | 0.52%   |
| 5.12.15 | 1         | 0.52%   |
| 5.11.20 | 1         | 0.52%   |
| 5.11.18 | 1         | 0.52%   |
| 5.11.15 | 1         | 0.52%   |
| 5.11.11 | 1         | 0.52%   |
| 5.10.4  | 1         | 0.52%   |
| 5.10.31 | 1         | 0.52%   |
| 5.10.30 | 1         | 0.52%   |
| 5.10.16 | 1         | 0.52%   |
| 5.10.0  | 1         | 0.52%   |
| 4.9.234 | 1         | 0.52%   |
| 4.8.0   | 1         | 0.52%   |
| 4.4.247 | 1         | 0.52%   |
| 4.17.19 | 1         | 0.52%   |
| 4.16.0  | 1         | 0.52%   |
| 4.13.0  | 1         | 0.52%   |
| 4.12.14 | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 21.47%  |
| 4.15    | 19        | 9.95%   |
| 5.11    | 18        | 9.42%   |
| 5.8     | 14        | 7.33%   |
| 5.13    | 14        | 7.33%   |
| 5.3     | 12        | 6.28%   |
| 4.16    | 12        | 6.28%   |
| 5.10    | 11        | 5.76%   |
| 4.18    | 11        | 5.76%   |
| 5.0     | 10        | 5.24%   |
| 5.16    | 8         | 4.19%   |
| 5.12    | 4         | 2.09%   |
| 5.15    | 3         | 1.57%   |
| 5.6     | 2         | 1.05%   |
| 5.5     | 2         | 1.05%   |
| 5.14    | 2         | 1.05%   |
| 5.2     | 1         | 0.52%   |
| 5.17    | 1         | 0.52%   |
| 4.9     | 1         | 0.52%   |
| 4.8     | 1         | 0.52%   |
| 4.4     | 1         | 0.52%   |
| 4.17    | 1         | 0.52%   |
| 4.13    | 1         | 0.52%   |
| 4.12    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 169       | 96.02%  |
| i686   | 5         | 2.84%   |
| armv8l | 2         | 1.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 60        | 32.79%  |
| Unknown         | 34        | 18.58%  |
| KDE5            | 28        | 15.3%   |
| XFCE            | 13        | 7.1%    |
| X-Cinnamon      | 11        | 6.01%   |
| GNOME Flashback | 11        | 6.01%   |
| KDE             | 7         | 3.83%   |
| MATE            | 5         | 2.73%   |
| LXQt            | 3         | 1.64%   |
| LXDE            | 3         | 1.64%   |
| Cinnamon        | 3         | 1.64%   |
| Pantheon        | 2         | 1.09%   |
| KDE4            | 2         | 1.09%   |
| sway            | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 146       | 81.56%  |
| Unknown | 17        | 9.5%    |
| Wayland | 15        | 8.38%   |
| Tty     | 1         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 100       | 55.87%  |
| GDM     | 28        | 15.64%  |
| SDDM    | 27        | 15.08%  |
| LightDM | 10        | 5.59%   |
| GDM3    | 7         | 3.91%   |
| TDM     | 4         | 2.23%   |
| KDM     | 2         | 1.12%   |
| GREETD  | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_UY   | 86        | 46.74%  |
| en_US   | 33        | 17.93%  |
| Unknown | 31        | 16.85%  |
| es_ES   | 20        | 10.87%  |
| es_AR   | 6         | 3.26%   |
| es_MX   | 3         | 1.63%   |
| C       | 3         | 1.63%   |
| POSIX   | 1         | 0.54%   |
| en_CA   | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 92        | 51.69%  |
| EFI  | 86        | 48.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 151       | 84.36%  |
| Overlay | 14        | 7.82%   |
| Unknown | 8         | 4.47%   |
| Btrfs   | 4         | 2.23%   |
| Xfs     | 1         | 0.56%   |
| Ext3    | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 116       | 65.17%  |
| GPT     | 44        | 24.72%  |
| MBR     | 18        | 10.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 81.36%  |
| Yes       | 33        | 18.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 65.17%  |
| Yes       | 62        | 34.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 29        | 16.48%  |
| Lenovo              | 23        | 13.07%  |
| ASUSTek Computer    | 22        | 12.5%   |
| Dell                | 15        | 8.52%   |
| ECS                 | 14        | 7.95%   |
| MSI                 | 11        | 6.25%   |
| ASRock              | 11        | 6.25%   |
| Acer                | 11        | 6.25%   |
| Gigabyte Technology | 10        | 5.68%   |
| Toshiba             | 6         | 3.41%   |
| Samsung Electronics | 4         | 2.27%   |
| Standard            | 3         | 1.7%    |
| Intel               | 3         | 1.7%    |
| Unknown             | 2         | 1.14%   |
| Supermicro          | 1         | 0.57%   |
| Sony                | 1         | 0.57%   |
| Positivo            | 1         | 0.57%   |
| Panasonic           | 1         | 0.57%   |
| OEM                 | 1         | 0.57%   |
| Haitech             | 1         | 0.57%   |
| GPU Company         | 1         | 0.57%   |
| Gateway             | 1         | 0.57%   |
| Fujitsu             | 1         | 0.57%   |
| Foxconn             | 1         | 0.57%   |
| Biostar             | 1         | 0.57%   |
| Apple               | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ECS SF20PA2                                | 13        | 7.39%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 3         | 1.7%    |
| Toshiba Satellite L55t-B                   | 2         | 1.14%   |
| Standard SF20BA2                           | 2         | 1.14%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL0014LD | 2         | 1.14%   |
| HP Pavilion 15                             | 2         | 1.14%   |
| HP Laptop 15-bs0xx                         | 2         | 1.14%   |
| Gigabyte Z390 AORUS ELITE                  | 2         | 1.14%   |
| ASRock ALiveNF6P-VSTA                      | 2         | 1.14%   |
| Unknown                                    | 2         | 1.14%   |
| Toshiba Satellite C75D-C                   | 1         | 0.57%   |
| Toshiba Satellite C645D                    | 1         | 0.57%   |
| Toshiba Satellite C55-B                    | 1         | 0.57%   |
| Toshiba Satellite C45-A                    | 1         | 0.57%   |
| Supermicro P4DMS                           | 1         | 0.57%   |
| Standard EF20EA                            | 1         | 0.57%   |
| Sony SVF14211CLB                           | 1         | 0.57%   |
| Samsung NC208/NC108                        | 1         | 0.57%   |
| Samsung N102SP/N100SP/N101SP               | 1         | 0.57%   |
| Samsung 700T                               | 1         | 0.57%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.57%   |
| Positivo Serie AT300                       | 1         | 0.57%   |
| Panasonic CF-31JEGAX1M                     | 1         | 0.57%   |
| OEM V40SI2                                 | 1         | 0.57%   |
| MSI MS-7C37                                | 1         | 0.57%   |
| MSI MS-7817                                | 1         | 0.57%   |
| MSI MS-7816                                | 1         | 0.57%   |
| MSI MS-7786                                | 1         | 0.57%   |
| MSI MS-7721                                | 1         | 0.57%   |
| MSI MS-7592                                | 1         | 0.57%   |
| MSI MS-7383                                | 1         | 0.57%   |
| MSI GS63VR 6RF                             | 1         | 0.57%   |
| MSI GL65 Leopard 10SCXR                    | 1         | 0.57%   |
| MSI GL63 8RD                               | 1         | 0.57%   |
| MSI GE62 6QD                               | 1         | 0.57%   |
| Lenovo V15-ADA 82C7                        | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AMS72901            | 1         | 0.57%   |
| Lenovo ThinkPad T590 20N5S2GP05            | 1         | 0.57%   |
| Lenovo ThinkPad T450 20BUS0G91F            | 1         | 0.57%   |
| Lenovo ThinkPad S1 Yoga 20CDS02V00         | 1         | 0.57%   |
| Lenovo ThinkPad L490 20Q6S0NF00            | 1         | 0.57%   |
| Lenovo ThinkPad L14 Gen 2 20X2S2HG00       | 1         | 0.57%   |
| Lenovo ThinkPad Edge E540 20C6005CLS       | 1         | 0.57%   |
| Lenovo ThinkPad E15 20RES31K00             | 1         | 0.57%   |
| Lenovo ThinkCentre M92p 3238BK7            | 1         | 0.57%   |
| Lenovo ThinkCentre M720q 10T8S32P00        | 1         | 0.57%   |
| Lenovo ThinkBook 15-IML 20RW               | 1         | 0.57%   |
| Lenovo IdeaPad S340-15IWL 81N8             | 1         | 0.57%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.57%   |
| Lenovo IdeaPad 330S-15ARR 81FB             | 1         | 0.57%   |
| Lenovo IdeaPad 320-17IKB 81BJ              | 1         | 0.57%   |
| Lenovo IdeaPad 300-15ISK 80RS              | 1         | 0.57%   |
| Lenovo G50-70 20351                        | 1         | 0.57%   |
| Lenovo G405 20239                          | 1         | 0.57%   |
| Lenovo B51-30 80LK                         | 1         | 0.57%   |
| Lenovo B50-45 20388                        | 1         | 0.57%   |
| Intel NUC5CPYB H61145-404                  | 1         | 0.57%   |
| Intel H61M-DS2                             | 1         | 0.57%   |
| Intel DP35DP AAD81073-208                  | 1         | 0.57%   |
| HP ZBook 14u G4                            | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ECS SF20PA2            | 13        | 7.39%   |
| Lenovo ThinkPad        | 8         | 4.55%   |
| HP Laptop              | 7         | 3.98%   |
| Dell Inspiron          | 7         | 3.98%   |
| Acer Aspire            | 7         | 3.98%   |
| Toshiba Satellite      | 6         | 3.41%   |
| HP Pavilion            | 6         | 3.41%   |
| Lenovo IdeaPad         | 5         | 2.84%   |
| HP Compaq              | 3         | 1.7%    |
| Dell OptiPlex          | 3         | 1.7%    |
| ASUS ROG               | 3         | 1.7%    |
| Standard SF20BA2       | 2         | 1.14%   |
| Lenovo ThinkCentre     | 2         | 1.14%   |
| Lenovo IdeaCentre      | 2         | 1.14%   |
| HP ENVY                | 2         | 1.14%   |
| Gigabyte Z390          | 2         | 1.14%   |
| Dell XPS               | 2         | 1.14%   |
| Dell Latitude          | 2         | 1.14%   |
| ASUS VivoBook          | 2         | 1.14%   |
| ASUS TUF               | 2         | 1.14%   |
| ASUS PRIME             | 2         | 1.14%   |
| ASRock ALiveNF6P-VSTA  | 2         | 1.14%   |
| ASRock A320M-HDV       | 2         | 1.14%   |
| Acer TravelMate        | 2         | 1.14%   |
| Unknown                | 2         | 1.14%   |
| Supermicro P4DMS       | 1         | 0.57%   |
| Standard EF20EA        | 1         | 0.57%   |
| Sony SVF14211CLB       | 1         | 0.57%   |
| Samsung NC208          | 1         | 0.57%   |
| Samsung N102SP         | 1         | 0.57%   |
| Samsung 700T           | 1         | 0.57%   |
| Samsung 300E4C         | 1         | 0.57%   |
| Positivo Serie         | 1         | 0.57%   |
| Panasonic CF-31JEGAX1M | 1         | 0.57%   |
| OEM V40SI2             | 1         | 0.57%   |
| MSI MS-7C37            | 1         | 0.57%   |
| MSI MS-7817            | 1         | 0.57%   |
| MSI MS-7816            | 1         | 0.57%   |
| MSI MS-7786            | 1         | 0.57%   |
| MSI MS-7721            | 1         | 0.57%   |
| MSI MS-7592            | 1         | 0.57%   |
| MSI MS-7383            | 1         | 0.57%   |
| MSI GS63VR             | 1         | 0.57%   |
| MSI GL65               | 1         | 0.57%   |
| MSI GL63               | 1         | 0.57%   |
| MSI GE62               | 1         | 0.57%   |
| Lenovo V15-ADA         | 1         | 0.57%   |
| Lenovo ThinkBook       | 1         | 0.57%   |
| Lenovo G50-70          | 1         | 0.57%   |
| Lenovo G405            | 1         | 0.57%   |
| Lenovo B51-30          | 1         | 0.57%   |
| Lenovo B50-45          | 1         | 0.57%   |
| Intel NUC5CPYB         | 1         | 0.57%   |
| Intel H61M-DS2         | 1         | 0.57%   |
| Intel DP35DP           | 1         | 0.57%   |
| HP ZBook               | 1         | 0.57%   |
| HP Stream              | 1         | 0.57%   |
| HP Presario            | 1         | 0.57%   |
| HP Notebook            | 1         | 0.57%   |
| HP EliteDesk           | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 24        | 13.64%  |
| 2019    | 21        | 11.93%  |
| 2011    | 19        | 10.8%   |
| 2013    | 18        | 10.23%  |
| 2018    | 15        | 8.52%   |
| 2020    | 14        | 7.95%   |
| 2016    | 12        | 6.82%   |
| 2014    | 10        | 5.68%   |
| 2012    | 10        | 5.68%   |
| 2015    | 7         | 3.98%   |
| 2007    | 6         | 3.41%   |
| 2010    | 5         | 2.84%   |
| 2009    | 5         | 2.84%   |
| 2008    | 4         | 2.27%   |
| Unknown | 2         | 1.14%   |
| 2021    | 1         | 0.57%   |
| 2005    | 1         | 0.57%   |
| 2004    | 1         | 0.57%   |
| 2003    | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 111       | 63.07%  |
| Desktop     | 56        | 31.82%  |
| Phone       | 2         | 1.14%   |
| Convertible | 2         | 1.14%   |
| Mini pc     | 2         | 1.14%   |
| All in one  | 2         | 1.14%   |
| Tablet      | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 162       | 92.05%  |
| Enabled  | 14        | 7.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 44        | 24.31%  |
| 4.01-8.0    | 40        | 22.1%   |
| 8.01-16.0   | 30        | 16.57%  |
| 16.01-24.0  | 23        | 12.71%  |
| 1.01-2.0    | 23        | 12.71%  |
| 32.01-64.0  | 10        | 5.52%   |
| 64.01-256.0 | 4         | 2.21%   |
| 24.01-32.0  | 3         | 1.66%   |
| 2.01-3.0    | 2         | 1.1%    |
| 0.51-1.0    | 1         | 0.55%   |
| 0.01-0.5    | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 77        | 41.4%   |
| 2.01-3.0  | 42        | 22.58%  |
| 4.01-8.0  | 18        | 9.68%   |
| 3.01-4.0  | 18        | 9.68%   |
| 0.51-1.0  | 18        | 9.68%   |
| 8.01-16.0 | 9         | 4.84%   |
| 0.01-0.5  | 4         | 2.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 68.72%  |
| 2      | 35        | 19.55%  |
| 3      | 10        | 5.59%   |
| 4      | 7         | 3.91%   |
| 5      | 2         | 1.12%   |
| 0      | 2         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 61.93%  |
| Yes       | 67        | 38.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 75.57%  |
| No        | 43        | 24.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 76.4%   |
| No        | 42        | 23.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 59.09%  |
| No        | 72        | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Uruguay | 176       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Montevideo             | 127       | 68.65%  |
| Maldonado              | 9         | 4.86%   |
| Canelones              | 8         | 4.32%   |
| Las Piedras            | 4         | 2.16%   |
| San Jose de Mayo       | 3         | 1.62%   |
| Salto                  | 2         | 1.08%   |
| Rocha                  | 2         | 1.08%   |
| Punta Gorda            | 2         | 1.08%   |
| Punta del Este         | 2         | 1.08%   |
| Parque Rodo            | 2         | 1.08%   |
| La Paz                 | 2         | 1.08%   |
| Durazno                | 2         | 1.08%   |
| Ciudad del Plata       | 2         | 1.08%   |
| Buceo                  | 2         | 1.08%   |
| Solymar                | 1         | 0.54%   |
| Paysandú              | 1         | 0.54%   |
| Nuevo Paris            | 1         | 0.54%   |
| Melo                   | 1         | 0.54%   |
| Melilla                | 1         | 0.54%   |
| Maronas                | 1         | 0.54%   |
| Malvin Norte           | 1         | 0.54%   |
| Las Flores             | 1         | 0.54%   |
| La Barra               | 1         | 0.54%   |
| Joaquin Suarez         | 1         | 0.54%   |
| Florida                | 1         | 0.54%   |
| El Tesoro              | 1         | 0.54%   |
| El Pinar               | 1         | 0.54%   |
| Centro                 | 1         | 0.54%   |
| Barrancas Coloradas    | 1         | 0.54%   |
| Arenas de Jose Ignacio | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 53        | 67     | 22.75%  |
| Seagate                   | 30        | 38     | 12.88%  |
| Kingston                  | 29        | 36     | 12.45%  |
| Samsung Electronics       | 27        | 28     | 11.59%  |
| Toshiba                   | 23        | 29     | 9.87%   |
| Unknown                   | 18        | 23     | 7.73%   |
| Sandisk                   | 11        | 12     | 4.72%   |
| Hitachi                   | 9         | 14     | 3.86%   |
| Crucial                   | 5         | 7      | 2.15%   |
| Intel                     | 4         | 4      | 1.72%   |
| HGST                      | 4         | 4      | 1.72%   |
| SK Hynix                  | 3         | 3      | 1.29%   |
| Netac                     | 2         | 2      | 0.86%   |
| Micron/Crucial Technology | 2         | 3      | 0.86%   |
| Hewlett-Packard           | 2         | 2      | 0.86%   |
| Silicon Motion            | 1         | 1      | 0.43%   |
| Phison                    | 1         | 1      | 0.43%   |
| Micron Technology         | 1         | 1      | 0.43%   |
| MAXTOR                    | 1         | 2      | 0.43%   |
| LITEON                    | 1         | 2      | 0.43%   |
| IBM-ESXS                  | 1         | 1      | 0.43%   |
| ExcelStor                 | 1         | 1      | 0.43%   |
| China                     | 1         | 1      | 0.43%   |
| BIWIN                     | 1         | 1      | 0.43%   |
| BHT                       | 1         | 1      | 0.43%   |
| Apple                     | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 10        | 4.03%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 3.23%   |
| Unknown DA4032  32GB                | 5         | 2.02%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 2.02%   |
| Samsung HD161HJ 160GB               | 5         | 2.02%   |
| Toshiba MQ01ABD075 752GB            | 4         | 1.61%   |
| Toshiba DT01ACA100 1TB              | 4         | 1.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.61%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 1.61%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 1.61%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 1.21%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 3         | 1.21%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 1.21%   |
| Toshiba DT01ACA300 3TB              | 3         | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 1.21%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.21%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 1.21%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.81%   |
| WDC WD5000LPVT-24G33T1 500GB        | 2         | 0.81%   |
| WDC WD10EFRX-68FYTN0 1TB            | 2         | 0.81%   |
| Unknown SD/MMC/MS PRO 999GB         | 2         | 0.81%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.81%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.81%   |
| Toshiba HDWK105 500GB               | 2         | 0.81%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.81%   |
| Seagate ST3250312AS 250GB           | 2         | 0.81%   |
| Sandisk NVMe SSD Drive 256GB        | 2         | 0.81%   |
| Sandisk NVMe SSD Drive 1024GB       | 2         | 0.81%   |
| SanDisk DF4032  32GB                | 2         | 0.81%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.81%   |
| Samsung HD103SJ 1TB                 | 2         | 0.81%   |
| Kingston SA2000M81000G 1TB          | 2         | 0.81%   |
| Crucial CT500P2SSD8 500GB           | 2         | 0.81%   |
| WDC WDS512G1X0C-00ENX0 512GB        | 1         | 0.4%    |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.4%    |
| WDC WDS250G2X0C-00L350 250GB        | 1         | 0.4%    |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.4%    |
| WDC WDS100T3X0C-00SJG0 1TB          | 1         | 0.4%    |
| WDC WD800JD-60LSA5 80GB             | 1         | 0.4%    |
| WDC WD7500BPVX-22JC3T0 752GB        | 1         | 0.4%    |
| WDC WD6400BPVT-75HXZT1 640GB        | 1         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPVX-00V0TT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.4%    |
| WDC WD5000AZLX-00ZR6A0 500GB        | 1         | 0.4%    |
| WDC WD5000AVVS-63ZWB0 500GB         | 1         | 0.4%    |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.4%    |
| WDC WD5000AAJS-00A8B0 500GB         | 1         | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB            | 1         | 0.4%    |
| WDC WD400BB-00DEA0 40GB             | 1         | 0.4%    |
| WDC WD3200LPCX-24C6HT0 320GB        | 1         | 0.4%    |
| WDC WD2500JS-58NCB1 250GB           | 1         | 0.4%    |
| WDC WD2500AAKX-603CA0 250GB         | 1         | 0.4%    |
| WDC WD2500AAKX-07U6AA0 250GB        | 1         | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 55     | 34.96%  |
| Seagate             | 30        | 38     | 24.39%  |
| Toshiba             | 19        | 25     | 15.45%  |
| Samsung Electronics | 14        | 14     | 11.38%  |
| Hitachi             | 9         | 14     | 7.32%   |
| HGST                | 4         | 4      | 3.25%   |
| Unknown             | 2         | 2      | 1.63%   |
| MAXTOR              | 1         | 2      | 0.81%   |
| ExcelStor           | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 27     | 40.35%  |
| WDC                 | 7         | 7      | 12.28%  |
| Samsung Electronics | 7         | 8      | 12.28%  |
| SanDisk             | 4         | 4      | 7.02%   |
| Crucial             | 3         | 4      | 5.26%   |
| SK Hynix            | 2         | 2      | 3.51%   |
| Netac               | 2         | 2      | 3.51%   |
| Intel               | 2         | 2      | 3.51%   |
| Hewlett-Packard     | 2         | 2      | 3.51%   |
| Toshiba             | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| BIWIN               | 1         | 1      | 1.75%   |
| BHT                 | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 99        | 155    | 47.6%   |
| SSD     | 56        | 63     | 26.92%  |
| NVMe    | 34        | 42     | 16.35%  |
| MMC     | 18        | 24     | 8.65%   |
| Unknown | 1         | 1      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 133       | 214    | 70%     |
| NVMe | 34        | 42     | 17.89%  |
| MMC  | 18        | 24     | 9.47%   |
| SAS  | 5         | 5      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 101       | 131    | 63.13%  |
| 0.51-1.0   | 51        | 79     | 31.88%  |
| 2.01-3.0   | 4         | 4      | 2.5%    |
| 3.01-4.0   | 2         | 2      | 1.25%   |
| 1.01-2.0   | 2         | 2      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 46        | 25.27%  |
| 251-500        | 38        | 20.88%  |
| 501-1000       | 30        | 16.48%  |
| 21-50          | 21        | 11.54%  |
| 1-20           | 18        | 9.89%   |
| 1001-2000      | 9         | 4.95%   |
| 51-100         | 8         | 4.4%    |
| Unknown        | 7         | 3.85%   |
| More than 3000 | 3         | 1.65%   |
| 2001-3000      | 2         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 44.09%  |
| 21-50          | 33        | 17.74%  |
| 251-500        | 18        | 9.68%   |
| 51-100         | 16        | 8.6%    |
| 101-250        | 15        | 8.06%   |
| 501-1000       | 10        | 5.38%   |
| Unknown        | 7         | 3.76%   |
| More than 3000 | 2         | 1.08%   |
| 1001-2000      | 2         | 1.08%   |
| 2001-3000      | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 3      | 15.79%  |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 5.26%   |
| WDC WD5000AAJS-00A8B0 500GB         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 5.26%   |
| Toshiba MK5059GSXP 500GB            | 1         | 2      | 5.26%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 5.26%   |
| Seagate ST500DM005 HD502HJ 500GB    | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 5.26%   |
| Seagate ST3750640NS 752GB           | 1         | 6      | 5.26%   |
| Seagate ST3250310CS 250GB           | 1         | 1      | 5.26%   |
| Seagate ST3200827AS 200GB           | 1         | 1      | 5.26%   |
| Seagate ST250DM000-1BD141 250GB     | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 5.26%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 5.26%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 14     | 44.44%  |
| WDC     | 5         | 5      | 27.78%  |
| Toshiba | 3         | 4      | 16.67%  |
| SanDisk | 1         | 1      | 5.56%   |
| Hitachi | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 14     | 47.06%  |
| WDC     | 5         | 5      | 29.41%  |
| Toshiba | 3         | 4      | 17.65%  |
| Hitachi | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 24     | 94.44%  |
| SSD  | 1         | 1      | 5.56%   |

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
| Detected | 114       | 177    | 61.62%  |
| Works    | 53        | 83     | 28.65%  |
| Malfunc  | 18        | 25     | 9.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 115       | 57.21%  |
| AMD                              | 41        | 20.4%   |
| Sandisk                          | 10        | 4.98%   |
| Samsung Electronics              | 6         | 2.99%   |
| Kingston Technology Company      | 6         | 2.99%   |
| Nvidia                           | 4         | 1.99%   |
| Micron/Crucial Technology        | 4         | 1.99%   |
| Toshiba America Info Systems     | 3         | 1.49%   |
| ASMedia Technology               | 3         | 1.49%   |
| VIA Technologies                 | 1         | 0.5%    |
| SK Hynix                         | 1         | 0.5%    |
| Silicon Motion                   | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |
| Phison Electronics               | 1         | 0.5%    |
| Marvell Technology Group         | 1         | 0.5%    |
| Lite-On Technology               | 1         | 0.5%    |
| Apple                            | 1         | 0.5%    |
| Adaptec                          | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30        | 12.77%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 16        | 6.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 4.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 2.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 2.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 2.13%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.7%    |
| Nvidia MCP61 SATA Controller                                                            | 4         | 1.7%    |
| Nvidia MCP61 IDE                                                                        | 4         | 1.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.28%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 1.28%   |
| AMD FCH IDE Controller                                                                  | 3         | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.28%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.85%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.85%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 2         | 0.85%   |
| Intel SSD 660P Series                                                                   | 2         | 0.85%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.85%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 0.43%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1         | 0.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.43%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1         | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.43%   |
| Sandisk WD Black NVMe SSD                                                               | 1         | 0.43%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1         | 0.43%   |
| Sandisk Non-Volatile memory controller                                                  | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 64.76%  |
| NVMe | 34        | 16.19%  |
| IDE  | 30        | 14.29%  |
| RAID | 9         | 4.29%   |
| SCSI | 1         | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 125       | 71.02%  |
| AMD      | 49        | 27.84%  |
| QUALCOMM | 1         | 0.57%   |
| ARM      | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 14        | 7.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 1.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 1.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 3         | 1.7%    |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 1.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 2         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 2         | 1.14%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.14%   |
| Intel Core i5-8400 CPU @ 2.80GHz             | 2         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.14%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.14%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 2         | 1.14%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 2         | 1.14%   |
| Intel Celeron CPU J3355 @ 2.00GHz            | 2         | 1.14%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2         | 1.14%   |
| AMD E-300 APU with Radeon HD Graphics        | 2         | 1.14%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.14%   |
| AMD A6-5200 APU with Radeon HD Graphics      | 2         | 1.14%   |
| QUALCOMM AArch64 Processor rev 1 (aarch64)   | 1         | 0.57%   |
| Intel Xeon CPU 2.40GHz                       | 1         | 0.57%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.57%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.57%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.57%   |
| Intel Pentium CPU B970 @ 2.30GHz             | 1         | 0.57%   |
| Intel Pentium CPU 2117U @ 1.80GHz            | 1         | 0.57%   |
| Intel Pentium 4 CPU 2.80GHz                  | 1         | 0.57%   |
| Intel Genuine CPU T1600 @ 1.66GHz            | 1         | 0.57%   |
| Intel Genuine CPU T1400 @ 1.73GHz            | 1         | 0.57%   |
| Intel Core i9-9900KF CPU @ 3.60GHz           | 1         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 1         | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.57%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 1         | 0.57%   |
| Intel Core i7-4930K CPU @ 3.40GHz            | 1         | 0.57%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.57%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 0.57%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1         | 0.57%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.57%   |
| Intel Core i7-2600K CPU @ 3.40GHz            | 1         | 0.57%   |
| Intel Core i7-2600 CPU @ 3.40GHz             | 1         | 0.57%   |
| Intel Core i7-10700F CPU @ 2.90GHz           | 1         | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 1         | 0.57%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.57%   |
| Intel Core i5-9400F CPU @ 2.90GHz            | 1         | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 1         | 0.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 0.57%   |
| Intel Core i5-5250U CPU @ 1.60GHz            | 1         | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz             | 1         | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.57%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.57%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 0.57%   |
| Intel Core i5-3470T CPU @ 2.90GHz            | 1         | 0.57%   |
| Intel Core i5-3340M CPU @ 2.70GHz            | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 30        | 17.05%  |
| Intel Core i5      | 30        | 17.05%  |
| Intel Celeron      | 24        | 13.64%  |
| Intel Core i3      | 14        | 7.95%   |
| Intel Pentium      | 6         | 3.41%   |
| Intel Core 2 Duo   | 6         | 3.41%   |
| AMD Ryzen 7        | 6         | 3.41%   |
| Intel Atom         | 5         | 2.84%   |
| AMD Ryzen 5        | 5         | 2.84%   |
| AMD A6             | 5         | 2.84%   |
| AMD FX             | 4         | 2.27%   |
| Other              | 3         | 1.7%    |
| Intel Core 2 Quad  | 3         | 1.7%    |
| AMD Ryzen 9        | 3         | 1.7%    |
| AMD Ryzen 3        | 3         | 1.7%    |
| AMD Athlon II X2   | 3         | 1.7%    |
| AMD A4             | 3         | 1.7%    |
| Intel Genuine      | 2         | 1.14%   |
| AMD Phenom II X6   | 2         | 1.14%   |
| AMD E1             | 2         | 1.14%   |
| AMD E              | 2         | 1.14%   |
| AMD Athlon         | 2         | 1.14%   |
| QUALCOMM AArch64   | 1         | 0.57%   |
| Intel Xeon         | 1         | 0.57%   |
| Intel Pentium Dual | 1         | 0.57%   |
| Intel Pentium 4    | 1         | 0.57%   |
| Intel Core i9      | 1         | 0.57%   |
| ARM AArch64        | 1         | 0.57%   |
| AMD Phenom II      | 1         | 0.57%   |
| AMD Phenom         | 1         | 0.57%   |
| AMD E2             | 1         | 0.57%   |
| AMD Athlon 64 X2   | 1         | 0.57%   |
| AMD Athlon 64      | 1         | 0.57%   |
| AMD A8             | 1         | 0.57%   |
| AMD A10            | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 90        | 51.14%  |
| 4      | 52        | 29.55%  |
| 6      | 15        | 8.52%   |
| 8      | 12        | 6.82%   |
| 1      | 7         | 3.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 173       | 98.3%   |
| 2      | 3         | 1.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 97        | 55.11%  |
| 1      | 79        | 44.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 169       | 96.02%  |
| Unknown        | 5         | 2.84%   |
| 32-bit         | 2         | 1.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 19.32%  |
| 0x206a7    | 10        | 5.68%   |
| 0x906ea    | 7         | 3.98%   |
| 0x406c4    | 7         | 3.98%   |
| 0x40651    | 6         | 3.41%   |
| 0x306c3    | 6         | 3.41%   |
| 0x806e9    | 5         | 2.84%   |
| 0x506c9    | 5         | 2.84%   |
| 0x306d4    | 5         | 2.84%   |
| 0x20655    | 5         | 2.84%   |
| 0x1067a    | 5         | 2.84%   |
| 0x806ec    | 4         | 2.27%   |
| 0x806ea    | 4         | 2.27%   |
| 0x08701021 | 4         | 2.27%   |
| 0x08108109 | 4         | 2.27%   |
| 0x6fd      | 3         | 1.7%    |
| 0x406e3    | 3         | 1.7%    |
| 0x306a9    | 3         | 1.7%    |
| 0x06001119 | 3         | 1.7%    |
| 0x06000852 | 3         | 1.7%    |
| 0x906eb    | 2         | 1.14%   |
| 0x706e5    | 2         | 1.14%   |
| 0x406c3    | 2         | 1.14%   |
| 0x10676    | 2         | 1.14%   |
| 0x08600104 | 2         | 1.14%   |
| 0x0810100b | 2         | 1.14%   |
| 0x07030104 | 2         | 1.14%   |
| 0x0700010f | 2         | 1.14%   |
| 0x06006705 | 2         | 1.14%   |
| 0x010000dc | 2         | 1.14%   |
| 0x010000b6 | 2         | 1.14%   |
| 0xf33      | 1         | 0.57%   |
| 0xf27      | 1         | 0.57%   |
| 0xa0655    | 1         | 0.57%   |
| 0xa0652    | 1         | 0.57%   |
| 0x906ec    | 1         | 0.57%   |
| 0x806eb    | 1         | 0.57%   |
| 0x806c1    | 1         | 0.57%   |
| 0x706a1    | 1         | 0.57%   |
| 0x506e3    | 1         | 0.57%   |
| 0x30678    | 1         | 0.57%   |
| 0x30661    | 1         | 0.57%   |
| 0x106e5    | 1         | 0.57%   |
| 0x106ca    | 1         | 0.57%   |
| 0x10677    | 1         | 0.57%   |
| 0x08600102 | 1         | 0.57%   |
| 0x08108102 | 1         | 0.57%   |
| 0x0800820d | 1         | 0.57%   |
| 0x08001137 | 1         | 0.57%   |
| 0x07030106 | 1         | 0.57%   |
| 0x07030105 | 1         | 0.57%   |
| 0x06006118 | 1         | 0.57%   |
| 0x06003106 | 1         | 0.57%   |
| 0x05000119 | 1         | 0.57%   |
| 0x05000101 | 1         | 0.57%   |
| 0x03000027 | 1         | 0.57%   |
| 0x010000c8 | 1         | 0.57%   |
| 0x01000083 | 1         | 0.57%   |
| 0x00000000 | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 14.2%   |
| Goldmont      | 16        | 9.09%   |
| SandyBridge   | 12        | 6.82%   |
| Haswell       | 12        | 6.82%   |
| Silvermont    | 11        | 6.25%   |
| Zen 2         | 8         | 4.55%   |
| Penryn        | 8         | 4.55%   |
| Zen+          | 7         | 3.98%   |
| K10           | 7         | 3.98%   |
| IvyBridge     | 7         | 3.98%   |
| Skylake       | 6         | 3.41%   |
| Piledriver    | 6         | 3.41%   |
| Broadwell     | 6         | 3.41%   |
| Westmere      | 5         | 2.84%   |
| Puma          | 4         | 2.27%   |
| Excavator     | 4         | 2.27%   |
| Core          | 4         | 2.27%   |
| CometLake     | 4         | 2.27%   |
| Zen           | 3         | 1.7%    |
| Jaguar        | 3         | 1.7%    |
| NetBurst      | 2         | 1.14%   |
| K8 Hammer     | 2         | 1.14%   |
| IceLake       | 2         | 1.14%   |
| Bonnell       | 2         | 1.14%   |
| Bobcat        | 2         | 1.14%   |
| Unknown       | 2         | 1.14%   |
| Zen 3         | 1         | 0.57%   |
| TigerLake     | 1         | 0.57%   |
| Steamroller   | 1         | 0.57%   |
| Nehalem       | 1         | 0.57%   |
| K10 Llano     | 1         | 0.57%   |
| Goldmont plus | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 105       | 53.03%  |
| AMD                              | 49        | 24.75%  |
| Nvidia                           | 43        | 21.72%  |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 16        | 7.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 4.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.96%   |
| Intel HD Graphics 620                                                                    | 5         | 2.46%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.97%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.97%   |
| AMD Renoir                                                                               | 4         | 1.97%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.48%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 1.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.48%   |
| Intel HD Graphics 530                                                                    | 3         | 1.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.48%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.48%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.48%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.99%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.99%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.99%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.99%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.99%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.99%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.99%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2         | 0.99%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.49%   |
| Nvidia TU117M                                                                            | 1         | 0.49%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.49%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.49%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.49%   |
| Nvidia NV34 [GeForce FX 5200]                                                            | 1         | 0.49%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.49%   |
| Nvidia GT216 [GeForce 210]                                                               | 1         | 0.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.49%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.49%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.49%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.49%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 48.86%  |
| 1 x AMD        | 33        | 18.75%  |
| 1 x Nvidia     | 28        | 15.91%  |
| Intel + Nvidia | 10        | 5.68%   |
| Intel + AMD    | 8         | 4.55%   |
| AMD + Nvidia   | 5         | 2.84%   |
| 2 x AMD        | 3         | 1.7%    |
| Other          | 2         | 1.14%   |
| 1 x SiS        | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 150       | 84.75%  |
| Proprietary | 19        | 10.73%  |
| Unknown     | 8         | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 56.98%  |
| 1.01-2.0   | 21        | 11.73%  |
| 0.51-1.0   | 20        | 11.17%  |
| 0.01-0.5   | 18        | 10.06%  |
| 3.01-4.0   | 12        | 6.7%    |
| 5.01-6.0   | 4         | 2.23%   |
| 7.01-8.0   | 1         | 0.56%   |
| 8.01-16.0  | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 21        | 11.48%  |
| LG Display              | 18        | 9.84%   |
| Chimei Innolux          | 17        | 9.29%   |
| BOE                     | 17        | 9.29%   |
| AU Optronics            | 17        | 9.29%   |
| AOC                     | 13        | 7.1%    |
| ViewSonic               | 11        | 6.01%   |
| KDC                     | 6         | 3.28%   |
| InfoVision              | 6         | 3.28%   |
| Acer                    | 6         | 3.28%   |
| KTC                     | 5         | 2.73%   |
| Sharp                   | 4         | 2.19%   |
| Lenovo                  | 4         | 2.19%   |
| Hewlett-Packard         | 4         | 2.19%   |
| Chi Mei Optoelectronics | 4         | 2.19%   |
| PANDA                   | 3         | 1.64%   |
| Goldstar                | 3         | 1.64%   |
| Dell                    | 3         | 1.64%   |
| Unknown                 | 2         | 1.09%   |
| Sun                     | 1         | 0.55%   |
| Sony                    | 1         | 0.55%   |
| RIS                     | 1         | 0.55%   |
| Panasonic               | 1         | 0.55%   |
| LG Philips              | 1         | 0.55%   |
| Lenovo Group Limited    | 1         | 0.55%   |
| KVM                     | 1         | 0.55%   |
| KOA                     | 1         | 0.55%   |
| JDI                     | 1         | 0.55%   |
| InnoLux Display         | 1         | 0.55%   |
| HSI                     | 1         | 0.55%   |
| HKC                     | 1         | 0.55%   |
| Hitachi                 | 1         | 0.55%   |
| Envision                | 1         | 0.55%   |
| CVT                     | 1         | 0.55%   |
| CPT                     | 1         | 0.55%   |
| BenQ                    | 1         | 0.55%   |
| Apple                   | 1         | 0.55%   |
| Ancor Communications    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 5         | 2.66%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch            | 4         | 2.13%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 4         | 2.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.6%    |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                  | 2         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.06%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 1.06%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 2         | 1.06%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 1.06%   |
| Lenovo LEN-AIO-330-E LEN0017 1440x900 420x270mm 19.7-inch                | 2         | 1.06%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 1.06%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 1.06%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 1.06%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 1.06%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 1.06%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 1.06%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                           | 2         | 1.06%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                   | 1         | 0.53%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch            | 1         | 0.53%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch            | 1         | 0.53%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch                  | 1         | 0.53%   |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch                   | 1         | 0.53%   |
| ViewSonic VA1903a VSC8A31 1366x768 410x230mm 18.5-inch                   | 1         | 0.53%   |
| ViewSonic LCD Monitor VX2240w 3600x1080                                  | 1         | 0.53%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch              | 1         | 0.53%   |
| ViewSonic LCD Monitor VA2261                                             | 1         | 0.53%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                         | 1         | 0.53%   |
| Unknown LCD Monitor RTK 2944x1080                                        | 1         | 0.53%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                   | 1         | 0.53%   |
| Sony LCD Monitor TV                                                      | 1         | 0.53%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                  | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch     | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch      | 1         | 0.53%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch     | 1         | 0.53%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch        | 1         | 0.53%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch        | 1         | 0.53%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch        | 1         | 0.53%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 286x179mm 13.3-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 344x194mm 15.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1210x680mm 54.6-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch    | 1         | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 0.53%   |
| RIS V19aLm RIS0709 1360x768 410x230mm 18.5-inch                          | 1         | 0.53%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 1         | 0.53%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 1         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.53%   |
| Panasonic LCD Monitor TV                                                 | 1         | 0.53%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 0.53%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch             | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 70        | 41.67%  |
| 1920x1080 (FHD)    | 50        | 29.76%  |
| 1600x900 (HD+)     | 11        | 6.55%   |
| 3840x2160 (4K)     | 5         | 2.98%   |
| 1920x1200 (WUXGA)  | 5         | 2.98%   |
| 1440x900 (WXGA+)   | 4         | 2.38%   |
| 1280x1024 (SXGA)   | 4         | 2.38%   |
| 2560x1440 (QHD)    | 3         | 1.79%   |
| 1280x800 (WXGA)    | 3         | 1.79%   |
| Unknown            | 3         | 1.79%   |
| 1680x1050 (WSXGA+) | 2         | 1.19%   |
| 1360x768           | 2         | 1.19%   |
| 1280x720 (HD)      | 2         | 1.19%   |
| 3600x1080          | 1         | 0.6%    |
| 2944x1080          | 1         | 0.6%    |
| 1280x768           | 1         | 0.6%    |
| 1024x600           | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 66        | 36.46%  |
| 13      | 19        | 10.5%   |
| 14      | 15        | 8.29%   |
| 23      | 11        | 6.08%   |
| 18      | 10        | 5.52%   |
| 24      | 8         | 4.42%   |
| 21      | 8         | 4.42%   |
| 27      | 5         | 2.76%   |
| 19      | 5         | 2.76%   |
| 17      | 5         | 2.76%   |
| 11      | 5         | 2.76%   |
| Unknown | 5         | 2.76%   |
| 20      | 3         | 1.66%   |
| 84      | 2         | 1.1%    |
| 44      | 2         | 1.1%    |
| 32      | 2         | 1.1%    |
| 12      | 2         | 1.1%    |
| 10      | 2         | 1.1%    |
| 57      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |
| 34      | 1         | 0.55%   |
| 31      | 1         | 0.55%   |
| 22      | 1         | 0.55%   |
| 16      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 94        | 52.81%  |
| 401-500     | 24        | 13.48%  |
| 501-600     | 22        | 12.36%  |
| 201-300     | 14        | 7.87%   |
| 351-400     | 9         | 5.06%   |
| Unknown     | 5         | 2.81%   |
| 701-800     | 3         | 1.69%   |
| 1501-2000   | 2         | 1.12%   |
| 901-1000    | 2         | 1.12%   |
| 801-900     | 1         | 0.56%   |
| 601-700     | 1         | 0.56%   |
| 1001-1500   | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 137       | 86.71%  |
| 16/10   | 11        | 6.96%   |
| Unknown | 5         | 3.16%   |
| 5/4     | 4         | 2.53%   |
| 21/9    | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 65        | 36.52%  |
| 81-90          | 29        | 16.29%  |
| 201-250        | 19        | 10.67%  |
| 151-200        | 15        | 8.43%   |
| 141-150        | 8         | 4.49%   |
| 71-80          | 5         | 2.81%   |
| 51-60          | 5         | 2.81%   |
| 301-350        | 5         | 2.81%   |
| 121-130        | 5         | 2.81%   |
| Unknown        | 5         | 2.81%   |
| 351-500        | 4         | 2.25%   |
| More than 1000 | 3         | 1.69%   |
| 501-1000       | 3         | 1.69%   |
| 61-70          | 2         | 1.12%   |
| 41-50          | 2         | 1.12%   |
| 251-300        | 2         | 1.12%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 68        | 38.86%  |
| 51-100        | 57        | 32.57%  |
| 121-160       | 35        | 20%     |
| 161-240       | 5         | 2.86%   |
| Unknown       | 5         | 2.86%   |
| 1-50          | 4         | 2.29%   |
| More than 240 | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 139       | 77.22%  |
| 2     | 27        | 15%     |
| 0     | 11        | 6.11%   |
| 3     | 2         | 1.11%   |
| 4     | 1         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 88        | 34.38%  |
| Intel                            | 76        | 29.69%  |
| Qualcomm Atheros                 | 37        | 14.45%  |
| Broadcom                         | 15        | 5.86%   |
| Ralink Technology                | 8         | 3.13%   |
| TP-Link                          | 4         | 1.56%   |
| Ralink                           | 4         | 1.56%   |
| Nvidia                           | 4         | 1.56%   |
| Xiaomi                           | 3         | 1.17%   |
| Broadcom Limited                 | 3         | 1.17%   |
| MediaTek                         | 2         | 0.78%   |
| VIA Technologies                 | 1         | 0.39%   |
| T & A Mobile Phones              | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| Sierra Wireless                  | 1         | 0.39%   |
| Samsung Electronics              | 1         | 0.39%   |
| Qualcomm Atheros Communications  | 1         | 0.39%   |
| Qualcomm                         | 1         | 0.39%   |
| Mercucys                         | 1         | 0.39%   |
| Lenovo                           | 1         | 0.39%   |
| Huawei Technologies              | 1         | 0.39%   |
| DisplayLink                      | 1         | 0.39%   |
| ASIX Electronics                 | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 58        | 19.8%   |
| Intel Wireless 3165                                                     | 20        | 6.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 6.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.39%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.71%   |
| Intel Wireless 7265                                                     | 5         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.71%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.37%   |
| Nvidia MCP61 Ethernet                                                   | 4         | 1.37%   |
| Intel Wireless 7260                                                     | 4         | 1.37%   |
| Intel Ethernet Connection (7) I219-V                                    | 4         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.02%   |
| Intel Wireless 8260                                                     | 3         | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.68%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.68%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.68%   |
| Intel 82579V Gigabit Network Connection                                 | 2         | 0.68%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                    | 2         | 0.68%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.34%   |
| VIA AC'97 Modem Controller                                              | 1         | 0.34%   |
| TP-Link USB 10/100/1000 LAN                                             | 1         | 0.34%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.34%   |
| T & A Mobile Phones MT65xx Android Phone                                | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.34%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.34%   |
| Samsung Kiera                                                           | 1         | 0.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.34%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.34%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1         | 0.34%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 39.16%  |
| Realtek Semiconductor           | 30        | 20.98%  |
| Qualcomm Atheros                | 26        | 18.18%  |
| Broadcom                        | 10        | 6.99%   |
| Ralink Technology               | 8         | 5.59%   |
| Ralink                          | 4         | 2.8%    |
| TP-Link                         | 3         | 2.1%    |
| Broadcom Limited                | 2         | 1.4%    |
| Sierra Wireless                 | 1         | 0.7%    |
| Qualcomm Atheros Communications | 1         | 0.7%    |
| Mercucys                        | 1         | 0.7%    |
| MEDIATEK                        | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 20        | 13.89%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.86%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.47%   |
| Intel Wireless 7265                                                     | 5         | 3.47%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 3.47%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.78%   |
| Intel Wireless 7260                                                     | 4         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.08%   |
| Intel Wireless 8260                                                     | 3         | 2.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.39%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1         | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.69%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.69%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.69%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.69%   |
| Mercucys 802.11n NIC                                                    | 1         | 0.69%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.69%   |
| Intel Wireless 3160                                                     | 1         | 0.69%   |
| Intel WiFi Link 5100                                                    | 1         | 0.69%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.69%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.69%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.69%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.69%   |
| Broadcom Limited BCM43225 802.11b/g/n                                   | 1         | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 79        | 54.48%  |
| Intel                            | 31        | 21.38%  |
| Qualcomm Atheros                 | 12        | 8.28%   |
| Broadcom                         | 6         | 4.14%   |
| Nvidia                           | 4         | 2.76%   |
| Xiaomi                           | 3         | 2.07%   |
| VIA Technologies                 | 1         | 0.69%   |
| TP-Link                          | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |
| Qualcomm                         | 1         | 0.69%   |
| MediaTek                         | 1         | 0.69%   |
| Lenovo                           | 1         | 0.69%   |
| Huawei Technologies              | 1         | 0.69%   |
| DisplayLink                      | 1         | 0.69%   |
| Broadcom Limited                 | 1         | 0.69%   |
| ASIX Electronics                 | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 39.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 12.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.42%   |
| Nvidia MCP61 Ethernet                                             | 4         | 2.74%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 2.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.37%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.37%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.37%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.37%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.68%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.68%   |
| Qualcomm Redmi Note 9S                                            | 1         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.68%   |
| MediaTek Vodafone Smart N10                                       | 1         | 0.68%   |
| Lenovo USB-C to LAN                                               | 1         | 0.68%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.68%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.68%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.68%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.68%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.68%   |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                   | 1         | 0.68%   |
| Huawei E353/E3131                                                 | 1         | 0.68%   |
| DisplayLink Plugable UD-3900                                      | 1         | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.68%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.68%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1         | 0.68%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 50%     |
| Ethernet | 133       | 48.9%   |
| Modem    | 2         | 0.74%   |
| Unknown  | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 67.05%  |
| Ethernet | 58        | 32.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 86        | 48.86%  |
| 2     | 83        | 47.16%  |
| 0     | 6         | 3.41%   |
| 3     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 85.39%  |
| Yes  | 26        | 14.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 46.67%  |
| Realtek Semiconductor           | 14        | 13.33%  |
| Qualcomm Atheros Communications | 12        | 11.43%  |
| Cambridge Silicon Radio         | 7         | 6.67%   |
| Toshiba                         | 5         | 4.76%   |
| IMC Networks                    | 5         | 4.76%   |
| Foxconn / Hon Hai               | 3         | 2.86%   |
| Ralink                          | 2         | 1.9%    |
| Lite-On Technology              | 2         | 1.9%    |
| Broadcom                        | 2         | 1.9%    |
| Ralink Technology               | 1         | 0.95%   |
| Foxconn International           | 1         | 0.95%   |
| Apple                           | 1         | 0.95%   |
| Alps Electric                   | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 31.43%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 7.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 7.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 6.67%   |
| Intel AX200 Bluetooth                               | 6         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.76%   |
| Realtek Bluetooth Radio                             | 4         | 3.81%   |
| Toshiba Bluetooth Device                            | 2         | 1.9%    |
| Toshiba BCM43142A0                                  | 2         | 1.9%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.9%    |
| Intel AX201 Bluetooth                               | 2         | 1.9%    |
| IMC Networks Bluetooth Radio                        | 2         | 1.9%    |
| Toshiba Bluetooth Radio                             | 1         | 0.95%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.95%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.95%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.95%   |
| Lite-On Bluetooth Device                            | 1         | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.95%   |
| IMC Networks Bluetooth Device                       | 1         | 0.95%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.95%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.95%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.95%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.95%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.95%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.95%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.95%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 120       | 54.55%  |
| AMD                                  | 45        | 20.45%  |
| Nvidia                               | 34        | 15.45%  |
| Logitech                             | 5         | 2.27%   |
| VIA Technologies                     | 2         | 0.91%   |
| Generalplus Technology               | 2         | 0.91%   |
| Creative Labs                        | 2         | 0.91%   |
| C-Media Electronics                  | 2         | 0.91%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.45%   |
| Texas Instruments                    | 1         | 0.45%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.45%   |
| Samson Technologies                  | 1         | 0.45%   |
| Rockwell International               | 1         | 0.45%   |
| Focusrite-Novation                   | 1         | 0.45%   |
| Elgato Systems                       | 1         | 0.45%   |
| Creative Technology                  | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 5.84%   |
| AMD FCH Azalia Controller                                                                         | 13        | 4.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 2.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.92%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.19%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.19%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.46%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.09%   |
| Logitech H390 headset with microphone                                                             | 3         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.09%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.09%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.73%   |
| Nvidia Audio device                                                                               | 2         | 0.73%   |
| Logitech Headset H390                                                                             | 2         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.73%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.73%   |
| Generalplus Technology Usb Audio Device                                                           | 2         | 0.73%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 0.73%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.73%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.73%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.36%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1         | 0.36%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 0.36%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.36%   |
| Samson Technologies C03U multi-pattern microphone                                                 | 1         | 0.36%   |
| Rockwell International Riptide Bus / Firmware Downloader [PCI Audio]                              | 1         | 0.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.36%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.36%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 22%     |
| SK Hynix            | 15        | 15%     |
| Kingston            | 14        | 14%     |
| Unknown             | 11        | 11%     |
| Micron Technology   | 11        | 11%     |
| Crucial             | 6         | 6%      |
| Ramaxel Technology  | 5         | 5%      |
| A-DATA Technology   | 4         | 4%      |
| Team                | 2         | 2%      |
| Goldkey             | 2         | 2%      |
| Elpida              | 2         | 2%      |
| Smart               | 1         | 1%      |
| Patriot             | 1         | 1%      |
| Nanya Technology    | 1         | 1%      |
| Infineon            | 1         | 1%      |
| Corsair             | 1         | 1%      |
| Avant               | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.88%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 3         | 2.88%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 2         | 1.92%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 1.92%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.92%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 2         | 1.92%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.92%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.96%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.96%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1         | 0.96%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.96%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.96%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.96%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 1         | 0.96%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 0.96%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s           | 1         | 0.96%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1         | 0.96%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 1         | 0.96%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s              | 1         | 0.96%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 533MT/s                      | 1         | 0.96%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.96%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.96%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.96%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.96%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.96%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.96%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.96%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.96%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.96%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.96%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 0.96%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 1         | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.96%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.96%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.96%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.96%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 0.96%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 0.96%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 0.96%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 0.96%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 0.96%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 0.96%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 0.96%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s                 | 1         | 0.96%   |
| Nanya RAM Module 2GB SODIMM DDR2 533MT/s                         | 1         | 0.96%   |
| Micron RAM MT52L1G32D4PG-107 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.96%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.96%   |
| Micron RAM 8KTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s           | 1         | 0.96%   |
| Micron RAM 8JTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s           | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 38        | 46.34%  |
| DDR4    | 31        | 37.8%   |
| SDRAM   | 3         | 3.66%   |
| LPDDR3  | 3         | 3.66%   |
| DDR2    | 3         | 3.66%   |
| Unknown | 3         | 3.66%   |
| DDR     | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 62.03%  |
| DIMM         | 27        | 34.18%  |
| Row Of Chips | 3         | 3.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 28        | 30.11%  |
| 8192  | 27        | 29.03%  |
| 2048  | 17        | 18.28%  |
| 16384 | 13        | 13.98%  |
| 32768 | 4         | 4.3%    |
| 1024  | 3         | 3.23%   |
| 256   | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 29        | 31.18%  |
| 2667  | 15        | 16.13%  |
| 1333  | 9         | 9.68%   |
| 2400  | 7         | 7.53%   |
| 3200  | 6         | 6.45%   |
| 2133  | 5         | 5.38%   |
| 1334  | 4         | 4.3%    |
| 3600  | 3         | 3.23%   |
| 1867  | 3         | 3.23%   |
| 533   | 3         | 3.23%   |
| 4199  | 2         | 2.15%   |
| 3000  | 2         | 2.15%   |
| 3733  | 1         | 1.08%   |
| 3266  | 1         | 1.08%   |
| 1067  | 1         | 1.08%   |
| 333   | 1         | 1.08%   |
| 266   | 1         | 1.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Xerox Phaser 3040    | 1         | 25%     |
| Samsung M288x Series | 1         | 25%     |
| Brother DCP-T500W    | 1         | 25%     |
| Brother DCP-T420W    | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 32        | 26.23%  |
| Realtek Semiconductor                  | 13        | 10.66%  |
| Acer                                   | 9         | 7.38%   |
| Microdia                               | 8         | 6.56%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 6.56%   |
| Logitech                               | 7         | 5.74%   |
| Unknown                                | 6         | 4.92%   |
| Sunplus Innovation Technology          | 6         | 4.92%   |
| Suyin                                  | 4         | 3.28%   |
| Silicon Motion                         | 4         | 3.28%   |
| IMC Networks                           | 4         | 3.28%   |
| Syntek                                 | 3         | 2.46%   |
| Quanta                                 | 3         | 2.46%   |
| Alcor Micro                            | 3         | 2.46%   |
| Samsung Electronics                    | 2         | 1.64%   |
| Lite-On Technology                     | 2         | 1.64%   |
| Importek                               | 2         | 1.64%   |
| Sony                                   | 1         | 0.82%   |
| Luxvisions Innotech Limited            | 1         | 0.82%   |
| GEMBIRD                                | 1         | 0.82%   |
| DigiTech                               | 1         | 0.82%   |
| Aveo Technology                        | 1         | 0.82%   |
| Apple                                  | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 11        | 9.02%   |
| Unknown USB Camera                                             | 5         | 4.1%    |
| Chicony HP Truevision HD                                       | 5         | 4.1%    |
| Microdia Integrated_Webcam_HD                                  | 4         | 3.28%   |
| Chicony Integrated Camera                                      | 4         | 3.28%   |
| Acer Integrated Camera                                         | 4         | 3.28%   |
| Realtek Lenovo EasyCamera                                      | 3         | 2.46%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 2.46%   |
| Logitech Webcam C270                                           | 3         | 2.46%   |
| Chicony TOSHIBA Web Camera - HD                                | 3         | 2.46%   |
| Syntek Integrated Camera                                       | 2         | 1.64%   |
| Sunplus HP TrueVision HD Camera                                | 2         | 1.64%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.64%   |
| Samsung Galaxy A5 (MTP)                                        | 2         | 1.64%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.64%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.64%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.64%   |
| Chicony HD WebCam                                              | 2         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.64%   |
| Acer HD Webcam                                                 | 2         | 1.64%   |
| Unknown HD camera                                              | 1         | 0.82%   |
| Syntek EasyCamera                                              | 1         | 0.82%   |
| Suyin HP Truevision HD                                         | 1         | 0.82%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.82%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 0.82%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.82%   |
| Sunplus HD WebCam                                              | 1         | 0.82%   |
| Sunplus Asus Webcam                                            | 1         | 0.82%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.82%   |
| Sony CEVCECM                                                   | 1         | 0.82%   |
| Silicon Motion WebCam SC-20FHM11347N                           | 1         | 0.82%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.82%   |
| Realtek USB Camera                                             | 1         | 0.82%   |
| Realtek Integrated Camera                                      | 1         | 0.82%   |
| Realtek HD WebCam                                              | 1         | 0.82%   |
| Realtek Front Camera                                           | 1         | 0.82%   |
| Realtek Acer 640 x 480 laptop camera                           | 1         | 0.82%   |
| Quanta HD Webcam                                               | 1         | 0.82%   |
| Microdia USB Camera                                            | 1         | 0.82%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 0.82%   |
| Microdia Laptop_Integrated_Webcam_0.3M                         | 1         | 0.82%   |
| Microdia HP Webcam                                             | 1         | 0.82%   |
| Luxvisions Innotech Limited Integrated Camera                  | 1         | 0.82%   |
| Logitech Webcam C930e                                          | 1         | 0.82%   |
| Logitech Webcam C110                                           | 1         | 0.82%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 0.82%   |
| Logitech C505e HD Webcam                                       | 1         | 0.82%   |
| Lite-On Integrated Camera                                      | 1         | 0.82%   |
| Lite-On HP Webcam                                              | 1         | 0.82%   |
| Importek TOSHIBA Web Camera                                    | 1         | 0.82%   |
| Importek HP Webcam                                             | 1         | 0.82%   |
| IMC Networks TOSHIBA Web Camera - HD                           | 1         | 0.82%   |
| IMC Networks Integrated Camera                                 | 1         | 0.82%   |
| GEMBIRD USB2.0 PC CAMERA                                       | 1         | 0.82%   |
| DigiTech WebCam SC-30AFL11449M                                 | 1         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 0.82%   |
| Chicony USB2.0 HD Camera                                       | 1         | 0.82%   |
| Chicony Lenovo EasyCamera                                      | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Elan Microelectronics      | 2         | 13.33%  |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 13.33%  |
| Elan ELAN:Fingerprint                                  | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 138       | 77.09%  |
| 1     | 37        | 20.67%  |
| 2     | 3         | 1.68%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 31.11%  |
| Graphics card            | 9         | 20%     |
| Net/wireless             | 8         | 17.78%  |
| Multimedia controller    | 5         | 11.11%  |
| Chipcard                 | 2         | 4.44%   |
| Bluetooth                | 2         | 4.44%   |
| Unassigned class         | 1         | 2.22%   |
| Storage                  | 1         | 2.22%   |
| Sound                    | 1         | 2.22%   |
| Modem                    | 1         | 2.22%   |
| Communication controller | 1         | 2.22%   |

