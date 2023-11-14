Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 6213

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15 3511            | Notebook    | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [8cd8d5ade1](https://linux-hardware.org/?probe=8cd8d5ade1) | Nov 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [fef5a2e8ae](https://linux-hardware.org/?probe=fef5a2e8ae) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | Notebook    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| Unknown       | H96 Max X3                  | Soc         | [362598f755](https://linux-hardware.org/?probe=362598f755) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [82bf4f530a](https://linux-hardware.org/?probe=82bf4f530a) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [5f192519d4](https://linux-hardware.org/?probe=5f192519d4) | Nov 05, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [1d1311204e](https://linux-hardware.org/?probe=1d1311204e) | Nov 05, 2023 |
| HP            | 8184 X4                     | Desktop     | [fb7f295b44](https://linux-hardware.org/?probe=fb7f295b44) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [85733c0ec0](https://linux-hardware.org/?probe=85733c0ec0) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8a4147b40a](https://linux-hardware.org/?probe=8a4147b40a) | Nov 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [482f1a0fe7](https://linux-hardware.org/?probe=482f1a0fe7) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [a386eceffe](https://linux-hardware.org/?probe=a386eceffe) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee2a20b30a](https://linux-hardware.org/?probe=ee2a20b30a) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [1e6407d9d5](https://linux-hardware.org/?probe=1e6407d9d5) | Nov 04, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a513bb8188](https://linux-hardware.org/?probe=a513bb8188) | Nov 04, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [04e96e2742](https://linux-hardware.org/?probe=04e96e2742) | Nov 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dd81ed04ea](https://linux-hardware.org/?probe=dd81ed04ea) | Nov 04, 2023 |
| HP            | Notebook                    | Notebook    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [b91d7803a2](https://linux-hardware.org/?probe=b91d7803a2) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [3030ad2bc8](https://linux-hardware.org/?probe=3030ad2bc8) | Nov 02, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6aa1f3a294](https://linux-hardware.org/?probe=6aa1f3a294) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [3e65346dfd](https://linux-hardware.org/?probe=3e65346dfd) | Nov 02, 2023 |
| Wortmann      | 1220777_1400328             | Notebook    | [778b1abc73](https://linux-hardware.org/?probe=778b1abc73) | Nov 02, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [677490b7c2](https://linux-hardware.org/?probe=677490b7c2) | Nov 02, 2023 |
| ASRock        | P67 Professional            | Desktop     | [c998340fa9](https://linux-hardware.org/?probe=c998340fa9) | Nov 02, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [2efa290a39](https://linux-hardware.org/?probe=2efa290a39) | Nov 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [0f4435d620](https://linux-hardware.org/?probe=0f4435d620) | Nov 02, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [cde7923bf2](https://linux-hardware.org/?probe=cde7923bf2) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [493dcbc1f8](https://linux-hardware.org/?probe=493dcbc1f8) | Nov 01, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [67863a015a](https://linux-hardware.org/?probe=67863a015a) | Nov 01, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [f0b1ef4bc8](https://linux-hardware.org/?probe=f0b1ef4bc8) | Nov 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [6895dd827a](https://linux-hardware.org/?probe=6895dd827a) | Nov 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [50a30d4ebd](https://linux-hardware.org/?probe=50a30d4ebd) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [f65225d50a](https://linux-hardware.org/?probe=f65225d50a) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [69f7a5ebed](https://linux-hardware.org/?probe=69f7a5ebed) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | Notebook    | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| HP            | 2AF7                        | Desktop     | [0a2c239b75](https://linux-hardware.org/?probe=0a2c239b75) | Nov 01, 2023 |
| Dell          | Latitude 7290               | Notebook    | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| ASUSTek       | BT1AD                       | Desktop     | [133784e5ee](https://linux-hardware.org/?probe=133784e5ee) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [1e3f228931](https://linux-hardware.org/?probe=1e3f228931) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [10382e8ed6](https://linux-hardware.org/?probe=10382e8ed6) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | Notebook    | [ebcacada49](https://linux-hardware.org/?probe=ebcacada49) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | Notebook    | [d8658ea415](https://linux-hardware.org/?probe=d8658ea415) | Oct 31, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [c889a29b7f](https://linux-hardware.org/?probe=c889a29b7f) | Oct 31, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [77d9982cf2](https://linux-hardware.org/?probe=77d9982cf2) | Oct 31, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [84064baf19](https://linux-hardware.org/?probe=84064baf19) | Oct 31, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [8a9f37b293](https://linux-hardware.org/?probe=8a9f37b293) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fe3816864f](https://linux-hardware.org/?probe=fe3816864f) | Oct 30, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [babfdba8f2](https://linux-hardware.org/?probe=babfdba8f2) | Oct 30, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [4825358a5d](https://linux-hardware.org/?probe=4825358a5d) | Oct 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5d7ab82de7](https://linux-hardware.org/?probe=5d7ab82de7) | Oct 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [986edacf9a](https://linux-hardware.org/?probe=986edacf9a) | Oct 30, 2023 |
| HP            | 2AF7                        | Desktop     | [04c535a13d](https://linux-hardware.org/?probe=04c535a13d) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [7ffe987b92](https://linux-hardware.org/?probe=7ffe987b92) | Oct 30, 2023 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [b160015184](https://linux-hardware.org/?probe=b160015184) | Oct 29, 2023 |
| HP            | 1790                        | Desktop     | [8bde9984db](https://linux-hardware.org/?probe=8bde9984db) | Oct 29, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [42e6514c85](https://linux-hardware.org/?probe=42e6514c85) | Oct 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [90ab9dafc5](https://linux-hardware.org/?probe=90ab9dafc5) | Oct 29, 2023 |
| Dell          | Precision M6800             | Notebook    | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0f69bc7ea0](https://linux-hardware.org/?probe=0f69bc7ea0) | Oct 28, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9b3c09e73a](https://linux-hardware.org/?probe=9b3c09e73a) | Oct 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e340ddc535](https://linux-hardware.org/?probe=e340ddc535) | Oct 27, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [9266111091](https://linux-hardware.org/?probe=9266111091) | Oct 27, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| EXTRA Comp... | MS-1758                     | Notebook    | [eced546e79](https://linux-hardware.org/?probe=eced546e79) | Oct 26, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [8516768801](https://linux-hardware.org/?probe=8516768801) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [d1c293b080](https://linux-hardware.org/?probe=d1c293b080) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| SYWZ          | S210H Series                | Desktop     | [9239922f80](https://linux-hardware.org/?probe=9239922f80) | Oct 26, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [35b07b6e34](https://linux-hardware.org/?probe=35b07b6e34) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [6e87d140be](https://linux-hardware.org/?probe=6e87d140be) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c64594fac3](https://linux-hardware.org/?probe=c64594fac3) | Oct 25, 2023 |
| WUYING        | NS01-4BGXG                  | Notebook    | [5c999216df](https://linux-hardware.org/?probe=5c999216df) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [36893aadc0](https://linux-hardware.org/?probe=36893aadc0) | Oct 25, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e25ec0e229](https://linux-hardware.org/?probe=e25ec0e229) | Oct 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [3bd963fd9e](https://linux-hardware.org/?probe=3bd963fd9e) | Oct 24, 2023 |
| HP            | 14                          | Notebook    | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | Notebook    | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [0f08eb340b](https://linux-hardware.org/?probe=0f08eb340b) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c74b24edc0](https://linux-hardware.org/?probe=c74b24edc0) | Oct 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| Colorful T... | BATTLE-AX B450M-HD V14      | Desktop     | [314500a8ed](https://linux-hardware.org/?probe=314500a8ed) | Oct 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [d71e04d478](https://linux-hardware.org/?probe=d71e04d478) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [55c5bbce9f](https://linux-hardware.org/?probe=55c5bbce9f) | Oct 23, 2023 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [806cdb2bef](https://linux-hardware.org/?probe=806cdb2bef) | Oct 23, 2023 |
| AZW           | SEi                         | Notebook    | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Dell          | Latitude E6520              | Notebook    | [5d73c1d444](https://linux-hardware.org/?probe=5d73c1d444) | Oct 22, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [bd8cdfe190](https://linux-hardware.org/?probe=bd8cdfe190) | Oct 22, 2023 |
| HP            | ProBook 4340s               | Notebook    | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [5962f780e9](https://linux-hardware.org/?probe=5962f780e9) | Oct 22, 2023 |
| ECS           | CHICAGO2                    | Desktop     | [e33ec52f5a](https://linux-hardware.org/?probe=e33ec52f5a) | Oct 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [9990a91f59](https://linux-hardware.org/?probe=9990a91f59) | Oct 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [33b1df369f](https://linux-hardware.org/?probe=33b1df369f) | Oct 21, 2023 |
| AZW           | SER V01                     | Mini pc     | [25ca388d81](https://linux-hardware.org/?probe=25ca388d81) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| AZW           | SER V1                      | Desktop     | [60f9b9fdd9](https://linux-hardware.org/?probe=60f9b9fdd9) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f23d0ff7da](https://linux-hardware.org/?probe=f23d0ff7da) | Oct 20, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [09b04f5fd5](https://linux-hardware.org/?probe=09b04f5fd5) | Oct 20, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [a7f26cedd6](https://linux-hardware.org/?probe=a7f26cedd6) | Oct 20, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [acf7108592](https://linux-hardware.org/?probe=acf7108592) | Oct 20, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [38436a17ef](https://linux-hardware.org/?probe=38436a17ef) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [4bfe18fe76](https://linux-hardware.org/?probe=4bfe18fe76) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [e83ad29e5e](https://linux-hardware.org/?probe=e83ad29e5e) | Oct 20, 2023 |
| ASUSTek       | X450LCP                     | Notebook    | [ae3fec47c6](https://linux-hardware.org/?probe=ae3fec47c6) | Oct 19, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8fd9d07f5d](https://linux-hardware.org/?probe=8fd9d07f5d) | Oct 19, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [c2215ccabb](https://linux-hardware.org/?probe=c2215ccabb) | Oct 19, 2023 |
| Acer          | AOD270                      | Notebook    | [20d5a5477c](https://linux-hardware.org/?probe=20d5a5477c) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aad7482915](https://linux-hardware.org/?probe=aad7482915) | Oct 19, 2023 |
| HP            | G60                         | Notebook    | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0c25658c6d](https://linux-hardware.org/?probe=0c25658c6d) | Oct 18, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [0944131c12](https://linux-hardware.org/?probe=0944131c12) | Oct 18, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [413edf8cdb](https://linux-hardware.org/?probe=413edf8cdb) | Oct 18, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [dd8c738dc7](https://linux-hardware.org/?probe=dd8c738dc7) | Oct 18, 2023 |
| Dell          | Precision 7520              | Notebook    | [bd78f68578](https://linux-hardware.org/?probe=bd78f68578) | Oct 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [be8c08b665](https://linux-hardware.org/?probe=be8c08b665) | Oct 18, 2023 |
| Dell          | G7 7790                     | Notebook    | [250d61d6a7](https://linux-hardware.org/?probe=250d61d6a7) | Oct 18, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [05ee51f822](https://linux-hardware.org/?probe=05ee51f822) | Oct 18, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [77690da2b6](https://linux-hardware.org/?probe=77690da2b6) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [4b4319490d](https://linux-hardware.org/?probe=4b4319490d) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Lenovo        | 01KN179                     | Server      | [9f36a4143d](https://linux-hardware.org/?probe=9f36a4143d) | Oct 16, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [5860734f3a](https://linux-hardware.org/?probe=5860734f3a) | Oct 16, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [6b4c286aca](https://linux-hardware.org/?probe=6b4c286aca) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| AMI           | Intel                       | Convertible | [38a3df30fe](https://linux-hardware.org/?probe=38a3df30fe) | Oct 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bc33324b0d](https://linux-hardware.org/?probe=bc33324b0d) | Oct 15, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [059145d98c](https://linux-hardware.org/?probe=059145d98c) | Oct 15, 2023 |
| Dell          | Latitude E7470              | Notebook    | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [e4bcb7e688](https://linux-hardware.org/?probe=e4bcb7e688) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [92049beb26](https://linux-hardware.org/?probe=92049beb26) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [3eff97b04d](https://linux-hardware.org/?probe=3eff97b04d) | Oct 15, 2023 |
| HP            | 829A                        | Mini pc     | [f9af7b48fe](https://linux-hardware.org/?probe=f9af7b48fe) | Oct 14, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dba250310](https://linux-hardware.org/?probe=1dba250310) | Oct 14, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [09a90189ec](https://linux-hardware.org/?probe=09a90189ec) | Oct 14, 2023 |
| Intel         | JSL MRD                     | Desktop     | [a39b6e2f92](https://linux-hardware.org/?probe=a39b6e2f92) | Oct 14, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [1bea1dafbf](https://linux-hardware.org/?probe=1bea1dafbf) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7045758f33](https://linux-hardware.org/?probe=7045758f33) | Oct 13, 2023 |
| ASUSTek       | PRIME H310M-C               | Desktop     | [2696ecde8d](https://linux-hardware.org/?probe=2696ecde8d) | Oct 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f18ac93db8](https://linux-hardware.org/?probe=f18ac93db8) | Oct 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [8684995c92](https://linux-hardware.org/?probe=8684995c92) | Oct 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [bf26581f5d](https://linux-hardware.org/?probe=bf26581f5d) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [09d2bdba5b](https://linux-hardware.org/?probe=09d2bdba5b) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c3be7c74a0](https://linux-hardware.org/?probe=c3be7c74a0) | Oct 11, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Notebook      | W510LU                      | Notebook    | [7b46aa1486](https://linux-hardware.org/?probe=7b46aa1486) | Oct 11, 2023 |
| ASRock        | X79 Extreme9                | Desktop     | [4a0805a07a](https://linux-hardware.org/?probe=4a0805a07a) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [6ea5ba513f](https://linux-hardware.org/?probe=6ea5ba513f) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [f9c4374e7c](https://linux-hardware.org/?probe=f9c4374e7c) | Oct 11, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [3fe42a607c](https://linux-hardware.org/?probe=3fe42a607c) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [3ba4207fd0](https://linux-hardware.org/?probe=3ba4207fd0) | Oct 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [5f179c5f02](https://linux-hardware.org/?probe=5f179c5f02) | Oct 09, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [02211f49db](https://linux-hardware.org/?probe=02211f49db) | Oct 08, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [38b7ffd223](https://linux-hardware.org/?probe=38b7ffd223) | Oct 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [26ba02b08e](https://linux-hardware.org/?probe=26ba02b08e) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7513e708f6](https://linux-hardware.org/?probe=7513e708f6) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [84ff0a9a08](https://linux-hardware.org/?probe=84ff0a9a08) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1505f63948](https://linux-hardware.org/?probe=1505f63948) | Oct 07, 2023 |
| Medion        | E15302                      | Notebook    | [d26c76cedf](https://linux-hardware.org/?probe=d26c76cedf) | Oct 07, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [5ff0e17804](https://linux-hardware.org/?probe=5ff0e17804) | Oct 07, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [5ac03d658c](https://linux-hardware.org/?probe=5ac03d658c) | Oct 07, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [7e01bc1824](https://linux-hardware.org/?probe=7e01bc1824) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [364af80964](https://linux-hardware.org/?probe=364af80964) | Oct 06, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [31248aa2bf](https://linux-hardware.org/?probe=31248aa2bf) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [5b84610e15](https://linux-hardware.org/?probe=5b84610e15) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c5a3a209c0](https://linux-hardware.org/?probe=c5a3a209c0) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c35ab8ae2e](https://linux-hardware.org/?probe=c35ab8ae2e) | Oct 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [e796c2f9ba](https://linux-hardware.org/?probe=e796c2f9ba) | Oct 05, 2023 |
| Google        | Woomax                      | Notebook    | [2163941472](https://linux-hardware.org/?probe=2163941472) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57b1771805](https://linux-hardware.org/?probe=57b1771805) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [2fdd309c6a](https://linux-hardware.org/?probe=2fdd309c6a) | Oct 04, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | Desktop     | [bb9493309a](https://linux-hardware.org/?probe=bb9493309a) | Oct 04, 2023 |
| HP            | 3396                        | Desktop     | [e83b1b4945](https://linux-hardware.org/?probe=e83b1b4945) | Oct 03, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [8892c7239e](https://linux-hardware.org/?probe=8892c7239e) | Oct 03, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [56a4c9aa55](https://linux-hardware.org/?probe=56a4c9aa55) | Oct 03, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0d7876c259](https://linux-hardware.org/?probe=0d7876c259) | Oct 03, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [4074b6cda1](https://linux-hardware.org/?probe=4074b6cda1) | Oct 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [f349819e0a](https://linux-hardware.org/?probe=f349819e0a) | Oct 02, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [124cb639c1](https://linux-hardware.org/?probe=124cb639c1) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5fe25903c1](https://linux-hardware.org/?probe=5fe25903c1) | Oct 02, 2023 |
| Google        | Blorb                       | Notebook    | [04e37bafe3](https://linux-hardware.org/?probe=04e37bafe3) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [122f1d4ca8](https://linux-hardware.org/?probe=122f1d4ca8) | Oct 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [f8ee109cbd](https://linux-hardware.org/?probe=f8ee109cbd) | Oct 01, 2023 |
| Schenker      | VIA 15 Pro (M22)            | Notebook    | [1919690674](https://linux-hardware.org/?probe=1919690674) | Oct 01, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b3eb082c5e](https://linux-hardware.org/?probe=b3eb082c5e) | Oct 01, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [4a47d466d9](https://linux-hardware.org/?probe=4a47d466d9) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [b87e9dd9ad](https://linux-hardware.org/?probe=b87e9dd9ad) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [89791e7bf0](https://linux-hardware.org/?probe=89791e7bf0) | Sep 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6f07d7c834](https://linux-hardware.org/?probe=6f07d7c834) | Sep 29, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9f32819945](https://linux-hardware.org/?probe=9f32819945) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| CHIPHD        | NT125D                      | Notebook    | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Acer          | FX58M                       | Desktop     | [e24f36e0bd](https://linux-hardware.org/?probe=e24f36e0bd) | Sep 26, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [37840dad1c](https://linux-hardware.org/?probe=37840dad1c) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [1b72e3fe1c](https://linux-hardware.org/?probe=1b72e3fe1c) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [0281cc244a](https://linux-hardware.org/?probe=0281cc244a) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe1163082c](https://linux-hardware.org/?probe=fe1163082c) | Sep 26, 2023 |
| Lenovo        | B480 20140                  | Notebook    | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [56cd5e0bfd](https://linux-hardware.org/?probe=56cd5e0bfd) | Sep 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4095fbc19e](https://linux-hardware.org/?probe=4095fbc19e) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [faf68444bc](https://linux-hardware.org/?probe=faf68444bc) | Sep 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2691aa5f87](https://linux-hardware.org/?probe=2691aa5f87) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7f88191a7b](https://linux-hardware.org/?probe=7f88191a7b) | Sep 23, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [583c577b02](https://linux-hardware.org/?probe=583c577b02) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [dc831a82cd](https://linux-hardware.org/?probe=dc831a82cd) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| HP            | 18E7                        | Desktop     | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [b6d619d509](https://linux-hardware.org/?probe=b6d619d509) | Sep 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [d4060b585a](https://linux-hardware.org/?probe=d4060b585a) | Sep 20, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [42b79f2641](https://linux-hardware.org/?probe=42b79f2641) | Sep 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [c7142a0d96](https://linux-hardware.org/?probe=c7142a0d96) | Sep 20, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [a24c6808ba](https://linux-hardware.org/?probe=a24c6808ba) | Sep 20, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e753271d63](https://linux-hardware.org/?probe=e753271d63) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [4ffee8598b](https://linux-hardware.org/?probe=4ffee8598b) | Sep 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c8a7f18e5d](https://linux-hardware.org/?probe=c8a7f18e5d) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [6f676cd559](https://linux-hardware.org/?probe=6f676cd559) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [17e0d2ab92](https://linux-hardware.org/?probe=17e0d2ab92) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e6db76aa66](https://linux-hardware.org/?probe=e6db76aa66) | Sep 17, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [76d6f570a8](https://linux-hardware.org/?probe=76d6f570a8) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [fabf2bef4c](https://linux-hardware.org/?probe=fabf2bef4c) | Sep 15, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [a73abd96f1](https://linux-hardware.org/?probe=a73abd96f1) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [de7e036404](https://linux-hardware.org/?probe=de7e036404) | Sep 15, 2023 |
| HP            | 0A9Ch                       | Desktop     | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [3a1c100a69](https://linux-hardware.org/?probe=3a1c100a69) | Sep 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [15256fdeb2](https://linux-hardware.org/?probe=15256fdeb2) | Sep 14, 2023 |
| Notebook      | P65_P67SA                   | Notebook    | [4d11ae0ff7](https://linux-hardware.org/?probe=4d11ae0ff7) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [20ad52b9a4](https://linux-hardware.org/?probe=20ad52b9a4) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [959fc9f783](https://linux-hardware.org/?probe=959fc9f783) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [641089b224](https://linux-hardware.org/?probe=641089b224) | Sep 13, 2023 |
| AZW           | MINI S 10                   | Desktop     | [5cd0efea8b](https://linux-hardware.org/?probe=5cd0efea8b) | Sep 12, 2023 |
| HP            | 1998                        | Desktop     | [c3451afea8](https://linux-hardware.org/?probe=c3451afea8) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9ea0aa4b28](https://linux-hardware.org/?probe=9ea0aa4b28) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [b12897892a](https://linux-hardware.org/?probe=b12897892a) | Sep 09, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [33cc2ca68e](https://linux-hardware.org/?probe=33cc2ca68e) | Sep 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [23da68a72c](https://linux-hardware.org/?probe=23da68a72c) | Sep 09, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [5180b1e51e](https://linux-hardware.org/?probe=5180b1e51e) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6f3051262d](https://linux-hardware.org/?probe=6f3051262d) | Sep 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [fe6b08c772](https://linux-hardware.org/?probe=fe6b08c772) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [c0422be924](https://linux-hardware.org/?probe=c0422be924) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Google        | Robo360                     | Notebook    | [86308cca01](https://linux-hardware.org/?probe=86308cca01) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Samsung       | 950QED                      | Convertible | [e15539dd35](https://linux-hardware.org/?probe=e15539dd35) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [b744dfb20a](https://linux-hardware.org/?probe=b744dfb20a) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [cdf37a1590](https://linux-hardware.org/?probe=cdf37a1590) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Dell          | XPS 9315                    | Notebook    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | Notebook    | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [5a4e0650a2](https://linux-hardware.org/?probe=5a4e0650a2) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| HP            | 212B                        | Desktop     | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| HP            | 18E7                        | Desktop     | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3acc953bde](https://linux-hardware.org/?probe=3acc953bde) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccdc0814a8](https://linux-hardware.org/?probe=ccdc0814a8) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| Dell          | Precision 7780              | Notebook    | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Irbis         | NB123                       | Notebook    | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [2da4b77f8a](https://linux-hardware.org/?probe=2da4b77f8a) | Aug 17, 2023 |
| Lenovo        | ThinkBook 14s Yoga G3 IR... | Convertible | [74da3f5482](https://linux-hardware.org/?probe=74da3f5482) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [f0d325d7d3](https://linux-hardware.org/?probe=f0d325d7d3) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [a395628119](https://linux-hardware.org/?probe=a395628119) | Aug 15, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [97c78c17bd](https://linux-hardware.org/?probe=97c78c17bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| AZW           | SER V01                     | Mini pc     | [542d8da36c](https://linux-hardware.org/?probe=542d8da36c) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [3d156d18e6](https://linux-hardware.org/?probe=3d156d18e6) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [cb3d78955a](https://linux-hardware.org/?probe=cb3d78955a) | Aug 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | 158A                        | Desktop     | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 3031h                       | Desktop     | [95b5c80f67](https://linux-hardware.org/?probe=95b5c80f67) | Aug 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| HP            | 3031h                       | Desktop     | [04c8ac1eee](https://linux-hardware.org/?probe=04c8ac1eee) | Aug 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [5e552472e5](https://linux-hardware.org/?probe=5e552472e5) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | 158A                        | Desktop     | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb493cc8c8](https://linux-hardware.org/?probe=cb493cc8c8) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Google        | Zako                        | Desktop     | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [65a741810c](https://linux-hardware.org/?probe=65a741810c) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [e5ad011556](https://linux-hardware.org/?probe=e5ad011556) | Jul 30, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7c5e9b6bc6](https://linux-hardware.org/?probe=7c5e9b6bc6) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| AZW           | SER V01                     | Mini pc     | [440a88b8bf](https://linux-hardware.org/?probe=440a88b8bf) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | Desktop     | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | G62                         | Notebook    | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c5028381e5](https://linux-hardware.org/?probe=c5028381e5) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | 83E9                        | Desktop     | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [392b85a82b](https://linux-hardware.org/?probe=392b85a82b) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [0b447416c6](https://linux-hardware.org/?probe=0b447416c6) | Jul 15, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0008f72dbf](https://linux-hardware.org/?probe=0008f72dbf) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [745fa6a1b4](https://linux-hardware.org/?probe=745fa6a1b4) | Jul 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c453f1df6b](https://linux-hardware.org/?probe=c453f1df6b) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [93b2067918](https://linux-hardware.org/?probe=93b2067918) | Jul 11, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [6f62e1063c](https://linux-hardware.org/?probe=6f62e1063c) | Jul 11, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | Notebook    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [9400bf75de](https://linux-hardware.org/?probe=9400bf75de) | Jul 09, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Dell          | G3 3779                     | Notebook    | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| AZW           | SER V01                     | Mini pc     | [49552e2240](https://linux-hardware.org/?probe=49552e2240) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [673c5bfa9a](https://linux-hardware.org/?probe=673c5bfa9a) | Jul 04, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [e76be78ba9](https://linux-hardware.org/?probe=e76be78ba9) | Jul 02, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | Desktop     | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [f953c21e8e](https://linux-hardware.org/?probe=f953c21e8e) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | Notebook                    | Notebook    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [e2c3a51177](https://linux-hardware.org/?probe=e2c3a51177) | Jun 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Irbis         | NB123                       | Notebook    | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [1b099710b7](https://linux-hardware.org/?probe=1b099710b7) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [9bf82397c3](https://linux-hardware.org/?probe=9bf82397c3) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Packard Be... | MCP73                       | Desktop     | [e180017a10](https://linux-hardware.org/?probe=e180017a10) | May 29, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| Packard Be... | MCP73                       | Desktop     | [1203dc5301](https://linux-hardware.org/?probe=1203dc5301) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [80c62a0473](https://linux-hardware.org/?probe=80c62a0473) | May 21, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| HP            | 350 G1                      | Notebook    | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | Desktop     | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Samsung       | Galaxy Book 10.6            | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [1ab8b910e4](https://linux-hardware.org/?probe=1ab8b910e4) | May 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [a3c89effff](https://linux-hardware.org/?probe=a3c89effff) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1417      | 31.7%   |
| Kubuntu 22.04   | 1118      | 25.01%  |
| Kubuntu 23.04   | 301       | 6.73%   |
| Kubuntu 22.10   | 297       | 6.64%   |
| Kubuntu 20.10   | 256       | 5.73%   |
| Kubuntu 21.10   | 242       | 5.41%   |
| Kubuntu 21.04   | 214       | 4.79%   |
| Kubuntu 18.04   | 202       | 4.52%   |
| Kubuntu 19.10   | 178       | 3.98%   |
| Kubuntu 11      | 95        | 2.13%   |
| Kubuntu 23.10   | 58        | 1.3%    |
| Kubuntu 11.1    | 26        | 0.58%   |
| Kubuntu 19.04   | 22        | 0.49%   |
| Kubuntu 16.04   | 13        | 0.29%   |
| Kubuntu         | 8         | 0.18%   |
| Kubuntu 18.10   | 7         | 0.16%   |
| Kubuntu 2.0     | 6         | 0.13%   |
| Kubuntu 17.10   | 3         | 0.07%   |
| Kubuntu 14.04   | 3         | 0.07%   |
| Kubuntu 17.04   | 2         | 0.04%   |
| Kubuntu 20.08.3 | 1         | 0.02%   |
| Kubuntu 12.04   | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 4263      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.09%   |
| 5.15.0-52-generic | 84        | 1.71%   |
| 6.2.0-20-generic  | 80        | 1.62%   |
| 5.15.0-56-generic | 80        | 1.62%   |
| 5.19.0-35-generic | 70        | 1.42%   |
| 5.4.0-52-generic  | 68        | 1.38%   |
| 5.4.0-58-generic  | 59        | 1.2%    |
| 5.4.0-48-generic  | 59        | 1.2%    |
| 5.15.0-48-generic | 58        | 1.18%   |
| 6.2.0-26-generic  | 54        | 1.1%    |
| 5.15.0-46-generic | 53        | 1.08%   |
| 5.13.0-39-generic | 53        | 1.08%   |
| 5.19.0-23-generic | 52        | 1.06%   |
| 5.4.0-40-generic  | 47        | 0.95%   |
| 5.19.0-38-generic | 47        | 0.95%   |
| 6.2.0-34-generic  | 46        | 0.93%   |
| 5.13.0-28-generic | 44        | 0.89%   |
| 5.19.0-31-generic | 43        | 0.87%   |
| 5.15.0-43-generic | 43        | 0.87%   |
| 5.19.0-26-generic | 42        | 0.85%   |
| 5.15.0-58-generic | 42        | 0.85%   |
| 5.15.0-47-generic | 41        | 0.83%   |
| 5.15.0-41-generic | 39        | 0.79%   |
| 5.11.0-37-generic | 38        | 0.77%   |
| 5.11.0-25-generic | 38        | 0.77%   |
| 5.15.0-53-generic | 37        | 0.75%   |
| 5.13.0-30-generic | 37        | 0.75%   |
| 5.4.0-47-generic  | 36        | 0.73%   |
| 5.4.0-65-generic  | 35        | 0.71%   |
| 6.2.0-33-generic  | 34        | 0.69%   |
| 6.2.0-32-generic  | 34        | 0.69%   |
| 5.8.0-48-generic  | 34        | 0.69%   |
| 5.3.0-40-generic  | 34        | 0.69%   |
| 5.4.0-37-generic  | 33        | 0.67%   |
| 5.4.0-29-generic  | 33        | 0.67%   |
| 5.19.0-29-generic | 32        | 0.65%   |
| 5.15.0-60-generic | 32        | 0.65%   |
| 5.13.0-22-generic | 32        | 0.65%   |
| 5.4.0-45-generic  | 30        | 0.61%   |
| 5.15.0-67-generic | 30        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 944       | 20.71%  |
| 5.15.0  | 895       | 19.63%  |
| 5.19.0  | 448       | 9.83%   |
| 5.13.0  | 409       | 8.97%   |
| 5.8.0   | 407       | 8.93%   |
| 6.2.0   | 383       | 8.4%    |
| 5.11.0  | 327       | 7.17%   |
| 5.3.0   | 224       | 4.91%   |
| 4.15.0  | 70        | 1.54%   |
| 6.5.0   | 48        | 1.05%   |
| 5.0.0   | 36        | 0.79%   |
| 5.17.0  | 21        | 0.46%   |
| 5.10.0  | 18        | 0.39%   |
| 5.6.0   | 15        | 0.33%   |
| 4.4.0   | 10        | 0.22%   |
| 6.1.0   | 9         | 0.2%    |
| 6.0.0   | 9         | 0.2%    |
| 5.14.0  | 9         | 0.2%    |
| 4.18.0  | 8         | 0.18%   |
| 6.0.9   | 6         | 0.13%   |
| 6.3.0   | 5         | 0.11%   |
| 5.9.0   | 5         | 0.11%   |
| 6.4.0   | 4         | 0.09%   |
| 6.3.8   | 4         | 0.09%   |
| 5.7.0   | 4         | 0.09%   |
| 6.4.8   | 3         | 0.07%   |
| 6.4.10  | 3         | 0.07%   |
| 6.3.6   | 3         | 0.07%   |
| 6.3.1   | 3         | 0.07%   |
| 6.1.5   | 3         | 0.07%   |
| 5.8.18  | 3         | 0.07%   |
| 5.18.4  | 3         | 0.07%   |
| 5.18.10 | 3         | 0.07%   |
| 5.16.0  | 3         | 0.07%   |
| 5.12.8  | 3         | 0.07%   |
| 5.12.0  | 3         | 0.07%   |
| 4.13.0  | 3         | 0.07%   |
| 4.10.0  | 3         | 0.07%   |
| 6.5.3   | 2         | 0.04%   |
| 6.3.7   | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 951       | 20.89%  |
| 5.15    | 910       | 19.99%  |
| 5.19    | 454       | 9.97%   |
| 5.8     | 423       | 9.29%   |
| 5.13    | 419       | 9.2%    |
| 6.2     | 393       | 8.63%   |
| 5.11    | 333       | 7.32%   |
| 5.3     | 227       | 4.99%   |
| 4.15    | 71        | 1.56%   |
| 6.5     | 55        | 1.21%   |
| 5.0     | 37        | 0.81%   |
| 5.10    | 30        | 0.66%   |
| 6.1     | 28        | 0.62%   |
| 5.17    | 28        | 0.62%   |
| 6.3     | 23        | 0.51%   |
| 6.0     | 21        | 0.46%   |
| 5.6     | 20        | 0.44%   |
| 5.14    | 18        | 0.4%    |
| 6.4     | 14        | 0.31%   |
| 5.9     | 13        | 0.29%   |
| 5.12    | 13        | 0.29%   |
| 5.18    | 12        | 0.26%   |
| 5.7     | 11        | 0.24%   |
| 5.16    | 10        | 0.22%   |
| 4.4     | 10        | 0.22%   |
| 4.18    | 10        | 0.22%   |
| 5.5     | 5         | 0.11%   |
| 4.13    | 3         | 0.07%   |
| 4.10    | 3         | 0.07%   |
| 5.1     | 2         | 0.04%   |
| 6.6     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4243      | 99.53%  |
| i686    | 12        | 0.28%   |
| aarch64 | 6         | 0.14%   |
| riscv64 | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 3344      | 77.19%  |
| KDE        | 923       | 21.31%  |
| GNOME      | 24        | 0.55%   |
| Cinnamon   | 11        | 0.25%   |
| Budgie     | 8         | 0.18%   |
| MATE       | 7         | 0.16%   |
| KDE4       | 4         | 0.09%   |
| XFCE       | 3         | 0.07%   |
| LXQt       | 3         | 0.07%   |
| X-Cinnamon | 1         | 0.02%   |
| Unity      | 1         | 0.02%   |
| i3         | 1         | 0.02%   |
| GNUstep    | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4062      | 94.62%  |
| Wayland | 180       | 4.19%   |
| Tty     | 50        | 1.16%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2589      | 59.6%   |
| Unknown | 1461      | 33.63%  |
| GDM     | 113       | 2.6%    |
| GDM3    | 83        | 1.91%   |
| LightDM | 73        | 1.68%   |
| TDM     | 21        | 0.48%   |
| SLiM    | 2         | 0.05%   |
| LXDM    | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1848      | 42.98%  |
| de_DE   | 365       | 8.49%   |
| ru_RU   | 214       | 4.98%   |
| en_GB   | 212       | 4.93%   |
| fr_FR   | 188       | 4.37%   |
| it_IT   | 183       | 4.26%   |
| pt_BR   | 175       | 4.07%   |
| es_ES   | 91        | 2.12%   |
| en_CA   | 88        | 2.05%   |
| en_AU   | 81        | 1.88%   |
| Unknown | 77        | 1.79%   |
| pl_PL   | 76        | 1.77%   |
| en_IN   | 74        | 1.72%   |
| C       | 46        | 1.07%   |
| hu_HU   | 31        | 0.72%   |
| es_MX   | 30        | 0.7%    |
| nl_NL   | 25        | 0.58%   |
| cs_CZ   | 25        | 0.58%   |
| ru_UA   | 24        | 0.56%   |
| es_AR   | 24        | 0.56%   |
| en_ZA   | 24        | 0.56%   |
| de_AT   | 21        | 0.49%   |
| en_NZ   | 19        | 0.44%   |
| zh_CN   | 15        | 0.35%   |
| tr_TR   | 15        | 0.35%   |
| sv_SE   | 15        | 0.35%   |
| de_CH   | 15        | 0.35%   |
| es_CO   | 14        | 0.33%   |
| pt_PT   | 12        | 0.28%   |
| en_PH   | 12        | 0.28%   |
| en_IE   | 12        | 0.28%   |
| fr_BE   | 11        | 0.26%   |
| fi_FI   | 11        | 0.26%   |
| es_CL   | 11        | 0.26%   |
| el_GR   | 11        | 0.26%   |
| en_IL   | 10        | 0.23%   |
| uk_UA   | 9         | 0.21%   |
| nl_BE   | 9         | 0.21%   |
| es_VE   | 9         | 0.21%   |
| zh_TW   | 7         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2364      | 54.56%  |
| BIOS | 1969      | 45.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3781      | 87.87%  |
| Btrfs    | 173       | 4.02%   |
| Tmpfs    | 149       | 3.46%   |
| Overlay  | 109       | 2.53%   |
| Xfs      | 42        | 0.98%   |
| Zfs      | 22        | 0.51%   |
| Unknown  | 12        | 0.28%   |
| Ext3     | 5         | 0.12%   |
| Ext2     | 4         | 0.09%   |
| F2fs     | 2         | 0.05%   |
| XXXX     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2264      | 52.19%  |
| Unknown | 1699      | 39.17%  |
| MBR     | 375       | 8.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3740      | 86.73%  |
| Yes       | 572       | 13.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2688      | 62.34%  |
| Yes       | 1624      | 37.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 709       | 16.63%  |
| Lenovo              | 654       | 15.34%  |
| Dell                | 572       | 13.42%  |
| Hewlett-Packard     | 571       | 13.39%  |
| Gigabyte Technology | 328       | 7.69%   |
| MSI                 | 285       | 6.69%   |
| Acer                | 198       | 4.64%   |
| ASRock              | 152       | 3.57%   |
| Apple               | 67        | 1.57%   |
| Intel               | 52        | 1.22%   |
| Samsung Electronics | 50        | 1.17%   |
| HUAWEI              | 47        | 1.1%    |
| Unknown             | 36        | 0.84%   |
| Toshiba             | 28        | 0.66%   |
| Notebook            | 28        | 0.66%   |
| Google              | 28        | 0.66%   |
| Fujitsu             | 26        | 0.61%   |
| Sony                | 23        | 0.54%   |
| TUXEDO              | 20        | 0.47%   |
| Alienware           | 19        | 0.45%   |
| AZW                 | 17        | 0.4%    |
| Medion              | 16        | 0.38%   |
| Pegatron            | 15        | 0.35%   |
| Timi                | 14        | 0.33%   |
| Positivo            | 13        | 0.3%    |
| Biostar             | 13        | 0.3%    |
| Packard Bell        | 10        | 0.23%   |
| Microsoft           | 10        | 0.23%   |
| Foxconn             | 10        | 0.23%   |
| Supermicro          | 9         | 0.21%   |
| ECS                 | 9         | 0.21%   |
| ZOTAC               | 8         | 0.19%   |
| System76            | 8         | 0.19%   |
| PC Specialist       | 8         | 0.19%   |
| Chuwi               | 8         | 0.19%   |
| LG Electronics      | 7         | 0.16%   |
| GPU Company         | 7         | 0.16%   |
| Shuttle             | 6         | 0.14%   |
| Schenker            | 6         | 0.14%   |
| Razer               | 6         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 51        | 1.2%    |
| Unknown                            | 50        | 1.17%   |
| ASUS ROG STRIX B550-F GAMING       | 14        | 0.33%   |
| Gigabyte B450M DS3H                | 11        | 0.26%   |
| MSI MS-7C37                        | 10        | 0.23%   |
| MSI MS-7B79                        | 10        | 0.23%   |
| HP Notebook                        | 10        | 0.23%   |
| HP Pavilion g6                     | 9         | 0.21%   |
| HP Pavilion dv6                    | 9         | 0.21%   |
| Dell XPS 15 9560                   | 9         | 0.21%   |
| Dell OptiPlex 9020                 | 9         | 0.21%   |
| Dell OptiPlex 7010                 | 9         | 0.21%   |
| ASUS ROG STRIX X570-E GAMING       | 9         | 0.21%   |
| MSI MS-7C91                        | 8         | 0.19%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.19%   |
| HP Pavilion 15                     | 8         | 0.19%   |
| Gigabyte A320M-S2H                 | 8         | 0.19%   |
| Dell XPS 15 9570                   | 8         | 0.19%   |
| AZW SER                            | 8         | 0.19%   |
| ASUS PRIME B350-PLUS               | 8         | 0.19%   |
| ASUS PRIME A320M-K                 | 8         | 0.19%   |
| MSI MS-7817                        | 7         | 0.16%   |
| HP Pavilion dv7                    | 7         | 0.16%   |
| HP ENVY x360 Convertible 13-ay0xxx | 7         | 0.16%   |
| HP EliteBook 840 G5                | 7         | 0.16%   |
| Gigabyte X570 AORUS MASTER         | 7         | 0.16%   |
| Gigabyte 970A-DS3P                 | 7         | 0.16%   |
| ASUS TUF Gaming B550-PLUS          | 7         | 0.16%   |
| ASUS PRIME B450M-A                 | 7         | 0.16%   |
| MSI MS-7C56                        | 6         | 0.14%   |
| MSI MS-7B86                        | 6         | 0.14%   |
| MSI MS-7A34                        | 6         | 0.14%   |
| MSI MS-7693                        | 6         | 0.14%   |
| HUAWEI HVY-WXX9                    | 6         | 0.14%   |
| HP Pavilion Notebook               | 6         | 0.14%   |
| HP EliteBook 840 G6                | 6         | 0.14%   |
| HP EliteBook 840 G3                | 6         | 0.14%   |
| Dell XPS 15 7590                   | 6         | 0.14%   |
| Dell Latitude 5480                 | 6         | 0.14%   |
| ASUS TUF Gaming X570-PLUS          | 6         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 296       | 6.94%   |
| Dell Latitude      | 158       | 3.71%   |
| Dell Inspiron      | 135       | 3.17%   |
| Acer Aspire        | 127       | 2.98%   |
| Lenovo IdeaPad     | 125       | 2.93%   |
| HP Pavilion        | 112       | 2.63%   |
| ASUS PRIME         | 103       | 2.42%   |
| ASUS ROG           | 100       | 2.35%   |
| Dell XPS           | 83        | 1.95%   |
| HP ProBook         | 71        | 1.67%   |
| HP EliteBook       | 70        | 1.64%   |
| Dell Precision     | 64        | 1.5%    |
| ASUS VivoBook      | 63        | 1.48%   |
| HP Laptop          | 59        | 1.38%   |
| Dell OptiPlex      | 57        | 1.34%   |
| ASUS TUF           | 52        | 1.22%   |
| ASUS All           | 51        | 1.2%    |
| Unknown            | 50        | 1.17%   |
| Lenovo ThinkCentre | 38        | 0.89%   |
| HP ENVY            | 37        | 0.87%   |
| Lenovo Yoga        | 36        | 0.84%   |
| HP Compaq          | 35        | 0.82%   |
| Dell Vostro        | 33        | 0.77%   |
| Lenovo Legion      | 31        | 0.73%   |
| Acer Nitro         | 28        | 0.66%   |
| ASUS ASUS          | 26        | 0.61%   |
| Lenovo ThinkBook   | 25        | 0.59%   |
| Toshiba Satellite  | 24        | 0.56%   |
| ASUS ZenBook       | 20        | 0.47%   |
| HP ZBook           | 19        | 0.45%   |
| Gigabyte B450M     | 19        | 0.45%   |
| Gigabyte X570      | 18        | 0.42%   |
| Acer Swift         | 18        | 0.42%   |
| HP Spectre         | 14        | 0.33%   |
| HP EliteDesk       | 14        | 0.33%   |
| Gigabyte B550      | 14        | 0.33%   |
| Gigabyte A320M-S2H | 12        | 0.28%   |
| Fujitsu ESPRIMO    | 12        | 0.28%   |
| Dell G3            | 12        | 0.28%   |
| ASUS M5A78L-M      | 11        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 524       | 12.29%  |
| 2019    | 486       | 11.4%   |
| 2018    | 452       | 10.6%   |
| 2021    | 387       | 9.08%   |
| 2017    | 303       | 7.11%   |
| 2012    | 295       | 6.92%   |
| 2013    | 282       | 6.62%   |
| 2014    | 251       | 5.89%   |
| 2011    | 241       | 5.65%   |
| 2022    | 207       | 4.86%   |
| 2016    | 199       | 4.67%   |
| 2015    | 190       | 4.46%   |
| 2010    | 134       | 3.14%   |
| 2008    | 101       | 2.37%   |
| 2009    | 100       | 2.35%   |
| 2023    | 49        | 1.15%   |
| 2007    | 41        | 0.96%   |
| 2006    | 9         | 0.21%   |
| Unknown | 8         | 0.19%   |
| 2005    | 3         | 0.07%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2349      | 55.1%   |
| Desktop        | 1594      | 37.39%  |
| Convertible    | 151       | 3.54%   |
| Mini pc        | 68        | 1.6%    |
| All in one     | 46        | 1.08%   |
| Tablet         | 29        | 0.68%   |
| Server         | 19        | 0.45%   |
| System on chip | 6         | 0.14%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3916      | 91.26%  |
| Enabled  | 375       | 8.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4228      | 99.18%  |
| Yes  | 35        | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1108      | 25.74%  |
| 4.01-8.0        | 942       | 21.88%  |
| 8.01-16.0       | 786       | 18.26%  |
| 32.01-64.0      | 618       | 14.36%  |
| 3.01-4.0        | 483       | 11.22%  |
| 64.01-256.0     | 158       | 3.67%   |
| 24.01-32.0      | 125       | 2.9%    |
| 1.01-2.0        | 55        | 1.28%   |
| 2.01-3.0        | 25        | 0.58%   |
| More than 256.0 | 5         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1186      | 25.68%  |
| 4.01-8.0    | 1121      | 24.27%  |
| 1.01-2.0    | 992       | 21.48%  |
| 3.01-4.0    | 802       | 17.37%  |
| 8.01-16.0   | 335       | 7.25%   |
| 0.51-1.0    | 90        | 1.95%   |
| 16.01-24.0  | 55        | 1.19%   |
| 24.01-32.0  | 18        | 0.39%   |
| 32.01-64.0  | 10        | 0.22%   |
| 0.01-0.5    | 7         | 0.15%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2334      | 53.28%  |
| 2      | 1183      | 27%     |
| 3      | 406       | 9.27%   |
| 4      | 228       | 5.2%    |
| 5      | 111       | 2.53%   |
| 6      | 51        | 1.16%   |
| 7      | 29        | 0.66%   |
| 0      | 14        | 0.32%   |
| 8      | 10        | 0.23%   |
| 9      | 5         | 0.11%   |
| 12     | 3         | 0.07%   |
| 11     | 3         | 0.07%   |
| 10     | 3         | 0.07%   |
| 13     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2958      | 68.95%  |
| Yes       | 1332      | 31.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3587      | 83.97%  |
| No        | 685       | 16.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3325      | 77.65%  |
| No        | 957       | 22.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2881      | 67.02%  |
| No        | 1418      | 32.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 829       | 19.39%  |
| Germany      | 490       | 11.46%  |
| Russia       | 287       | 6.71%   |
| Italy        | 238       | 5.57%   |
| France       | 236       | 5.52%   |
| Brazil       | 228       | 5.33%   |
| UK           | 199       | 4.65%   |
| Spain        | 128       | 2.99%   |
| Canada       | 112       | 2.62%   |
| Poland       | 109       | 2.55%   |
| Netherlands  | 99        | 2.32%   |
| India        | 79        | 1.85%   |
| Australia    | 79        | 1.85%   |
| Ukraine      | 64        | 1.5%    |
| Mexico       | 55        | 1.29%   |
| Hungary      | 53        | 1.24%   |
| Switzerland  | 52        | 1.22%   |
| Czechia      | 46        | 1.08%   |
| Belgium      | 41        | 0.96%   |
| Argentina    | 39        | 0.91%   |
| Austria      | 36        | 0.84%   |
| Turkey       | 35        | 0.82%   |
| Sweden       | 33        | 0.77%   |
| Finland      | 29        | 0.68%   |
| South Africa | 27        | 0.63%   |
| Indonesia    | 27        | 0.63%   |
| Bulgaria     | 27        | 0.63%   |
| Greece       | 26        | 0.61%   |
| Portugal     | 23        | 0.54%   |
| Slovenia     | 22        | 0.51%   |
| Romania      | 22        | 0.51%   |
| Denmark      | 22        | 0.51%   |
| Serbia       | 21        | 0.49%   |
| Colombia     | 20        | 0.47%   |
| China        | 20        | 0.47%   |
| New Zealand  | 19        | 0.44%   |
| Norway       | 17        | 0.4%    |
| Chile        | 17        | 0.4%    |
| Slovakia     | 16        | 0.37%   |
| Belarus      | 16        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 78        | 1.74%   |
| Berlin            | 50        | 1.12%   |
| Paris             | 39        | 0.87%   |
| St Petersburg     | 33        | 0.74%   |
| Hamburg           | 33        | 0.74%   |
| Milan             | 31        | 0.69%   |
| Warsaw            | 30        | 0.67%   |
| Rome              | 28        | 0.63%   |
| Sao Paulo         | 26        | 0.58%   |
| Budapest          | 26        | 0.58%   |
| Madrid            | 23        | 0.51%   |
| Cologne           | 23        | 0.51%   |
| Sydney            | 22        | 0.49%   |
| Munich            | 22        | 0.49%   |
| Vienna            | 21        | 0.47%   |
| Amsterdam         | 21        | 0.47%   |
| London            | 20        | 0.45%   |
| Frankfurt am Main | 20        | 0.45%   |
| Rio de Janeiro    | 19        | 0.42%   |
| Kyiv              | 19        | 0.42%   |
| Zurich            | 18        | 0.4%    |
| Melbourne         | 18        | 0.4%    |
| Prague            | 16        | 0.36%   |
| Dallas            | 15        | 0.34%   |
| Sofia             | 14        | 0.31%   |
| Montreal          | 14        | 0.31%   |
| Belgrade          | 14        | 0.31%   |
| Minsk             | 13        | 0.29%   |
| Seattle           | 12        | 0.27%   |
| Novosibirsk       | 12        | 0.27%   |
| Krakow            | 12        | 0.27%   |
| Jakarta           | 12        | 0.27%   |
| Helsinki          | 12        | 0.27%   |
| Athens            | 12        | 0.27%   |
| San Francisco     | 11        | 0.25%   |
| Phoenix           | 11        | 0.25%   |
| Miami             | 11        | 0.25%   |
| Los Angeles       | 11        | 0.25%   |
| Leipzig           | 11        | 0.25%   |
| Istanbul          | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1195      | 1871   | 17.69%  |
| WDC                         | 960       | 1515   | 14.21%  |
| Seagate                     | 848       | 1328   | 12.55%  |
| Kingston                    | 394       | 480    | 5.83%   |
| Toshiba                     | 384       | 534    | 5.68%   |
| SanDisk                     | 382       | 490    | 5.65%   |
| Crucial                     | 285       | 352    | 4.22%   |
| Unknown                     | 220       | 273    | 3.26%   |
| Intel                       | 206       | 271    | 3.05%   |
| SK hynix                    | 182       | 215    | 2.69%   |
| Hitachi                     | 167       | 207    | 2.47%   |
| Micron Technology           | 125       | 143    | 1.85%   |
| HGST                        | 119       | 158    | 1.76%   |
| A-DATA Technology           | 101       | 114    | 1.49%   |
| KIOXIA                      | 63        | 71     | 0.93%   |
| China                       | 57        | 75     | 0.84%   |
| Phison                      | 53        | 68     | 0.78%   |
| Silicon Motion              | 45        | 53     | 0.67%   |
| SPCC                        | 40        | 53     | 0.59%   |
| PNY                         | 39        | 55     | 0.58%   |
| Apple                       | 39        | 45     | 0.58%   |
| Phison Electronics          | 34        | 34     | 0.5%    |
| Intenso                     | 34        | 41     | 0.5%    |
| Patriot                     | 33        | 45     | 0.49%   |
| Transcend                   | 32        | 34     | 0.47%   |
| LITEON                      | 28        | 30     | 0.41%   |
| OCZ                         | 27        | 34     | 0.4%    |
| Micron/Crucial Technology   | 27        | 37     | 0.4%    |
| Corsair                     | 27        | 41     | 0.4%    |
| Unknown                     | 27        | 29     | 0.4%    |
| Maxtor                      | 25        | 29     | 0.37%   |
| JMicron Technology          | 24        | 26     | 0.36%   |
| Kingston Technology Company | 22        | 28     | 0.33%   |
| Team                        | 19        | 20     | 0.28%   |
| GOODRAM                     | 19        | 34     | 0.28%   |
| SABRENT                     | 17        | 20     | 0.25%   |
| XPG                         | 16        | 17     | 0.24%   |
| LITEONIT                    | 15        | 17     | 0.22%   |
| Gigabyte Technology         | 14        | 15     | 0.21%   |
| KingSpec                    | 13        | 15     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                          | 69        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                    | 65        | 0.86%   |
| Samsung SSD 850 EVO 250GB                          | 55        | 0.73%   |
| Samsung SSD 850 EVO 500GB                          | 54        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                    | 49        | 0.65%   |
| Samsung SSD 860 EVO 1TB                            | 45        | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB                     | 43        | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 43        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 38        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                        | 38        | 0.5%    |
| Unknown MMC Card  64GB                             | 35        | 0.46%   |
| Unknown MMC Card  32GB                             | 34        | 0.45%   |
| Toshiba MQ04ABF100 1TB                             | 33        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB                     | 33        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB                       | 33        | 0.44%   |
| Samsung NVMe SSD Drive 500GB                       | 33        | 0.44%   |
| Toshiba MQ01ABD100 1TB                             | 32        | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                     | 32        | 0.42%   |
| HGST HTS721010A9E630 1TB                           | 31        | 0.41%   |
| Samsung NVMe SSD Drive 1TB                         | 30        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 29        | 0.38%   |
| Samsung NVMe SSD Drive 512GB                       | 28        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                     | 27        | 0.36%   |
| Samsung SSD 860 EVO 250GB                          | 27        | 0.36%   |
| Unknown                                            | 27        | 0.36%   |
| Toshiba HDWD110 1TB                                | 26        | 0.34%   |
| Toshiba DT01ACA100 1TB                             | 26        | 0.34%   |
| Seagate ST500DM002-1BD142 500GB                    | 26        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB                     | 26        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                     | 25        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB                     | 25        | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB                     | 23        | 0.3%    |
| SanDisk SSD PLUS 240GB                             | 23        | 0.3%    |
| SanDisk NVMe SSD Drive 1TB                         | 23        | 0.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 23        | 0.3%    |
| Crucial CT500MX500SSD1 500GB                       | 23        | 0.3%    |
| Crucial CT240BX500SSD1 240GB                       | 23        | 0.3%    |
| Seagate Expansion 1TB                              | 22        | 0.29%   |
| Kingston SA400S37120G 120GB SSD                    | 22        | 0.29%   |
| Seagate ST500LT012-1DG142 500GB                    | 21        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 824       | 1284   | 35.76%  |
| WDC                 | 712       | 1161   | 30.9%   |
| Toshiba             | 268       | 379    | 11.63%  |
| Hitachi             | 167       | 207    | 7.25%   |
| HGST                | 118       | 157    | 5.12%   |
| Samsung Electronics | 111       | 174    | 4.82%   |
| Unknown             | 24        | 28     | 1.04%   |
| Maxtor              | 24        | 28     | 1.04%   |
| Apple               | 15        | 15     | 0.65%   |
| Fujitsu             | 12        | 15     | 0.52%   |
| External            | 6         | 12     | 0.26%   |
| Hewlett-Packard     | 3         | 5      | 0.13%   |
| USB3.0              | 2         | 2      | 0.09%   |
| SAGE                | 2         | 2      | 0.09%   |
| LaCie               | 2         | 3      | 0.09%   |
| JMicron Technology  | 2         | 2      | 0.09%   |
| ASMT                | 2         | 2      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| USB                 | 1         | 1      | 0.04%   |
| SABRENT             | 1         | 1      | 0.04%   |
| Magnetic Data       | 1         | 2      | 0.04%   |
| LIO-ORG             | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| ipTIME              | 1         | 1      | 0.04%   |
| IET                 | 1         | 1      | 0.04%   |
| HPE                 | 1         | 6      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 596       | 859    | 25.76%  |
| Kingston            | 287       | 346    | 12.4%   |
| Crucial             | 235       | 296    | 10.16%  |
| SanDisk             | 222       | 278    | 9.59%   |
| WDC                 | 128       | 172    | 5.53%   |
| A-DATA Technology   | 72        | 81     | 3.11%   |
| Intel               | 61        | 79     | 2.64%   |
| China               | 56        | 74     | 2.42%   |
| Micron Technology   | 41        | 46     | 1.77%   |
| Toshiba             | 37        | 52     | 1.6%    |
| PNY                 | 35        | 51     | 1.51%   |
| SPCC                | 33        | 45     | 1.43%   |
| Patriot             | 32        | 44     | 1.38%   |
| SK hynix            | 29        | 31     | 1.25%   |
| Intenso             | 28        | 32     | 1.21%   |
| OCZ                 | 27        | 34     | 1.17%   |
| Transcend           | 26        | 26     | 1.12%   |
| LITEON              | 23        | 24     | 0.99%   |
| GOODRAM             | 19        | 34     | 0.82%   |
| Team                | 17        | 17     | 0.73%   |
| SABRENT             | 16        | 19     | 0.69%   |
| LITEONIT            | 15        | 17     | 0.65%   |
| Corsair             | 15        | 26     | 0.65%   |
| Apple               | 14        | 14     | 0.61%   |
| KingSpec            | 13        | 15     | 0.56%   |
| Apacer              | 11        | 16     | 0.48%   |
| Mushkin             | 10        | 11     | 0.43%   |
| Lexar               | 9         | 10     | 0.39%   |
| Verbatim            | 8         | 10     | 0.35%   |
| Emtec               | 8         | 9      | 0.35%   |
| Unknown             | 8         | 8      | 0.35%   |
| Seagate             | 7         | 12     | 0.3%    |
| Plextor             | 7         | 8      | 0.3%    |
| ASMT                | 7         | 8      | 0.3%    |
| Netac               | 6         | 7      | 0.26%   |
| Hewlett-Packard     | 6         | 6      | 0.26%   |
| Gigabyte Technology | 6         | 6      | 0.26%   |
| Dogfish             | 6         | 6      | 0.26%   |
| Unknown             | 4         | 4      | 0.17%   |
| KingDian            | 4         | 5      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1971      | 2998   | 33.03%  |
| HDD     | 1858      | 3492   | 31.13%  |
| NVMe    | 1843      | 2544   | 30.88%  |
| MMC     | 195       | 239    | 3.27%   |
| Unknown | 101       | 142    | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2941      | 6248   | 56.17%  |
| NVMe | 1832      | 2518   | 34.99%  |
| SAS  | 268       | 410    | 5.12%   |
| MMC  | 195       | 239    | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2067      | 3278   | 50.15%  |
| 0.51-1.0   | 1275      | 1934   | 30.93%  |
| 1.01-2.0   | 432       | 685    | 10.48%  |
| 3.01-4.0   | 152       | 285    | 3.69%   |
| 2.01-3.0   | 101       | 148    | 2.45%   |
| 4.01-10.0  | 81        | 135    | 1.97%   |
| 10.01-20.0 | 14        | 25     | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1070      | 24.19%  |
| 251-500        | 1049      | 23.71%  |
| 501-1000       | 816       | 18.44%  |
| 1001-2000      | 483       | 10.92%  |
| More than 3000 | 346       | 7.82%   |
| 51-100         | 215       | 4.86%   |
| 2001-3000      | 206       | 4.66%   |
| 1-20           | 124       | 2.8%    |
| 21-50          | 97        | 2.19%   |
| Unknown        | 18        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1011      | 22.18%  |
| 101-250        | 796       | 17.46%  |
| 21-50          | 710       | 15.58%  |
| 51-100         | 602       | 13.21%  |
| 251-500        | 532       | 11.67%  |
| 501-1000       | 411       | 9.02%   |
| 1001-2000      | 241       | 5.29%   |
| More than 3000 | 159       | 3.49%   |
| 2001-3000      | 78        | 1.71%   |
| Unknown        | 18        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6         | 6      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 12     | 1.32%   |
| HGST HTS721010A9E630 1TB              | 6         | 7      | 1.32%   |
| Seagate ST31000524AS 1TB              | 5         | 6      | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 5      | 1.1%    |
| Toshiba MQ04ABF100 1TB                | 4         | 4      | 0.88%   |
| Toshiba MQ01ABD100 1TB                | 4         | 6      | 0.88%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 0.88%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 0.88%   |
| Seagate ST1000DM003-1CH162 1TB        | 4         | 10     | 0.88%   |
| Crucial CT1050MX300SSD1 1050GB        | 4         | 4      | 0.88%   |
| WDC WD5000AAKS-00V1A0 500GB           | 3         | 4      | 0.66%   |
| WDC WD30EZRX-00MMMB0 3TB              | 3         | 3      | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3         | 6      | 0.66%   |
| Seagate ST9500325AS 500GB             | 3         | 7      | 0.66%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.66%   |
| Seagate ST31000528AS 1TB              | 3         | 3      | 0.66%   |
| Seagate ST1000LM048-2E7172 1TB        | 3         | 3      | 0.66%   |
| SanDisk SSD PLUS 240GB                | 3         | 3      | 0.66%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 0.66%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.66%   |
| Hitachi HTS547564A9E384 640GB         | 3         | 3      | 0.66%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 0.66%   |
| HGST HTS541010A9E680 1TB              | 3         | 7      | 0.66%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 0.66%   |
| WDC WD5000AAKS-00A7B0 500GB           | 2         | 2      | 0.44%   |
| WDC WD40EZRZ-00GXCB0 4TB              | 2         | 2      | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB              | 2         | 4      | 0.44%   |
| WDC WD3200JD-22KLB0 320GB             | 2         | 2      | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 0.44%   |
| WDC WD20EARX-00PASB0 2TB              | 2         | 2      | 0.44%   |
| WDC WD15EARS-00Z5B1 1TB               | 2         | 2      | 0.44%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2         | 3      | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 2      | 0.44%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2         | 2      | 0.44%   |
| WDC WD10EARS-00MVWB0 1TB              | 2         | 4      | 0.44%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 0.44%   |
| WDC WD1001FALS-40U9B0 1TB             | 2         | 2      | 0.44%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 2         | 2      | 0.44%   |
| Toshiba MQ01ABD075 752GB              | 2         | 4      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 97        | 121    | 22%     |
| Seagate             | 95        | 125    | 21.54%  |
| Samsung Electronics | 46        | 63     | 10.43%  |
| Toshiba             | 37        | 43     | 8.39%   |
| Hitachi             | 29        | 29     | 6.58%   |
| Crucial             | 19        | 23     | 4.31%   |
| SanDisk             | 17        | 18     | 3.85%   |
| Intel               | 15        | 20     | 3.4%    |
| HGST                | 15        | 20     | 3.4%    |
| SK hynix            | 11        | 11     | 2.49%   |
| Kingston            | 10        | 10     | 2.27%   |
| Maxtor              | 6         | 7      | 1.36%   |
| A-DATA Technology   | 6         | 6      | 1.36%   |
| Micron Technology   | 5         | 5      | 1.13%   |
| OCZ                 | 4         | 4      | 0.91%   |
| Apple               | 4         | 4      | 0.91%   |
| Neo                 | 2         | 2      | 0.45%   |
| LITEONIT            | 2         | 2      | 0.45%   |
| Intenso             | 2         | 2      | 0.45%   |
| Fujitsu             | 2         | 2      | 0.45%   |
| Zheino              | 1         | 2      | 0.23%   |
| XPG                 | 1         | 1      | 0.23%   |
| VISIPRO             | 1         | 2      | 0.23%   |
| VENO                | 1         | 1      | 0.23%   |
| tecmiyo             | 1         | 3      | 0.23%   |
| Team                | 1         | 1      | 0.23%   |
| T-FORCE             | 1         | 1      | 0.23%   |
| SPCC                | 1         | 1      | 0.23%   |
| R580                | 1         | 1      | 0.23%   |
| Phison Electronics  | 1         | 1      | 0.23%   |
| ORTIAL              | 1         | 1      | 0.23%   |
| Mushkin             | 1         | 1      | 0.23%   |
| LITEON              | 1         | 1      | 0.23%   |
| Drevo               | 1         | 1      | 0.23%   |
| BAITITON            | 1         | 3      | 0.23%   |
| ASMT                | 1         | 1      | 0.23%   |
| ASENNO              | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 95        | 125    | 31.99%  |
| WDC                 | 94        | 118    | 31.65%  |
| Toshiba             | 32        | 38     | 10.77%  |
| Hitachi             | 29        | 29     | 9.76%   |
| Samsung Electronics | 19        | 34     | 6.4%    |
| HGST                | 15        | 20     | 5.05%   |
| Maxtor              | 6         | 7      | 2.02%   |
| Apple               | 4         | 4      | 1.35%   |
| Fujitsu             | 2         | 2      | 0.67%   |
| ASMT                | 1         | 1      | 0.34%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 269       | 378    | 65.61%  |
| SSD  | 115       | 135    | 28.05%  |
| NVMe | 26        | 27     | 6.34%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 14.29%  |
| OCZ VERTEX460A 480GB SSD              | 1         | 1      | 14.29%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 14.29%  |
| Acer SSD FA100 256GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 28.57%  |
| Seagate             | 1         | 1      | 14.29%  |
| OCZ                 | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Acer                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2204      | 4938   | 45.99%  |
| Works    | 2184      | 3929   | 45.58%  |
| Malfunc  | 398       | 540    | 8.31%   |
| Failed   | 6         | 8      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2670      | 46.27%  |
| AMD                              | 960       | 16.64%  |
| Samsung Electronics              | 596       | 10.33%  |
| SanDisk                          | 313       | 5.42%   |
| SK hynix                         | 152       | 2.63%   |
| Kingston Technology Company      | 130       | 2.25%   |
| Phison Electronics               | 107       | 1.85%   |
| ASMedia Technology               | 100       | 1.73%   |
| Toshiba America Info Systems     | 91        | 1.58%   |
| Micron Technology                | 84        | 1.46%   |
| Micron/Crucial Technology        | 77        | 1.33%   |
| Silicon Motion                   | 62        | 1.07%   |
| KIOXIA                           | 59        | 1.02%   |
| JMicron Technology               | 57        | 0.99%   |
| Marvell Technology Group         | 49        | 0.85%   |
| ADATA Technology                 | 46        | 0.8%    |
| Nvidia                           | 43        | 0.75%   |
| Realtek Semiconductor            | 27        | 0.47%   |
| Solid State Storage Technology   | 18        | 0.31%   |
| Union Memory (Shenzhen)          | 17        | 0.29%   |
| Broadcom / LSI                   | 14        | 0.24%   |
| LSI Logic / Symbios Logic        | 13        | 0.23%   |
| Silicon Image                    | 10        | 0.17%   |
| Lite-On Technology               | 10        | 0.17%   |
| Seagate Technology               | 8         | 0.14%   |
| Apple                            | 8         | 0.14%   |
| VIA Technologies                 | 7         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.12%   |
| Lenovo                           | 5         | 0.09%   |
| Shenzhen Longsys Electronics     | 4         | 0.07%   |
| Netac Technology                 | 3         | 0.05%   |
| INNOGRIT                         | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Solidigm                         | 2         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Zhaoxin                          | 1         | 0.02%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 681       | 10.4%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 321       | 4.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 219       | 3.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 210       | 3.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 172       | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 167       | 2.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 144       | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 133       | 2.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 105       | 1.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 103       | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 103       | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 102       | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                         | 94        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 93        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 93        | 1.42%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 92        | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 91        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 84        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 84        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 82        | 1.25%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 78        | 1.19%   |
| Intel SSD 660P Series                                                          | 72        | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 71        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 66        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 66        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 66        | 1.01%   |
| Intel SATA Controller [RAID mode]                                              | 64        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 59        | 0.9%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 57        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 54        | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 0.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 52        | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 49        | 0.75%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 47        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 46        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 45        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 45        | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 43        | 0.66%   |
| AMD FCH SATA Controller D                                                      | 43        | 0.66%   |
| AMD 300 Series Chipset SATA Controller                                         | 43        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3110      | 54.04%  |
| NVMe | 1824      | 31.69%  |
| RAID | 431       | 7.49%   |
| IDE  | 365       | 6.34%   |
| SAS  | 17        | 0.3%    |
| SCSI | 8         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 3049      | 71.52%  |
| AMD           | 1205      | 28.27%  |
| ARM           | 4         | 0.09%   |
| sifive,u74-mc | 2         | 0.05%   |
| QUALCOMM      | 1         | 0.02%   |
| Phytium       | 1         | 0.02%   |
| CentaurHauls  | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 68        | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 54        | 1.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 50        | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 48        | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 43        | 1.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 42        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 41        | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 39        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 39        | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 39        | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 38        | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 37        | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 33        | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 31        | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 29        | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 29        | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 28        | 0.66%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 28        | 0.66%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.61%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 26        | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 26        | 0.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 25        | 0.59%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 24        | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 22        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 21        | 0.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 20        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 20        | 0.47%   |
| Intel 12th Gen Core i7-12700H                 | 20        | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 19        | 0.44%   |
| Intel 12th Gen Core i7-1260P                  | 19        | 0.44%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 19        | 0.44%   |
| AMD FX-8350 Eight-Core Processor              | 19        | 0.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 18        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 964       | 22.57%  |
| Intel Core i5           | 908       | 21.26%  |
| Other                   | 385       | 9.01%   |
| AMD Ryzen 5             | 349       | 8.17%   |
| AMD Ryzen 7             | 294       | 6.88%   |
| Intel Core i3           | 220       | 5.15%   |
| Intel Celeron           | 156       | 3.65%   |
| AMD Ryzen 9             | 100       | 2.34%   |
| Intel Core 2 Duo        | 94        | 2.2%    |
| Intel Xeon              | 90        | 2.11%   |
| Intel Pentium           | 73        | 1.71%   |
| AMD FX                  | 72        | 1.69%   |
| AMD Ryzen 3             | 51        | 1.19%   |
| Intel Core i9           | 41        | 0.96%   |
| AMD A10                 | 33        | 0.77%   |
| AMD A6                  | 32        | 0.75%   |
| AMD Ryzen 7 PRO         | 31        | 0.73%   |
| AMD A8                  | 30        | 0.7%    |
| Intel Atom              | 28        | 0.66%   |
| Intel Pentium Dual-Core | 27        | 0.63%   |
| AMD Phenom II X4        | 25        | 0.59%   |
| Intel Core 2 Quad       | 24        | 0.56%   |
| AMD Ryzen 5 PRO         | 18        | 0.42%   |
| Intel Pentium Silver    | 17        | 0.4%    |
| AMD Athlon              | 15        | 0.35%   |
| AMD A4                  | 15        | 0.35%   |
| AMD Athlon II X4        | 14        | 0.33%   |
| AMD Ryzen Threadripper  | 11        | 0.26%   |
| AMD E                   | 9         | 0.21%   |
| AMD Athlon II X2        | 9         | 0.21%   |
| AMD Athlon 64 X2        | 9         | 0.21%   |
| Intel Pentium Dual      | 8         | 0.19%   |
| Intel Genuine           | 8         | 0.19%   |
| AMD E1                  | 8         | 0.19%   |
| AMD Phenom II X6        | 7         | 0.16%   |
| AMD E2                  | 7         | 0.16%   |
| Intel Core m3           | 6         | 0.14%   |
| Intel Core 2            | 5         | 0.12%   |
| Intel Celeron Dual-Core | 5         | 0.12%   |
| AMD Sempron             | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1684      | 39.44%  |
| 2       | 1285      | 30.09%  |
| 6       | 569       | 13.33%  |
| 8       | 426       | 9.98%   |
| 12      | 100       | 2.34%   |
| 16      | 53        | 1.24%   |
| 1       | 39        | 0.91%   |
| 10      | 36        | 0.84%   |
| 14      | 34        | 0.8%    |
| 24      | 14        | 0.33%   |
| 3       | 12        | 0.28%   |
| 32      | 5         | 0.12%   |
| Unknown | 4         | 0.09%   |
| 20      | 3         | 0.07%   |
| 18      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4227      | 99.16%  |
| 2       | 29        | 0.68%   |
| Unknown | 4         | 0.09%   |
| 4       | 2         | 0.05%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3218      | 75.29%  |
| 1       | 1052      | 24.61%  |
| Unknown | 4         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4257      | 99.86%  |
| Unknown        | 3         | 0.07%   |
| 32-bit         | 2         | 0.05%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1417      | 32.25%  |
| 0x306a9    | 181       | 4.12%   |
| 0x306c3    | 171       | 3.89%   |
| 0x206a7    | 158       | 3.6%    |
| 0x906ea    | 128       | 2.91%   |
| 0x806ec    | 113       | 2.57%   |
| 0x806c1    | 109       | 2.48%   |
| 0x806ea    | 103       | 2.34%   |
| 0x40651    | 82        | 1.87%   |
| 0x1067a    | 80        | 1.82%   |
| 0x906e9    | 79        | 1.8%    |
| 0x08701021 | 79        | 1.8%    |
| 0x806e9    | 76        | 1.73%   |
| 0x506e3    | 75        | 1.71%   |
| 0x406e3    | 62        | 1.41%   |
| 0x0a50000c | 62        | 1.41%   |
| 0x08108109 | 58        | 1.32%   |
| 0x08600106 | 47        | 1.07%   |
| 0x0800820d | 47        | 1.07%   |
| 0x306d4    | 46        | 1.05%   |
| 0x906a3    | 43        | 0.98%   |
| 0x06000852 | 40        | 0.91%   |
| 0x706e5    | 39        | 0.89%   |
| 0x08701013 | 39        | 0.89%   |
| 0x08108102 | 39        | 0.89%   |
| 0xa0652    | 37        | 0.84%   |
| 0x906ed    | 32        | 0.73%   |
| 0x806eb    | 32        | 0.73%   |
| 0x08608103 | 31        | 0.71%   |
| 0x20655    | 29        | 0.66%   |
| 0x010000c8 | 29        | 0.66%   |
| 0x706a1    | 28        | 0.64%   |
| 0x706a8    | 24        | 0.55%   |
| 0x406c4    | 23        | 0.52%   |
| 0x08600104 | 23        | 0.52%   |
| 0x06001119 | 21        | 0.48%   |
| 0x806d1    | 20        | 0.46%   |
| 0x30678    | 20        | 0.46%   |
| 0xa0653    | 19        | 0.43%   |
| 0x506c9    | 19        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 793       | 18.55%  |
| Haswell          | 402       | 9.4%    |
| IvyBridge        | 288       | 6.74%   |
| Zen 2            | 275       | 6.43%   |
| SandyBridge      | 242       | 5.66%   |
| Skylake          | 212       | 4.96%   |
| Zen+             | 208       | 4.86%   |
| Unknown          | 196       | 4.58%   |
| Zen 3            | 187       | 4.37%   |
| TigerLake        | 174       | 4.07%   |
| Penryn           | 133       | 3.11%   |
| CometLake        | 112       | 2.62%   |
| Zen              | 96        | 2.25%   |
| Icelake          | 94        | 2.2%    |
| Alderlake Hybrid | 94        | 2.2%    |
| Piledriver       | 92        | 2.15%   |
| Goldmont plus    | 80        | 1.87%   |
| K10              | 75        | 1.75%   |
| Broadwell        | 75        | 1.75%   |
| Westmere         | 72        | 1.68%   |
| Silvermont       | 64        | 1.5%    |
| Core             | 55        | 1.29%   |
| Excavator        | 49        | 1.15%   |
| Nehalem          | 47        | 1.1%    |
| Goldmont         | 28        | 0.65%   |
| Puma             | 20        | 0.47%   |
| Steamroller      | 19        | 0.44%   |
| K10 Llano        | 19        | 0.44%   |
| K8 Hammer        | 16        | 0.37%   |
| Bobcat           | 16        | 0.37%   |
| Jaguar           | 15        | 0.35%   |
| Bulldozer        | 8         | 0.19%   |
| NetBurst         | 7         | 0.16%   |
| Bonnell          | 6         | 0.14%   |
| Tremont          | 4         | 0.09%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2367      | 45.78%  |
| Nvidia                           | 1542      | 29.83%  |
| AMD                              | 1239      | 23.97%  |
| Matrox Electronics Systems       | 9         | 0.17%   |
| ASPEED Technology                | 9         | 0.17%   |
| ATI Technologies                 | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 168       | 3.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 161       | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 159       | 3.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 137       | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 135       | 2.55%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 123       | 2.33%   |
| Intel UHD Graphics 620                                                                   | 119       | 2.25%   |
| Intel HD Graphics 620                                                                    | 101       | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 97        | 1.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 96        | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 93        | 1.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 92        | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 90        | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 88        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 84        | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 1.51%   |
| Intel HD Graphics 530                                                                    | 70        | 1.32%   |
| Intel HD Graphics 630                                                                    | 66        | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 60        | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 60        | 1.13%   |
| Intel HD Graphics 5500                                                                   | 57        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 56        | 1.06%   |
| AMD Lucienne                                                                             | 56        | 1.06%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 54        | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 42        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 41        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 38        | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 35        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 34        | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 32        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 31        | 0.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 29        | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 0.55%   |
| AMD Rembrandt [Radeon 680M]                                                              | 29        | 0.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 28        | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 28        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1561      | 36.47%  |
| 1 x AMD                  | 969       | 22.64%  |
| 1 x Nvidia               | 785       | 18.34%  |
| Intel + Nvidia           | 639       | 14.93%  |
| Intel + AMD              | 112       | 2.62%   |
| AMD + Nvidia             | 92        | 2.15%   |
| 2 x AMD                  | 66        | 1.54%   |
| 2 x Nvidia               | 17        | 0.4%    |
| Other                    | 11        | 0.26%   |
| 1 x ASPEED               | 5         | 0.12%   |
| Nvidia + ASPEED          | 4         | 0.09%   |
| 1 x Matrox               | 4         | 0.09%   |
| 3 x Nvidia               | 3         | 0.07%   |
| Nvidia + Matrox          | 3         | 0.07%   |
| 2 x Intel                | 2         | 0.05%   |
| AMD + Matrox             | 2         | 0.05%   |
| 3 x AMD                  | 1         | 0.02%   |
| 1 x Zhaoxin              | 1         | 0.02%   |
| 1 x SiS                  | 1         | 0.02%   |
| Intel + 2 x AMD          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3115      | 72.17%  |
| Proprietary | 1110      | 25.72%  |
| Unknown     | 91        | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2429      | 55.57%  |
| 1.01-2.0   | 480       | 10.98%  |
| 0.01-0.5   | 378       | 8.65%   |
| 3.01-4.0   | 328       | 7.5%    |
| 0.51-1.0   | 294       | 6.73%   |
| 7.01-8.0   | 223       | 5.1%    |
| 5.01-6.0   | 124       | 2.84%   |
| 8.01-16.0  | 59        | 1.35%   |
| 2.01-3.0   | 39        | 0.89%   |
| 16.01-24.0 | 12        | 0.27%   |
| 4.01-5.0   | 4         | 0.09%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 640       | 12.75%  |
| AU Optronics            | 530       | 10.56%  |
| BOE                     | 456       | 9.08%   |
| LG Display              | 421       | 8.38%   |
| Chimei Innolux          | 407       | 8.11%   |
| Dell                    | 331       | 6.59%   |
| Goldstar                | 276       | 5.5%    |
| Hewlett-Packard         | 177       | 3.53%   |
| Acer                    | 176       | 3.51%   |
| BenQ                    | 125       | 2.49%   |
| Philips                 | 124       | 2.47%   |
| Ancor Communications    | 121       | 2.41%   |
| AOC                     | 120       | 2.39%   |
| Sharp                   | 115       | 2.29%   |
| Lenovo                  | 68        | 1.35%   |
| Iiyama                  | 67        | 1.33%   |
| ASUSTek Computer        | 66        | 1.31%   |
| ViewSonic               | 58        | 1.16%   |
| Apple                   | 55        | 1.1%    |
| PANDA                   | 52        | 1.04%   |
| Chi Mei Optoelectronics | 49        | 0.98%   |
| InfoVision              | 40        | 0.8%    |
| LG Electronics          | 31        | 0.62%   |
| Sony                    | 25        | 0.5%    |
| Unknown                 | 24        | 0.48%   |
| NEC Computers           | 21        | 0.42%   |
| Eizo                    | 20        | 0.4%    |
| CSO                     | 20        | 0.4%    |
| Panasonic               | 19        | 0.38%   |
| Sceptre Tech            | 15        | 0.3%    |
| HannStar                | 15        | 0.3%    |
| MSI                     | 13        | 0.26%   |
| Medion                  | 12        | 0.24%   |
| Gigabyte Technology     | 12        | 0.24%   |
| Vizio                   | 11        | 0.22%   |
| Toshiba                 | 10        | 0.2%    |
| Vestel Elektronik       | 8         | 0.16%   |
| Idek Iiyama             | 8         | 0.16%   |
| RTK                     | 7         | 0.14%   |
| LG Philips              | 7         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 23        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 22        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 22        | 0.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 21        | 0.4%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch               | 20        | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 20        | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 18        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 18        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 18        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 16        | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 15        | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 13        | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 13        | 0.25%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 13        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 12        | 0.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 11        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 11        | 0.21%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 10        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 10        | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 9         | 0.17%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 9         | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.17%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                          | 9         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 8         | 0.15%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 8         | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 8         | 0.15%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 8         | 0.15%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 8         | 0.15%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 8         | 0.15%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 8         | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                        | 8         | 0.15%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 8         | 0.15%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 8         | 0.15%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 8         | 0.15%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 7         | 0.13%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 7         | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2277      | 48.19%  |
| 1366x768 (WXGA)    | 657       | 13.9%   |
| 3840x2160 (4K)     | 349       | 7.39%   |
| 2560x1440 (QHD)    | 258       | 5.46%   |
| 1600x900 (HD+)     | 167       | 3.53%   |
| 1920x1200 (WUXGA)  | 154       | 3.26%   |
| 1680x1050 (WSXGA+) | 111       | 2.35%   |
| 1280x1024 (SXGA)   | 90        | 1.9%    |
| Unknown            | 77        | 1.63%   |
| 1440x900 (WXGA+)   | 64        | 1.35%   |
| 3440x1440          | 62        | 1.31%   |
| 2560x1080          | 52        | 1.1%    |
| 2560x1600          | 43        | 0.91%   |
| 1280x800 (WXGA)    | 42        | 0.89%   |
| 3840x1080          | 37        | 0.78%   |
| 1360x768           | 33        | 0.7%    |
| 2880x1800          | 32        | 0.68%   |
| 3840x2400          | 20        | 0.42%   |
| 2160x1440          | 20        | 0.42%   |
| 1920x540           | 14        | 0.3%    |
| 1600x1200          | 13        | 0.28%   |
| 1024x768 (XGA)     | 12        | 0.25%   |
| 2240x1400          | 11        | 0.23%   |
| 3840x1200          | 9         | 0.19%   |
| 3200x1800 (QHD+)   | 8         | 0.17%   |
| 1920x1280          | 8         | 0.17%   |
| 2256x1504          | 7         | 0.15%   |
| 4480x1440          | 6         | 0.13%   |
| 3840x1600          | 6         | 0.13%   |
| 2736x1824          | 5         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.11%   |
| 5760x1080          | 4         | 0.08%   |
| 3456x2160          | 4         | 0.08%   |
| 3072x1920          | 4         | 0.08%   |
| 2520x1680          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 5760x2160          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3200x2000          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1173      | 23.44%  |
| 27      | 436       | 8.71%   |
| 24      | 430       | 8.59%   |
| 13      | 407       | 8.13%   |
| 14      | 395       | 7.89%   |
| 23      | 351       | 7.01%   |
| 17      | 290       | 5.8%    |
| 21      | 275       | 5.5%    |
| Unknown | 243       | 4.86%   |
| 31      | 126       | 2.52%   |
| 34      | 100       | 2%      |
| 19      | 96        | 1.92%   |
| 22      | 70        | 1.4%    |
| 20      | 66        | 1.32%   |
| 16      | 63        | 1.26%   |
| 12      | 61        | 1.22%   |
| 11      | 57        | 1.14%   |
| 18      | 53        | 1.06%   |
| 84      | 30        | 0.6%    |
| 32      | 30        | 0.6%    |
| 54      | 29        | 0.58%   |
| 72      | 27        | 0.54%   |
| 40      | 26        | 0.52%   |
| 25      | 25        | 0.5%    |
| 26      | 14        | 0.28%   |
| 46      | 13        | 0.26%   |
| 28      | 13        | 0.26%   |
| 48      | 10        | 0.2%    |
| 37      | 8         | 0.16%   |
| 42      | 7         | 0.14%   |
| 10      | 7         | 0.14%   |
| 65      | 6         | 0.12%   |
| 52      | 5         | 0.1%    |
| 36      | 5         | 0.1%    |
| 69      | 4         | 0.08%   |
| 60      | 4         | 0.08%   |
| 49      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 35      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1820      | 37.3%   |
| 501-600        | 1111      | 22.77%  |
| 401-500        | 498       | 10.21%  |
| 351-400        | 344       | 7.05%   |
| 201-300        | 326       | 6.68%   |
| Unknown        | 243       | 4.98%   |
| 601-700        | 190       | 3.89%   |
| 701-800        | 137       | 2.81%   |
| 1001-1500      | 83        | 1.7%    |
| 1501-2000      | 65        | 1.33%   |
| 801-900        | 44        | 0.9%    |
| 901-1000       | 10        | 0.2%    |
| More than 2000 | 3         | 0.06%   |
| 1-100          | 3         | 0.06%   |
| 101-200        | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3341      | 76.52%  |
| 16/10   | 498       | 11.41%  |
| Unknown | 211       | 4.83%   |
| 21/9    | 113       | 2.59%   |
| 5/4     | 84        | 1.92%   |
| 3/2     | 57        | 1.31%   |
| 4/3     | 28        | 0.64%   |
| 32/9    | 16        | 0.37%   |
| 6/5     | 5         | 0.11%   |
| 0.56    | 4         | 0.09%   |
| 1.00    | 3         | 0.07%   |
| 1.96    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1172      | 23.82%  |
| 201-250        | 853       | 17.34%  |
| 81-90          | 636       | 12.93%  |
| 301-350        | 447       | 9.09%   |
| 351-500        | 271       | 5.51%   |
| Unknown        | 243       | 4.94%   |
| 151-200        | 229       | 4.65%   |
| 121-130        | 224       | 4.55%   |
| 71-80          | 173       | 3.52%   |
| 251-300        | 169       | 3.43%   |
| More than 1000 | 124       | 2.52%   |
| 141-150        | 83        | 1.69%   |
| 501-1000       | 80        | 1.63%   |
| 51-60          | 58        | 1.18%   |
| 111-120        | 55        | 1.12%   |
| 61-70          | 50        | 1.02%   |
| 131-140        | 28        | 0.57%   |
| 91-100         | 13        | 0.26%   |
| 41-50          | 7         | 0.14%   |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1506      | 31.55%  |
| 121-160       | 1399      | 29.3%   |
| 101-120       | 1034      | 21.66%  |
| 161-240       | 330       | 6.91%   |
| Unknown       | 243       | 5.09%   |
| More than 240 | 145       | 3.04%   |
| 1-50          | 117       | 2.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3210      | 73.78%  |
| 2     | 917       | 21.08%  |
| 3     | 115       | 2.64%   |
| 0     | 95        | 2.18%   |
| 4     | 14        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2417      | 37.54%  |
| Intel                             | 2210      | 34.32%  |
| Qualcomm Atheros                  | 614       | 9.54%   |
| Broadcom                          | 269       | 4.18%   |
| MediaTek                          | 142       | 2.21%   |
| TP-Link                           | 75        | 1.16%   |
| Ralink Technology                 | 67        | 1.04%   |
| Ralink                            | 59        | 0.92%   |
| Broadcom Limited                  | 46        | 0.71%   |
| ASIX Electronics                  | 36        | 0.56%   |
| Nvidia                            | 35        | 0.54%   |
| Marvell Technology Group          | 32        | 0.5%    |
| Samsung Electronics               | 29        | 0.45%   |
| Aquantia                          | 24        | 0.37%   |
| Qualcomm Atheros Communications   | 21        | 0.33%   |
| Lenovo                            | 21        | 0.33%   |
| DisplayLink                       | 21        | 0.33%   |
| NetGear                           | 20        | 0.31%   |
| Microsoft                         | 19        | 0.3%    |
| Xiaomi                            | 18        | 0.28%   |
| Qualcomm                          | 18        | 0.28%   |
| Huawei Technologies               | 18        | 0.28%   |
| Sierra Wireless                   | 16        | 0.25%   |
| D-Link                            | 15        | 0.23%   |
| Dell                              | 13        | 0.2%    |
| Edimax Technology                 | 12        | 0.19%   |
| ASUSTek Computer                  | 12        | 0.19%   |
| Hewlett-Packard                   | 11        | 0.17%   |
| Ericsson Business Mobile Networks | 10        | 0.16%   |
| JMicron Technology                | 8         | 0.12%   |
| Linksys                           | 7         | 0.11%   |
| Google                            | 7         | 0.11%   |
| Belkin Components                 | 7         | 0.11%   |
| Apple                             | 7         | 0.11%   |
| D-Link System                     | 6         | 0.09%   |
| Fibocom                           | 5         | 0.08%   |
| AVM                               | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.06%   |
| VIA Technologies                  | 4         | 0.06%   |
| Arduino SA                        | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1636      | 21.7%   |
| Intel Wi-Fi 6 AX200                                               | 245       | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 208       | 2.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 150       | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 147       | 1.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 144       | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 140       | 1.86%   |
| Intel I211 Gigabit Network Connection                             | 130       | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 122       | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 114       | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 102       | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 98        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 97        | 1.29%   |
| Intel Wireless 7260                                               | 97        | 1.29%   |
| Intel Wireless 7265                                               | 96        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 87        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 81        | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 80        | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 76        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 75        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 71        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 67        | 0.89%   |
| Intel Wireless 8260                                               | 66        | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 65        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 65        | 0.86%   |
| Intel Wireless 3165                                               | 64        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 63        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 59        | 0.78%   |
| Intel Wireless-AC 9260                                            | 52        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 51        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 49        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 45        | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 44        | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 43        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 40        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 37        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 35        | 0.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 34        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1694      | 48.34%  |
| Realtek Semiconductor                 | 584       | 16.67%  |
| Qualcomm Atheros                      | 483       | 13.78%  |
| Broadcom                              | 179       | 5.11%   |
| MediaTek                              | 136       | 3.88%   |
| TP-Link                               | 67        | 1.91%   |
| Ralink Technology                     | 67        | 1.91%   |
| Ralink                                | 59        | 1.68%   |
| Broadcom Limited                      | 36        | 1.03%   |
| Qualcomm Atheros Communications       | 21        | 0.6%    |
| NetGear                               | 20        | 0.57%   |
| Microsoft                             | 18        | 0.51%   |
| Sierra Wireless                       | 16        | 0.46%   |
| D-Link                                | 15        | 0.43%   |
| Qualcomm                              | 12        | 0.34%   |
| Edimax Technology                     | 12        | 0.34%   |
| ASUSTek Computer                      | 12        | 0.34%   |
| Dell                                  | 8         | 0.23%   |
| Belkin Components                     | 7         | 0.2%    |
| Marvell Technology Group              | 6         | 0.17%   |
| Linksys                               | 6         | 0.17%   |
| Fibocom                               | 5         | 0.14%   |
| AVM                                   | 5         | 0.14%   |
| Hewlett-Packard                       | 4         | 0.11%   |
| Ericsson Business Mobile Networks     | 4         | 0.11%   |
| D-Link System                         | 4         | 0.11%   |
| Wacom                                 | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| ZyDAS                                 | 2         | 0.06%   |
| Wilocity                              | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| Texas Instruments                     | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| LG Electronics                        | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 245       | 6.93%   |
| Intel Wireless 8265 / 8275                                     | 140       | 3.96%   |
| Intel Wi-Fi 6 AX201                                            | 122       | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 114       | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 102       | 2.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 98        | 2.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 97        | 2.74%   |
| Intel Wireless 7260                                            | 97        | 2.74%   |
| Intel Wireless 7265                                            | 96        | 2.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 87        | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 81        | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 80        | 2.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 76        | 2.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 70        | 1.98%   |
| Intel Wireless 8260                                            | 66        | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 65        | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 65        | 1.84%   |
| Intel Wireless 3165                                            | 64        | 1.81%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 59        | 1.67%   |
| Intel Wireless-AC 9260                                         | 52        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 51        | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 49        | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 44        | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 43        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 40        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 37        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 35        | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 34        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 31        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                | 31        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 30        | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 30        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 29        | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 28        | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 28        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 27        | 0.76%   |
| Intel Wireless 3160                                            | 27        | 0.76%   |
| Realtek 802.11ac NIC                                           | 26        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 25        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 24        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2151      | 55.88%  |
| Intel                            | 1091      | 28.35%  |
| Qualcomm Atheros                 | 172       | 4.47%   |
| Broadcom                         | 116       | 3.01%   |
| ASIX Electronics                 | 36        | 0.94%   |
| Nvidia                           | 35        | 0.91%   |
| Samsung Electronics              | 29        | 0.75%   |
| Marvell Technology Group         | 26        | 0.68%   |
| Aquantia                         | 24        | 0.62%   |
| Lenovo                           | 21        | 0.55%   |
| DisplayLink                      | 21        | 0.55%   |
| Xiaomi                           | 18        | 0.47%   |
| Huawei Technologies              | 15        | 0.39%   |
| Broadcom Limited                 | 11        | 0.29%   |
| TP-Link                          | 8         | 0.21%   |
| JMicron Technology               | 8         | 0.21%   |
| Google                           | 7         | 0.18%   |
| Apple                            | 7         | 0.18%   |
| Qualcomm                         | 6         | 0.16%   |
| MediaTek                         | 6         | 0.16%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.1%    |
| VIA Technologies                 | 4         | 0.1%    |
| T & A Mobile Phones              | 3         | 0.08%   |
| Mellanox Technologies            | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| IBM                              | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| D-Link System                    | 2         | 0.05%   |
| American Megatrends              | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Solarflare Communications        | 1         | 0.03%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1636      | 41.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 208       | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 150       | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 147       | 3.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 144       | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 130       | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 75        | 1.9%    |
| Intel Ethernet Controller I225-V                                  | 67        | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 63        | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 45        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 32        | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 29        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 25        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 23        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 22        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.38%   |
| Intel Ethernet Connection (13) I219-V                             | 15        | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15        | 0.38%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3579      | 51.51%  |
| WiFi     | 3324      | 47.84%  |
| Modem    | 41        | 0.59%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2597      | 57.6%   |
| Ethernet | 1911      | 42.38%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2271      | 53.2%   |
| 1     | 1807      | 42.33%  |
| 3     | 101       | 2.37%   |
| 0     | 67        | 1.57%   |
| 4     | 17        | 0.4%    |
| 6     | 4         | 0.09%   |
| 5     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3438      | 79.51%  |
| Yes     | 885       | 20.47%  |
| Unknown | 1         | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1472      | 50.36%  |
| Realtek Semiconductor           | 302       | 10.33%  |
| Qualcomm Atheros Communications | 212       | 7.25%   |
| Cambridge Silicon Radio         | 195       | 6.67%   |
| Broadcom                        | 129       | 4.41%   |
| IMC Networks                    | 125       | 4.28%   |
| Lite-On Technology              | 90        | 3.08%   |
| Foxconn / Hon Hai               | 88        | 3.01%   |
| Apple                           | 59        | 2.02%   |
| ASUSTek Computer                | 51        | 1.74%   |
| Dell                            | 34        | 1.16%   |
| Realtek                         | 31        | 1.06%   |
| MediaTek                        | 21        | 0.72%   |
| Ralink                          | 19        | 0.65%   |
| Hewlett-Packard                 | 13        | 0.44%   |
| Toshiba                         | 12        | 0.41%   |
| TP-Link                         | 11        | 0.38%   |
| Foxconn International           | 8         | 0.27%   |
| Marvell Semiconductor           | 7         | 0.24%   |
| Ralink Technology               | 5         | 0.17%   |
| Dynex                           | 5         | 0.17%   |
| ISSC                            | 4         | 0.14%   |
| Edimax Technology               | 4         | 0.14%   |
| Alps Electric                   | 4         | 0.14%   |
| USI                             | 2         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| D-Link                          | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 473       | 16.16%  |
| Intel AX201 Bluetooth                               | 294       | 10.04%  |
| Intel AX200 Bluetooth                               | 239       | 8.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 205       | 7%      |
| Realtek Bluetooth Radio                             | 196       | 6.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 195       | 6.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 110       | 3.76%   |
| Intel Bluetooth Device                              | 93        | 3.18%   |
| Realtek  Bluetooth 4.2 Adapter                      | 79        | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 50        | 1.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 46        | 1.57%   |
| IMC Networks Bluetooth Radio                        | 45        | 1.54%   |
| Intel AX210 Bluetooth                               | 43        | 1.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 40        | 1.37%   |
| IMC Networks Wireless_Device                        | 38        | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 1.09%   |
| Realtek Bluetooth Radio                             | 31        | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.06%   |
| Lite-On Bluetooth Device                            | 30        | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 28        | 0.96%   |
| Apple Bluetooth Host Controller                     | 25        | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 0.79%   |
| MediaTek Wireless_Device                            | 21        | 0.72%   |
| Lite-On Wireless_Device                             | 21        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 0.72%   |
| IMC Networks Bluetooth Device                       | 20        | 0.68%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 18        | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 18        | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.55%   |
| ASUS ASUS USB-BT500                                 | 16        | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 15        | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.48%   |
| Broadcom HP Portable SoftSailing                    | 13        | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.41%   |
| TP-Link UB500 Adapter                               | 11        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2970      | 47.29%  |
| AMD                        | 1411      | 22.46%  |
| Nvidia                     | 1130      | 17.99%  |
| C-Media Electronics        | 117       | 1.86%   |
| Logitech                   | 47        | 0.75%   |
| GN Netcom                  | 42        | 0.67%   |
| Creative Labs              | 38        | 0.6%    |
| JMTek                      | 34        | 0.54%   |
| Realtek Semiconductor      | 32        | 0.51%   |
| Texas Instruments          | 27        | 0.43%   |
| ASUSTek Computer           | 23        | 0.37%   |
| Generalplus Technology     | 22        | 0.35%   |
| Corsair                    | 21        | 0.33%   |
| Creative Technology        | 20        | 0.32%   |
| Razer USA                  | 18        | 0.29%   |
| Lenovo                     | 18        | 0.29%   |
| Hewlett-Packard            | 18        | 0.29%   |
| Focusrite-Novation         | 17        | 0.27%   |
| Plantronics                | 16        | 0.25%   |
| SteelSeries ApS            | 14        | 0.22%   |
| Kingston Technology        | 13        | 0.21%   |
| VIA Technologies           | 11        | 0.18%   |
| Blue Microphones           | 9         | 0.14%   |
| Tenx Technology            | 8         | 0.13%   |
| Sony                       | 7         | 0.11%   |
| Micro Star International   | 7         | 0.11%   |
| Dell                       | 7         | 0.11%   |
| Sennheiser Communications  | 6         | 0.1%    |
| SAVITECH                   | 6         | 0.1%    |
| PreSonus Audio Electronics | 5         | 0.08%   |
| Yamaha                     | 4         | 0.06%   |
| Trust                      | 4         | 0.06%   |
| Nordic Semiconductor ASA   | 4         | 0.06%   |
| M-Audio                    | 4         | 0.06%   |
| GYROCOM C&C                | 4         | 0.06%   |
| BEHRINGER International    | 4         | 0.06%   |
| ZOOM                       | 3         | 0.05%   |
| TerraTec Electronic        | 3         | 0.05%   |
| TEAC                       | 3         | 0.05%   |
| Samson Technologies        | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 511       | 6.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 325       | 4.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 266       | 3.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 262       | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 235       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 230       | 3.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 214       | 2.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 211       | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 184       | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 174       | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 163       | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 139       | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 130       | 1.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 119       | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 115       | 1.53%   |
| AMD FCH Azalia Controller                                                  | 107       | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 103       | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 99        | 1.32%   |
| Intel 8 Series HD Audio Controller                                         | 98        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                               | 97        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 95        | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 86        | 1.14%   |
| Intel 200 Series PCH HD Audio                                              | 86        | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 83        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 81        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 80        | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 79        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 74        | 0.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 73        | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 71        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 71        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 66        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 65        | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 65        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 62        | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 57        | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 56        | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 54        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 53        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 53        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 692       | 21.8%   |
| SK hynix            | 507       | 15.97%  |
| Kingston            | 404       | 12.73%  |
| Micron Technology   | 331       | 10.43%  |
| Crucial             | 234       | 7.37%   |
| Unknown             | 203       | 6.4%    |
| Corsair             | 199       | 6.27%   |
| G.Skill             | 144       | 4.54%   |
| A-DATA Technology   | 64        | 2.02%   |
| Ramaxel Technology  | 52        | 1.64%   |
| Unknown (ABCD)      | 44        | 1.39%   |
| Nanya Technology    | 37        | 1.17%   |
| Elpida              | 33        | 1.04%   |
| Team                | 25        | 0.79%   |
| Patriot             | 21        | 0.66%   |
| Unknown             | 20        | 0.63%   |
| Transcend           | 17        | 0.54%   |
| Smart               | 17        | 0.54%   |
| GOODRAM             | 9         | 0.28%   |
| Silicon Power       | 8         | 0.25%   |
| AMD                 | 8         | 0.25%   |
| Apacer              | 7         | 0.22%   |
| Wilk                | 5         | 0.16%   |
| Teikon              | 5         | 0.16%   |
| Smart Brazil        | 5         | 0.16%   |
| Avant               | 5         | 0.16%   |
| ASint Technology    | 5         | 0.16%   |
| PNY                 | 4         | 0.13%   |
| SHARETRONIC         | 3         | 0.09%   |
| Goldkey             | 3         | 0.09%   |
| GeIL                | 3         | 0.09%   |
| CSX                 | 3         | 0.09%   |
| 4ea5                | 3         | 0.09%   |
| V-GeN               | 2         | 0.06%   |
| Unifosa             | 2         | 0.06%   |
| Reboto              | 2         | 0.06%   |
| Lexar               | 2         | 0.06%   |
| Kllisre             | 2         | 0.06%   |
| Kingmax             | 2         | 0.06%   |
| Imation             | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 35        | 1.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 28        | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 23        | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.59%   |
| Unknown                                                          | 20        | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 19        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.53%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 18        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 15        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 0.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 12        | 0.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.32%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 11        | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.29%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.29%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.29%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 10        | 0.29%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.29%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.29%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 10        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1538      | 56.61%  |
| DDR3    | 732       | 26.94%  |
| LPDDR4  | 126       | 4.64%   |
| Unknown | 65        | 2.39%   |
| DDR5    | 62        | 2.28%   |
| LPDDR3  | 60        | 2.21%   |
| DDR2    | 51        | 1.88%   |
| SDRAM   | 39        | 1.44%   |
| LPDDR5  | 32        | 1.18%   |
| DDR     | 10        | 0.37%   |
| DRAM    | 2         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1549      | 56.82%  |
| DIMM         | 920       | 33.75%  |
| Row Of Chips | 225       | 8.25%   |
| Chip         | 15        | 0.55%   |
| Unknown      | 12        | 0.44%   |
| FB-DIMM      | 3         | 0.11%   |
| RIMM         | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1291      | 43.41%  |
| 4096  | 719       | 24.18%  |
| 16384 | 573       | 19.27%  |
| 2048  | 235       | 7.9%    |
| 32768 | 121       | 4.07%   |
| 1024  | 31        | 1.04%   |
| 12288 | 1         | 0.03%   |
| 512   | 1         | 0.03%   |
| 256   | 1         | 0.03%   |
| 128   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 536       | 18.18%  |
| 2667    | 506       | 17.16%  |
| 1600    | 492       | 16.69%  |
| 2400    | 254       | 8.62%   |
| 1333    | 173       | 5.87%   |
| 2133    | 139       | 4.72%   |
| 3600    | 96        | 3.26%   |
| 1334    | 63        | 2.14%   |
| 4267    | 55        | 1.87%   |
| 1867    | 44        | 1.49%   |
| 4800    | 42        | 1.42%   |
| 800     | 35        | 1.19%   |
| 6400    | 33        | 1.12%   |
| 3266    | 32        | 1.09%   |
| 667     | 30        | 1.02%   |
| 2666    | 29        | 0.98%   |
| Unknown | 25        | 0.85%   |
| 3733    | 24        | 0.81%   |
| 3000    | 23        | 0.78%   |
| 3400    | 22        | 0.75%   |
| 2933    | 22        | 0.75%   |
| 3800    | 21        | 0.71%   |
| 1066    | 17        | 0.58%   |
| 1067    | 16        | 0.54%   |
| 8400    | 14        | 0.47%   |
| 1866    | 14        | 0.47%   |
| 1800    | 13        | 0.44%   |
| 3866    | 12        | 0.41%   |
| 2800    | 11        | 0.37%   |
| 4199    | 10        | 0.34%   |
| 3533    | 10        | 0.34%   |
| 4266    | 9         | 0.31%   |
| 3666    | 9         | 0.31%   |
| 400     | 9         | 0.31%   |
| 5600    | 8         | 0.27%   |
| 3466    | 7         | 0.24%   |
| 3333    | 7         | 0.24%   |
| 3066    | 7         | 0.24%   |
| 2048    | 6         | 0.2%    |
| 2000    | 6         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 48        | 37.5%   |
| Brother Industries     | 28        | 21.88%  |
| Seiko Epson            | 14        | 10.94%  |
| Samsung Electronics    | 11        | 8.59%   |
| Canon                  | 11        | 8.59%   |
| Xerox                  | 2         | 1.56%   |
| Prolific Technology    | 2         | 1.56%   |
| Pantum                 | 2         | 1.56%   |
| Dymo-CoStar            | 2         | 1.56%   |
| Zebra                  | 1         | 0.78%   |
| QinHeng Electronics    | 1         | 0.78%   |
| Panasonic (Matsushita) | 1         | 0.78%   |
| Kyocera                | 1         | 0.78%   |
| ICS Advent             | 1         | 0.78%   |
| Datamax-O'Neil         | 1         | 0.78%   |
| BESTEASY               | 1         | 0.78%   |
| Apple                  | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.31%   |
| Seiko Epson L360 Series                                | 2         | 1.54%   |
| Seiko Epson L3110 Series                               | 2         | 1.54%   |
| Samsung M2070 Series                                   | 2         | 1.54%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.54%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.54%   |
| HP LaserJet P2015 series                               | 2         | 1.54%   |
| HP LaserJet 1020                                       | 2         | 1.54%   |
| HP LaserJet 1018                                       | 2         | 1.54%   |
| HP ENVY 4500 series                                    | 2         | 1.54%   |
| HP DeskJet 2700 series                                 | 2         | 1.54%   |
| HP DeskJet 2600 series                                 | 2         | 1.54%   |
| Brother MFC-J460DW                                     | 2         | 1.54%   |
| Brother HL-L2320D series                               | 2         | 1.54%   |
| Brother HL-2230 series                                 | 2         | 1.54%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.77%   |
| Xerox Phaser 6500N                                     | 1         | 0.77%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.77%   |
| Seiko Epson XP-7100 Series                             | 1         | 0.77%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.77%   |
| Seiko Epson XP-2200 Series                             | 1         | 0.77%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.77%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.77%   |
| Seiko Epson Printer                                    | 1         | 0.77%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.77%   |
| Seiko Epson L120 Series                                | 1         | 0.77%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.77%   |
| Seiko Epson ET-2700 Series                             | 1         | 0.77%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.77%   |
| Samsung SCX-3200 Series                                | 1         | 0.77%   |
| Samsung ML-2250 Series                                 | 1         | 0.77%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.77%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.77%   |
| Samsung M2020 Series                                   | 1         | 0.77%   |
| Samsung CLX-3180 Series                                | 1         | 0.77%   |
| Samsung CLX-3170 Series                                | 1         | 0.77%   |
| Samsung CLP-360 Series                                 | 1         | 0.77%   |
| QinHeng CH340S                                         | 1         | 0.77%   |
| Pantum P2200W series                                   | 1         | 0.77%   |
| Pantum P2200 series                                    | 1         | 0.77%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 51.72%  |
| Seiko Epson     | 8         | 27.59%  |
| Mustek Systems  | 3         | 10.34%  |
| Hewlett-Packard | 3         | 10.34%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 10.34%  |
| Canon CanoScan N670U/N676U/LiDE 20                      | 3         | 10.34%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 6.9%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 6.9%    |
| Canon CanoScan LIDE 25                                  | 2         | 6.9%    |
| Canon CanoScan LiDE 220                                 | 2         | 6.9%    |
| Canon CanoScan LiDE 210                                 | 2         | 6.9%    |
| Canon CanoScan LiDE 110                                 | 2         | 6.9%    |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.45%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.45%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.45%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.45%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.45%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.45%   |
| HP ScanJet G4010                                        | 1         | 3.45%   |
| HP ScanJet 82x0C                                        | 1         | 3.45%   |
| HP ScanJet 3770                                         | 1         | 3.45%   |
| Canon CanoScan LiDE 60                                  | 1         | 3.45%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.45%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 522       | 18.43%  |
| IMC Networks                           | 282       | 9.95%   |
| Microdia                               | 259       | 9.14%   |
| Logitech                               | 213       | 7.52%   |
| Realtek Semiconductor                  | 212       | 7.48%   |
| Bison Electronics                      | 171       | 6.04%   |
| Quanta                                 | 155       | 5.47%   |
| Sunplus Innovation Technology          | 149       | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 112       | 3.95%   |
| Acer                                   | 67        | 2.36%   |
| Syntek                                 | 63        | 2.22%   |
| Apple                                  | 57        | 2.01%   |
| Suyin                                  | 49        | 1.73%   |
| Lite-On Technology                     | 47        | 1.66%   |
| Luxvisions Innotech Limited            | 46        | 1.62%   |
| Silicon Motion                         | 44        | 1.55%   |
| Microsoft                              | 37        | 1.31%   |
| Alcor Micro                            | 31        | 1.09%   |
| Samsung Electronics                    | 30        | 1.06%   |
| Sonix Technology                       | 18        | 0.64%   |
| Generalplus Technology                 | 18        | 0.64%   |
| Ricoh                                  | 17        | 0.6%    |
| Lenovo                                 | 14        | 0.49%   |
| Z-Star Microelectronics                | 13        | 0.46%   |
| SunplusIT                              | 11        | 0.39%   |
| KYE Systems (Mouse Systems)            | 9         | 0.32%   |
| ARC International                      | 9         | 0.32%   |
| Y Media                                | 8         | 0.28%   |
| MacroSilicon                           | 8         | 0.28%   |
| Genesys Logic                          | 8         | 0.28%   |
| Huawei Technologies                    | 7         | 0.25%   |
| GEMBIRD                                | 7         | 0.25%   |
| Cubeternet                             | 7         | 0.25%   |
| Sunplus Technology                     | 6         | 0.21%   |
| Importek                               | 6         | 0.21%   |
| icSpring                               | 6         | 0.21%   |
| Primax Electronics                     | 5         | 0.18%   |
| LG Electronics                         | 5         | 0.18%   |
| Creative Technology                    | 5         | 0.18%   |
| USB Camera CS                          | 4         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 125       | 4.38%   |
| Microdia Integrated_Webcam_HD                                              | 113       | 3.96%   |
| Realtek Integrated_Webcam_HD                                               | 87        | 3.05%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 87        | 3.05%   |
| IMC Networks Integrated Camera                                             | 85        | 2.98%   |
| Sunplus Integrated_Webcam_HD                                               | 60        | 2.1%    |
| Chicony HD Webcam                                                          | 48        | 1.68%   |
| Logitech HD Pro Webcam C920                                                | 47        | 1.65%   |
| Syntek Integrated Camera                                                   | 45        | 1.58%   |
| Bison Integrated Camera                                                    | 45        | 1.58%   |
| Logitech Webcam C270                                                       | 40        | 1.4%    |
| Chicony HP HD Camera                                                       | 33        | 1.16%   |
| Acer Integrated Camera                                                     | 32        | 1.12%   |
| Quanta HD User Facing                                                      | 31        | 1.09%   |
| Chicony USB2.0 Camera                                                      | 31        | 1.09%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 29        | 1.02%   |
| Chicony HD User Facing                                                     | 28        | 0.98%   |
| Bison HD Webcam                                                            | 26        | 0.91%   |
| Microdia Integrated Webcam                                                 | 23        | 0.81%   |
| Microdia Webcam Vitade AF                                                  | 22        | 0.77%   |
| Quanta HP TrueVision HD Camera                                             | 21        | 0.74%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 20        | 0.7%    |
| Quanta HP HD Camera                                                        | 19        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                                    | 19        | 0.67%   |
| Lite-On Integrated Camera                                                  | 18        | 0.63%   |
| Bison Lenovo EasyCamera                                                    | 18        | 0.63%   |
| Microdia Integrated_Webcam_FHD                                             | 17        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 17        | 0.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 16        | 0.56%   |
| Chicony HP Truevision HD camera                                            | 16        | 0.56%   |
| Chicony HP TrueVision HD                                                   | 16        | 0.56%   |
| Alcor Micro USB 2.0 Camera                                                 | 16        | 0.56%   |
| Microsoft LifeCam HD-3000                                                  | 15        | 0.53%   |
| Logitech C922 Pro Stream Webcam                                            | 15        | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 15        | 0.53%   |
| Realtek Integrated Webcam                                                  | 14        | 0.49%   |
| Quanta HP Wide Vision HD Camera                                            | 14        | 0.49%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 14        | 0.49%   |
| Bison BisonCam,NB Pro                                                      | 14        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 192       | 33.45%  |
| Validity Sensors                   | 147       | 25.61%  |
| Shenzhen Goodix Technology         | 113       | 19.69%  |
| Elan Microelectronics              | 40        | 6.97%   |
| AuthenTec                          | 23        | 4.01%   |
| Upek                               | 22        | 3.83%   |
| LighTuning Technology              | 22        | 3.83%   |
| STMicroelectronics                 | 6         | 1.05%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.7%    |
| Focal-systems.Corp                 | 2         | 0.35%   |
| Samsung Electronics                | 1         | 0.17%   |
| FocalTech                          | 1         | 0.17%   |
| DigitalPersona                     | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 65        | 11.32%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 60        | 10.45%  |
| Shenzhen Goodix Fingerprint Reader                                         | 31        | 5.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 4.7%    |
| Elan ELAN:Fingerprint                                                      | 23        | 4.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 3.83%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.66%   |
| Synaptics UWP WBDI                                                         | 19        | 3.31%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.96%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 2.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 2.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 2.61%   |
| Elan ELAN:ARM-M4                                                           | 15        | 2.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 2.44%   |
| Synaptics WBDI                                                             | 13        | 2.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.09%   |
| Synaptics  WBDI                                                            | 12        | 2.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.74%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 1.74%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.57%   |
| Validity Sensors VFS491                                                    | 8         | 1.39%   |
| AuthenTec AES2810                                                          | 8         | 1.39%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.22%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.22%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.05%   |
| Synaptics TouchPad                                                         | 6         | 1.05%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.05%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.87%   |
| Unknown                                                                    | 5         | 0.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.7%    |
| Synaptics UWP WBDI Device                                                  | 4         | 0.7%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.7%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.7%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 105       | 42.51%  |
| Alcor Micro               | 73        | 29.55%  |
| Upek                      | 14        | 5.67%   |
| O2 Micro                  | 9         | 3.64%   |
| Lenovo                    | 8         | 3.24%   |
| Advanced Card Systems     | 7         | 2.83%   |
| SCM Microsystems          | 4         | 1.62%   |
| Yubico.com                | 3         | 1.21%   |
| OmniKey                   | 3         | 1.21%   |
| Gemalto (was Gemplus)     | 3         | 1.21%   |
| Reiner SCT Kartensysteme  | 2         | 0.81%   |
| Realtek Semiconductor     | 2         | 0.81%   |
| Fujitsu Siemens Computers | 2         | 0.81%   |
| Clay Logic                | 2         | 0.81%   |
| Bit4id                    | 2         | 0.81%   |
| Aladdin R.D.              | 2         | 0.81%   |
| Watchdata                 | 1         | 0.4%    |
| In Focus Systems          | 1         | 0.4%    |
| Giesecke & Devrient       | 1         | 0.4%    |
| Chicony Electronics       | 1         | 0.4%    |
| Aladdin Knowledge Systems | 1         | 0.4%    |
| Aktiv                     | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 28.74%  |
| Broadcom 5880                                                                | 32        | 12.96%  |
| Broadcom 58200                                                               | 28        | 11.34%  |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 10.93%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 6.48%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 5.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 3.64%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.24%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.62%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.21%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.21%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.81%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.81%   |
| OmniKey CardMan 1021                                                         | 2         | 0.81%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.81%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.81%   |
| Bit4id miniLector EVO                                                        | 2         | 0.81%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.81%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.81%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.81%   |
| Watchdata USB Key                                                            | 1         | 0.4%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.4%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.4%    |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.4%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.4%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.4%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.4%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.4%    |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.4%    |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.4%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.4%    |
| Aktiv Rutoken lite                                                           | 1         | 0.4%    |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2968      | 68.25%  |
| 1     | 1117      | 25.68%  |
| 2     | 219       | 5.04%   |
| 3     | 24        | 0.55%   |
| 4     | 9         | 0.21%   |
| 7     | 4         | 0.09%   |
| 6     | 4         | 0.09%   |
| 5     | 3         | 0.07%   |
| 9     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 565       | 34.26%  |
| Graphics card            | 270       | 16.37%  |
| Chipcard                 | 213       | 12.92%  |
| Net/wireless             | 195       | 11.83%  |
| Camera                   | 78        | 4.73%   |
| Multimedia controller    | 76        | 4.61%   |
| Bluetooth                | 48        | 2.91%   |
| Sound                    | 45        | 2.73%   |
| Communication controller | 39        | 2.37%   |
| Unassigned class         | 38        | 2.3%    |
| Card reader              | 22        | 1.33%   |
| Storage                  | 20        | 1.21%   |
| Net/ethernet             | 11        | 0.67%   |
| Network                  | 8         | 0.49%   |
| Modem                    | 7         | 0.42%   |
| Storage/ide              | 6         | 0.36%   |
| Firewire controller      | 4         | 0.24%   |
| Dvb card                 | 3         | 0.18%   |
| Storage/raid             | 1         | 0.06%   |

