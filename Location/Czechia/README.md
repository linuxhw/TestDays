Linux in Czechia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Czechia/Desktop/README.md) and [notebooks](/Location/Czechia/Notebook/README.md).

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

Total: 2430

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | A88XM-A/USB                 | Desktop     | [012f2dccba](https://linux-hardware.org/?probe=012f2dccba) | Dec 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [44170ddf90](https://linux-hardware.org/?probe=44170ddf90) | Nov 29, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [5953c13736](https://linux-hardware.org/?probe=5953c13736) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [aad7343998](https://linux-hardware.org/?probe=aad7343998) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [dad186aa07](https://linux-hardware.org/?probe=dad186aa07) | Nov 24, 2022 |
| HP            | 8750                        | Desktop     | [b1ac308187](https://linux-hardware.org/?probe=b1ac308187) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| HP            | 0AACh                       | Desktop     | [9e37ad4151](https://linux-hardware.org/?probe=9e37ad4151) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| HP            | 82B4                        | Desktop     | [c56604f389](https://linux-hardware.org/?probe=c56604f389) | Nov 21, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1502b216b8](https://linux-hardware.org/?probe=1502b216b8) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [73c9daf454](https://linux-hardware.org/?probe=73c9daf454) | Nov 19, 2022 |
| Dell          | Precision 5510              | Notebook    | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [9ed6d8ee1e](https://linux-hardware.org/?probe=9ed6d8ee1e) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [b8da32bca0](https://linux-hardware.org/?probe=b8da32bca0) | Nov 14, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [48572e207b](https://linux-hardware.org/?probe=48572e207b) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | 872E                        | Mini pc     | [b2e72a139e](https://linux-hardware.org/?probe=b2e72a139e) | Nov 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [9f586bafd4](https://linux-hardware.org/?probe=9f586bafd4) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1d9cb16e2f](https://linux-hardware.org/?probe=1d9cb16e2f) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [96bd39af33](https://linux-hardware.org/?probe=96bd39af33) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1833650d](https://linux-hardware.org/?probe=bd1833650d) | Nov 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| HP            | 3029h                       | Desktop     | [2acf620628](https://linux-hardware.org/?probe=2acf620628) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | Notebook    | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | Notebook    | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f45ab957da](https://linux-hardware.org/?probe=f45ab957da) | Oct 28, 2022 |
| UMAX          | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [46c9e39101](https://linux-hardware.org/?probe=46c9e39101) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [6d3bf37ff3](https://linux-hardware.org/?probe=6d3bf37ff3) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c97e42e738](https://linux-hardware.org/?probe=c97e42e738) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5335a66143](https://linux-hardware.org/?probe=5335a66143) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [a6e072bc6b](https://linux-hardware.org/?probe=a6e072bc6b) | Oct 15, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [6bc730181f](https://linux-hardware.org/?probe=6bc730181f) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [da04425205](https://linux-hardware.org/?probe=da04425205) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [18ac5ede65](https://linux-hardware.org/?probe=18ac5ede65) | Oct 08, 2022 |
| Dell          | Latitude E7250              | Notebook    | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [829a14598f](https://linux-hardware.org/?probe=829a14598f) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | Notebook    | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Dell          | 0D28YY A01                  | Desktop     | [5c85c7623a](https://linux-hardware.org/?probe=5c85c7623a) | Oct 04, 2022 |
| Timi          | A35S                        | Notebook    | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [13f60e066f](https://linux-hardware.org/?probe=13f60e066f) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e3eb4cd95f](https://linux-hardware.org/?probe=e3eb4cd95f) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ff11bc4efb](https://linux-hardware.org/?probe=ff11bc4efb) | Oct 02, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | Notebook    | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | Notebook    | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ea8ea96269](https://linux-hardware.org/?probe=ea8ea96269) | Sep 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ea0ab53cac](https://linux-hardware.org/?probe=ea0ab53cac) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | Notebook    | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [b7f881a109](https://linux-hardware.org/?probe=b7f881a109) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [59e7485a11](https://linux-hardware.org/?probe=59e7485a11) | Sep 19, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [b9693eaf7c](https://linux-hardware.org/?probe=b9693eaf7c) | Sep 17, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [b5a0c6309d](https://linux-hardware.org/?probe=b5a0c6309d) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | Notebook    | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bfd4a6b00a](https://linux-hardware.org/?probe=bfd4a6b00a) | Sep 13, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | Notebook    | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | Notebook    | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [be7516b088](https://linux-hardware.org/?probe=be7516b088) | Sep 10, 2022 |
| Dell          | Latitude 5531               | Notebook    | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | Notebook    | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | Notebook    | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | Notebook    | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [4d1339ef49](https://linux-hardware.org/?probe=4d1339ef49) | Aug 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [fc3200b967](https://linux-hardware.org/?probe=fc3200b967) | Aug 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a01239fd83](https://linux-hardware.org/?probe=a01239fd83) | Aug 29, 2022 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| HP            | 8509                        | Desktop     | [0656e40cba](https://linux-hardware.org/?probe=0656e40cba) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | Notebook    | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | Stream 7 Tablet             | Tablet      | [9d4dabb130](https://linux-hardware.org/?probe=9d4dabb130) | Aug 19, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [acf8952e47](https://linux-hardware.org/?probe=acf8952e47) | Aug 13, 2022 |
| HP            | 805B                        | Desktop     | [188fdd3a56](https://linux-hardware.org/?probe=188fdd3a56) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | Notebook    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [cba7d360f1](https://linux-hardware.org/?probe=cba7d360f1) | Aug 10, 2022 |
| Dell          | Latitude 5421               | Notebook    | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Dell          | Latitude 5531               | Notebook    | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | Desktop     | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [61e317887a](https://linux-hardware.org/?probe=61e317887a) | Aug 07, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [61b30cfde0](https://linux-hardware.org/?probe=61b30cfde0) | Aug 06, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [01430753da](https://linux-hardware.org/?probe=01430753da) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d704ff7364](https://linux-hardware.org/?probe=d704ff7364) | Jul 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| HP            | 1494                        | Desktop     | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [55e2c27aaa](https://linux-hardware.org/?probe=55e2c27aaa) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [e8c6448552](https://linux-hardware.org/?probe=e8c6448552) | Jul 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [2986a26253](https://linux-hardware.org/?probe=2986a26253) | Jul 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [c6888145e7](https://linux-hardware.org/?probe=c6888145e7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | Notebook    | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [02a8803d9a](https://linux-hardware.org/?probe=02a8803d9a) | Jul 07, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Dell          | Latitude 7520               | Notebook    | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | Notebook    | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [38b91d59e7](https://linux-hardware.org/?probe=38b91d59e7) | Jul 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [01fb492b9d](https://linux-hardware.org/?probe=01fb492b9d) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [b4b8457bd9](https://linux-hardware.org/?probe=b4b8457bd9) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [7b07f30b17](https://linux-hardware.org/?probe=7b07f30b17) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| Gigabyte      | Z690 UD                     | Desktop     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | Notebook    | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | Notebook    | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| HP            | 8711                        | Mini pc     | [6ceafddb10](https://linux-hardware.org/?probe=6ceafddb10) | Jun 13, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [bbba4fae4b](https://linux-hardware.org/?probe=bbba4fae4b) | Jun 12, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8b02f3e420](https://linux-hardware.org/?probe=8b02f3e420) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | Notebook    | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [805f88e697](https://linux-hardware.org/?probe=805f88e697) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | Notebook    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | Desktop     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [276f8565dc](https://linux-hardware.org/?probe=276f8565dc) | May 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | Notebook    | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [e7c21e067a](https://linux-hardware.org/?probe=e7c21e067a) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [8ed772fb1d](https://linux-hardware.org/?probe=8ed772fb1d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | Notebook    | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Acer          | Z2621G                      | All in one  | [139c780029](https://linux-hardware.org/?probe=139c780029) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| MSI           | B85M-G43                    | Desktop     | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [77c7c34b9e](https://linux-hardware.org/?probe=77c7c34b9e) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HP            | 22F8                        | Desktop     | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [e8915a5023](https://linux-hardware.org/?probe=e8915a5023) | May 15, 2022 |
| ASUSTek       | X555LB                      | Notebook    | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [5f148de534](https://linux-hardware.org/?probe=5f148de534) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [14905c8ec7](https://linux-hardware.org/?probe=14905c8ec7) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | Notebook    | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [d2deff798c](https://linux-hardware.org/?probe=d2deff798c) | May 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a3e95474a0](https://linux-hardware.org/?probe=a3e95474a0) | May 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [97a95fa1af](https://linux-hardware.org/?probe=97a95fa1af) | May 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [09944d29bf](https://linux-hardware.org/?probe=09944d29bf) | May 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | Notebook    | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f4a6777382](https://linux-hardware.org/?probe=f4a6777382) | Apr 30, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [3b927afe90](https://linux-hardware.org/?probe=3b927afe90) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [97c0bfb76c](https://linux-hardware.org/?probe=97c0bfb76c) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| HP            | 22F8                        | Desktop     | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [ab5986371d](https://linux-hardware.org/?probe=ab5986371d) | Apr 23, 2022 |
| HP            | 22F8                        | Desktop     | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | Notebook    | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | Notebook    | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [68d9ef89c7](https://linux-hardware.org/?probe=68d9ef89c7) | Apr 19, 2022 |
| MSI           | B150 PC MATE                | Desktop     | [34c7fe45bc](https://linux-hardware.org/?probe=34c7fe45bc) | Apr 19, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [497807c732](https://linux-hardware.org/?probe=497807c732) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [874e39c8ef](https://linux-hardware.org/?probe=874e39c8ef) | Apr 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a2b841241d](https://linux-hardware.org/?probe=a2b841241d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| Acer          | Aspire V3-112P              | Notebook    | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [b1944bf89e](https://linux-hardware.org/?probe=b1944bf89e) | Apr 15, 2022 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [19b11d696f](https://linux-hardware.org/?probe=19b11d696f) | Apr 15, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | Notebook    | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Gigabyte      | Z590 VISION D               | Desktop     | [4bde7cc5cd](https://linux-hardware.org/?probe=4bde7cc5cd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8a5920ae1a](https://linux-hardware.org/?probe=8a5920ae1a) | Apr 13, 2022 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [46dc99c237](https://linux-hardware.org/?probe=46dc99c237) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | Desktop     | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c01d51d1f5](https://linux-hardware.org/?probe=c01d51d1f5) | Apr 09, 2022 |
| Acer          | TravelMate 4670             | Notebook    | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| HP            | 1495                        | Desktop     | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Dell          | 0VD5HY A04                  | Desktop     | [8672ef6c18](https://linux-hardware.org/?probe=8672ef6c18) | Apr 07, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [0f8ce13fb9](https://linux-hardware.org/?probe=0f8ce13fb9) | Apr 06, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [046d0eb6c8](https://linux-hardware.org/?probe=046d0eb6c8) | Apr 05, 2022 |
| Acer          | Extensa 5630                | Notebook    | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [d95c37955a](https://linux-hardware.org/?probe=d95c37955a) | Apr 03, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | Notebook    | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Intel         | DG45ID AAE27729-310         | Desktop     | [4a15651672](https://linux-hardware.org/?probe=4a15651672) | Apr 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Dell          | OptiPlex 7010               | Desktop     | [f1167c797e](https://linux-hardware.org/?probe=f1167c797e) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | Notebook    | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [b951c3cc48](https://linux-hardware.org/?probe=b951c3cc48) | Mar 29, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | Notebook    | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | Notebook    | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| Le Cube 1     | Unknown                     | Desktop     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | Notebook    | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | Notebook    | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [4ee969ac04](https://linux-hardware.org/?probe=4ee969ac04) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3193e91c83](https://linux-hardware.org/?probe=3193e91c83) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a5d1f1ec32](https://linux-hardware.org/?probe=a5d1f1ec32) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | Notebook    | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| MSI           | B85M-G43                    | Desktop     | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| MSI           | B85M-E45 2015-08-19         | Desktop     | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9ba6eb4ae](https://linux-hardware.org/?probe=c9ba6eb4ae) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [038e9b79ef](https://linux-hardware.org/?probe=038e9b79ef) | Mar 08, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [ce5f22f97a](https://linux-hardware.org/?probe=ce5f22f97a) | Mar 08, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| Acer          | Extensa 5620                | Notebook    | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [047ff4ad80](https://linux-hardware.org/?probe=047ff4ad80) | Mar 04, 2022 |
| MSI           | B85M-G43                    | Desktop     | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Dell          | Latitude 7520               | Notebook    | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| HP            | 3031h                       | Desktop     | [52a519941d](https://linux-hardware.org/?probe=52a519941d) | Mar 03, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | Notebook    | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| Gigabyte      | G1.Sniper                   | Desktop     | [59b1ae56dd](https://linux-hardware.org/?probe=59b1ae56dd) | Mar 01, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 821D                        | Desktop     | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| ASUSTek       | P8Q67-M DO/TPM              | Desktop     | [ee784c0a7e](https://linux-hardware.org/?probe=ee784c0a7e) | Feb 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| ASRock        | Z370M Pro4                  | Desktop     | [8e08f3846b](https://linux-hardware.org/?probe=8e08f3846b) | Feb 27, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [b2e75d51bb](https://linux-hardware.org/?probe=b2e75d51bb) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [1a4f0d32ab](https://linux-hardware.org/?probe=1a4f0d32ab) | Feb 22, 2022 |
| Gigabyte      | G1.Sniper                   | Desktop     | [615669f693](https://linux-hardware.org/?probe=615669f693) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [de7189b0d4](https://linux-hardware.org/?probe=de7189b0d4) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| MSI           | Boston                      | Desktop     | [0f7a7dd744](https://linux-hardware.org/?probe=0f7a7dd744) | Feb 19, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Google        | Chell                       | Notebook    | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [51dfd147ef](https://linux-hardware.org/?probe=51dfd147ef) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | Notebook    | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [bec0b9ac1e](https://linux-hardware.org/?probe=bec0b9ac1e) | Feb 13, 2022 |
| Google        | Homestar (rev3)             | Soc         | [313894dec8](https://linux-hardware.org/?probe=313894dec8) | Feb 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b5dd380b9a](https://linux-hardware.org/?probe=b5dd380b9a) | Feb 10, 2022 |
| Dell          | Latitude 5480               | Notebook    | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| HP            | 18E7                        | Desktop     | [11c3f1c67f](https://linux-hardware.org/?probe=11c3f1c67f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Google        | Homestar (rev3)             | Soc         | [58d09ccbf3](https://linux-hardware.org/?probe=58d09ccbf3) | Feb 04, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4aece000f1](https://linux-hardware.org/?probe=4aece000f1) | Feb 03, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [4cf4045deb](https://linux-hardware.org/?probe=4cf4045deb) | Feb 01, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | Notebook    | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [182ad67187](https://linux-hardware.org/?probe=182ad67187) | Feb 01, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [6afebcc975](https://linux-hardware.org/?probe=6afebcc975) | Feb 01, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [8fba4698c9](https://linux-hardware.org/?probe=8fba4698c9) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | Notebook    | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | Notebook    | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [dcc55138d2](https://linux-hardware.org/?probe=dcc55138d2) | Jan 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | Notebook    | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0977601aad](https://linux-hardware.org/?probe=0977601aad) | Jan 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | Notebook    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | Notebook    | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | Notebook    | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [a920db9f29](https://linux-hardware.org/?probe=a920db9f29) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | Notebook    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | Notebook    | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | Notebook    | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | Notebook    | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | Notebook    | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | Notebook    | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [c0039193bb](https://linux-hardware.org/?probe=c0039193bb) | Jan 09, 2022 |
| HP            | 18E7                        | Desktop     | [2598720ae1](https://linux-hardware.org/?probe=2598720ae1) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b4f5f6f8da](https://linux-hardware.org/?probe=b4f5f6f8da) | Jan 08, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | Notebook    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | Notebook    | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | Desktop     | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5107953369](https://linux-hardware.org/?probe=5107953369) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | Notebook    | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | Notebook    | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | Notebook    | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [c5c108c138](https://linux-hardware.org/?probe=c5c108c138) | Jan 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | Notebook    | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [5d1e83c959](https://linux-hardware.org/?probe=5d1e83c959) | Jan 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| HP            | 18E7                        | Desktop     | [8fe0391d59](https://linux-hardware.org/?probe=8fe0391d59) | Dec 28, 2021 |
| HP            | ProLiant DL380e Gen8        | Server      | [a28b637049](https://linux-hardware.org/?probe=a28b637049) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | Notebook    | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| HP            | 872E                        | Mini pc     | [84eb03ce6d](https://linux-hardware.org/?probe=84eb03ce6d) | Dec 25, 2021 |
| HP            | 872E                        | Mini pc     | [c2eff247c6](https://linux-hardware.org/?probe=c2eff247c6) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| HP            | 1905                        | Desktop     | [9e2637fa00](https://linux-hardware.org/?probe=9e2637fa00) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [180954acf2](https://linux-hardware.org/?probe=180954acf2) | Dec 23, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| Dell          | Latitude 5400               | Notebook    | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| UMAX          | VisionBook 10Wi-S 64G       | Tablet      | [5143e2a3fe](https://linux-hardware.org/?probe=5143e2a3fe) | Dec 18, 2021 |
| Dell          | 0478VN A00                  | Desktop     | [67955910cb](https://linux-hardware.org/?probe=67955910cb) | Dec 18, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | Notebook    | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | Notebook    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [86aff395eb](https://linux-hardware.org/?probe=86aff395eb) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6b3727344c](https://linux-hardware.org/?probe=6b3727344c) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | Notebook    | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [efb6380716](https://linux-hardware.org/?probe=efb6380716) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | Notebook    | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| Acer          | Extensa 5220                | Notebook    | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | Notebook    | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [e96b1f7f6b](https://linux-hardware.org/?probe=e96b1f7f6b) | Dec 07, 2021 |
| Dell          | 0PTTT9 A01                  | Desktop     | [fb7c5092e9](https://linux-hardware.org/?probe=fb7c5092e9) | Dec 07, 2021 |
| HP            | 1905                        | Desktop     | [e16a65e786](https://linux-hardware.org/?probe=e16a65e786) | Dec 06, 2021 |
| HP            | 1905                        | Desktop     | [d58c2f29a4](https://linux-hardware.org/?probe=d58c2f29a4) | Dec 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [63319937d0](https://linux-hardware.org/?probe=63319937d0) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | Notebook    | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | Notebook    | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [24800d20ac](https://linux-hardware.org/?probe=24800d20ac) | Dec 01, 2021 |
| Google        | Akemi                       | Notebook    | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | Notebook    | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | Notebook    | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | Notebook    | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | Notebook    | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| EVGA          | 142-SS-E178                 | Desktop     | [8ad978bbf2](https://linux-hardware.org/?probe=8ad978bbf2) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | Desktop     | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d6e422cfc](https://linux-hardware.org/?probe=6d6e422cfc) | Nov 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [021a54d6d2](https://linux-hardware.org/?probe=021a54d6d2) | Nov 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [5edbaed472](https://linux-hardware.org/?probe=5edbaed472) | Nov 18, 2021 |
| Supermicro    | X10SLL-F                    | Server      | [f9e64483fd](https://linux-hardware.org/?probe=f9e64483fd) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | Notebook    | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [19a21ae965](https://linux-hardware.org/?probe=19a21ae965) | Nov 17, 2021 |
| Biostar       | TH67B                       | Desktop     | [5d655fd2bd](https://linux-hardware.org/?probe=5d655fd2bd) | Nov 17, 2021 |
| HP            | ProBook 4510s               | Notebook    | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| MSI           | A88X-G43                    | Desktop     | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | Desktop     | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| ASUSTek       | P5KPL                       | Desktop     | [6e52b269ee](https://linux-hardware.org/?probe=6e52b269ee) | Nov 15, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [89c5a1af70](https://linux-hardware.org/?probe=89c5a1af70) | Nov 15, 2021 |
| Dell          | Latitude E6420              | Notebook    | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6bc1b40b7](https://linux-hardware.org/?probe=b6bc1b40b7) | Nov 14, 2021 |
| Seeed Stud... | ODYSSEY-TGL-A               | Desktop     | [b05c5533b0](https://linux-hardware.org/?probe=b05c5533b0) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| HP            | 1998                        | Desktop     | [2e830badd5](https://linux-hardware.org/?probe=2e830badd5) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| MSI           | 970A-G43                    | Desktop     | [da61ca8b52](https://linux-hardware.org/?probe=da61ca8b52) | Nov 13, 2021 |
| MSI           | 970A-G43                    | Desktop     | [d27f131cce](https://linux-hardware.org/?probe=d27f131cce) | Nov 13, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [59ca43cb01](https://linux-hardware.org/?probe=59ca43cb01) | Nov 12, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [0f4ebd720e](https://linux-hardware.org/?probe=0f4ebd720e) | Nov 11, 2021 |
| Dell          | Latitude E5440              | Notebook    | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | Notebook    | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [2af76d7459](https://linux-hardware.org/?probe=2af76d7459) | Nov 09, 2021 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [ecf35bff43](https://linux-hardware.org/?probe=ecf35bff43) | Nov 09, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| HP            | 1998                        | Desktop     | [c2ab98c42f](https://linux-hardware.org/?probe=c2ab98c42f) | Nov 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [68d7274a99](https://linux-hardware.org/?probe=68d7274a99) | Nov 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [12800ce664](https://linux-hardware.org/?probe=12800ce664) | Nov 06, 2021 |
| HP            | Pavilion dv6                | Notebook    | [9b00744856](https://linux-hardware.org/?probe=9b00744856) | Nov 06, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [1ae65e25ca](https://linux-hardware.org/?probe=1ae65e25ca) | Nov 06, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [3cea241e9d](https://linux-hardware.org/?probe=3cea241e9d) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | Notebook    | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [510bf1ba13](https://linux-hardware.org/?probe=510bf1ba13) | Nov 03, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [7295833004](https://linux-hardware.org/?probe=7295833004) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| MSI           | GE76 Raider 11UG            | Notebook    | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Purism        | librem_15v4                 | Notebook    | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | Notebook    | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [7a2e7c66e9](https://linux-hardware.org/?probe=7a2e7c66e9) | Oct 31, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eadbbabab0](https://linux-hardware.org/?probe=eadbbabab0) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| Dell          | Latitude E7240              | Notebook    | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | Notebook    | [3678e02e46](https://linux-hardware.org/?probe=3678e02e46) | Oct 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | Notebook    | [5a44640ff8](https://linux-hardware.org/?probe=5a44640ff8) | Oct 27, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Sony          | VPCZ13M9E                   | Notebook    | [2d1739dc58](https://linux-hardware.org/?probe=2d1739dc58) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Alienware     | 15                          | Notebook    | [5a84b0e8e8](https://linux-hardware.org/?probe=5a84b0e8e8) | Oct 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Acer          | Aspire E5-721               | Notebook    | [0b2ec748f2](https://linux-hardware.org/?probe=0b2ec748f2) | Oct 23, 2021 |
| Acer          | Aspire E5-721               | Notebook    | [46ae1c3c30](https://linux-hardware.org/?probe=46ae1c3c30) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | Notebook    | [d727cf6e00](https://linux-hardware.org/?probe=d727cf6e00) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | Notebook    | [6ccc652e28](https://linux-hardware.org/?probe=6ccc652e28) | Oct 22, 2021 |
| Alienware     | 15                          | Notebook    | [8c4eaaa333](https://linux-hardware.org/?probe=8c4eaaa333) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Dell          | Latitude 5400               | Notebook    | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | Notebook    | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f60949a3cc](https://linux-hardware.org/?probe=f60949a3cc) | Oct 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9f21330313](https://linux-hardware.org/?probe=9f21330313) | Oct 18, 2021 |
| Sony          | VPCEB1E1E                   | Notebook    | [1473b3d2ca](https://linux-hardware.org/?probe=1473b3d2ca) | Oct 18, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Dell          | Latitude E5420              | Notebook    | [a1027f938f](https://linux-hardware.org/?probe=a1027f938f) | Oct 16, 2021 |
| Medion        | E7218                       | Notebook    | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d890edb314](https://linux-hardware.org/?probe=d890edb314) | Oct 16, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [ae854c2ff2](https://linux-hardware.org/?probe=ae854c2ff2) | Oct 16, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| MSI           | MS-7309                     | Desktop     | [33faf5dbef](https://linux-hardware.org/?probe=33faf5dbef) | Oct 14, 2021 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [878347dd71](https://linux-hardware.org/?probe=878347dd71) | Oct 13, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [2269836aab](https://linux-hardware.org/?probe=2269836aab) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| MSI           | MS-7309                     | Desktop     | [b0ddfaaa86](https://linux-hardware.org/?probe=b0ddfaaa86) | Oct 12, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [928665d302](https://linux-hardware.org/?probe=928665d302) | Oct 12, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [b624e54271](https://linux-hardware.org/?probe=b624e54271) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Lenovo        | ThinkPad T570 20H90000MC    | Notebook    | [51c709d90c](https://linux-hardware.org/?probe=51c709d90c) | Oct 09, 2021 |
| UMAX          | J42 Nano                    | Desktop     | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5174e188c0](https://linux-hardware.org/?probe=5174e188c0) | Oct 09, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [81c36c3a21](https://linux-hardware.org/?probe=81c36c3a21) | Oct 09, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b3a9a2c025](https://linux-hardware.org/?probe=b3a9a2c025) | Oct 08, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [13444fc399](https://linux-hardware.org/?probe=13444fc399) | Oct 08, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [7034e6708d](https://linux-hardware.org/?probe=7034e6708d) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | Notebook    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3cab016500](https://linux-hardware.org/?probe=3cab016500) | Oct 06, 2021 |
| ASUSTek       | ET2010AG                    | All in one  | [86cd4a72d1](https://linux-hardware.org/?probe=86cd4a72d1) | Oct 05, 2021 |
| ASUSTek       | ET2010AG                    | All in one  | [a96edf35cd](https://linux-hardware.org/?probe=a96edf35cd) | Oct 05, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [2615e61a63](https://linux-hardware.org/?probe=2615e61a63) | Oct 05, 2021 |
| Acer          | Aspire M1930                | Desktop     | [0f21c5864a](https://linux-hardware.org/?probe=0f21c5864a) | Oct 05, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [f6518ea548](https://linux-hardware.org/?probe=f6518ea548) | Oct 04, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [43115b1585](https://linux-hardware.org/?probe=43115b1585) | Oct 04, 2021 |
| HP            | 3047h                       | Desktop     | [15f4144ba7](https://linux-hardware.org/?probe=15f4144ba7) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [38422d16b5](https://linux-hardware.org/?probe=38422d16b5) | Oct 02, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [21453a290c](https://linux-hardware.org/?probe=21453a290c) | Oct 02, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [26fb963760](https://linux-hardware.org/?probe=26fb963760) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [7f17ddd3af](https://linux-hardware.org/?probe=7f17ddd3af) | Sep 30, 2021 |
| Acer          | Extensa 5235                | Notebook    | [aadc334520](https://linux-hardware.org/?probe=aadc334520) | Sep 29, 2021 |
| MSI           | GL72 6QD                    | Notebook    | [4a25280ba6](https://linux-hardware.org/?probe=4a25280ba6) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [7e82dd3e6d](https://linux-hardware.org/?probe=7e82dd3e6d) | Sep 25, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [f64736711c](https://linux-hardware.org/?probe=f64736711c) | Sep 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [b39008d274](https://linux-hardware.org/?probe=b39008d274) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [0f57a946c9](https://linux-hardware.org/?probe=0f57a946c9) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [5422161d82](https://linux-hardware.org/?probe=5422161d82) | Sep 21, 2021 |
| Lenovo        | C200 10040                  | All in one  | [0c9232361d](https://linux-hardware.org/?probe=0c9232361d) | Sep 21, 2021 |
| HP            | 255 G4                      | Notebook    | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| Toshiba       | Satellite C850-19P          | Notebook    | [be0e0fc39c](https://linux-hardware.org/?probe=be0e0fc39c) | Sep 19, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [4dae78bc6e](https://linux-hardware.org/?probe=4dae78bc6e) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Lenovo        | B51-80 80LM                 | Notebook    | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [507fbfc464](https://linux-hardware.org/?probe=507fbfc464) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [8bd0f5b675](https://linux-hardware.org/?probe=8bd0f5b675) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [e044b5770b](https://linux-hardware.org/?probe=e044b5770b) | Sep 15, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [61c16353ce](https://linux-hardware.org/?probe=61c16353ce) | Sep 14, 2021 |
| Intel         | S2600WFT H48104-850         | Server      | [36c4acac2d](https://linux-hardware.org/?probe=36c4acac2d) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [49a26a21af](https://linux-hardware.org/?probe=49a26a21af) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | UX303LA                     | Notebook    | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [5ef10e99fc](https://linux-hardware.org/?probe=5ef10e99fc) | Sep 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d069d8c301](https://linux-hardware.org/?probe=d069d8c301) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [4078ccd6f6](https://linux-hardware.org/?probe=4078ccd6f6) | Sep 08, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [fb3c4b683c](https://linux-hardware.org/?probe=fb3c4b683c) | Sep 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [75e4394ca1](https://linux-hardware.org/?probe=75e4394ca1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [7d28c4a737](https://linux-hardware.org/?probe=7d28c4a737) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [c33f77f320](https://linux-hardware.org/?probe=c33f77f320) | Sep 07, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [9e43cd58cd](https://linux-hardware.org/?probe=9e43cd58cd) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6db0aec69b](https://linux-hardware.org/?probe=6db0aec69b) | Sep 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [eb43b257f2](https://linux-hardware.org/?probe=eb43b257f2) | Sep 05, 2021 |
| Acer          | Spin SP111-33               | Convertible | [2a5ddf7be8](https://linux-hardware.org/?probe=2a5ddf7be8) | Sep 05, 2021 |
| ASUSTek       | P5KPL                       | Desktop     | [5abf2f2b22](https://linux-hardware.org/?probe=5abf2f2b22) | Sep 05, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d0d9c89285](https://linux-hardware.org/?probe=d0d9c89285) | Sep 04, 2021 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e9741b1baf](https://linux-hardware.org/?probe=e9741b1baf) | Sep 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [c31af0c00d](https://linux-hardware.org/?probe=c31af0c00d) | Sep 02, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7f23204904](https://linux-hardware.org/?probe=7f23204904) | Sep 02, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| MSI           | GP72MVR 7RFX                | Notebook    | [8bf96cd534](https://linux-hardware.org/?probe=8bf96cd534) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [9ac57ec075](https://linux-hardware.org/?probe=9ac57ec075) | Aug 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [47c81ea7a3](https://linux-hardware.org/?probe=47c81ea7a3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d744798f8c](https://linux-hardware.org/?probe=d744798f8c) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| HP            | Pavilion dv7                | Notebook    | [89e7202467](https://linux-hardware.org/?probe=89e7202467) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [2a6bfff91f](https://linux-hardware.org/?probe=2a6bfff91f) | Aug 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Supermicro    | X10DRi                      | Server      | [c04f902b93](https://linux-hardware.org/?probe=c04f902b93) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7e6371d41f](https://linux-hardware.org/?probe=7e6371d41f) | Aug 22, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a253cd3e21](https://linux-hardware.org/?probe=a253cd3e21) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Dell          | Latitude 7320               | Notebook    | [33536a85d3](https://linux-hardware.org/?probe=33536a85d3) | Aug 19, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [7306b98101](https://linux-hardware.org/?probe=7306b98101) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| Lenovo        | 3176 NOK                    | Desktop     | [ed11430a97](https://linux-hardware.org/?probe=ed11430a97) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |
| ASRock        | B460M-ITX/ac                | Desktop     | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Dell          | 02YYK5 A00                  | Desktop     | [2918bafc50](https://linux-hardware.org/?probe=2918bafc50) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [7b007be9fd](https://linux-hardware.org/?probe=7b007be9fd) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [f9243be85f](https://linux-hardware.org/?probe=f9243be85f) | Aug 16, 2021 |
| Acer          | Extensa 5630                | Notebook    | [29a71214dd](https://linux-hardware.org/?probe=29a71214dd) | Aug 15, 2021 |
| AMI           | Intel                       | Convertible | [c96146f531](https://linux-hardware.org/?probe=c96146f531) | Aug 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [465b8fec82](https://linux-hardware.org/?probe=465b8fec82) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [80cfc9b687](https://linux-hardware.org/?probe=80cfc9b687) | Aug 12, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [5e65f099db](https://linux-hardware.org/?probe=5e65f099db) | Aug 12, 2021 |
| Acer          | Extensa 5630                | Notebook    | [43a2f7646a](https://linux-hardware.org/?probe=43a2f7646a) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASUSTek       | X553SA                      | Notebook    | [58875de3c3](https://linux-hardware.org/?probe=58875de3c3) | Aug 12, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [4651e027d9](https://linux-hardware.org/?probe=4651e027d9) | Aug 11, 2021 |
| Dell          | Latitude 5400               | Notebook    | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [28897c5b5f](https://linux-hardware.org/?probe=28897c5b5f) | Aug 09, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a52650a605](https://linux-hardware.org/?probe=a52650a605) | Aug 09, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [17e8358196](https://linux-hardware.org/?probe=17e8358196) | Aug 08, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [5c64722433](https://linux-hardware.org/?probe=5c64722433) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [88c691e7f1](https://linux-hardware.org/?probe=88c691e7f1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [32c82c54b5](https://linux-hardware.org/?probe=32c82c54b5) | Aug 06, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [983611f01f](https://linux-hardware.org/?probe=983611f01f) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [5e399cedc5](https://linux-hardware.org/?probe=5e399cedc5) | Aug 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 243       | 13.64%  |
| Ubuntu 18.04                 | 151       | 8.48%   |
| OpenMandriva 4.2             | 115       | 6.46%   |
| OpenMandriva 4.50            | 62        | 3.48%   |
| Ubuntu 22.04                 | 58        | 3.26%   |
| OpenMandriva 4.3             | 52        | 2.92%   |
| Ubuntu 21.10                 | 38        | 2.13%   |
| Ubuntu 20.10                 | 35        | 1.97%   |
| Fedora 34                    | 35        | 1.97%   |
| Ubuntu 19.10                 | 28        | 1.57%   |
| Linux Mint 20.1              | 28        | 1.57%   |
| Debian 11                    | 28        | 1.57%   |
| Ubuntu 21.04                 | 27        | 1.52%   |
| Arch                         | 27        | 1.52%   |
| Linux Mint 20                | 26        | 1.46%   |
| Fedora 35                    | 26        | 1.46%   |
| Fedora 32                    | 25        | 1.4%    |
| Ubuntu 19.04                 | 24        | 1.35%   |
| Linux Mint 20.2              | 24        | 1.35%   |
| Fedora 33                    | 23        | 1.29%   |
| Zorin 16                     | 22        | 1.24%   |
| Linux Mint 19.3              | 22        | 1.24%   |
| Arch Rolling                 | 22        | 1.24%   |
| Linux Mint 20.3              | 20        | 1.12%   |
| Zorin 15                     | 18        | 1.01%   |
| Fedora 31                    | 18        | 1.01%   |
| Kubuntu 20.04                | 17        | 0.95%   |
| Fedora 36                    | 17        | 0.95%   |
| Xubuntu 20.04                | 15        | 0.84%   |
| Pop!_OS 20.04                | 15        | 0.84%   |
| Linux Mint 21                | 15        | 0.84%   |
| Xubuntu 18.04                | 14        | 0.79%   |
| openSUSE Tumbleweed-XXXXXXXX | 14        | 0.79%   |
| Debian 10                    | 14        | 0.79%   |
| Manjaro                      | 13        | 0.73%   |
| KDE neon 20.04               | 13        | 0.73%   |
| Ubuntu 18.10                 | 11        | 0.62%   |
| RHEL 8                       | 11        | 0.62%   |
| Gentoo 2.6                   | 10        | 0.56%   |
| Ubuntu 16.04                 | 9         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 591       | 35.12%  |
| OpenMandriva  | 233       | 13.84%  |
| Fedora        | 149       | 8.85%   |
| Linux Mint    | 143       | 8.5%    |
| Debian        | 52        | 3.09%   |
| Arch          | 49        | 2.91%   |
| Manjaro       | 46        | 2.73%   |
| Zorin         | 44        | 2.61%   |
| Xubuntu       | 40        | 2.38%   |
| ROSA          | 35        | 2.08%   |
| Pop!_OS       | 35        | 2.08%   |
| Kubuntu       | 34        | 2.02%   |
| Gentoo        | 22        | 1.31%   |
| openSUSE      | 19        | 1.13%   |
| KDE neon      | 17        | 1.01%   |
| Lubuntu       | 16        | 0.95%   |
| RHEL          | 13        | 0.77%   |
| Endless       | 13        | 0.77%   |
| Ubuntu MATE   | 11        | 0.65%   |
| Kali          | 11        | 0.65%   |
| Elementary    | 11        | 0.65%   |
| Ubuntu Unity  | 9         | 0.53%   |
| CentOS        | 9         | 0.53%   |
| ArcoLinux     | 9         | 0.53%   |
| Void Linux    | 6         | 0.36%   |
| Parrot        | 5         | 0.3%    |
| EndeavourOS   | 5         | 0.3%    |
| ACI           | 5         | 0.3%    |
| Rocky Linux   | 4         | 0.24%   |
| LMDE          | 4         | 0.24%   |
| BlackPanther  | 4         | 0.24%   |
| SteamOS       | 3         | 0.18%   |
| MX            | 3         | 0.18%   |
| LinuxFX       | 3         | 0.18%   |
| Nobara        | 2         | 0.12%   |
| NixOS         | 2         | 0.12%   |
| Artix         | 2         | 0.12%   |
| Ubuntu Budgie | 1         | 0.06%   |
| SystemRescue  | 1         | 0.06%   |
| Sparky        | 1         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 113       | 5.78%   |
| 5.16.7-desktop-1omv4003  | 52        | 2.66%   |
| 5.14.7-desktop-1omv4050  | 52        | 2.66%   |
| 5.4.0-42-generic         | 34        | 1.74%   |
| 5.4.0-58-generic         | 22        | 1.12%   |
| 5.4.0-52-generic         | 22        | 1.12%   |
| 5.15.0-46-generic        | 21        | 1.07%   |
| 5.4.0-26-generic         | 20        | 1.02%   |
| 5.15.0-52-generic        | 16        | 0.82%   |
| 5.11.0-27-generic        | 16        | 0.82%   |
| 5.3.0-40-generic         | 15        | 0.77%   |
| 5.0.0-37-generic         | 15        | 0.77%   |
| 5.13.0-30-generic        | 14        | 0.72%   |
| 5.4.0-48-generic         | 12        | 0.61%   |
| 5.4.0-40-generic         | 12        | 0.61%   |
| 5.3.0-28-generic         | 12        | 0.61%   |
| 5.15.0-48-generic        | 12        | 0.61%   |
| 5.4.0-65-generic         | 11        | 0.56%   |
| 5.4.0-29-generic         | 10        | 0.51%   |
| 5.11.0-37-generic        | 10        | 0.51%   |
| 5.8.0-53-generic         | 9         | 0.46%   |
| 5.4.0-91-generic         | 9         | 0.46%   |
| 5.4.0-37-generic         | 9         | 0.46%   |
| 5.10.0-8-amd64           | 9         | 0.46%   |
| 4.15.0-43-generic        | 9         | 0.46%   |
| 5.8.0-59-generic         | 8         | 0.41%   |
| 5.8.0-50-generic         | 8         | 0.41%   |
| 5.4.0-72-generic         | 8         | 0.41%   |
| 5.4.0-56-generic         | 8         | 0.41%   |
| 5.4.0-33-generic         | 8         | 0.41%   |
| 5.3.0-42-generic         | 8         | 0.41%   |
| 5.15.0-41-generic        | 8         | 0.41%   |
| 5.13.0-22-generic        | 8         | 0.41%   |
| 5.13.0-21-generic        | 8         | 0.41%   |
| 5.0.0-32-generic         | 8         | 0.41%   |
| 5.0.0-31-generic         | 8         | 0.41%   |
| 5.0.0-29-generic         | 8         | 0.41%   |
| 5.0.0-25-generic         | 8         | 0.41%   |
| 4.18.0-10-generic        | 8         | 0.41%   |
| 5.8.0-48-generic         | 7         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 303       | 16.64%  |
| 5.10.14 | 113       | 6.21%   |
| 4.15.0  | 109       | 5.99%   |
| 5.8.0   | 101       | 5.55%   |
| 5.15.0  | 98        | 5.38%   |
| 5.11.0  | 96        | 5.27%   |
| 5.3.0   | 92        | 5.05%   |
| 5.13.0  | 90        | 4.94%   |
| 5.0.0   | 71        | 3.9%    |
| 4.18.0  | 57        | 3.13%   |
| 5.16.7  | 53        | 2.91%   |
| 5.14.7  | 53        | 2.91%   |
| 5.10.0  | 35        | 1.92%   |
| 4.19.0  | 17        | 0.93%   |
| 3.10.0  | 11        | 0.6%    |
| 5.19.0  | 10        | 0.55%   |
| 4.9.20  | 9         | 0.49%   |
| 5.16.11 | 8         | 0.44%   |
| 5.15.12 | 7         | 0.38%   |
| 5.11.12 | 7         | 0.38%   |
| 5.9.16  | 6         | 0.33%   |
| 5.9.0   | 6         | 0.33%   |
| 5.14.0  | 6         | 0.33%   |
| 5.12.4  | 6         | 0.33%   |
| 5.10.74 | 6         | 0.33%   |
| 4.4.0   | 6         | 0.33%   |
| 4.13.0  | 6         | 0.33%   |
| 5.8.18  | 5         | 0.27%   |
| 5.18.12 | 5         | 0.27%   |
| 5.17.5  | 5         | 0.27%   |
| 5.14.10 | 5         | 0.27%   |
| 5.7.0   | 4         | 0.22%   |
| 5.6.6   | 4         | 0.22%   |
| 5.6.16  | 4         | 0.22%   |
| 5.6.0   | 4         | 0.22%   |
| 5.3.18  | 4         | 0.22%   |
| 5.17.1  | 4         | 0.22%   |
| 5.17.0  | 4         | 0.22%   |
| 5.16.0  | 4         | 0.22%   |
| 5.13.4  | 4         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 327       | 18.07%  |
| 5.10    | 189       | 10.44%  |
| 5.15    | 139       | 7.68%   |
| 5.8     | 134       | 7.4%    |
| 5.11    | 129       | 7.13%   |
| 4.15    | 111       | 6.13%   |
| 5.13    | 107       | 5.91%   |
| 5.3     | 103       | 5.69%   |
| 5.16    | 82        | 4.53%   |
| 5.14    | 78        | 4.31%   |
| 5.0     | 77        | 4.25%   |
| 4.18    | 60        | 3.31%   |
| 5.19    | 32        | 1.77%   |
| 5.17    | 30        | 1.66%   |
| 5.9     | 25        | 1.38%   |
| 5.6     | 23        | 1.27%   |
| 5.18    | 22        | 1.22%   |
| 4.19    | 22        | 1.22%   |
| 5.12    | 21        | 1.16%   |
| 4.9     | 20        | 1.1%    |
| 5.7     | 14        | 0.77%   |
| 3.10    | 12        | 0.66%   |
| 6.0     | 11        | 0.61%   |
| 5.5     | 11        | 0.61%   |
| 4.4     | 6         | 0.33%   |
| 4.13    | 6         | 0.33%   |
| 5.1     | 4         | 0.22%   |
| 5.2     | 3         | 0.17%   |
| 4.17    | 3         | 0.17%   |
| 4.14    | 3         | 0.17%   |
| 4.1     | 2         | 0.11%   |
| 4.8     | 1         | 0.06%   |
| 4.20    | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 2.6     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1585      | 95.89%  |
| i686    | 56        | 3.39%   |
| aarch64 | 10        | 0.6%    |
| armv8l  | 1         | 0.06%   |
| armv7l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 677       | 39.59%  |
| KDE5              | 365       | 21.35%  |
| Unknown           | 251       | 14.68%  |
| XFCE              | 121       | 7.08%   |
| X-Cinnamon        | 83        | 4.85%   |
| KDE               | 46        | 2.69%   |
| MATE              | 40        | 2.34%   |
| Cinnamon          | 31        | 1.81%   |
| LXQt              | 13        | 0.76%   |
| KDE4              | 13        | 0.76%   |
| Pantheon          | 11        | 0.64%   |
| Unity             | 10        | 0.58%   |
| LXDE              | 9         | 0.53%   |
| GNOME Flashback   | 9         | 0.53%   |
| openbox           | 5         | 0.29%   |
| i3                | 5         | 0.29%   |
| awesome           | 4         | 0.23%   |
| qtile             | 3         | 0.18%   |
| Budgie            | 3         | 0.18%   |
| sway              | 2         | 0.12%   |
| Yaru:ubuntu:GNOME | 1         | 0.06%   |
| XSession          | 1         | 0.06%   |
| xinitrc           | 1         | 0.06%   |
| GNUstep           | 1         | 0.06%   |
| GNOME Classic     | 1         | 0.06%   |
| Enlightenment     | 1         | 0.06%   |
| DWM               | 1         | 0.06%   |
| custom            | 1         | 0.06%   |
| Core              | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1309      | 77.27%  |
| Wayland | 226       | 13.34%  |
| Unknown | 136       | 8.03%   |
| Tty     | 23        | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 834       | 48.77%  |
| SDDM    | 350       | 20.47%  |
| GDM     | 195       | 11.4%   |
| GDM3    | 127       | 7.43%   |
| LightDM | 112       | 6.55%   |
| TDM     | 71        | 4.15%   |
| KDM     | 12        | 0.7%    |
| XDM     | 4         | 0.23%   |
| LXDM    | 2         | 0.12%   |
| SLiM    | 1         | 0.06%   |
| Ly      | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| cs_CZ   | 871       | 51.66%  |
| en_US   | 476       | 28.23%  |
| Unknown | 225       | 13.35%  |
| en_GB   | 39        | 2.31%   |
| C       | 27        | 1.6%    |
| ru_RU   | 16        | 0.95%   |
| sk_SK   | 8         | 0.47%   |
| POSIX   | 4         | 0.24%   |
| pl_PL   | 3         | 0.18%   |
| it_IT   | 3         | 0.18%   |
| fr_FR   | 2         | 0.12%   |
| de_DE   | 2         | 0.12%   |
| uk_UA   | 1         | 0.06%   |
| ro_RO   | 1         | 0.06%   |
| pt_PT   | 1         | 0.06%   |
| fi_FI   | 1         | 0.06%   |
| es_ES   | 1         | 0.06%   |
| en_NG   | 1         | 0.06%   |
| en_CA   | 1         | 0.06%   |
| en_AU   | 1         | 0.06%   |
| en_150  | 1         | 0.06%   |
| el_GR   | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 928       | 54.91%  |
| EFI  | 762       | 45.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1162      | 69%     |
| Overlay  | 255       | 15.14%  |
| Btrfs    | 133       | 7.9%    |
| Unknown  | 64        | 3.8%    |
| Xfs      | 45        | 2.67%   |
| Zfs      | 9         | 0.53%   |
| Ext3     | 4         | 0.24%   |
| Ext2     | 4         | 0.24%   |
| Tmpfs    | 2         | 0.12%   |
| Reiserfs | 2         | 0.12%   |
| F2fs     | 2         | 0.12%   |
| Aufs     | 2         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 877       | 52.2%   |
| GPT     | 517       | 30.77%  |
| MBR     | 286       | 17.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1465      | 87.57%  |
| Yes       | 208       | 12.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1105      | 65.7%   |
| Yes       | 577       | 34.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 357       | 21.61%  |
| Lenovo                         | 294       | 17.8%   |
| Hewlett-Packard                | 258       | 15.62%  |
| Dell                           | 173       | 10.47%  |
| Gigabyte Technology            | 121       | 7.32%   |
| Acer                           | 108       | 6.54%   |
| MSI                            | 97        | 5.87%   |
| ASRock                         | 41        | 2.48%   |
| Intel                          | 25        | 1.51%   |
| Toshiba                        | 15        | 0.91%   |
| Sony                           | 14        | 0.85%   |
| Fujitsu                        | 14        | 0.85%   |
| UMAX                           | 13        | 0.79%   |
| Raspberry Pi Foundation        | 10        | 0.61%   |
| Unknown                        | 9         | 0.54%   |
| HUAWEI                         | 7         | 0.42%   |
| Apple                          | 7         | 0.42%   |
| Fujitsu Siemens                | 6         | 0.36%   |
| Supermicro                     | 5         | 0.3%    |
| Google                         | 5         | 0.3%    |
| AMI                            | 5         | 0.3%    |
| Timi                           | 4         | 0.24%   |
| Pegatron                       | 4         | 0.24%   |
| Packard Bell                   | 4         | 0.24%   |
| Microsoft                      | 4         | 0.24%   |
| ZOTAC                          | 3         | 0.18%   |
| Valve                          | 3         | 0.18%   |
| TUXEDO                         | 3         | 0.18%   |
| Notebook                       | 2         | 0.12%   |
| Insyde                         | 2         | 0.12%   |
| IBM                            | 2         | 0.12%   |
| Foxconn                        | 2         | 0.12%   |
| Clientron                      | 2         | 0.12%   |
| Chuwi                          | 2         | 0.12%   |
| Biostar                        | 2         | 0.12%   |
| Alienware                      | 2         | 0.12%   |
| Wortmann AG                    | 1         | 0.06%   |
| SmbiosType1_SystemManufacturer | 1         | 0.06%   |
| SLIMBOOK                       | 1         | 0.06%   |
| SIEMENS                        | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 103       | 6.23%   |
| Unknown                               | 11        | 0.67%   |
| ASUS All Series                       | 8         | 0.48%   |
| MSI MS-7A34                           | 6         | 0.36%   |
| MSI MS-7693                           | 6         | 0.36%   |
| HP ProBook 455 G7                     | 6         | 0.36%   |
| RPi Raspberry Pi                      | 5         | 0.3%    |
| MSI MS-7C02                           | 5         | 0.3%    |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.3%    |
| HP ProLiant DL380e Gen8               | 5         | 0.3%    |
| HP ProBook 4530s                      | 5         | 0.3%    |
| HP ProBook 450 G5                     | 5         | 0.3%    |
| Dell Latitude E6400                   | 5         | 0.3%    |
| Dell Latitude 5401                    | 5         | 0.3%    |
| MSI MS-7C91                           | 4         | 0.24%   |
| HP ProDesk 405 G6 Desktop Mini PC     | 4         | 0.24%   |
| HP ProBook 4540s                      | 4         | 0.24%   |
| HP Pavilion dv7                       | 4         | 0.24%   |
| HP Notebook                           | 4         | 0.24%   |
| HP EliteBook 840 G6                   | 4         | 0.24%   |
| Dell XPS 15 7590                      | 4         | 0.24%   |
| Dell Precision M6500                  | 4         | 0.24%   |
| Acer Extensa 5620                     | 4         | 0.24%   |
| Valve Jupiter                         | 3         | 0.18%   |
| MSI MS-7592                           | 3         | 0.18%   |
| Lenovo Z50-75 80EC                    | 3         | 0.18%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.18%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.18%   |
| HP ProBook 4510s                      | 3         | 0.18%   |
| HP Pavilion dv6                       | 3         | 0.18%   |
| HP ENVY x360 Convertible 15-cn0xxx    | 3         | 0.18%   |
| HP EliteBook 855 G7 Notebook PC       | 3         | 0.18%   |
| HP EliteBook 850 G6                   | 3         | 0.18%   |
| HP EliteBook 840 G3                   | 3         | 0.18%   |
| HP Compaq 8200 Elite SFF PC           | 3         | 0.18%   |
| HP 250 G6 Notebook PC                 | 3         | 0.18%   |
| Gigabyte B450 AORUS ELITE             | 3         | 0.18%   |
| Gigabyte 970A-DS3P                    | 3         | 0.18%   |
| Dell XPS 15 9560                      | 3         | 0.18%   |
| Dell XPS 13 9360                      | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 141       | 8.54%   |
| ASUS UX31E         | 103       | 6.23%   |
| Dell Latitude      | 75        | 4.54%   |
| Acer Aspire        | 65        | 3.93%   |
| HP ProBook         | 56        | 3.39%   |
| HP EliteBook       | 54        | 3.27%   |
| Lenovo IdeaPad     | 49        | 2.97%   |
| HP Compaq          | 29        | 1.76%   |
| HP Pavilion        | 27        | 1.63%   |
| ASUS ROG           | 24        | 1.45%   |
| ASUS PRIME         | 24        | 1.45%   |
| Dell XPS           | 23        | 1.39%   |
| Dell Precision     | 21        | 1.27%   |
| Dell Inspiron      | 20        | 1.21%   |
| Lenovo Yoga        | 17        | 1.03%   |
| Dell OptiPlex      | 15        | 0.91%   |
| Toshiba Satellite  | 14        | 0.85%   |
| Acer Extensa       | 13        | 0.79%   |
| Lenovo ThinkCentre | 12        | 0.73%   |
| Lenovo Legion      | 12        | 0.73%   |
| ASUS TUF           | 12        | 0.73%   |
| HP ENVY            | 11        | 0.67%   |
| Unknown            | 11        | 0.67%   |
| RPi Raspberry      | 10        | 0.61%   |
| HP ProDesk         | 10        | 0.61%   |
| ASUS VivoBook      | 10        | 0.61%   |
| UMAX VisionBook    | 9         | 0.54%   |
| HP ZBook           | 9         | 0.54%   |
| Dell Vostro        | 9         | 0.54%   |
| ASUS ZenBook       | 9         | 0.54%   |
| Acer TravelMate    | 9         | 0.54%   |
| Lenovo ThinkBook   | 8         | 0.48%   |
| HP Laptop          | 8         | 0.48%   |
| Fujitsu LIFEBOOK   | 8         | 0.48%   |
| ASUS All           | 8         | 0.48%   |
| Acer Swift         | 8         | 0.48%   |
| Gigabyte B450      | 7         | 0.42%   |
| MSI MS-7A34        | 6         | 0.36%   |
| MSI MS-7693        | 6         | 0.36%   |
| HP ProLiant        | 6         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 201       | 12.17%  |
| 2020    | 153       | 9.26%   |
| 2018    | 153       | 9.26%   |
| 2019    | 144       | 8.72%   |
| 2017    | 118       | 7.14%   |
| 2012    | 115       | 6.96%   |
| 2014    | 94        | 5.69%   |
| 2021    | 92        | 5.57%   |
| 2013    | 88        | 5.33%   |
| 2008    | 86        | 5.21%   |
| 2015    | 84        | 5.08%   |
| 2016    | 71        | 4.3%    |
| 2010    | 68        | 4.12%   |
| 2009    | 62        | 3.75%   |
| 2007    | 60        | 3.63%   |
| 2006    | 22        | 1.33%   |
| 2022    | 17        | 1.03%   |
| Unknown | 12        | 0.73%   |
| 2005    | 7         | 0.42%   |
| 2004    | 4         | 0.24%   |
| 2000    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1003      | 60.71%  |
| Desktop        | 527       | 31.9%   |
| Convertible    | 43        | 2.6%    |
| Mini pc        | 24        | 1.45%   |
| Tablet         | 15        | 0.91%   |
| Server         | 15        | 0.91%   |
| All in one     | 13        | 0.79%   |
| System on chip | 11        | 0.67%   |
| Phone          | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1510      | 90.64%  |
| Enabled  | 156       | 9.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1647      | 99.7%   |
| Yes  | 5         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 438       | 25.98%  |
| 4.01-8.0        | 306       | 18.15%  |
| 8.01-16.0       | 293       | 17.38%  |
| 16.01-24.0      | 284       | 16.84%  |
| 32.01-64.0      | 163       | 9.67%   |
| 1.01-2.0        | 91        | 5.4%    |
| 64.01-256.0     | 34        | 2.02%   |
| 24.01-32.0      | 29        | 1.72%   |
| 2.01-3.0        | 28        | 1.66%   |
| 0.51-1.0        | 16        | 0.95%   |
| More than 256.0 | 2         | 0.12%   |
| 0.01-0.5        | 2         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 698       | 38.23%  |
| 2.01-3.0   | 384       | 21.03%  |
| 4.01-8.0   | 268       | 14.68%  |
| 3.01-4.0   | 203       | 11.12%  |
| 0.51-1.0   | 126       | 6.9%    |
| 8.01-16.0  | 100       | 5.48%   |
| 0.01-0.5   | 22        | 1.2%    |
| 16.01-24.0 | 14        | 0.77%   |
| 32.01-64.0 | 6         | 0.33%   |
| 24.01-32.0 | 4         | 0.22%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1115      | 65.4%   |
| 2      | 360       | 21.11%  |
| 3      | 107       | 6.28%   |
| 4      | 48        | 2.82%   |
| 5      | 25        | 1.47%   |
| 0      | 23        | 1.35%   |
| 6      | 13        | 0.76%   |
| 7      | 9         | 0.53%   |
| 8      | 4         | 0.23%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1058      | 63.51%  |
| Yes       | 608       | 36.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1447      | 87.17%  |
| No        | 213       | 12.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1219      | 73.52%  |
| No        | 439       | 26.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 922       | 55.11%  |
| No        | 751       | 44.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Czechia | 1652      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Prague               | 648       | 38.03%  |
| Brno                 | 154       | 9.04%   |
| Ostrava              | 45        | 2.64%   |
| Pilsen               | 35        | 2.05%   |
| Hradec Králové     | 26        | 1.53%   |
| Pardubice            | 22        | 1.29%   |
| Liberec              | 22        | 1.29%   |
| Olomouc              | 21        | 1.23%   |
| České Budějovice  | 21        | 1.23%   |
| Zlín                | 16        | 0.94%   |
| Havířov            | 15        | 0.88%   |
| Chomutov             | 12        | 0.7%    |
| Znojmo               | 10        | 0.59%   |
| Most                 | 10        | 0.59%   |
| Jihlava              | 9         | 0.53%   |
| Ústí nad Labem     | 8         | 0.47%   |
| Přerov              | 8         | 0.47%   |
| Karlovy Vary         | 8         | 0.47%   |
| Frýdek-Místek      | 8         | 0.47%   |
| Uherské Hradiště  | 7         | 0.41%   |
| Praha 10             | 7         | 0.41%   |
| Česká Lípa        | 7         | 0.41%   |
| Teplice              | 6         | 0.35%   |
| Opava                | 6         | 0.35%   |
| Mladá Boleslav      | 6         | 0.35%   |
| Litoměřice         | 6         | 0.35%   |
| Kralupy nad Vltavou  | 6         | 0.35%   |
| Kladno               | 6         | 0.35%   |
| As                   | 6         | 0.35%   |
| Uvaly                | 5         | 0.29%   |
| Třebíč            | 5         | 0.29%   |
| Rumburk              | 5         | 0.29%   |
| Roznov pod Radhostem | 5         | 0.29%   |
| Příbram            | 5         | 0.29%   |
| Odolena Voda         | 5         | 0.29%   |
| Mariánské Lázně  | 5         | 0.29%   |
| Ivancice             | 5         | 0.29%   |
| Bohumin              | 5         | 0.29%   |
| Vyškov              | 4         | 0.23%   |
| Vsetin               | 4         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 381       | 612    | 16.71%  |
| Samsung Electronics       | 356       | 497    | 15.61%  |
| Seagate                   | 325       | 492    | 14.25%  |
| SanDisk                   | 169       | 178    | 7.41%   |
| Kingston                  | 161       | 197    | 7.06%   |
| Toshiba                   | 137       | 168    | 6.01%   |
| Unknown                   | 97        | 131    | 4.25%   |
| Hitachi                   | 75        | 88     | 3.29%   |
| SK hynix                  | 66        | 76     | 2.89%   |
| A-DATA Technology         | 58        | 71     | 2.54%   |
| Intel                     | 56        | 66     | 2.46%   |
| Crucial                   | 54        | 68     | 2.37%   |
| HGST                      | 44        | 55     | 1.93%   |
| Micron Technology         | 43        | 59     | 1.89%   |
| Patriot                   | 38        | 49     | 1.67%   |
| Transcend                 | 16        | 24     | 0.7%    |
| Phison                    | 14        | 26     | 0.61%   |
| KIOXIA                    | 14        | 20     | 0.61%   |
| Apacer                    | 11        | 15     | 0.48%   |
| OCZ                       | 10        | 33     | 0.44%   |
| Gigabyte Technology       | 10        | 17     | 0.44%   |
| Maxtor                    | 9         | 13     | 0.39%   |
| LITEONIT                  | 9         | 11     | 0.39%   |
| Fujitsu                   | 9         | 10     | 0.39%   |
| Verbatim                  | 7         | 7      | 0.31%   |
| Silicon Motion            | 7         | 7      | 0.31%   |
| LITEON                    | 7         | 8      | 0.31%   |
| China                     | 7         | 8      | 0.31%   |
| XPG                       | 6         | 8      | 0.26%   |
| JMicron Technology        | 6         | 7      | 0.26%   |
| GOODRAM                   | 5         | 8      | 0.22%   |
| Corsair                   | 5         | 5      | 0.22%   |
| Apple                     | 5         | 8      | 0.22%   |
| Micron/Crucial Technology | 4         | 4      | 0.18%   |
| ASMedia                   | 4         | 6      | 0.18%   |
| Unknown                   | 4         | 5      | 0.18%   |
| UMAX                      | 3         | 3      | 0.13%   |
| Team                      | 3         | 3      | 0.13%   |
| Phison Electronics        | 3         | 3      | 0.13%   |
| SPCC                      | 2         | 2      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                 | 103       | 4.11%   |
| Samsung SSD 860 EVO 500GB              | 28        | 1.12%   |
| Kingston SA400S37240G 240GB SSD        | 25        | 1%      |
| Samsung NVMe SSD Drive 512GB           | 24        | 0.96%   |
| Unknown MMC Card  64GB                 | 19        | 0.76%   |
| Kingston SA400S37120G 120GB SSD        | 18        | 0.72%   |
| Samsung SSD 850 EVO 250GB              | 17        | 0.68%   |
| Kingston SA400S37480G 480GB SSD        | 17        | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB         | 16        | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 15        | 0.6%    |
| Samsung NVMe SSD Drive 500GB           | 15        | 0.6%    |
| HGST HTS721010A9E630 1TB               | 15        | 0.6%    |
| Unknown MMC Card  32GB                 | 14        | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 13        | 0.52%   |
| Toshiba NVMe SSD Drive 256GB           | 13        | 0.52%   |
| Seagate ST3500418AS 500GB              | 12        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB         | 12        | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB         | 12        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 12        | 0.48%   |
| Samsung SSD 860 EVO 1TB                | 11        | 0.44%   |
| Patriot Burst 480GB SSD                | 11        | 0.44%   |
| Patriot Burst 120GB SSD                | 11        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD       | 11        | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB               | 10        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 10        | 0.4%    |
| Samsung SSD 850 EVO 500GB              | 10        | 0.4%    |
| Toshiba MQ01ABD100 1TB                 | 9         | 0.36%   |
| SK hynix NVMe SSD Drive 512GB          | 9         | 0.36%   |
| Seagate ST500DM002-1BD142 500GB        | 9         | 0.36%   |
| Samsung MZVLB1T0HBLR-000L2 1TB         | 9         | 0.36%   |
| Kingston SHFS37A120G 120GB SSD         | 9         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 8         | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB               | 8         | 0.32%   |
| WDC WD10EZEX-08M2NA0 1TB               | 8         | 0.32%   |
| Unknown MMC Card  128GB                | 8         | 0.32%   |
| Toshiba MQ01ABF050 500GB               | 8         | 0.32%   |
| Seagate ST500LT012-1DG142 500GB        | 8         | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB         | 8         | 0.32%   |
| SanDisk NVMe SSD Drive 512GB           | 8         | 0.32%   |
| Samsung SSD 970 EVO 1TB                | 8         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 318       | 482    | 35.97%  |
| WDC                 | 294       | 481    | 33.26%  |
| Toshiba             | 80        | 88     | 9.05%   |
| Hitachi             | 75        | 88     | 8.48%   |
| HGST                | 44        | 55     | 4.98%   |
| Samsung Electronics | 42        | 61     | 4.75%   |
| Maxtor              | 9         | 13     | 1.02%   |
| Fujitsu             | 9         | 10     | 1.02%   |
| Unknown             | 4         | 4      | 0.45%   |
| pqi                 | 2         | 2      | 0.23%   |
| ASMedia             | 2         | 3      | 0.23%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| External            | 1         | 1      | 0.11%   |
| ASUSTOR             | 1         | 1      | 0.11%   |
| ASMT                | 1         | 1      | 0.11%   |
| Apple               | 1         | 4      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 154       | 196    | 19.23%  |
| SanDisk             | 135       | 140    | 16.85%  |
| Kingston            | 130       | 162    | 16.23%  |
| WDC                 | 64        | 85     | 7.99%   |
| A-DATA Technology   | 53        | 64     | 6.62%   |
| Crucial             | 51        | 65     | 6.37%   |
| Patriot             | 37        | 48     | 4.62%   |
| Micron Technology   | 22        | 34     | 2.75%   |
| Intel               | 22        | 26     | 2.75%   |
| Transcend           | 15        | 22     | 1.87%   |
| SK hynix            | 13        | 13     | 1.62%   |
| Toshiba             | 12        | 15     | 1.5%    |
| Apacer              | 11        | 15     | 1.37%   |
| LITEONIT            | 9         | 11     | 1.12%   |
| OCZ                 | 8         | 15     | 1%      |
| Verbatim            | 7         | 7      | 0.87%   |
| China               | 7         | 8      | 0.87%   |
| LITEON              | 6         | 7      | 0.75%   |
| GOODRAM             | 5         | 8      | 0.62%   |
| Gigabyte Technology | 4         | 9      | 0.5%    |
| UMAX                | 3         | 3      | 0.37%   |
| Seagate             | 3         | 3      | 0.37%   |
| JMicron Technology  | 3         | 3      | 0.37%   |
| Apple               | 3         | 3      | 0.37%   |
| Unknown             | 2         | 3      | 0.25%   |
| Team                | 2         | 2      | 0.25%   |
| SPCC                | 2         | 2      | 0.25%   |
| WDC WDS1            | 1         | 1      | 0.12%   |
| USB3.0              | 1         | 1      | 0.12%   |
| UMIS                | 1         | 1      | 0.12%   |
| TO Exter            | 1         | 2      | 0.12%   |
| TCSUNBOW            | 1         | 1      | 0.12%   |
| ShanDianZhe         | 1         | 1      | 0.12%   |
| Phison              | 1         | 1      | 0.12%   |
| Netac               | 1         | 1      | 0.12%   |
| Mushkin             | 1         | 1      | 0.12%   |
| Linux               | 1         | 1      | 0.12%   |
| Innodisk            | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 1      | 0.12%   |
| FORESEE             | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 756       | 1295   | 36.45%  |
| SSD     | 724       | 988    | 34.91%  |
| NVMe    | 483       | 678    | 23.29%  |
| MMC     | 99        | 136    | 4.77%   |
| Unknown | 12        | 16     | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1228      | 2222   | 65.46%  |
| NVMe | 483       | 675    | 25.75%  |
| MMC  | 99        | 136    | 5.28%   |
| SAS  | 66        | 80     | 3.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1006      | 1462   | 65.41%  |
| 0.51-1.0   | 371       | 524    | 24.12%  |
| 1.01-2.0   | 76        | 157    | 4.94%   |
| 2.01-3.0   | 28        | 41     | 1.82%   |
| 3.01-4.0   | 27        | 39     | 1.76%   |
| 4.01-10.0  | 21        | 46     | 1.37%   |
| 10.01-20.0 | 9         | 14     | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 443       | 25.58%  |
| 251-500        | 355       | 20.5%   |
| 1-20           | 242       | 13.97%  |
| 501-1000       | 210       | 12.12%  |
| 51-100         | 133       | 7.68%   |
| 1001-2000      | 113       | 6.52%   |
| Unknown        | 72        | 4.16%   |
| 21-50          | 71        | 4.1%    |
| More than 3000 | 65        | 3.75%   |
| 2001-3000      | 28        | 1.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 790       | 43.96%  |
| 21-50          | 230       | 12.8%   |
| 101-250        | 214       | 11.91%  |
| 51-100         | 175       | 9.74%   |
| 251-500        | 136       | 7.57%   |
| 501-1000       | 85        | 4.73%   |
| Unknown        | 72        | 4.01%   |
| 1001-2000      | 46        | 2.56%   |
| More than 3000 | 33        | 1.84%   |
| 2001-3000      | 16        | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 103       | 103    | 44.78%  |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.3%    |
| WDC WD60EFRX-68L0BN1 6TB              | 2         | 3      | 0.87%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.87%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 2         | 2      | 0.87%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.87%   |
| Seagate ST3160318AS 160GB             | 2         | 2      | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.87%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.87%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.87%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.87%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.43%   |
| WDC WD800BB-00JHA0 80GB               | 1         | 1      | 0.43%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.43%   |
| WDC WD7500AADS-00M2B0 752GB           | 1         | 1      | 0.43%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.43%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.43%   |
| WDC WD5000AAKS-00V0A0 500GB           | 1         | 1      | 0.43%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.43%   |
| WDC WD2502ABYS-02B7A0 256GB           | 1         | 1      | 0.43%   |
| WDC WD2500BPVT-22JJ5T0 250GB          | 1         | 1      | 0.43%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 0.43%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.43%   |
| WDC WD2500AAKX-60U6AA0 250GB          | 1         | 1      | 0.43%   |
| WDC WD2500AAKX-603CA0 250GB           | 1         | 1      | 0.43%   |
| WDC WD2500AAKX-083CA1 250GB           | 1         | 1      | 0.43%   |
| WDC WD2500AAJS-08L7A0 250GB           | 1         | 2      | 0.43%   |
| WDC WD20EARX-008FB0 2TB               | 1         | 2      | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 0.43%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 1      | 0.43%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 1      | 0.43%   |
| WDC WD10EZEX-35M2NA0 1TB              | 1         | 1      | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.43%   |
| WDC WD1001FALS-40K1B0 1TB             | 1         | 1      | 0.43%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD | 1         | 1      | 0.43%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.43%   |
| Toshiba MK8037GSX 80GB                | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 105       | 105    | 46.26%  |
| Seagate             | 37        | 45     | 16.3%   |
| WDC                 | 26        | 31     | 11.45%  |
| Hitachi             | 13        | 13     | 5.73%   |
| Toshiba             | 8         | 8      | 3.52%   |
| Samsung Electronics | 8         | 8      | 3.52%   |
| HGST                | 7         | 7      | 3.08%   |
| Kingston            | 5         | 5      | 2.2%    |
| SK hynix            | 4         | 4      | 1.76%   |
| Micron Technology   | 3         | 3      | 1.32%   |
| A-DATA Technology   | 3         | 5      | 1.32%   |
| Intel               | 2         | 2      | 0.88%   |
| Crucial             | 2         | 2      | 0.88%   |
| Maxtor              | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 1      | 0.44%   |
| IBM/Hitachi         | 1         | 1      | 0.44%   |
| Fujitsu             | 1         | 1      | 0.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 45     | 38.14%  |
| WDC                 | 24        | 28     | 24.74%  |
| Hitachi             | 13        | 13     | 13.4%   |
| Toshiba             | 8         | 8      | 8.25%   |
| HGST                | 7         | 7      | 7.22%   |
| Samsung Electronics | 5         | 5      | 5.15%   |
| Maxtor              | 1         | 1      | 1.03%   |
| IBM/Hitachi         | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 128       | 130    | 56.64%  |
| HDD  | 95        | 109    | 42.04%  |
| NVMe | 3         | 3      | 1.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 2         | 3      | 66.67%  |
| Unknown 00000  16GB       | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 66.67%  |
| Unknown | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 938       | 1885   | 53.36%  |
| Works    | 593       | 982    | 33.73%  |
| Malfunc  | 224       | 242    | 12.74%  |
| Failed   | 3         | 4      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1088      | 53.57%  |
| AMD                              | 321       | 15.81%  |
| Samsung Electronics              | 183       | 9.01%   |
| SanDisk                          | 66        | 3.25%   |
| SK hynix                         | 48        | 2.36%   |
| Toshiba America Info Systems     | 44        | 2.17%   |
| Kingston Technology Company      | 33        | 1.62%   |
| JMicron Technology               | 31        | 1.53%   |
| Phison Electronics               | 25        | 1.23%   |
| ASMedia Technology               | 24        | 1.18%   |
| Nvidia                           | 23        | 1.13%   |
| Marvell Technology Group         | 23        | 1.13%   |
| Micron Technology                | 21        | 1.03%   |
| KIOXIA                           | 17        | 0.84%   |
| ADATA Technology                 | 13        | 0.64%   |
| Silicon Motion                   | 12        | 0.59%   |
| VIA Technologies                 | 8         | 0.39%   |
| Micron/Crucial Technology        | 7         | 0.34%   |
| Hewlett-Packard                  | 6         | 0.3%    |
| Seagate Technology               | 5         | 0.25%   |
| Union Memory (Shenzhen)          | 3         | 0.15%   |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| Silicon Image                    | 3         | 0.15%   |
| LSI Logic / Symbios Logic        | 3         | 0.15%   |
| Lite-On Technology               | 3         | 0.15%   |
| Adaptec                          | 3         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.1%    |
| OCZ Technology Group             | 2         | 0.1%    |
| Lenovo                           | 2         | 0.1%    |
| Integrated Technology Express    | 2         | 0.1%    |
| Western Digital                  | 1         | 0.05%   |
| Promise Technology               | 1         | 0.05%   |
| Chelsio Communications           | 1         | 0.05%   |
| Broadcom / LSI                   | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| 3ware                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 200       | 8.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 154       | 6.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 95        | 3.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 76        | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 66        | 2.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 62        | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 51        | 2.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 44        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 43        | 1.81%   |
| Samsung NVMe SSD Controller 980                                                | 42        | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                         | 42        | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 37        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 37        | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 36        | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 31        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 28        | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 28        | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 26        | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 25        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 25        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 1.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 24        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 24        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 23        | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 23        | 0.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 22        | 0.92%   |
| Micron Non-Volatile memory controller                                          | 21        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 20        | 0.84%   |
| JMicron JMB363 SATA/IDE Controller                                             | 20        | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 19        | 0.8%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 17        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 17        | 0.71%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 17        | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1182      | 57.21%  |
| NVMe | 491       | 23.77%  |
| IDE  | 270       | 13.07%  |
| RAID | 114       | 5.52%   |
| SAS  | 5         | 0.24%   |
| SCSI | 4         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1236      | 74.82%  |
| AMD      | 404       | 24.46%  |
| ARM      | 11        | 0.67%   |
| QUALCOMM | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 103       | 6.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 0.84%   |
| AMD Ryzen 5 3600 6-Core Processor             | 14        | 0.84%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 13        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 10        | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 9         | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.54%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 9         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 9         | 0.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.54%   |
| ARM Processor                                 | 9         | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.48%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 8         | 0.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.48%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.48%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 8         | 0.48%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.42%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.42%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 7         | 0.42%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 7         | 0.42%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 372       | 22.41%  |
| Intel Core i5           | 305       | 18.37%  |
| Intel Core 2 Duo        | 106       | 6.39%   |
| AMD Ryzen 5             | 95        | 5.72%   |
| Intel Celeron           | 91        | 5.48%   |
| Intel Core i3           | 87        | 5.24%   |
| Other                   | 75        | 4.52%   |
| AMD Ryzen 7             | 64        | 3.86%   |
| Intel Pentium           | 49        | 2.95%   |
| Intel Atom              | 34        | 2.05%   |
| Intel Xeon              | 33        | 1.99%   |
| AMD FX                  | 33        | 1.99%   |
| AMD Ryzen 7 PRO         | 24        | 1.45%   |
| AMD Ryzen 9             | 22        | 1.33%   |
| Intel Pentium Dual-Core | 19        | 1.14%   |
| AMD A8                  | 14        | 0.84%   |
| Intel Core 2            | 13        | 0.78%   |
| AMD Ryzen 3             | 13        | 0.78%   |
| AMD A4                  | 13        | 0.78%   |
| AMD Athlon 64 X2        | 12        | 0.72%   |
| AMD A6                  | 12        | 0.72%   |
| Intel Pentium Dual      | 11        | 0.66%   |
| Intel Core 2 Quad       | 11        | 0.66%   |
| AMD A10                 | 10        | 0.6%    |
| AMD Phenom II X4        | 9         | 0.54%   |
| Intel Pentium Silver    | 8         | 0.48%   |
| AMD Athlon              | 8         | 0.48%   |
| Intel Core i9           | 7         | 0.42%   |
| AMD Ryzen 5 PRO         | 7         | 0.42%   |
| Intel Pentium Gold      | 6         | 0.36%   |
| Intel Celeron M         | 6         | 0.36%   |
| AMD Athlon II X2        | 6         | 0.36%   |
| Intel Celeron Dual-Core | 5         | 0.3%    |
| Intel Pentium M         | 4         | 0.24%   |
| Intel Pentium 4         | 4         | 0.24%   |
| Intel Genuine           | 4         | 0.24%   |
| AMD Turion II           | 4         | 0.24%   |
| AMD E1                  | 4         | 0.24%   |
| AMD E                   | 4         | 0.24%   |
| AMD Athlon II X4        | 4         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 753       | 45.36%  |
| 4       | 542       | 32.65%  |
| 6       | 155       | 9.34%   |
| 8       | 110       | 6.63%   |
| 1       | 53        | 3.19%   |
| 12      | 21        | 1.27%   |
| 3       | 11        | 0.66%   |
| 16      | 6         | 0.36%   |
| Unknown | 3         | 0.18%   |
| 14      | 2         | 0.12%   |
| 10      | 2         | 0.12%   |
| 32      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1639      | 99.21%  |
| 2      | 13        | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1043      | 62.98%  |
| 1       | 609       | 36.78%  |
| Unknown | 3         | 0.18%   |
| 4       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1597      | 96.2%   |
| Unknown        | 36        | 2.17%   |
| 32-bit         | 24        | 1.45%   |
| 64-bit         | 3         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 297       | 17.35%  |
| 0x206a7    | 182       | 10.63%  |
| 0x1067a    | 70        | 4.09%   |
| 0x306c3    | 69        | 4.03%   |
| 0x306a9    | 65        | 3.8%    |
| 0x906ea    | 46        | 2.69%   |
| 0x806ec    | 45        | 2.63%   |
| 0x806ea    | 43        | 2.51%   |
| 0x806c1    | 33        | 1.93%   |
| 0x406e3    | 33        | 1.93%   |
| 0x806e9    | 31        | 1.81%   |
| 0x6fd      | 29        | 1.69%   |
| 0x40651    | 28        | 1.64%   |
| 0x08600106 | 28        | 1.64%   |
| 0x906e9    | 27        | 1.58%   |
| 0x506e3    | 27        | 1.58%   |
| 0x306d4    | 21        | 1.23%   |
| 0x6fb      | 20        | 1.17%   |
| 0x30678    | 20        | 1.17%   |
| 0x010000c8 | 19        | 1.11%   |
| 0x10676    | 18        | 1.05%   |
| 0x0a50000c | 18        | 1.05%   |
| 0x06000852 | 18        | 1.05%   |
| 0x406c4    | 17        | 0.99%   |
| 0x08701021 | 17        | 0.99%   |
| 0x706a1    | 15        | 0.88%   |
| 0x20655    | 15        | 0.88%   |
| 0x0800820d | 15        | 0.88%   |
| 0x906ed    | 14        | 0.82%   |
| 0x506c9    | 14        | 0.82%   |
| 0xa0652    | 13        | 0.76%   |
| 0x06001119 | 13        | 0.76%   |
| 0x08701013 | 12        | 0.7%    |
| 0x08600104 | 12        | 0.7%    |
| 0x08108102 | 12        | 0.7%    |
| 0x406c3    | 11        | 0.64%   |
| 0x08608103 | 11        | 0.64%   |
| 0x706e5    | 10        | 0.58%   |
| 0x20652    | 10        | 0.58%   |
| 0x6f6      | 9         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 260       | 15.72%  |
| SandyBridge      | 207       | 12.52%  |
| Haswell          | 120       | 7.26%   |
| Penryn           | 106       | 6.41%   |
| Zen 2            | 90        | 5.44%   |
| IvyBridge        | 84        | 5.08%   |
| Core             | 72        | 4.35%   |
| Skylake          | 71        | 4.29%   |
| Silvermont       | 63        | 3.81%   |
| Zen 3            | 45        | 2.72%   |
| Piledriver       | 43        | 2.6%    |
| Zen+             | 39        | 2.36%   |
| TigerLake        | 39        | 2.36%   |
| Zen              | 38        | 2.3%    |
| Unknown          | 37        | 2.24%   |
| Westmere         | 35        | 2.12%   |
| K10              | 35        | 2.12%   |
| CometLake        | 30        | 1.81%   |
| Goldmont plus    | 26        | 1.57%   |
| Broadwell        | 26        | 1.57%   |
| K8 Hammer        | 25        | 1.51%   |
| Excavator        | 18        | 1.09%   |
| IceLake          | 16        | 0.97%   |
| Goldmont         | 16        | 0.97%   |
| Nehalem          | 15        | 0.91%   |
| Bonnell          | 14        | 0.85%   |
| Steamroller      | 13        | 0.79%   |
| P6               | 12        | 0.73%   |
| Puma             | 11        | 0.67%   |
| Bobcat           | 9         | 0.54%   |
| NetBurst         | 8         | 0.48%   |
| Alderlake Hybrid | 8         | 0.48%   |
| Jaguar           | 6         | 0.36%   |
| Tremont          | 5         | 0.3%    |
| K10 Llano        | 5         | 0.3%    |
| K8 & K10 hybrid  | 3         | 0.18%   |
| Bulldozer        | 3         | 0.18%   |
| K6               | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 975       | 50.68%  |
| Nvidia                           | 484       | 25.16%  |
| AMD                              | 446       | 23.18%  |
| Matrox Electronics Systems       | 11        | 0.57%   |
| ASPEED Technology                | 4         | 0.21%   |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| VIA Technologies                 | 1         | 0.05%   |
| ATI Technologies                 | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 178       | 8.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 2.74%   |
| Intel UHD Graphics 620                                                                   | 53        | 2.64%   |
| AMD Renoir                                                                               | 51        | 2.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 1.65%   |
| Intel HD Graphics 620                                                                    | 33        | 1.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 31        | 1.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 1.35%   |
| Intel HD Graphics 5500                                                                   | 22        | 1.1%    |
| Intel HD Graphics 630                                                                    | 21        | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.95%   |
| Intel HD Graphics 530                                                                    | 19        | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 16        | 0.8%    |
| Intel HD Graphics 500                                                                    | 15        | 0.75%   |
| AMD Lucienne                                                                             | 15        | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.7%    |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.65%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 721       | 43.46%  |
| 1 x AMD        | 345       | 20.8%   |
| 1 x Nvidia     | 262       | 15.79%  |
| Intel + Nvidia | 196       | 11.81%  |
| Intel + AMD    | 51        | 3.07%   |
| 2 x AMD        | 31        | 1.87%   |
| AMD + Nvidia   | 19        | 1.15%   |
| Other          | 12        | 0.72%   |
| 1 x Matrox     | 10        | 0.6%    |
| 1 x ASPEED     | 4         | 0.24%   |
| 3 x Nvidia     | 2         | 0.12%   |
| 2 x Nvidia     | 2         | 0.12%   |
| 1 x SiS        | 2         | 0.12%   |
| 1 x VIA        | 1         | 0.06%   |
| AMD + Matrox   | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1380      | 82.49%  |
| Proprietary | 231       | 13.81%  |
| Unknown     | 62        | 3.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 956       | 56.1%   |
| 0.01-0.5   | 223       | 13.09%  |
| 1.01-2.0   | 204       | 11.97%  |
| 0.51-1.0   | 125       | 7.34%   |
| 3.01-4.0   | 92        | 5.4%    |
| 7.01-8.0   | 47        | 2.76%   |
| 5.01-6.0   | 26        | 1.53%   |
| 2.01-3.0   | 18        | 1.06%   |
| 8.01-16.0  | 12        | 0.7%    |
| 16.01-24.0 | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 221       | 11.58%  |
| Samsung Electronics     | 219       | 11.47%  |
| LG Display              | 165       | 8.64%   |
| Chimei Innolux          | 140       | 7.33%   |
| Dell                    | 123       | 6.44%   |
| BOE                     | 114       | 5.97%   |
| CPT                     | 105       | 5.5%    |
| Goldstar                | 80        | 4.19%   |
| BenQ                    | 78        | 4.09%   |
| Acer                    | 71        | 3.72%   |
| Hewlett-Packard         | 58        | 3.04%   |
| Eizo                    | 55        | 2.88%   |
| Philips                 | 53        | 2.78%   |
| Lenovo                  | 46        | 2.41%   |
| AOC                     | 43        | 2.25%   |
| Sharp                   | 38        | 1.99%   |
| Ancor Communications    | 38        | 1.99%   |
| Chi Mei Optoelectronics | 28        | 1.47%   |
| Iiyama                  | 22        | 1.15%   |
| PANDA                   | 20        | 1.05%   |
| Sony                    | 16        | 0.84%   |
| LG Philips              | 15        | 0.79%   |
| Fujitsu Siemens         | 11        | 0.58%   |
| Panasonic               | 10        | 0.52%   |
| NEC Computers           | 10        | 0.52%   |
| InfoVision              | 9         | 0.47%   |
| CSO                     | 8         | 0.42%   |
| ASUSTek Computer        | 8         | 0.42%   |
| Apple                   | 7         | 0.37%   |
| ViewSonic               | 6         | 0.31%   |
| Vestel Elektronik       | 6         | 0.31%   |
| Quanta Display          | 6         | 0.31%   |
| LG Electronics          | 5         | 0.26%   |
| Unknown                 | 4         | 0.21%   |
| Toshiba                 | 4         | 0.21%   |
| Lenovo Group Limited    | 4         | 0.21%   |
| Hitachi                 | 4         | 0.21%   |
| HannStar                | 4         | 0.21%   |
| OEM                     | 3         | 0.16%   |
| MStar                   | 3         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 103       | 5.15%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 37        | 1.85%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 12        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.55%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 11        | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.55%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 9         | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.35%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 7         | 0.35%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 6         | 0.3%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 6         | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 6         | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 6         | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.3%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.3%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 5         | 0.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 5         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 5         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.25%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                    | 5         | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 5         | 0.25%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                        | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 5         | 0.25%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 5         | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 4         | 0.2%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 4         | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.2%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 4         | 0.2%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 4         | 0.2%    |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 4         | 0.2%    |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch                 | 4         | 0.2%    |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                     | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 788       | 43.66%  |
| 1366x768 (WXGA)    | 220       | 12.19%  |
| 1600x900 (HD+)     | 168       | 9.31%   |
| 3840x2160 (4K)     | 123       | 6.81%   |
| 2560x1440 (QHD)    | 79        | 4.38%   |
| 1920x1200 (WUXGA)  | 69        | 3.82%   |
| 1280x1024 (SXGA)   | 69        | 3.82%   |
| 1680x1050 (WSXGA+) | 67        | 3.71%   |
| 1280x800 (WXGA)    | 58        | 3.21%   |
| 1440x900 (WXGA+)   | 31        | 1.72%   |
| 1024x768 (XGA)     | 11        | 0.61%   |
| Unknown            | 11        | 0.61%   |
| 2560x1600          | 9         | 0.5%    |
| 3440x1440          | 8         | 0.44%   |
| 1360x768           | 8         | 0.44%   |
| 3840x1080          | 7         | 0.39%   |
| 2560x1080          | 7         | 0.39%   |
| 1600x1200          | 7         | 0.39%   |
| 1920x540           | 6         | 0.33%   |
| 1024x600           | 5         | 0.28%   |
| 2160x1350          | 4         | 0.22%   |
| 1280x720 (HD)      | 4         | 0.22%   |
| 800x1280           | 3         | 0.17%   |
| 3840x2400          | 3         | 0.17%   |
| 3456x2160          | 3         | 0.17%   |
| 3000x2000          | 3         | 0.17%   |
| 2880x1800          | 3         | 0.17%   |
| 2736x1824          | 3         | 0.17%   |
| 2288x1287          | 3         | 0.17%   |
| 2160x1440          | 3         | 0.17%   |
| 1400x1050          | 3         | 0.17%   |
| 3840x1200          | 2         | 0.11%   |
| 3200x1800 (QHD+)   | 2         | 0.11%   |
| 1280x768           | 2         | 0.11%   |
| 9600x2160          | 1         | 0.06%   |
| 8320x2160          | 1         | 0.06%   |
| 7680x2160          | 1         | 0.06%   |
| 640x480            | 1         | 0.06%   |
| 6400x2160          | 1         | 0.06%   |
| 6080x1440          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 436       | 22.61%  |
| 13      | 263       | 13.64%  |
| 24      | 194       | 10.06%  |
| 14      | 139       | 7.21%   |
| 27      | 126       | 6.54%   |
| 23      | 110       | 5.71%   |
| 17      | 99        | 5.13%   |
| 21      | 88        | 4.56%   |
| 31      | 69        | 3.58%   |
| Unknown | 66        | 3.42%   |
| 19      | 64        | 3.32%   |
| 22      | 42        | 2.18%   |
| 12      | 34        | 1.76%   |
| 20      | 29        | 1.5%    |
| 11      | 23        | 1.19%   |
| 18      | 20        | 1.04%   |
| 84      | 14        | 0.73%   |
| 34      | 13        | 0.67%   |
| 25      | 11        | 0.57%   |
| 26      | 8         | 0.41%   |
| 16      | 8         | 0.41%   |
| 72      | 7         | 0.36%   |
| 54      | 7         | 0.36%   |
| 32      | 7         | 0.36%   |
| 10      | 7         | 0.36%   |
| 33      | 6         | 0.31%   |
| 52      | 5         | 0.26%   |
| 65      | 4         | 0.21%   |
| 47      | 4         | 0.21%   |
| 46      | 4         | 0.21%   |
| 39      | 4         | 0.21%   |
| 49      | 3         | 0.16%   |
| 43      | 3         | 0.16%   |
| 40      | 3         | 0.16%   |
| 60      | 1         | 0.05%   |
| 59      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 38      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 672       | 35.8%   |
| 501-600     | 396       | 21.1%   |
| 201-300     | 245       | 13.05%  |
| 401-500     | 191       | 10.18%  |
| 351-400     | 137       | 7.3%    |
| 601-700     | 80        | 4.26%   |
| Unknown     | 66        | 3.52%   |
| 1001-1500   | 33        | 1.76%   |
| 701-800     | 25        | 1.33%   |
| 1501-2000   | 21        | 1.12%   |
| 801-900     | 9         | 0.48%   |
| 901-1000    | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1219      | 72.99%  |
| 16/10   | 262       | 15.69%  |
| 5/4     | 74        | 4.43%   |
| Unknown | 54        | 3.23%   |
| 4/3     | 24        | 1.44%   |
| 3/2     | 16        | 0.96%   |
| 21/9    | 12        | 0.72%   |
| 32/9    | 3         | 0.18%   |
| 0.62    | 3         | 0.18%   |
| 3.20    | 2         | 0.12%   |
| 3.73    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 430       | 22.49%  |
| 201-250        | 332       | 17.36%  |
| 81-90          | 227       | 11.87%  |
| 71-80          | 179       | 9.36%   |
| 301-350        | 133       | 6.96%   |
| 151-200        | 111       | 5.81%   |
| 351-500        | 96        | 5.02%   |
| 251-300        | 86        | 4.5%    |
| Unknown        | 66        | 3.45%   |
| 121-130        | 60        | 3.14%   |
| More than 1000 | 41        | 2.14%   |
| 141-150        | 41        | 2.14%   |
| 61-70          | 29        | 1.52%   |
| 51-60          | 23        | 1.2%    |
| 501-1000       | 23        | 1.2%    |
| 131-140        | 13        | 0.68%   |
| 111-120        | 9         | 0.47%   |
| 41-50          | 7         | 0.37%   |
| 91-100         | 6         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 627       | 34.6%   |
| 121-160       | 607       | 33.5%   |
| 101-120       | 345       | 19.04%  |
| 161-240       | 104       | 5.74%   |
| Unknown       | 66        | 3.64%   |
| 1-50          | 36        | 1.99%   |
| More than 240 | 27        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1267      | 74.22%  |
| 2     | 318       | 18.63%  |
| 0     | 72        | 4.22%   |
| 3     | 48        | 2.81%   |
| 4     | 2         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 778       | 31.38%  |
| Realtek Semiconductor                  | 777       | 31.34%  |
| Qualcomm Atheros                       | 374       | 15.09%  |
| Broadcom                               | 108       | 4.36%   |
| Samsung Electronics                    | 106       | 4.28%   |
| Broadcom Limited                       | 45        | 1.82%   |
| Marvell Technology Group               | 35        | 1.41%   |
| TP-Link                                | 25        | 1.01%   |
| MediaTek                               | 23        | 0.93%   |
| Lenovo                                 | 21        | 0.85%   |
| Nvidia                                 | 18        | 0.73%   |
| Ralink Technology                      | 14        | 0.56%   |
| Qualcomm Atheros Communications        | 14        | 0.56%   |
| Ralink                                 | 13        | 0.52%   |
| Dell                                   | 13        | 0.52%   |
| DisplayLink                            | 11        | 0.44%   |
| Sierra Wireless                        | 10        | 0.4%    |
| ASIX Electronics                       | 10        | 0.4%    |
| ASUSTek Computer                       | 8         | 0.32%   |
| Microsoft                              | 6         | 0.24%   |
| QLogic                                 | 5         | 0.2%    |
| VIA Technologies                       | 4         | 0.16%   |
| D-Link                                 | 4         | 0.16%   |
| Attansic Technology                    | 4         | 0.16%   |
| ZyDAS                                  | 3         | 0.12%   |
| Xiaomi                                 | 3         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.12%   |
| Huawei Technologies                    | 3         | 0.12%   |
| Hewlett-Packard                        | 3         | 0.12%   |
| Ericsson Business Mobile Networks      | 3         | 0.12%   |
| Edimax Technology                      | 3         | 0.12%   |
| Spreadtrum Communications              | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.08%   |
| Mellanox Technologies                  | 2         | 0.08%   |
| Arduino SA                             | 2         | 0.08%   |
| ZyXEL Communications                   | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| SIEMENS                                | 1         | 0.04%   |
| Seeed Technology                       | 1         | 0.04%   |
| Qualcomm                               | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 558       | 19.38%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 126       | 4.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 104       | 3.61%   |
| Intel Wi-Fi 6 AX200                                               | 86        | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 58        | 2.01%   |
| Intel Wireless 8265 / 8275                                        | 57        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 39        | 1.35%   |
| Intel Wireless 7260                                               | 39        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 38        | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 1.08%   |
| Intel Wireless 8260                                               | 30        | 1.04%   |
| Intel I211 Gigabit Network Connection                             | 30        | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 30        | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.01%   |
| Intel Wi-Fi 6 AX201                                               | 29        | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 0.97%   |
| Intel Wireless 7265                                               | 27        | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 26        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25        | 0.87%   |
| Intel Wireless 3165                                               | 25        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 17        | 0.59%   |
| Intel WiFi Link 5100                                              | 16        | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 16        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16        | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 0.52%   |
| Intel Wireless 3160                                               | 15        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 618       | 48.66%  |
| Qualcomm Atheros                | 303       | 23.86%  |
| Realtek Semiconductor           | 133       | 10.47%  |
| Broadcom                        | 59        | 4.65%   |
| TP-Link                         | 23        | 1.81%   |
| Broadcom Limited                | 23        | 1.81%   |
| MediaTek                        | 22        | 1.73%   |
| Ralink Technology               | 14        | 1.1%    |
| Qualcomm Atheros Communications | 14        | 1.1%    |
| Ralink                          | 13        | 1.02%   |
| Sierra Wireless                 | 10        | 0.79%   |
| Dell                            | 7         | 0.55%   |
| ASUSTek Computer                | 7         | 0.55%   |
| Microsoft                       | 6         | 0.47%   |
| ZyDAS                           | 3         | 0.24%   |
| Edimax Technology               | 3         | 0.24%   |
| D-Link                          | 3         | 0.24%   |
| Marvell Technology Group        | 2         | 0.16%   |
| Hewlett-Packard                 | 2         | 0.16%   |
| ZyXEL Communications            | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Intersil                        | 1         | 0.08%   |
| Fujitsu Siemens Computers       | 1         | 0.08%   |
| Fibocom                         | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 126       | 9.9%    |
| Intel Wi-Fi 6 AX200                                            | 86        | 6.76%   |
| Intel Wireless 8265 / 8275                                     | 57        | 4.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 39        | 3.06%   |
| Intel Wireless 7260                                            | 39        | 3.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 38        | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 31        | 2.44%   |
| Intel Wireless 8260                                            | 30        | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 29        | 2.28%   |
| Intel Wi-Fi 6 AX201                                            | 29        | 2.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 28        | 2.2%    |
| Intel Wireless 7265                                            | 27        | 2.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 26        | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25        | 1.96%   |
| Intel Wireless 3165                                            | 25        | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22        | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 18        | 1.41%   |
| Intel WiFi Link 5100                                           | 16        | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 16        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 16        | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 1.18%   |
| Intel Wireless 3160                                            | 15        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 1.02%   |
| Intel Centrino Wireless-N 2230                                 | 12        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                | 11        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 0.79%   |
| Intel Wireless-AC 9260                                         | 10        | 0.79%   |
| Intel Ultimate N WiFi Link 5300                                | 10        | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 10        | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 0.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 8         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 715       | 46.52%  |
| Intel                            | 396       | 25.76%  |
| Qualcomm Atheros                 | 108       | 7.03%   |
| Samsung Electronics              | 106       | 6.9%    |
| Broadcom                         | 56        | 3.64%   |
| Marvell Technology Group         | 34        | 2.21%   |
| Broadcom Limited                 | 22        | 1.43%   |
| Lenovo                           | 21        | 1.37%   |
| Nvidia                           | 18        | 1.17%   |
| DisplayLink                      | 11        | 0.72%   |
| ASIX Electronics                 | 10        | 0.65%   |
| QLogic                           | 5         | 0.33%   |
| Attansic Technology              | 4         | 0.26%   |
| Xiaomi                           | 3         | 0.2%    |
| VIA Technologies                 | 3         | 0.2%    |
| TP-Link                          | 2         | 0.13%   |
| Spreadtrum Communications        | 2         | 0.13%   |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| Huawei Technologies              | 2         | 0.13%   |
| MosChip Semiconductor            | 1         | 0.07%   |
| Microchip Technology             | 1         | 0.07%   |
| Mellanox Technologies            | 1         | 0.07%   |
| MediaTek                         | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |
| IBM                              | 1         | 0.07%   |
| Google                           | 1         | 0.07%   |
| Foxconn / Hon Hai                | 1         | 0.07%   |
| Emulex                           | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| D-Link                           | 1         | 0.07%   |
| Chelsio Communications           | 1         | 0.07%   |
| ASUSTek Computer                 | 1         | 0.07%   |
| Aquantia                         | 1         | 0.07%   |
| American Megatrends              | 1         | 0.07%   |
| 3Com                             | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 558       | 35.36%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 104       | 6.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 71        | 4.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 58        | 3.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 57        | 3.61%   |
| Intel I211 Gigabit Network Connection                                          | 30        | 1.9%    |
| Intel Ethernet Connection I217-LM                                              | 30        | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                                          | 26        | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                              | 23        | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 19        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 18        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                           | 18        | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 17        | 1.08%   |
| Intel Ethernet Connection I219-LM                                              | 14        | 0.89%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 0.82%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 0.76%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                          | 12        | 0.76%   |
| Intel Ethernet Controller I225-V                                               | 11        | 0.7%    |
| Intel Ethernet Connection (7) I219-V                                           | 11        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 10        | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 10        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 9         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 8         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 8         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 7         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                                         | 7         | 0.44%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 7         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1443      | 53.64%  |
| WiFi     | 1219      | 45.32%  |
| Modem    | 22        | 0.82%   |
| Unknown  | 6         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 874       | 51.14%  |
| Ethernet | 834       | 48.8%   |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 847       | 51.09%  |
| 1     | 730       | 44.03%  |
| 0     | 41        | 2.47%   |
| 3     | 28        | 1.69%   |
| 4     | 5         | 0.3%    |
| 8     | 4         | 0.24%   |
| 5     | 2         | 0.12%   |
| 10    | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1494      | 89.14%  |
| Yes  | 182       | 10.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 458       | 49.19%  |
| Realtek Semiconductor           | 74        | 7.95%   |
| Qualcomm Atheros Communications | 65        | 6.98%   |
| IMC Networks                    | 57        | 6.12%   |
| Broadcom                        | 55        | 5.91%   |
| Cambridge Silicon Radio         | 46        | 4.94%   |
| Foxconn / Hon Hai               | 34        | 3.65%   |
| Lite-On Technology              | 33        | 3.54%   |
| ASUSTek Computer                | 33        | 3.54%   |
| Hewlett-Packard                 | 22        | 2.36%   |
| Dell                            | 14        | 1.5%    |
| Apple                           | 6         | 0.64%   |
| MediaTek                        | 5         | 0.54%   |
| Alps Electric                   | 5         | 0.54%   |
| Realtek                         | 4         | 0.43%   |
| Ralink                          | 4         | 0.43%   |
| Toshiba                         | 3         | 0.32%   |
| Ralink Technology               | 2         | 0.21%   |
| Micro Star International        | 2         | 0.21%   |
| Marvell Semiconductor           | 2         | 0.21%   |
| Integrated System Solution      | 2         | 0.21%   |
| TP-Link                         | 1         | 0.11%   |
| Mobile Action Technology        | 1         | 0.11%   |
| Fujitsu Siemens Computers       | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 185       | 19.87%  |
| Intel AX200 Bluetooth                                                               | 83        | 8.92%   |
| Intel AX201 Bluetooth                                                               | 75        | 8.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 60        | 6.44%   |
| Realtek Bluetooth Radio                                                             | 47        | 5.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 46        | 4.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 24        | 2.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 21        | 2.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 18        | 1.93%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 1.83%   |
| IMC Networks Bluetooth Device                                                       | 17        | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 16        | 1.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 13        | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 13        | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.18%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 1.18%   |
| Broadcom BCM2045 Bluetooth                                                          | 11        | 1.18%   |
| IMC Networks Wireless_Device                                                        | 10        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 0.86%   |
| Intel AX210 Bluetooth                                                               | 8         | 0.86%   |
| Dell DW375 Bluetooth Module                                                         | 8         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 0.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 8         | 0.86%   |
| ASUS ASUS USB-BT500                                                                 | 8         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 7         | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 0.75%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 7         | 0.75%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.64%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.64%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.54%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.43%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.43%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 4         | 0.43%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1175      | 53.51%  |
| AMD                                  | 477       | 21.72%  |
| Nvidia                               | 309       | 14.07%  |
| C-Media Electronics                  | 45        | 2.05%   |
| Lenovo                               | 25        | 1.14%   |
| Realtek Semiconductor                | 21        | 0.96%   |
| Creative Labs                        | 14        | 0.64%   |
| Logitech                             | 13        | 0.59%   |
| Creative Technology                  | 13        | 0.59%   |
| VIA Technologies                     | 9         | 0.41%   |
| GN Netcom                            | 8         | 0.36%   |
| JMTek                                | 7         | 0.32%   |
| Hewlett-Packard                      | 7         | 0.32%   |
| Plantronics                          | 6         | 0.27%   |
| Dell                                 | 5         | 0.23%   |
| Razer USA                            | 4         | 0.18%   |
| Kingston Technology                  | 4         | 0.18%   |
| GYROCOM C&C                          | 4         | 0.18%   |
| Focusrite-Novation                   | 4         | 0.18%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.14%   |
| DSEA A/S                             | 3         | 0.14%   |
| BEHRINGER International              | 3         | 0.14%   |
| ASUSTek Computer                     | 3         | 0.14%   |
| Trust                                | 2         | 0.09%   |
| RODE Microphones                     | 2         | 0.09%   |
| M-Audio                              | 2         | 0.09%   |
| DigiTech                             | 2         | 0.09%   |
| Conexant Systems                     | 2         | 0.09%   |
| Yealink Network Technology           | 1         | 0.05%   |
| Toshiba                              | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Texas Instruments                    | 1         | 0.05%   |
| Tenx Technology                      | 1         | 0.05%   |
| Syntek                               | 1         | 0.05%   |
| SteelSeries ApS                      | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Samson Technologies                  | 1         | 0.05%   |
| Orbbec 3D Technology International   | 1         | 0.05%   |
| Microsoft                            | 1         | 0.05%   |
| Micro Star International             | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 190       | 7.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 136       | 5.24%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 124       | 4.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 85        | 3.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 82        | 3.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 78        | 3%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 74        | 2.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 71        | 2.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 62        | 2.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 59        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 58        | 2.23%   |
| AMD FCH Azalia Controller                                                                         | 54        | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 53        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 43        | 1.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 39        | 1.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 37        | 1.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 35        | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 1.31%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 34        | 1.31%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 32        | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 32        | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 32        | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 31        | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 31        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 28        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 27        | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 26        | 1%      |
| Intel Broadwell-U Audio Controller                                                                | 26        | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 25        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 0.92%   |
| Intel 200 Series PCH HD Audio                                                                     | 22        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 21        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 20        | 0.77%   |
| Realtek Semiconductor USB Audio                                                                   | 19        | 0.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 18        | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 199       | 19.21%  |
| Kingston            | 173       | 16.7%   |
| SK hynix            | 163       | 15.73%  |
| Elpida              | 118       | 11.39%  |
| Unknown             | 113       | 10.91%  |
| Micron Technology   | 103       | 9.94%   |
| Crucial             | 42        | 4.05%   |
| Corsair             | 26        | 2.51%   |
| Ramaxel Technology  | 23        | 2.22%   |
| A-DATA Technology   | 19        | 1.83%   |
| Patriot             | 18        | 1.74%   |
| Unknown (ABCD)      | 9         | 0.87%   |
| Nanya Technology    | 6         | 0.58%   |
| Transcend           | 5         | 0.48%   |
| G.Skill             | 5         | 0.48%   |
| Unknown             | 2         | 0.19%   |
| Unknown (AB)        | 1         | 0.1%    |
| Toshiba             | 1         | 0.1%    |
| PDPSystems          | 1         | 0.1%    |
| OnBoard             | 1         | 0.1%    |
| Nayna               | 1         | 0.1%    |
| Kingmax             | 1         | 0.1%    |
| Kimtigo             | 1         | 0.1%    |
| H                   | 1         | 0.1%    |
| GOODRAM             | 1         | 0.1%    |
| Golden Empire       | 1         | 0.1%    |
| Apacer              | 1         | 0.1%    |
| AMD                 | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 103       | 9.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.99%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 8         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.54%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.54%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 6         | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.45%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 5         | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.45%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.45%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 5         | 0.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.45%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 5         | 0.45%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 5         | 0.45%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 5         | 0.45%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.36%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 4         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 4         | 0.36%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                  | 4         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.36%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 4         | 0.36%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 391       | 42.97%  |
| DDR3    | 358       | 39.34%  |
| DDR2    | 49        | 5.38%   |
| LPDDR4  | 38        | 4.18%   |
| Unknown | 30        | 3.3%    |
| LPDDR3  | 21        | 2.31%   |
| SDRAM   | 15        | 1.65%   |
| DDR     | 5         | 0.55%   |
| LPDDR5  | 1         | 0.11%   |
| DRAM    | 1         | 0.11%   |
| DDR5    | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 577       | 63.13%  |
| DIMM         | 268       | 29.32%  |
| Row Of Chips | 54        | 5.91%   |
| Chip         | 12        | 1.31%   |
| RIMM         | 2         | 0.22%   |
| Unknown      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 321       | 32.72%  |
| 4096  | 227       | 23.14%  |
| 2048  | 210       | 21.41%  |
| 16384 | 147       | 14.98%  |
| 1024  | 35        | 3.57%   |
| 32768 | 33        | 3.36%   |
| 512   | 4         | 0.41%   |
| 256   | 2         | 0.2%    |
| 6144  | 1         | 0.1%    |
| 3072  | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1333    | 159       | 16.22%  |
| 1600    | 156       | 15.92%  |
| 3200    | 141       | 14.39%  |
| 2667    | 123       | 12.55%  |
| 2400    | 76        | 7.76%   |
| 2133    | 51        | 5.2%    |
| 800     | 33        | 3.37%   |
| 1334    | 30        | 3.06%   |
| 3600    | 22        | 2.24%   |
| Unknown | 20        | 2.04%   |
| 667     | 17        | 1.73%   |
| 1867    | 15        | 1.53%   |
| 4267    | 14        | 1.43%   |
| 1067    | 11        | 1.12%   |
| 3400    | 9         | 0.92%   |
| 3466    | 7         | 0.71%   |
| 3266    | 7         | 0.71%   |
| 2666    | 7         | 0.71%   |
| 1866    | 7         | 0.71%   |
| 1066    | 7         | 0.71%   |
| 3733    | 5         | 0.51%   |
| 3000    | 5         | 0.51%   |
| 4266    | 4         | 0.41%   |
| 4199    | 4         | 0.41%   |
| 3800    | 4         | 0.41%   |
| 2933    | 4         | 0.41%   |
| 975     | 4         | 0.41%   |
| 533     | 4         | 0.41%   |
| 400     | 4         | 0.41%   |
| 3333    | 3         | 0.31%   |
| 8400    | 2         | 0.2%    |
| 4800    | 2         | 0.2%    |
| 4133    | 2         | 0.2%    |
| 3666    | 2         | 0.2%    |
| 3334    | 2         | 0.2%    |
| 2800    | 2         | 0.2%    |
| 2048    | 2         | 0.2%    |
| 1400    | 2         | 0.2%    |
| 6400    | 1         | 0.1%    |
| 6000    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 9         | 28.13%  |
| Hewlett-Packard     | 7         | 21.88%  |
| Samsung Electronics | 5         | 15.63%  |
| Brother Industries  | 5         | 15.63%  |
| Seiko Epson         | 1         | 3.13%   |
| QinHeng Electronics | 1         | 3.13%   |
| Prolific Technology | 1         | 3.13%   |
| Pantum              | 1         | 3.13%   |
| Minolta             | 1         | 3.13%   |
| ICS Advent          | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer      | 3         | 9.09%   |
| Samsung M2070 Series                    | 2         | 6.06%   |
| Seiko Epson L365 Series                 | 1         | 3.03%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 3.03%   |
| Samsung M267x 287x Series               | 1         | 3.03%   |
| Samsung C460 Series                     | 1         | 3.03%   |
| QinHeng CH340S                          | 1         | 3.03%   |
| Prolific PL2305 Parallel Port           | 1         | 3.03%   |
| Pantum P2000                            | 1         | 3.03%   |
| Minolta PagePro 1300W                   | 1         | 3.03%   |
| ICS Advent Parallel Adapter             | 1         | 3.03%   |
| HP Officejet 4500 G510g-m               | 1         | 3.03%   |
| HP Neverstop Laser 100x                 | 1         | 3.03%   |
| HP LaserJet P2014                       | 1         | 3.03%   |
| HP Deskjet 3050 J610 series             | 1         | 3.03%   |
| Canon TS6300 series                     | 1         | 3.03%   |
| Canon PIXMA MX920 Series                | 1         | 3.03%   |
| Canon PIXMA MX720 Series                | 1         | 3.03%   |
| Canon PIXMA MP280                       | 1         | 3.03%   |
| Canon PIXMA MG3500 Series               | 1         | 3.03%   |
| Canon PIXMA MG2500 Series               | 1         | 3.03%   |
| Canon MG5600 series                     | 1         | 3.03%   |
| Canon MF4100 series                     | 1         | 3.03%   |
| Canon LBP3010/LBP3018/LBP3050           | 1         | 3.03%   |
| Canon iP7200 series                     | 1         | 3.03%   |
| Brother MFC-J3930DW                     | 1         | 3.03%   |
| Brother HL-2030 Laser Printer           | 1         | 3.03%   |
| Brother HL-1430 Laser Printer           | 1         | 3.03%   |
| Brother DCP-J105                        | 1         | 3.03%   |
| Brother DCP-1610W                       | 1         | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 6         | 85.71%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25              | 2         | 28.57%  |
| Canon CanoScan LiDE 210             | 2         | 28.57%  |
| Mustek Systems BearPaw 1200 CU Plus | 1         | 14.29%  |
| Canon CanoScan LiDE 200             | 1         | 14.29%  |
| Canon CanoScan LiDE 100             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 230       | 25.03%  |
| Realtek Semiconductor                  | 93        | 10.12%  |
| Acer                                   | 81        | 8.81%   |
| IMC Networks                           | 76        | 8.27%   |
| Microdia                               | 70        | 7.62%   |
| Sunplus Innovation Technology          | 52        | 5.66%   |
| Lite-On Technology                     | 41        | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 4.24%   |
| Quanta                                 | 35        | 3.81%   |
| Suyin                                  | 28        | 3.05%   |
| Syntek                                 | 25        | 2.72%   |
| Logitech                               | 22        | 2.39%   |
| Apple                                  | 12        | 1.31%   |
| Lenovo                                 | 11        | 1.2%    |
| Alcor Micro                            | 11        | 1.2%    |
| Samsung Electronics                    | 10        | 1.09%   |
| Ricoh                                  | 10        | 1.09%   |
| KYE Systems (Mouse Systems)            | 10        | 1.09%   |
| Creative Technology                    | 8         | 0.87%   |
| Z-Star Microelectronics                | 7         | 0.76%   |
| Microsoft                              | 7         | 0.76%   |
| GEMBIRD                                | 5         | 0.54%   |
| Unknown                                | 4         | 0.44%   |
| Primax Electronics                     | 4         | 0.44%   |
| Generalplus Technology                 | 3         | 0.33%   |
| Sonix Technology                       | 2         | 0.22%   |
| Luxvisions Innotech Limited            | 2         | 0.22%   |
| Intel                                  | 2         | 0.22%   |
| Hewlett-Packard                        | 2         | 0.22%   |
| YGTek                                  | 1         | 0.11%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Smartronix                             | 1         | 0.11%   |
| Silicon Motion                         | 1         | 0.11%   |
| Ruision                                | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| Orbbec 3D Technology International     | 1         | 0.11%   |
| Nokia Mobile Phones                    | 1         | 0.11%   |
| MacroSilicon                           | 1         | 0.11%   |
| Goodong Industry                       | 1         | 0.11%   |
| Genesys Logic                          | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 59        | 6.35%   |
| IMC Networks Integrated Camera                                  | 34        | 3.66%   |
| Realtek Integrated_Webcam_HD                                    | 33        | 3.55%   |
| Microdia Integrated_Webcam_HD                                   | 31        | 3.34%   |
| Chicony HP HD Camera                                            | 23        | 2.48%   |
| Chicony HD WebCam                                               | 23        | 2.48%   |
| Acer Lenovo EasyCamera                                          | 20        | 2.15%   |
| Lite-On HP HD Camera                                            | 18        | 1.94%   |
| Acer Integrated Camera                                          | 18        | 1.94%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 15        | 1.61%   |
| Realtek USB Camera                                              | 13        | 1.4%    |
| Chicony Integrated Camera (1280x720@30)                         | 13        | 1.4%    |
| Sunplus Integrated_Webcam_HD                                    | 12        | 1.29%   |
| Lite-On Integrated Camera                                       | 11        | 1.18%   |
| Syntek Integrated Camera                                        | 10        | 1.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 10        | 1.08%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 10        | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 9         | 0.97%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 9         | 0.97%   |
| Syntek Lenovo EasyCamera                                        | 8         | 0.86%   |
| Realtek Integrated Webcam HD                                    | 8         | 0.86%   |
| Quanta HP HD Camera                                             | 8         | 0.86%   |
| Quanta HD User Facing                                           | 8         | 0.86%   |
| Microdia Integrated Webcam                                      | 8         | 0.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 8         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 8         | 0.86%   |
| Acer SunplusIT Integrated Camera                                | 8         | 0.86%   |
| Logitech Webcam C270                                            | 7         | 0.75%   |
| Lenovo Integrated Webcam                                        | 7         | 0.75%   |
| Chicony Lenovo EasyCamera                                       | 7         | 0.75%   |
| Acer EasyCamera                                                 | 7         | 0.75%   |
| Sunplus Laptop Integrated WebCam HD                             | 6         | 0.65%   |
| Sunplus HD WebCam                                               | 6         | 0.65%   |
| Sunplus Asus Webcam                                             | 6         | 0.65%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 6         | 0.65%   |
| Quanta HP Wide Vision HD Camera                                 | 6         | 0.65%   |
| Creative Live! Cam Sync HD [VF0770]                             | 6         | 0.65%   |
| Chicony HP HD Webcam                                            | 6         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.65%   |
| Alcor Micro USB 2.0 Camera                                      | 6         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 87        | 33.08%  |
| Synaptics                  | 87        | 33.08%  |
| Shenzhen Goodix Technology | 31        | 11.79%  |
| AuthenTec                  | 26        | 9.89%   |
| Elan Microelectronics      | 13        | 4.94%   |
| Upek                       | 12        | 4.56%   |
| LighTuning Technology      | 5         | 1.9%    |
| Microsoft                  | 1         | 0.38%   |
| Dell                       | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 9.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 8.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 6.84%   |
| Unknown                                                                    | 18        | 6.84%   |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 6.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 4.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 4.56%   |
| AuthenTec AES2810                                                          | 11        | 4.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 3.8%    |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.42%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.42%   |
| Validity Sensors VFS491                                                    | 8         | 3.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.66%   |
| AuthenTec AES1600                                                          | 7         | 2.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.9%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.9%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.9%    |
| Synaptics  WBDI                                                            | 4         | 1.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.52%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.14%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.14%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.76%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.38%   |
| Synaptics WBDI Device                                                      | 1         | 0.38%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.38%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.38%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.38%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 52        | 50%     |
| Alcor Micro               | 29        | 27.88%  |
| O2 Micro                  | 9         | 8.65%   |
| Lenovo                    | 5         | 4.81%   |
| SCM Microsystems          | 2         | 1.92%   |
| Aladdin Knowledge Systems | 2         | 1.92%   |
| Upek                      | 1         | 0.96%   |
| Realtek Semiconductor     | 1         | 0.96%   |
| Purism, SPC               | 1         | 0.96%   |
| OmniKey                   | 1         | 0.96%   |
| Fujitsu Siemens Computers | 1         | 0.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 27.88%  |
| Broadcom 58200                                                               | 16        | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 13.46%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 10.58%  |
| Broadcom 5880                                                                | 11        | 10.58%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.81%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.92%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 0.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.96%   |
| Purism, SPC Librem Key                                                       | 1         | 0.96%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.96%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.96%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1144      | 68.14%  |
| 1     | 411       | 24.48%  |
| 2     | 96        | 5.72%   |
| 3     | 20        | 1.19%   |
| 4     | 5         | 0.3%    |
| 5     | 3         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 258       | 38.57%  |
| Graphics card            | 122       | 18.24%  |
| Chipcard                 | 90        | 13.45%  |
| Net/wireless             | 49        | 7.32%   |
| Multimedia controller    | 33        | 4.93%   |
| Communication controller | 20        | 2.99%   |
| Storage                  | 16        | 2.39%   |
| Bluetooth                | 15        | 2.24%   |
| Camera                   | 14        | 2.09%   |
| Unassigned class         | 9         | 1.35%   |
| Net/ethernet             | 9         | 1.35%   |
| Sound                    | 8         | 1.2%    |
| Card reader              | 7         | 1.05%   |
| Modem                    | 6         | 0.9%    |
| Flash memory             | 6         | 0.9%    |
| Network                  | 3         | 0.45%   |
| Storage/raid             | 1         | 0.15%   |
| Storage/ide              | 1         | 0.15%   |
| Storage/ata              | 1         | 0.15%   |
| Dvb card                 | 1         | 0.15%   |

