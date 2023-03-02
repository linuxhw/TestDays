Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 439

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-56-generic     | 43        | 11.53%  |
| 5.15.0-52-generic     | 35        | 9.38%   |
| 5.15.0-47-generic     | 31        | 8.31%   |
| 5.15.0-58-generic     | 27        | 7.24%   |
| 5.15.0-48-generic     | 25        | 6.7%    |
| 5.15.0-25-generic     | 20        | 5.36%   |
| 5.15.0-60-generic     | 19        | 5.09%   |
| 5.15.0-46-generic     | 17        | 4.56%   |
| 5.15.0-53-generic     | 14        | 3.75%   |
| 5.15.0-27-generic     | 14        | 3.75%   |
| 5.15.0-57-generic     | 9         | 2.41%   |
| 5.15.0-50-generic     | 9         | 2.41%   |
| 5.15.0-43-generic     | 9         | 2.41%   |
| 5.15.0-41-generic     | 9         | 2.41%   |
| 5.15.0-40-generic     | 9         | 2.41%   |
| 5.15.0-39-generic     | 6         | 1.61%   |
| 5.15.0-37-generic     | 5         | 1.34%   |
| 5.15.0-35-generic     | 5         | 1.34%   |
| 5.15.0-33-generic     | 4         | 1.07%   |
| 5.15.0-30-generic     | 4         | 1.07%   |
| 6.1.0-1006-oem        | 2         | 0.54%   |
| 5.19.0-32-generic     | 2         | 0.54%   |
| 5.17.0-1020-oem       | 2         | 0.54%   |
| 5.17.0-1013-oem       | 2         | 0.54%   |
| 5.15.0-60-lowlatency  | 2         | 0.54%   |
| 5.15.0-54-generic     | 2         | 0.54%   |
| 5.15.0-50-lowlatency  | 2         | 0.54%   |
| 5.15.0-48-lowlatency  | 2         | 0.54%   |
| 5.15.0-46-lowlatency  | 2         | 0.54%   |
| 6.1.6-060106-generic  | 1         | 0.27%   |
| 6.1.10.mmn            | 1         | 0.27%   |
| 6.1.0                 | 1         | 0.27%   |
| 6.0.9-060009-generic  | 1         | 0.27%   |
| 6.0.7-x64v3-xanmod1   | 1         | 0.27%   |
| 6.0.0-1007-oem        | 1         | 0.27%   |
| 6.0.0                 | 1         | 0.27%   |
| 5.4.0-126-generic     | 1         | 0.27%   |
| 5.4.0-122-generic     | 1         | 0.27%   |
| 5.19.5-051905-generic | 1         | 0.27%   |
| 5.19.13-xanmod1       | 1         | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 313       | 88.17%  |
| 5.17.0   | 9         | 2.54%   |
| 5.19.0   | 6         | 1.69%   |
| 6.1.0    | 3         | 0.85%   |
| 6.0.0    | 2         | 0.56%   |
| 5.4.0    | 2         | 0.56%   |
| 5.18.0   | 2         | 0.56%   |
| 6.1.6    | 1         | 0.28%   |
| 6.1.10   | 1         | 0.28%   |
| 6.0.9    | 1         | 0.28%   |
| 6.0.7    | 1         | 0.28%   |
| 5.19.5   | 1         | 0.28%   |
| 5.19.13  | 1         | 0.28%   |
| 5.19.1   | 1         | 0.28%   |
| 5.18.12  | 1         | 0.28%   |
| 5.17.3   | 1         | 0.28%   |
| 5.16.9   | 1         | 0.28%   |
| 5.15.74  | 1         | 0.28%   |
| 5.15.68  | 1         | 0.28%   |
| 5.15.61  | 1         | 0.28%   |
| 5.15.59  | 1         | 0.28%   |
| 5.15.48  | 1         | 0.28%   |
| 5.15.23  | 1         | 0.28%   |
| 5.10.110 | 1         | 0.28%   |
| 4.19.241 | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 319       | 89.86%  |
| 5.17    | 10        | 2.82%   |
| 5.19    | 9         | 2.54%   |
| 6.1     | 5         | 1.41%   |
| 6.0     | 4         | 1.13%   |
| 5.18    | 3         | 0.85%   |
| 5.4     | 2         | 0.56%   |
| 5.16    | 1         | 0.28%   |
| 5.10    | 1         | 0.28%   |
| 4.19    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 345       | 98.01%  |
| aarch64 | 5         | 1.42%   |
| armv7l  | 2         | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 339       | 96.31%  |
| GNOME           | 11        | 3.13%   |
| i3              | 1         | 0.28%   |
| GNOME Flashback | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 340       | 96.05%  |
| Tty     | 9         | 2.54%   |
| Wayland | 5         | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 308       | 87.5%   |
| GDM3    | 21        | 5.97%   |
| Unknown | 19        | 5.4%    |
| SDDM    | 2         | 0.57%   |
| SLiM    | 1         | 0.28%   |
| GDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 135       | 38.35%  |
| de_DE | 47        | 13.35%  |
| fr_FR | 42        | 11.93%  |
| it_IT | 25        | 7.1%    |
| ru_RU | 13        | 3.69%   |
| pt_BR | 11        | 3.13%   |
| en_GB | 11        | 3.13%   |
| en_CA | 8         | 2.27%   |
| es_ES | 6         | 1.7%    |
| cs_CZ | 6         | 1.7%    |
| en_AU | 5         | 1.42%   |
| nl_NL | 4         | 1.14%   |
| hu_HU | 3         | 0.85%   |
| en_IN | 3         | 0.85%   |
| C     | 3         | 0.85%   |
| tr_TR | 2         | 0.57%   |
| ru_UA | 2         | 0.57%   |
| ja_JP | 2         | 0.57%   |
| es_VE | 2         | 0.57%   |
| es_CO | 2         | 0.57%   |
| es_AR | 2         | 0.57%   |
| sv_SE | 1         | 0.28%   |
| ro_RO | 1         | 0.28%   |
| pt_PT | 1         | 0.28%   |
| pl_PL | 1         | 0.28%   |
| nl_BE | 1         | 0.28%   |
| ko_KR | 1         | 0.28%   |
| fr_CH | 1         | 0.28%   |
| fr_CA | 1         | 0.28%   |
| fr_BE | 1         | 0.28%   |
| fi_FI | 1         | 0.28%   |
| es_MX | 1         | 0.28%   |
| es_CL | 1         | 0.28%   |
| en_ZA | 1         | 0.28%   |
| en_IL | 1         | 0.28%   |
| en_IE | 1         | 0.28%   |
| el_GR | 1         | 0.28%   |
| de_CH | 1         | 0.28%   |
| bg_BG | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 186       | 52.39%  |
| BIOS | 169       | 47.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 319       | 90.63%  |
| Overlay | 14        | 3.98%   |
| Btrfs   | 10        | 2.84%   |
| Zfs     | 8         | 2.27%   |
| Ext3    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 246       | 67.96%  |
| Unknown | 66        | 18.23%  |
| MBR     | 50        | 13.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 309       | 87.04%  |
| Yes       | 46        | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 240       | 67.99%  |
| Yes       | 113       | 32.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 57        | 16.19%  |
| Lenovo                  | 55        | 15.63%  |
| Hewlett-Packard         | 53        | 15.06%  |
| Dell                    | 38        | 10.8%   |
| Acer                    | 24        | 6.82%   |
| MSI                     | 21        | 5.97%   |
| Gigabyte Technology     | 21        | 5.97%   |
| ASRock                  | 7         | 1.99%   |
| Google                  | 6         | 1.7%    |
| Apple                   | 5         | 1.42%   |
| Toshiba                 | 4         | 1.14%   |
| Supermicro              | 4         | 1.14%   |
| Sony                    | 4         | 1.14%   |
| Intel                   | 4         | 1.14%   |
| Rockchip                | 3         | 0.85%   |
| HUAWEI                  | 3         | 0.85%   |
| GPU Company             | 3         | 0.85%   |
| Unknown                 | 3         | 0.85%   |
| sunxi                   | 2         | 0.57%   |
| Samsung Electronics     | 2         | 0.57%   |
| PCWare                  | 2         | 0.57%   |
| Packard Bell            | 2         | 0.57%   |
| Notebook                | 2         | 0.57%   |
| HONOR                   | 2         | 0.57%   |
| VIT                     | 1         | 0.28%   |
| Tactus                  | 1         | 0.28%   |
| Standard                | 1         | 0.28%   |
| Schenker                | 1         | 0.28%   |
| Raspberry Pi Foundation | 1         | 0.28%   |
| Pine Microsystems       | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |
| MiPi PC                 | 1         | 0.28%   |
| Microsoft               | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| Mediacom                | 1         | 0.28%   |
| MACHINIST               | 1         | 0.28%   |
| LG Electronics          | 1         | 0.28%   |
| Itautec                 | 1         | 0.28%   |
| HIGRADED                | 1         | 0.28%   |
| Hardkernel              | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                                                      | 4         | 1.14%   |
| ASUS All Series                                                                          | 4         | 1.14%   |
| Unknown                                                                                  | 4         | 1.14%   |
| MSI MS-7D43                                                                              | 3         | 0.85%   |
| Dell OptiPlex 7010                                                                       | 3         | 0.85%   |
| Rockchip RK3318 BOX                                                                      | 2         | 0.57%   |
| MSI MS-7D46                                                                              | 2         | 0.57%   |
| MSI MS-7D25                                                                              | 2         | 0.57%   |
| MSI MS-7C52                                                                              | 2         | 0.57%   |
| HP Pavilion Notebook                                                                     | 2         | 0.57%   |
| HP Pavilion 15                                                                           | 2         | 0.57%   |
| HP 255 G8 Notebook PC                                                                    | 2         | 0.57%   |
| GPU Company GWTN116-3                                                                    | 2         | 0.57%   |
| Dell Latitude E5450                                                                      | 2         | 0.57%   |
| Dell Latitude 7420                                                                       | 2         | 0.57%   |
| ASUS K30AD_M31AD_M51AD                                                                   | 2         | 0.57%   |
| Acer Switch SW312-31                                                                     | 2         | 0.57%   |
| VIT Aptio CRB                                                                            | 1         | 0.28%   |
| Toshiba Satellite Pro R50-C                                                              | 1         | 0.28%   |
| Toshiba Satellite Pro R50-B                                                              | 1         | 0.28%   |
| Toshiba Satellite C650                                                                   | 1         | 0.28%   |
| Toshiba PT10F                                                                            | 1         | 0.28%   |
| Tactus GeoBook 140                                                                       | 1         | 0.28%   |
| Supermicro X10SRA                                                                        | 1         | 0.28%   |
| Supermicro Super Server                                                                  | 1         | 0.28%   |
| Supermicro M12SWA-TF                                                                     | 1         | 0.28%   |
| Supermicro AS -5014A-TT                                                                  | 1         | 0.28%   |
| sunxi LeMaker Banana Pi                                                                  | 1         | 0.28%   |
| sunxi Allwinner sun7i (A20) Family                                                       | 1         | 0.28%   |
| Sony VPCS12V9E                                                                           | 1         | 0.28%   |
| Sony VPCEH25EN                                                                           | 1         | 0.28%   |
| Sony VPCEA3S1E                                                                           | 1         | 0.28%   |
| Sony SVE1512C6EB                                                                         | 1         | 0.28%   |
| Schenker WORK (Early 2021)                                                               | 1         | 0.28%   |
| Samsung 370E4K                                                                           | 1         | 0.28%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.28%   |
| Rockchip Orange Pi 5                                                                     | 1         | 0.28%   |
| RPi Raspberry Pi 4 Model B Rev 1.5                                                       | 1         | 0.28%   |
| Pine Microsystems Pine64 Rock64                                                          | 1         | 0.28%   |
| PCWare IPX1800E2                                                                         | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 27        | 7.67%   |
| Acer Aspire           | 15        | 4.26%   |
| HP Pavilion           | 14        | 3.98%   |
| Dell Latitude         | 12        | 3.41%   |
| HP EliteBook          | 8         | 2.27%   |
| Dell OptiPlex         | 8         | 2.27%   |
| ASUS PRIME            | 8         | 2.27%   |
| Lenovo IdeaPad        | 7         | 1.99%   |
| Dell Inspiron         | 7         | 1.99%   |
| HP Compaq             | 6         | 1.7%    |
| Lenovo ThinkCentre    | 5         | 1.42%   |
| HP Laptop             | 4         | 1.14%   |
| ASUS VivoBook         | 4         | 1.14%   |
| ASUS All              | 4         | 1.14%   |
| Unknown               | 4         | 1.14%   |
| Toshiba Satellite     | 3         | 0.85%   |
| MSI MS-7D43           | 3         | 0.85%   |
| HP EliteDesk          | 3         | 0.85%   |
| HP 255                | 3         | 0.85%   |
| Dell Precision        | 3         | 0.85%   |
| Dell PowerEdge        | 3         | 0.85%   |
| ASUS TUF              | 3         | 0.85%   |
| ASUS ROG              | 3         | 0.85%   |
| Acer Veriton          | 3         | 0.85%   |
| Rockchip RK3318       | 2         | 0.57%   |
| MSI MS-7D46           | 2         | 0.57%   |
| MSI MS-7D25           | 2         | 0.57%   |
| MSI MS-7C52           | 2         | 0.57%   |
| Lenovo Yoga           | 2         | 0.57%   |
| Lenovo ThinkBook      | 2         | 0.57%   |
| HP Stream             | 2         | 0.57%   |
| HP ProBook            | 2         | 0.57%   |
| HP 250                | 2         | 0.57%   |
| GPU Company GWTN116-3 | 2         | 0.57%   |
| Gigabyte B550         | 2         | 0.57%   |
| Dell XPS              | 2         | 0.57%   |
| ASUS ZenBook          | 2         | 0.57%   |
| ASUS P8H61-M          | 2         | 0.57%   |
| ASUS K30AD            | 2         | 0.57%   |
| ASUS ASUS             | 2         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 36        | 10.23%  |
| 2020    | 32        | 9.09%   |
| 2014    | 29        | 8.24%   |
| 2017    | 27        | 7.67%   |
| 2018    | 26        | 7.39%   |
| 2012    | 23        | 6.53%   |
| 2016    | 22        | 6.25%   |
| 2015    | 21        | 5.97%   |
| 2013    | 21        | 5.97%   |
| 2011    | 20        | 5.68%   |
| 2019    | 19        | 5.4%    |
| 2010    | 18        | 5.11%   |
| 2022    | 17        | 4.83%   |
| 2009    | 11        | 3.13%   |
| 2007    | 11        | 3.13%   |
| 2008    | 8         | 2.27%   |
| Unknown | 7         | 1.99%   |
| 2006    | 2         | 0.57%   |
| 2005    | 2         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 196       | 55.68%  |
| Desktop        | 122       | 34.66%  |
| Server         | 8         | 2.27%   |
| System on chip | 7         | 1.99%   |
| Convertible    | 6         | 1.7%    |
| All in one     | 5         | 1.42%   |
| Tablet         | 4         | 1.14%   |
| Mini pc        | 4         | 1.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 322       | 91.48%  |
| Enabled  | 30        | 8.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 346       | 98.3%   |
| Yes  | 6         | 1.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 93        | 26.35%  |
| 3.01-4.0        | 88        | 24.93%  |
| 16.01-24.0      | 64        | 18.13%  |
| 8.01-16.0       | 43        | 12.18%  |
| 32.01-64.0      | 26        | 7.37%   |
| 1.01-2.0        | 19        | 5.38%   |
| 24.01-32.0      | 7         | 1.98%   |
| 64.01-256.0     | 6         | 1.7%    |
| 2.01-3.0        | 3         | 0.85%   |
| 0.51-1.0        | 3         | 0.85%   |
| More than 256.0 | 1         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 160       | 43.6%   |
| 2.01-3.0  | 95        | 25.89%  |
| 3.01-4.0  | 35        | 9.54%   |
| 4.01-8.0  | 34        | 9.26%   |
| 0.51-1.0  | 26        | 7.08%   |
| 8.01-16.0 | 14        | 3.81%   |
| 0.01-0.5  | 3         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 215       | 60.56%  |
| 2      | 87        | 24.51%  |
| 3      | 25        | 7.04%   |
| 4      | 15        | 4.23%   |
| 5      | 5         | 1.41%   |
| 6      | 3         | 0.85%   |
| 7      | 2         | 0.56%   |
| 10     | 1         | 0.28%   |
| 9      | 1         | 0.28%   |
| 0      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 58.36%  |
| Yes       | 147       | 41.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 296       | 84.09%  |
| No        | 56        | 15.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 255       | 72.44%  |
| No        | 97        | 27.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 56.82%  |
| No        | 152       | 43.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 56        | 15.82%  |
| USA          | 49        | 13.84%  |
| France       | 45        | 12.71%  |
| Italy        | 29        | 8.19%   |
| Russia       | 16        | 4.52%   |
| Brazil       | 13        | 3.67%   |
| UK           | 11        | 3.11%   |
| Netherlands  | 9         | 2.54%   |
| Canada       | 9         | 2.54%   |
| Sweden       | 8         | 2.26%   |
| Czechia      | 8         | 2.26%   |
| Poland       | 6         | 1.69%   |
| Mexico       | 6         | 1.69%   |
| India        | 6         | 1.69%   |
| Belgium      | 5         | 1.41%   |
| Australia    | 5         | 1.41%   |
| Spain        | 4         | 1.13%   |
| Iran         | 4         | 1.13%   |
| Belarus      | 4         | 1.13%   |
| Argentina    | 4         | 1.13%   |
| Venezuela    | 3         | 0.85%   |
| Turkey       | 3         | 0.85%   |
| Switzerland  | 3         | 0.85%   |
| Portugal     | 3         | 0.85%   |
| Malaysia     | 3         | 0.85%   |
| Indonesia    | 3         | 0.85%   |
| Hungary      | 3         | 0.85%   |
| Greece       | 3         | 0.85%   |
| Colombia     | 3         | 0.85%   |
| Taiwan       | 2         | 0.56%   |
| Slovenia     | 2         | 0.56%   |
| Romania      | 2         | 0.56%   |
| Japan        | 2         | 0.56%   |
| Israel       | 2         | 0.56%   |
| Finland      | 2         | 0.56%   |
| Austria      | 2         | 0.56%   |
| Vietnam      | 1         | 0.28%   |
| Ukraine      | 1         | 0.28%   |
| South Korea  | 1         | 0.28%   |
| South Africa | 1         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 9         | 2.47%   |
| Berlin           | 6         | 1.64%   |
| Munich           | 5         | 1.37%   |
| Milan            | 5         | 1.37%   |
| Melbourne        | 5         | 1.37%   |
| Stuttgart        | 4         | 1.1%    |
| Uppsala          | 3         | 0.82%   |
| Moscow           | 3         | 0.82%   |
| Kuala Lumpur     | 3         | 0.82%   |
| Biella           | 3         | 0.82%   |
| Ankara           | 3         | 0.82%   |
| Witten           | 2         | 0.55%   |
| Washington       | 2         | 0.55%   |
| Warsaw           | 2         | 0.55%   |
| Västerås       | 2         | 0.55%   |
| Tehran           | 2         | 0.55%   |
| St Petersburg    | 2         | 0.55%   |
| Rochester        | 2         | 0.55%   |
| Pilsen           | 2         | 0.55%   |
| Oklahoma City    | 2         | 0.55%   |
| Mumbai           | 2         | 0.55%   |
| Minsk            | 2         | 0.55%   |
| Mexico City      | 2         | 0.55%   |
| Leipzig          | 2         | 0.55%   |
| Lavras           | 2         | 0.55%   |
| Kazan’         | 2         | 0.55%   |
| Jakarta          | 2         | 0.55%   |
| Indianapolis     | 2         | 0.55%   |
| Helsinki         | 2         | 0.55%   |
| Hanover          | 2         | 0.55%   |
| Hamburg          | 2         | 0.55%   |
| Farmington       | 2         | 0.55%   |
| Clermont-Ferrand | 2         | 0.55%   |
| Caracas          | 2         | 0.55%   |
| Budapest         | 2         | 0.55%   |
| Bucharest        | 2         | 0.55%   |
| Brest            | 2         | 0.55%   |
| Bellevue         | 2         | 0.55%   |
| Belfort          | 2         | 0.55%   |
| Auxerre          | 2         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 76        | 94     | 14.81%  |
| WDC                         | 75        | 103    | 14.62%  |
| Seagate                     | 61        | 79     | 11.89%  |
| Unknown                     | 35        | 40     | 6.82%   |
| Kingston                    | 28        | 35     | 5.46%   |
| Toshiba                     | 26        | 27     | 5.07%   |
| SanDisk                     | 26        | 30     | 5.07%   |
| Hitachi                     | 22        | 31     | 4.29%   |
| SK hynix                    | 18        | 20     | 3.51%   |
| Crucial                     | 15        | 20     | 2.92%   |
| Intel                       | 13        | 13     | 2.53%   |
| HGST                        | 10        | 14     | 1.95%   |
| PNY                         | 9         | 9      | 1.75%   |
| A-DATA Technology           | 9         | 12     | 1.75%   |
| China                       | 7         | 8      | 1.36%   |
| Unknown                     | 6         | 6      | 1.17%   |
| Phison                      | 5         | 12     | 0.97%   |
| Patriot                     | 4         | 4      | 0.78%   |
| Micron Technology           | 4         | 4      | 0.78%   |
| Transcend                   | 3         | 4      | 0.58%   |
| Silicon Motion              | 3         | 3      | 0.58%   |
| Intenso                     | 3         | 3      | 0.58%   |
| USB3.0                      | 2         | 4      | 0.39%   |
| TO Exter                    | 2         | 2      | 0.39%   |
| TEXTORM                     | 2         | 2      | 0.39%   |
| OCZ                         | 2         | 2      | 0.39%   |
| Maxtor                      | 2         | 2      | 0.39%   |
| LITEON                      | 2         | 2      | 0.39%   |
| KIOXIA                      | 2         | 2      | 0.39%   |
| Kingston Technology Company | 2         | 3      | 0.39%   |
| Gigabyte Technology         | 2         | 2      | 0.39%   |
| ASMT                        | 2         | 5      | 0.39%   |
| Apacer                      | 2         | 2      | 0.39%   |
| XPG                         | 1         | 1      | 0.19%   |
| Veno                        | 1         | 1      | 0.19%   |
| Vaseky                      | 1         | 1      | 0.19%   |
| SSSTC                       | 1         | 1      | 0.19%   |
| SSK                         | 1         | 1      | 0.19%   |
| SSD0240S                    | 1         | 1      | 0.19%   |
| SPCC                        | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 7         | 1.24%   |
| Kingston SA400S37240G 240GB SSD        | 7         | 1.24%   |
| Samsung SSD 850 EVO 500GB              | 6         | 1.06%   |
| Crucial CT480BX500SSD1 480GB           | 6         | 1.06%   |
| Unknown                                | 6         | 1.06%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.88%   |
| Unknown MMC Card  32GB                 | 4         | 0.71%   |
| Seagate ST500DM002-1BD142 500GB        | 4         | 0.71%   |
| Unknown SD/MMC/MS PRO 16GB             | 3         | 0.53%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 0.53%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.53%   |
| Toshiba HDWD110 1TB                    | 3         | 0.53%   |
| Toshiba DT01ACA200 2TB                 | 3         | 0.53%   |
| Seagate ST500LT012-1DG142 500GB        | 3         | 0.53%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 3         | 0.53%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.53%   |
| SanDisk DF4064  64GB                   | 3         | 0.53%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.53%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.53%   |
| PNY CS900 120GB SSD                    | 3         | 0.53%   |
| Hitachi HDS721050CLA362 500GB          | 3         | 0.53%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.35%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 0.35%   |
| WDC WD10EZEX-00BBHA0 1TB               | 2         | 0.35%   |
| WDC PC SN530 SDBPNPZ-512G-1036 512GB   | 2         | 0.35%   |
| Unknown SA08G  8GB                     | 2         | 0.35%   |
| Unknown NCard  32GB                    | 2         | 0.35%   |
| Unknown MMC64G  64GB                   | 2         | 0.35%   |
| Toshiba DT01ACA100 1TB                 | 2         | 0.35%   |
| Toshiba DT01ACA050 500GB               | 2         | 0.35%   |
| TO Exter nal USB 3.0 240GB             | 2         | 0.35%   |
| TEXTORM BM5 240GB SSD                  | 2         | 0.35%   |
| SK hynix NVMe SSD Drive 1024GB         | 2         | 0.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 2         | 0.35%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.35%   |
| Seagate ST4000VX007-2DT166 4TB         | 2         | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB         | 2         | 0.35%   |
| Seagate ST31000528AS 1TB               | 2         | 0.35%   |
| Seagate ST3000DM008-2DM166 3TB         | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 61        | 87     | 30.81%  |
| Seagate             | 61        | 78     | 30.81%  |
| Toshiba             | 22        | 23     | 11.11%  |
| Hitachi             | 22        | 31     | 11.11%  |
| HGST                | 10        | 14     | 5.05%   |
| Samsung Electronics | 9         | 13     | 4.55%   |
| Unknown             | 3         | 4      | 1.52%   |
| USB3.0              | 2         | 4      | 1.01%   |
| ASMT                | 2         | 5      | 1.01%   |
| PHD 3.0             | 1         | 1      | 0.51%   |
| Maxtor              | 1         | 1      | 0.51%   |
| LaCie               | 1         | 1      | 0.51%   |
| JMicron Technology  | 1         | 1      | 0.51%   |
| Fujitsu             | 1         | 1      | 0.51%   |
| ASMedia             | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 48     | 23.26%  |
| Kingston            | 24        | 28     | 13.95%  |
| SanDisk             | 15        | 17     | 8.72%   |
| Crucial             | 14        | 19     | 8.14%   |
| A-DATA Technology   | 9         | 12     | 5.23%   |
| PNY                 | 8         | 8      | 4.65%   |
| WDC                 | 7         | 7      | 4.07%   |
| China               | 7         | 8      | 4.07%   |
| Intel               | 5         | 5      | 2.91%   |
| Patriot             | 4         | 4      | 2.33%   |
| Transcend           | 3         | 3      | 1.74%   |
| Toshiba             | 3         | 3      | 1.74%   |
| Intenso             | 3         | 3      | 1.74%   |
| TO Exter            | 2         | 2      | 1.16%   |
| TEXTORM             | 2         | 2      | 1.16%   |
| SK hynix            | 2         | 2      | 1.16%   |
| OCZ                 | 2         | 2      | 1.16%   |
| Micron Technology   | 2         | 2      | 1.16%   |
| LITEON              | 2         | 2      | 1.16%   |
| Apacer              | 2         | 2      | 1.16%   |
| Veno                | 1         | 1      | 0.58%   |
| Vaseky              | 1         | 1      | 0.58%   |
| SSSTC               | 1         | 1      | 0.58%   |
| SPCC                | 1         | 1      | 0.58%   |
| Netac               | 1         | 1      | 0.58%   |
| Maxtor              | 1         | 1      | 0.58%   |
| LITEONIT            | 1         | 1      | 0.58%   |
| Linux               | 1         | 1      | 0.58%   |
| KingFast            | 1         | 1      | 0.58%   |
| KingDian            | 1         | 1      | 0.58%   |
| Kimtigo             | 1         | 1      | 0.58%   |
| INNOVATION IT       | 1         | 1      | 0.58%   |
| FORESEE             | 1         | 1      | 0.58%   |
| EVM                 | 1         | 1      | 0.58%   |
| addlink             | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 159       | 265    | 35.02%  |
| SSD     | 151       | 195    | 33.26%  |
| NVMe    | 96        | 122    | 21.15%  |
| MMC     | 42        | 48     | 9.25%   |
| Unknown | 6         | 6      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 256       | 432    | 61.54%  |
| NVMe | 96        | 122    | 23.08%  |
| MMC  | 42        | 48     | 10.1%   |
| SAS  | 22        | 34     | 5.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 204       | 295    | 60.9%   |
| 0.51-1.0   | 83        | 101    | 24.78%  |
| 1.01-2.0   | 22        | 26     | 6.57%   |
| 3.01-4.0   | 16        | 25     | 4.78%   |
| 2.01-3.0   | 6         | 7      | 1.79%   |
| 10.01-20.0 | 2         | 3      | 0.6%    |
| 4.01-10.0  | 2         | 3      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 28.29%  |
| 251-500        | 83        | 23.25%  |
| 501-1000       | 51        | 14.29%  |
| 51-100         | 28        | 7.84%   |
| 1001-2000      | 26        | 7.28%   |
| 1-20           | 23        | 6.44%   |
| 21-50          | 18        | 5.04%   |
| More than 3000 | 16        | 4.48%   |
| 2001-3000      | 10        | 2.8%    |
| Unknown        | 1         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 34.07%  |
| 21-50          | 73        | 20.22%  |
| 101-250        | 47        | 13.02%  |
| 51-100         | 43        | 11.91%  |
| 251-500        | 37        | 10.25%  |
| 501-1000       | 17        | 4.71%   |
| 1001-2000      | 8         | 2.22%   |
| More than 3000 | 6         | 1.66%   |
| 2001-3000      | 6         | 1.66%   |
| Unknown        | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB                           | 2         | 2      | 3.51%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 3.51%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 1.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                 | 1         | 1      | 1.75%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 1.75%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 1.75%   |
| WDC WD2500AAKS-00VSA0 250GB                      | 1         | 1      | 1.75%   |
| WDC WD20EFRX-68AX9N0 2TB                         | 1         | 1      | 1.75%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.75%   |
| WDC WD2002FYPS-02W3B0 2TB                        | 1         | 1      | 1.75%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.75%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 1.75%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1         | 1      | 1.75%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1         | 1      | 1.75%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1         | 1      | 1.75%   |
| WDC WD1001FALS-40Y6A0 1TB                        | 1         | 1      | 1.75%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 1.75%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 1.75%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 1.75%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 1.75%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 1.75%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 1.75%   |
| Seagate ST3750840AS 752GB                        | 1         | 1      | 1.75%   |
| Seagate ST3250318AS 250GB                        | 1         | 2      | 1.75%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.75%   |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 1.75%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.75%   |
| Samsung Electronics SP2514N 250GB                | 1         | 1      | 1.75%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.75%   |
| Samsung Electronics HM321HI 320GB                | 1         | 2      | 1.75%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 1.75%   |
| Samsung Electronics HD250HJ 250GB                | 1         | 1      | 1.75%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 1.75%   |
| PNY 69D03094-T 40GB SSD                          | 1         | 1      | 1.75%   |
| Maxtor STM3160215AS 160GB                        | 1         | 1      | 1.75%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 1.75%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 1.75%   |
| JMicron Technology Generic 200GB                 | 1         | 1      | 1.75%   |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 14     | 23.64%  |
| Seagate             | 12        | 13     | 21.82%  |
| Hitachi             | 7         | 8      | 12.73%  |
| Samsung Electronics | 5         | 7      | 9.09%   |
| HGST                | 3         | 5      | 5.45%   |
| Toshiba             | 2         | 2      | 3.64%   |
| Intel               | 2         | 2      | 3.64%   |
| SSSTC               | 1         | 1      | 1.82%   |
| SanDisk             | 1         | 1      | 1.82%   |
| PNY                 | 1         | 1      | 1.82%   |
| Maxtor              | 1         | 1      | 1.82%   |
| LITEON              | 1         | 1      | 1.82%   |
| Kingston            | 1         | 2      | 1.82%   |
| JMicron Technology  | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| Crucial             | 1         | 1      | 1.82%   |
| ASMT                | 1         | 4      | 1.82%   |
| Unknown             | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 27.91%  |
| WDC                 | 11        | 12     | 25.58%  |
| Hitachi             | 7         | 8      | 16.28%  |
| Samsung Electronics | 4         | 6      | 9.3%    |
| HGST                | 3         | 5      | 6.98%   |
| Toshiba             | 2         | 2      | 4.65%   |
| Maxtor              | 1         | 1      | 2.33%   |
| JMicron Technology  | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| ASMT                | 1         | 4      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 53     | 78%     |
| SSD  | 11        | 13     | 22%     |

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
| Works    | 193       | 301    | 49.23%  |
| Detected | 150       | 269    | 38.27%  |
| Malfunc  | 49        | 66     | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 230       | 55.69%  |
| AMD                          | 70        | 16.95%  |
| Samsung Electronics          | 30        | 7.26%   |
| SK hynix                     | 16        | 3.87%   |
| SanDisk                      | 13        | 3.15%   |
| Kingston Technology Company  | 8         | 1.94%   |
| Phison Electronics           | 7         | 1.69%   |
| Silicon Motion               | 6         | 1.45%   |
| ASMedia Technology           | 6         | 1.45%   |
| JMicron Technology           | 4         | 0.97%   |
| VIA Technologies             | 3         | 0.73%   |
| Nvidia                       | 3         | 0.73%   |
| Silicon Image                | 2         | 0.48%   |
| Realtek Semiconductor        | 2         | 0.48%   |
| KIOXIA                       | 2         | 0.48%   |
| Toshiba America Info Systems | 1         | 0.24%   |
| Shenzhen Longsys Electronics | 1         | 0.24%   |
| Micron/Crucial Technology    | 1         | 0.24%   |
| Micron Technology            | 1         | 0.24%   |
| Marvell Technology Group     | 1         | 0.24%   |
| Lenovo                       | 1         | 0.24%   |
| INNOGRIT                     | 1         | 0.24%   |
| Broadcom / LSI               | 1         | 0.24%   |
| Biwin Storage Technology     | 1         | 0.24%   |
| Apple                        | 1         | 0.24%   |
| Adaptec                      | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 52        | 10.81%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 17        | 3.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 3.33%   |
| Samsung NVMe SSD Controller 980                                                         | 13        | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 2.49%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 11        | 2.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 8         | 1.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 1.46%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 7         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7         | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.25%   |
| AMD FCH SATA Controller D                                                               | 6         | 1.25%   |
| Kingston Company A2000 NVMe SSD                                                         | 5         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 262       | 61.65%  |
| NVMe | 95        | 22.35%  |
| IDE  | 41        | 9.65%   |
| RAID | 26        | 6.12%   |
| SAS  | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 260       | 73.86%  |
| AMD    | 85        | 24.15%  |
| ARM    | 7         | 1.99%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 1.42%   |
| ARM Processor                               | 5         | 1.42%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 5         | 1.42%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 1.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 4         | 1.13%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 1.13%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 1.13%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4         | 1.13%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 0.85%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 0.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 0.85%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.85%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 3         | 0.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 0.85%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3         | 0.85%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 0.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 0.85%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 2         | 0.57%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.57%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.57%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.57%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 0.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.57%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2         | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.57%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 2         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 20.11%  |
| Intel Celeron           | 42        | 11.9%   |
| Other                   | 34        | 9.63%   |
| Intel Core i7           | 33        | 9.35%   |
| Intel Core i3           | 29        | 8.22%   |
| AMD Ryzen 5             | 25        | 7.08%   |
| Intel Core 2 Duo        | 12        | 3.4%    |
| AMD Ryzen 7             | 12        | 3.4%    |
| Intel Xeon              | 10        | 2.83%   |
| Intel Atom              | 9         | 2.55%   |
| Intel Pentium           | 8         | 2.27%   |
| AMD A6                  | 5         | 1.42%   |
| AMD Ryzen 9             | 4         | 1.13%   |
| AMD FX                  | 4         | 1.13%   |
| AMD A8                  | 4         | 1.13%   |
| Intel Core 2 Quad       | 3         | 0.85%   |
| Intel Core 2            | 3         | 0.85%   |
| AMD Ryzen 5 PRO         | 3         | 0.85%   |
| AMD Ryzen 3             | 3         | 0.85%   |
| AMD Phenom II X4        | 3         | 0.85%   |
| AMD A10                 | 3         | 0.85%   |
| Intel Pentium Dual-Core | 2         | 0.57%   |
| Intel Pentium Dual      | 2         | 0.57%   |
| Intel Pentium 4         | 2         | 0.57%   |
| Intel Genuine           | 2         | 0.57%   |
| ARM Allwinner           | 2         | 0.57%   |
| AMD Ryzen Threadripper  | 2         | 0.57%   |
| AMD Ryzen 7 PRO         | 2         | 0.57%   |
| AMD E2                  | 2         | 0.57%   |
| AMD E1                  | 2         | 0.57%   |
| AMD Athlon II X2        | 2         | 0.57%   |
| AMD Athlon              | 2         | 0.57%   |
| AMD A4                  | 2         | 0.57%   |
| Intel Xeon Gold         | 1         | 0.28%   |
| Intel Pentium Silver    | 1         | 0.28%   |
| Intel Core m3           | 1         | 0.28%   |
| Intel Core 2 Extreme    | 1         | 0.28%   |
| AMD Sempron             | 1         | 0.28%   |
| AMD Ryzen Embedded      | 1         | 0.28%   |
| AMD Phenom II X6        | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 154       | 43.5%   |
| 4       | 121       | 34.18%  |
| 6       | 33        | 9.32%   |
| 8       | 21        | 5.93%   |
| 12      | 6         | 1.69%   |
| 1       | 5         | 1.41%   |
| 10      | 3         | 0.85%   |
| Unknown | 3         | 0.85%   |
| 64      | 2         | 0.56%   |
| 16      | 2         | 0.56%   |
| 14      | 2         | 0.56%   |
| 3       | 2         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 346       | 98.3%   |
| 2       | 3         | 0.85%   |
| Unknown | 3         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 211       | 59.94%  |
| 1       | 138       | 39.2%   |
| Unknown | 3         | 0.85%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 349       | 99.15%  |
| Unknown        | 3         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 33.24%  |
| 0x806c1    | 15        | 4.23%   |
| 0x306a9    | 13        | 3.66%   |
| 0x206a7    | 10        | 2.82%   |
| 0x306c3    | 9         | 2.54%   |
| 0x406e3    | 8         | 2.25%   |
| 0x306d4    | 7         | 1.97%   |
| 0x08608103 | 7         | 1.97%   |
| 0x806ec    | 6         | 1.69%   |
| 0x506c9    | 6         | 1.69%   |
| 0x406c4    | 6         | 1.69%   |
| 0x406c3    | 6         | 1.69%   |
| 0x106e5    | 6         | 1.69%   |
| 0x506e3    | 5         | 1.41%   |
| 0x30678    | 5         | 1.41%   |
| 0x0800820d | 5         | 1.41%   |
| 0xa0652    | 4         | 1.13%   |
| 0x906ea    | 4         | 1.13%   |
| 0x6fb      | 4         | 1.13%   |
| 0x40651    | 4         | 1.13%   |
| 0x1067a    | 4         | 1.13%   |
| 0x08701021 | 4         | 1.13%   |
| 0x08108109 | 4         | 1.13%   |
| 0x90672    | 3         | 0.85%   |
| 0x806ea    | 3         | 0.85%   |
| 0x806e9    | 3         | 0.85%   |
| 0x706a8    | 3         | 0.85%   |
| 0x706a1    | 3         | 0.85%   |
| 0x6fd      | 3         | 0.85%   |
| 0x20655    | 3         | 0.85%   |
| 0x20652    | 3         | 0.85%   |
| 0x10676    | 3         | 0.85%   |
| 0x0a50000c | 3         | 0.85%   |
| 0x010000c8 | 3         | 0.85%   |
| 0x906a3    | 2         | 0.56%   |
| 0x806d1    | 2         | 0.56%   |
| 0x6f6      | 2         | 0.56%   |
| 0x506ca    | 2         | 0.56%   |
| 0x306f2    | 2         | 0.56%   |
| 0x206d7    | 2         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 32        | 9.07%   |
| SandyBridge      | 26        | 7.37%   |
| Silvermont       | 25        | 7.08%   |
| Haswell          | 24        | 6.8%    |
| IvyBridge        | 23        | 6.52%   |
| Unknown          | 23        | 6.52%   |
| Skylake          | 21        | 5.95%   |
| TigerLake        | 17        | 4.82%   |
| Zen 2            | 16        | 4.53%   |
| Core             | 13        | 3.68%   |
| Zen+             | 12        | 3.4%    |
| Penryn           | 12        | 3.4%    |
| Broadwell        | 10        | 2.83%   |
| Zen 3            | 9         | 2.55%   |
| Westmere         | 9         | 2.55%   |
| Goldmont         | 9         | 2.55%   |
| Nehalem          | 7         | 1.98%   |
| K10              | 7         | 1.98%   |
| Goldmont plus    | 7         | 1.98%   |
| Piledriver       | 6         | 1.7%    |
| CometLake        | 6         | 1.7%    |
| Zen              | 5         | 1.42%   |
| Puma             | 5         | 1.42%   |
| Excavator        | 5         | 1.42%   |
| Alderlake Hybrid | 5         | 1.42%   |
| IceLake          | 4         | 1.13%   |
| K10 Llano        | 3         | 0.85%   |
| Bonnell          | 3         | 0.85%   |
| Bobcat           | 3         | 0.85%   |
| NetBurst         | 2         | 0.57%   |
| Tremont          | 1         | 0.28%   |
| Steamroller      | 1         | 0.28%   |
| K8 Hammer        | 1         | 0.28%   |
| Jaguar           | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 212       | 53.81%  |
| Nvidia                     | 91        | 23.1%   |
| AMD                        | 84        | 21.32%  |
| ASPEED Technology          | 4         | 1.02%   |
| Matrox Electronics Systems | 3         | 0.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 5.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 4.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 3.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.98%   |
| AMD Lucienne                                                                             | 8         | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.73%   |
| Intel HD Graphics 620                                                                    | 7         | 1.73%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.73%   |
| Intel HD Graphics 500                                                                    | 7         | 1.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 1.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.48%   |
| Intel HD Graphics 530                                                                    | 6         | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.23%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.99%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.99%   |
| Intel UHD Graphics 620                                                                   | 4         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.99%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 0.99%   |
| AMD Renoir                                                                               | 4         | 0.99%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.99%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.74%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.74%   |
| Intel AlderLake-S GT1                                                                    | 3         | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.74%   |
| Nvidia TU117M                                                                            | 2         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 171       | 48.58%  |
| 1 x AMD         | 68        | 19.32%  |
| 1 x Nvidia      | 54        | 15.34%  |
| Intel + Nvidia  | 29        | 8.24%   |
| Other           | 8         | 2.27%   |
| 2 x AMD         | 5         | 1.42%   |
| Intel + AMD     | 5         | 1.42%   |
| AMD + Nvidia    | 5         | 1.42%   |
| Nvidia + ASPEED | 3         | 0.85%   |
| 1 x Matrox      | 2         | 0.57%   |
| 1 x ASPEED      | 1         | 0.28%   |
| AMD + Matrox    | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 282       | 80.11%  |
| Proprietary | 54        | 15.34%  |
| Unknown     | 16        | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 241       | 67.89%  |
| 0.01-0.5   | 38        | 10.7%   |
| 1.01-2.0   | 28        | 7.89%   |
| 0.51-1.0   | 21        | 5.92%   |
| 3.01-4.0   | 14        | 3.94%   |
| 7.01-8.0   | 6         | 1.69%   |
| 8.01-16.0  | 4         | 1.13%   |
| 32.01-64.0 | 1         | 0.28%   |
| 5.01-6.0   | 1         | 0.28%   |
| 2.01-3.0   | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 14.52%  |
| Samsung Electronics     | 42        | 11.51%  |
| LG Display              | 33        | 9.04%   |
| BOE                     | 32        | 8.77%   |
| Dell                    | 27        | 7.4%    |
| Chimei Innolux          | 26        | 7.12%   |
| Goldstar                | 16        | 4.38%   |
| Hewlett-Packard         | 14        | 3.84%   |
| Acer                    | 11        | 3.01%   |
| AOC                     | 10        | 2.74%   |
| ViewSonic               | 8         | 2.19%   |
| Lenovo                  | 7         | 1.92%   |
| Iiyama                  | 7         | 1.92%   |
| Chi Mei Optoelectronics | 7         | 1.92%   |
| Philips                 | 6         | 1.64%   |
| PANDA                   | 5         | 1.37%   |
| BenQ                    | 5         | 1.37%   |
| Apple                   | 5         | 1.37%   |
| InfoVision              | 4         | 1.1%    |
| LG Philips              | 3         | 0.82%   |
| Vizio                   | 2         | 0.55%   |
| Toshiba                 | 2         | 0.55%   |
| Sony                    | 2         | 0.55%   |
| KDC                     | 2         | 0.55%   |
| Fujitsu Siemens         | 2         | 0.55%   |
| Envision Peripherals    | 2         | 0.55%   |
| Ancor Communications    | 2         | 0.55%   |
| ___                     | 1         | 0.27%   |
| Vita                    | 1         | 0.27%   |
| Vestel Elektronik       | 1         | 0.27%   |
| Unknown                 | 1         | 0.27%   |
| TEO                     | 1         | 0.27%   |
| TCL                     | 1         | 0.27%   |
| Sharp                   | 1         | 0.27%   |
| Sceptre Tech            | 1         | 0.27%   |
| SAC                     | 1         | 0.27%   |
| RTK                     | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| Packard Bell            | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.8%    |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.53%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                       | 2         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.53%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.53%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.53%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.53%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                      | 2         | 0.53%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                       | 1         | 0.27%   |
| Vizio E421VO VIZ0070 1920x1080 930x523mm 42.0-inch                       | 1         | 0.27%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.27%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                       | 1         | 0.27%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.27%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch            | 1         | 0.27%   |
| ViewSonic VX3276-UHD VSC5138 2048x1152 700x390mm 31.5-inch               | 1         | 0.27%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch            | 1         | 0.27%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.27%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch             | 1         | 0.27%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 1         | 0.27%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.27%   |
| Toshiba TV TSB0109 1920x1080                                             | 1         | 0.27%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.27%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                          | 1         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 156       | 44.32%  |
| 1366x768 (WXGA)    | 71        | 20.17%  |
| 1600x900 (HD+)     | 25        | 7.1%    |
| 3840x2160 (4K)     | 12        | 3.41%   |
| 1280x1024 (SXGA)   | 12        | 3.41%   |
| 2560x1440 (QHD)    | 11        | 3.13%   |
| 1440x900 (WXGA+)   | 11        | 3.13%   |
| 1920x1200 (WUXGA)  | 9         | 2.56%   |
| 1280x800 (WXGA)    | 9         | 2.56%   |
| 1680x1050 (WSXGA+) | 7         | 1.99%   |
| 3440x1440          | 3         | 0.85%   |
| 2560x1600          | 3         | 0.85%   |
| 1360x768           | 3         | 0.85%   |
| 1024x768 (XGA)     | 3         | 0.85%   |
| 3840x1600          | 2         | 0.57%   |
| 3840x1080          | 2         | 0.57%   |
| 2160x1440          | 2         | 0.57%   |
| 1600x1200          | 2         | 0.57%   |
| 1024x600           | 2         | 0.57%   |
| Unknown            | 2         | 0.57%   |
| 2880x1800          | 1         | 0.28%   |
| 2560x1080          | 1         | 0.28%   |
| 1920x540           | 1         | 0.28%   |
| 1920x515           | 1         | 0.28%   |
| 1366x912           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 88        | 23.91%  |
| 14      | 37        | 10.05%  |
| 13      | 35        | 9.51%   |
| 24      | 26        | 7.07%   |
| 23      | 26        | 7.07%   |
| 17      | 26        | 7.07%   |
| 27      | 22        | 5.98%   |
| 21      | 16        | 4.35%   |
| Unknown | 14        | 3.8%    |
| 19      | 12        | 3.26%   |
| 18      | 11        | 2.99%   |
| 20      | 8         | 2.17%   |
| 11      | 6         | 1.63%   |
| 31      | 5         | 1.36%   |
| 26      | 5         | 1.36%   |
| 12      | 5         | 1.36%   |
| 22      | 4         | 1.09%   |
| 34      | 3         | 0.82%   |
| 16      | 3         | 0.82%   |
| 40      | 2         | 0.54%   |
| 37      | 2         | 0.54%   |
| 25      | 2         | 0.54%   |
| 10      | 2         | 0.54%   |
| 84      | 1         | 0.27%   |
| 72      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 30      | 1         | 0.27%   |
| 29      | 1         | 0.27%   |
| 6       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 159       | 44.04%  |
| 501-600     | 74        | 20.5%   |
| 401-500     | 47        | 13.02%  |
| 201-300     | 24        | 6.65%   |
| 351-400     | 22        | 6.09%   |
| Unknown     | 14        | 3.88%   |
| 601-700     | 8         | 2.22%   |
| 801-900     | 4         | 1.11%   |
| 701-800     | 4         | 1.11%   |
| 1501-2000   | 2         | 0.55%   |
| 101-200     | 1         | 0.28%   |
| 1001-1500   | 1         | 0.28%   |
| 901-1000    | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 260       | 77.15%  |
| 16/10   | 44        | 13.06%  |
| 5/4     | 11        | 3.26%   |
| Unknown | 8         | 2.37%   |
| 4/3     | 6         | 1.78%   |
| 21/9    | 5         | 1.48%   |
| 3/2     | 2         | 0.59%   |
| 3.73    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 23.9%   |
| 81-90          | 63        | 17.31%  |
| 201-250        | 58        | 15.93%  |
| 151-200        | 28        | 7.69%   |
| 301-350        | 25        | 6.87%   |
| 141-150        | 17        | 4.67%   |
| Unknown        | 14        | 3.85%   |
| 121-130        | 13        | 3.57%   |
| 351-500        | 11        | 3.02%   |
| 71-80          | 10        | 2.75%   |
| 251-300        | 9         | 2.47%   |
| 51-60          | 6         | 1.65%   |
| 131-140        | 5         | 1.37%   |
| 61-70          | 4         | 1.1%    |
| 501-1000       | 4         | 1.1%    |
| More than 1000 | 3         | 0.82%   |
| 41-50          | 2         | 0.55%   |
| 111-120        | 2         | 0.55%   |
| 91-100         | 2         | 0.55%   |
| 1-40           | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 127       | 35.67%  |
| 121-160       | 106       | 29.78%  |
| 101-120       | 96        | 26.97%  |
| Unknown       | 14        | 3.93%   |
| 161-240       | 7         | 1.97%   |
| More than 240 | 4         | 1.12%   |
| 1-50          | 2         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 293       | 83.24%  |
| 2     | 41        | 11.65%  |
| 0     | 13        | 3.69%   |
| 3     | 5         | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 189       | 37.2%   |
| Intel                             | 168       | 33.07%  |
| Qualcomm Atheros                  | 54        | 10.63%  |
| Broadcom                          | 28        | 5.51%   |
| Ralink Technology                 | 5         | 0.98%   |
| MediaTek                          | 5         | 0.98%   |
| Marvell Technology Group          | 5         | 0.98%   |
| Qualcomm                          | 4         | 0.79%   |
| Dell                              | 4         | 0.79%   |
| Broadcom Limited                  | 4         | 0.79%   |
| TP-Link                           | 3         | 0.59%   |
| Nvidia                            | 3         | 0.59%   |
| Huawei Technologies               | 3         | 0.59%   |
| Xiaomi                            | 2         | 0.39%   |
| Sierra Wireless                   | 2         | 0.39%   |
| Samsung Electronics               | 2         | 0.39%   |
| Ralink                            | 2         | 0.39%   |
| Qualcomm Atheros Communications   | 2         | 0.39%   |
| Microchip Technology              | 2         | 0.39%   |
| Insyde Software                   | 2         | 0.39%   |
| Hewlett-Packard                   | 2         | 0.39%   |
| D-Link System                     | 2         | 0.39%   |
| ASIX Electronics                  | 2         | 0.39%   |
| Aquantia                          | 2         | 0.39%   |
| ZyDAS                             | 1         | 0.2%    |
| TRENDnet                          | 1         | 0.2%    |
| OPPO                              | 1         | 0.2%    |
| NetGear                           | 1         | 0.2%    |
| Microsoft                         | 1         | 0.2%    |
| LG Electronics                    | 1         | 0.2%    |
| Ericsson Business Mobile Networks | 1         | 0.2%    |
| D-Link                            | 1         | 0.2%    |
| BUFFALO                           | 1         | 0.2%    |
| Attansic Technology               | 1         | 0.2%    |
| Apple                             | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 131       | 21.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 3.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.33%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.16%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.66%   |
| Intel Wireless 8260                                               | 10        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.33%   |
| Intel Wireless 7265                                               | 8         | 1.33%   |
| Intel Wireless 7260                                               | 7         | 1.16%   |
| Intel Wireless 3165                                               | 7         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.16%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.83%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.83%   |
| Intel Wireless 3160                                               | 5         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.67%   |
| Realtek 802.11ac NIC                                              | 4         | 0.67%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 4         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.67%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 44.89%  |
| Realtek Semiconductor           | 53        | 19.34%  |
| Qualcomm Atheros                | 50        | 18.25%  |
| Broadcom                        | 14        | 5.11%   |
| Ralink Technology               | 5         | 1.82%   |
| MediaTek                        | 5         | 1.82%   |
| Qualcomm                        | 4         | 1.46%   |
| Dell                            | 3         | 1.09%   |
| TP-Link                         | 2         | 0.73%   |
| Sierra Wireless                 | 2         | 0.73%   |
| Ralink                          | 2         | 0.73%   |
| Qualcomm Atheros Communications | 2         | 0.73%   |
| ZyDAS                           | 1         | 0.36%   |
| TRENDnet                        | 1         | 0.36%   |
| NetGear                         | 1         | 0.36%   |
| Microsoft                       | 1         | 0.36%   |
| Marvell Technology Group        | 1         | 0.36%   |
| D-Link System                   | 1         | 0.36%   |
| D-Link                          | 1         | 0.36%   |
| BUFFALO                         | 1         | 0.36%   |
| Broadcom Limited                | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 13        | 4.69%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.61%   |
| Intel Wireless 8260                                            | 10        | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.89%   |
| Intel Wireless 7265                                            | 8         | 2.89%   |
| Intel Wireless 7260                                            | 7         | 2.53%   |
| Intel Wireless 3165                                            | 7         | 2.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 2.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 1.81%   |
| Intel Wireless 8265 / 8275                                     | 5         | 1.81%   |
| Intel Wireless 3160                                            | 5         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.44%   |
| Realtek 802.11ac NIC                                           | 4         | 1.44%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.44%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 1.08%   |
| Sierra Wireless EM7455                                         | 2         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 170       | 53.63%  |
| Intel                    | 90        | 28.39%  |
| Broadcom                 | 15        | 4.73%   |
| Qualcomm Atheros         | 10        | 3.15%   |
| Marvell Technology Group | 4         | 1.26%   |
| Nvidia                   | 3         | 0.95%   |
| Huawei Technologies      | 3         | 0.95%   |
| Broadcom Limited         | 3         | 0.95%   |
| Xiaomi                   | 2         | 0.63%   |
| Samsung Electronics      | 2         | 0.63%   |
| Insyde Software          | 2         | 0.63%   |
| Hewlett-Packard          | 2         | 0.63%   |
| ASIX Electronics         | 2         | 0.63%   |
| Aquantia                 | 2         | 0.63%   |
| TP-Link                  | 1         | 0.32%   |
| OPPO                     | 1         | 0.32%   |
| Microchip Technology     | 1         | 0.32%   |
| LG Electronics           | 1         | 0.32%   |
| D-Link System            | 1         | 0.32%   |
| Attansic Technology      | 1         | 0.32%   |
| Apple                    | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 131       | 40.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 7.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14        | 4.36%   |
| Realtek RTL8125 2.5GbE Controller                                              | 10        | 3.12%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.18%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.25%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.25%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.93%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 0.93%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.93%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.93%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.93%   |
| Huawei MLA-L11                                                                 | 3         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.62%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.62%   |
| Intel Ethernet Connection (17) I219-V                                          | 2         | 0.62%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.62%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.62%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.62%   |
| Insyde Software RNDIS/Ethernet Gadget                                          | 2         | 0.62%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.62%   |
| Aquantia Ethernet controller                                                   | 2         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.31%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 295       | 53.35%  |
| WiFi     | 255       | 46.11%  |
| Modem    | 3         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 207       | 58.15%  |
| Ethernet | 149       | 41.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 191       | 54.11%  |
| 1     | 140       | 39.66%  |
| 0     | 15        | 4.25%   |
| 3     | 4         | 1.13%   |
| 4     | 3         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 233       | 65.45%  |
| Yes  | 123       | 34.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 47.29%  |
| Realtek Semiconductor           | 22        | 10.84%  |
| Broadcom                        | 14        | 6.9%    |
| Cambridge Silicon Radio         | 13        | 6.4%    |
| Foxconn / Hon Hai               | 10        | 4.93%   |
| Qualcomm Atheros Communications | 9         | 4.43%   |
| Lite-On Technology              | 9         | 4.43%   |
| IMC Networks                    | 7         | 3.45%   |
| Apple                           | 4         | 1.97%   |
| Realtek                         | 3         | 1.48%   |
| Hewlett-Packard                 | 3         | 1.48%   |
| Dell                            | 2         | 0.99%   |
| ASUSTek Computer                | 2         | 0.99%   |
| USI                             | 1         | 0.49%   |
| Toshiba                         | 1         | 0.49%   |
| Ralink                          | 1         | 0.49%   |
| MediaTek                        | 1         | 0.49%   |
| Marvell Semiconductor           | 1         | 0.49%   |
| Fujitsu                         | 1         | 0.49%   |
| Foxconn International           | 1         | 0.49%   |
| Chicony Electronics             | 1         | 0.49%   |
| Alps Electric                   | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 43        | 21.18%  |
| Intel AX201 Bluetooth                                                               | 19        | 9.36%   |
| Realtek Bluetooth Radio                                                             | 15        | 7.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 6.4%    |
| Intel AX200 Bluetooth                                                               | 12        | 5.91%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.96%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 2.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 2.96%   |
| Intel AX210 Bluetooth                                                               | 6         | 2.96%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 2.96%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.48%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.48%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.48%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.99%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.99%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.99%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.99%   |
| Intel Bluetooth Device                                                              | 2         | 0.99%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.99%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.99%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.99%   |
| USI Bluetooth Device                                                                | 1         | 0.49%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.49%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.49%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.49%   |
| MediaTek Wireless_Device                                                            | 1         | 0.49%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.49%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.49%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.49%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 249       | 57.37%  |
| AMD                         | 93        | 21.43%  |
| Nvidia                      | 61        | 14.06%  |
| C-Media Electronics         | 5         | 1.15%   |
| Texas Instruments           | 3         | 0.69%   |
| SAVITECH                    | 2         | 0.46%   |
| JMTek                       | 2         | 0.46%   |
| Generalplus Technology      | 2         | 0.46%   |
| ASUSTek Computer            | 2         | 0.46%   |
| VIA Technologies            | 1         | 0.23%   |
| Trust International         | 1         | 0.23%   |
| Tenx Technology             | 1         | 0.23%   |
| Samson Technologies         | 1         | 0.23%   |
| Plantronics                 | 1         | 0.23%   |
| Medeli Electronics          | 1         | 0.23%   |
| MAG Technology              | 1         | 0.23%   |
| Logitech                    | 1         | 0.23%   |
| Lenovo                      | 1         | 0.23%   |
| Kingston Technology         | 1         | 0.23%   |
| Hewlett-Packard             | 1         | 0.23%   |
| GN Netcom                   | 1         | 0.23%   |
| FiiO Electronics Technology | 1         | 0.23%   |
| Creative Labs               | 1         | 0.23%   |
| Corsair                     | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 4.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 4.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 4.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 3.28%   |
| AMD FCH Azalia Controller                                                                         | 16        | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 2.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 2.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 1.74%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.35%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 7         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.16%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.77%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 72        | 24.16%  |
| Unknown                    | 47        | 15.77%  |
| SK hynix                   | 39        | 13.09%  |
| Kingston                   | 38        | 12.75%  |
| Micron Technology          | 26        | 8.72%   |
| Crucial                    | 22        | 7.38%   |
| G.Skill                    | 10        | 3.36%   |
| Ramaxel Technology         | 8         | 2.68%   |
| Unknown (ABCD)             | 7         | 2.35%   |
| Corsair                    | 5         | 1.68%   |
| Nanya Technology           | 3         | 1.01%   |
| Elpida                     | 3         | 1.01%   |
| Transcend                  | 2         | 0.67%   |
| Smart                      | 2         | 0.67%   |
| A-DATA Technology          | 2         | 0.67%   |
| Unknown                    | 2         | 0.67%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.34%   |
| Timetec                    | 1         | 0.34%   |
| Qumo                       | 1         | 0.34%   |
| Qimonda                    | 1         | 0.34%   |
| GLOWAY                     | 1         | 0.34%   |
| Foxline                    | 1         | 0.34%   |
| fef5                       | 1         | 0.34%   |
| Essencore                  | 1         | 0.34%   |
| Daten Tecnologia           | 1         | 0.34%   |
| ASint Technology           | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.62%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.29%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.29%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 3         | 0.97%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 3         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.97%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.65%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                    | 2         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.65%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.65%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.65%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.65%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.65%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.65%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.65%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.65%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s             | 2         | 0.65%   |
| Unknown                                                          | 2         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.32%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 107       | 41.96%  |
| DDR3    | 95        | 37.25%  |
| LPDDR4  | 18        | 7.06%   |
| DDR2    | 13        | 5.1%    |
| LPDDR3  | 6         | 2.35%   |
| Unknown | 6         | 2.35%   |
| SDRAM   | 4         | 1.57%   |
| LPDDR5  | 2         | 0.78%   |
| DDR5    | 2         | 0.78%   |
| DRAM    | 1         | 0.39%   |
| DDR     | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 55.64%  |
| DIMM         | 89        | 34.63%  |
| Row Of Chips | 20        | 7.78%   |
| Chip         | 3         | 1.17%   |
| Unknown      | 2         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 87        | 31.75%  |
| 4096  | 87        | 31.75%  |
| 2048  | 46        | 16.79%  |
| 16384 | 37        | 13.5%   |
| 1024  | 10        | 3.65%   |
| 32768 | 4         | 1.46%   |
| 65536 | 1         | 0.36%   |
| 1536  | 1         | 0.36%   |
| 512   | 1         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 64        | 23.62%  |
| 3200    | 45        | 16.61%  |
| 2667    | 30        | 11.07%  |
| 2400    | 21        | 7.75%   |
| 1333    | 21        | 7.75%   |
| 2133    | 15        | 5.54%   |
| 667     | 10        | 3.69%   |
| 1334    | 6         | 2.21%   |
| 4267    | 5         | 1.85%   |
| Unknown | 5         | 1.85%   |
| 3600    | 4         | 1.48%   |
| 3000    | 4         | 1.48%   |
| 1067    | 4         | 1.48%   |
| 1066    | 4         | 1.48%   |
| 2666    | 3         | 1.11%   |
| 1867    | 3         | 1.11%   |
| 6400    | 2         | 0.74%   |
| 3466    | 2         | 0.74%   |
| 3266    | 2         | 0.74%   |
| 1866    | 2         | 0.74%   |
| 800     | 2         | 0.74%   |
| 6000    | 1         | 0.37%   |
| 4800    | 1         | 0.37%   |
| 4266    | 1         | 0.37%   |
| 4199    | 1         | 0.37%   |
| 4000    | 1         | 0.37%   |
| 3866    | 1         | 0.37%   |
| 3733    | 1         | 0.37%   |
| 3400    | 1         | 0.37%   |
| 3020    | 1         | 0.37%   |
| 2800    | 1         | 0.37%   |
| 2134    | 1         | 0.37%   |
| 2000    | 1         | 0.37%   |
| 1800    | 1         | 0.37%   |
| 1776    | 1         | 0.37%   |
| 1648    | 1         | 0.37%   |
| 533     | 1         | 0.37%   |
| 400     | 1         | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Brother Industries  | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| Minolta             | 1         | 12.5%   |
| Canon               | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SF-760 Series         | 1         | 12.5%   |
| Minolta PagePro 1300W         | 1         | 12.5%   |
| HP DeskJet D1360              | 1         | 12.5%   |
| HP DeskJet 840c               | 1         | 12.5%   |
| HP Deskjet 3070 B611 series   | 1         | 12.5%   |
| Canon TS3500 series           | 1         | 12.5%   |
| Brother HL-2030 Laser Printer | 1         | 12.5%   |
| Brother DCP-7040              | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 66.67%  |
| Seiko Epson     | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                | 3         | 50%     |
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 16.67%  |
| HP ScanJet 7400c                       | 1         | 16.67%  |
| Canon CanoScan LiDE 110                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 54        | 24.66%  |
| Realtek Semiconductor                  | 19        | 8.68%   |
| IMC Networks                           | 16        | 7.31%   |
| Quanta                                 | 15        | 6.85%   |
| Microdia                               | 15        | 6.85%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 6.39%   |
| Suyin                                  | 13        | 5.94%   |
| Sunplus Innovation Technology          | 12        | 5.48%   |
| Logitech                               | 8         | 3.65%   |
| Acer                                   | 7         | 3.2%    |
| Apple                                  | 4         | 1.83%   |
| Z-Star Microelectronics                | 3         | 1.37%   |
| Microsoft                              | 3         | 1.37%   |
| Luxvisions Innotech Limited            | 3         | 1.37%   |
| Lite-On Technology                     | 3         | 1.37%   |
| Alcor Micro                            | 3         | 1.37%   |
| Syntek                                 | 2         | 0.91%   |
| Silicon Motion                         | 2         | 0.91%   |
| Ricoh                                  | 2         | 0.91%   |
| icSpring                               | 2         | 0.91%   |
| Xiongmai                               | 1         | 0.46%   |
| Xiaomi                                 | 1         | 0.46%   |
| USB Camera CS                          | 1         | 0.46%   |
| SunplusIT                              | 1         | 0.46%   |
| Sunplus Technology                     | 1         | 0.46%   |
| Sonix Technology                       | 1         | 0.46%   |
| Samsung Electronics                    | 1         | 0.46%   |
| Primax Electronics                     | 1         | 0.46%   |
| OYT Tech                               | 1         | 0.46%   |
| OmniVision Technologies                | 1         | 0.46%   |
| MacroSilicon                           | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| KYE Systems (Mouse Systems)            | 1         | 0.46%   |
| Importek                               | 1         | 0.46%   |
| Guillemot                              | 1         | 0.46%   |
| DLEQNA19IFK6G2                         | 1         | 0.46%   |
| Creative Technology                    | 1         | 0.46%   |
| Bison Electronics                      | 1         | 0.46%   |
| Alpha Imaging Technology               | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 18        | 8.18%   |
| Chicony HD WebCam                                   | 5         | 2.27%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.82%   |
| IMC Networks Integrated Camera                      | 4         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 1.82%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 1.36%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.36%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 1.36%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.36%   |
| Quanta HD User Facing                               | 3         | 1.36%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 1.36%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.36%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.36%   |
| Chicony EasyCamera                                  | 3         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.36%   |
| Acer Integrated Camera                              | 3         | 1.36%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.91%   |
| Realtek USB Camera                                  | 2         | 0.91%   |
| Realtek HP Truevision HD                            | 2         | 0.91%   |
| Realtek FULL HD 1080P Webcam                        | 2         | 0.91%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 0.91%   |
| Quanta HP Webcam                                    | 2         | 0.91%   |
| Microdia Webcam Vitade AF                           | 2         | 0.91%   |
| Microdia Lenovo EasyCamera                          | 2         | 0.91%   |
| Logitech HD Pro Webcam C920                         | 2         | 0.91%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 0.91%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.91%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 0.91%   |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.91%   |
| IMC Networks HD Camera                              | 2         | 0.91%   |
| icSpring camera                                     | 2         | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.91%   |
| Chicony USB2.0 Camera                               | 2         | 0.91%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 0.91%   |
| Chicony HP Truevision HD                            | 2         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 0.91%   |
| Apple Built-in iSight                               | 2         | 0.91%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 32.35%  |
| Shenzhen Goodix Technology | 8         | 23.53%  |
| Synaptics                  | 6         | 17.65%  |
| Upek                       | 5         | 14.71%  |
| STMicroelectronics         | 2         | 5.88%   |
| Elan Microelectronics      | 1         | 2.94%   |
| AuthenTec                  | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 5         | 14.71%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 11.76%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 11.76%  |
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 8.82%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 8.82%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 5.88%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 5.88%   |
| Unknown                                                | 2         | 5.88%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 2.94%   |
| Synaptics  WBDI                                        | 1         | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.94%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 9         | 40.91%  |
| Alcor Micro              | 7         | 31.82%  |
| O2 Micro                 | 2         | 9.09%   |
| Lenovo                   | 2         | 9.09%   |
| Reiner SCT Kartensysteme | 1         | 4.55%   |
| In Focus Systems         | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 31.82%  |
| Broadcom 5880                                                                | 3         | 13.64%  |
| Broadcom 58200                                                               | 3         | 13.64%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 9.09%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 4.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.55%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 257       | 72.6%   |
| 1     | 74        | 20.9%   |
| 2     | 18        | 5.08%   |
| 3     | 4         | 1.13%   |
| 5     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 27.27%  |
| Chipcard                 | 22        | 18.18%  |
| Graphics card            | 21        | 17.36%  |
| Camera                   | 10        | 8.26%   |
| Net/wireless             | 7         | 5.79%   |
| Multimedia controller    | 5         | 4.13%   |
| Bluetooth                | 5         | 4.13%   |
| Unassigned class         | 4         | 3.31%   |
| Communication controller | 4         | 3.31%   |
| Card reader              | 4         | 3.31%   |
| Network                  | 3         | 2.48%   |
| Storage                  | 1         | 0.83%   |
| Sound                    | 1         | 0.83%   |
| Net/ethernet             | 1         | 0.83%   |

