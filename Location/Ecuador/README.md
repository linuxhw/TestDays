Linux in Ecuador - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ecuador/Desktop/README.md) and [notebooks](/Location/Ecuador/Notebook/README.md).

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

Total: 416

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 245 G8                      | Notebook    | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Razer         | Blade Stealth               | Notebook    | [0ebbfdba6a](https://linux-hardware.org/?probe=0ebbfdba6a) | Oct 26, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [46e4f7a743](https://linux-hardware.org/?probe=46e4f7a743) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Alienware     | m15                         | Notebook    | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware     | m15                         | Notebook    | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9b1cc15d8a](https://linux-hardware.org/?probe=9b1cc15d8a) | Sep 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2c6027a51](https://linux-hardware.org/?probe=e2c6027a51) | Sep 30, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [8c1d3fc469](https://linux-hardware.org/?probe=8c1d3fc469) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [c38ca27643](https://linux-hardware.org/?probe=c38ca27643) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4582a5754](https://linux-hardware.org/?probe=f4582a5754) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5fac0d7732](https://linux-hardware.org/?probe=5fac0d7732) | Sep 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [09c45a1e2d](https://linux-hardware.org/?probe=09c45a1e2d) | Sep 17, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [eb0aa53dc9](https://linux-hardware.org/?probe=eb0aa53dc9) | Sep 08, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [ecc10a1197](https://linux-hardware.org/?probe=ecc10a1197) | Sep 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [9dd40cd022](https://linux-hardware.org/?probe=9dd40cd022) | Sep 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a1caab6466](https://linux-hardware.org/?probe=a1caab6466) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | Desktop     | [5df6fee2f9](https://linux-hardware.org/?probe=5df6fee2f9) | Aug 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5bd12768fa](https://linux-hardware.org/?probe=5bd12768fa) | Aug 09, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [5bd6d0c2d8](https://linux-hardware.org/?probe=5bd6d0c2d8) | Jul 20, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [d80699b846](https://linux-hardware.org/?probe=d80699b846) | Jul 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Biostar       | H61MGV3                     | Desktop     | [109f8064f6](https://linux-hardware.org/?probe=109f8064f6) | Jun 21, 2023 |
| Intel         | DG35EC AAE29266-209         | Desktop     | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | Desktop     | [3e5a0aac78](https://linux-hardware.org/?probe=3e5a0aac78) | Jun 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Dell          | Inspiron 3493               | Notebook    | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f661806559](https://linux-hardware.org/?probe=f661806559) | Jun 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [a57949da97](https://linux-hardware.org/?probe=a57949da97) | Jun 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e365621d30](https://linux-hardware.org/?probe=e365621d30) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | Notebook    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Acer          | Extensa 5220                | Notebook    | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [1f232288d7](https://linux-hardware.org/?probe=1f232288d7) | May 07, 2023 |
| Sony          | VPCEG23EL                   | Notebook    | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [76674fb178](https://linux-hardware.org/?probe=76674fb178) | Apr 26, 2023 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [5cb6709055](https://linux-hardware.org/?probe=5cb6709055) | Apr 20, 2023 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d7d0bcde76](https://linux-hardware.org/?probe=d7d0bcde76) | Apr 15, 2023 |
| Biostar       | H81MHV3L                    | Desktop     | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| HP            | Notebook                    | Notebook    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| HP            | 245 G6                      | Notebook    | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [078e440a68](https://linux-hardware.org/?probe=078e440a68) | Mar 31, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [1812fe9a19](https://linux-hardware.org/?probe=1812fe9a19) | Mar 26, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [a302d93972](https://linux-hardware.org/?probe=a302d93972) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9e45f992a1](https://linux-hardware.org/?probe=9e45f992a1) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [34fd631d2b](https://linux-hardware.org/?probe=34fd631d2b) | Mar 22, 2023 |
| Samsung       | R519/R719                   | Notebook    | [9e1cdf3582](https://linux-hardware.org/?probe=9e1cdf3582) | Mar 17, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Dell          | 014GRG A01                  | Desktop     | [2e7b556001](https://linux-hardware.org/?probe=2e7b556001) | Mar 05, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [0cf17a3787](https://linux-hardware.org/?probe=0cf17a3787) | Feb 27, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5bf68a313d](https://linux-hardware.org/?probe=5bf68a313d) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [72d2220b42](https://linux-hardware.org/?probe=72d2220b42) | Feb 07, 2023 |
| HP            | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [85dbbce597](https://linux-hardware.org/?probe=85dbbce597) | Jan 27, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [b4d38fb35a](https://linux-hardware.org/?probe=b4d38fb35a) | Jan 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| Gateway       | NV55C                       | Notebook    | [b8ae4adfdc](https://linux-hardware.org/?probe=b8ae4adfdc) | Jan 12, 2023 |
| Lenovo        | 300e 2nd Gen 81M9           | Convertible | [d36b6385d2](https://linux-hardware.org/?probe=d36b6385d2) | Jan 11, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [d7abd06e34](https://linux-hardware.org/?probe=d7abd06e34) | Jan 08, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [aa67834a96](https://linux-hardware.org/?probe=aa67834a96) | Jan 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [93adad7445](https://linux-hardware.org/?probe=93adad7445) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf4ba78c7d](https://linux-hardware.org/?probe=cf4ba78c7d) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [296edfbde5](https://linux-hardware.org/?probe=296edfbde5) | Dec 22, 2022 |
| Dynabook      | PORTEGE X40-J               | Notebook    | [3f1fc426b0](https://linux-hardware.org/?probe=3f1fc426b0) | Dec 05, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Gateway       | NV510P                      | Notebook    | [13fe5a5e78](https://linux-hardware.org/?probe=13fe5a5e78) | Oct 16, 2022 |
| Gateway       | NV510P                      | Notebook    | [7cb93d25ac](https://linux-hardware.org/?probe=7cb93d25ac) | Oct 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [71a25274d7](https://linux-hardware.org/?probe=71a25274d7) | Oct 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [ea7b836323](https://linux-hardware.org/?probe=ea7b836323) | Oct 08, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [6b528465e2](https://linux-hardware.org/?probe=6b528465e2) | Sep 20, 2022 |
| HP            | 8768 A                      | Desktop     | [dd63bfb225](https://linux-hardware.org/?probe=dd63bfb225) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fbe2b37462](https://linux-hardware.org/?probe=fbe2b37462) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [eaab7f2460](https://linux-hardware.org/?probe=eaab7f2460) | Aug 09, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [6e9be54f47](https://linux-hardware.org/?probe=6e9be54f47) | Jul 09, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google        | Delbin                      | Notebook    | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek       | UX360CA                     | Notebook    | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Alienware     | 15 R3                       | Notebook    | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Sony          | SVE14113ELW                 | Notebook    | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | Desktop     | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| Biostar       | G41D3C                      | Desktop     | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| HP            | Unknown                     | Notebook    | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| HP            | Unknown                     | Notebook    | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Google        | Panther                     | Desktop     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | Desktop     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony          | VPCEG30EL                   | Notebook    | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony          | SVE14A25CLB                 | Notebook    | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell          | Inspiron 7547               | Notebook    | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| TrekStor      | Primebook C13               | Convertible | [2c908202fc](https://linux-hardware.org/?probe=2c908202fc) | Mar 17, 2022 |
| Toshiba       | Satellite C55D-A            | Notebook    | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal        | PBL2021                     | Notebook    | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Intel         | H81                         | Desktop     | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Dell          | G5 5587                     | Notebook    | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell          | Latitude 7280               | Notebook    | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ddd3544bcf](https://linux-hardware.org/?probe=ddd3544bcf) | Jan 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fbd40dba79](https://linux-hardware.org/?probe=fbd40dba79) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f2ba12e1f](https://linux-hardware.org/?probe=9f2ba12e1f) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [82281b42b0](https://linux-hardware.org/?probe=82281b42b0) | Dec 29, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Google        | Treeya                      | Notebook    | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP            | G42                         | Notebook    | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP            | G42                         | Notebook    | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [6257ee6ddd](https://linux-hardware.org/?probe=6257ee6ddd) | Oct 07, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [5972d02719](https://linux-hardware.org/?probe=5972d02719) | Oct 07, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [2307619c77](https://linux-hardware.org/?probe=2307619c77) | Sep 27, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [d4cd8cbc7e](https://linux-hardware.org/?probe=d4cd8cbc7e) | Sep 27, 2021 |
| Foxconn       | H61MXL-K                    | Desktop     | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Toshiba       | Satellite S55-B             | Notebook    | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer          | TravelMate X3410-M          | Notebook    | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google        | Banjo                       | Notebook    | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Google        | Grunt                       | Notebook    | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google        | Grunt                       | Notebook    | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| Google        | Kip                         | Notebook    | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP            | 1000                        | Notebook    | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | 1000                        | Notebook    | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo        | ThinkPad E15 20REA00000     | Notebook    | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Dell          | G5 5587                     | Notebook    | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Shuttle       | SFM27 V20                   | Desktop     | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [35cc521571](https://linux-hardware.org/?probe=35cc521571) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony          | VPCCW1S1E                   | Notebook    | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google        | Parrot                      | Notebook    | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google        | Parrot                      | Notebook    | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP            | Pavilion 14                 | Notebook    | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| Intel         | DP55KG AAE47218-404         | Desktop     | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| HP            | ProBook 4440s               | Notebook    | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell          | Inspiron 1750               | Notebook    | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP            | 3115m                       | Notebook    | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba       | PORTEGE M805                | Notebook    | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| MSI           | B75A-G43                    | Desktop     | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | Desktop     | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Mini 210-1100               | Notebook    | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP            | 1497                        | Desktop     | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [40aeea62f1](https://linux-hardware.org/?probe=40aeea62f1) | Sep 13, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba       | Satellite P775              | Notebook    | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [1f4ef5bb49](https://linux-hardware.org/?probe=1f4ef5bb49) | Aug 19, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek       | X502CA                      | Notebook    | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer          | AO722                       | Notebook    | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | Notebook                    | Notebook    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [853f76e35e](https://linux-hardware.org/?probe=853f76e35e) | Jun 23, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [87e6d2f056](https://linux-hardware.org/?probe=87e6d2f056) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [7332f612bc](https://linux-hardware.org/?probe=7332f612bc) | May 30, 2020 |
| HP            | ProBook 4440s               | Notebook    | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [15c3385fcd](https://linux-hardware.org/?probe=15c3385fcd) | May 30, 2020 |
| Biostar       | H81MLV3                     | Desktop     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Apple         | MacBookPro13,3              | Notebook    | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP            | 15                          | Notebook    | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | Notebook    | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer          | AO722                       | Notebook    | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer          | AO722                       | Notebook    | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b37b6efdf7](https://linux-hardware.org/?probe=b37b6efdf7) | Feb 18, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [f8c6ef3229](https://linux-hardware.org/?probe=f8c6ef3229) | Feb 17, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0893b14338](https://linux-hardware.org/?probe=0893b14338) | Feb 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer          | Aspire ES1-131              | Notebook    | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell          | System XPS L502X            | Notebook    | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| HP            | 18E7                        | Desktop     | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| Toshiba       | Satellite E45t-B            | Notebook    | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Toshiba       | Satellite P55W-C            | Notebook    | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP            | Pavilion 14                 | Notebook    | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple         | MacBook1,1                  | Notebook    | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| Dell          | 0CRH6C A02                  | Desktop     | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP            | ENVY Notebook               | Notebook    | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |
| Cartimex      | H61H2-MV                    | Desktop     | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 40        | 13.56%  |
| Ubuntu 18.04       | 22        | 7.46%   |
| Ubuntu 22.04       | 15        | 5.08%   |
| Debian 11          | 10        | 3.39%   |
| OpenMandriva 4.3   | 9         | 3.05%   |
| Linux Mint 20.3    | 8         | 2.71%   |
| Linux Mint 21.1    | 7         | 2.37%   |
| Fedora 38          | 7         | 2.37%   |
| KDE neon 20.04     | 6         | 2.03%   |
| Zorin 16           | 5         | 1.69%   |
| Linux Mint 19.3    | 5         | 1.69%   |
| Fedora 36          | 5         | 1.69%   |
| Fedora 34          | 5         | 1.69%   |
| Zorin 15           | 4         | 1.36%   |
| Pop!_OS 21.10      | 4         | 1.36%   |
| Pop!_OS 21.04      | 4         | 1.36%   |
| OpenMandriva 4.2   | 4         | 1.36%   |
| OpenMandriva 23.03 | 4         | 1.36%   |
| LMDE 4             | 4         | 1.36%   |
| Fedora 33          | 4         | 1.36%   |
| Ubuntu 22.10       | 3         | 1.02%   |
| Ubuntu 21.10       | 3         | 1.02%   |
| Pop!_OS 20.04      | 3         | 1.02%   |
| OpenMandriva 23.01 | 3         | 1.02%   |
| LMDE 5             | 3         | 1.02%   |
| Linux Mint 21.2    | 3         | 1.02%   |
| Linux Mint 20.1    | 3         | 1.02%   |
| Kubuntu 22.04      | 3         | 1.02%   |
| Fedora 37          | 3         | 1.02%   |
| Elementary 5.1.7   | 3         | 1.02%   |
| CentOS 7           | 3         | 1.02%   |
| Arch Rolling       | 3         | 1.02%   |
| Arch               | 3         | 1.02%   |
| Xubuntu 20.04      | 2         | 0.68%   |
| Xubuntu 18.04      | 2         | 0.68%   |
| Ubuntu 23.10       | 2         | 0.68%   |
| Ubuntu 21.04       | 2         | 0.68%   |
| Ubuntu             | 2         | 0.68%   |
| Manjaro 21.2.5     | 2         | 0.68%   |
| Manjaro            | 2         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 91        | 31.93%  |
| Linux Mint    | 32        | 11.23%  |
| Fedora        | 28        | 9.82%   |
| OpenMandriva  | 21        | 7.37%   |
| Debian        | 15        | 5.26%   |
| Pop!_OS       | 12        | 4.21%   |
| Zorin         | 9         | 3.16%   |
| Manjaro       | 8         | 2.81%   |
| KDE neon      | 8         | 2.81%   |
| LMDE          | 7         | 2.46%   |
| Elementary    | 6         | 2.11%   |
| Arch          | 6         | 2.11%   |
| Xubuntu       | 5         | 1.75%   |
| Lubuntu       | 4         | 1.4%    |
| Kubuntu       | 4         | 1.4%    |
| CentOS        | 3         | 1.05%   |
| Ubuntu MATE   | 2         | 0.7%    |
| Ubuntu Budgie | 2         | 0.7%    |
| SteamOS       | 2         | 0.7%    |
| openSUSE      | 2         | 0.7%    |
| Kali          | 2         | 0.7%    |
| Garuda Linux  | 2         | 0.7%    |
| Endless       | 2         | 0.7%    |
| Clear Linux   | 2         | 0.7%    |
| BlackPanther  | 2         | 0.7%    |
| ArcoLinux     | 2         | 0.7%    |
| Void Linux    | 1         | 0.35%   |
| RHEL          | 1         | 0.35%   |
| Peppermint    | 1         | 0.35%   |
| Nobara        | 1         | 0.35%   |
| EndeavourOS   | 1         | 0.35%   |
| Deepin        | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 8         | 2.51%   |
| 5.4.0-54-generic         | 6         | 1.88%   |
| 5.4.0-42-generic         | 5         | 1.57%   |
| 5.15.0-56-generic        | 5         | 1.57%   |
| 5.13.0-35-generic        | 5         | 1.57%   |
| 5.4.0-45-generic         | 4         | 1.25%   |
| 5.15.0-33-generic        | 4         | 1.25%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.25%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.94%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.94%   |
| 5.8.0-41-generic         | 3         | 0.94%   |
| 5.4.0-7634-generic       | 3         | 0.94%   |
| 5.4.0-58-generic         | 3         | 0.94%   |
| 5.4.0-56-generic         | 3         | 0.94%   |
| 5.4.0-48-generic         | 3         | 0.94%   |
| 5.4.0-37-generic         | 3         | 0.94%   |
| 5.4.0-26-generic         | 3         | 0.94%   |
| 5.16.11-76051611-generic | 3         | 0.94%   |
| 5.13.0-7614-generic      | 3         | 0.94%   |
| 5.0.0-37-generic         | 3         | 0.94%   |
| 5.0.0-23-generic         | 3         | 0.94%   |
| 6.2.15-300.fc38.x86_64   | 2         | 0.63%   |
| 6.2.0-33-generic         | 2         | 0.63%   |
| 6.1.0-9-amd64            | 2         | 0.63%   |
| 6.1.0-13-amd64           | 2         | 0.63%   |
| 5.8.0-50-generic         | 2         | 0.63%   |
| 5.8.0-43-generic         | 2         | 0.63%   |
| 5.8.0-14-generic         | 2         | 0.63%   |
| 5.4.0-77-generic         | 2         | 0.63%   |
| 5.4.0-73-generic         | 2         | 0.63%   |
| 5.4.0-47-generic         | 2         | 0.63%   |
| 5.4.0-29-generic         | 2         | 0.63%   |
| 5.4.0-110-generic        | 2         | 0.63%   |
| 5.3.0-62-generic         | 2         | 0.63%   |
| 5.15.59-xanmod1          | 2         | 0.63%   |
| 5.15.0-73-generic        | 2         | 0.63%   |
| 5.15.0-58-generic        | 2         | 0.63%   |
| 5.15.0-50-generic        | 2         | 0.63%   |
| 5.15.0-27-generic        | 2         | 0.63%   |
| 5.13.0-51-generic        | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 57        | 18.94%  |
| 5.15.0  | 30        | 9.97%   |
| 5.13.0  | 19        | 6.31%   |
| 4.15.0  | 18        | 5.98%   |
| 5.8.0   | 12        | 3.99%   |
| 5.16.7  | 9         | 2.99%   |
| 5.11.0  | 9         | 2.99%   |
| 5.10.0  | 9         | 2.99%   |
| 5.0.0   | 9         | 2.99%   |
| 5.19.0  | 7         | 2.33%   |
| 5.3.0   | 6         | 1.99%   |
| 6.2.0   | 5         | 1.66%   |
| 6.1.0   | 4         | 1.33%   |
| 5.10.14 | 4         | 1.33%   |
| 6.2.6   | 3         | 1%      |
| 6.1.1   | 3         | 1%      |
| 5.17.5  | 3         | 1%      |
| 5.16.11 | 3         | 1%      |
| 4.19.0  | 3         | 1%      |
| 4.18.0  | 3         | 1%      |
| 3.10.0  | 3         | 1%      |
| 6.5.0   | 2         | 0.66%   |
| 6.4.10  | 2         | 0.66%   |
| 6.3.5   | 2         | 0.66%   |
| 6.2.2   | 2         | 0.66%   |
| 6.2.15  | 2         | 0.66%   |
| 5.16.13 | 2         | 0.66%   |
| 5.16.0  | 2         | 0.66%   |
| 5.15.59 | 2         | 0.66%   |
| 5.11.16 | 2         | 0.66%   |
| 4.18.16 | 2         | 0.66%   |
| 6.5.6   | 1         | 0.33%   |
| 6.5.3   | 1         | 0.33%   |
| 6.4.8   | 1         | 0.33%   |
| 6.4.6   | 1         | 0.33%   |
| 6.2.9   | 1         | 0.33%   |
| 6.2.12  | 1         | 0.33%   |
| 6.2.1   | 1         | 0.33%   |
| 6.1.9   | 1         | 0.33%   |
| 6.1.2   | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 20.27%  |
| 5.15    | 37        | 12.5%   |
| 5.13    | 20        | 6.76%   |
| 5.10    | 18        | 6.08%   |
| 4.15    | 18        | 6.08%   |
| 5.16    | 17        | 5.74%   |
| 6.2     | 15        | 5.07%   |
| 5.8     | 14        | 4.73%   |
| 5.19    | 12        | 4.05%   |
| 5.11    | 12        | 4.05%   |
| 5.0     | 10        | 3.38%   |
| 6.1     | 9         | 3.04%   |
| 5.3     | 8         | 2.7%    |
| 5.17    | 6         | 2.03%   |
| 4.18    | 5         | 1.69%   |
| 6.5     | 4         | 1.35%   |
| 6.4     | 4         | 1.35%   |
| 5.18    | 4         | 1.35%   |
| 6.0     | 3         | 1.01%   |
| 5.7     | 3         | 1.01%   |
| 5.14    | 3         | 1.01%   |
| 4.19    | 3         | 1.01%   |
| 3.10    | 3         | 1.01%   |
| 6.3     | 2         | 0.68%   |
| 5.5     | 2         | 0.68%   |
| 5.12    | 2         | 0.68%   |
| 5.9     | 1         | 0.34%   |
| 4.9     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 256       | 95.52%  |
| i686   | 12        | 4.48%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 122       | 43.26%  |
| KDE5       | 46        | 16.31%  |
| Unknown    | 30        | 10.64%  |
| X-Cinnamon | 29        | 10.28%  |
| XFCE       | 17        | 6.03%   |
| MATE       | 9         | 3.19%   |
| Pantheon   | 6         | 2.13%   |
| KDE        | 6         | 2.13%   |
| LXDE       | 5         | 1.77%   |
| LXQt       | 3         | 1.06%   |
| qtile      | 2         | 0.71%   |
| Deepin     | 2         | 0.71%   |
| Budgie     | 2         | 0.71%   |
| jwm        | 1         | 0.35%   |
| ICEWM      | 1         | 0.35%   |
| Cinnamon   | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 212       | 75.44%  |
| Wayland | 53        | 18.86%  |
| Unknown | 15        | 5.34%   |
| Tty     | 1         | 0.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 149       | 52.46%  |
| SDDM    | 41        | 14.44%  |
| GDM     | 35        | 12.32%  |
| GDM3    | 31        | 10.92%  |
| LightDM | 23        | 8.1%    |
| TDM     | 5         | 1.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_EC   | 124       | 44.77%  |
| en_US   | 78        | 28.16%  |
| es_ES   | 25        | 9.03%   |
| Unknown | 20        | 7.22%   |
| es_MX   | 8         | 2.89%   |
| de_DE   | 4         | 1.44%   |
| es_US   | 3         | 1.08%   |
| es_PE   | 3         | 1.08%   |
| es_CO   | 3         | 1.08%   |
| C       | 3         | 1.08%   |
| ru_RU   | 2         | 0.72%   |
| fr_FR   | 2         | 0.72%   |
| en_GB   | 1         | 0.36%   |
| en_AG   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 139       | 50.36%  |
| BIOS | 137       | 49.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 207       | 74.73%  |
| Btrfs   | 29        | 10.47%  |
| Overlay | 24        | 8.66%   |
| Xfs     | 5         | 1.81%   |
| Tmpfs   | 5         | 1.81%   |
| Unknown | 4         | 1.44%   |
| Zfs     | 2         | 0.72%   |
| Ext2    | 1         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 156       | 56.93%  |
| GPT     | 91        | 33.21%  |
| MBR     | 27        | 9.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 235       | 86.08%  |
| Yes       | 38        | 13.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 188       | 68.86%  |
| Yes       | 85        | 31.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 47        | 17.54%  |
| ASUSTek Computer      | 39        | 14.55%  |
| Lenovo                | 34        | 12.69%  |
| Dell                  | 31        | 11.57%  |
| Toshiba               | 13        | 4.85%   |
| Gigabyte Technology   | 13        | 4.85%   |
| Intel                 | 10        | 3.73%   |
| Acer                  | 10        | 3.73%   |
| Biostar               | 9         | 3.36%   |
| Apple                 | 8         | 2.99%   |
| Google                | 7         | 2.61%   |
| Sony                  | 6         | 2.24%   |
| Samsung Electronics   | 4         | 1.49%   |
| MSI                   | 4         | 1.49%   |
| ASRock                | 4         | 1.49%   |
| Gateway               | 3         | 1.12%   |
| Foxconn               | 3         | 1.12%   |
| Unknown               | 3         | 1.12%   |
| Valve                 | 2         | 0.75%   |
| Razer                 | 2         | 0.75%   |
| Alienware             | 2         | 0.75%   |
| XTRATECH COMPUTERS SA | 1         | 0.37%   |
| TrekStor              | 1         | 0.37%   |
| TPV-INVENTA           | 1         | 0.37%   |
| Timi                  | 1         | 0.37%   |
| Shuttle               | 1         | 0.37%   |
| Pegatron              | 1         | 0.37%   |
| HUAWEI                | 1         | 0.37%   |
| Fujitsu               | 1         | 0.37%   |
| ECS                   | 1         | 0.37%   |
| Dynabook              | 1         | 0.37%   |
| Compal                | 1         | 0.37%   |
| Chuwi                 | 1         | 0.37%   |
| Cartimex              | 1         | 0.37%   |
| AMI                   | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 1.49%   |
| Unknown                                  | 4         | 1.49%   |
| HP Notebook                              | 3         | 1.12%   |
| ASUS PRIME A320M-A                       | 3         | 1.12%   |
| Valve Jupiter                            | 2         | 0.75%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 2         | 0.75%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.75%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 2         | 0.75%   |
| HP ProBook 4440s                         | 2         | 0.75%   |
| HP Pavilion Laptop 15-cw1xxx             | 2         | 0.75%   |
| HP Pavilion Laptop 15-cw0xxx             | 2         | 0.75%   |
| HP Laptop 15-da0xxx                      | 2         | 0.75%   |
| Gigabyte H81M-H                          | 2         | 0.75%   |
| Dell Vostro 3480                         | 2         | 0.75%   |
| Dell OptiPlex 9020                       | 2         | 0.75%   |
| Dell Inspiron 5570                       | 2         | 0.75%   |
| Dell Inspiron 3442                       | 2         | 0.75%   |
| Dell Inspiron 1420                       | 2         | 0.75%   |
| Dell G5 5587                             | 2         | 0.75%   |
| Biostar H61MGV3                          | 2         | 0.75%   |
| Biostar G31-M7 TE                        | 2         | 0.75%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 2         | 0.75%   |
| Apple MacBookPro12,1                     | 2         | 0.75%   |
| XTRATECH COMPUTERS SA MN-1022X           | 1         | 0.37%   |
| TrekStor Primebook C13                   | 1         | 0.37%   |
| TPV-INVENTA 2AF2 A01                     | 1         | 0.37%   |
| Toshiba Satellite S55-B                  | 1         | 0.37%   |
| Toshiba Satellite S55-A                  | 1         | 0.37%   |
| Toshiba Satellite P775                   | 1         | 0.37%   |
| Toshiba Satellite P55W-C                 | 1         | 0.37%   |
| Toshiba Satellite L50-B                  | 1         | 0.37%   |
| Toshiba Satellite L45-B                  | 1         | 0.37%   |
| Toshiba Satellite E45t-B                 | 1         | 0.37%   |
| Toshiba Satellite C55D-A                 | 1         | 0.37%   |
| Toshiba Satellite C55-B                  | 1         | 0.37%   |
| Toshiba Satellite C45-A                  | 1         | 0.37%   |
| Toshiba Satellite A205                   | 1         | 0.37%   |
| Toshiba Satellite A135                   | 1         | 0.37%   |
| Toshiba PORTEGE M805                     | 1         | 0.37%   |
| Timi RedmiBook 14-APCS                   | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 17        | 6.34%   |
| Lenovo IdeaPad                 | 15        | 5.6%    |
| Toshiba Satellite              | 12        | 4.48%   |
| HP Pavilion                    | 11        | 4.1%    |
| ASUS PRIME                     | 10        | 3.73%   |
| Lenovo ThinkPad                | 8         | 2.99%   |
| HP Laptop                      | 7         | 2.61%   |
| ASUS VivoBook                  | 7         | 2.61%   |
| Acer Aspire                    | 6         | 2.24%   |
| HP ENVY                        | 5         | 1.87%   |
| Dell Latitude                  | 5         | 1.87%   |
| ASUS All                       | 4         | 1.49%   |
| Unknown                        | 4         | 1.49%   |
| HP ProBook                     | 3         | 1.12%   |
| HP Notebook                    | 3         | 1.12%   |
| HP EliteBook                   | 3         | 1.12%   |
| Valve Jupiter                  | 2         | 0.75%   |
| Razer Blade                    | 2         | 0.75%   |
| Lenovo Yoga                    | 2         | 0.75%   |
| HP 245                         | 2         | 0.75%   |
| HP 15                          | 2         | 0.75%   |
| Gigabyte H81M-H                | 2         | 0.75%   |
| Gigabyte H410M                 | 2         | 0.75%   |
| Dell Vostro                    | 2         | 0.75%   |
| Dell OptiPlex                  | 2         | 0.75%   |
| Dell G5                        | 2         | 0.75%   |
| Biostar H61MGV3                | 2         | 0.75%   |
| Biostar G31-M7                 | 2         | 0.75%   |
| ASUS TUF                       | 2         | 0.75%   |
| ASUS ROG                       | 2         | 0.75%   |
| ASUS ASUS                      | 2         | 0.75%   |
| Apple MacBookPro12             | 2         | 0.75%   |
| Acer TravelMate                | 2         | 0.75%   |
| XTRATECH COMPUTERS SA MN-1022X | 1         | 0.37%   |
| TrekStor Primebook             | 1         | 0.37%   |
| TPV-INVENTA 2AF2               | 1         | 0.37%   |
| Toshiba PORTEGE                | 1         | 0.37%   |
| Timi RedmiBook                 | 1         | 0.37%   |
| Sony VPCEG30EL                 | 1         | 0.37%   |
| Sony VPCEG23EL                 | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 31        | 11.57%  |
| 2020 | 27        | 10.07%  |
| 2019 | 25        | 9.33%   |
| 2013 | 23        | 8.58%   |
| 2017 | 22        | 8.21%   |
| 2012 | 22        | 8.21%   |
| 2021 | 16        | 5.97%   |
| 2011 | 16        | 5.97%   |
| 2016 | 14        | 5.22%   |
| 2015 | 13        | 4.85%   |
| 2014 | 12        | 4.48%   |
| 2009 | 11        | 4.1%    |
| 2010 | 9         | 3.36%   |
| 2007 | 9         | 3.36%   |
| 2008 | 6         | 2.24%   |
| 2023 | 4         | 1.49%   |
| 2022 | 4         | 1.49%   |
| 2006 | 3         | 1.12%   |
| 2005 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 179       | 66.79%  |
| Desktop     | 75        | 27.99%  |
| Convertible | 11        | 4.1%    |
| Mini pc     | 2         | 0.75%   |
| Tablet      | 1         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 252       | 93.33%  |
| Enabled  | 18        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 260       | 97.01%  |
| Yes  | 8         | 2.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 27.08%  |
| 8.01-16.0   | 61        | 22.02%  |
| 3.01-4.0    | 54        | 19.49%  |
| 16.01-24.0  | 38        | 13.72%  |
| 1.01-2.0    | 20        | 7.22%   |
| 32.01-64.0  | 16        | 5.78%   |
| 24.01-32.0  | 6         | 2.17%   |
| 2.01-3.0    | 4         | 1.44%   |
| 64.01-256.0 | 2         | 0.72%   |
| 0.51-1.0    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 89        | 29.77%  |
| 2.01-3.0   | 87        | 29.1%   |
| 4.01-8.0   | 49        | 16.39%  |
| 3.01-4.0   | 45        | 15.05%  |
| 0.51-1.0   | 13        | 4.35%   |
| 8.01-16.0  | 11        | 3.68%   |
| 0.01-0.5   | 4         | 1.34%   |
| 24.01-32.0 | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 188       | 68.36%  |
| 2      | 68        | 24.73%  |
| 3      | 15        | 5.45%   |
| 5      | 2         | 0.73%   |
| 4      | 2         | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 171       | 63.33%  |
| Yes       | 99        | 36.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 82.84%  |
| No        | 46        | 17.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 218       | 80.74%  |
| No        | 52        | 19.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 62.59%  |
| No        | 101       | 37.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ecuador | 268       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 111       | 40.22%  |
| Guayaquil                      | 76        | 27.54%  |
| Cuenca                         | 27        | 9.78%   |
| Loja                           | 8         | 2.9%    |
| Manta                          | 7         | 2.54%   |
| Ambato                         | 5         | 1.81%   |
| Machala                        | 4         | 1.45%   |
| Riobamba                       | 3         | 1.09%   |
| Portoviejo                     | 3         | 1.09%   |
| Latacunga                      | 3         | 1.09%   |
| Hacienda Ibarra                | 3         | 1.09%   |
| Santo Domingo de los Colorados | 2         | 0.72%   |
| Cotacachi                      | 2         | 0.72%   |
| Uyumbicho                      | 1         | 0.36%   |
| Samborondon                    | 1         | 0.36%   |
| Quevedo                        | 1         | 0.36%   |
| Ponceano                       | 1         | 0.36%   |
| Otavalo                        | 1         | 0.36%   |
| Nueva Loja                     | 1         | 0.36%   |
| Montecristi                    | 1         | 0.36%   |
| Las Pinas                      | 1         | 0.36%   |
| La Troncal                     | 1         | 0.36%   |
| La Providencia                 | 1         | 0.36%   |
| La Mana                        | 1         | 0.36%   |
| La Concordia Numero Uno        | 1         | 0.36%   |
| Ibarra                         | 1         | 0.36%   |
| Hacienda San Sebastian         | 1         | 0.36%   |
| Hacienda La Libertad           | 1         | 0.36%   |
| Guanujo                        | 1         | 0.36%   |
| Guamani                        | 1         | 0.36%   |
| Cayambe                        | 1         | 0.36%   |
| Cariamanga                     | 1         | 0.36%   |
| Babahoyo                       | 1         | 0.36%   |
| Azogues                        | 1         | 0.36%   |
| Ayacucho                       | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 75        | 106    | 21.19%  |
| Toshiba                     | 48        | 55     | 13.56%  |
| Seagate                     | 48        | 73     | 13.56%  |
| Samsung Electronics         | 26        | 28     | 7.34%   |
| Kingston                    | 26        | 46     | 7.34%   |
| Hitachi                     | 16        | 19     | 4.52%   |
| Unknown                     | 13        | 21     | 3.67%   |
| SK hynix                    | 10        | 12     | 2.82%   |
| SanDisk                     | 9         | 13     | 2.54%   |
| Hewlett-Packard             | 9         | 9      | 2.54%   |
| A-DATA Technology           | 9         | 14     | 2.54%   |
| Intel                       | 6         | 9      | 1.69%   |
| HGST                        | 6         | 8      | 1.69%   |
| Micron Technology           | 5         | 5      | 1.41%   |
| KIOXIA                      | 4         | 5      | 1.13%   |
| Kingston Technology Company | 4         | 6      | 1.13%   |
| Apple                       | 4         | 5      | 1.13%   |
| PNY                         | 3         | 3      | 0.85%   |
| Fujitsu                     | 3         | 3      | 0.85%   |
| SPCC                        | 2         | 2      | 0.56%   |
| Phison Electronics          | 2         | 2      | 0.56%   |
| JMicron Technology          | 2         | 2      | 0.56%   |
| Gigabyte Technology         | 2         | 2      | 0.56%   |
| Crucial                     | 2         | 2      | 0.56%   |
| Unknown                     | 2         | 2      | 0.56%   |
| USB3.0                      | 1         | 1      | 0.28%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.28%   |
| UMIS                        | 1         | 1      | 0.28%   |
| SABRENT                     | 1         | 1      | 0.28%   |
| Realtek Semiconductor       | 1         | 1      | 0.28%   |
| Phison                      | 1         | 1      | 0.28%   |
| Patriot                     | 1         | 1      | 0.28%   |
| OWC                         | 1         | 1      | 0.28%   |
| Netac                       | 1         | 1      | 0.28%   |
| Micron/Crucial Technology   | 1         | 1      | 0.28%   |
| Micro Center                | 1         | 1      | 0.28%   |
| Maxtor                      | 1         | 1      | 0.28%   |
| LITEON                      | 1         | 1      | 0.28%   |
| Lite-On                     | 1         | 1      | 0.28%   |
| Imation                     | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 11        | 2.88%   |
| Toshiba MQ04ABF100 1TB                  | 7         | 1.83%   |
| Toshiba MQ01ABF050 500GB                | 6         | 1.57%   |
| Seagate ST500DM002-1BD142 500GB         | 6         | 1.57%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 5         | 1.31%   |
| Toshiba DT01ACA100 1TB                  | 5         | 1.31%   |
| HP SSD S700 500GB                       | 5         | 1.31%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 4         | 1.05%   |
| Unknown MMC Card  16GB                  | 4         | 1.05%   |
| Seagate ST2000LM007-1R8174 2TB          | 4         | 1.05%   |
| Kingston SA400S37480G 480GB SSD         | 4         | 1.05%   |
| WDC WD10SPZX-24Z10 1TB                  | 3         | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 0.79%   |
| Unknown MMC Card  32GB                  | 3         | 0.79%   |
| Toshiba DT01ACA200 2TB                  | 3         | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.79%   |
| Samsung HD502HJ 500GB                   | 3         | 0.79%   |
| Kingston SV300S37A60G 64GB SSD          | 3         | 0.79%   |
| A-DATA SU650 120GB SSD                  | 3         | 0.79%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 2         | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 2         | 0.52%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 0.52%   |
| WDC WD40EFAX-68JH4N1 4TB                | 2         | 0.52%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 0.52%   |
| WDC WD10SPZX-22Z10T1 1TB                | 2         | 0.52%   |
| WDC WD10JPVX-75JC3T0 1TB                | 2         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.52%   |
| Unknown MMC Card  64GB                  | 2         | 0.52%   |
| Unknown MMC Card  128GB                 | 2         | 0.52%   |
| Toshiba MQ01ABD100M 1TB                 | 2         | 0.52%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.52%   |
| Toshiba MK7559GSXP 752GB                | 2         | 0.52%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 256GB           | 2         | 0.52%   |
| Seagate ST9500325AS 500GB               | 2         | 0.52%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 55        | 81     | 29.41%  |
| Seagate             | 48        | 73     | 25.67%  |
| Toshiba             | 43        | 49     | 22.99%  |
| Hitachi             | 16        | 19     | 8.56%   |
| Samsung Electronics | 12        | 14     | 6.42%   |
| HGST                | 6         | 8      | 3.21%   |
| Fujitsu             | 3         | 3      | 1.6%    |
| USB3.0              | 1         | 1      | 0.53%   |
| Unknown             | 1         | 3      | 0.53%   |
| Maxtor              | 1         | 1      | 0.53%   |
| HPE                 | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 33     | 25%     |
| WDC                 | 16        | 18     | 17.39%  |
| Hewlett-Packard     | 8         | 8      | 8.7%    |
| A-DATA Technology   | 8         | 12     | 8.7%    |
| SanDisk             | 5         | 5      | 5.43%   |
| Samsung Electronics | 4         | 4      | 4.35%   |
| Toshiba             | 3         | 4      | 3.26%   |
| PNY                 | 3         | 3      | 3.26%   |
| Apple               | 3         | 4      | 3.26%   |
| SPCC                | 2         | 2      | 2.17%   |
| SK hynix            | 2         | 2      | 2.17%   |
| Intel               | 2         | 2      | 2.17%   |
| Gigabyte Technology | 2         | 2      | 2.17%   |
| Crucial             | 2         | 2      | 2.17%   |
| SABRENT             | 1         | 1      | 1.09%   |
| Patriot             | 1         | 1      | 1.09%   |
| OWC                 | 1         | 1      | 1.09%   |
| Netac               | 1         | 1      | 1.09%   |
| Micron Technology   | 1         | 1      | 1.09%   |
| Micro Center        | 1         | 1      | 1.09%   |
| LITEON              | 1         | 1      | 1.09%   |
| HS-SSD-E100N        | 1         | 1      | 1.09%   |
| Golden              | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 168       | 253    | 51.69%  |
| SSD     | 82        | 110    | 25.23%  |
| NVMe    | 60        | 85     | 18.46%  |
| MMC     | 13        | 20     | 4%      |
| Unknown | 2         | 2      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 221       | 352    | 73.42%  |
| NVMe | 60        | 84     | 19.93%  |
| MMC  | 13        | 20     | 4.32%   |
| SAS  | 7         | 14     | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 150       | 207    | 57.92%  |
| 0.51-1.0   | 86        | 124    | 33.2%   |
| 1.01-2.0   | 19        | 25     | 7.34%   |
| 3.01-4.0   | 3         | 6      | 1.16%   |
| 2.01-3.0   | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 72        | 25.17%  |
| 101-250        | 66        | 23.08%  |
| 501-1000       | 47        | 16.43%  |
| 1001-2000      | 34        | 11.89%  |
| 1-20           | 23        | 8.04%   |
| 51-100         | 15        | 5.24%   |
| 21-50          | 13        | 4.55%   |
| More than 3000 | 8         | 2.8%    |
| Unknown        | 7         | 2.45%   |
| 2001-3000      | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 106       | 35.81%  |
| 21-50          | 54        | 18.24%  |
| 101-250        | 46        | 15.54%  |
| 251-500        | 29        | 9.8%    |
| 51-100         | 28        | 9.46%   |
| 501-1000       | 15        | 5.07%   |
| 1001-2000      | 8         | 2.7%    |
| Unknown        | 7         | 2.36%   |
| More than 3000 | 2         | 0.68%   |
| 2001-3000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2         | 3      | 6.9%    |
| Hitachi HDS721050CLA660 500GB     | 2         | 2      | 6.9%    |
| WDC WD5000LPVT-00G33T0 500GB      | 1         | 1      | 3.45%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 1      | 3.45%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1         | 1      | 3.45%   |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB          | 1         | 2      | 3.45%   |
| Toshiba MQ01ABD100M 1TB           | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 3.45%   |
| Toshiba MK7559GSXP 752GB          | 1         | 1      | 3.45%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 3.45%   |
| Toshiba MK3259GSXP 320GB          | 1         | 1      | 3.45%   |
| Toshiba MK2561GSYN 250GB          | 1         | 2      | 3.45%   |
| Seagate ST3750330AS 752GB         | 1         | 1      | 3.45%   |
| Seagate ST31000333AS 1TB          | 1         | 2      | 3.45%   |
| Seagate ST1000LX015-1U7172 1TB    | 1         | 3      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 3.45%   |
| Samsung Electronics HD501LJ 500GB | 1         | 1      | 3.45%   |
| Samsung Electronics HD322HJ 320GB | 1         | 1      | 3.45%   |
| Kingston SNS4151S316GD 16GB SSD   | 1         | 1      | 3.45%   |
| HPE MB0500EAMZD 500GB             | 1         | 1      | 3.45%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 3.45%   |
| Hitachi HTS543232L9SA00 320GB     | 1         | 1      | 3.45%   |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 3.45%   |
| Fujitsu MHZ2160BH G1 160GB        | 1         | 1      | 3.45%   |
| Fujitsu MHY2250BH 250GB           | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 9      | 24.14%  |
| Seagate             | 7         | 12     | 24.14%  |
| WDC                 | 4         | 4      | 13.79%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Fujitsu             | 2         | 2      | 6.9%    |
| Kingston            | 1         | 1      | 3.45%   |
| HPE                 | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 9      | 25%     |
| Seagate             | 7         | 12     | 25%     |
| WDC                 | 4         | 4      | 14.29%  |
| Hitachi             | 4         | 4      | 14.29%  |
| Samsung Electronics | 2         | 2      | 7.14%   |
| Fujitsu             | 2         | 2      | 7.14%   |
| HPE                 | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 35     | 96%     |
| SSD  | 1         | 1      | 4%      |

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
| Detected | 171       | 310    | 59.79%  |
| Works    | 90        | 124    | 31.47%  |
| Malfunc  | 25        | 36     | 8.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 183       | 58.84%  |
| AMD                          | 53        | 17.04%  |
| Samsung Electronics          | 13        | 4.18%   |
| SanDisk                      | 11        | 3.54%   |
| Kingston Technology Company  | 9         | 2.89%   |
| SK hynix                     | 8         | 2.57%   |
| Micron Technology            | 4         | 1.29%   |
| Marvell Technology Group     | 4         | 1.29%   |
| KIOXIA                       | 4         | 1.29%   |
| Phison Electronics           | 3         | 0.96%   |
| JMicron Technology           | 3         | 0.96%   |
| VIA Technologies             | 2         | 0.64%   |
| Union Memory (Shenzhen)      | 2         | 0.64%   |
| Toshiba America Info Systems | 2         | 0.64%   |
| Nvidia                       | 2         | 0.64%   |
| ASMedia Technology           | 2         | 0.64%   |
| Silicon Motion               | 1         | 0.32%   |
| Realtek Semiconductor        | 1         | 0.32%   |
| Micron/Crucial Technology    | 1         | 0.32%   |
| Lite-On Technology           | 1         | 0.32%   |
| Apple                        | 1         | 0.32%   |
| ADATA Technology             | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42        | 11.9%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 19        | 5.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 18        | 5.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 3.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 3.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5         | 1.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.42%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 4         | 1.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 1.13%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                                  | 4         | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.13%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.13%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.13%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 0.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 3         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 0.57%   |
| SK hynix BC511 NVMe SSD                                                                 | 2         | 0.57%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 190       | 60.32%  |
| NVMe | 60        | 19.05%  |
| IDE  | 36        | 11.43%  |
| RAID | 29        | 9.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 204       | 76.12%  |
| AMD    | 64        | 23.88%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 3.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 2.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 4         | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.12%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 1.12%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 1.12%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.12%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.12%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.12%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.12%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 1.12%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 3         | 1.12%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 2         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.75%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.75%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 2         | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.75%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 2         | 0.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.75%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.75%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.75%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 0.75%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 2         | 0.75%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 2         | 0.75%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz          | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 58        | 21.64%  |
| Intel Core i5           | 52        | 19.4%   |
| Intel Core i3           | 25        | 9.33%   |
| AMD Ryzen 5             | 23        | 8.58%   |
| Intel Celeron           | 22        | 8.21%   |
| Intel Core 2 Duo        | 13        | 4.85%   |
| Other                   | 12        | 4.48%   |
| AMD Ryzen 7             | 8         | 2.99%   |
| Intel Pentium           | 7         | 2.61%   |
| Intel Atom              | 7         | 2.61%   |
| AMD E1                  | 4         | 1.49%   |
| Intel Pentium Dual-Core | 3         | 1.12%   |
| AMD Ryzen 3             | 3         | 1.12%   |
| AMD A6                  | 3         | 1.12%   |
| Intel Genuine           | 2         | 0.75%   |
| Intel Core 2 Quad       | 2         | 0.75%   |
| AMD E2                  | 2         | 0.75%   |
| AMD E                   | 2         | 0.75%   |
| AMD Athlon II X2        | 2         | 0.75%   |
| AMD A8                  | 2         | 0.75%   |
| AMD A4                  | 2         | 0.75%   |
| AMD A12                 | 2         | 0.75%   |
| Intel Xeon              | 1         | 0.37%   |
| Intel Pentium M         | 1         | 0.37%   |
| Intel Core m3           | 1         | 0.37%   |
| Intel Celeron M         | 1         | 0.37%   |
| AMD Ryzen 7 PRO         | 1         | 0.37%   |
| AMD Phenom II X6        | 1         | 0.37%   |
| AMD Phenom II X2        | 1         | 0.37%   |
| AMD FX                  | 1         | 0.37%   |
| AMD C-70                | 1         | 0.37%   |
| AMD C-60                | 1         | 0.37%   |
| AMD Athlon II Neo       | 1         | 0.37%   |
| AMD A10                 | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 130       | 48.51%  |
| 4      | 94        | 35.07%  |
| 6      | 23        | 8.58%   |
| 8      | 10        | 3.73%   |
| 1      | 8         | 2.99%   |
| 14     | 3         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 268       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 167       | 62.31%  |
| 1      | 101       | 37.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 263       | 98.13%  |
| 32-bit         | 3         | 1.12%   |
| Unknown        | 2         | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 22.58%  |
| 0x306a9    | 18        | 6.45%   |
| 0x206a7    | 16        | 5.73%   |
| 0x806ea    | 15        | 5.38%   |
| 0x306c3    | 14        | 5.02%   |
| 0x306d4    | 9         | 3.23%   |
| 0x1067a    | 9         | 3.23%   |
| 0x40651    | 8         | 2.87%   |
| 0x6fd      | 7         | 2.51%   |
| 0x08108109 | 7         | 2.51%   |
| 0x06006705 | 5         | 1.79%   |
| 0xa0653    | 4         | 1.43%   |
| 0x906ed    | 4         | 1.43%   |
| 0x906ea    | 4         | 1.43%   |
| 0x806c1    | 4         | 1.43%   |
| 0x706e5    | 4         | 1.43%   |
| 0x0810100b | 4         | 1.43%   |
| 0x05000119 | 4         | 1.43%   |
| 0x806eb    | 3         | 1.08%   |
| 0x806e9    | 3         | 1.08%   |
| 0x706a1    | 3         | 1.08%   |
| 0x406e3    | 3         | 1.08%   |
| 0x406c4    | 3         | 1.08%   |
| 0x30678    | 3         | 1.08%   |
| 0x106ca    | 3         | 1.08%   |
| 0x08600104 | 3         | 1.08%   |
| 0x06006704 | 3         | 1.08%   |
| 0x0600611a | 3         | 1.08%   |
| 0x806ec    | 2         | 0.72%   |
| 0x706a8    | 2         | 0.72%   |
| 0x6e8      | 2         | 0.72%   |
| 0x506e3    | 2         | 0.72%   |
| 0x20655    | 2         | 0.72%   |
| 0x106e5    | 2         | 0.72%   |
| 0x0a201005 | 2         | 0.72%   |
| 0x08701021 | 2         | 0.72%   |
| 0x0700010f | 2         | 0.72%   |
| 0x010000c8 | 2         | 0.72%   |
| 0xb06f2    | 1         | 0.36%   |
| 0xa0660    | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 47        | 17.47%  |
| Haswell          | 28        | 10.41%  |
| IvyBridge        | 21        | 7.81%   |
| SandyBridge      | 17        | 6.32%   |
| Excavator        | 12        | 4.46%   |
| Penryn           | 11        | 4.09%   |
| Core             | 11        | 4.09%   |
| Zen+             | 10        | 3.72%   |
| Zen 2            | 9         | 3.35%   |
| Broadwell        | 9         | 3.35%   |
| Unknown          | 9         | 3.35%   |
| Skylake          | 8         | 2.97%   |
| Silvermont       | 8         | 2.97%   |
| CometLake        | 7         | 2.6%    |
| Zen              | 6         | 2.23%   |
| TigerLake        | 6         | 2.23%   |
| IceLake          | 6         | 2.23%   |
| Bobcat           | 6         | 2.23%   |
| Zen 3            | 5         | 1.86%   |
| K10              | 5         | 1.86%   |
| Goldmont plus    | 5         | 1.86%   |
| Bonnell          | 5         | 1.86%   |
| Westmere         | 4         | 1.49%   |
| P6               | 3         | 1.12%   |
| Nehalem          | 3         | 1.12%   |
| Jaguar           | 2         | 0.74%   |
| Goldmont         | 2         | 0.74%   |
| Alderlake Hybrid | 2         | 0.74%   |
| Puma             | 1         | 0.37%   |
| K10 Llano        | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 184       | 59.35%  |
| AMD              | 73        | 23.55%  |
| Nvidia           | 52        | 16.77%  |
| VIA Technologies | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 18        | 5.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 4.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 3.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 3.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 2.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 2.18%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.87%   |
| Intel HD Graphics 620                                                                    | 6         | 1.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 5         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.25%   |
| Intel HD Graphics 630                                                                    | 4         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.25%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1.25%   |
| AMD Lucienne                                                                             | 4         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.93%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.93%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.93%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 146       | 53.87%  |
| 1 x AMD                  | 58        | 21.4%   |
| 1 x Nvidia               | 24        | 8.86%   |
| Intel + Nvidia           | 24        | 8.86%   |
| Intel + AMD              | 10        | 3.69%   |
| AMD + Nvidia             | 4         | 1.48%   |
| 2 x Intel                | 2         | 0.74%   |
| 2 x AMD                  | 1         | 0.37%   |
| 1 x VIA                  | 1         | 0.37%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 233       | 85.66%  |
| Proprietary | 29        | 10.66%  |
| Unknown     | 10        | 3.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 176       | 63.08%  |
| 0.01-0.5   | 35        | 12.54%  |
| 1.01-2.0   | 34        | 12.19%  |
| 3.01-4.0   | 13        | 4.66%   |
| 0.51-1.0   | 12        | 4.3%    |
| 7.01-8.0   | 3         | 1.08%   |
| 5.01-6.0   | 3         | 1.08%   |
| 8.01-16.0  | 2         | 0.72%   |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 40        | 13.79%  |
| BOE                     | 38        | 13.1%   |
| AU Optronics            | 35        | 12.07%  |
| Chimei Innolux          | 34        | 11.72%  |
| LG Display              | 29        | 10%     |
| Samsung Electronics     | 23        | 7.93%   |
| AOC                     | 12        | 4.14%   |
| BenQ                    | 10        | 3.45%   |
| Hewlett-Packard         | 8         | 2.76%   |
| Apple                   | 8         | 2.76%   |
| Chi Mei Optoelectronics | 6         | 2.07%   |
| PANDA                   | 4         | 1.38%   |
| LG Electronics          | 4         | 1.38%   |
| Dell                    | 4         | 1.38%   |
| Acer                    | 4         | 1.38%   |
| LG Philips              | 3         | 1.03%   |
| Valve                   | 2         | 0.69%   |
| Unknown (XXX)           | 2         | 0.69%   |
| Sharp                   | 2         | 0.69%   |
| InnoLux Display         | 2         | 0.69%   |
| InfoVision              | 2         | 0.69%   |
| ASUSTek Computer        | 2         | 0.69%   |
| ViewSonic               | 1         | 0.34%   |
| Toshiba                 | 1         | 0.34%   |
| TCL                     | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| SKY                     | 1         | 0.34%   |
| RTK                     | 1         | 0.34%   |
| Philips                 | 1         | 0.34%   |
| NEC Computers           | 1         | 0.34%   |
| MStar                   | 1         | 0.34%   |
| MSI                     | 1         | 0.34%   |
| Lenovo                  | 1         | 0.34%   |
| KTC                     | 1         | 0.34%   |
| Huion                   | 1         | 0.34%   |
| DTV                     | 1         | 0.34%   |
| DMT                     | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 7         | 2.35%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 4         | 1.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 4         | 1.34%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 4         | 1.34%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 3         | 1.01%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 1.01%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3         | 1.01%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.01%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.67%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 2         | 0.67%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.67%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 2         | 0.67%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2         | 0.67%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 2         | 0.67%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                 | 2         | 0.67%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 2         | 0.67%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 2         | 0.67%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 2         | 0.67%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 2         | 0.67%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.67%   |
| BenQ GL930A BNQ7870 1366x768 410x230mm 18.5-inch                     | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.67%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                | 2         | 0.67%   |
| AOC 2251w AOC2251 1920x1080 477x268mm 21.5-inch                      | 2         | 0.67%   |
| ViewSonic VA2855 SERIES VSCD62F 1920x1080 621x341mm 27.9-inch        | 1         | 0.34%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch             | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 115       | 40.93%  |
| 1920x1080 (FHD)    | 81        | 28.83%  |
| 1600x900 (HD+)     | 19        | 6.76%   |
| 1280x800 (WXGA)    | 11        | 3.91%   |
| 1440x900 (WXGA+)   | 9         | 3.2%    |
| 3840x2160 (4K)     | 7         | 2.49%   |
| 1360x768           | 7         | 2.49%   |
| 2560x1600          | 5         | 1.78%   |
| 1024x768 (XGA)     | 5         | 1.78%   |
| 2560x1440 (QHD)    | 3         | 1.07%   |
| 1280x1024 (SXGA)   | 3         | 1.07%   |
| 1024x600           | 3         | 1.07%   |
| 800x1280           | 2         | 0.71%   |
| 1920x1200 (WUXGA)  | 2         | 0.71%   |
| Unknown            | 2         | 0.71%   |
| 4093x4093          | 1         | 0.36%   |
| 3520x1080          | 1         | 0.36%   |
| 3440x1440          | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2646x1024          | 1         | 0.36%   |
| 1680x1050 (WSXGA+) | 1         | 0.36%   |
| 1600x1200          | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 91        | 31.06%  |
| 13      | 38        | 12.97%  |
| 18      | 32        | 10.92%  |
| 14      | 30        | 10.24%  |
| 19      | 21        | 7.17%   |
| 21      | 12        | 4.1%    |
| 11      | 10        | 3.41%   |
| 23      | 9         | 3.07%   |
| Unknown | 9         | 3.07%   |
| 17      | 7         | 2.39%   |
| 12      | 6         | 2.05%   |
| 24      | 4         | 1.37%   |
| 20      | 4         | 1.37%   |
| 54      | 3         | 1.02%   |
| 10      | 3         | 1.02%   |
| 52      | 2         | 0.68%   |
| 32      | 2         | 0.68%   |
| 31      | 2         | 0.68%   |
| 27      | 2         | 0.68%   |
| 16      | 2         | 0.68%   |
| 7       | 2         | 0.68%   |
| 40      | 1         | 0.34%   |
| 34      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 145       | 50.35%  |
| 401-500     | 62        | 21.53%  |
| 201-300     | 33        | 11.46%  |
| 501-600     | 14        | 4.86%   |
| 351-400     | 11        | 3.82%   |
| Unknown     | 9         | 3.13%   |
| 1001-1500   | 5         | 1.74%   |
| 701-800     | 3         | 1.04%   |
| 601-700     | 3         | 1.04%   |
| 1-100       | 2         | 0.69%   |
| 801-900     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 206       | 80.16%  |
| 16/10   | 29        | 11.28%  |
| Unknown | 9         | 3.5%    |
| 4/3     | 6         | 2.33%   |
| 5/4     | 3         | 1.17%   |
| 0.67    | 2         | 0.78%   |
| 3/2     | 1         | 0.39%   |
| 21/9    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 89        | 30.38%  |
| 81-90          | 58        | 19.8%   |
| 141-150        | 31        | 10.58%  |
| 151-200        | 30        | 10.24%  |
| 201-250        | 20        | 6.83%   |
| 71-80          | 10        | 3.41%   |
| 51-60          | 10        | 3.41%   |
| Unknown        | 9         | 3.07%   |
| 61-70          | 6         | 2.05%   |
| More than 1000 | 5         | 1.71%   |
| 351-500        | 5         | 1.71%   |
| 121-130        | 5         | 1.71%   |
| 41-50          | 3         | 1.02%   |
| 111-120        | 3         | 1.02%   |
| 1-40           | 2         | 0.68%   |
| 301-350        | 2         | 0.68%   |
| 131-140        | 2         | 0.68%   |
| 251-300        | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |
| 91-100         | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 99        | 34.74%  |
| 51-100        | 81        | 28.42%  |
| 121-160       | 73        | 25.61%  |
| 161-240       | 14        | 4.91%   |
| Unknown       | 9         | 3.16%   |
| 1-50          | 7         | 2.46%   |
| More than 240 | 2         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 225       | 82.12%  |
| 2     | 40        | 14.6%   |
| 0     | 7         | 2.55%   |
| 3     | 2         | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 169       | 42.04%  |
| Intel                           | 86        | 21.39%  |
| Qualcomm Atheros                | 65        | 16.17%  |
| Broadcom                        | 27        | 6.72%   |
| TP-Link                         | 8         | 1.99%   |
| Ralink Technology               | 7         | 1.74%   |
| Ralink                          | 6         | 1.49%   |
| Marvell Technology Group        | 5         | 1.24%   |
| Xiaomi                          | 4         | 1%      |
| MediaTek                        | 4         | 1%      |
| Broadcom Limited                | 4         | 1%      |
| Samsung Electronics             | 3         | 0.75%   |
| Qualcomm Atheros Communications | 2         | 0.5%    |
| Nvidia                          | 2         | 0.5%    |
| D-Link System                   | 2         | 0.5%    |
| ASIX Electronics                | 2         | 0.5%    |
| VIA Technologies                | 1         | 0.25%   |
| TRENDnet                        | 1         | 0.25%   |
| OPPO Electronics                | 1         | 0.25%   |
| NetGear                         | 1         | 0.25%   |
| Hewlett-Packard                 | 1         | 0.25%   |
| Arduino SA                      | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 97        | 20.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 39        | 8.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.71%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 1.5%    |
| Intel Wireless 8265 / 8275                                              | 6         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.07%   |
| Intel Wireless 3160                                                     | 5         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 4         | 0.86%   |
| Intel Wireless 7260                                                     | 4         | 0.86%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.86%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 3         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.64%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.64%   |
| Intel Wireless 8260                                                     | 3         | 0.64%   |
| Intel Wireless 7265                                                     | 3         | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.64%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.64%   |
| Intel 82579V Gigabit Network Connection                                 | 3         | 0.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 3         | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 30.4%   |
| Realtek Semiconductor           | 55        | 24.23%  |
| Qualcomm Atheros                | 53        | 23.35%  |
| Broadcom                        | 20        | 8.81%   |
| TP-Link                         | 7         | 3.08%   |
| Ralink Technology               | 7         | 3.08%   |
| Ralink                          | 6         | 2.64%   |
| MediaTek                        | 4         | 1.76%   |
| Qualcomm Atheros Communications | 2         | 0.88%   |
| Broadcom Limited                | 2         | 0.88%   |
| TRENDnet                        | 1         | 0.44%   |
| NetGear                         | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 6.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 6.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 4.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 4.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.49%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 3.06%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.62%   |
| Intel Wireless 3160                                                     | 5         | 2.18%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.75%   |
| Intel Wireless 7260                                                     | 4         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.31%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 3         | 1.31%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.31%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.31%   |
| Intel Wireless 8260                                                     | 3         | 1.31%   |
| Intel Wireless 7265                                                     | 3         | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.31%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.87%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                    | 2         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.87%   |
| Intel Wireless 3165                                                     | 2         | 0.87%   |
| Intel WiFi Link 5100                                                    | 2         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 150       | 64.66%  |
| Intel                    | 30        | 12.93%  |
| Qualcomm Atheros         | 18        | 7.76%   |
| Broadcom                 | 12        | 5.17%   |
| Marvell Technology Group | 5         | 2.16%   |
| Xiaomi                   | 4         | 1.72%   |
| Samsung Electronics      | 2         | 0.86%   |
| Nvidia                   | 2         | 0.86%   |
| D-Link System            | 2         | 0.86%   |
| Broadcom Limited         | 2         | 0.86%   |
| ASIX Electronics         | 2         | 0.86%   |
| VIA Technologies         | 1         | 0.43%   |
| TP-Link                  | 1         | 0.43%   |
| OPPO Electronics         | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97        | 41.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 16.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 1.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.28%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.85%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.85%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.43%   |
| OPPO RMX2027                                                      | 1         | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.43%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 222       | 50%     |
| WiFi     | 218       | 49.1%   |
| Modem    | 4         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 59.93%  |
| Ethernet | 111       | 40.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 147       | 54.65%  |
| 1     | 117       | 43.49%  |
| 0     | 3         | 1.12%   |
| 3     | 2         | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 229       | 83.27%  |
| Yes  | 46        | 16.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 30.77%  |
| Realtek Semiconductor           | 29        | 17.16%  |
| Qualcomm Atheros Communications | 24        | 14.2%   |
| Cambridge Silicon Radio         | 11        | 6.51%   |
| IMC Networks                    | 9         | 5.33%   |
| Foxconn / Hon Hai               | 9         | 5.33%   |
| Lite-On Technology              | 8         | 4.73%   |
| Broadcom                        | 7         | 4.14%   |
| Apple                           | 6         | 3.55%   |
| Toshiba                         | 3         | 1.78%   |
| Ralink Technology               | 2         | 1.18%   |
| Ralink                          | 2         | 1.18%   |
| TP-Link                         | 1         | 0.59%   |
| Realtek                         | 1         | 0.59%   |
| Hewlett-Packard                 | 1         | 0.59%   |
| Foxconn International           | 1         | 0.59%   |
| Dell                            | 1         | 0.59%   |
| D-Link System                   | 1         | 0.59%   |
| Alps Electric                   | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 14.2%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 9.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 8.88%   |
| Realtek Bluetooth Radio                             | 12        | 7.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 6.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 4.73%   |
| Intel AX201 Bluetooth                               | 8         | 4.73%   |
| IMC Networks Bluetooth Radio                        | 6         | 3.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.37%   |
| Intel AX200 Bluetooth                               | 4         | 2.37%   |
| Toshiba Bluetooth Device                            | 3         | 1.78%   |
| Lite-On Bluetooth Device                            | 3         | 1.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.78%   |
| Intel Bluetooth Device                              | 3         | 1.78%   |
| Apple Bluetooth Host Controller                     | 3         | 1.78%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.18%   |
| Lite-On Wireless_Device                             | 2         | 1.18%   |
| Lite-On Bluetooth Radio                             | 2         | 1.18%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 1.18%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.18%   |
| TP-Link UB500 Adapter                               | 1         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.59%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.59%   |
| Realtek Bluetooth Radio                             | 1         | 0.59%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.59%   |
| Ralink CSR BS8510                                   | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.59%   |
| IMC Networks Wireless_Device                        | 1         | 0.59%   |
| IMC Networks Bluetooth Device                       | 1         | 0.59%   |
| IMC Networks BCM20702A0                             | 1         | 0.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.59%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 202       | 64.33%  |
| AMD                 | 69        | 21.97%  |
| Nvidia              | 35        | 11.15%  |
| VIA Technologies    | 1         | 0.32%   |
| Samson Technologies | 1         | 0.32%   |
| GN Netcom           | 1         | 0.32%   |
| Focusrite-Novation  | 1         | 0.32%   |
| Corsair             | 1         | 0.32%   |
| C-Media Electronics | 1         | 0.32%   |
| Audient             | 1         | 0.32%   |
| Apple               | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 7.29%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 7.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 5.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 4.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 3.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 3.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.51%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 2.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.26%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.01%   |
| AMD High Definition Audio Controller                                                              | 8         | 2.01%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.26%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.26%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.75%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 25.99%  |
| SK hynix            | 32        | 18.08%  |
| Kingston            | 28        | 15.82%  |
| Micron Technology   | 16        | 9.04%   |
| Unknown             | 15        | 8.47%   |
| Ramaxel Technology  | 6         | 3.39%   |
| Corsair             | 6         | 3.39%   |
| A-DATA Technology   | 6         | 3.39%   |
| Crucial             | 5         | 2.82%   |
| Avant               | 4         | 2.26%   |
| Nanya Technology    | 3         | 1.69%   |
| Unknown (ABCD)      | 2         | 1.13%   |
| Team                | 1         | 0.56%   |
| PNY                 | 1         | 0.56%   |
| Hikvision           | 1         | 0.56%   |
| Hewlett-Packard     | 1         | 0.56%   |
| GOODRAM             | 1         | 0.56%   |
| Gold Key            | 1         | 0.56%   |
| Elpida              | 1         | 0.56%   |
| Unknown             | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 3.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.04%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.04%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 2         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.04%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.04%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 1.04%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.04%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.04%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 1.04%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 1.04%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR2                                 | 1         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                          | 1         | 0.52%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.52%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 73        | 51.41%  |
| DDR3    | 43        | 30.28%  |
| DDR2    | 8         | 5.63%   |
| LPDDR4  | 7         | 4.93%   |
| SDRAM   | 3         | 2.11%   |
| LPDDR3  | 3         | 2.11%   |
| Unknown | 3         | 2.11%   |
| DDR5    | 1         | 0.7%    |
| DDR     | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 70.42%  |
| DIMM         | 32        | 22.54%  |
| Row Of Chips | 8         | 5.63%   |
| Chip         | 1         | 0.7%    |
| Unknown      | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 56        | 34.36%  |
| 4096  | 55        | 33.74%  |
| 16384 | 24        | 14.72%  |
| 2048  | 19        | 11.66%  |
| 1024  | 7         | 4.29%   |
| 32768 | 2         | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 43        | 26.38%  |
| 1600    | 33        | 20.25%  |
| 3200    | 16        | 9.82%   |
| 1333    | 12        | 7.36%   |
| 2400    | 9         | 5.52%   |
| 3266    | 6         | 3.68%   |
| 2133    | 6         | 3.68%   |
| 1334    | 5         | 3.07%   |
| Unknown | 5         | 3.07%   |
| 667     | 3         | 1.84%   |
| 4199    | 2         | 1.23%   |
| 3733    | 2         | 1.23%   |
| 800     | 2         | 1.23%   |
| 8400    | 1         | 0.61%   |
| 5600    | 1         | 0.61%   |
| 4267    | 1         | 0.61%   |
| 3933    | 1         | 0.61%   |
| 3600    | 1         | 0.61%   |
| 3534    | 1         | 0.61%   |
| 3533    | 1         | 0.61%   |
| 3466    | 1         | 0.61%   |
| 3400    | 1         | 0.61%   |
| 3000    | 1         | 0.61%   |
| 2666    | 1         | 0.61%   |
| 1867    | 1         | 0.61%   |
| 1866    | 1         | 0.61%   |
| 1776    | 1         | 0.61%   |
| 1067    | 1         | 0.61%   |
| 1066    | 1         | 0.61%   |
| 975     | 1         | 0.61%   |
| 933     | 1         | 0.61%   |
| 533     | 1         | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Seiko Epson         | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L3110 Series           | 1         | 20%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| Prolific PL2305 Parallel Port      | 1         | 20%     |
| HP Ink Tank Wireless 410 series    | 1         | 20%     |
| HP Deskjet 2050 J510               | 1         | 20%     |

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
| Chicony Electronics                    | 45        | 24.06%  |
| IMC Networks                           | 25        | 13.37%  |
| Microdia                               | 14        | 7.49%   |
| Realtek Semiconductor                  | 13        | 6.95%   |
| Quanta                                 | 11        | 5.88%   |
| Syntek                                 | 8         | 4.28%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.28%   |
| Suyin                                  | 7         | 3.74%   |
| Sunplus Innovation Technology          | 6         | 3.21%   |
| Lite-On Technology                     | 5         | 2.67%   |
| Apple                                  | 4         | 2.14%   |
| Silicon Motion                         | 3         | 1.6%    |
| Ricoh                                  | 3         | 1.6%    |
| KYE Systems (Mouse Systems)            | 3         | 1.6%    |
| Generalplus Technology                 | 3         | 1.6%    |
| Bison Electronics                      | 3         | 1.6%    |
| Alcor Micro                            | 3         | 1.6%    |
| Pixart Imaging                         | 2         | 1.07%   |
| OmniVision Technologies                | 2         | 1.07%   |
| Luxvisions Innotech Limited            | 2         | 1.07%   |
| Logitech                               | 2         | 1.07%   |
| Acer                                   | 2         | 1.07%   |
| Z-Star Microelectronics                | 1         | 0.53%   |
| Unknown                                | 1         | 0.53%   |
| Sonix Technology                       | 1         | 0.53%   |
| Samsung Electronics                    | 1         | 0.53%   |
| Lenovo                                 | 1         | 0.53%   |
| Jieli Technology                       | 1         | 0.53%   |
| Importek                               | 1         | 0.53%   |
| icSpring                               | 1         | 0.53%   |
| Genesys Logic                          | 1         | 0.53%   |
| GEMBIRD                                | 1         | 0.53%   |
| Foxconn / Hon Hai                      | 1         | 0.53%   |
| Arkmicro Technologies                  | 1         | 0.53%   |
| ALi                                    | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 8         | 4.28%   |
| IMC Networks Integrated Camera                                 | 7         | 3.74%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 3.21%   |
| Chicony Integrated Camera                                      | 6         | 3.21%   |
| Chicony HP Truevision HD                                       | 6         | 3.21%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.14%   |
| Syntek Integrated Camera                                       | 3         | 1.6%    |
| IMC Networks VGA UVC WebCam                                    | 3         | 1.6%    |
| IMC Networks TOSHIBA Web Camera - HD                           | 3         | 1.6%    |
| Chicony TOSHIBA Web Camera - HD                                | 3         | 1.6%    |
| Chicony HD User Facing                                         | 3         | 1.6%    |
| Syntek Lenovo EasyCamera                                       | 2         | 1.07%   |
| Syntek EasyCamera                                              | 2         | 1.07%   |
| Suyin Integrated_Webcam_HD                                     | 2         | 1.07%   |
| Suyin HP Truevision HD                                         | 2         | 1.07%   |
| Suyin HD WebCam                                                | 2         | 1.07%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 1.07%   |
| Realtek Integrated Webcam                                      | 2         | 1.07%   |
| Realtek HP "Truevision HD" laptop camera                       | 2         | 1.07%   |
| Realtek HD WebCam                                              | 2         | 1.07%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 1.07%   |
| Quanta HP Webcam-50                                            | 2         | 1.07%   |
| Quanta HP Webcam                                               | 2         | 1.07%   |
| OmniVision OV2640 Webcam                                       | 2         | 1.07%   |
| Microdia Camera                                                | 2         | 1.07%   |
| Logitech Webcam C270                                           | 2         | 1.07%   |
| Lite-On TOSHIBA Web Camera - HD                                | 2         | 1.07%   |
| Lite-On HP TrueVision HD Camera                                | 2         | 1.07%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 1.07%   |
| Chicony HP Wide Vision HD Camera                               | 2         | 1.07%   |
| Chicony HP TrueVision HD Camera                                | 2         | 1.07%   |
| Chicony HP HD Webcam [Fixed]                                   | 2         | 1.07%   |
| Chicony EasyCamera                                             | 2         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.07%   |
| Acer Integrated Camera                                         | 2         | 1.07%   |
| Z-Star WebCam SCB-0320N                                        | 1         | 0.53%   |
| Unknown HD camera                                              | 1         | 0.53%   |
| Syntek USB Video Device                                        | 1         | 0.53%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.53%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 31.82%  |
| Validity Sensors           | 4         | 18.18%  |
| AuthenTec                  | 4         | 18.18%  |
| Upek                       | 2         | 9.09%   |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES1600                                      | 3         | 13.64%  |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 9.09%   |
| Synaptics  WBDI                                        | 2         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.55%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.55%   |
| Synaptics WBDI                                         | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.55%   |
| Synaptics Fingerprint scanner                          | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.55%   |
| LighTuning Fingerprint Sensor                          | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 2         | 33.33%  |
| Broadcom    | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 199       | 73.16%  |
| 1     | 61        | 22.43%  |
| 2     | 11        | 4.04%   |
| 5     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 22        | 25%     |
| Fingerprint reader       | 22        | 25%     |
| Net/wireless             | 17        | 19.32%  |
| Multimedia controller    | 7         | 7.95%   |
| Chipcard                 | 6         | 6.82%   |
| Sound                    | 3         | 3.41%   |
| Communication controller | 3         | 3.41%   |
| Bluetooth                | 3         | 3.41%   |
| Storage                  | 2         | 2.27%   |
| Camera                   | 2         | 2.27%   |
| Network                  | 1         | 1.14%   |

