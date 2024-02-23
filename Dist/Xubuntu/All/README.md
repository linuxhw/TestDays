Xubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

Total: 6799

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A10M              | Notebook    | [22f3c2e58e](https://linux-hardware.org/?probe=22f3c2e58e) | Feb 02, 2024 |
| INP           | i1000BTS                    | Desktop     | [3148738295](https://linux-hardware.org/?probe=3148738295) | Feb 02, 2024 |
| Acer          | NC-F5-771G-72XY             | Notebook    | [2f4c6fbadb](https://linux-hardware.org/?probe=2f4c6fbadb) | Feb 02, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [c22226fe6f](https://linux-hardware.org/?probe=c22226fe6f) | Feb 01, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [920b1ecb34](https://linux-hardware.org/?probe=920b1ecb34) | Jan 31, 2024 |
| Acer          | Aspire 5735                 | Notebook    | [365fd9fe4d](https://linux-hardware.org/?probe=365fd9fe4d) | Jan 31, 2024 |
| Acer          | Aspire 5735                 | Notebook    | [bed38c72c8](https://linux-hardware.org/?probe=bed38c72c8) | Jan 31, 2024 |
| HP            | Pavilion g6                 | Notebook    | [7f9863aaa2](https://linux-hardware.org/?probe=7f9863aaa2) | Jan 31, 2024 |
| Dell          | 06D7TR A01                  | Desktop     | [34d3eaffac](https://linux-hardware.org/?probe=34d3eaffac) | Jan 31, 2024 |
| Lenovo        | ThinkPad T570 20HAS0NU00    | Notebook    | [39f3b9fb56](https://linux-hardware.org/?probe=39f3b9fb56) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [ad26dae776](https://linux-hardware.org/?probe=ad26dae776) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [bc4394a85f](https://linux-hardware.org/?probe=bc4394a85f) | Jan 30, 2024 |
| HP            | 859C                        | Desktop     | [866ac7f0ed](https://linux-hardware.org/?probe=866ac7f0ed) | Jan 30, 2024 |
| Dell          | Latitude 5510               | Notebook    | [4abbee3451](https://linux-hardware.org/?probe=4abbee3451) | Jan 30, 2024 |
| Packard Be... | IXTREME M5800               | Desktop     | [f31eaf65b4](https://linux-hardware.org/?probe=f31eaf65b4) | Jan 29, 2024 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [737d54004b](https://linux-hardware.org/?probe=737d54004b) | Jan 29, 2024 |
| Dell          | Latitude 5511               | Notebook    | [40fad497db](https://linux-hardware.org/?probe=40fad497db) | Jan 29, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [72dee51fa2](https://linux-hardware.org/?probe=72dee51fa2) | Jan 29, 2024 |
| Packard Be... | IXTREME M5800               | Desktop     | [8d8f99feb9](https://linux-hardware.org/?probe=8d8f99feb9) | Jan 28, 2024 |
| Lenovo        | V560                        | Notebook    | [a0dbd66d53](https://linux-hardware.org/?probe=a0dbd66d53) | Jan 28, 2024 |
| ASUSTek       | X205TA                      | Notebook    | [83899dcb83](https://linux-hardware.org/?probe=83899dcb83) | Jan 27, 2024 |
| Lenovo        | ThinkPad T400 6474AW6       | Notebook    | [0ddfcaf599](https://linux-hardware.org/?probe=0ddfcaf599) | Jan 27, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [c85674acbd](https://linux-hardware.org/?probe=c85674acbd) | Jan 26, 2024 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [0948177334](https://linux-hardware.org/?probe=0948177334) | Jan 26, 2024 |
| Toshiba       | Satellite L300              | Notebook    | [127697d4f1](https://linux-hardware.org/?probe=127697d4f1) | Jan 26, 2024 |
| Toshiba       | Satellite L300              | Notebook    | [63be13a245](https://linux-hardware.org/?probe=63be13a245) | Jan 26, 2024 |
| PC Special... | NH5x_7xDPx                  | Notebook    | [0f28a5d513](https://linux-hardware.org/?probe=0f28a5d513) | Jan 26, 2024 |
| Shuttle       | NC40U                       | Desktop     | [893dcee1f0](https://linux-hardware.org/?probe=893dcee1f0) | Jan 26, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [38a14a6e3b](https://linux-hardware.org/?probe=38a14a6e3b) | Jan 26, 2024 |
| Gigabyte      | C1037UN                     | Desktop     | [7d3a3e3ca9](https://linux-hardware.org/?probe=7d3a3e3ca9) | Jan 26, 2024 |
| Intel         | DB75EN                      | Desktop     | [41cea41d1e](https://linux-hardware.org/?probe=41cea41d1e) | Jan 26, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [51346a4084](https://linux-hardware.org/?probe=51346a4084) | Jan 25, 2024 |
| Dell          | Latitude 7340               | Notebook    | [880054b099](https://linux-hardware.org/?probe=880054b099) | Jan 25, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [fe08501f76](https://linux-hardware.org/?probe=fe08501f76) | Jan 24, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [961ba7a8a2](https://linux-hardware.org/?probe=961ba7a8a2) | Jan 24, 2024 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [5a5ec0016f](https://linux-hardware.org/?probe=5a5ec0016f) | Jan 24, 2024 |
| Gigabyte      | 8IPE1000P-G                 | Desktop     | [052ba36722](https://linux-hardware.org/?probe=052ba36722) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d11d529522](https://linux-hardware.org/?probe=d11d529522) | Jan 23, 2024 |
| Gigabyte      | C1037UN                     | Desktop     | [344699bbb2](https://linux-hardware.org/?probe=344699bbb2) | Jan 23, 2024 |
| ASRock        | A520M-HVS                   | Desktop     | [87e6c23293](https://linux-hardware.org/?probe=87e6c23293) | Jan 23, 2024 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [545e0a6896](https://linux-hardware.org/?probe=545e0a6896) | Jan 23, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [dc061193f2](https://linux-hardware.org/?probe=dc061193f2) | Jan 22, 2024 |
| AOpen         | D2644 S26361-D2644          | Desktop     | [f45673bd59](https://linux-hardware.org/?probe=f45673bd59) | Jan 22, 2024 |
| HP            | Pavilion dv6                | Notebook    | [ac628c20c7](https://linux-hardware.org/?probe=ac628c20c7) | Jan 22, 2024 |
| HP            | Pavilion dv6                | Notebook    | [6d29e8c44e](https://linux-hardware.org/?probe=6d29e8c44e) | Jan 22, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b6fa224856](https://linux-hardware.org/?probe=b6fa224856) | Jan 21, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4254242157](https://linux-hardware.org/?probe=4254242157) | Jan 21, 2024 |
| ASUSTek       | T100HAN                     | Notebook    | [02f115dc2a](https://linux-hardware.org/?probe=02f115dc2a) | Jan 21, 2024 |
| Intel         | DB75EN                      | Desktop     | [f639799c41](https://linux-hardware.org/?probe=f639799c41) | Jan 21, 2024 |
| Lenovo        | 1037 NO DPK                 | Server      | [da53a6a2c0](https://linux-hardware.org/?probe=da53a6a2c0) | Jan 20, 2024 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [22c44fb878](https://linux-hardware.org/?probe=22c44fb878) | Jan 19, 2024 |
| ASUSTek       | K55VM                       | Notebook    | [a684c7f5fc](https://linux-hardware.org/?probe=a684c7f5fc) | Jan 19, 2024 |
| Dell          | 0F5C5X A00                  | Desktop     | [f320dddb34](https://linux-hardware.org/?probe=f320dddb34) | Jan 19, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [c7872b9640](https://linux-hardware.org/?probe=c7872b9640) | Jan 18, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [15f0af587b](https://linux-hardware.org/?probe=15f0af587b) | Jan 17, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [4b39b1cbe0](https://linux-hardware.org/?probe=4b39b1cbe0) | Jan 17, 2024 |
| ASUSTek       | PN40                        | Mini pc     | [f7cb91c837](https://linux-hardware.org/?probe=f7cb91c837) | Jan 17, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [bcbb9c099f](https://linux-hardware.org/?probe=bcbb9c099f) | Jan 16, 2024 |
| ASRock        | E350M1                      | Desktop     | [7fe46e5672](https://linux-hardware.org/?probe=7fe46e5672) | Jan 15, 2024 |
| HP            | Compaq Presario CQ60        | Notebook    | [fd48d4e0d2](https://linux-hardware.org/?probe=fd48d4e0d2) | Jan 15, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6d2801d1d8](https://linux-hardware.org/?probe=6d2801d1d8) | Jan 14, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [77032de9df](https://linux-hardware.org/?probe=77032de9df) | Jan 14, 2024 |
| ASUSTek       | P8H61-M2 USB3               | Desktop     | [705185dd25](https://linux-hardware.org/?probe=705185dd25) | Jan 13, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [5dacf75c7d](https://linux-hardware.org/?probe=5dacf75c7d) | Jan 12, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [1ad7806df7](https://linux-hardware.org/?probe=1ad7806df7) | Jan 12, 2024 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b6d8783c20](https://linux-hardware.org/?probe=b6d8783c20) | Jan 12, 2024 |
| ASUSTek       | K55VM                       | Notebook    | [99003258ce](https://linux-hardware.org/?probe=99003258ce) | Jan 11, 2024 |
| Dell          | 0T0MHW A03                  | Desktop     | [2ad439d95f](https://linux-hardware.org/?probe=2ad439d95f) | Jan 11, 2024 |
| Gigazone      | X107(B-B)                   | Notebook    | [a72cbb0097](https://linux-hardware.org/?probe=a72cbb0097) | Jan 10, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [ce397f675e](https://linux-hardware.org/?probe=ce397f675e) | Jan 10, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [f02310e366](https://linux-hardware.org/?probe=f02310e366) | Jan 10, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [60423ae46b](https://linux-hardware.org/?probe=60423ae46b) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [0e47261be0](https://linux-hardware.org/?probe=0e47261be0) | Jan 09, 2024 |
| Gigazone      | X107(B-B)                   | Notebook    | [54085fcb32](https://linux-hardware.org/?probe=54085fcb32) | Jan 09, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [1834cfc875](https://linux-hardware.org/?probe=1834cfc875) | Jan 09, 2024 |
| ASRock        | N68-S3 FX                   | Desktop     | [ce413f7140](https://linux-hardware.org/?probe=ce413f7140) | Jan 09, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e72b2cebd3](https://linux-hardware.org/?probe=e72b2cebd3) | Jan 08, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [511526bcf7](https://linux-hardware.org/?probe=511526bcf7) | Jan 08, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [59adb7b85b](https://linux-hardware.org/?probe=59adb7b85b) | Jan 08, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [9e3cd173d7](https://linux-hardware.org/?probe=9e3cd173d7) | Jan 08, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [22ef91bad9](https://linux-hardware.org/?probe=22ef91bad9) | Jan 08, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [00ef8580ff](https://linux-hardware.org/?probe=00ef8580ff) | Jan 07, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | IdeaPad 510S-13ISK 80SJ     | Notebook    | [90fe273da6](https://linux-hardware.org/?probe=90fe273da6) | Jan 06, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [40b853c9b9](https://linux-hardware.org/?probe=40b853c9b9) | Jan 06, 2024 |
| Dell          | Inspiron 1501               | Notebook    | [65d521ef7c](https://linux-hardware.org/?probe=65d521ef7c) | Jan 06, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [d138fd288d](https://linux-hardware.org/?probe=d138fd288d) | Jan 06, 2024 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [e131bcc2a6](https://linux-hardware.org/?probe=e131bcc2a6) | Jan 06, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [753ed1e625](https://linux-hardware.org/?probe=753ed1e625) | Jan 05, 2024 |
| Acer          | Aspire A517-52              | Notebook    | [610817c6c9](https://linux-hardware.org/?probe=610817c6c9) | Jan 05, 2024 |
| Gigabyte      | P55-UD3R                    | Desktop     | [44658131d3](https://linux-hardware.org/?probe=44658131d3) | Jan 05, 2024 |
| Dell          | 0P658H A05                  | Server      | [74f28d91a3](https://linux-hardware.org/?probe=74f28d91a3) | Jan 05, 2024 |
| HP            | Pavilion dv7                | Notebook    | [dc31f854de](https://linux-hardware.org/?probe=dc31f854de) | Jan 04, 2024 |
| Dell          | Precision M6800             | Notebook    | [5049c54004](https://linux-hardware.org/?probe=5049c54004) | Jan 04, 2024 |
| ASUSTek       | X540SAA                     | Notebook    | [179249edef](https://linux-hardware.org/?probe=179249edef) | Jan 03, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [d01ee5a226](https://linux-hardware.org/?probe=d01ee5a226) | Jan 02, 2024 |
| Lenovo        | ThinkPad X260 20F5S0KE00    | Notebook    | [08d2a7a982](https://linux-hardware.org/?probe=08d2a7a982) | Jan 01, 2024 |
| KunPengDia... | Unknown                     | Desktop     | [574df96e17](https://linux-hardware.org/?probe=574df96e17) | Jan 01, 2024 |
| Dell          | 0P658H A05                  | Server      | [1ae3680481](https://linux-hardware.org/?probe=1ae3680481) | Jan 01, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [08f5647277](https://linux-hardware.org/?probe=08f5647277) | Dec 31, 2023 |
| Foxconn       | Irvine HP P/N               | Desktop     | [cd125aca3c](https://linux-hardware.org/?probe=cd125aca3c) | Dec 29, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [2b8b39d335](https://linux-hardware.org/?probe=2b8b39d335) | Dec 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f73670f10](https://linux-hardware.org/?probe=1f73670f10) | Dec 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| HP            | ProBook 6570b               | Notebook    | [61f91864e5](https://linux-hardware.org/?probe=61f91864e5) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [38b1c283b4](https://linux-hardware.org/?probe=38b1c283b4) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [6b4237a1ea](https://linux-hardware.org/?probe=6b4237a1ea) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [408e19e1f2](https://linux-hardware.org/?probe=408e19e1f2) | Dec 26, 2023 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6bf30b2ec5](https://linux-hardware.org/?probe=6bf30b2ec5) | Dec 26, 2023 |
| HP            | Compaq nx7400 (RH609ES#A... | Notebook    | [6a6b1d3722](https://linux-hardware.org/?probe=6a6b1d3722) | Dec 26, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [1a5a81980b](https://linux-hardware.org/?probe=1a5a81980b) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [14d453985d](https://linux-hardware.org/?probe=14d453985d) | Dec 25, 2023 |
| ASUSTek       | X201EP                      | Notebook    | [944a54b7f4](https://linux-hardware.org/?probe=944a54b7f4) | Dec 25, 2023 |
| Intel         | DB75EN                      | Desktop     | [c2c820f0d9](https://linux-hardware.org/?probe=c2c820f0d9) | Dec 25, 2023 |
| Intel         | DB75EN                      | Desktop     | [6ec790f3fc](https://linux-hardware.org/?probe=6ec790f3fc) | Dec 24, 2023 |
| ASRock        | Q1900DC-ITX                 | Desktop     | [ee59bde7c9](https://linux-hardware.org/?probe=ee59bde7c9) | Dec 23, 2023 |
| ASRock        | Q1900DC-ITX                 | Desktop     | [9733217ad2](https://linux-hardware.org/?probe=9733217ad2) | Dec 23, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [039823b939](https://linux-hardware.org/?probe=039823b939) | Dec 23, 2023 |
| eMachines     | E527                        | Notebook    | [cf5b096be7](https://linux-hardware.org/?probe=cf5b096be7) | Dec 22, 2023 |
| Dell          | Latitude E5510              | Notebook    | [92074a5231](https://linux-hardware.org/?probe=92074a5231) | Dec 22, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [741ad16651](https://linux-hardware.org/?probe=741ad16651) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [07a7762b25](https://linux-hardware.org/?probe=07a7762b25) | Dec 21, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [16a8e6f875](https://linux-hardware.org/?probe=16a8e6f875) | Dec 21, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c5d51ca43d](https://linux-hardware.org/?probe=c5d51ca43d) | Dec 21, 2023 |
| Sony          | VGN-NW270F                  | Notebook    | [eee640a54d](https://linux-hardware.org/?probe=eee640a54d) | Dec 20, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [ee1a222677](https://linux-hardware.org/?probe=ee1a222677) | Dec 20, 2023 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [6b0274e802](https://linux-hardware.org/?probe=6b0274e802) | Dec 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [4cc379dfbd](https://linux-hardware.org/?probe=4cc379dfbd) | Dec 19, 2023 |
| HP            | Notebook                    | Notebook    | [31d6fc4280](https://linux-hardware.org/?probe=31d6fc4280) | Dec 19, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [c7aaf87bcd](https://linux-hardware.org/?probe=c7aaf87bcd) | Dec 17, 2023 |
| Unknown       | YL-J1900-V1                 | Desktop     | [257144f3a3](https://linux-hardware.org/?probe=257144f3a3) | Dec 17, 2023 |
| Unknown       | YL-J1900-V1                 | Desktop     | [c14e43b65f](https://linux-hardware.org/?probe=c14e43b65f) | Dec 17, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [06556bd61a](https://linux-hardware.org/?probe=06556bd61a) | Dec 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [ce0e0e1bc1](https://linux-hardware.org/?probe=ce0e0e1bc1) | Dec 17, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f0ed04c975](https://linux-hardware.org/?probe=f0ed04c975) | Dec 16, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6a2633018c](https://linux-hardware.org/?probe=6a2633018c) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [e7ca2f3a6e](https://linux-hardware.org/?probe=e7ca2f3a6e) | Dec 14, 2023 |
| HP            | 212B                        | Desktop     | [1ce8b8d929](https://linux-hardware.org/?probe=1ce8b8d929) | Dec 14, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [35a6370b07](https://linux-hardware.org/?probe=35a6370b07) | Dec 14, 2023 |
| Intel         | H310 Series                 | Desktop     | [9565b22822](https://linux-hardware.org/?probe=9565b22822) | Dec 13, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [2204183295](https://linux-hardware.org/?probe=2204183295) | Dec 12, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [63cf57fa53](https://linux-hardware.org/?probe=63cf57fa53) | Dec 12, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [10a266d0ff](https://linux-hardware.org/?probe=10a266d0ff) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [e223660e23](https://linux-hardware.org/?probe=e223660e23) | Dec 11, 2023 |
| Lenovo        | ThinkPad T530 2429W1E       | Notebook    | [02a4811e8d](https://linux-hardware.org/?probe=02a4811e8d) | Dec 10, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6c3916c3fa](https://linux-hardware.org/?probe=6c3916c3fa) | Dec 10, 2023 |
| HP            | ProBook 4535s               | Notebook    | [9005c587a8](https://linux-hardware.org/?probe=9005c587a8) | Dec 10, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [ba43863b29](https://linux-hardware.org/?probe=ba43863b29) | Dec 09, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [7907f73ee0](https://linux-hardware.org/?probe=7907f73ee0) | Dec 09, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [93672594de](https://linux-hardware.org/?probe=93672594de) | Dec 09, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [cc2b6e8b40](https://linux-hardware.org/?probe=cc2b6e8b40) | Dec 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [74440ebfad](https://linux-hardware.org/?probe=74440ebfad) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [beaa75c727](https://linux-hardware.org/?probe=beaa75c727) | Dec 06, 2023 |
| Intel         | STK1AW32SC H91596-302       | Desktop     | [9dbc61e045](https://linux-hardware.org/?probe=9dbc61e045) | Dec 05, 2023 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [dfc6e4c96b](https://linux-hardware.org/?probe=dfc6e4c96b) | Dec 05, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [0c680c33ec](https://linux-hardware.org/?probe=0c680c33ec) | Dec 05, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [7b1c8f906b](https://linux-hardware.org/?probe=7b1c8f906b) | Dec 04, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30fc1de681](https://linux-hardware.org/?probe=30fc1de681) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [203357a4dd](https://linux-hardware.org/?probe=203357a4dd) | Dec 03, 2023 |
| Intel         | DB75EN                      | Desktop     | [15f11719b5](https://linux-hardware.org/?probe=15f11719b5) | Dec 02, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [7d88a4ceef](https://linux-hardware.org/?probe=7d88a4ceef) | Dec 01, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c8e6af0346](https://linux-hardware.org/?probe=c8e6af0346) | Nov 30, 2023 |
| Dell          | Latitude 7370               | Notebook    | [356b2e9e31](https://linux-hardware.org/?probe=356b2e9e31) | Nov 30, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [7c7825a9c9](https://linux-hardware.org/?probe=7c7825a9c9) | Nov 30, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [5e8be973c6](https://linux-hardware.org/?probe=5e8be973c6) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [2c9b3f229e](https://linux-hardware.org/?probe=2c9b3f229e) | Nov 29, 2023 |
| Unknown       | HX90                        | Desktop     | [54a2eb227b](https://linux-hardware.org/?probe=54a2eb227b) | Nov 29, 2023 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [aedaf10575](https://linux-hardware.org/?probe=aedaf10575) | Nov 27, 2023 |
| Sony          | VGN-NS12M_W                 | Notebook    | [c1400d8699](https://linux-hardware.org/?probe=c1400d8699) | Nov 27, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [c179f18d96](https://linux-hardware.org/?probe=c179f18d96) | Nov 27, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [25fd880050](https://linux-hardware.org/?probe=25fd880050) | Nov 26, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [4b14c830c0](https://linux-hardware.org/?probe=4b14c830c0) | Nov 26, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [7130842b5a](https://linux-hardware.org/?probe=7130842b5a) | Nov 26, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [214c1cc15b](https://linux-hardware.org/?probe=214c1cc15b) | Nov 25, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a59b920838](https://linux-hardware.org/?probe=a59b920838) | Nov 24, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d3697eee2c](https://linux-hardware.org/?probe=d3697eee2c) | Nov 24, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [8edef55308](https://linux-hardware.org/?probe=8edef55308) | Nov 24, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [78748bcf50](https://linux-hardware.org/?probe=78748bcf50) | Nov 24, 2023 |
| Itautec       | SM 3322 SM-3322 Padrao 0... | Desktop     | [2cf2808a7f](https://linux-hardware.org/?probe=2cf2808a7f) | Nov 23, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [0edf2befff](https://linux-hardware.org/?probe=0edf2befff) | Nov 21, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [de97cb0d6f](https://linux-hardware.org/?probe=de97cb0d6f) | Nov 21, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cc2aa981d3](https://linux-hardware.org/?probe=cc2aa981d3) | Nov 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [b6cfe558cb](https://linux-hardware.org/?probe=b6cfe558cb) | Nov 21, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9701d268e8](https://linux-hardware.org/?probe=9701d268e8) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [2b84d65d1a](https://linux-hardware.org/?probe=2b84d65d1a) | Nov 20, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [d5ccc9cfc9](https://linux-hardware.org/?probe=d5ccc9cfc9) | Nov 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [b81902d8d5](https://linux-hardware.org/?probe=b81902d8d5) | Nov 20, 2023 |
| HP            | ProBook 6570b               | Notebook    | [39ba398a11](https://linux-hardware.org/?probe=39ba398a11) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [17c2f68bc7](https://linux-hardware.org/?probe=17c2f68bc7) | Nov 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [078f4227bd](https://linux-hardware.org/?probe=078f4227bd) | Nov 19, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [e5a62b2035](https://linux-hardware.org/?probe=e5a62b2035) | Nov 18, 2023 |
| HP            | 21B4 A01                    | Desktop     | [73a4740b8f](https://linux-hardware.org/?probe=73a4740b8f) | Nov 18, 2023 |
| Acer          | EG43LMK                     | Desktop     | [bc1ab38f8f](https://linux-hardware.org/?probe=bc1ab38f8f) | Nov 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [b8bca4e3cd](https://linux-hardware.org/?probe=b8bca4e3cd) | Nov 18, 2023 |
| SiComputer    | Nauta 01E                   | Notebook    | [1631e065bd](https://linux-hardware.org/?probe=1631e065bd) | Nov 17, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [8a23e4f586](https://linux-hardware.org/?probe=8a23e4f586) | Nov 16, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [7fabbf9cb1](https://linux-hardware.org/?probe=7fabbf9cb1) | Nov 16, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [6401616423](https://linux-hardware.org/?probe=6401616423) | Nov 16, 2023 |
| OrangePi      | 4 LTS                       | Soc         | [a770db570a](https://linux-hardware.org/?probe=a770db570a) | Nov 15, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [6806c7c828](https://linux-hardware.org/?probe=6806c7c828) | Nov 15, 2023 |
| Lenovo        | IdeaPad S300 9803           | Notebook    | [21f7433934](https://linux-hardware.org/?probe=21f7433934) | Nov 15, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [6560a26a12](https://linux-hardware.org/?probe=6560a26a12) | Nov 15, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [a05c294e1e](https://linux-hardware.org/?probe=a05c294e1e) | Nov 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS2P703    | Notebook    | [b15506a2b9](https://linux-hardware.org/?probe=b15506a2b9) | Nov 14, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [e592b6bf5d](https://linux-hardware.org/?probe=e592b6bf5d) | Nov 13, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [79b891b4df](https://linux-hardware.org/?probe=79b891b4df) | Nov 13, 2023 |
| Dell          | Latitude E5420              | Notebook    | [dc67f70b3b](https://linux-hardware.org/?probe=dc67f70b3b) | Nov 13, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [7deb21f5d9](https://linux-hardware.org/?probe=7deb21f5d9) | Nov 13, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [aefe53a7b6](https://linux-hardware.org/?probe=aefe53a7b6) | Nov 13, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [6c532c337f](https://linux-hardware.org/?probe=6c532c337f) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [ec22cbd65c](https://linux-hardware.org/?probe=ec22cbd65c) | Nov 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [450bb23de1](https://linux-hardware.org/?probe=450bb23de1) | Nov 10, 2023 |
| Lenovo        | ThinkPad E470 20H1006NHV    | Notebook    | [a43db58ab7](https://linux-hardware.org/?probe=a43db58ab7) | Nov 10, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [238b7326f1](https://linux-hardware.org/?probe=238b7326f1) | Nov 10, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [941b37816d](https://linux-hardware.org/?probe=941b37816d) | Nov 10, 2023 |
| Khadas        | VIM2                        | Soc         | [3db877cd01](https://linux-hardware.org/?probe=3db877cd01) | Nov 09, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [c1a263f3b5](https://linux-hardware.org/?probe=c1a263f3b5) | Nov 08, 2023 |
| OrangePi      | 4 LTS                       | Soc         | [04e71993b5](https://linux-hardware.org/?probe=04e71993b5) | Nov 08, 2023 |
| Dell          | Latitude 9420               | Convertible | [772d54e7c0](https://linux-hardware.org/?probe=772d54e7c0) | Nov 08, 2023 |
| ASUSTek       | P5K                         | Desktop     | [4870e13f93](https://linux-hardware.org/?probe=4870e13f93) | Nov 08, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Medion        | Crawler E25                 | Notebook    | [945026c1b8](https://linux-hardware.org/?probe=945026c1b8) | Nov 07, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [d918aae63e](https://linux-hardware.org/?probe=d918aae63e) | Nov 06, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [de892702f8](https://linux-hardware.org/?probe=de892702f8) | Nov 05, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5c4543cc31](https://linux-hardware.org/?probe=5c4543cc31) | Nov 05, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | Notebook    | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [10b1460f7a](https://linux-hardware.org/?probe=10b1460f7a) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| HP            | Presario C500 (GF849EA#A... | Notebook    | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [51c94bc00f](https://linux-hardware.org/?probe=51c94bc00f) | Nov 03, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [80fb26e63a](https://linux-hardware.org/?probe=80fb26e63a) | Nov 03, 2023 |
| Acer          | Predator PH717-71           | Notebook    | [a72ab29450](https://linux-hardware.org/?probe=a72ab29450) | Nov 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a871f012a2](https://linux-hardware.org/?probe=a871f012a2) | Nov 02, 2023 |
| HP            | Presario CQ57               | Notebook    | [4874030c75](https://linux-hardware.org/?probe=4874030c75) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [a2a8295797](https://linux-hardware.org/?probe=a2a8295797) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [0d49a75fe1](https://linux-hardware.org/?probe=0d49a75fe1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [cbe947aefc](https://linux-hardware.org/?probe=cbe947aefc) | Nov 01, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [ad5e8f91e5](https://linux-hardware.org/?probe=ad5e8f91e5) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [cd9e941307](https://linux-hardware.org/?probe=cd9e941307) | Nov 01, 2023 |
| Lenovo        | IdeaPad S300 9803           | Notebook    | [543dfc0b4e](https://linux-hardware.org/?probe=543dfc0b4e) | Oct 31, 2023 |
| Medion        | E3223                       | Convertible | [e35701b198](https://linux-hardware.org/?probe=e35701b198) | Oct 31, 2023 |
| HP            | Presario C500 (GF849EA#A... | Notebook    | [580f4bdb18](https://linux-hardware.org/?probe=580f4bdb18) | Oct 31, 2023 |
| AMI           | Intel                       | Notebook    | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| ASUSTek       | K53E                        | Notebook    | [8b7c83e9d7](https://linux-hardware.org/?probe=8b7c83e9d7) | Oct 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e06f6c5888](https://linux-hardware.org/?probe=e06f6c5888) | Oct 30, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [6273e445bd](https://linux-hardware.org/?probe=6273e445bd) | Oct 30, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [dd2a52ab8f](https://linux-hardware.org/?probe=dd2a52ab8f) | Oct 30, 2023 |
| OrangePi      | Zero3                       | Soc         | [6d3ecf003f](https://linux-hardware.org/?probe=6d3ecf003f) | Oct 29, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9c77415bfc](https://linux-hardware.org/?probe=9c77415bfc) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6a8554304e](https://linux-hardware.org/?probe=6a8554304e) | Oct 27, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [291bf42f9d](https://linux-hardware.org/?probe=291bf42f9d) | Oct 27, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [2c88e089bb](https://linux-hardware.org/?probe=2c88e089bb) | Oct 27, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | Notebook    | [413cefff03](https://linux-hardware.org/?probe=413cefff03) | Oct 26, 2023 |
| HP            | Presario CQ57               | Notebook    | [a3f31b427e](https://linux-hardware.org/?probe=a3f31b427e) | Oct 26, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [1d3f58a610](https://linux-hardware.org/?probe=1d3f58a610) | Oct 25, 2023 |
| Gigabyte      | 965P-DS3                    | Desktop     | [b33d6b8a3c](https://linux-hardware.org/?probe=b33d6b8a3c) | Oct 24, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [15ac9c0529](https://linux-hardware.org/?probe=15ac9c0529) | Oct 24, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [1f7af8af3e](https://linux-hardware.org/?probe=1f7af8af3e) | Oct 23, 2023 |
| Dell          | Latitude 3490               | Notebook    | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Dell          | 0XKH0D A02                  | Desktop     | [bba36c01cf](https://linux-hardware.org/?probe=bba36c01cf) | Oct 19, 2023 |
| HP            | 0A68h                       | Desktop     | [376c3156a9](https://linux-hardware.org/?probe=376c3156a9) | Oct 19, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | Notebook    | [7be90734f6](https://linux-hardware.org/?probe=7be90734f6) | Oct 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [cf4a419a07](https://linux-hardware.org/?probe=cf4a419a07) | Oct 17, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [4a5c5417b7](https://linux-hardware.org/?probe=4a5c5417b7) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [e657535210](https://linux-hardware.org/?probe=e657535210) | Oct 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d519c10989](https://linux-hardware.org/?probe=d519c10989) | Oct 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [626c7e1591](https://linux-hardware.org/?probe=626c7e1591) | Oct 16, 2023 |
| HP            | 18E5                        | Desktop     | [d869fcd6dc](https://linux-hardware.org/?probe=d869fcd6dc) | Oct 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [949b939768](https://linux-hardware.org/?probe=949b939768) | Oct 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [18922baf01](https://linux-hardware.org/?probe=18922baf01) | Oct 15, 2023 |
| Acer          | Aspire A317-51K             | Notebook    | [b342c56fc5](https://linux-hardware.org/?probe=b342c56fc5) | Oct 15, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [7f99209a06](https://linux-hardware.org/?probe=7f99209a06) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [430df05ea3](https://linux-hardware.org/?probe=430df05ea3) | Oct 14, 2023 |
| HP            | 339A                        | Desktop     | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| Dell          | Latitude 7330               | Notebook    | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [edb8f551bf](https://linux-hardware.org/?probe=edb8f551bf) | Oct 14, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b7a193296f](https://linux-hardware.org/?probe=b7a193296f) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [2bda5e79a4](https://linux-hardware.org/?probe=2bda5e79a4) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [4bc1c4e1b6](https://linux-hardware.org/?probe=4bc1c4e1b6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | Notebook    | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [1a8e527488](https://linux-hardware.org/?probe=1a8e527488) | Oct 13, 2023 |
| Intel         | DB75EN                      | Desktop     | [3d5c90093d](https://linux-hardware.org/?probe=3d5c90093d) | Oct 13, 2023 |
| Intel         | DB75EN                      | Desktop     | [30be24215f](https://linux-hardware.org/?probe=30be24215f) | Oct 13, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [ef43db2db3](https://linux-hardware.org/?probe=ef43db2db3) | Oct 12, 2023 |
| Dell          | Latitude 5411               | Notebook    | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| Dell          | MXG061                      | Notebook    | [61763acf36](https://linux-hardware.org/?probe=61763acf36) | Oct 08, 2023 |
| Dell          | MXG061                      | Notebook    | [93939082fa](https://linux-hardware.org/?probe=93939082fa) | Oct 08, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [6b02c3ce0f](https://linux-hardware.org/?probe=6b02c3ce0f) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a92453737d](https://linux-hardware.org/?probe=a92453737d) | Oct 06, 2023 |
| OrangePi      | Zero3                       | Soc         | [a97205648a](https://linux-hardware.org/?probe=a97205648a) | Oct 05, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [a1f4e6f6cc](https://linux-hardware.org/?probe=a1f4e6f6cc) | Oct 05, 2023 |
| HP            | 18E5                        | Desktop     | [653e855c90](https://linux-hardware.org/?probe=653e855c90) | Oct 05, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [870556d425](https://linux-hardware.org/?probe=870556d425) | Oct 04, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | Notebook    | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G814JU_G814JU     | Notebook    | [45be832065](https://linux-hardware.org/?probe=45be832065) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G814JU_G814JU     | Notebook    | [2dc93ff736](https://linux-hardware.org/?probe=2dc93ff736) | Oct 04, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a3f55874e2](https://linux-hardware.org/?probe=a3f55874e2) | Oct 03, 2023 |
| HP            | 09F8h                       | Desktop     | [996f1179ba](https://linux-hardware.org/?probe=996f1179ba) | Oct 02, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [e9ce3eada7](https://linux-hardware.org/?probe=e9ce3eada7) | Oct 02, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [df644adbab](https://linux-hardware.org/?probe=df644adbab) | Oct 01, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2ccade9ad8](https://linux-hardware.org/?probe=2ccade9ad8) | Oct 01, 2023 |
| HP            | 18E5                        | Desktop     | [1f3e02bd3e](https://linux-hardware.org/?probe=1f3e02bd3e) | Oct 01, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [79d4084e18](https://linux-hardware.org/?probe=79d4084e18) | Sep 30, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [99587baa3d](https://linux-hardware.org/?probe=99587baa3d) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| Google        | Swanky                      | Notebook    | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Lenovo        | NOK                         | Desktop     | [95ba956749](https://linux-hardware.org/?probe=95ba956749) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [39fd38bc98](https://linux-hardware.org/?probe=39fd38bc98) | Sep 28, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [ac27d821ae](https://linux-hardware.org/?probe=ac27d821ae) | Sep 27, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [060deb4c88](https://linux-hardware.org/?probe=060deb4c88) | Sep 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [275018a17e](https://linux-hardware.org/?probe=275018a17e) | Sep 26, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f3b7fdc0c1](https://linux-hardware.org/?probe=f3b7fdc0c1) | Sep 26, 2023 |
| Medion        | MS-7848                     | Desktop     | [5ce2a07d18](https://linux-hardware.org/?probe=5ce2a07d18) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [61f61b1b63](https://linux-hardware.org/?probe=61f61b1b63) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [ffb5ff9359](https://linux-hardware.org/?probe=ffb5ff9359) | Sep 25, 2023 |
| Toshiba       | Satellite C50D-A-10E        | Notebook    | [46f0ec000d](https://linux-hardware.org/?probe=46f0ec000d) | Sep 24, 2023 |
| Google        | Magpie                      | Notebook    | [3da6f69ed3](https://linux-hardware.org/?probe=3da6f69ed3) | Sep 24, 2023 |
| MSI           | GS75 Stealth 10SGS          | Notebook    | [9a310dd76b](https://linux-hardware.org/?probe=9a310dd76b) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [364ee59aef](https://linux-hardware.org/?probe=364ee59aef) | Sep 23, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [cfcdb2a961](https://linux-hardware.org/?probe=cfcdb2a961) | Sep 23, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [c3043092b9](https://linux-hardware.org/?probe=c3043092b9) | Sep 22, 2023 |
| Lenovo        | 7Y03CTO1WW                  | Server      | [424e70419e](https://linux-hardware.org/?probe=424e70419e) | Sep 21, 2023 |
| Lenovo        | 7Y03CTO1WW                  | Server      | [9838fce2b8](https://linux-hardware.org/?probe=9838fce2b8) | Sep 21, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [e4b8175a36](https://linux-hardware.org/?probe=e4b8175a36) | Sep 21, 2023 |
| Dell          | Latitude D500               | Notebook    | [1861582ebd](https://linux-hardware.org/?probe=1861582ebd) | Sep 21, 2023 |
| Dell          | Latitude D500               | Notebook    | [19ccfd47c6](https://linux-hardware.org/?probe=19ccfd47c6) | Sep 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [a6fd72ec9a](https://linux-hardware.org/?probe=a6fd72ec9a) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [d2fe3f1d44](https://linux-hardware.org/?probe=d2fe3f1d44) | Sep 19, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [d8f04cd109](https://linux-hardware.org/?probe=d8f04cd109) | Sep 19, 2023 |
| Samsung       | DP500A2D-A02UK SEC_SW_RE... | All in one  | [e0c767e50f](https://linux-hardware.org/?probe=e0c767e50f) | Sep 19, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | Notebook    | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Dell          | Latitude 3520               | Notebook    | [c74d2293dd](https://linux-hardware.org/?probe=c74d2293dd) | Sep 18, 2023 |
| Acer          | Aspire E5-473G              | Notebook    | [936a48fb5a](https://linux-hardware.org/?probe=936a48fb5a) | Sep 16, 2023 |
| Intel         | NUC11TNBi5 M11904-403       | Mini pc     | [e2504a32cf](https://linux-hardware.org/?probe=e2504a32cf) | Sep 15, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | Notebook    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| ASUSTek       | K72Dr                       | Notebook    | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| HP            | 86FB MVB A                  | Desktop     | [cdb3ae1787](https://linux-hardware.org/?probe=cdb3ae1787) | Sep 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [cf69e328c4](https://linux-hardware.org/?probe=cf69e328c4) | Sep 14, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [08e19ba183](https://linux-hardware.org/?probe=08e19ba183) | Sep 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b6a4327a8b](https://linux-hardware.org/?probe=b6a4327a8b) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| HP            | 8433 11                     | Desktop     | [6160c13209](https://linux-hardware.org/?probe=6160c13209) | Sep 12, 2023 |
| HP            | 8433 11                     | Desktop     | [2fbe297e6c](https://linux-hardware.org/?probe=2fbe297e6c) | Sep 12, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [7d201de7d6](https://linux-hardware.org/?probe=7d201de7d6) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5b93cd5b36](https://linux-hardware.org/?probe=5b93cd5b36) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [adc1e755c4](https://linux-hardware.org/?probe=adc1e755c4) | Sep 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ddddf5662e](https://linux-hardware.org/?probe=ddddf5662e) | Sep 10, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | Notebook    | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Google        | Rabbid                      | Notebook    | [c55be85343](https://linux-hardware.org/?probe=c55be85343) | Sep 09, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [c043df4efb](https://linux-hardware.org/?probe=c043df4efb) | Sep 09, 2023 |
| Lenovo        | ThinkPad X250 20CLA1YJUK    | Notebook    | [a068fec56f](https://linux-hardware.org/?probe=a068fec56f) | Sep 09, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [841d189992](https://linux-hardware.org/?probe=841d189992) | Sep 09, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [b3756f752a](https://linux-hardware.org/?probe=b3756f752a) | Sep 08, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [1f89d511d0](https://linux-hardware.org/?probe=1f89d511d0) | Sep 08, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [af67c49814](https://linux-hardware.org/?probe=af67c49814) | Sep 06, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c404211007](https://linux-hardware.org/?probe=c404211007) | Sep 05, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [da9dc1f5d9](https://linux-hardware.org/?probe=da9dc1f5d9) | Sep 05, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9b43cf14a3](https://linux-hardware.org/?probe=9b43cf14a3) | Sep 04, 2023 |
| HP            | 198E                        | Desktop     | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9234028f1](https://linux-hardware.org/?probe=e9234028f1) | Sep 03, 2023 |
| AMD           | A88K                        | Desktop     | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [62f941ff29](https://linux-hardware.org/?probe=62f941ff29) | Sep 03, 2023 |
| HP            | 2B2C                        | Desktop     | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| HP            | 198E                        | Desktop     | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [6decc4abdd](https://linux-hardware.org/?probe=6decc4abdd) | Sep 01, 2023 |
| AMD           | A88K                        | Desktop     | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [281e7176d8](https://linux-hardware.org/?probe=281e7176d8) | Aug 31, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [43c2d13a44](https://linux-hardware.org/?probe=43c2d13a44) | Aug 31, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [32a123fc5d](https://linux-hardware.org/?probe=32a123fc5d) | Aug 31, 2023 |
| OrangePi      | Zero3                       | Soc         | [34919a3af1](https://linux-hardware.org/?probe=34919a3af1) | Aug 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | Notebook    | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [f94a46ad17](https://linux-hardware.org/?probe=f94a46ad17) | Aug 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9ee073735e](https://linux-hardware.org/?probe=9ee073735e) | Aug 28, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | Notebook    | [b886de0613](https://linux-hardware.org/?probe=b886de0613) | Aug 28, 2023 |
| Google        | Banjo                       | Notebook    | [fcac9f460e](https://linux-hardware.org/?probe=fcac9f460e) | Aug 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [26c7035d28](https://linux-hardware.org/?probe=26c7035d28) | Aug 25, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [b7dce1f6e0](https://linux-hardware.org/?probe=b7dce1f6e0) | Aug 25, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e5317c3887](https://linux-hardware.org/?probe=e5317c3887) | Aug 25, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [082e1c2cc1](https://linux-hardware.org/?probe=082e1c2cc1) | Aug 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [4d01543131](https://linux-hardware.org/?probe=4d01543131) | Aug 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [a7fbf7edf2](https://linux-hardware.org/?probe=a7fbf7edf2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | Notebook    | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [c5484868fd](https://linux-hardware.org/?probe=c5484868fd) | Aug 23, 2023 |
| Acer          | AOD255                      | Notebook    | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b40144bd93](https://linux-hardware.org/?probe=b40144bd93) | Aug 22, 2023 |
| Acer          | TMP255-M                    | Notebook    | [4d5632e2d0](https://linux-hardware.org/?probe=4d5632e2d0) | Aug 22, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [d8a6683747](https://linux-hardware.org/?probe=d8a6683747) | Aug 21, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [aad70f30d7](https://linux-hardware.org/?probe=aad70f30d7) | Aug 21, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [22efc40cfd](https://linux-hardware.org/?probe=22efc40cfd) | Aug 21, 2023 |
| HP            | Presario CQ42               | Notebook    | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [277050ce29](https://linux-hardware.org/?probe=277050ce29) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [3c24c755d6](https://linux-hardware.org/?probe=3c24c755d6) | Aug 20, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [6aec4cb61e](https://linux-hardware.org/?probe=6aec4cb61e) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [48af3e541c](https://linux-hardware.org/?probe=48af3e541c) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [5b482b674c](https://linux-hardware.org/?probe=5b482b674c) | Aug 16, 2023 |
| Supermicro    | H12DSG-O-CPUA               | Server      | [b4efbfe41e](https://linux-hardware.org/?probe=b4efbfe41e) | Aug 16, 2023 |
| MSI           | U90/U100                    | Notebook    | [e8ae0fbcfb](https://linux-hardware.org/?probe=e8ae0fbcfb) | Aug 14, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | Notebook    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [39acd7fbd5](https://linux-hardware.org/?probe=39acd7fbd5) | Aug 13, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [10d9228c2d](https://linux-hardware.org/?probe=10d9228c2d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b2acf53271](https://linux-hardware.org/?probe=b2acf53271) | Aug 12, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [cb455d1334](https://linux-hardware.org/?probe=cb455d1334) | Aug 12, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f8fa12cc07](https://linux-hardware.org/?probe=f8fa12cc07) | Aug 11, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [3ab135e657](https://linux-hardware.org/?probe=3ab135e657) | Aug 11, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [09000d6461](https://linux-hardware.org/?probe=09000d6461) | Aug 10, 2023 |
| Dell          | Latitude 3540               | Notebook    | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [c05973af65](https://linux-hardware.org/?probe=c05973af65) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| Dell          | Latitude 5411               | Notebook    | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [7a15d18c93](https://linux-hardware.org/?probe=7a15d18c93) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [5796ca55ef](https://linux-hardware.org/?probe=5796ca55ef) | Aug 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [cc7ae6c4e9](https://linux-hardware.org/?probe=cc7ae6c4e9) | Aug 04, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [0068fdf226](https://linux-hardware.org/?probe=0068fdf226) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [a999a00c0a](https://linux-hardware.org/?probe=a999a00c0a) | Aug 03, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [60cb0baf9d](https://linux-hardware.org/?probe=60cb0baf9d) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [80558a1dcd](https://linux-hardware.org/?probe=80558a1dcd) | Aug 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Unknown       | Unknown                     | Soc         | [b89f7f59c6](https://linux-hardware.org/?probe=b89f7f59c6) | Aug 01, 2023 |
| Acer          | AOD255                      | Notebook    | [bdaffcb2ef](https://linux-hardware.org/?probe=bdaffcb2ef) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [edbd410baa](https://linux-hardware.org/?probe=edbd410baa) | Jul 30, 2023 |
| SiComputer    | NL40_50CU                   | Notebook    | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Acer          | AOD255                      | Notebook    | [53c73b6ad3](https://linux-hardware.org/?probe=53c73b6ad3) | Jul 29, 2023 |
| HP            | ProBook 4525s               | Notebook    | [f1f6309860](https://linux-hardware.org/?probe=f1f6309860) | Jul 29, 2023 |
| Gateway       | NV57H                       | Notebook    | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [136cb11fa2](https://linux-hardware.org/?probe=136cb11fa2) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | Notebook    | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | Notebook    | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [14b58ac305](https://linux-hardware.org/?probe=14b58ac305) | Jul 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6a1aa5fbc8](https://linux-hardware.org/?probe=6a1aa5fbc8) | Jul 26, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| Acer          | AOD255                      | Notebook    | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [2ae4820944](https://linux-hardware.org/?probe=2ae4820944) | Jul 25, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [e1db241198](https://linux-hardware.org/?probe=e1db241198) | Jul 24, 2023 |
| Acer          | AOD255                      | Notebook    | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [f4e52f14b5](https://linux-hardware.org/?probe=f4e52f14b5) | Jul 22, 2023 |
| HP            | 158A                        | Desktop     | [a2a4176353](https://linux-hardware.org/?probe=a2a4176353) | Jul 22, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [1c28b8d159](https://linux-hardware.org/?probe=1c28b8d159) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | Notebook    | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [5bf3142c39](https://linux-hardware.org/?probe=5bf3142c39) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [287298e199](https://linux-hardware.org/?probe=287298e199) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e4cc108748](https://linux-hardware.org/?probe=e4cc108748) | Jul 20, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [59cf8541b4](https://linux-hardware.org/?probe=59cf8541b4) | Jul 20, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [014e4a907f](https://linux-hardware.org/?probe=014e4a907f) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [39742015a1](https://linux-hardware.org/?probe=39742015a1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [e69885810c](https://linux-hardware.org/?probe=e69885810c) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02958438e7](https://linux-hardware.org/?probe=02958438e7) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [28850b9e94](https://linux-hardware.org/?probe=28850b9e94) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [35c4f96184](https://linux-hardware.org/?probe=35c4f96184) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [3b0be53d2b](https://linux-hardware.org/?probe=3b0be53d2b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f35f948278](https://linux-hardware.org/?probe=f35f948278) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [cb12281aa1](https://linux-hardware.org/?probe=cb12281aa1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [3bfca8e034](https://linux-hardware.org/?probe=3bfca8e034) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [667a30309b](https://linux-hardware.org/?probe=667a30309b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [08cca00ba4](https://linux-hardware.org/?probe=08cca00ba4) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [646ef2c43e](https://linux-hardware.org/?probe=646ef2c43e) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d1f453b1cf](https://linux-hardware.org/?probe=d1f453b1cf) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [0525e36038](https://linux-hardware.org/?probe=0525e36038) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [56571f9682](https://linux-hardware.org/?probe=56571f9682) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [b4516f6d51](https://linux-hardware.org/?probe=b4516f6d51) | Jul 19, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [94c330e355](https://linux-hardware.org/?probe=94c330e355) | Jul 19, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Dell          | Latitude 5590               | Notebook    | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Pegatron      | IPM41G                      | Desktop     | [9d29cf9820](https://linux-hardware.org/?probe=9d29cf9820) | Jul 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e790be3f6e](https://linux-hardware.org/?probe=e790be3f6e) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [08fc7fff38](https://linux-hardware.org/?probe=08fc7fff38) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | Notebook    | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0bd37865ac](https://linux-hardware.org/?probe=0bd37865ac) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | ProBook 4525s               | Notebook    | [6bae89bb98](https://linux-hardware.org/?probe=6bae89bb98) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| MSI           | H81M-P32                    | Desktop     | [2bf59485a6](https://linux-hardware.org/?probe=2bf59485a6) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | Notebook    | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [cc05c0d021](https://linux-hardware.org/?probe=cc05c0d021) | Jul 09, 2023 |
| Pegatron      | IPM41G                      | Desktop     | [be1f42c658](https://linux-hardware.org/?probe=be1f42c658) | Jul 09, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | Notebook    | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Dell          | Latitude 3540               | Notebook    | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [4fbf0f4e5d](https://linux-hardware.org/?probe=4fbf0f4e5d) | Jul 04, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a9b28705a3](https://linux-hardware.org/?probe=a9b28705a3) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [349ff94e9f](https://linux-hardware.org/?probe=349ff94e9f) | Jul 02, 2023 |
| Google        | Snappy                      | Notebook    | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | Notebook    | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| Chuwi         | CoreBox                     | Mini pc     | [7a2a217b46](https://linux-hardware.org/?probe=7a2a217b46) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [b9d71582c0](https://linux-hardware.org/?probe=b9d71582c0) | Jul 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [72d0376041](https://linux-hardware.org/?probe=72d0376041) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | Notebook    | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| HP            | Unknown                     | Notebook    | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e46c7340d7](https://linux-hardware.org/?probe=e46c7340d7) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | Unknown                     | Notebook    | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Alienware     | 18                          | Notebook    | [047bc74541](https://linux-hardware.org/?probe=047bc74541) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| Google        | Link                        | Notebook    | [b8284753ca](https://linux-hardware.org/?probe=b8284753ca) | Jun 22, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [2e4e948549](https://linux-hardware.org/?probe=2e4e948549) | Jun 22, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| HP            | Unknown                     | Notebook    | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| HP            | 18E7                        | Desktop     | [3b872d2a88](https://linux-hardware.org/?probe=3b872d2a88) | Jun 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [c2313cf371](https://linux-hardware.org/?probe=c2313cf371) | Jun 20, 2023 |
| Lenovo        | 1057 SDK0T76530 WIN 3556... | Desktop     | [0502b8f756](https://linux-hardware.org/?probe=0502b8f756) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [a7238c71a7](https://linux-hardware.org/?probe=a7238c71a7) | Jun 20, 2023 |
| TUXEDO        | P65xRP                      | Notebook    | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Standard      | Unknown                     | Desktop     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [601d7611be](https://linux-hardware.org/?probe=601d7611be) | Jun 17, 2023 |
| Unknown       | Minix Neo U9-H              | Soc         | [7b845b4b0b](https://linux-hardware.org/?probe=7b845b4b0b) | Jun 16, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [53a0b2f173](https://linux-hardware.org/?probe=53a0b2f173) | Jun 15, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| HP            | Unknown                     | Notebook    | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Samsung       | 760XDA                      | Notebook    | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [04f1fdc3c9](https://linux-hardware.org/?probe=04f1fdc3c9) | Jun 14, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Unknown       | Unknown                     | Other       | [00ad49fe2f](https://linux-hardware.org/?probe=00ad49fe2f) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [61e759f7db](https://linux-hardware.org/?probe=61e759f7db) | Jun 11, 2023 |
| Biostar       | TPower I45                  | Desktop     | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| TYAN Compu... | S7010                       | Server      | [a8b96e89f2](https://linux-hardware.org/?probe=a8b96e89f2) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| MSI           | A55M-E35                    | Desktop     | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| Acer          | AO722                       | Notebook    | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Acer          | AO722                       | Notebook    | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Dell          | Precision 5510              | Notebook    | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| LORD ELECT... | I915 Series V1.0            | Desktop     | [d693b7baec](https://linux-hardware.org/?probe=d693b7baec) | Jun 05, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [741e39b142](https://linux-hardware.org/?probe=741e39b142) | Jun 05, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Lenovo        | V560                        | Notebook    | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| SK hynix      | HyBook                      | Notebook    | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [1d9f5bc60f](https://linux-hardware.org/?probe=1d9f5bc60f) | Jun 02, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [33eb5df96b](https://linux-hardware.org/?probe=33eb5df96b) | May 26, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [7788147663](https://linux-hardware.org/?probe=7788147663) | May 24, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [2dfed39533](https://linux-hardware.org/?probe=2dfed39533) | May 24, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | Notebook    | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [50b46e4d8c](https://linux-hardware.org/?probe=50b46e4d8c) | May 22, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| HP            | 0A08h                       | Desktop     | [9d159d2637](https://linux-hardware.org/?probe=9d159d2637) | May 21, 2023 |
| Dell          | G3 3500                     | Notebook    | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [84bd50bc27](https://linux-hardware.org/?probe=84bd50bc27) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | Notebook    | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [3191d9fca4](https://linux-hardware.org/?probe=3191d9fca4) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | Notebook    | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Unknown       | Kontron BL i.MX8MM OSM-S... | Soc         | [958fed11ae](https://linux-hardware.org/?probe=958fed11ae) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9726453f00](https://linux-hardware.org/?probe=9726453f00) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ac436d763](https://linux-hardware.org/?probe=7ac436d763) | May 08, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [a915e84a9a](https://linux-hardware.org/?probe=a915e84a9a) | May 08, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | Desktop     | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f5f0edbac8](https://linux-hardware.org/?probe=f5f0edbac8) | May 05, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| HP            | ENVY 4                      | Notebook    | [20395a1739](https://linux-hardware.org/?probe=20395a1739) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | Notebook    | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Acer          | Peppy                       | Notebook    | [dcac703c46](https://linux-hardware.org/?probe=dcac703c46) | Apr 30, 2023 |
| Acer          | Extensa 5620                | Notebook    | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| HP            | 158A                        | Desktop     | [fb7aef7883](https://linux-hardware.org/?probe=fb7aef7883) | Apr 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 158A                        | Desktop     | [c3189bccb1](https://linux-hardware.org/?probe=c3189bccb1) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [98ed5e9a2e](https://linux-hardware.org/?probe=98ed5e9a2e) | Apr 25, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| OrangePi      | 4 (DT)                      | Soc         | [a1c0a82172](https://linux-hardware.org/?probe=a1c0a82172) | Apr 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [9ff4edba5b](https://linux-hardware.org/?probe=9ff4edba5b) | Apr 20, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [e062ca363c](https://linux-hardware.org/?probe=e062ca363c) | Apr 20, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [704778a577](https://linux-hardware.org/?probe=704778a577) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [9539ccfd4d](https://linux-hardware.org/?probe=9539ccfd4d) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [4cb39d1136](https://linux-hardware.org/?probe=4cb39d1136) | Apr 15, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [ae144ff4c8](https://linux-hardware.org/?probe=ae144ff4c8) | Apr 12, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Dell          | 060K5C A04                  | Server      | [962b265260](https://linux-hardware.org/?probe=962b265260) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e99e4b1fac](https://linux-hardware.org/?probe=e99e4b1fac) | Apr 10, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9dde876e9](https://linux-hardware.org/?probe=e9dde876e9) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [9f0d854259](https://linux-hardware.org/?probe=9f0d854259) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [1b8983e24d](https://linux-hardware.org/?probe=1b8983e24d) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Nvidia        | Tegra                       | Soc         | [d57318f254](https://linux-hardware.org/?probe=d57318f254) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [25c3fdc9f7](https://linux-hardware.org/?probe=25c3fdc9f7) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8b4f79808a](https://linux-hardware.org/?probe=8b4f79808a) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [deedee079c](https://linux-hardware.org/?probe=deedee079c) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| Gateway       | LT27                        | Notebook    | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [94cd15664b](https://linux-hardware.org/?probe=94cd15664b) | Mar 27, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| MSI           | MEG B550 UNIFY              | Desktop     | [492a70f1c3](https://linux-hardware.org/?probe=492a70f1c3) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [0fc1609d81](https://linux-hardware.org/?probe=0fc1609d81) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| HP            | 158A                        | Desktop     | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | Notebook    | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| Biostar       | TZ77A                       | Desktop     | [9484c73494](https://linux-hardware.org/?probe=9484c73494) | Mar 21, 2023 |
| HP            | 158A                        | Desktop     | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [62d90f07ba](https://linux-hardware.org/?probe=62d90f07ba) | Mar 20, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | Notebook    | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [653b1820fe](https://linux-hardware.org/?probe=653b1820fe) | Mar 20, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Amlogic       | Meson8B                     | Soc         | [c564829ae4](https://linux-hardware.org/?probe=c564829ae4) | Mar 17, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [4efa1b8600](https://linux-hardware.org/?probe=4efa1b8600) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [406ea57f9c](https://linux-hardware.org/?probe=406ea57f9c) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Gigabyte      | 8IR533                      | Desktop     | [ee9bb6485a](https://linux-hardware.org/?probe=ee9bb6485a) | Mar 12, 2023 |
| Gigabyte      | 8IR533                      | Desktop     | [9e5837ddaf](https://linux-hardware.org/?probe=9e5837ddaf) | Mar 12, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [b7de8d093d](https://linux-hardware.org/?probe=b7de8d093d) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Apple         | MacBookPro1,1               | Notebook    | [105d39532f](https://linux-hardware.org/?probe=105d39532f) | Mar 10, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82551d929c](https://linux-hardware.org/?probe=82551d929c) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [66f6a0491e](https://linux-hardware.org/?probe=66f6a0491e) | Mar 07, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [c0f8008427](https://linux-hardware.org/?probe=c0f8008427) | Mar 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Toshiba       | Satellite L775              | Notebook    | [75a1948a64](https://linux-hardware.org/?probe=75a1948a64) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| Microtech     | ebookPro                    | Notebook    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [e513434675](https://linux-hardware.org/?probe=e513434675) | Mar 04, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [5c3d9047bd](https://linux-hardware.org/?probe=5c3d9047bd) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| Google        | Nautilus                    | Convertible | [5aff7271ac](https://linux-hardware.org/?probe=5aff7271ac) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [aeb7d7a9f4](https://linux-hardware.org/?probe=aeb7d7a9f4) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [83e6da010b](https://linux-hardware.org/?probe=83e6da010b) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| Alienware     | 17 R4                       | Notebook    | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [43b2cca281](https://linux-hardware.org/?probe=43b2cca281) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | Notebook    | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| HP            | 158A                        | Desktop     | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [e85ff6e5c3](https://linux-hardware.org/?probe=e85ff6e5c3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [8cd6645d36](https://linux-hardware.org/?probe=8cd6645d36) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Pegatron      | EVE                         | Desktop     | [0bde64bb64](https://linux-hardware.org/?probe=0bde64bb64) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [6e1d13cecb](https://linux-hardware.org/?probe=6e1d13cecb) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [33e3d93b19](https://linux-hardware.org/?probe=33e3d93b19) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [bb037d75a7](https://linux-hardware.org/?probe=bb037d75a7) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [dd2d87798a](https://linux-hardware.org/?probe=dd2d87798a) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | Notebook    | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [74013e0688](https://linux-hardware.org/?probe=74013e0688) | Feb 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| HP            | Compaq Presario A900        | Notebook    | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | Notebook    | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| Dell          | Latitude D430               | Notebook    | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| MSI           | MS-7309                     | Desktop     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [99dc5ad30d](https://linux-hardware.org/?probe=99dc5ad30d) | Feb 05, 2023 |
| ASUSTek       | P5V-VM DH                   | Desktop     | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | Notebook    | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Xubuntu 20.04        | 2016      | 43.93%  |
| Xubuntu 18.04        | 1069      | 23.29%  |
| Xubuntu 22.04        | 698       | 15.21%  |
| Xubuntu 19.10        | 199       | 4.34%   |
| Xubuntu 16.04        | 101       | 2.2%    |
| Xubuntu 21.10        | 96        | 2.09%   |
| Xubuntu 20.10        | 93        | 2.03%   |
| Xubuntu 21.04        | 81        | 1.77%   |
| Xubuntu 23.04        | 73        | 1.59%   |
| Xubuntu 22.10        | 58        | 1.26%   |
| Xubuntu 23.10        | 44        | 0.96%   |
| Xubuntu 19.04        | 26        | 0.57%   |
| Xubuntu 18.10        | 11        | 0.24%   |
| Xubuntu 17.10        | 6         | 0.13%   |
| Xubuntu              | 6         | 0.13%   |
| Xubuntu 14.04        | 3         | 0.07%   |
| Xubuntu 2023.4~rc    | 2         | 0.04%   |
| Xubuntu 2023.2       | 2         | 0.04%   |
| Xubuntu 17.04        | 2         | 0.04%   |
| Xubuntu 2023.3~rc    | 1         | 0.02%   |
| Xubuntu 2023.3       | 1         | 0.02%   |
| Xubuntu 2023.1-beta5 | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 4415      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 156       | 2.97%   |
| 5.4.0-48-generic    | 65        | 1.24%   |
| 5.4.0-58-generic    | 60        | 1.14%   |
| 5.4.0-52-generic    | 59        | 1.12%   |
| 5.3.0-46-generic    | 59        | 1.12%   |
| 5.15.0-56-generic   | 51        | 0.97%   |
| 5.11.0-27-generic   | 50        | 0.95%   |
| 5.4.0-65-generic    | 48        | 0.91%   |
| 5.3.0-40-generic    | 48        | 0.91%   |
| 5.4.0-29-generic    | 46        | 0.88%   |
| 5.4.0-54-generic    | 45        | 0.86%   |
| 5.15.0-52-generic   | 44        | 0.84%   |
| 5.4.0-47-generic    | 42        | 0.8%    |
| 5.4.0-42-lowlatency | 40        | 0.76%   |
| 5.4.0-26-generic    | 39        | 0.74%   |
| 5.3.0-42-generic    | 38        | 0.72%   |
| 5.3.0-28-generic    | 36        | 0.69%   |
| 5.4.0-40-generic    | 35        | 0.67%   |
| 5.0.0-37-generic    | 35        | 0.67%   |
| 5.3.0-51-generic    | 34        | 0.65%   |
| 6.2.0-26-generic    | 33        | 0.63%   |
| 5.4.0-37-generic    | 33        | 0.63%   |
| 5.4.0-66-generic    | 31        | 0.59%   |
| 5.15.0-58-generic   | 31        | 0.59%   |
| 5.15.0-47-generic   | 31        | 0.59%   |
| 4.15.0-99-generic   | 31        | 0.59%   |
| 5.4.0-89-generic    | 30        | 0.57%   |
| 5.4.0-31-generic    | 30        | 0.57%   |
| 5.15.0-48-generic   | 30        | 0.57%   |
| 5.15.0-46-generic   | 29        | 0.55%   |
| 5.4.0-72-generic    | 28        | 0.53%   |
| 5.3.0-53-generic    | 28        | 0.53%   |
| 5.4.0-29-lowlatency | 27        | 0.51%   |
| 5.4.0-91-generic    | 26        | 0.5%    |
| 5.4.0-81-generic    | 26        | 0.5%    |
| 5.13.0-39-generic   | 26        | 0.5%    |
| 5.13.0-30-generic   | 26        | 0.5%    |
| 5.8.0-53-generic    | 25        | 0.48%   |
| 5.4.0-33-generic    | 25        | 0.48%   |
| 5.15.0-60-generic   | 25        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1641      | 35.04%  |
| 5.15.0  | 540       | 11.53%  |
| 4.15.0  | 494       | 10.55%  |
| 5.3.0   | 438       | 9.35%   |
| 5.11.0  | 276       | 5.89%   |
| 5.8.0   | 255       | 5.45%   |
| 5.13.0  | 225       | 4.8%    |
| 6.2.0   | 179       | 3.82%   |
| 5.19.0  | 142       | 3.03%   |
| 5.0.0   | 107       | 2.28%   |
| 6.5.0   | 56        | 1.2%    |
| 4.4.0   | 49        | 1.05%   |
| 4.18.0  | 26        | 0.56%   |
| 5.17.0  | 12        | 0.26%   |
| 6.1.0   | 9         | 0.19%   |
| 4.13.0  | 9         | 0.19%   |
| 4.10.0  | 6         | 0.13%   |
| 5.6.0   | 5         | 0.11%   |
| 5.4.217 | 5         | 0.11%   |
| 5.14.0  | 5         | 0.11%   |
| 5.10.0  | 5         | 0.11%   |
| 6.0.0   | 4         | 0.09%   |
| 5.9.8   | 4         | 0.09%   |
| 5.18.0  | 4         | 0.09%   |
| 6.5.1   | 3         | 0.06%   |
| 6.1.31  | 3         | 0.06%   |
| 6.1.30  | 3         | 0.06%   |
| 5.9.16  | 3         | 0.06%   |
| 5.9.0   | 3         | 0.06%   |
| 5.15.1  | 3         | 0.06%   |
| 5.11.16 | 3         | 0.06%   |
| 4.8.0   | 3         | 0.06%   |
| 4.4.194 | 3         | 0.06%   |
| 6.2.7   | 2         | 0.04%   |
| 6.2.2   | 2         | 0.04%   |
| 6.0.9   | 2         | 0.04%   |
| 5.7.7   | 2         | 0.04%   |
| 5.7.6   | 2         | 0.04%   |
| 5.7.1   | 2         | 0.04%   |
| 5.7.0   | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1653      | 35.34%  |
| 5.15    | 555       | 11.86%  |
| 4.15    | 495       | 10.58%  |
| 5.3     | 440       | 9.41%   |
| 5.11    | 283       | 6.05%   |
| 5.8     | 260       | 5.56%   |
| 5.13    | 229       | 4.9%    |
| 6.2     | 185       | 3.95%   |
| 5.19    | 146       | 3.12%   |
| 5.0     | 109       | 2.33%   |
| 6.5     | 61        | 1.3%    |
| 4.4     | 55        | 1.18%   |
| 4.18    | 26        | 0.56%   |
| 6.1     | 18        | 0.38%   |
| 5.10    | 17        | 0.36%   |
| 5.17    | 14        | 0.3%    |
| 5.9     | 13        | 0.28%   |
| 5.7     | 10        | 0.21%   |
| 5.6     | 10        | 0.21%   |
| 5.14    | 10        | 0.21%   |
| 4.13    | 9         | 0.19%   |
| 5.12    | 8         | 0.17%   |
| 6.0     | 7         | 0.15%   |
| 5.18    | 7         | 0.15%   |
| 4.19    | 7         | 0.15%   |
| 6.4     | 6         | 0.13%   |
| 6.3     | 6         | 0.13%   |
| 4.9     | 6         | 0.13%   |
| 4.10    | 6         | 0.13%   |
| 6.6     | 5         | 0.11%   |
| 5.16    | 5         | 0.11%   |
| 5.5     | 3         | 0.06%   |
| 4.8     | 3         | 0.06%   |
| 5.2     | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.11    | 2         | 0.04%   |
| 6.7     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3843      | 86.91%  |
| i686    | 521       | 11.78%  |
| aarch64 | 45        | 1.02%   |
| armv7l  | 13        | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 4256      | 96.2%   |
| GNOME           | 112       | 2.53%   |
| KDE5            | 10        | 0.23%   |
| i3              | 10        | 0.23%   |
| Cinnamon        | 8         | 0.18%   |
| Unicorn:XFCE    | 5         | 0.11%   |
| GNOME Flashback | 5         | 0.11%   |
| Unity           | 4         | 0.09%   |
| X-Cinnamon      | 3         | 0.07%   |
| MATE            | 3         | 0.07%   |
| LXQt            | 2         | 0.05%   |
| GNUstep         | 2         | 0.05%   |
| xmonad          | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |
| Unknown         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4327      | 97.83%  |
| Tty     | 69        | 1.56%   |
| Wayland | 22        | 0.5%    |
| Web     | 3         | 0.07%   |
| Unknown | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2140      | 46.94%  |
| LightDM | 1756      | 38.52%  |
| TDM     | 508       | 11.14%  |
| GDM3    | 79        | 1.73%   |
| GDM     | 48        | 1.05%   |
| SDDM    | 19        | 0.42%   |
| XDM     | 4         | 0.09%   |
| SLiM    | 3         | 0.07%   |
| NODM    | 1         | 0.02%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1479      | 33.33%  |
| de_DE   | 447       | 10.07%  |
| fr_FR   | 401       | 9.04%   |
| it_IT   | 295       | 6.65%   |
| ru_RU   | 219       | 4.93%   |
| pt_BR   | 216       | 4.87%   |
| en_GB   | 173       | 3.9%    |
| C       | 147       | 3.31%   |
| es_ES   | 114       | 2.57%   |
| en_CA   | 104       | 2.34%   |
| Unknown | 82        | 1.85%   |
| en_AU   | 77        | 1.74%   |
| pl_PL   | 67        | 1.51%   |
| es_AR   | 42        | 0.95%   |
| hu_HU   | 41        | 0.92%   |
| nl_NL   | 38        | 0.86%   |
| ja_JP   | 38        | 0.86%   |
| cs_CZ   | 34        | 0.77%   |
| en_IN   | 29        | 0.65%   |
| es_MX   | 24        | 0.54%   |
| fr_BE   | 18        | 0.41%   |
| fi_FI   | 18        | 0.41%   |
| ru_UA   | 17        | 0.38%   |
| pt_PT   | 17        | 0.38%   |
| sv_SE   | 15        | 0.34%   |
| sk_SK   | 15        | 0.34%   |
| en_ZA   | 15        | 0.34%   |
| tr_TR   | 14        | 0.32%   |
| es_CO   | 14        | 0.32%   |
| de_CH   | 14        | 0.32%   |
| de_AT   | 14        | 0.32%   |
| zh_TW   | 13        | 0.29%   |
| el_GR   | 13        | 0.29%   |
| zh_CN   | 11        | 0.25%   |
| fr_CA   | 11        | 0.25%   |
| es_VE   | 11        | 0.25%   |
| nl_BE   | 10        | 0.23%   |
| ro_RO   | 7         | 0.16%   |
| es_UY   | 7         | 0.16%   |
| es_CL   | 7         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2867      | 64.12%  |
| EFI  | 1604      | 35.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3954      | 88.46%  |
| Tmpfs   | 172       | 3.85%   |
| Overlay | 165       | 3.69%   |
| Btrfs   | 74        | 1.66%   |
| Zfs     | 42        | 0.94%   |
| Unknown | 24        | 0.54%   |
| Xfs     | 17        | 0.38%   |
| Ext2    | 11        | 0.25%   |
| Ext3    | 9         | 0.2%    |
| Ufs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2546      | 56.7%   |
| GPT     | 1319      | 29.38%  |
| MBR     | 625       | 13.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3779      | 83.75%  |
| Yes       | 733       | 16.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2987      | 66.5%   |
| Yes       | 1505      | 33.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 664       | 15.04%  |
| Hewlett-Packard         | 659       | 14.93%  |
| Lenovo                  | 535       | 12.12%  |
| Dell                    | 535       | 12.12%  |
| Acer                    | 287       | 6.5%    |
| Gigabyte Technology     | 263       | 5.96%   |
| MSI                     | 207       | 4.69%   |
| ASRock                  | 166       | 3.76%   |
| Toshiba                 | 104       | 2.36%   |
| Apple                   | 85        | 1.93%   |
| Intel                   | 74        | 1.68%   |
| Samsung Electronics     | 63        | 1.43%   |
| Unknown                 | 54        | 1.22%   |
| Sony                    | 53        | 1.2%    |
| Medion                  | 49        | 1.11%   |
| Fujitsu                 | 37        | 0.84%   |
| Fujitsu Siemens         | 34        | 0.77%   |
| Packard Bell            | 29        | 0.66%   |
| ECS                     | 29        | 0.66%   |
| Google                  | 28        | 0.63%   |
| Foxconn                 | 24        | 0.54%   |
| Pegatron                | 19        | 0.43%   |
| Notebook                | 17        | 0.39%   |
| Positivo                | 16        | 0.36%   |
| Raspberry Pi Foundation | 15        | 0.34%   |
| eMachines               | 15        | 0.34%   |
| Clevo                   | 15        | 0.34%   |
| HUAWEI                  | 14        | 0.32%   |
| IBM                     | 12        | 0.27%   |
| Supermicro              | 11        | 0.25%   |
| Gateway                 | 11        | 0.25%   |
| AMI                     | 11        | 0.25%   |
| Biostar                 | 10        | 0.23%   |
| GPU Company             | 9         | 0.2%    |
| ZOTAC                   | 8         | 0.18%   |
| LG Electronics          | 8         | 0.18%   |
| Itautec                 | 7         | 0.16%   |
| Alienware               | 7         | 0.16%   |
| TUXEDO                  | 6         | 0.14%   |
| Semp Toshiba            | 6         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 79        | 1.79%   |
| ASUS All Series                        | 38        | 0.86%   |
| HP Pavilion dv6                        | 20        | 0.45%   |
| HP Notebook                            | 17        | 0.39%   |
| Gigabyte H410M S2H                     | 15        | 0.34%   |
| Dell OptiPlex 7010                     | 15        | 0.34%   |
| Dell OptiPlex 755                      | 11        | 0.25%   |
| Dell Latitude D630                     | 11        | 0.25%   |
| HP Pavilion 15                         | 10        | 0.23%   |
| HP 15                                  | 10        | 0.23%   |
| HP Pavilion g6                         | 9         | 0.2%    |
| Gigabyte H81M-S2V                      | 9         | 0.2%    |
| ECS G31T-M9                            | 9         | 0.2%    |
| Dell OptiPlex 390                      | 9         | 0.2%    |
| Dell Latitude E6430                    | 9         | 0.2%    |
| ASRock N68C-S UCC                      | 9         | 0.2%    |
| HP Pavilion dv7                        | 8         | 0.18%   |
| Dell OptiPlex 780                      | 8         | 0.18%   |
| Dell OptiPlex 760                      | 8         | 0.18%   |
| MSI MS-7C37                            | 7         | 0.16%   |
| MSI MS-7721                            | 7         | 0.16%   |
| HP Pavilion dv6500                     | 7         | 0.16%   |
| Dell OptiPlex 3020                     | 7         | 0.16%   |
| ASUS TUF Gaming X570-PLUS              | 7         | 0.16%   |
| MSI MS-7C56                            | 6         | 0.14%   |
| MSI MS-7817                            | 6         | 0.14%   |
| HP EliteDesk 800 G1 SFF                | 6         | 0.14%   |
| Dell OptiPlex 9020                     | 6         | 0.14%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.14%   |
| ASUS M5A78L-M/USB3                     | 6         | 0.14%   |
| MSI MS-7C02                            | 5         | 0.11%   |
| MSI MS-7B89                            | 5         | 0.11%   |
| MSI MS-7B79                            | 5         | 0.11%   |
| MSI MS-7A38                            | 5         | 0.11%   |
| Intel H61                              | 5         | 0.11%   |
| HP Pavilion 17                         | 5         | 0.11%   |
| HP EliteBook 840 G3                    | 5         | 0.11%   |
| HP Compaq Pro 6300 SFF                 | 5         | 0.11%   |
| HP Compaq Elite 8300 SFF               | 5         | 0.11%   |
| HP Compaq dc7600 Small Form Factor     | 5         | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 268       | 6.07%   |
| Acer Aspire           | 180       | 4.08%   |
| Dell Latitude         | 141       | 3.19%   |
| Dell Inspiron         | 138       | 3.13%   |
| HP Pavilion           | 123       | 2.79%   |
| HP Compaq             | 115       | 2.6%    |
| Dell OptiPlex         | 109       | 2.47%   |
| Toshiba Satellite     | 88        | 1.99%   |
| Lenovo IdeaPad        | 80        | 1.81%   |
| Unknown               | 79        | 1.79%   |
| HP EliteBook          | 63        | 1.43%   |
| ASUS PRIME            | 55        | 1.25%   |
| HP ProBook            | 49        | 1.11%   |
| Lenovo ThinkCentre    | 44        | 1%      |
| HP Laptop             | 43        | 0.97%   |
| ASUS VivoBook         | 41        | 0.93%   |
| Dell Precision        | 39        | 0.88%   |
| ASUS All              | 38        | 0.86%   |
| ASUS ROG              | 28        | 0.63%   |
| Dell XPS              | 26        | 0.59%   |
| ASUS TUF              | 25        | 0.57%   |
| Dell Vostro           | 24        | 0.54%   |
| HP ProDesk            | 20        | 0.45%   |
| Acer Veriton          | 19        | 0.43%   |
| Acer Extensa          | 19        | 0.43%   |
| HP Notebook           | 18        | 0.41%   |
| Gigabyte H410M        | 16        | 0.36%   |
| Fujitsu LIFEBOOK      | 16        | 0.36%   |
| Dell PowerEdge        | 16        | 0.36%   |
| RPi Raspberry         | 15        | 0.34%   |
| Packard Bell EasyNote | 15        | 0.34%   |
| Fujitsu Siemens AMILO | 15        | 0.34%   |
| HP Presario           | 14        | 0.32%   |
| HP ENVY               | 14        | 0.32%   |
| HP EliteDesk          | 14        | 0.32%   |
| Fujitsu ESPRIMO       | 13        | 0.29%   |
| Lenovo IdeaCentre     | 12        | 0.27%   |
| Dell Studio           | 12        | 0.27%   |
| ASUS M5A78L-M         | 12        | 0.27%   |
| Lenovo Yoga           | 11        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 365       | 8.27%   |
| 2011    | 363       | 8.22%   |
| 2010    | 318       | 7.2%    |
| 2008    | 318       | 7.2%    |
| 2013    | 315       | 7.13%   |
| 2009    | 300       | 6.8%    |
| 2007    | 274       | 6.21%   |
| 2014    | 262       | 5.93%   |
| 2019    | 256       | 5.8%    |
| 2018    | 244       | 5.53%   |
| 2020    | 242       | 5.48%   |
| 2017    | 222       | 5.03%   |
| 2015    | 176       | 3.99%   |
| 2021    | 171       | 3.87%   |
| 2016    | 171       | 3.87%   |
| 2006    | 150       | 3.4%    |
| 2022    | 75        | 1.7%    |
| 2005    | 72        | 1.63%   |
| Unknown | 54        | 1.22%   |
| 2023    | 26        | 0.59%   |
| 2004    | 17        | 0.39%   |
| 2003    | 16        | 0.36%   |
| 2002    | 4         | 0.09%   |
| 2001    | 4         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2395      | 54.25%  |
| Desktop        | 1748      | 39.59%  |
| Mini pc        | 65        | 1.47%   |
| System on chip | 54        | 1.22%   |
| All in one     | 48        | 1.09%   |
| Convertible    | 46        | 1.04%   |
| Server         | 39        | 0.88%   |
| Tablet         | 18        | 0.41%   |
| Other          | 1         | 0.02%   |
| Firewall       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4182      | 94.25%  |
| Enabled  | 255       | 5.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4385      | 99.32%  |
| Yes  | 30        | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1183      | 26.39%  |
| 4.01-8.0        | 855       | 19.08%  |
| 8.01-16.0       | 605       | 13.5%   |
| 16.01-24.0      | 582       | 12.99%  |
| 1.01-2.0        | 490       | 10.93%  |
| 32.01-64.0      | 261       | 5.82%   |
| 2.01-3.0        | 162       | 3.61%   |
| 0.51-1.0        | 158       | 3.53%   |
| 64.01-256.0     | 112       | 2.5%    |
| 24.01-32.0      | 58        | 1.29%   |
| 0.01-0.5        | 12        | 0.27%   |
| More than 256.0 | 4         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1973      | 40.41%  |
| 0.51-1.0   | 916       | 18.76%  |
| 2.01-3.0   | 912       | 18.68%  |
| 4.01-8.0   | 429       | 8.79%   |
| 3.01-4.0   | 364       | 7.46%   |
| 8.01-16.0  | 127       | 2.6%    |
| 0.01-0.5   | 127       | 2.6%    |
| 16.01-24.0 | 22        | 0.45%   |
| 24.01-32.0 | 8         | 0.16%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2829      | 62.34%  |
| 2      | 1080      | 23.8%   |
| 3      | 336       | 7.4%    |
| 4      | 127       | 2.8%    |
| 5      | 63        | 1.39%   |
| 0      | 50        | 1.1%    |
| 6      | 24        | 0.53%   |
| 7      | 15        | 0.33%   |
| 8      | 5         | 0.11%   |
| 10     | 4         | 0.09%   |
| 9      | 3         | 0.07%   |
| 11     | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2238      | 50.33%  |
| No        | 2209      | 49.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3972      | 89.88%  |
| No        | 447       | 10.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3213      | 72.28%  |
| No        | 1232      | 27.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2456      | 54.94%  |
| Yes       | 2014      | 45.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 703       | 15.83%  |
| Germany      | 545       | 12.27%  |
| France       | 423       | 9.53%   |
| Italy        | 328       | 7.39%   |
| Russia       | 284       | 6.4%    |
| Brazil       | 252       | 5.68%   |
| UK           | 169       | 3.81%   |
| Canada       | 166       | 3.74%   |
| Spain        | 137       | 3.09%   |
| Netherlands  | 102       | 2.3%    |
| Australia    | 88        | 1.98%   |
| Poland       | 86        | 1.94%   |
| Argentina    | 59        | 1.33%   |
| Ukraine      | 57        | 1.28%   |
| Belgium      | 57        | 1.28%   |
| Czechia      | 49        | 1.1%    |
| Hungary      | 48        | 1.08%   |
| Mexico       | 47        | 1.06%   |
| Japan        | 46        | 1.04%   |
| Sweden       | 45        | 1.01%   |
| Finland      | 41        | 0.92%   |
| India        | 39        | 0.88%   |
| Portugal     | 36        | 0.81%   |
| Greece       | 36        | 0.81%   |
| Austria      | 32        | 0.72%   |
| Switzerland  | 28        | 0.63%   |
| Indonesia    | 27        | 0.61%   |
| Bulgaria     | 27        | 0.61%   |
| Turkey       | 25        | 0.56%   |
| Romania      | 25        | 0.56%   |
| Iran         | 21        | 0.47%   |
| Slovakia     | 20        | 0.45%   |
| Colombia     | 19        | 0.43%   |
| Norway       | 17        | 0.38%   |
| Taiwan       | 16        | 0.36%   |
| Venezuela    | 15        | 0.34%   |
| South Africa | 15        | 0.34%   |
| Israel       | 15        | 0.34%   |
| Denmark      | 14        | 0.32%   |
| China        | 14        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 57        | 1.21%   |
| Berlin            | 52        | 1.11%   |
| Moscow            | 49        | 1.04%   |
| Voronezh          | 46        | 0.98%   |
| Rome              | 39        | 0.83%   |
| Milan             | 38        | 0.81%   |
| Sydney            | 30        | 0.64%   |
| Warsaw            | 27        | 0.57%   |
| Sao Paulo         | 27        | 0.57%   |
| Amsterdam         | 27        | 0.57%   |
| Athens            | 25        | 0.53%   |
| St Petersburg     | 24        | 0.51%   |
| Munich            | 24        | 0.51%   |
| Madrid            | 23        | 0.49%   |
| Budapest          | 23        | 0.49%   |
| Hamburg           | 22        | 0.47%   |
| Rio de Janeiro    | 20        | 0.43%   |
| Québec           | 19        | 0.4%    |
| Helsinki          | 19        | 0.4%    |
| Melbourne         | 17        | 0.36%   |
| Barcelona         | 17        | 0.36%   |
| Tehran            | 16        | 0.34%   |
| Prague            | 16        | 0.34%   |
| Montreal          | 16        | 0.34%   |
| Genoa             | 16        | 0.34%   |
| Oryol             | 15        | 0.32%   |
| Kyiv              | 15        | 0.32%   |
| Buenos Aires      | 15        | 0.32%   |
| Turin             | 14        | 0.3%    |
| Toronto           | 14        | 0.3%    |
| Stuttgart         | 14        | 0.3%    |
| Vancouver         | 13        | 0.28%   |
| Sofia             | 13        | 0.28%   |
| Frankfurt am Main | 13        | 0.28%   |
| Vienna            | 12        | 0.26%   |
| Leipzig           | 12        | 0.26%   |
| Seattle           | 11        | 0.23%   |
| Lisbon            | 11        | 0.23%   |
| Cologne           | 11        | 0.23%   |
| Chicago           | 11        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1071      | 1573   | 17.53%  |
| WDC                         | 1014      | 1495   | 16.59%  |
| Samsung Electronics         | 828       | 1168   | 13.55%  |
| Toshiba                     | 414       | 520    | 6.77%   |
| Hitachi                     | 342       | 450    | 5.6%    |
| Unknown                     | 317       | 413    | 5.19%   |
| Kingston                    | 286       | 362    | 4.68%   |
| SanDisk                     | 227       | 288    | 3.71%   |
| Crucial                     | 175       | 229    | 2.86%   |
| HGST                        | 116       | 141    | 1.9%    |
| Intel                       | 113       | 159    | 1.85%   |
| SK hynix                    | 98        | 118    | 1.6%    |
| A-DATA Technology           | 82        | 107    | 1.34%   |
| Fujitsu                     | 73        | 91     | 1.19%   |
| China                       | 68        | 79     | 1.11%   |
| Maxtor                      | 62        | 87     | 1.01%   |
| Micron Technology           | 54        | 63     | 0.88%   |
| PNY                         | 43        | 58     | 0.7%    |
| Patriot                     | 32        | 37     | 0.52%   |
| Intenso                     | 32        | 39     | 0.52%   |
| Transcend                   | 31        | 35     | 0.51%   |
| Phison                      | 28        | 52     | 0.46%   |
| OCZ                         | 28        | 36     | 0.46%   |
| KIOXIA                      | 27        | 35     | 0.44%   |
| SPCC                        | 26        | 40     | 0.43%   |
| Apple                       | 22        | 32     | 0.36%   |
| Unknown                     | 22        | 23     | 0.36%   |
| LITEON                      | 19        | 21     | 0.31%   |
| LITEONIT                    | 18        | 21     | 0.29%   |
| Silicon Motion              | 17        | 18     | 0.28%   |
| ASMT                        | 17        | 26     | 0.28%   |
| Apacer                      | 16        | 22     | 0.26%   |
| JMicron Technology          | 15        | 15     | 0.25%   |
| Hewlett-Packard             | 15        | 26     | 0.25%   |
| KingDian                    | 14        | 21     | 0.23%   |
| Lexar                       | 12        | 12     | 0.2%    |
| Kingston Technology Company | 10        | 13     | 0.16%   |
| KingSpec                    | 10        | 12     | 0.16%   |
| USB3.0                      | 8         | 11     | 0.13%   |
| Netac                       | 8         | 12     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 77        | 1.15%   |
| Unknown MMC Card  32GB              | 59        | 0.88%   |
| Seagate ST500DM002-1BD142 500GB     | 55        | 0.82%   |
| Samsung SSD 860 EVO 500GB           | 52        | 0.78%   |
| Kingston SA400S37480G 480GB SSD     | 42        | 0.63%   |
| Unknown MMC Card  64GB              | 37        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 0.52%   |
| Samsung SSD 850 EVO 250GB           | 35        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB      | 34        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB     | 33        | 0.49%   |
| Samsung SSD 850 EVO 500GB           | 33        | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 31        | 0.46%   |
| Toshiba MQ01ABF050 500GB            | 30        | 0.45%   |
| Unknown SD/MMC/MS PRO 256GB         | 28        | 0.42%   |
| Toshiba MQ01ABD100 1TB              | 28        | 0.42%   |
| Kingston SA400S37120G 120GB SSD     | 28        | 0.42%   |
| Toshiba DT01ACA100 1TB              | 27        | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB      | 27        | 0.4%    |
| Seagate Expansion 1TB               | 27        | 0.4%    |
| Seagate ST3500418AS 500GB           | 26        | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB      | 26        | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB      | 25        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB      | 24        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD    | 23        | 0.34%   |
| Unknown MMC Card  128GB             | 22        | 0.33%   |
| HGST HTS721010A9E630 1TB            | 22        | 0.33%   |
| Unknown                             | 22        | 0.33%   |
| Unknown MMC Card  16GB              | 21        | 0.31%   |
| Seagate ST2000DM001-1CH164 2TB      | 21        | 0.31%   |
| Samsung SSD 860 EVO 1TB             | 21        | 0.31%   |
| HGST HTS541010A9E680 1TB            | 21        | 0.31%   |
| Seagate ST9500325AS 500GB           | 20        | 0.3%    |
| Seagate ST4000DM004-2CV104 4TB      | 20        | 0.3%    |
| Samsung SSD 860 EVO 250GB           | 20        | 0.3%    |
| Crucial CT240BX500SSD1 240GB        | 20        | 0.3%    |
| Seagate ST9320325AS 320GB           | 19        | 0.28%   |
| Seagate ST31000528AS 1TB            | 19        | 0.28%   |
| Crucial CT500MX500SSD1 500GB        | 19        | 0.28%   |
| WDC WD10JPVX-22JC3T0 1TB            | 18        | 0.27%   |
| Toshiba DT01ACA050 500GB            | 18        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1051      | 1537   | 33.07%  |
| WDC                 | 883       | 1301   | 27.78%  |
| Toshiba             | 353       | 448    | 11.11%  |
| Hitachi             | 342       | 450    | 10.76%  |
| Samsung Electronics | 197       | 274    | 6.2%    |
| HGST                | 116       | 141    | 3.65%   |
| Fujitsu             | 71        | 89     | 2.23%   |
| Maxtor              | 60        | 85     | 1.89%   |
| Unknown             | 29        | 36     | 0.91%   |
| JMicron Technology  | 7         | 7      | 0.22%   |
| IBM/Hitachi         | 7         | 7      | 0.22%   |
| TO Exter            | 6         | 8      | 0.19%   |
| Intenso             | 6         | 7      | 0.19%   |
| ASMT                | 6         | 12     | 0.19%   |
| Hewlett-Packard     | 5         | 11     | 0.16%   |
| SSK                 | 4         | 4      | 0.13%   |
| External            | 4         | 5      | 0.13%   |
| Apple               | 4         | 5      | 0.13%   |
| USB3.0              | 3         | 5      | 0.09%   |
| WD MediaMax         | 2         | 2      | 0.06%   |
| Lenovo              | 2         | 8      | 0.06%   |
| Inateck             | 2         | 2      | 0.06%   |
| HPE                 | 2         | 5      | 0.06%   |
| HGST HTS            | 2         | 2      | 0.06%   |
| ExcelStor           | 2         | 2      | 0.06%   |
| Apricorn            | 2         | 3      | 0.06%   |
| SAGE                | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 5      | 0.03%   |
| ICY BOX             | 1         | 2      | 0.03%   |
| IBM-ESXS            | 1         | 1      | 0.03%   |
| Ext Hard            | 1         | 1      | 0.03%   |
| CLOVER              | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 427       | 584    | 23.09%  |
| Kingston            | 252       | 315    | 13.63%  |
| SanDisk             | 161       | 215    | 8.71%   |
| Crucial             | 157       | 211    | 8.49%   |
| WDC                 | 90        | 116    | 4.87%   |
| A-DATA Technology   | 69        | 93     | 3.73%   |
| China               | 68        | 79     | 3.68%   |
| Intel               | 54        | 78     | 2.92%   |
| PNY                 | 42        | 56     | 2.27%   |
| Micron Technology   | 34        | 39     | 1.84%   |
| Patriot             | 32        | 37     | 1.73%   |
| Toshiba             | 31        | 38     | 1.68%   |
| Transcend           | 28        | 30     | 1.51%   |
| OCZ                 | 27        | 34     | 1.46%   |
| SPCC                | 26        | 40     | 1.41%   |
| SK hynix            | 25        | 26     | 1.35%   |
| Intenso             | 24        | 26     | 1.3%    |
| LITEON              | 19        | 21     | 1.03%   |
| LITEONIT            | 18        | 21     | 0.97%   |
| Apacer              | 15        | 21     | 0.81%   |
| KingDian            | 14        | 21     | 0.76%   |
| Lexar               | 11        | 11     | 0.59%   |
| ASMT                | 11        | 14     | 0.59%   |
| Apple               | 10        | 15     | 0.54%   |
| Unknown             | 9         | 10     | 0.49%   |
| KingSpec            | 9         | 11     | 0.49%   |
| Hewlett-Packard     | 8         | 12     | 0.43%   |
| GOODRAM             | 8         | 10     | 0.43%   |
| Smartbuy            | 7         | 7      | 0.38%   |
| Plextor             | 7         | 13     | 0.38%   |
| Corsair             | 7         | 8      | 0.38%   |
| Team                | 6         | 13     | 0.32%   |
| Netac               | 6         | 10     | 0.32%   |
| Dogfish             | 6         | 9      | 0.32%   |
| USB3.0              | 5         | 6      | 0.27%   |
| SABRENT             | 5         | 5      | 0.27%   |
| Mushkin             | 5         | 5      | 0.27%   |
| Gigabyte Technology | 5         | 7      | 0.27%   |
| FORESEE             | 5         | 9      | 0.27%   |
| Seagate             | 4         | 7      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2682      | 4471   | 49.18%  |
| SSD     | 1656      | 2402   | 30.37%  |
| NVMe    | 734       | 981    | 13.46%  |
| MMC     | 294       | 384    | 5.39%   |
| Unknown | 87        | 110    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3696      | 6630   | 74.23%  |
| NVMe | 733       | 979    | 14.72%  |
| MMC  | 294       | 384    | 5.9%    |
| SAS  | 256       | 355    | 5.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3009      | 4558   | 66.45%  |
| 0.51-1.0        | 1024      | 1510   | 22.61%  |
| 1.01-2.0        | 277       | 443    | 6.12%   |
| 3.01-4.0        | 86        | 146    | 1.9%    |
| 2.01-3.0        | 67        | 116    | 1.48%   |
| 4.01-10.0       | 58        | 91     | 1.28%   |
| 10.01-20.0      | 5         | 7      | 0.11%   |
| More than 100.0 | 1         | 1      | 0.02%   |
| 0               | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1410      | 30.65%  |
| 251-500        | 1035      | 22.5%   |
| 501-1000       | 604       | 13.13%  |
| 51-100         | 418       | 9.08%   |
| 1001-2000      | 306       | 6.65%   |
| 21-50          | 289       | 6.28%   |
| 1-20           | 216       | 4.69%   |
| More than 3000 | 183       | 3.98%   |
| 2001-3000      | 113       | 2.46%   |
| Unknown        | 27        | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1910      | 39.92%  |
| 21-50          | 825       | 17.24%  |
| 101-250        | 603       | 12.6%   |
| 51-100         | 562       | 11.75%  |
| 251-500        | 337       | 7.04%   |
| 501-1000       | 257       | 5.37%   |
| 1001-2000      | 136       | 2.84%   |
| More than 3000 | 74        | 1.55%   |
| 2001-3000      | 53        | 1.11%   |
| Unknown        | 27        | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 9      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB     | 8         | 8      | 2.17%   |
| Seagate ST9500325AS 500GB           | 6         | 8      | 1.63%   |
| Toshiba MQ01ABD100 1TB              | 5         | 6      | 1.36%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.36%   |
| Seagate ST2000DM001-1CH164 2TB      | 4         | 6      | 1.08%   |
| Samsung Electronics HM321HI 320GB   | 4         | 5      | 1.08%   |
| Toshiba MQ01ABD050 500GB            | 3         | 3      | 0.81%   |
| Toshiba DT01ACA100 1TB              | 3         | 3      | 0.81%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.81%   |
| Seagate ST3500418AS 500GB           | 3         | 4      | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 3      | 0.81%   |
| Maxtor STM3160215AS 160GB           | 3         | 3      | 0.81%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 3      | 0.81%   |
| Hitachi HDS721050CLA362 500GB       | 3         | 3      | 0.81%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 0.81%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.81%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 2      | 0.54%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 2         | 2      | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.54%   |
| WDC WD4000FYYZ-01UL1B1 4TB          | 2         | 3      | 0.54%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 2      | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 3      | 0.54%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.54%   |
| Toshiba MK5065GSXN 500GB            | 2         | 4      | 0.54%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.54%   |
| Seagate ST9500423AS 500GB           | 2         | 2      | 0.54%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.54%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.54%   |
| Seagate ST9250410AS 250GB           | 2         | 2      | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.54%   |
| Seagate ST3250318AS 250GB           | 2         | 4      | 0.54%   |
| Seagate ST3250310AS 250GB           | 2         | 2      | 0.54%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 2      | 0.54%   |
| Seagate ST31000528AS 1TB            | 2         | 2      | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB      | 2         | 2      | 0.54%   |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 2      | 0.54%   |
| Samsung Electronics HD753LJ 752GB   | 2         | 3      | 0.54%   |
| Samsung Electronics HD103SJ 1TB     | 2         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 102       | 117    | 28.25%  |
| WDC                 | 71        | 83     | 19.67%  |
| Toshiba             | 35        | 41     | 9.7%    |
| Hitachi             | 33        | 40     | 9.14%   |
| Samsung Electronics | 27        | 34     | 7.48%   |
| Kingston            | 11        | 13     | 3.05%   |
| HGST                | 10        | 13     | 2.77%   |
| Maxtor              | 8         | 8      | 2.22%   |
| Fujitsu             | 8         | 9      | 2.22%   |
| Intel               | 6         | 7      | 1.66%   |
| SK hynix            | 5         | 6      | 1.39%   |
| SanDisk             | 4         | 4      | 1.11%   |
| Micron Technology   | 4         | 4      | 1.11%   |
| A-DATA Technology   | 4         | 5      | 1.11%   |
| Crucial             | 3         | 3      | 0.83%   |
| OCZ                 | 2         | 2      | 0.55%   |
| LITEON              | 2         | 2      | 0.55%   |
| KingDian            | 2         | 4      | 0.55%   |
| Hewlett-Packard     | 2         | 3      | 0.55%   |
| China               | 2         | 2      | 0.55%   |
| Unknown             | 1         | 1      | 0.28%   |
| SSSTC               | 1         | 1      | 0.28%   |
| SPCC                | 1         | 1      | 0.28%   |
| PNY                 | 1         | 1      | 0.28%   |
| Netac               | 1         | 1      | 0.28%   |
| Neo Forza           | 1         | 1      | 0.28%   |
| Mushkin             | 1         | 1      | 0.28%   |
| LDLC                | 1         | 1      | 0.28%   |
| KEEPDATA            | 1         | 1      | 0.28%   |
| JMicron Technology  | 1         | 1      | 0.28%   |
| Intenso             | 1         | 1      | 0.28%   |
| ICY BOX             | 1         | 2      | 0.28%   |
| FORESEE             | 1         | 1      | 0.28%   |
| Drevo               | 1         | 1      | 0.28%   |
| Corsair             | 1         | 1      | 0.28%   |
| Avant               | 1         | 1      | 0.28%   |
| ASMT                | 1         | 4      | 0.28%   |
| Apple               | 1         | 2      | 0.28%   |
| Apacer              | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 102       | 117    | 35.42%  |
| WDC                 | 68        | 80     | 23.61%  |
| Toshiba             | 34        | 40     | 11.81%  |
| Hitachi             | 33        | 40     | 11.46%  |
| Samsung Electronics | 20        | 26     | 6.94%   |
| HGST                | 10        | 13     | 3.47%   |
| Maxtor              | 8         | 8      | 2.78%   |
| Fujitsu             | 8         | 9      | 2.78%   |
| Hewlett-Packard     | 2         | 3      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.35%   |
| ICY BOX             | 1         | 2      | 0.35%   |
| ASMT                | 1         | 4      | 0.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 271       | 343    | 79.24%  |
| SSD  | 67        | 78     | 19.59%  |
| NVMe | 4         | 4      | 1.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1      | 16.67%  |
| WDC WD20EARS-00J99B0 2TB            | 1         | 2      | 16.67%  |
| Toshiba DT01ACA200 2TB              | 1         | 1      | 16.67%  |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 16.67%  |
| Seagate ST500DM002-1BC142 500GB     | 1         | 1      | 16.67%  |
| A-DATA Technology SP800 32GB SSD    | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 3      | 33.33%  |
| Seagate           | 2         | 2      | 33.33%  |
| Toshiba           | 1         | 1      | 16.67%  |
| A-DATA Technology | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2954      | 5580   | 63.16%  |
| Works    | 1381      | 2336   | 29.53%  |
| Malfunc  | 336       | 425    | 7.18%   |
| Failed   | 6         | 7      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3036      | 60.32%  |
| AMD                              | 760       | 15.1%   |
| Samsung Electronics              | 254       | 5.05%   |
| Nvidia                           | 151       | 3%      |
| SanDisk                          | 113       | 2.25%   |
| JMicron Technology               | 76        | 1.51%   |
| ASMedia Technology               | 73        | 1.45%   |
| SK hynix                         | 65        | 1.29%   |
| VIA Technologies                 | 55        | 1.09%   |
| Marvell Technology Group         | 54        | 1.07%   |
| Kingston Technology Company      | 48        | 0.95%   |
| Silicon Integrated Systems [SiS] | 42        | 0.83%   |
| Phison Electronics               | 39        | 0.77%   |
| Toshiba America Info Systems     | 30        | 0.6%    |
| KIOXIA                           | 27        | 0.54%   |
| Silicon Motion                   | 23        | 0.46%   |
| Micron/Crucial Technology        | 22        | 0.44%   |
| Micron Technology                | 21        | 0.42%   |
| ADATA Technology                 | 18        | 0.36%   |
| LSI Logic / Symbios Logic        | 16        | 0.32%   |
| Realtek Semiconductor            | 15        | 0.3%    |
| Broadcom / LSI                   | 14        | 0.28%   |
| Silicon Image                    | 11        | 0.22%   |
| Apple                            | 7         | 0.14%   |
| Adaptec                          | 7         | 0.14%   |
| ULi Electronics                  | 6         | 0.12%   |
| Hewlett-Packard                  | 6         | 0.12%   |
| Union Memory (Shenzhen)          | 5         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 5         | 0.1%    |
| Integrated Technology Express    | 5         | 0.1%    |
| Seagate Technology               | 4         | 0.08%   |
| Promise Technology               | 4         | 0.08%   |
| Lenovo                           | 4         | 0.08%   |
| Lite-On Technology               | 3         | 0.06%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Hosin Global Electronics         | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| TenaFe                           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 446       | 7.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 195       | 3.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 183       | 2.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 178       | 2.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 160       | 2.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 150       | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 139       | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 136       | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 136       | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 134       | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 116       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 116       | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 107       | 1.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 106       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 100       | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 83        | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 81        | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 78        | 1.25%   |
| Intel SATA Controller [RAID mode]                                                       | 74        | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 71        | 1.13%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 69        | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 69        | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 68        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 66        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 64        | 1.02%   |
| Nvidia MCP61 SATA Controller                                                            | 63        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 63        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 63        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 57        | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 54        | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 52        | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 51        | 0.81%   |
| Nvidia MCP61 IDE                                                                        | 50        | 0.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 50        | 0.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 48        | 0.77%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 47        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 47        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 47        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 46        | 0.73%   |
| AMD 500 Series Chipset SATA Controller                                                  | 42        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3003      | 56.3%   |
| IDE  | 1269      | 23.79%  |
| NVMe | 729       | 13.67%  |
| RAID | 304       | 5.7%    |
| SAS  | 16        | 0.3%    |
| SCSI | 13        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3402      | 77.06%  |
| AMD          | 951       | 21.54%  |
| ARM          | 57        | 1.29%   |
| CentaurHauls | 4         | 0.09%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Processor                           | 45        | 1.02%   |
| Intel Atom CPU N270 @ 1.60GHz           | 33        | 0.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 29        | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 27        | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 27        | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 25        | 0.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 25        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 24        | 0.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 24        | 0.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 24        | 0.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 24        | 0.54%   |
| Intel Pentium 4 CPU 3.00GHz             | 23        | 0.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 23        | 0.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 23        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 23        | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 23        | 0.52%   |
| Intel Atom CPU N450 @ 1.66GHz           | 22        | 0.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.47%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 21        | 0.47%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 21        | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 0.45%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 20        | 0.45%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 19        | 0.43%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 19        | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 18        | 0.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 18        | 0.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 18        | 0.41%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 18        | 0.41%   |
| AMD Ryzen 5 3600 6-Core Processor       | 18        | 0.41%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 17        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 17        | 0.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 17        | 0.38%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 17        | 0.38%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 17        | 0.38%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 17        | 0.38%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 17        | 0.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 16        | 0.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 16        | 0.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.34%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 746       | 16.84%  |
| Intel Core i7           | 556       | 12.55%  |
| Intel Core 2 Duo        | 343       | 7.74%   |
| Intel Core i3           | 341       | 7.7%    |
| Intel Celeron           | 320       | 7.23%   |
| Other                   | 194       | 4.38%   |
| Intel Atom              | 188       | 4.24%   |
| AMD Ryzen 5             | 143       | 3.23%   |
| Intel Pentium           | 128       | 2.89%   |
| Intel Xeon              | 108       | 2.44%   |
| AMD Ryzen 7             | 105       | 2.37%   |
| Intel Pentium Dual-Core | 92        | 2.08%   |
| Intel Pentium Dual      | 68        | 1.54%   |
| Intel Pentium 4         | 66        | 1.49%   |
| Intel Core 2            | 61        | 1.38%   |
| Intel Genuine           | 60        | 1.35%   |
| Intel Core 2 Quad       | 58        | 1.31%   |
| AMD FX                  | 56        | 1.26%   |
| AMD A8                  | 53        | 1.2%    |
| AMD Ryzen 9             | 42        | 0.95%   |
| AMD Athlon 64 X2        | 42        | 0.95%   |
| AMD A6                  | 35        | 0.79%   |
| AMD E1                  | 34        | 0.77%   |
| AMD Ryzen 3             | 33        | 0.75%   |
| AMD Phenom II X4        | 31        | 0.7%    |
| Intel Pentium M         | 29        | 0.65%   |
| AMD Athlon II X2        | 29        | 0.65%   |
| AMD A4                  | 28        | 0.63%   |
| Intel Celeron M         | 26        | 0.59%   |
| AMD A10                 | 24        | 0.54%   |
| AMD E                   | 21        | 0.47%   |
| AMD Turion 64 X2 Mobile | 20        | 0.45%   |
| AMD Sempron             | 20        | 0.45%   |
| AMD Athlon              | 20        | 0.45%   |
| AMD Ryzen 7 PRO         | 19        | 0.43%   |
| Intel Pentium D         | 17        | 0.38%   |
| Intel Core i9           | 17        | 0.38%   |
| AMD E2                  | 16        | 0.36%   |
| AMD Athlon 64           | 16        | 0.36%   |
| Intel Pentium Silver    | 14        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2124      | 47.98%  |
| 4       | 1354      | 30.59%  |
| 1       | 365       | 8.24%   |
| 6       | 247       | 5.58%   |
| 8       | 190       | 4.29%   |
| 12      | 46        | 1.04%   |
| 16      | 29        | 0.66%   |
| 3       | 21        | 0.47%   |
| 10      | 17        | 0.38%   |
| Unknown | 12        | 0.27%   |
| 14      | 9         | 0.2%    |
| 24      | 4         | 0.09%   |
| 20      | 4         | 0.09%   |
| 64      | 3         | 0.07%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4353      | 98.6%   |
| 2       | 51        | 1.16%   |
| Unknown | 11        | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2238      | 50.63%  |
| 1       | 2169      | 49.07%  |
| Unknown | 12        | 0.27%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4178      | 94.61%  |
| 32-bit         | 201       | 4.55%   |
| Unknown        | 32        | 0.72%   |
| 64-bit         | 5         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 995       | 21.87%  |
| 0x206a7    | 279       | 6.13%   |
| 0x306a9    | 255       | 5.6%    |
| 0x1067a    | 244       | 5.36%   |
| 0x306c3    | 172       | 3.78%   |
| 0x6fd      | 147       | 3.23%   |
| 0x20655    | 91        | 2%      |
| 0x10676    | 85        | 1.87%   |
| 0x40651    | 70        | 1.54%   |
| 0x506e3    | 67        | 1.47%   |
| 0x906ea    | 65        | 1.43%   |
| 0x30678    | 62        | 1.36%   |
| 0x406c4    | 61        | 1.34%   |
| 0x406e3    | 60        | 1.32%   |
| 0x106ca    | 55        | 1.21%   |
| 0x010000c8 | 55        | 1.21%   |
| 0x6fb      | 54        | 1.19%   |
| 0x6f6      | 54        | 1.19%   |
| 0x806ea    | 51        | 1.12%   |
| 0x806ec    | 49        | 1.08%   |
| 0x106c2    | 49        | 1.08%   |
| 0x806c1    | 48        | 1.05%   |
| 0x20652    | 46        | 1.01%   |
| 0x806e9    | 44        | 0.97%   |
| 0x906e9    | 43        | 0.95%   |
| 0x306d4    | 43        | 0.95%   |
| 0x06000852 | 41        | 0.9%    |
| 0x08108109 | 40        | 0.88%   |
| 0x6e8      | 37        | 0.81%   |
| 0x08701021 | 36        | 0.79%   |
| 0x406c3    | 35        | 0.77%   |
| 0x05000119 | 35        | 0.77%   |
| 0x6d8      | 34        | 0.75%   |
| 0x106e5    | 34        | 0.75%   |
| 0x0800820d | 33        | 0.73%   |
| 0x07030105 | 31        | 0.68%   |
| 0x0700010f | 30        | 0.66%   |
| 0x506c9    | 27        | 0.59%   |
| 0x03000027 | 27        | 0.59%   |
| 0x706a1    | 26        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 390       | 8.81%   |
| KabyLake         | 381       | 8.6%    |
| SandyBridge      | 346       | 7.81%   |
| Core             | 320       | 7.23%   |
| IvyBridge        | 316       | 7.14%   |
| Haswell          | 316       | 7.14%   |
| Silvermont       | 203       | 4.58%   |
| Westmere         | 180       | 4.07%   |
| Skylake          | 168       | 3.79%   |
| Bonnell          | 132       | 2.98%   |
| K8 Hammer        | 127       | 2.87%   |
| Unknown          | 127       | 2.87%   |
| K10              | 123       | 2.78%   |
| Zen 2            | 118       | 2.66%   |
| P6               | 104       | 2.35%   |
| Zen+             | 101       | 2.28%   |
| NetBurst         | 93        | 2.1%    |
| Piledriver       | 81        | 1.83%   |
| CometLake        | 71        | 1.6%    |
| TigerLake        | 70        | 1.58%   |
| Broadwell        | 65        | 1.47%   |
| Zen 3            | 63        | 1.42%   |
| Zen              | 57        | 1.29%   |
| Nehalem          | 57        | 1.29%   |
| Goldmont plus    | 57        | 1.29%   |
| Bobcat           | 51        | 1.15%   |
| Excavator        | 44        | 0.99%   |
| Goldmont         | 43        | 0.97%   |
| Puma             | 40        | 0.9%    |
| IceLake          | 40        | 0.9%    |
| Jaguar           | 35        | 0.79%   |
| K10 Llano        | 31        | 0.7%    |
| Alderlake Hybrid | 29        | 0.65%   |
| Steamroller      | 15        | 0.34%   |
| K8 & K10 hybrid  | 12        | 0.27%   |
| Bulldozer        | 11        | 0.25%   |
| K6               | 6         | 0.14%   |
| Tremont          | 5         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2498      | 50.87%  |
| Nvidia                           | 1235      | 25.15%  |
| AMD                              | 1095      | 22.3%   |
| Silicon Integrated Systems [SiS] | 28        | 0.57%   |
| Matrox Electronics Systems       | 25        | 0.51%   |
| VIA Technologies                 | 19        | 0.39%   |
| ASPEED Technology                | 9         | 0.18%   |
| S3 Graphics                      | 1         | 0.02%   |
| Alliance Semiconductor           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 259       | 4.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 168       | 3.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 131       | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 111       | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 110       | 2.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 95        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 92        | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 92        | 1.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 88        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 88        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 1.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 70        | 1.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 66        | 1.26%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 64        | 1.23%   |
| Intel UHD Graphics 620                                                                   | 62        | 1.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 62        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 57        | 1.09%   |
| Intel HD Graphics 620                                                                    | 57        | 1.09%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 56        | 1.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 52        | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 51        | 0.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 49        | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 47        | 0.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 0.88%   |
| Intel HD Graphics 5500                                                                   | 45        | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 45        | 0.86%   |
| Intel HD Graphics 530                                                                    | 44        | 0.84%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 44        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 38        | 0.73%   |
| Intel HD Graphics 500                                                                    | 36        | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 0.69%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 35        | 0.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 33        | 0.63%   |
| Intel HD Graphics 630                                                                    | 32        | 0.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 32        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 31        | 0.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 30        | 0.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 29        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 2015      | 45.36%  |
| 1 x AMD                              | 868       | 19.54%  |
| 1 x Nvidia                           | 844       | 19%     |
| Intel + Nvidia                       | 330       | 7.43%   |
| Intel + AMD                          | 100       | 2.25%   |
| 2 x AMD                              | 79        | 1.78%   |
| Other                                | 70        | 1.58%   |
| AMD + Nvidia                         | 39        | 0.88%   |
| 1 x SiS                              | 28        | 0.63%   |
| 1 x VIA                              | 19        | 0.43%   |
| 1 x Matrox                           | 19        | 0.43%   |
| 2 x Nvidia                           | 6         | 0.14%   |
| Nvidia + ASPEED                      | 6         | 0.14%   |
| 2 x Intel                            | 3         | 0.07%   |
| Nvidia + Matrox                      | 3         | 0.07%   |
| 2 x AMD + 1 x Nvidia                 | 2         | 0.05%   |
| 1 x ASPEED                           | 2         | 0.05%   |
| AMD + Matrox                         | 2         | 0.05%   |
| 3 x AMD                              | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.02%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.02%   |
| 1 x S3 Graphics                      | 1         | 0.02%   |
| Intel + 2 x AMD                      | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia             | 1         | 0.02%   |
| AMD + ASPEED                         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3559      | 79.91%  |
| Proprietary | 669       | 15.02%  |
| Unknown     | 226       | 5.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2368      | 52.48%  |
| 0.01-0.5   | 848       | 18.79%  |
| 1.01-2.0   | 494       | 10.95%  |
| 0.51-1.0   | 389       | 8.62%   |
| 3.01-4.0   | 214       | 4.74%   |
| 7.01-8.0   | 89        | 1.97%   |
| 5.01-6.0   | 57        | 1.26%   |
| 8.01-16.0  | 29        | 0.64%   |
| 2.01-3.0   | 19        | 0.42%   |
| 4.01-5.0   | 2         | 0.04%   |
| 16.01-24.0 | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 648       | 14.21%  |
| AU Optronics            | 503       | 11.03%  |
| LG Display              | 392       | 8.59%   |
| Dell                    | 263       | 5.77%   |
| BOE                     | 263       | 5.77%   |
| Chimei Innolux          | 256       | 5.61%   |
| Goldstar                | 216       | 4.74%   |
| Hewlett-Packard         | 171       | 3.75%   |
| Acer                    | 165       | 3.62%   |
| AOC                     | 118       | 2.59%   |
| Philips                 | 114       | 2.5%    |
| Lenovo                  | 105       | 2.3%    |
| Chi Mei Optoelectronics | 103       | 2.26%   |
| Ancor Communications    | 92        | 2.02%   |
| BenQ                    | 82        | 1.8%    |
| LG Philips              | 75        | 1.64%   |
| Apple                   | 67        | 1.47%   |
| ViewSonic               | 56        | 1.23%   |
| HannStar                | 52        | 1.14%   |
| Iiyama                  | 49        | 1.07%   |
| Sony                    | 40        | 0.88%   |
| Unknown                 | 39        | 0.86%   |
| Sharp                   | 39        | 0.86%   |
| InfoVision              | 39        | 0.86%   |
| LG Electronics          | 37        | 0.81%   |
| Fujitsu Siemens         | 30        | 0.66%   |
| NEC Computers           | 26        | 0.57%   |
| CPT                     | 25        | 0.55%   |
| PANDA                   | 24        | 0.53%   |
| Panasonic               | 22        | 0.48%   |
| Eizo                    | 19        | 0.42%   |
| ASUSTek Computer        | 18        | 0.39%   |
| Toshiba                 | 17        | 0.37%   |
| Vizio                   | 14        | 0.31%   |
| Medion                  | 14        | 0.31%   |
| Quanta Display          | 11        | 0.24%   |
| PKB                     | 11        | 0.24%   |
| Packard Bell            | 11        | 0.24%   |
| Vestel Elektronik       | 10        | 0.22%   |
| RTK                     | 10        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 28        | 0.59%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 23        | 0.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 20        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 19        | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.36%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 16        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 11        | 0.23%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 10        | 0.21%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 10        | 0.21%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.21%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 10        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.21%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                     | 9         | 0.19%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.19%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch              | 9         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.19%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 9         | 0.19%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 9         | 0.19%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch     | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.17%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 8         | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.17%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch            | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.17%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.17%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 7         | 0.15%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1519      | 34.16%  |
| 1366x768 (WXGA)    | 963       | 21.66%  |
| 1280x800 (WXGA)    | 267       | 6%      |
| 1280x1024 (SXGA)   | 243       | 5.46%   |
| 1600x900 (HD+)     | 216       | 4.86%   |
| 1440x900 (WXGA+)   | 190       | 4.27%   |
| 3840x2160 (4K)     | 183       | 4.12%   |
| 1680x1050 (WSXGA+) | 165       | 3.71%   |
| 2560x1440 (QHD)    | 132       | 2.97%   |
| 1920x1200 (WUXGA)  | 112       | 2.52%   |
| 1024x600           | 72        | 1.62%   |
| Unknown            | 61        | 1.37%   |
| 1024x768 (XGA)     | 50        | 1.12%   |
| 1360x768           | 45        | 1.01%   |
| 3840x1080          | 24        | 0.54%   |
| 2560x1080          | 19        | 0.43%   |
| 2560x1600          | 18        | 0.4%    |
| 1920x540           | 18        | 0.4%    |
| 1600x1200          | 18        | 0.4%    |
| 3440x1440          | 17        | 0.38%   |
| 1280x720 (HD)      | 10        | 0.22%   |
| 2288x1287          | 8         | 0.18%   |
| 3200x1080          | 6         | 0.13%   |
| 3200x1800 (QHD+)   | 5         | 0.11%   |
| 2160x1440          | 5         | 0.11%   |
| 2048x1152          | 5         | 0.11%   |
| 1400x1050          | 5         | 0.11%   |
| 5120x1440          | 4         | 0.09%   |
| 3840x1200          | 4         | 0.09%   |
| 2880x1800          | 4         | 0.09%   |
| 3840x2400          | 3         | 0.07%   |
| 3840x1600          | 3         | 0.07%   |
| 4480x1440          | 2         | 0.04%   |
| 3600x1080          | 2         | 0.04%   |
| 3286x1080          | 2         | 0.04%   |
| 3200x900           | 2         | 0.04%   |
| 3000x2000          | 2         | 0.04%   |
| 2960x1050          | 2         | 0.04%   |
| 2736x1824          | 2         | 0.04%   |
| 2304x1440          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1087      | 23.89%  |
| 14      | 346       | 7.6%    |
| 17      | 334       | 7.34%   |
| Unknown | 314       | 6.9%    |
| 13      | 305       | 6.7%    |
| 23      | 267       | 5.87%   |
| 21      | 259       | 5.69%   |
| 24      | 258       | 5.67%   |
| 27      | 206       | 4.53%   |
| 19      | 206       | 4.53%   |
| 18      | 145       | 3.19%   |
| 20      | 109       | 2.4%    |
| 12      | 91        | 2%      |
| 22      | 89        | 1.96%   |
| 31      | 83        | 1.82%   |
| 10      | 79        | 1.74%   |
| 11      | 77        | 1.69%   |
| 84      | 35        | 0.77%   |
| 34      | 27        | 0.59%   |
| 54      | 25        | 0.55%   |
| 16      | 25        | 0.55%   |
| 72      | 22        | 0.48%   |
| 40      | 21        | 0.46%   |
| 32      | 21        | 0.46%   |
| 26      | 16        | 0.35%   |
| 25      | 16        | 0.35%   |
| 52      | 11        | 0.24%   |
| 28      | 10        | 0.22%   |
| 37      | 9         | 0.2%    |
| 48      | 7         | 0.15%   |
| 46      | 6         | 0.13%   |
| 29      | 5         | 0.11%   |
| 49      | 4         | 0.09%   |
| 8       | 4         | 0.09%   |
| 142     | 3         | 0.07%   |
| 65      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 86      | 2         | 0.04%   |
| 74      | 2         | 0.04%   |
| 63      | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1683      | 37.42%  |
| 501-600        | 701       | 15.59%  |
| 401-500        | 677       | 15.05%  |
| 201-300        | 407       | 9.05%   |
| 351-400        | 370       | 8.23%   |
| Unknown        | 314       | 6.98%   |
| 601-700        | 125       | 2.78%   |
| 1001-1500      | 64        | 1.42%   |
| 1501-2000      | 60        | 1.33%   |
| 701-800        | 50        | 1.11%   |
| 801-900        | 34        | 0.76%   |
| 101-200        | 5         | 0.11%   |
| 901-1000       | 4         | 0.09%   |
| More than 2000 | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2820      | 66.79%  |
| 16/10   | 712       | 16.86%  |
| Unknown | 283       | 6.7%    |
| 5/4     | 227       | 5.38%   |
| 4/3     | 86        | 2.04%   |
| 21/9    | 33        | 0.78%   |
| 3/2     | 31        | 0.73%   |
| 6/5     | 12        | 0.28%   |
| 32/9    | 6         | 0.14%   |
| 1.00    | 5         | 0.12%   |
| 0.56    | 2         | 0.05%   |
| 3.73    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.75    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1086      | 24.02%  |
| 201-250        | 708       | 15.66%  |
| 81-90          | 518       | 11.46%  |
| 151-200        | 410       | 9.07%   |
| Unknown        | 314       | 6.95%   |
| 141-150        | 233       | 5.15%   |
| 301-350        | 214       | 4.73%   |
| 121-130        | 166       | 3.67%   |
| 351-500        | 142       | 3.14%   |
| 71-80          | 117       | 2.59%   |
| More than 1000 | 116       | 2.57%   |
| 251-300        | 109       | 2.41%   |
| 61-70          | 83        | 1.84%   |
| 51-60          | 78        | 1.73%   |
| 41-50          | 78        | 1.73%   |
| 131-140        | 52        | 1.15%   |
| 501-1000       | 50        | 1.11%   |
| 91-100         | 25        | 0.55%   |
| 111-120        | 17        | 0.38%   |
| 1-40           | 5         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1673      | 38.21%  |
| 101-120       | 1274      | 29.09%  |
| 121-160       | 851       | 19.43%  |
| Unknown       | 314       | 7.17%   |
| 161-240       | 132       | 3.01%   |
| 1-50          | 101       | 2.31%   |
| More than 240 | 34        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3693      | 82.05%  |
| 2     | 557       | 12.38%  |
| 0     | 200       | 4.44%   |
| 3     | 47        | 1.04%   |
| 4     | 4         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2313      | 34.16%  |
| Intel                             | 1821      | 26.89%  |
| Qualcomm Atheros                  | 831       | 12.27%  |
| Broadcom                          | 480       | 7.09%   |
| Marvell Technology Group          | 159       | 2.35%   |
| Broadcom Limited                  | 128       | 1.89%   |
| Nvidia                            | 123       | 1.82%   |
| Ralink Technology                 | 100       | 1.48%   |
| Ralink                            | 89        | 1.31%   |
| TP-Link                           | 79        | 1.17%   |
| MediaTek                          | 51        | 0.75%   |
| VIA Technologies                  | 42        | 0.62%   |
| Qualcomm Atheros Communications   | 38        | 0.56%   |
| Samsung Electronics               | 36        | 0.53%   |
| Silicon Integrated Systems [SiS]  | 34        | 0.5%    |
| Huawei Technologies               | 29        | 0.43%   |
| D-Link System                     | 27        | 0.4%    |
| NetGear                           | 26        | 0.38%   |
| JMicron Technology                | 24        | 0.35%   |
| D-Link                            | 24        | 0.35%   |
| Sierra Wireless                   | 20        | 0.3%    |
| ASIX Electronics                  | 18        | 0.27%   |
| Ericsson Business Mobile Networks | 17        | 0.25%   |
| Attansic Technology               | 15        | 0.22%   |
| Xiaomi                            | 13        | 0.19%   |
| Dell                              | 13        | 0.19%   |
| DisplayLink                       | 12        | 0.18%   |
| Belkin Components                 | 12        | 0.18%   |
| ASUSTek Computer                  | 12        | 0.18%   |
| Qualcomm                          | 11        | 0.16%   |
| Lenovo                            | 10        | 0.15%   |
| Edimax Technology                 | 10        | 0.15%   |
| Aquantia                          | 10        | 0.15%   |
| AMD                               | 8         | 0.12%   |
| Linksys                           | 7         | 0.1%    |
| Fibocom                           | 7         | 0.1%    |
| Microsoft                         | 6         | 0.09%   |
| ZyDAS                             | 5         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.07%   |
| ULi Electronics                   | 5         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1461      | 18.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 354       | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 187       | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 127       | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 110       | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 102       | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 100       | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 96        | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 95        | 1.21%   |
| Intel Wireless 7260                                                     | 85        | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 77        | 0.98%   |
| Intel Wireless 7265                                                     | 74        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 72        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 70        | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 68        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 0.86%   |
| Intel Wireless 8265 / 8275                                              | 67        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 67        | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 59        | 0.75%   |
| Intel Wireless 8260                                                     | 59        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 0.71%   |
| Nvidia MCP61 Ethernet                                                   | 56        | 0.71%   |
| Intel I211 Gigabit Network Connection                                   | 55        | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                       | 53        | 0.67%   |
| Intel Wireless 3165                                                     | 53        | 0.67%   |
| Intel Wi-Fi 6 AX201                                                     | 49        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 45        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 44        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 44        | 0.56%   |
| Intel 82579V Gigabit Network Connection                                 | 44        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                         | 41        | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                    | 41        | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 40        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 40        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 38        | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 36        | 0.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 35        | 0.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 35        | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 34        | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 33        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1268      | 37.02%  |
| Qualcomm Atheros                      | 674       | 19.68%  |
| Realtek Semiconductor                 | 587       | 17.14%  |
| Broadcom                              | 294       | 8.58%   |
| Ralink Technology                     | 100       | 2.92%   |
| Ralink                                | 89        | 2.6%    |
| TP-Link                               | 74        | 2.16%   |
| Broadcom Limited                      | 61        | 1.78%   |
| MediaTek                              | 40        | 1.17%   |
| Qualcomm Atheros Communications       | 38        | 1.11%   |
| NetGear                               | 26        | 0.76%   |
| D-Link                                | 23        | 0.67%   |
| Sierra Wireless                       | 20        | 0.58%   |
| D-Link System                         | 19        | 0.55%   |
| Belkin Components                     | 12        | 0.35%   |
| ASUSTek Computer                      | 11        | 0.32%   |
| Edimax Technology                     | 10        | 0.29%   |
| Dell                                  | 8         | 0.23%   |
| Qualcomm                              | 7         | 0.2%    |
| Fibocom                               | 7         | 0.2%    |
| Microsoft                             | 6         | 0.18%   |
| Linksys                               | 6         | 0.18%   |
| ZyDAS                                 | 5         | 0.15%   |
| Sitecom Europe                        | 5         | 0.15%   |
| Marvell Technology Group              | 4         | 0.12%   |
| IMC Networks                          | 4         | 0.12%   |
| AVM                                   | 4         | 0.12%   |
| TRENDnet                              | 3         | 0.09%   |
| Ericsson Business Mobile Networks     | 3         | 0.09%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Toshiba                               | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 127       | 3.67%   |
| Intel Wi-Fi 6 AX200                                                     | 110       | 3.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 102       | 2.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 100       | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 96        | 2.77%   |
| Intel Wireless 7260                                                     | 85        | 2.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 77        | 2.22%   |
| Intel Wireless 7265                                                     | 74        | 2.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 72        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 70        | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 68        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 67        | 1.94%   |
| Intel Wireless 8260                                                     | 59        | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 1.62%   |
| Intel Wireless 3165                                                     | 53        | 1.53%   |
| Intel Wi-Fi 6 AX201                                                     | 49        | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 45        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 44        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 44        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                         | 41        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 40        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 40        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 36        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 35        | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 35        | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                         | 33        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 33        | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 32        | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 32        | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 30        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 30        | 0.87%   |
| Intel Wireless 3160                                                     | 30        | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 30        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 27        | 0.78%   |
| Realtek 802.11ac NIC                                                    | 26        | 0.75%   |
| Intel WiFi Link 5100                                                    | 26        | 0.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 26        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2044      | 48.41%  |
| Intel                            | 1028      | 24.35%  |
| Qualcomm Atheros                 | 257       | 6.09%   |
| Broadcom                         | 235       | 5.57%   |
| Marvell Technology Group         | 155       | 3.67%   |
| Nvidia                           | 122       | 2.89%   |
| Broadcom Limited                 | 68        | 1.61%   |
| VIA Technologies                 | 42        | 0.99%   |
| Samsung Electronics              | 35        | 0.83%   |
| Silicon Integrated Systems [SiS] | 32        | 0.76%   |
| JMicron Technology               | 24        | 0.57%   |
| Huawei Technologies              | 18        | 0.43%   |
| ASIX Electronics                 | 18        | 0.43%   |
| Attansic Technology              | 15        | 0.36%   |
| Xiaomi                           | 12        | 0.28%   |
| MediaTek                         | 12        | 0.28%   |
| DisplayLink                      | 12        | 0.28%   |
| Lenovo                           | 10        | 0.24%   |
| Aquantia                         | 10        | 0.24%   |
| D-Link System                    | 8         | 0.19%   |
| TP-Link                          | 5         | 0.12%   |
| IBM                              | 5         | 0.12%   |
| HTC (High Tech Computer)         | 5         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.09%   |
| Qualcomm                         | 4         | 0.09%   |
| LG Electronics                   | 4         | 0.09%   |
| OPPO Electronics                 | 3         | 0.07%   |
| Motorola PCS                     | 3         | 0.07%   |
| Insyde Software                  | 3         | 0.07%   |
| Hewlett-Packard                  | 3         | 0.07%   |
| Apple                            | 3         | 0.07%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| Microchip Technology             | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Accton Technology                | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| ULi Electronics                  | 1         | 0.02%   |
| T & A Mobile Phones              | 1         | 0.02%   |
| NetXen Incorporated              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1461      | 34.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 354       | 8.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 187       | 4.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 95        | 2.21%   |
| Intel Ethernet Connection I217-LM                                      | 67        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 59        | 1.37%   |
| Nvidia MCP61 Ethernet                                                  | 56        | 1.31%   |
| Intel I211 Gigabit Network Connection                                  | 55        | 1.28%   |
| Realtek RTL8125 2.5GbE Controller                                      | 53        | 1.24%   |
| Intel 82579V Gigabit Network Connection                                | 44        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 41        | 0.96%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 38        | 0.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 34        | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 32        | 0.75%   |
| Intel Ethernet Connection I219-LM                                      | 32        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 31        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 31        | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 30        | 0.7%    |
| Intel 82577LM Gigabit Network Connection                               | 30        | 0.7%    |
| Intel 82567LM Gigabit Network Connection                               | 29        | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 27        | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 27        | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 25        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 24        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 24        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 22        | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 22        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 21        | 0.49%   |
| Intel 82566MM Gigabit Network Connection                               | 21        | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 20        | 0.47%   |
| Nvidia MCP79 Ethernet                                                  | 20        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 20        | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 19        | 0.44%   |
| Intel Ethernet Connection I218-LM                                      | 19        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                  | 19        | 0.44%   |
| Intel 82574L Gigabit Network Connection                                | 19        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 18        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 18        | 0.42%   |
| Intel PRO/100 VE Network Connection                                    | 17        | 0.4%    |
| Intel Ethernet Controller I225-V                                       | 17        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3966      | 54.43%  |
| WiFi     | 3207      | 44.02%  |
| Modem    | 106       | 1.45%   |
| Unknown  | 7         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2546      | 55.75%  |
| Ethernet | 2021      | 44.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2446      | 55.18%  |
| 1     | 1747      | 39.41%  |
| 0     | 137       | 3.09%   |
| 3     | 74        | 1.67%   |
| 4     | 21        | 0.47%   |
| 5     | 4         | 0.09%   |
| 6     | 2         | 0.05%   |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3722      | 83.02%  |
| Yes  | 761       | 16.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 805       | 39.35%  |
| Realtek Semiconductor           | 193       | 9.43%   |
| Broadcom                        | 186       | 9.09%   |
| Qualcomm Atheros Communications | 174       | 8.5%    |
| Cambridge Silicon Radio         | 136       | 6.65%   |
| Apple                           | 75        | 3.67%   |
| IMC Networks                    | 71        | 3.47%   |
| Lite-On Technology              | 69        | 3.37%   |
| Foxconn / Hon Hai               | 65        | 3.18%   |
| Dell                            | 57        | 2.79%   |
| Hewlett-Packard                 | 52        | 2.54%   |
| ASUSTek Computer                | 32        | 1.56%   |
| Toshiba                         | 21        | 1.03%   |
| Ralink                          | 17        | 0.83%   |
| MediaTek                        | 15        | 0.73%   |
| Alps Electric                   | 15        | 0.73%   |
| Realtek                         | 8         | 0.39%   |
| Integrated System Solution      | 8         | 0.39%   |
| Foxconn International           | 8         | 0.39%   |
| Ralink Technology               | 7         | 0.34%   |
| TP-Link                         | 6         | 0.29%   |
| Chicony Electronics             | 4         | 0.2%    |
| Taiyo Yuden                     | 3         | 0.15%   |
| Edimax Technology               | 3         | 0.15%   |
| Qcom                            | 2         | 0.1%    |
| Micro Star International        | 2         | 0.1%    |
| Fujitsu                         | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| Syntek                          | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 348       | 16.99%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 136       | 6.64%   |
| Realtek Bluetooth Radio                                                             | 132       | 6.45%   |
| Intel AX201 Bluetooth                                                               | 113       | 5.52%   |
| Intel AX200 Bluetooth                                                               | 109       | 5.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 87        | 4.25%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 68        | 3.32%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 46        | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 36        | 1.76%   |
| Intel Bluetooth Device                                                              | 36        | 1.76%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 35        | 1.71%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 34        | 1.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 33        | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 27        | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 27        | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 24        | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 23        | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 22        | 1.07%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 22        | 1.07%   |
| Apple Bluetooth HCI                                                                 | 22        | 1.07%   |
| IMC Networks Bluetooth Radio                                                        | 21        | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 21        | 1.03%   |
| Intel AX210 Bluetooth                                                               | 20        | 0.98%   |
| IMC Networks Bluetooth Device                                                       | 20        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 20        | 0.98%   |
| Lite-On Bluetooth Device                                                            | 19        | 0.93%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 18        | 0.88%   |
| Ralink RT3290 Bluetooth                                                             | 17        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 17        | 0.83%   |
| Broadcom BCM2045 Bluetooth                                                          | 17        | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 16        | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 16        | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 15        | 0.73%   |
| Dell DW375 Bluetooth Module                                                         | 14        | 0.68%   |
| Realtek RTL8723B Bluetooth                                                          | 13        | 0.63%   |
| MediaTek Wireless_Device                                                            | 13        | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.63%   |
| Apple Bluetooth USB Host Controller                                                 | 13        | 0.63%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 12        | 0.59%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3162      | 55.04%  |
| AMD                              | 1052      | 18.31%  |
| Nvidia                           | 897       | 15.61%  |
| C-Media Electronics              | 84        | 1.46%   |
| Creative Labs                    | 61        | 1.06%   |
| VIA Technologies                 | 53        | 0.92%   |
| Silicon Integrated Systems [SiS] | 42        | 0.73%   |
| Logitech                         | 34        | 0.59%   |
| Texas Instruments                | 33        | 0.57%   |
| GN Netcom                        | 19        | 0.33%   |
| Focusrite-Novation               | 16        | 0.28%   |
| M-Audio                          | 14        | 0.24%   |
| JMTek                            | 13        | 0.23%   |
| Generalplus Technology           | 13        | 0.23%   |
| Creative Technology              | 13        | 0.23%   |
| Plantronics                      | 12        | 0.21%   |
| Yamaha                           | 11        | 0.19%   |
| Lenovo                           | 11        | 0.19%   |
| BEHRINGER International          | 9         | 0.16%   |
| ASUSTek Computer                 | 9         | 0.16%   |
| Realtek Semiconductor            | 8         | 0.14%   |
| Sennheiser Communications        | 7         | 0.12%   |
| ULi Electronics                  | 6         | 0.1%    |
| Tenx Technology                  | 5         | 0.09%   |
| Razer USA                        | 5         | 0.09%   |
| SAVITECH                         | 4         | 0.07%   |
| Roland                           | 4         | 0.07%   |
| Micro Star International         | 4         | 0.07%   |
| Kingston Technology              | 4         | 0.07%   |
| Ensoniq                          | 4         | 0.07%   |
| DigiTech                         | 4         | 0.07%   |
| Dell                             | 4         | 0.07%   |
| Corsair                          | 4         | 0.07%   |
| AKAI Professional M.I.           | 4         | 0.07%   |
| XMOS                             | 3         | 0.05%   |
| Xilinx                           | 3         | 0.05%   |
| Textech International            | 3         | 0.05%   |
| TEAC                             | 3         | 0.05%   |
| RODE Microphones                 | 3         | 0.05%   |
| PreSonus Audio Electronics       | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 350       | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 316       | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 303       | 4.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 231       | 3.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 214       | 3.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 207       | 3.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 198       | 2.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 197       | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 189       | 2.84%   |
| AMD FCH Azalia Controller                                                                         | 182       | 2.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 161       | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 153       | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 102       | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 93        | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 90        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 89        | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 89        | 1.34%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 86        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 84        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 83        | 1.25%   |
| Intel 8 Series HD Audio Controller                                                                | 83        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 80        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 78        | 1.17%   |
| Nvidia High Definition Audio Controller                                                           | 73        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 71        | 1.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 70        | 1.05%   |
| Nvidia MCP61 High Definition Audio                                                                | 59        | 0.89%   |
| Intel Broadwell-U Audio Controller                                                                | 59        | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 57        | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 57        | 0.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 57        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 55        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 55        | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 54        | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 52        | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 49        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 44        | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 41        | 0.62%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 41        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 496       | 20.68%  |
| SK hynix                     | 409       | 17.05%  |
| Unknown                      | 364       | 15.17%  |
| Kingston                     | 274       | 11.42%  |
| Micron Technology            | 186       | 7.75%   |
| Crucial                      | 147       | 6.13%   |
| Corsair                      | 103       | 4.29%   |
| G.Skill                      | 61        | 2.54%   |
| Elpida                       | 48        | 2%      |
| Ramaxel Technology           | 44        | 1.83%   |
| Nanya Technology             | 38        | 1.58%   |
| Unknown (ABCD)               | 35        | 1.46%   |
| A-DATA Technology            | 32        | 1.33%   |
| Smart                        | 17        | 0.71%   |
| Transcend                    | 14        | 0.58%   |
| Unknown                      | 11        | 0.46%   |
| Team                         | 10        | 0.42%   |
| Patriot                      | 10        | 0.42%   |
| GOODRAM                      | 9         | 0.38%   |
| Qimonda                      | 5         | 0.21%   |
| Avant                        | 5         | 0.21%   |
| Apacer                       | 5         | 0.21%   |
| Unifosa                      | 4         | 0.17%   |
| 48spaces                     | 4         | 0.17%   |
| Timetec                      | 3         | 0.13%   |
| GeIL                         | 3         | 0.13%   |
| fef5                         | 3         | 0.13%   |
| V-Color                      | 2         | 0.08%   |
| Teikon                       | 2         | 0.08%   |
| Super Talent                 | 2         | 0.08%   |
| PNY                          | 2         | 0.08%   |
| Neo Forza                    | 2         | 0.08%   |
| High Bridge                  | 2         | 0.08%   |
| CSX                          | 2         | 0.08%   |
| ASint Technology             | 2         | 0.08%   |
| Walton Chaintech             | 1         | 0.04%   |
| V-GeN                        | 1         | 0.04%   |
| Unknown (AB)                 | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.04%   |
| Unknown (0x7FA8000000000000) | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 29        | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 23        | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 20        | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 18        | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 18        | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 17        | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 16        | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 16        | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 15        | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 15        | 0.58%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s               | 15        | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 13        | 0.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 12        | 0.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 12        | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.46%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 11        | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 11        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 11        | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 11        | 0.42%   |
| Unknown                                                             | 11        | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 10        | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 10        | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 10        | 0.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 10        | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 9         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 9         | 0.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 9         | 0.35%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 9         | 0.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 9         | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 9         | 0.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 9         | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 8         | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 8         | 0.31%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 8         | 0.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 8         | 0.31%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 8         | 0.31%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 8         | 0.31%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 8         | 0.31%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 7         | 0.27%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 7         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 810       | 38.61%  |
| DDR4    | 741       | 35.32%  |
| DDR2    | 198       | 9.44%   |
| SDRAM   | 97        | 4.62%   |
| LPDDR4  | 81        | 3.86%   |
| Unknown | 73        | 3.48%   |
| LPDDR3  | 36        | 1.72%   |
| DDR     | 27        | 1.29%   |
| DDR5    | 17        | 0.81%   |
| DRAM    | 9         | 0.43%   |
| LPDDR5  | 8         | 0.38%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1199      | 58.12%  |
| DIMM         | 754       | 36.55%  |
| Row Of Chips | 83        | 4.02%   |
| Chip         | 13        | 0.63%   |
| Unknown      | 10        | 0.48%   |
| FB-DIMM      | 4         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 665       | 29.28%  |
| 8192    | 657       | 28.93%  |
| 2048    | 450       | 19.82%  |
| 16384   | 281       | 12.37%  |
| 1024    | 138       | 6.08%   |
| 32768   | 59        | 2.6%    |
| 512     | 15        | 0.66%   |
| 1536    | 2         | 0.09%   |
| 65536   | 1         | 0.04%   |
| 256     | 1         | 0.04%   |
| 1       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 499       | 22.25%  |
| 2667    | 280       | 12.48%  |
| 3200    | 240       | 10.7%   |
| 1333    | 175       | 7.8%    |
| 2400    | 146       | 6.51%   |
| 667     | 104       | 4.64%   |
| Unknown | 87        | 3.88%   |
| 800     | 84        | 3.74%   |
| 2133    | 77        | 3.43%   |
| 1334    | 73        | 3.25%   |
| 1066    | 37        | 1.65%   |
| 3600    | 34        | 1.52%   |
| 1867    | 33        | 1.47%   |
| 1067    | 33        | 1.47%   |
| 1866    | 25        | 1.11%   |
| 3266    | 23        | 1.03%   |
| 4199    | 21        | 0.94%   |
| 1800    | 20        | 0.89%   |
| 533     | 20        | 0.89%   |
| 4267    | 19        | 0.85%   |
| 2666    | 17        | 0.76%   |
| 2048    | 17        | 0.76%   |
| 3000    | 16        | 0.71%   |
| 4800    | 14        | 0.62%   |
| 3800    | 12        | 0.53%   |
| 3733    | 11        | 0.49%   |
| 975     | 10        | 0.45%   |
| 2000    | 8         | 0.36%   |
| 400     | 8         | 0.36%   |
| 6400    | 6         | 0.27%   |
| 2733    | 6         | 0.27%   |
| 333     | 6         | 0.27%   |
| 49926   | 5         | 0.22%   |
| 4266    | 5         | 0.22%   |
| 3466    | 4         | 0.18%   |
| 2200    | 4         | 0.18%   |
| 8400    | 3         | 0.13%   |
| 3400    | 3         | 0.13%   |
| 3066    | 3         | 0.13%   |
| 2933    | 3         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 59        | 40.97%  |
| Brother Industries    | 27        | 18.75%  |
| Canon                 | 24        | 16.67%  |
| Samsung Electronics   | 11        | 7.64%   |
| Seiko Epson           | 5         | 3.47%   |
| Zebra                 | 4         | 2.78%   |
| QinHeng Electronics   | 3         | 2.08%   |
| Prolific Technology   | 2         | 1.39%   |
| Kyocera               | 2         | 1.39%   |
| Xiaomi                | 1         | 0.69%   |
| STMicroelectronics    | 1         | 0.69%   |
| Pantum                | 1         | 0.69%   |
| Minolta               | 1         | 0.69%   |
| Lexmark International | 1         | 0.69%   |
| Dymo-CoStar           | 1         | 0.69%   |
| Belkin Components     | 1         | 0.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1005                                                     | 4         | 2.76%   |
| HP LaserJet 400 M401dn                                                | 4         | 2.76%   |
| Zebra ZP 450 Printer                                                  | 3         | 2.07%   |
| QinHeng CH340S                                                        | 3         | 2.07%   |
| HP ENVY 4520 series                                                   | 3         | 2.07%   |
| HP DeskJet 3700 series                                                | 3         | 2.07%   |
| Brother HL-5370DW series                                              | 3         | 2.07%   |
| Seiko Epson L360 Series                                               | 2         | 1.38%   |
| Prolific PL2305 Parallel Port                                         | 2         | 1.38%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 1.38%   |
| HP LaserJet P2055 series                                              | 2         | 1.38%   |
| HP LaserJet P1006                                                     | 2         | 1.38%   |
| HP LaserJet 1320                                                      | 2         | 1.38%   |
| HP LaserJet 1020                                                      | 2         | 1.38%   |
| HP LaserJet 1018                                                      | 2         | 1.38%   |
| HP LaserJet 1015                                                      | 2         | 1.38%   |
| HP Deskjet 3050A                                                      | 2         | 1.38%   |
| Canon TS3100 series                                                   | 2         | 1.38%   |
| Canon PIXMA MX530 Series                                              | 2         | 1.38%   |
| Canon LBP6000                                                         | 2         | 1.38%   |
| Brother HL-L2320D series                                              | 2         | 1.38%   |
| Brother HL-5340 series                                                | 2         | 1.38%   |
| Brother HL-2270DW Laser Printer                                       | 2         | 1.38%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.69%   |
| Xiaomi MiMouse 2                                                      | 1         | 0.69%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.69%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.69%   |
| Seiko Epson ET-2720 Series                                            | 1         | 0.69%   |
| Seiko Epson ET-2600 Series                                            | 1         | 0.69%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 0.69%   |
| Samsung SF-760 Series                                                 | 1         | 0.69%   |
| Samsung SCX-4200 series                                               | 1         | 0.69%   |
| Samsung SCX-4100 Scanner                                              | 1         | 0.69%   |
| Samsung SCX-3400 Series                                               | 1         | 0.69%   |
| Samsung ML-2525W Series                                               | 1         | 0.69%   |
| Samsung ML-1865                                                       | 1         | 0.69%   |
| Samsung ML-1740 Printer                                               | 1         | 0.69%   |
| Samsung M2070 Series                                                  | 1         | 0.69%   |
| Samsung M2020 Series                                                  | 1         | 0.69%   |
| Samsung C48x Series                                                   | 1         | 0.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 28        | 71.79%  |
| Hewlett-Packard | 6         | 15.38%  |
| Seiko Epson     | 5         | 12.82%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                     | 5         | 12.82%  |
| Canon CanoScan LIDE 25                                      | 4         | 10.26%  |
| Canon CanoScan LiDE 100                                     | 4         | 10.26%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 7.69%   |
| Canon CanoScan N650U/N656U                                  | 2         | 5.13%   |
| Canon CanoScan LiDE 220                                     | 2         | 5.13%   |
| Canon CanoScan LiDE 210                                     | 2         | 5.13%   |
| Canon CanoScan LiDE 120                                     | 2         | 5.13%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 2.56%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 2.56%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 2.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 2.56%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 2.56%   |
| HP ScanJet 82x0C                                            | 1         | 2.56%   |
| HP ScanJet 7400c                                            | 1         | 2.56%   |
| HP ScanJet 5590                                             | 1         | 2.56%   |
| HP ScanJet 3570c                                            | 1         | 2.56%   |
| HP Scanjet 200                                              | 1         | 2.56%   |
| HP PSC 1200                                                 | 1         | 2.56%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 2.56%   |
| Canon CanoScan LiDE 90                                      | 1         | 2.56%   |
| Canon CanoScan LiDE 200                                     | 1         | 2.56%   |
| Canon CanoScan 4400F                                        | 1         | 2.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 570       | 24.5%   |
| Microdia                               | 183       | 7.86%   |
| IMC Networks                           | 153       | 6.57%   |
| Realtek Semiconductor                  | 149       | 6.4%    |
| Suyin                                  | 124       | 5.33%   |
| Logitech                               | 124       | 5.33%   |
| Sunplus Innovation Technology          | 111       | 4.77%   |
| Bison Electronics                      | 93        | 4%      |
| Quanta                                 | 81        | 3.48%   |
| Cheng Uei Precision Industry (Foxlink) | 74        | 3.18%   |
| Apple                                  | 60        | 2.58%   |
| Acer                                   | 60        | 2.58%   |
| Silicon Motion                         | 49        | 2.11%   |
| Syntek                                 | 48        | 2.06%   |
| Alcor Micro                            | 48        | 2.06%   |
| Ricoh                                  | 43        | 1.85%   |
| Lite-On Technology                     | 41        | 1.76%   |
| Samsung Electronics                    | 28        | 1.2%    |
| Z-Star Microelectronics                | 25        | 1.07%   |
| Microsoft                              | 23        | 0.99%   |
| Luxvisions Innotech Limited            | 18        | 0.77%   |
| Lenovo                                 | 17        | 0.73%   |
| ALi                                    | 17        | 0.73%   |
| Primax Electronics                     | 11        | 0.47%   |
| Importek                               | 10        | 0.43%   |
| GEMBIRD                                | 10        | 0.43%   |
| Sonix Technology                       | 9         | 0.39%   |
| USB Camera                             | 8         | 0.34%   |
| MacroSilicon                           | 8         | 0.34%   |
| Generalplus Technology                 | 8         | 0.34%   |
| OmniVision Technologies                | 7         | 0.3%    |
| Jieli Technology                       | 7         | 0.3%    |
| DigiTech                               | 7         | 0.3%    |
| KYE Systems (Mouse Systems)            | 6         | 0.26%   |
| Cubeternet                             | 6         | 0.26%   |
| ARC International                      | 6         | 0.26%   |
| Creative Technology                    | 5         | 0.21%   |
| Trust                                  | 4         | 0.17%   |
| Sunplus Technology                     | 4         | 0.17%   |
| Razer USA                              | 4         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 92        | 3.94%   |
| Realtek Integrated_Webcam_HD                     | 42        | 1.8%    |
| Microdia Integrated_Webcam_HD                    | 40        | 1.71%   |
| Chicony HD WebCam                                | 36        | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                | 32        | 1.37%   |
| Chicony USB 2.0 Camera                           | 31        | 1.33%   |
| Sunplus Integrated_Webcam_HD                     | 28        | 1.2%    |
| Logitech Webcam C270                             | 28        | 1.2%    |
| Samsung Galaxy series, misc. (MTP mode)          | 27        | 1.16%   |
| IMC Networks Integrated Camera                   | 25        | 1.07%   |
| Alcor Micro USB 2.0 Camera                       | 25        | 1.07%   |
| Chicony TOSHIBA Web Camera - HD                  | 24        | 1.03%   |
| Realtek USB Camera                               | 23        | 0.98%   |
| Apple Built-in iSight                            | 23        | 0.98%   |
| Microdia Sonix USB 2.0 Camera                    | 21        | 0.9%    |
| Logitech HD Pro Webcam C920                      | 21        | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 21        | 0.9%    |
| Chicony HP TrueVision HD                         | 20        | 0.86%   |
| Lite-On Integrated Camera                        | 19        | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 19        | 0.81%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 18        | 0.77%   |
| Syntek Integrated Camera                         | 17        | 0.73%   |
| Suyin HP TrueVision HD                           | 17        | 0.73%   |
| Bison Lenovo EasyCamera                          | 17        | 0.73%   |
| Bison Integrated Camera                          | 17        | 0.73%   |
| Microdia Integrated Webcam                       | 16        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                    | 16        | 0.68%   |
| Microdia USB 2.0 Camera                          | 15        | 0.64%   |
| IMC Networks UVC VGA Webcam                      | 15        | 0.64%   |
| Suyin Acer CrystalEye Webcam                     | 14        | 0.6%    |
| Sunplus HD WebCam                                | 14        | 0.6%    |
| Chicony HP HD Camera                             | 14        | 0.6%    |
| Acer SunplusIT Integrated Camera                 | 14        | 0.6%    |
| Quanta HP Webcam                                 | 13        | 0.56%   |
| Quanta HD User Facing                            | 13        | 0.56%   |
| Logitech C922 Pro Stream Webcam                  | 13        | 0.56%   |
| Chicony HP Truevision HD camera                  | 13        | 0.56%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.51%   |
| Realtek Lenovo EasyCamera                        | 12        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 138       | 35.48%  |
| Synaptics                          | 74        | 19.02%  |
| AuthenTec                          | 57        | 14.65%  |
| Upek                               | 34        | 8.74%   |
| Shenzhen Goodix Technology         | 30        | 7.71%   |
| STMicroelectronics                 | 22        | 5.66%   |
| LighTuning Technology              | 15        | 3.86%   |
| Elan Microelectronics              | 11        | 2.83%   |
| Samsung Electronics                | 3         | 0.77%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.51%   |
| Gingytech                          | 1         | 0.26%   |
| Focal-systems.Corp                 | 1         | 0.26%   |
| DigitalPersona                     | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 7.97%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 7.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 7.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 24        | 6.17%   |
| STMicroelectronics Fingerprint Reader                                      | 22        | 5.66%   |
| Shenzhen Goodix  Fingerprint Device                                        | 20        | 5.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.63%   |
| AuthenTec AES2810                                                          | 16        | 4.11%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 3.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 3.08%   |
| Validity Sensors VFS491                                                    | 11        | 2.83%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 2.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 2.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.31%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.31%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.06%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.06%   |
| AuthenTec AES1600                                                          | 7         | 1.8%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.54%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.54%   |
| Synaptics  WBDI                                                            | 5         | 1.29%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.29%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.29%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.29%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.03%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.03%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.03%   |
| LighTuning Fingerprint Reader                                              | 4         | 1.03%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.77%   |
| Synaptics UWP WBDI                                                         | 3         | 0.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.77%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.51%   |
| Synaptics WBDI Device                                                      | 2         | 0.51%   |
| Synaptics WBDI                                                             | 2         | 0.51%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.51%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.51%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 78        | 35.62%  |
| Alcor Micro                       | 57        | 26.03%  |
| O2 Micro                          | 31        | 14.16%  |
| Lenovo                            | 18        | 8.22%   |
| Upek                              | 17        | 7.76%   |
| OmniKey                           | 3         | 1.37%   |
| Gemalto (was Gemplus)             | 3         | 1.37%   |
| Reiner SCT Kartensysteme          | 2         | 0.91%   |
| Yubico.com                        | 1         | 0.46%   |
| VASCO Data Security International | 1         | 0.46%   |
| In Focus Systems                  | 1         | 0.46%   |
| Fujitsu Siemens Computers         | 1         | 0.46%   |
| Clay Logic                        | 1         | 0.46%   |
| Chicony Electronics               | 1         | 0.46%   |
| Cherry                            | 1         | 0.46%   |
| C3PO                              | 1         | 0.46%   |
| Aktiv                             | 1         | 0.46%   |
| Advanced Card Systems             | 1         | 0.46%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 57        | 26.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 15.53%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 10.96%  |
| Broadcom 5880                                                                | 19        | 8.68%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 7.76%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 7.76%   |
| Broadcom 58200                                                               | 13        | 5.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.02%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 3.2%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.91%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.91%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.46%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.46%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.46%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.46%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.46%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.46%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.46%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.46%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.46%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.46%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.46%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.46%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.46%   |
| Aktiv Rutoken lite                                                           | 1         | 0.46%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.46%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3243      | 72.26%  |
| 1     | 981       | 21.86%  |
| 2     | 211       | 4.7%    |
| 3     | 33        | 0.74%   |
| 4     | 12        | 0.27%   |
| 5     | 4         | 0.09%   |
| 6     | 2         | 0.04%   |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 385       | 25.63%  |
| Graphics card            | 359       | 23.9%   |
| Chipcard                 | 206       | 13.72%  |
| Net/wireless             | 154       | 10.25%  |
| Communication controller | 65        | 4.33%   |
| Camera                   | 51        | 3.4%    |
| Modem                    | 49        | 3.26%   |
| Multimedia controller    | 42        | 2.8%    |
| Unassigned class         | 33        | 2.2%    |
| Bluetooth                | 30        | 2%      |
| Sound                    | 27        | 1.8%    |
| Storage                  | 26        | 1.73%   |
| Card reader              | 23        | 1.53%   |
| Flash memory             | 16        | 1.07%   |
| Net/ethernet             | 13        | 0.87%   |
| Network                  | 11        | 0.73%   |
| Dvb card                 | 4         | 0.27%   |
| Storage/ide              | 3         | 0.2%    |
| Storage/raid             | 2         | 0.13%   |
| Video                    | 1         | 0.07%   |
| Storage/nvme             | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

