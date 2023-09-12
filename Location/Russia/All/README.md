Linux in Russia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Russia/Desktop/README.md) and [notebooks](/Location/Russia/Notebook/README.md).

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

Total: 40792

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | V15-IGL 82C3                | Notebook    | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [38ebaae5c3](https://linux-hardware.org/?probe=38ebaae5c3) | Sep 07, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | Desktop     | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [ade0754252](https://linux-hardware.org/?probe=ade0754252) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | Notebook    | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| Biostar       | A320MH                      | Desktop     | [87ae9fef79](https://linux-hardware.org/?probe=87ae9fef79) | Sep 07, 2023 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [76b044add6](https://linux-hardware.org/?probe=76b044add6) | Sep 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [67934ce24a](https://linux-hardware.org/?probe=67934ce24a) | Sep 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [43fa75d035](https://linux-hardware.org/?probe=43fa75d035) | Sep 07, 2023 |
| Biostar       | B550M-SILVER                | Desktop     | [12ad2e157b](https://linux-hardware.org/?probe=12ad2e157b) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [83b9205283](https://linux-hardware.org/?probe=83b9205283) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [b2ba03726a](https://linux-hardware.org/?probe=b2ba03726a) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [6783f1d181](https://linux-hardware.org/?probe=6783f1d181) | Sep 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [29e1f84537](https://linux-hardware.org/?probe=29e1f84537) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [9370483c5f](https://linux-hardware.org/?probe=9370483c5f) | Sep 06, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [32c34f0aa2](https://linux-hardware.org/?probe=32c34f0aa2) | Sep 06, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [ffe10aadbe](https://linux-hardware.org/?probe=ffe10aadbe) | Sep 06, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | H420                        | Desktop     | [f84aae6411](https://linux-hardware.org/?probe=f84aae6411) | Sep 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [c3a39bc1f1](https://linux-hardware.org/?probe=c3a39bc1f1) | Sep 06, 2023 |
| Supermicro    | X8DTU                       | Server      | [ceac91ff5e](https://linux-hardware.org/?probe=ceac91ff5e) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [ba211ae5ca](https://linux-hardware.org/?probe=ba211ae5ca) | Sep 06, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [5ba13c092c](https://linux-hardware.org/?probe=5ba13c092c) | Sep 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c22fad9c67](https://linux-hardware.org/?probe=c22fad9c67) | Sep 06, 2023 |
| Lenovo        | 3144                        | Mini pc     | [8dbb3d65e7](https://linux-hardware.org/?probe=8dbb3d65e7) | Sep 06, 2023 |
| Supermicro    | X9DRW                       | Server      | [8108cf6d57](https://linux-hardware.org/?probe=8108cf6d57) | Sep 06, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [c93409061c](https://linux-hardware.org/?probe=c93409061c) | Sep 06, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [01d640708d](https://linux-hardware.org/?probe=01d640708d) | Sep 06, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [c309162d11](https://linux-hardware.org/?probe=c309162d11) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c7bdf1cee6](https://linux-hardware.org/?probe=c7bdf1cee6) | Sep 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e8caa63849](https://linux-hardware.org/?probe=e8caa63849) | Sep 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [4a5a98638e](https://linux-hardware.org/?probe=4a5a98638e) | Sep 06, 2023 |
| ASRock        | Z690 PG Velocita            | Desktop     | [0064d9d9e2](https://linux-hardware.org/?probe=0064d9d9e2) | Sep 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1c8b9eed31](https://linux-hardware.org/?probe=1c8b9eed31) | Sep 06, 2023 |
| Biostar       | A68MHE                      | Desktop     | [65bd192bf0](https://linux-hardware.org/?probe=65bd192bf0) | Sep 06, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [54556adb0b](https://linux-hardware.org/?probe=54556adb0b) | Sep 05, 2023 |
| ECS           | A740GM-M                    | Desktop     | [132b141a7d](https://linux-hardware.org/?probe=132b141a7d) | Sep 05, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [9c7d201848](https://linux-hardware.org/?probe=9c7d201848) | Sep 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0f5597eb7e](https://linux-hardware.org/?probe=0f5597eb7e) | Sep 05, 2023 |
| ASUSTek       | N76VJ                       | Notebook    | [382d892ff6](https://linux-hardware.org/?probe=382d892ff6) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [baad816533](https://linux-hardware.org/?probe=baad816533) | Sep 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [8bca1f8244](https://linux-hardware.org/?probe=8bca1f8244) | Sep 05, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b8dd9b8f96](https://linux-hardware.org/?probe=b8dd9b8f96) | Sep 05, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [d83ba68fcb](https://linux-hardware.org/?probe=d83ba68fcb) | Sep 05, 2023 |
| Biostar       | A68MHE                      | Desktop     | [65a3d0ff34](https://linux-hardware.org/?probe=65a3d0ff34) | Sep 05, 2023 |
| ASRock        | B450M Pro4-F R2.0           | Desktop     | [3eef4ac5d3](https://linux-hardware.org/?probe=3eef4ac5d3) | Sep 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [40098c0a79](https://linux-hardware.org/?probe=40098c0a79) | Sep 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [1af9fd689a](https://linux-hardware.org/?probe=1af9fd689a) | Sep 05, 2023 |
| Supermicro    | X9DRW                       | Server      | [0276a103dd](https://linux-hardware.org/?probe=0276a103dd) | Sep 05, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [28d5496080](https://linux-hardware.org/?probe=28d5496080) | Sep 04, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [0830aad0cc](https://linux-hardware.org/?probe=0830aad0cc) | Sep 04, 2023 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [bce72e53fa](https://linux-hardware.org/?probe=bce72e53fa) | Sep 04, 2023 |
| Supermicro    | X8DTT                       | Server      | [1dbd818a95](https://linux-hardware.org/?probe=1dbd818a95) | Sep 04, 2023 |
| HP            | 8526 MVB, A                 | Desktop     | [3133ab688e](https://linux-hardware.org/?probe=3133ab688e) | Sep 04, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [5a772c1cbf](https://linux-hardware.org/?probe=5a772c1cbf) | Sep 04, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [bbcfaaaaed](https://linux-hardware.org/?probe=bbcfaaaaed) | Sep 04, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [3462791aa1](https://linux-hardware.org/?probe=3462791aa1) | Sep 04, 2023 |
| OEM           | Intel H81                   | Desktop     | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| MSI           | B360M MORTAR                | Desktop     | [d023a05e0b](https://linux-hardware.org/?probe=d023a05e0b) | Sep 04, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [246d3b2d0a](https://linux-hardware.org/?probe=246d3b2d0a) | Sep 04, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [8928cdbfa8](https://linux-hardware.org/?probe=8928cdbfa8) | Sep 04, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2135954523](https://linux-hardware.org/?probe=2135954523) | Sep 04, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [543ae5c1f3](https://linux-hardware.org/?probe=543ae5c1f3) | Sep 04, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [cb59b205d9](https://linux-hardware.org/?probe=cb59b205d9) | Sep 04, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [590b5224d9](https://linux-hardware.org/?probe=590b5224d9) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [68bea64ed6](https://linux-hardware.org/?probe=68bea64ed6) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8320743af2](https://linux-hardware.org/?probe=8320743af2) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | Desktop     | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [0eff1074a1](https://linux-hardware.org/?probe=0eff1074a1) | Sep 03, 2023 |
| Lenovo        | B460e                       | Notebook    | [7134698bfb](https://linux-hardware.org/?probe=7134698bfb) | Sep 03, 2023 |
| ASUSTek       | X507UB                      | Notebook    | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c5ffec4746](https://linux-hardware.org/?probe=c5ffec4746) | Sep 03, 2023 |
| ASUSTek       | V221IC                      | All in one  | [1abad6ed2e](https://linux-hardware.org/?probe=1abad6ed2e) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d8b388ed5f](https://linux-hardware.org/?probe=d8b388ed5f) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [94da12d8d8](https://linux-hardware.org/?probe=94da12d8d8) | Sep 03, 2023 |
| HUAWEI        | FRD-WX9                     | Notebook    | [5831652a84](https://linux-hardware.org/?probe=5831652a84) | Sep 03, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [7abcd39073](https://linux-hardware.org/?probe=7abcd39073) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | Notebook    | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| ASRock        | FM2A78M-HD+                 | Desktop     | [a2d8c14a71](https://linux-hardware.org/?probe=a2d8c14a71) | Sep 03, 2023 |
| ASUSTek       | V221IC                      | All in one  | [06240bab5b](https://linux-hardware.org/?probe=06240bab5b) | Sep 03, 2023 |
| HP            | ENVY m6                     | Notebook    | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | Desktop     | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| Sony          | VPCEL1E1R                   | Notebook    | [64dec0f73c](https://linux-hardware.org/?probe=64dec0f73c) | Sep 03, 2023 |
| Sony          | VPCEL1E1R                   | Notebook    | [4a55a9ce8d](https://linux-hardware.org/?probe=4a55a9ce8d) | Sep 03, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [6624329e1c](https://linux-hardware.org/?probe=6624329e1c) | Sep 03, 2023 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [f0c5bbc0c1](https://linux-hardware.org/?probe=f0c5bbc0c1) | Sep 03, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [0f08b5b0ad](https://linux-hardware.org/?probe=0f08b5b0ad) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [78c449e398](https://linux-hardware.org/?probe=78c449e398) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [7f25cc995d](https://linux-hardware.org/?probe=7f25cc995d) | Sep 03, 2023 |
| ASUSTek       | M2N                         | Desktop     | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| MSI           | 770-C45                     | Desktop     | [002c1856c6](https://linux-hardware.org/?probe=002c1856c6) | Sep 03, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6b33c9cb36](https://linux-hardware.org/?probe=6b33c9cb36) | Sep 02, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3ee4e0f848](https://linux-hardware.org/?probe=3ee4e0f848) | Sep 02, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| MSI           | GT60 2QE                    | Notebook    | [234502653b](https://linux-hardware.org/?probe=234502653b) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [3969affef8](https://linux-hardware.org/?probe=3969affef8) | Sep 02, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [c74782636f](https://linux-hardware.org/?probe=c74782636f) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [1b5109eb83](https://linux-hardware.org/?probe=1b5109eb83) | Sep 02, 2023 |
| Irbis         | NB133                       | Notebook    | [62f2194b9a](https://linux-hardware.org/?probe=62f2194b9a) | Sep 02, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [1af7f717b0](https://linux-hardware.org/?probe=1af7f717b0) | Sep 02, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [48c352470d](https://linux-hardware.org/?probe=48c352470d) | Sep 02, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| HP            | 630                         | Notebook    | [a1f0efde46](https://linux-hardware.org/?probe=a1f0efde46) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [5542a06e1c](https://linux-hardware.org/?probe=5542a06e1c) | Sep 02, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [fb0900afbb](https://linux-hardware.org/?probe=fb0900afbb) | Sep 02, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [b50da6446a](https://linux-hardware.org/?probe=b50da6446a) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [8e59296a5c](https://linux-hardware.org/?probe=8e59296a5c) | Sep 02, 2023 |
| Foxconn       | 45CS                        | Desktop     | [56c503e42c](https://linux-hardware.org/?probe=56c503e42c) | Sep 02, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [400dc7ae1b](https://linux-hardware.org/?probe=400dc7ae1b) | Sep 01, 2023 |
| Prestigio     | Multipad Visconte V         | Notebook    | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [91d7a53a1b](https://linux-hardware.org/?probe=91d7a53a1b) | Sep 01, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1e51610ea3](https://linux-hardware.org/?probe=1e51610ea3) | Sep 01, 2023 |
| eMachines     | eME442                      | Notebook    | [7b765f910c](https://linux-hardware.org/?probe=7b765f910c) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [45c37720b0](https://linux-hardware.org/?probe=45c37720b0) | Sep 01, 2023 |
| Aquarius      | Cmp NS483                   | Convertible | [64c1508237](https://linux-hardware.org/?probe=64c1508237) | Sep 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [52911d341d](https://linux-hardware.org/?probe=52911d341d) | Sep 01, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [2a11f6be15](https://linux-hardware.org/?probe=2a11f6be15) | Sep 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [42547fa1b3](https://linux-hardware.org/?probe=42547fa1b3) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [1e7179e4f0](https://linux-hardware.org/?probe=1e7179e4f0) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [e9f211faf1](https://linux-hardware.org/?probe=e9f211faf1) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b1a3900bdd](https://linux-hardware.org/?probe=b1a3900bdd) | Sep 01, 2023 |
| Unknown       | Unknown                     | Soc         | [8d270a161d](https://linux-hardware.org/?probe=8d270a161d) | Sep 01, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [87f94b4ba7](https://linux-hardware.org/?probe=87f94b4ba7) | Sep 01, 2023 |
| ASUSTek       | N3050T                      | Desktop     | [fa4b0cbf08](https://linux-hardware.org/?probe=fa4b0cbf08) | Sep 01, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [dd5735f315](https://linux-hardware.org/?probe=dd5735f315) | Sep 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [16059fa2ec](https://linux-hardware.org/?probe=16059fa2ec) | Sep 01, 2023 |
| ASUSTek       | W7S                         | Notebook    | [6865435d79](https://linux-hardware.org/?probe=6865435d79) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | Notebook    | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [0265cb5d01](https://linux-hardware.org/?probe=0265cb5d01) | Aug 31, 2023 |
| HP            | Notebook                    | Notebook    | [0d55f397ff](https://linux-hardware.org/?probe=0d55f397ff) | Aug 31, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [305133ce29](https://linux-hardware.org/?probe=305133ce29) | Aug 31, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [25339d5009](https://linux-hardware.org/?probe=25339d5009) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | Desktop     | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| Intel         | B75                         | Desktop     | [55695d0962](https://linux-hardware.org/?probe=55695d0962) | Aug 31, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [7c560dfe57](https://linux-hardware.org/?probe=7c560dfe57) | Aug 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a829cc0dce](https://linux-hardware.org/?probe=a829cc0dce) | Aug 31, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [293c912276](https://linux-hardware.org/?probe=293c912276) | Aug 31, 2023 |
| OrangePi      | Zero3                       | Soc         | [34919a3af1](https://linux-hardware.org/?probe=34919a3af1) | Aug 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [9cb322dda0](https://linux-hardware.org/?probe=9cb322dda0) | Aug 30, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [10444e1cd3](https://linux-hardware.org/?probe=10444e1cd3) | Aug 30, 2023 |
| HUAWEI        | KLVF-XX                     | Notebook    | [747a685cc1](https://linux-hardware.org/?probe=747a685cc1) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | Server      | [6b931a0ef2](https://linux-hardware.org/?probe=6b931a0ef2) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [a71700e059](https://linux-hardware.org/?probe=a71700e059) | Aug 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [afb724c8da](https://linux-hardware.org/?probe=afb724c8da) | Aug 30, 2023 |
| ASUSTek       | P8H61 EVO                   | Desktop     | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [cd7bf0b2db](https://linux-hardware.org/?probe=cd7bf0b2db) | Aug 30, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ea587f2b2e](https://linux-hardware.org/?probe=ea587f2b2e) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ef1b605965](https://linux-hardware.org/?probe=ef1b605965) | Aug 30, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [27136611ed](https://linux-hardware.org/?probe=27136611ed) | Aug 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| MSI           | A68HM-P33 V2                | Desktop     | [44d09f93c9](https://linux-hardware.org/?probe=44d09f93c9) | Aug 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [91d3472ba6](https://linux-hardware.org/?probe=91d3472ba6) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [a7b83b57e0](https://linux-hardware.org/?probe=a7b83b57e0) | Aug 30, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3eb3a344ee](https://linux-hardware.org/?probe=3eb3a344ee) | Aug 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [efee17a022](https://linux-hardware.org/?probe=efee17a022) | Aug 30, 2023 |
| Supermicro    | X8DTT                       | Server      | [d1c898358d](https://linux-hardware.org/?probe=d1c898358d) | Aug 30, 2023 |
| ASRock        | M3A UCC                     | Desktop     | [b46f15b2d2](https://linux-hardware.org/?probe=b46f15b2d2) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [d7860c1c92](https://linux-hardware.org/?probe=d7860c1c92) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| Aquarius      | Cmp NS483                   | Convertible | [4205c815b9](https://linux-hardware.org/?probe=4205c815b9) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [1ff3234fa5](https://linux-hardware.org/?probe=1ff3234fa5) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [98d2e58ba6](https://linux-hardware.org/?probe=98d2e58ba6) | Aug 30, 2023 |
| HP            | ENVY Notebook               | Notebook    | [eda6f43e59](https://linux-hardware.org/?probe=eda6f43e59) | Aug 30, 2023 |
| Foxconn       | H55MXV Series               | Desktop     | [af9d0ad662](https://linux-hardware.org/?probe=af9d0ad662) | Aug 30, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [26558ed0ce](https://linux-hardware.org/?probe=26558ed0ce) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Dell          | 0J2J3Y A00                  | Desktop     | [57ac609885](https://linux-hardware.org/?probe=57ac609885) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [d6fded6169](https://linux-hardware.org/?probe=d6fded6169) | Aug 30, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [c5030f8fa1](https://linux-hardware.org/?probe=c5030f8fa1) | Aug 30, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [7b3b082c14](https://linux-hardware.org/?probe=7b3b082c14) | Aug 30, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [927a574e71](https://linux-hardware.org/?probe=927a574e71) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | Notebook    | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | Notebook    | [95aa09fab6](https://linux-hardware.org/?probe=95aa09fab6) | Aug 29, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d5e628923](https://linux-hardware.org/?probe=2d5e628923) | Aug 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [708fc220a9](https://linux-hardware.org/?probe=708fc220a9) | Aug 29, 2023 |
| MSI           | PH61-SP35                   | Desktop     | [590f47f3fd](https://linux-hardware.org/?probe=590f47f3fd) | Aug 29, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [4acce51a96](https://linux-hardware.org/?probe=4acce51a96) | Aug 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [9bd0b91866](https://linux-hardware.org/?probe=9bd0b91866) | Aug 29, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [205286a7e8](https://linux-hardware.org/?probe=205286a7e8) | Aug 29, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [861e741d6a](https://linux-hardware.org/?probe=861e741d6a) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [09ed405682](https://linux-hardware.org/?probe=09ed405682) | Aug 29, 2023 |
| ASUSTek       | STRIX B250G GAMING          | Desktop     | [16d3d84013](https://linux-hardware.org/?probe=16d3d84013) | Aug 29, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [6bd291c8b0](https://linux-hardware.org/?probe=6bd291c8b0) | Aug 29, 2023 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [e0d36eed9a](https://linux-hardware.org/?probe=e0d36eed9a) | Aug 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [59cfa4ea58](https://linux-hardware.org/?probe=59cfa4ea58) | Aug 29, 2023 |
| Timi          | A34S                        | Notebook    | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| Huanan        | X99-ZD4 V2.1                | Desktop     | [2ab7a21e20](https://linux-hardware.org/?probe=2ab7a21e20) | Aug 29, 2023 |
| ASUSTek       | M3N78-EH                    | Desktop     | [c0fb869905](https://linux-hardware.org/?probe=c0fb869905) | Aug 29, 2023 |
| HP            | ProBook 430 G4 NOTEBOOK ... | Notebook    | [6ee102c046](https://linux-hardware.org/?probe=6ee102c046) | Aug 28, 2023 |
| Gigabyte      | 8IPE1000                    | Desktop     | [50a9455c00](https://linux-hardware.org/?probe=50a9455c00) | Aug 28, 2023 |
| MSI           | 770-C45                     | Desktop     | [6f52d0be24](https://linux-hardware.org/?probe=6f52d0be24) | Aug 28, 2023 |
| Gigabyte      | 8IPE1000                    | Desktop     | [eb4740694a](https://linux-hardware.org/?probe=eb4740694a) | Aug 28, 2023 |
| Supermicro    | X8DAH                       | Server      | [212e13684b](https://linux-hardware.org/?probe=212e13684b) | Aug 28, 2023 |
| Supermicro    | X8DTU                       | Server      | [cd21e7a0c4](https://linux-hardware.org/?probe=cd21e7a0c4) | Aug 28, 2023 |
| Supermicro    | X8DTU                       | Server      | [92730a1996](https://linux-hardware.org/?probe=92730a1996) | Aug 28, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [3883cc4a8a](https://linux-hardware.org/?probe=3883cc4a8a) | Aug 28, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [d79a840057](https://linux-hardware.org/?probe=d79a840057) | Aug 28, 2023 |
| Supermicro    | X8DTL                       | Server      | [7b9e15fe6a](https://linux-hardware.org/?probe=7b9e15fe6a) | Aug 28, 2023 |
| Supermicro    | X8DTU                       | Server      | [6d0fc7c8d2](https://linux-hardware.org/?probe=6d0fc7c8d2) | Aug 28, 2023 |
| Supermicro    | X8DTT                       | Server      | [d16e11aed8](https://linux-hardware.org/?probe=d16e11aed8) | Aug 28, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [6c232e36c3](https://linux-hardware.org/?probe=6c232e36c3) | Aug 28, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [c823f63fd6](https://linux-hardware.org/?probe=c823f63fd6) | Aug 28, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [a102cdc504](https://linux-hardware.org/?probe=a102cdc504) | Aug 28, 2023 |
| Dell          | 068CDY A01                  | Server      | [1debff900a](https://linux-hardware.org/?probe=1debff900a) | Aug 28, 2023 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [b2bc9269e5](https://linux-hardware.org/?probe=b2bc9269e5) | Aug 28, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [7c1198413a](https://linux-hardware.org/?probe=7c1198413a) | Aug 28, 2023 |
| ICL           | S1511 G1R                   | Notebook    | [421df1df8d](https://linux-hardware.org/?probe=421df1df8d) | Aug 28, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [c6614846b5](https://linux-hardware.org/?probe=c6614846b5) | Aug 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [9d90b80d9a](https://linux-hardware.org/?probe=9d90b80d9a) | Aug 27, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [ad478d48ad](https://linux-hardware.org/?probe=ad478d48ad) | Aug 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4e7e2a9946](https://linux-hardware.org/?probe=4e7e2a9946) | Aug 27, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [14d4e6bf4c](https://linux-hardware.org/?probe=14d4e6bf4c) | Aug 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a3a1e805b2](https://linux-hardware.org/?probe=a3a1e805b2) | Aug 27, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [b21ba1741e](https://linux-hardware.org/?probe=b21ba1741e) | Aug 27, 2023 |
| ASUSTek       | K42DY                       | Notebook    | [5a9171654b](https://linux-hardware.org/?probe=5a9171654b) | Aug 27, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [dfc1f52af5](https://linux-hardware.org/?probe=dfc1f52af5) | Aug 27, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1f59c17089](https://linux-hardware.org/?probe=1f59c17089) | Aug 27, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [ca9ccf934d](https://linux-hardware.org/?probe=ca9ccf934d) | Aug 27, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [5ad490f8cb](https://linux-hardware.org/?probe=5ad490f8cb) | Aug 27, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [ee07c69165](https://linux-hardware.org/?probe=ee07c69165) | Aug 27, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [173b99bf55](https://linux-hardware.org/?probe=173b99bf55) | Aug 27, 2023 |
| ASRock        | N68PV-GS                    | Desktop     | [d9171bedd5](https://linux-hardware.org/?probe=d9171bedd5) | Aug 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [4d432af6c0](https://linux-hardware.org/?probe=4d432af6c0) | Aug 27, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [3efec986ee](https://linux-hardware.org/?probe=3efec986ee) | Aug 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [eadc869c4b](https://linux-hardware.org/?probe=eadc869c4b) | Aug 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [c675cc9767](https://linux-hardware.org/?probe=c675cc9767) | Aug 27, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [75836d26df](https://linux-hardware.org/?probe=75836d26df) | Aug 26, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [c0480c060a](https://linux-hardware.org/?probe=c0480c060a) | Aug 26, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [a869037c97](https://linux-hardware.org/?probe=a869037c97) | Aug 26, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [df0bcd69ff](https://linux-hardware.org/?probe=df0bcd69ff) | Aug 26, 2023 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [c9505b94ed](https://linux-hardware.org/?probe=c9505b94ed) | Aug 26, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [aa3b7fe20f](https://linux-hardware.org/?probe=aa3b7fe20f) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1f606cb9da](https://linux-hardware.org/?probe=1f606cb9da) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8f033793a9](https://linux-hardware.org/?probe=8f033793a9) | Aug 26, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [3601cce38e](https://linux-hardware.org/?probe=3601cce38e) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0e107ac9bb](https://linux-hardware.org/?probe=0e107ac9bb) | Aug 26, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [a305956d47](https://linux-hardware.org/?probe=a305956d47) | Aug 26, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [5ca33a6111](https://linux-hardware.org/?probe=5ca33a6111) | Aug 26, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [5d4b85d28b](https://linux-hardware.org/?probe=5d4b85d28b) | Aug 26, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [088ef87d1b](https://linux-hardware.org/?probe=088ef87d1b) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [e0989b8f9e](https://linux-hardware.org/?probe=e0989b8f9e) | Aug 25, 2023 |
| ZOTAC         | ZBOX-MI531/MI551/MI571 R... | Mini pc     | [aec073fccb](https://linux-hardware.org/?probe=aec073fccb) | Aug 25, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fd03f60906](https://linux-hardware.org/?probe=fd03f60906) | Aug 25, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [916bceacca](https://linux-hardware.org/?probe=916bceacca) | Aug 25, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [aa3de32445](https://linux-hardware.org/?probe=aa3de32445) | Aug 25, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b328603445](https://linux-hardware.org/?probe=b328603445) | Aug 25, 2023 |
| ASRock        | M3N78D                      | Desktop     | [cbaee686c2](https://linux-hardware.org/?probe=cbaee686c2) | Aug 25, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [5f24b13b35](https://linux-hardware.org/?probe=5f24b13b35) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [a5812138d3](https://linux-hardware.org/?probe=a5812138d3) | Aug 25, 2023 |
| ASUSTek       | M4N78 SE                    | Desktop     | [aff07fea82](https://linux-hardware.org/?probe=aff07fea82) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [3ce0d3817d](https://linux-hardware.org/?probe=3ce0d3817d) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [2f5a204e94](https://linux-hardware.org/?probe=2f5a204e94) | Aug 25, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [825725cf8d](https://linux-hardware.org/?probe=825725cf8d) | Aug 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [84ef801923](https://linux-hardware.org/?probe=84ef801923) | Aug 24, 2023 |
| Intel         | D2700DC AAG32420-602        | Desktop     | [d3743d52fa](https://linux-hardware.org/?probe=d3743d52fa) | Aug 24, 2023 |
| HP            | 635                         | Notebook    | [4c35f9ca58](https://linux-hardware.org/?probe=4c35f9ca58) | Aug 24, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [298355e334](https://linux-hardware.org/?probe=298355e334) | Aug 24, 2023 |
| Unknown       | Unknown                     | Phone       | [fa01e31d06](https://linux-hardware.org/?probe=fa01e31d06) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge E120 3043A... | Notebook    | [14d6dcc28e](https://linux-hardware.org/?probe=14d6dcc28e) | Aug 24, 2023 |
| Rockchip      | RK3568 EVB1 DDR4 V10        | Soc         | [846c733ed7](https://linux-hardware.org/?probe=846c733ed7) | Aug 24, 2023 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [2436229edb](https://linux-hardware.org/?probe=2436229edb) | Aug 24, 2023 |
| Intel         | D2700DC AAG32420-602        | Desktop     | [3381b3de96](https://linux-hardware.org/?probe=3381b3de96) | Aug 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [9d09e14624](https://linux-hardware.org/?probe=9d09e14624) | Aug 24, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [4ec7353bd2](https://linux-hardware.org/?probe=4ec7353bd2) | Aug 24, 2023 |
| Digma         | Pro Fortis M DN15P7-ADXW... | Notebook    | [8b2a8a66d0](https://linux-hardware.org/?probe=8b2a8a66d0) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [4953513629](https://linux-hardware.org/?probe=4953513629) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [ca7dfec56f](https://linux-hardware.org/?probe=ca7dfec56f) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [14a41c3719](https://linux-hardware.org/?probe=14a41c3719) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [a60dcbf314](https://linux-hardware.org/?probe=a60dcbf314) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [a8b60e35a5](https://linux-hardware.org/?probe=a8b60e35a5) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [1e1f8d3969](https://linux-hardware.org/?probe=1e1f8d3969) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [bcd724308d](https://linux-hardware.org/?probe=bcd724308d) | Aug 24, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [28cc19809a](https://linux-hardware.org/?probe=28cc19809a) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [b96cc7270e](https://linux-hardware.org/?probe=b96cc7270e) | Aug 24, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [083700ba74](https://linux-hardware.org/?probe=083700ba74) | Aug 23, 2023 |
| ASRock        | M3N78D                      | Desktop     | [86e93b6cec](https://linux-hardware.org/?probe=86e93b6cec) | Aug 23, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [15c7624753](https://linux-hardware.org/?probe=15c7624753) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| ASRock        | P4i945GC                    | Desktop     | [5fd422ae68](https://linux-hardware.org/?probe=5fd422ae68) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [061ecf9479](https://linux-hardware.org/?probe=061ecf9479) | Aug 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0228bd6d42](https://linux-hardware.org/?probe=0228bd6d42) | Aug 23, 2023 |
| Digma         | Pro Fortis M DN15P7-ADXW... | Notebook    | [400fb89d1d](https://linux-hardware.org/?probe=400fb89d1d) | Aug 23, 2023 |
| AZW           | SER V01                     | Mini pc     | [035a23669b](https://linux-hardware.org/?probe=035a23669b) | Aug 23, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [2889ef1f56](https://linux-hardware.org/?probe=2889ef1f56) | Aug 23, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [01beb6bf37](https://linux-hardware.org/?probe=01beb6bf37) | Aug 23, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| ANCOMP        | LearnMate A15-501           | Notebook    | [f886cf8a23](https://linux-hardware.org/?probe=f886cf8a23) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| Biostar       | A68MHE                      | Desktop     | [3ff360b5c5](https://linux-hardware.org/?probe=3ff360b5c5) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | Notebook    | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| Yadro Clie... | KVADRA LE15T                | Notebook    | [985b61f2b2](https://linux-hardware.org/?probe=985b61f2b2) | Aug 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1510eba46f](https://linux-hardware.org/?probe=1510eba46f) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e3c7a7a5b3](https://linux-hardware.org/?probe=e3c7a7a5b3) | Aug 22, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [297d07a2e3](https://linux-hardware.org/?probe=297d07a2e3) | Aug 22, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [64f3da359d](https://linux-hardware.org/?probe=64f3da359d) | Aug 22, 2023 |
| COLORFUL      | X15 XS 22                   | Notebook    | [2e8aa13f76](https://linux-hardware.org/?probe=2e8aa13f76) | Aug 22, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [10a345d2ef](https://linux-hardware.org/?probe=10a345d2ef) | Aug 22, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [df34a2b0db](https://linux-hardware.org/?probe=df34a2b0db) | Aug 22, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [c8aa8973a4](https://linux-hardware.org/?probe=c8aa8973a4) | Aug 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [a83e32b89c](https://linux-hardware.org/?probe=a83e32b89c) | Aug 22, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [82b421a678](https://linux-hardware.org/?probe=82b421a678) | Aug 22, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [6ca5d6cce7](https://linux-hardware.org/?probe=6ca5d6cce7) | Aug 22, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [d3b3052832](https://linux-hardware.org/?probe=d3b3052832) | Aug 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [39fa23e4b7](https://linux-hardware.org/?probe=39fa23e4b7) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [cb2839d263](https://linux-hardware.org/?probe=cb2839d263) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [af048c393b](https://linux-hardware.org/?probe=af048c393b) | Aug 22, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [e405022cc9](https://linux-hardware.org/?probe=e405022cc9) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [60c353baa1](https://linux-hardware.org/?probe=60c353baa1) | Aug 22, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [7687b9e74a](https://linux-hardware.org/?probe=7687b9e74a) | Aug 22, 2023 |
| Irbis         | NB123                       | Notebook    | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [01ee3a9784](https://linux-hardware.org/?probe=01ee3a9784) | Aug 21, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e06223da9](https://linux-hardware.org/?probe=2e06223da9) | Aug 21, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [191c724d49](https://linux-hardware.org/?probe=191c724d49) | Aug 21, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [c3207e25fd](https://linux-hardware.org/?probe=c3207e25fd) | Aug 21, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| WeiBu         | H310CX1B V1.0               | Desktop     | [b3ec8e66ae](https://linux-hardware.org/?probe=b3ec8e66ae) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [3bea77516f](https://linux-hardware.org/?probe=3bea77516f) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | Notebook    | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [41ba06b203](https://linux-hardware.org/?probe=41ba06b203) | Aug 21, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [3d706eb2f3](https://linux-hardware.org/?probe=3d706eb2f3) | Aug 21, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [7993a53688](https://linux-hardware.org/?probe=7993a53688) | Aug 21, 2023 |
| HP            | EliteBook 835 13 inch G9... | Notebook    | [f973c9678d](https://linux-hardware.org/?probe=f973c9678d) | Aug 20, 2023 |
| Intel         | X99                         | Desktop     | [c1ad35e185](https://linux-hardware.org/?probe=c1ad35e185) | Aug 20, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [e784b29438](https://linux-hardware.org/?probe=e784b29438) | Aug 20, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [30f233a018](https://linux-hardware.org/?probe=30f233a018) | Aug 20, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [e4c7b8207c](https://linux-hardware.org/?probe=e4c7b8207c) | Aug 20, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [bc9275cc73](https://linux-hardware.org/?probe=bc9275cc73) | Aug 20, 2023 |
| Intel         | X99                         | Desktop     | [3f141e2bd1](https://linux-hardware.org/?probe=3f141e2bd1) | Aug 20, 2023 |
| Dell          | Inspiron 11-3157            | Notebook    | [eae8586474](https://linux-hardware.org/?probe=eae8586474) | Aug 20, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [581265dcb6](https://linux-hardware.org/?probe=581265dcb6) | Aug 20, 2023 |
| Lenovo        | H420                        | Desktop     | [0741adee29](https://linux-hardware.org/?probe=0741adee29) | Aug 20, 2023 |
| HP            | Laptop 17-by1xxx            | Notebook    | [658e65bba8](https://linux-hardware.org/?probe=658e65bba8) | Aug 20, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [11d699cccd](https://linux-hardware.org/?probe=11d699cccd) | Aug 20, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [d8fd2a6d98](https://linux-hardware.org/?probe=d8fd2a6d98) | Aug 20, 2023 |
| ROMBICA       | myBook Eclipse              | Notebook    | [01efda8d0a](https://linux-hardware.org/?probe=01efda8d0a) | Aug 20, 2023 |
| ASUSTek       | P5P41D                      | Desktop     | [4ccbd3e19e](https://linux-hardware.org/?probe=4ccbd3e19e) | Aug 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [8d8d50eabc](https://linux-hardware.org/?probe=8d8d50eabc) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [b0580e41dc](https://linux-hardware.org/?probe=b0580e41dc) | Aug 20, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a3dc3ffc3b](https://linux-hardware.org/?probe=a3dc3ffc3b) | Aug 20, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [12f3b0d269](https://linux-hardware.org/?probe=12f3b0d269) | Aug 20, 2023 |
| Infomash      | RoverBook                   | Notebook    | [a105ac22d7](https://linux-hardware.org/?probe=a105ac22d7) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| Lenovo        | H420                        | Desktop     | [ef44de6298](https://linux-hardware.org/?probe=ef44de6298) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [8838204e5f](https://linux-hardware.org/?probe=8838204e5f) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [398280327e](https://linux-hardware.org/?probe=398280327e) | Aug 19, 2023 |
| Intel         | X99                         | Desktop     | [e16fe5b0f3](https://linux-hardware.org/?probe=e16fe5b0f3) | Aug 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [c6a4bc6b75](https://linux-hardware.org/?probe=c6a4bc6b75) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [dc1060bc0d](https://linux-hardware.org/?probe=dc1060bc0d) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [74c4c66eba](https://linux-hardware.org/?probe=74c4c66eba) | Aug 19, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [34a23c836c](https://linux-hardware.org/?probe=34a23c836c) | Aug 19, 2023 |
| Notebook      | WA50SRQ                     | Notebook    | [615e7be12b](https://linux-hardware.org/?probe=615e7be12b) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [36417c2601](https://linux-hardware.org/?probe=36417c2601) | Aug 19, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [ed572b9b04](https://linux-hardware.org/?probe=ed572b9b04) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [81dd9b9a7a](https://linux-hardware.org/?probe=81dd9b9a7a) | Aug 19, 2023 |
| K-Systems     | Unknown                     | Desktop     | [52ff91dc03](https://linux-hardware.org/?probe=52ff91dc03) | Aug 19, 2023 |
| HP            | 630                         | Notebook    | [ad9f585249](https://linux-hardware.org/?probe=ad9f585249) | Aug 19, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [651f263a9d](https://linux-hardware.org/?probe=651f263a9d) | Aug 19, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [ac85dd7bb4](https://linux-hardware.org/?probe=ac85dd7bb4) | Aug 19, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [8af741a2c4](https://linux-hardware.org/?probe=8af741a2c4) | Aug 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6a0b53d7c1](https://linux-hardware.org/?probe=6a0b53d7c1) | Aug 18, 2023 |
| Supermicro    | X8DTU                       | Server      | [e29948351c](https://linux-hardware.org/?probe=e29948351c) | Aug 18, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [9b7cf0384c](https://linux-hardware.org/?probe=9b7cf0384c) | Aug 18, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [767b42eeca](https://linux-hardware.org/?probe=767b42eeca) | Aug 18, 2023 |
| Notebook      | WA50SRQ                     | Notebook    | [5970fa0344](https://linux-hardware.org/?probe=5970fa0344) | Aug 18, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [12c6ae9006](https://linux-hardware.org/?probe=12c6ae9006) | Aug 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [097825338b](https://linux-hardware.org/?probe=097825338b) | Aug 18, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [7a9ae970e6](https://linux-hardware.org/?probe=7a9ae970e6) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7911ff1df6](https://linux-hardware.org/?probe=7911ff1df6) | Aug 18, 2023 |
| ANCOMP        | LearnMate A15-501           | Notebook    | [cf541ae2bd](https://linux-hardware.org/?probe=cf541ae2bd) | Aug 18, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [0a2d342da5](https://linux-hardware.org/?probe=0a2d342da5) | Aug 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [2de4fc4556](https://linux-hardware.org/?probe=2de4fc4556) | Aug 18, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [b83a6ac1b7](https://linux-hardware.org/?probe=b83a6ac1b7) | Aug 18, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [98b50f195d](https://linux-hardware.org/?probe=98b50f195d) | Aug 18, 2023 |
| Biostar       | A68MHE                      | Desktop     | [0c88bf33f4](https://linux-hardware.org/?probe=0c88bf33f4) | Aug 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [83dfd08b75](https://linux-hardware.org/?probe=83dfd08b75) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [88076446b3](https://linux-hardware.org/?probe=88076446b3) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [201a0612e4](https://linux-hardware.org/?probe=201a0612e4) | Aug 18, 2023 |
| MSI           | MS-1057                     | Notebook    | [081ae63942](https://linux-hardware.org/?probe=081ae63942) | Aug 18, 2023 |
| MSI           | MS-1057                     | Notebook    | [615f03f3b8](https://linux-hardware.org/?probe=615f03f3b8) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [085d83c79a](https://linux-hardware.org/?probe=085d83c79a) | Aug 17, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [dbe8d496ac](https://linux-hardware.org/?probe=dbe8d496ac) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [54a5786749](https://linux-hardware.org/?probe=54a5786749) | Aug 17, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [e2078f93dd](https://linux-hardware.org/?probe=e2078f93dd) | Aug 17, 2023 |
| Positivo      | N6440                       | Notebook    | [66e9ee4711](https://linux-hardware.org/?probe=66e9ee4711) | Aug 17, 2023 |
| Sony          | VGN-NW2SRF_S                | Notebook    | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| Positivo      | N6440                       | Notebook    | [3516f8d728](https://linux-hardware.org/?probe=3516f8d728) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [4b8894823c](https://linux-hardware.org/?probe=4b8894823c) | Aug 17, 2023 |
| Supermicro    | X8DTU                       | Server      | [2633eb78a6](https://linux-hardware.org/?probe=2633eb78a6) | Aug 17, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [eb0dd75419](https://linux-hardware.org/?probe=eb0dd75419) | Aug 17, 2023 |
| Intel         | X99H                        | Desktop     | [ee1fff7602](https://linux-hardware.org/?probe=ee1fff7602) | Aug 17, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [31165e8a73](https://linux-hardware.org/?probe=31165e8a73) | Aug 17, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1bca67f78b](https://linux-hardware.org/?probe=1bca67f78b) | Aug 17, 2023 |
| Supermicro    | X8DTU                       | Server      | [16c5e53f8a](https://linux-hardware.org/?probe=16c5e53f8a) | Aug 17, 2023 |
| Supermicro    | X9DRW                       | Server      | [e8f79a0ff8](https://linux-hardware.org/?probe=e8f79a0ff8) | Aug 17, 2023 |
| Supermicro    | X8DTL                       | Server      | [860b0959e6](https://linux-hardware.org/?probe=860b0959e6) | Aug 17, 2023 |
| Supermicro    | X8DTU                       | Server      | [696b0ae5a9](https://linux-hardware.org/?probe=696b0ae5a9) | Aug 17, 2023 |
| Supermicro    | X8DTT                       | Server      | [3991283a38](https://linux-hardware.org/?probe=3991283a38) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | Notebook    | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cfe21994b6](https://linux-hardware.org/?probe=cfe21994b6) | Aug 17, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Sony          | VAIO                        | All in one  | [7478d42db4](https://linux-hardware.org/?probe=7478d42db4) | Aug 17, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [98629bd8c4](https://linux-hardware.org/?probe=98629bd8c4) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | Notebook    | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [f69a3b4363](https://linux-hardware.org/?probe=f69a3b4363) | Aug 17, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [fe8d01fa26](https://linux-hardware.org/?probe=fe8d01fa26) | Aug 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [8933be3bc7](https://linux-hardware.org/?probe=8933be3bc7) | Aug 16, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [131eb14e26](https://linux-hardware.org/?probe=131eb14e26) | Aug 16, 2023 |
| Supermicro    | X8DTU                       | Server      | [674ea9e9f1](https://linux-hardware.org/?probe=674ea9e9f1) | Aug 16, 2023 |
| Gigabyte      | 965P-S3                     | Desktop     | [d9557da16c](https://linux-hardware.org/?probe=d9557da16c) | Aug 16, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [af4abf9f1d](https://linux-hardware.org/?probe=af4abf9f1d) | Aug 16, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [26b07a9b9c](https://linux-hardware.org/?probe=26b07a9b9c) | Aug 16, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [8e3f72e46d](https://linux-hardware.org/?probe=8e3f72e46d) | Aug 16, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [4e25d8ef9f](https://linux-hardware.org/?probe=4e25d8ef9f) | Aug 16, 2023 |
| Timi          | A35S                        | Notebook    | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [25279b238a](https://linux-hardware.org/?probe=25279b238a) | Aug 16, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [ea88be85a3](https://linux-hardware.org/?probe=ea88be85a3) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| MSI           | X460/X460DX                 | Notebook    | [2e5d1c9b46](https://linux-hardware.org/?probe=2e5d1c9b46) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [f0d325d7d3](https://linux-hardware.org/?probe=f0d325d7d3) | Aug 15, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [7052cd45dc](https://linux-hardware.org/?probe=7052cd45dc) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [632e853b38](https://linux-hardware.org/?probe=632e853b38) | Aug 15, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | Notebook    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [e1d0ef3bb8](https://linux-hardware.org/?probe=e1d0ef3bb8) | Aug 15, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [8d6a3e990c](https://linux-hardware.org/?probe=8d6a3e990c) | Aug 15, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [0fdb533afb](https://linux-hardware.org/?probe=0fdb533afb) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [ac6dd63085](https://linux-hardware.org/?probe=ac6dd63085) | Aug 15, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [3156a63d06](https://linux-hardware.org/?probe=3156a63d06) | Aug 15, 2023 |
| Supermicro    | X10DRH-i                    | Server      | [fe5b74afef](https://linux-hardware.org/?probe=fe5b74afef) | Aug 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [0d21b420ac](https://linux-hardware.org/?probe=0d21b420ac) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6c933602ca](https://linux-hardware.org/?probe=6c933602ca) | Aug 15, 2023 |
| HP            | 1495                        | Desktop     | [d038a45bbd](https://linux-hardware.org/?probe=d038a45bbd) | Aug 15, 2023 |
| Supermicro    | X12SDV-16C-SPT8FA           | Server      | [54a4e7c93e](https://linux-hardware.org/?probe=54a4e7c93e) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [a395628119](https://linux-hardware.org/?probe=a395628119) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [618b4d5598](https://linux-hardware.org/?probe=618b4d5598) | Aug 15, 2023 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [fd38ce192c](https://linux-hardware.org/?probe=fd38ce192c) | Aug 15, 2023 |
| Dell          | Studio 1735                 | Notebook    | [ff082d7af8](https://linux-hardware.org/?probe=ff082d7af8) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [52bd9574d8](https://linux-hardware.org/?probe=52bd9574d8) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f4ba515a8d](https://linux-hardware.org/?probe=f4ba515a8d) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [2473d1c807](https://linux-hardware.org/?probe=2473d1c807) | Aug 14, 2023 |
| ASRock        | G41C-GS R2.0                | Desktop     | [82d639b155](https://linux-hardware.org/?probe=82d639b155) | Aug 14, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [63c0e75955](https://linux-hardware.org/?probe=63c0e75955) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [85ce620e44](https://linux-hardware.org/?probe=85ce620e44) | Aug 14, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [4062060fba](https://linux-hardware.org/?probe=4062060fba) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [74eb1759e1](https://linux-hardware.org/?probe=74eb1759e1) | Aug 14, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [64c547a12b](https://linux-hardware.org/?probe=64c547a12b) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [1d96e3b473](https://linux-hardware.org/?probe=1d96e3b473) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ECS           | G41T-M2                     | Desktop     | [b67afe5845](https://linux-hardware.org/?probe=b67afe5845) | Aug 13, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d11f1184c5](https://linux-hardware.org/?probe=d11f1184c5) | Aug 13, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | Desktop     | [ccaf390b87](https://linux-hardware.org/?probe=ccaf390b87) | Aug 13, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [e0b2f87734](https://linux-hardware.org/?probe=e0b2f87734) | Aug 13, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | Desktop     | [aeee4a0b68](https://linux-hardware.org/?probe=aeee4a0b68) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [aa5cd42803](https://linux-hardware.org/?probe=aa5cd42803) | Aug 13, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [823d437123](https://linux-hardware.org/?probe=823d437123) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | Notebook    | [f709dd85f7](https://linux-hardware.org/?probe=f709dd85f7) | Aug 13, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [788c2c9e31](https://linux-hardware.org/?probe=788c2c9e31) | Aug 12, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [1f86102443](https://linux-hardware.org/?probe=1f86102443) | Aug 12, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [8599cd2ad3](https://linux-hardware.org/?probe=8599cd2ad3) | Aug 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ae8c13e17e](https://linux-hardware.org/?probe=ae8c13e17e) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7d7349fef7](https://linux-hardware.org/?probe=7d7349fef7) | Aug 12, 2023 |
| Irbis         | NB264                       | Notebook    | [ed38bccd6d](https://linux-hardware.org/?probe=ed38bccd6d) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| MSI           | P67A-GD65                   | Desktop     | [1024e95ca9](https://linux-hardware.org/?probe=1024e95ca9) | Aug 12, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [f57a3e9f6a](https://linux-hardware.org/?probe=f57a3e9f6a) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [24d6504b2c](https://linux-hardware.org/?probe=24d6504b2c) | Aug 12, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b80181bc47](https://linux-hardware.org/?probe=b80181bc47) | Aug 12, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [96995d7026](https://linux-hardware.org/?probe=96995d7026) | Aug 12, 2023 |
| HP            | ENVY Notebook               | Notebook    | [24c2810def](https://linux-hardware.org/?probe=24c2810def) | Aug 12, 2023 |
| Lenovo        | PIQY0                       | Notebook    | [0149927d91](https://linux-hardware.org/?probe=0149927d91) | Aug 11, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [c2d9d3160b](https://linux-hardware.org/?probe=c2d9d3160b) | Aug 11, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [8ad81394c8](https://linux-hardware.org/?probe=8ad81394c8) | Aug 11, 2023 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [e0fa5039b4](https://linux-hardware.org/?probe=e0fa5039b4) | Aug 11, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [2805e140b5](https://linux-hardware.org/?probe=2805e140b5) | Aug 11, 2023 |
| HP            | ENVY Notebook               | Notebook    | [6327abde35](https://linux-hardware.org/?probe=6327abde35) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [a4a009cd79](https://linux-hardware.org/?probe=a4a009cd79) | Aug 11, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0f7859844f](https://linux-hardware.org/?probe=0f7859844f) | Aug 11, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [262bb059eb](https://linux-hardware.org/?probe=262bb059eb) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [e32bb1bbb2](https://linux-hardware.org/?probe=e32bb1bbb2) | Aug 11, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [d8d7d7bad7](https://linux-hardware.org/?probe=d8d7d7bad7) | Aug 11, 2023 |
| Acer          | Extensa 2511G               | Notebook    | [536699834a](https://linux-hardware.org/?probe=536699834a) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [c9b1265a23](https://linux-hardware.org/?probe=c9b1265a23) | Aug 11, 2023 |
| MSI           | G33M                        | Desktop     | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [1dc2c421f8](https://linux-hardware.org/?probe=1dc2c421f8) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [cc7efa7eba](https://linux-hardware.org/?probe=cc7efa7eba) | Aug 11, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f028b8f65d](https://linux-hardware.org/?probe=f028b8f65d) | Aug 11, 2023 |
| HP            | 84DE                        | All in one  | [bdd2e74d54](https://linux-hardware.org/?probe=bdd2e74d54) | Aug 11, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [07e0bad7da](https://linux-hardware.org/?probe=07e0bad7da) | Aug 10, 2023 |
| Aquarius P... | MBM                         | Soc         | [09d0d96e92](https://linux-hardware.org/?probe=09d0d96e92) | Aug 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3de983a470](https://linux-hardware.org/?probe=3de983a470) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [6f80191c4a](https://linux-hardware.org/?probe=6f80191c4a) | Aug 10, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [26597d8a51](https://linux-hardware.org/?probe=26597d8a51) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| Acer          | Extensa 5630                | Notebook    | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Lenovo        | H420                        | Desktop     | [d418e9d1d1](https://linux-hardware.org/?probe=d418e9d1d1) | Aug 10, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [6c4354fa1c](https://linux-hardware.org/?probe=6c4354fa1c) | Aug 10, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [584a47e4ae](https://linux-hardware.org/?probe=584a47e4ae) | Aug 10, 2023 |
| HP            | ENVY Notebook               | Notebook    | [9e8624aa8d](https://linux-hardware.org/?probe=9e8624aa8d) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [204b2fa0a0](https://linux-hardware.org/?probe=204b2fa0a0) | Aug 09, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [18ace46778](https://linux-hardware.org/?probe=18ace46778) | Aug 09, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [6fc4589ff0](https://linux-hardware.org/?probe=6fc4589ff0) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [6ea2dae05b](https://linux-hardware.org/?probe=6ea2dae05b) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [1c9d71f553](https://linux-hardware.org/?probe=1c9d71f553) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [47da29a7a0](https://linux-hardware.org/?probe=47da29a7a0) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [d464f66e20](https://linux-hardware.org/?probe=d464f66e20) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [9f725868e8](https://linux-hardware.org/?probe=9f725868e8) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [dd82024730](https://linux-hardware.org/?probe=dd82024730) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [11d70c86e3](https://linux-hardware.org/?probe=11d70c86e3) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [1b3e4092b5](https://linux-hardware.org/?probe=1b3e4092b5) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [92f521b3e8](https://linux-hardware.org/?probe=92f521b3e8) | Aug 09, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [e6cc7a97b6](https://linux-hardware.org/?probe=e6cc7a97b6) | Aug 09, 2023 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [52ff19e47c](https://linux-hardware.org/?probe=52ff19e47c) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [70765ac17b](https://linux-hardware.org/?probe=70765ac17b) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a43111576a](https://linux-hardware.org/?probe=a43111576a) | Aug 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [8636764a35](https://linux-hardware.org/?probe=8636764a35) | Aug 09, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [253c6295e0](https://linux-hardware.org/?probe=253c6295e0) | Aug 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [9326dd9736](https://linux-hardware.org/?probe=9326dd9736) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [5911a0289e](https://linux-hardware.org/?probe=5911a0289e) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [62d3166469](https://linux-hardware.org/?probe=62d3166469) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [4b7e9a8b93](https://linux-hardware.org/?probe=4b7e9a8b93) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| Unknown       | Unknown                     | Soc         | [42d4093f63](https://linux-hardware.org/?probe=42d4093f63) | Aug 08, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| ASUSTek       | X501U                       | Notebook    | [1cd218236c](https://linux-hardware.org/?probe=1cd218236c) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [42b79d59b6](https://linux-hardware.org/?probe=42b79d59b6) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [0503a83389](https://linux-hardware.org/?probe=0503a83389) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [29e048b78b](https://linux-hardware.org/?probe=29e048b78b) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [9183ba34b1](https://linux-hardware.org/?probe=9183ba34b1) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [f07e24722e](https://linux-hardware.org/?probe=f07e24722e) | Aug 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [42303ab8af](https://linux-hardware.org/?probe=42303ab8af) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [f26c990dc3](https://linux-hardware.org/?probe=f26c990dc3) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [f190fa8e05](https://linux-hardware.org/?probe=f190fa8e05) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [183e9d899a](https://linux-hardware.org/?probe=183e9d899a) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [33d78efc8a](https://linux-hardware.org/?probe=33d78efc8a) | Aug 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [7053bcfeac](https://linux-hardware.org/?probe=7053bcfeac) | Aug 08, 2023 |
| MSI           | H61M-P31                    | Desktop     | [3fa41aaf62](https://linux-hardware.org/?probe=3fa41aaf62) | Aug 08, 2023 |
| Dell          | Precision M4700             | Notebook    | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| HP            | ENVY Notebook               | Notebook    | [9c6d8ac7f9](https://linux-hardware.org/?probe=9c6d8ac7f9) | Aug 08, 2023 |
| Dell          | Latitude 5511               | Notebook    | [e9ea435e85](https://linux-hardware.org/?probe=e9ea435e85) | Aug 08, 2023 |
| MSI           | H97M-G43                    | Desktop     | [f8905cffe2](https://linux-hardware.org/?probe=f8905cffe2) | Aug 08, 2023 |
| Supermicro    | X11DDW-L                    | Server      | [d6fe66b73c](https://linux-hardware.org/?probe=d6fe66b73c) | Aug 08, 2023 |
| Supermicro    | X9DRW                       | Server      | [007ab23cd1](https://linux-hardware.org/?probe=007ab23cd1) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [d292db651b](https://linux-hardware.org/?probe=d292db651b) | Aug 08, 2023 |
| Acer          | Extensa 215-51K             | Notebook    | [27a26187b9](https://linux-hardware.org/?probe=27a26187b9) | Aug 08, 2023 |
| HP            | Presario CQ58               | Notebook    | [07f5cdfaa8](https://linux-hardware.org/?probe=07f5cdfaa8) | Aug 08, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [305061b67e](https://linux-hardware.org/?probe=305061b67e) | Aug 08, 2023 |
| Samsung       | R528/R728                   | Notebook    | [cc6458fab9](https://linux-hardware.org/?probe=cc6458fab9) | Aug 08, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [04962a5072](https://linux-hardware.org/?probe=04962a5072) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | Notebook    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [eff926e4a9](https://linux-hardware.org/?probe=eff926e4a9) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | Notebook    | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| ASUSTek       | X751NV                      | Notebook    | [ff33d23814](https://linux-hardware.org/?probe=ff33d23814) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [bd036e1e65](https://linux-hardware.org/?probe=bd036e1e65) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [dbefafc94d](https://linux-hardware.org/?probe=dbefafc94d) | Aug 07, 2023 |
| Soyo          | SY-Classic B450M            | Desktop     | [708e9837c5](https://linux-hardware.org/?probe=708e9837c5) | Aug 07, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [209b568765](https://linux-hardware.org/?probe=209b568765) | Aug 07, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [71b00682fc](https://linux-hardware.org/?probe=71b00682fc) | Aug 07, 2023 |
| Intel         | S3420GPV E80883-106         | Server      | [3ed0bb462d](https://linux-hardware.org/?probe=3ed0bb462d) | Aug 07, 2023 |
| Supermicro    | X8DTU-LN4+                  | Server      | [4e56bb1720](https://linux-hardware.org/?probe=4e56bb1720) | Aug 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [52c9bb6c33](https://linux-hardware.org/?probe=52c9bb6c33) | Aug 06, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [667b258dd5](https://linux-hardware.org/?probe=667b258dd5) | Aug 06, 2023 |
| ASUSTek       | UX32VD                      | Notebook    | [298a3261a0](https://linux-hardware.org/?probe=298a3261a0) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [baf3a83d91](https://linux-hardware.org/?probe=baf3a83d91) | Aug 06, 2023 |
| Soyo          | SY-Classic B450M            | Desktop     | [04a850b33b](https://linux-hardware.org/?probe=04a850b33b) | Aug 06, 2023 |
| Timi          | TM1701                      | Notebook    | [2fc0a44940](https://linux-hardware.org/?probe=2fc0a44940) | Aug 06, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [0a99f6f654](https://linux-hardware.org/?probe=0a99f6f654) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [23298de8c1](https://linux-hardware.org/?probe=23298de8c1) | Aug 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [6bf7b7dc2b](https://linux-hardware.org/?probe=6bf7b7dc2b) | Aug 05, 2023 |
| Supermicro    | X8DTU-LN4+                  | Server      | [fe2ea0ea4b](https://linux-hardware.org/?probe=fe2ea0ea4b) | Aug 05, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [efe021e3b5](https://linux-hardware.org/?probe=efe021e3b5) | Aug 05, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [5f516e849d](https://linux-hardware.org/?probe=5f516e849d) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [776bcc618a](https://linux-hardware.org/?probe=776bcc618a) | Aug 05, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [2c4db62652](https://linux-hardware.org/?probe=2c4db62652) | Aug 05, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [c95d1a55cd](https://linux-hardware.org/?probe=c95d1a55cd) | Aug 05, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [71ca443602](https://linux-hardware.org/?probe=71ca443602) | Aug 05, 2023 |
| MSI           | GE70 0NC                    | Notebook    | [c9fd935b80](https://linux-hardware.org/?probe=c9fd935b80) | Aug 05, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [d4ebcfaf3d](https://linux-hardware.org/?probe=d4ebcfaf3d) | Aug 05, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [cf67e6a006](https://linux-hardware.org/?probe=cf67e6a006) | Aug 05, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| RuggedPC      | T8S                         | Tablet      | [18f5243a7c](https://linux-hardware.org/?probe=18f5243a7c) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7abc08a315](https://linux-hardware.org/?probe=7abc08a315) | Aug 04, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [a650338ead](https://linux-hardware.org/?probe=a650338ead) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| Dell          | Vostro 5515                 | Notebook    | [bd17eec0e3](https://linux-hardware.org/?probe=bd17eec0e3) | Aug 04, 2023 |
| iRU           | J231                        | All in one  | [ddf5429a07](https://linux-hardware.org/?probe=ddf5429a07) | Aug 04, 2023 |
| ASRock        | G31M-S                      | Desktop     | [02bb341cc9](https://linux-hardware.org/?probe=02bb341cc9) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| iRU           | J231                        | All in one  | [e0bc93351c](https://linux-hardware.org/?probe=e0bc93351c) | Aug 04, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c677637c2](https://linux-hardware.org/?probe=4c677637c2) | Aug 04, 2023 |
| Dell          | Latitude E6510              | Notebook    | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [6d37036a76](https://linux-hardware.org/?probe=6d37036a76) | Aug 03, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [163708151e](https://linux-hardware.org/?probe=163708151e) | Aug 03, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [381ebee880](https://linux-hardware.org/?probe=381ebee880) | Aug 03, 2023 |
| MSI           | H110M PRO-VD Plus           | Desktop     | [de9bb54769](https://linux-hardware.org/?probe=de9bb54769) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Samsung       | 305U1A                      | Notebook    | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | Desktop     | [beddea6e34](https://linux-hardware.org/?probe=beddea6e34) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | Desktop     | [92bf3762f2](https://linux-hardware.org/?probe=92bf3762f2) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | Desktop     | [37ebe498c2](https://linux-hardware.org/?probe=37ebe498c2) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | Desktop     | [53edc778db](https://linux-hardware.org/?probe=53edc778db) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | Desktop     | [dc1c75a471](https://linux-hardware.org/?probe=dc1c75a471) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [28007801d5](https://linux-hardware.org/?probe=28007801d5) | Aug 03, 2023 |
| Supermicro    | X8DAH                       | Server      | [5db60ccf19](https://linux-hardware.org/?probe=5db60ccf19) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [5e3a46dee8](https://linux-hardware.org/?probe=5e3a46dee8) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1f1f14320c](https://linux-hardware.org/?probe=1f1f14320c) | Aug 03, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [448ad2c06a](https://linux-hardware.org/?probe=448ad2c06a) | Aug 03, 2023 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [5a368bb70f](https://linux-hardware.org/?probe=5a368bb70f) | Aug 03, 2023 |
| Panasonic     | CF-31WBLAXLM                | Notebook    | [580b017d88](https://linux-hardware.org/?probe=580b017d88) | Aug 03, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [c9e4b6dd90](https://linux-hardware.org/?probe=c9e4b6dd90) | Aug 03, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [bd5d07f54f](https://linux-hardware.org/?probe=bd5d07f54f) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [fabe23f1a8](https://linux-hardware.org/?probe=fabe23f1a8) | Aug 02, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [b8c2590139](https://linux-hardware.org/?probe=b8c2590139) | Aug 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [1ea7139d7e](https://linux-hardware.org/?probe=1ea7139d7e) | Aug 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [28ff7ce482](https://linux-hardware.org/?probe=28ff7ce482) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [23ba156377](https://linux-hardware.org/?probe=23ba156377) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e3f2347cf7](https://linux-hardware.org/?probe=e3f2347cf7) | Aug 02, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [c12e9ed368](https://linux-hardware.org/?probe=c12e9ed368) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [70c8bcf589](https://linux-hardware.org/?probe=70c8bcf589) | Aug 02, 2023 |
| ASUSTek       | P7F-M                       | Desktop     | [5c04bf12d0](https://linux-hardware.org/?probe=5c04bf12d0) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | Notebook    | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [41ff18df05](https://linux-hardware.org/?probe=41ff18df05) | Aug 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [eb3d428d41](https://linux-hardware.org/?probe=eb3d428d41) | Aug 02, 2023 |
| Dell          | 0GRJJ9 A01                  | Desktop     | [dca7ee3fdc](https://linux-hardware.org/?probe=dca7ee3fdc) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [4a6b173235](https://linux-hardware.org/?probe=4a6b173235) | Aug 01, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [56c71bf2d5](https://linux-hardware.org/?probe=56c71bf2d5) | Aug 01, 2023 |
| Acer          | Aspire 5600U                | All in one  | [dd8dcf6ed8](https://linux-hardware.org/?probe=dd8dcf6ed8) | Aug 01, 2023 |
| Supermicro    | X8DTT                       | Server      | [246d7ec81b](https://linux-hardware.org/?probe=246d7ec81b) | Aug 01, 2023 |
| Supermicro    | X8DTT                       | Server      | [f3d30d9bdb](https://linux-hardware.org/?probe=f3d30d9bdb) | Aug 01, 2023 |
| Supermicro    | X8DTT                       | Server      | [74803958ac](https://linux-hardware.org/?probe=74803958ac) | Aug 01, 2023 |
| Supermicro    | X8DTT                       | Server      | [b0c1b2fbb0](https://linux-hardware.org/?probe=b0c1b2fbb0) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [ef1917aa93](https://linux-hardware.org/?probe=ef1917aa93) | Aug 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [266d25478e](https://linux-hardware.org/?probe=266d25478e) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [9164151f28](https://linux-hardware.org/?probe=9164151f28) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| Teclast       | Tbolt 10 DG                 | Notebook    | [cd75496056](https://linux-hardware.org/?probe=cd75496056) | Aug 01, 2023 |
| Teclast       | F5                          | Convertible | [76fcc31a43](https://linux-hardware.org/?probe=76fcc31a43) | Aug 01, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [7f3c7327b7](https://linux-hardware.org/?probe=7f3c7327b7) | Aug 01, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [ec5e4c2338](https://linux-hardware.org/?probe=ec5e4c2338) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [9e8acac201](https://linux-hardware.org/?probe=9e8acac201) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | Notebook    | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Gigabyte      | MP32-AR0                    | Server      | [f6563c2624](https://linux-hardware.org/?probe=f6563c2624) | Jul 31, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [bdf93fa781](https://linux-hardware.org/?probe=bdf93fa781) | Jul 31, 2023 |
| Supermicro    | X11SCL-F                    | Server      | [6198182426](https://linux-hardware.org/?probe=6198182426) | Jul 31, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [81ab0317ab](https://linux-hardware.org/?probe=81ab0317ab) | Jul 31, 2023 |
| ASUSTek       | TUF H310-PLUS GAMING        | Desktop     | [a9326ba27e](https://linux-hardware.org/?probe=a9326ba27e) | Jul 31, 2023 |
| ASUSTek       | X411UA                      | Notebook    | [9ceaa9062e](https://linux-hardware.org/?probe=9ceaa9062e) | Jul 31, 2023 |
| Supermicro    | X7DWE                       | Desktop     | [a35080b0e5](https://linux-hardware.org/?probe=a35080b0e5) | Jul 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [c42c13e7be](https://linux-hardware.org/?probe=c42c13e7be) | Jul 31, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| Supermicro    | X11SCL-F                    | Server      | [89115fb3d2](https://linux-hardware.org/?probe=89115fb3d2) | Jul 31, 2023 |
| ASRock        | ALiveSATA2-GLAN             | Desktop     | [3c4fbfa426](https://linux-hardware.org/?probe=3c4fbfa426) | Jul 31, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [ef86202c7f](https://linux-hardware.org/?probe=ef86202c7f) | Jul 31, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [a757cca527](https://linux-hardware.org/?probe=a757cca527) | Jul 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e11390bc86](https://linux-hardware.org/?probe=e11390bc86) | Jul 31, 2023 |
| ASUSTek       | F3Se                        | Notebook    | [e5f8a806ea](https://linux-hardware.org/?probe=e5f8a806ea) | Jul 31, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [df16b38d10](https://linux-hardware.org/?probe=df16b38d10) | Jul 30, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [11fd627963](https://linux-hardware.org/?probe=11fd627963) | Jul 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [522c7e4381](https://linux-hardware.org/?probe=522c7e4381) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [14307e0b7e](https://linux-hardware.org/?probe=14307e0b7e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [583bc42f4e](https://linux-hardware.org/?probe=583bc42f4e) | Jul 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [71379f70f2](https://linux-hardware.org/?probe=71379f70f2) | Jul 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [b5f5ef27a8](https://linux-hardware.org/?probe=b5f5ef27a8) | Jul 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2046d205d6](https://linux-hardware.org/?probe=2046d205d6) | Jul 30, 2023 |
| Dell          | Vostro A860                 | Notebook    | [0148ba9cdc](https://linux-hardware.org/?probe=0148ba9cdc) | Jul 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cefd14313d](https://linux-hardware.org/?probe=cefd14313d) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [cdf06f1680](https://linux-hardware.org/?probe=cdf06f1680) | Jul 30, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [b69caa0c17](https://linux-hardware.org/?probe=b69caa0c17) | Jul 29, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [d7434fdb2a](https://linux-hardware.org/?probe=d7434fdb2a) | Jul 29, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| Sony          | SVS13A1Z9RN                 | Notebook    | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | Desktop     | [9c5eccdca7](https://linux-hardware.org/?probe=9c5eccdca7) | Jul 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [d43f4e6715](https://linux-hardware.org/?probe=d43f4e6715) | Jul 29, 2023 |
| ASRock        | G41M-VS2                    | Desktop     | [74564d3418](https://linux-hardware.org/?probe=74564d3418) | Jul 28, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [3ef07a69e6](https://linux-hardware.org/?probe=3ef07a69e6) | Jul 28, 2023 |
| ASUSTek       | X411UA                      | Notebook    | [0126e6254a](https://linux-hardware.org/?probe=0126e6254a) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cb17388b8c](https://linux-hardware.org/?probe=cb17388b8c) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | Desktop     | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [03b716e2bf](https://linux-hardware.org/?probe=03b716e2bf) | Jul 28, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [b24aea2d95](https://linux-hardware.org/?probe=b24aea2d95) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| ECS           | G33T_M                      | Desktop     | [cfaf5eaf20](https://linux-hardware.org/?probe=cfaf5eaf20) | Jul 28, 2023 |
| Lenovo        | No DPK                      | Desktop     | [c6af16725d](https://linux-hardware.org/?probe=c6af16725d) | Jul 28, 2023 |
| ASUSTek       | P9D-I Series                | Server      | [b8af713f2c](https://linux-hardware.org/?probe=b8af713f2c) | Jul 28, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [3ef67c1e1c](https://linux-hardware.org/?probe=3ef67c1e1c) | Jul 27, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | Notebook    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [27a13f80b2](https://linux-hardware.org/?probe=27a13f80b2) | Jul 27, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [cc502a8417](https://linux-hardware.org/?probe=cc502a8417) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| Unknown       | SCHNEIDER                   | Desktop     | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| HP            | 1495                        | Desktop     | [7db2d77f67](https://linux-hardware.org/?probe=7db2d77f67) | Jul 27, 2023 |
| HP            | 1495                        | Desktop     | [376f9777d4](https://linux-hardware.org/?probe=376f9777d4) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [eebd657892](https://linux-hardware.org/?probe=eebd657892) | Jul 27, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | Desktop     | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [7ca21b7b46](https://linux-hardware.org/?probe=7ca21b7b46) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [dc484f95af](https://linux-hardware.org/?probe=dc484f95af) | Jul 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [52358f6567](https://linux-hardware.org/?probe=52358f6567) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [6b35cdc0ae](https://linux-hardware.org/?probe=6b35cdc0ae) | Jul 26, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [29aa67256f](https://linux-hardware.org/?probe=29aa67256f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | Desktop     | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [8a0b28f729](https://linux-hardware.org/?probe=8a0b28f729) | Jul 26, 2023 |
| Supermicro    | X10DRH-iT                   | Server      | [d1ff1af77c](https://linux-hardware.org/?probe=d1ff1af77c) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [30cb22d368](https://linux-hardware.org/?probe=30cb22d368) | Jul 26, 2023 |
| Sony          | VPCSB1V9R                   | Notebook    | [12b5777cff](https://linux-hardware.org/?probe=12b5777cff) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [b28bc4ba91](https://linux-hardware.org/?probe=b28bc4ba91) | Jul 25, 2023 |
| AZW           | U59                         | Desktop     | [fcf46a9025](https://linux-hardware.org/?probe=fcf46a9025) | Jul 25, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1852d1455f](https://linux-hardware.org/?probe=1852d1455f) | Jul 25, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [761f825569](https://linux-hardware.org/?probe=761f825569) | Jul 25, 2023 |
| Gigabyte      | MP32-AR0                    | Server      | [8b0443884b](https://linux-hardware.org/?probe=8b0443884b) | Jul 25, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [15d4d04323](https://linux-hardware.org/?probe=15d4d04323) | Jul 25, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [543257c1b1](https://linux-hardware.org/?probe=543257c1b1) | Jul 25, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [dd2b862a0c](https://linux-hardware.org/?probe=dd2b862a0c) | Jul 25, 2023 |
| Dell          | Vostro A860                 | Notebook    | [8932ae1e87](https://linux-hardware.org/?probe=8932ae1e87) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bd31324aeb](https://linux-hardware.org/?probe=bd31324aeb) | Jul 25, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [9b0d43ec8f](https://linux-hardware.org/?probe=9b0d43ec8f) | Jul 25, 2023 |
| ASUSTek       | D500TC                      | Desktop     | [4fa391d922](https://linux-hardware.org/?probe=4fa391d922) | Jul 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [58ac4a2c1b](https://linux-hardware.org/?probe=58ac4a2c1b) | Jul 25, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bfa56fe825](https://linux-hardware.org/?probe=bfa56fe825) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c4d5317061](https://linux-hardware.org/?probe=c4d5317061) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5262229deb](https://linux-hardware.org/?probe=5262229deb) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | Desktop     | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| Notebook      | W510LU                      | Notebook    | [c770b71a6b](https://linux-hardware.org/?probe=c770b71a6b) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ad266cd914](https://linux-hardware.org/?probe=ad266cd914) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [a15d078adf](https://linux-hardware.org/?probe=a15d078adf) | Jul 24, 2023 |
| SiS Techno... | 760                         | Desktop     | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| INSYS         | IP1-XN23                    | Notebook    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [6dbfb1d71e](https://linux-hardware.org/?probe=6dbfb1d71e) | Jul 24, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [5b6e05fa3b](https://linux-hardware.org/?probe=5b6e05fa3b) | Jul 24, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [b571da19fb](https://linux-hardware.org/?probe=b571da19fb) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | Notebook    | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [2a23928116](https://linux-hardware.org/?probe=2a23928116) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [247870abec](https://linux-hardware.org/?probe=247870abec) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [7bd82402c7](https://linux-hardware.org/?probe=7bd82402c7) | Jul 24, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [27a5af5007](https://linux-hardware.org/?probe=27a5af5007) | Jul 24, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [f8df0d0706](https://linux-hardware.org/?probe=f8df0d0706) | Jul 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f64a4762c](https://linux-hardware.org/?probe=1f64a4762c) | Jul 24, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4a262a2a2d](https://linux-hardware.org/?probe=4a262a2a2d) | Jul 24, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [2a01d75ab6](https://linux-hardware.org/?probe=2a01d75ab6) | Jul 24, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [eef65c51cf](https://linux-hardware.org/?probe=eef65c51cf) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [304505406b](https://linux-hardware.org/?probe=304505406b) | Jul 24, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [696b36cfb3](https://linux-hardware.org/?probe=696b36cfb3) | Jul 24, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [a0cb68bf97](https://linux-hardware.org/?probe=a0cb68bf97) | Jul 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [cdf83d0eb8](https://linux-hardware.org/?probe=cdf83d0eb8) | Jul 24, 2023 |
| Samsung       | R780                        | Notebook    | [5f994aa483](https://linux-hardware.org/?probe=5f994aa483) | Jul 24, 2023 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [d4af5c7529](https://linux-hardware.org/?probe=d4af5c7529) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [db7d7ddd9c](https://linux-hardware.org/?probe=db7d7ddd9c) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | Notebook    | [d25f59d64d](https://linux-hardware.org/?probe=d25f59d64d) | Jul 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [3c35f3e9b5](https://linux-hardware.org/?probe=3c35f3e9b5) | Jul 23, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [7b591c93bb](https://linux-hardware.org/?probe=7b591c93bb) | Jul 23, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [0581ed028d](https://linux-hardware.org/?probe=0581ed028d) | Jul 23, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [3eadaff590](https://linux-hardware.org/?probe=3eadaff590) | Jul 23, 2023 |
| Lenovo        | IdeaPad Yoga 2-13 594202... | Notebook    | [66db18067c](https://linux-hardware.org/?probe=66db18067c) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [383118634e](https://linux-hardware.org/?probe=383118634e) | Jul 23, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [09beccd6f9](https://linux-hardware.org/?probe=09beccd6f9) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [a14a1b8379](https://linux-hardware.org/?probe=a14a1b8379) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| Intel         | X79 V1.x                    | Desktop     | [dda9563d4a](https://linux-hardware.org/?probe=dda9563d4a) | Jul 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [95e16f79ed](https://linux-hardware.org/?probe=95e16f79ed) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [46218bae31](https://linux-hardware.org/?probe=46218bae31) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b2870ce6ad](https://linux-hardware.org/?probe=b2870ce6ad) | Jul 22, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [f12c3b23e5](https://linux-hardware.org/?probe=f12c3b23e5) | Jul 22, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [2f8efec736](https://linux-hardware.org/?probe=2f8efec736) | Jul 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [7a3abd2e4d](https://linux-hardware.org/?probe=7a3abd2e4d) | Jul 22, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [c716419bfb](https://linux-hardware.org/?probe=c716419bfb) | Jul 22, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [8c75932124](https://linux-hardware.org/?probe=8c75932124) | Jul 22, 2023 |
| Biostar       | A320MH                      | Desktop     | [b4ad5e7452](https://linux-hardware.org/?probe=b4ad5e7452) | Jul 22, 2023 |
| HP            | 2AA6 PVT                    | Desktop     | [de8572b8cf](https://linux-hardware.org/?probe=de8572b8cf) | Jul 22, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | Notebook    | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [d47c43e734](https://linux-hardware.org/?probe=d47c43e734) | Jul 22, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [41f2b0b599](https://linux-hardware.org/?probe=41f2b0b599) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | Notebook    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | Notebook    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| RuggedPC      | T10S                        | Tablet      | [1d2ff7b1fc](https://linux-hardware.org/?probe=1d2ff7b1fc) | Jul 21, 2023 |
| ASRock        | M3N78D                      | Desktop     | [4ab55414b4](https://linux-hardware.org/?probe=4ab55414b4) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASRock        | M3N78D                      | Desktop     | [8175c636e8](https://linux-hardware.org/?probe=8175c636e8) | Jul 21, 2023 |
| ASUSTek       | X55A                        | Notebook    | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| RuggedPC      | T8S                         | Tablet      | [5ad27683aa](https://linux-hardware.org/?probe=5ad27683aa) | Jul 21, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e98c83ea9b](https://linux-hardware.org/?probe=e98c83ea9b) | Jul 21, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [c9c45ceeaf](https://linux-hardware.org/?probe=c9c45ceeaf) | Jul 21, 2023 |
| Azimut        | t8x-s                       | Tablet      | [68eadde1f0](https://linux-hardware.org/?probe=68eadde1f0) | Jul 21, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c0d9daee63](https://linux-hardware.org/?probe=c0d9daee63) | Jul 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7930c61fb6](https://linux-hardware.org/?probe=7930c61fb6) | Jul 21, 2023 |
| Acer          | Aspire 5610                 | Notebook    | [aa66524b51](https://linux-hardware.org/?probe=aa66524b51) | Jul 21, 2023 |
| Lenovo        | ThinkCentre M81 5049C12     | Desktop     | [a3cb3aa377](https://linux-hardware.org/?probe=a3cb3aa377) | Jul 21, 2023 |
| ZoomSmart     | A8006                       | Tablet      | [4d20f47175](https://linux-hardware.org/?probe=4d20f47175) | Jul 21, 2023 |
| Gigabyte      | MG51-G21-00 01010101        | Server      | [c9d3376115](https://linux-hardware.org/?probe=c9d3376115) | Jul 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [139780d2a0](https://linux-hardware.org/?probe=139780d2a0) | Jul 21, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [de2decf47b](https://linux-hardware.org/?probe=de2decf47b) | Jul 20, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [10c841c8ae](https://linux-hardware.org/?probe=10c841c8ae) | Jul 20, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [f21f00d216](https://linux-hardware.org/?probe=f21f00d216) | Jul 20, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| Gigabyte      | H61M-DS2V                   | Desktop     | [4720d80645](https://linux-hardware.org/?probe=4720d80645) | Jul 20, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [97c85ab250](https://linux-hardware.org/?probe=97c85ab250) | Jul 20, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| Samsung       | R530/R730                   | Notebook    | [0af014c11b](https://linux-hardware.org/?probe=0af014c11b) | Jul 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [6284551b74](https://linux-hardware.org/?probe=6284551b74) | Jul 20, 2023 |
| MSI           | GS73 Stealth 8RE            | Notebook    | [8fdb7e6e4e](https://linux-hardware.org/?probe=8fdb7e6e4e) | Jul 20, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [5fbf587eba](https://linux-hardware.org/?probe=5fbf587eba) | Jul 19, 2023 |
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
| Gigabyte      | H81M-S2V                    | Desktop     | [b380a59bd3](https://linux-hardware.org/?probe=b380a59bd3) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d1f453b1cf](https://linux-hardware.org/?probe=d1f453b1cf) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [0525e36038](https://linux-hardware.org/?probe=0525e36038) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [56571f9682](https://linux-hardware.org/?probe=56571f9682) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [b4516f6d51](https://linux-hardware.org/?probe=b4516f6d51) | Jul 19, 2023 |
| Acer          | AOD260                      | Notebook    | [e3854aa993](https://linux-hardware.org/?probe=e3854aa993) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [fd2864f7e1](https://linux-hardware.org/?probe=fd2864f7e1) | Jul 19, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [9dd9b64ff1](https://linux-hardware.org/?probe=9dd9b64ff1) | Jul 19, 2023 |
| Biostar       | H61MHV2                     | Desktop     | [c108eac8f6](https://linux-hardware.org/?probe=c108eac8f6) | Jul 19, 2023 |
| Chuwi         | CoreBook                    | Notebook    | [816be37c03](https://linux-hardware.org/?probe=816be37c03) | Jul 19, 2023 |
| Aquarius      | AQNS483V2                   | Convertible | [0d820d1ddd](https://linux-hardware.org/?probe=0d820d1ddd) | Jul 19, 2023 |
| Toshiba       | QOSMIO G30                  | Notebook    | [520eb05b29](https://linux-hardware.org/?probe=520eb05b29) | Jul 19, 2023 |
| HP            | Notebook                    | Notebook    | [92bc221e2c](https://linux-hardware.org/?probe=92bc221e2c) | Jul 19, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [39035af050](https://linux-hardware.org/?probe=39035af050) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | Notebook    | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b5b8d4fce2](https://linux-hardware.org/?probe=b5b8d4fce2) | Jul 19, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [5f2fbf2720](https://linux-hardware.org/?probe=5f2fbf2720) | Jul 19, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [ad25a9b9a2](https://linux-hardware.org/?probe=ad25a9b9a2) | Jul 19, 2023 |
| ASUSTek       | P5QL-CM                     | Desktop     | [65fe34f4ce](https://linux-hardware.org/?probe=65fe34f4ce) | Jul 19, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [15f6e3e7e0](https://linux-hardware.org/?probe=15f6e3e7e0) | Jul 19, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [278c03b690](https://linux-hardware.org/?probe=278c03b690) | Jul 19, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [f81b2bedb9](https://linux-hardware.org/?probe=f81b2bedb9) | Jul 18, 2023 |
| Lenovo        | IdeaPad S10-2 20027         | Notebook    | [ea5513d981](https://linux-hardware.org/?probe=ea5513d981) | Jul 18, 2023 |
| HP            | Compaq nx7400 (EY587ES#A... | Notebook    | [15ba20b136](https://linux-hardware.org/?probe=15ba20b136) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [8ce3a9560a](https://linux-hardware.org/?probe=8ce3a9560a) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [fe575143d6](https://linux-hardware.org/?probe=fe575143d6) | Jul 18, 2023 |
| MSI           | GS73 Stealth 8RE            | Notebook    | [83f9ea8fc6](https://linux-hardware.org/?probe=83f9ea8fc6) | Jul 18, 2023 |
| HP            | 17-ak041ur                  | Notebook    | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [0eea552cfa](https://linux-hardware.org/?probe=0eea552cfa) | Jul 18, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4b683fcc22](https://linux-hardware.org/?probe=4b683fcc22) | Jul 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R11           | 3119      | 10.36%  |
| ROSA R10           | 3116      | 10.35%  |
| ROSA R8.1          | 2217      | 7.37%   |
| ROSA R8            | 1995      | 6.63%   |
| ROSA R9            | 1814      | 6.03%   |
| ROSA 12.2          | 1754      | 5.83%   |
| ROSA R11.1         | 1706      | 5.67%   |
| Debian 11          | 1010      | 3.36%   |
| Ubuntu 20.04       | 897       | 2.98%   |
| ROSA 12.3          | 825       | 2.74%   |
| ROSA 12.4          | 637       | 2.12%   |
| Ubuntu 18.04       | 485       | 1.61%   |
| Ubuntu 22.04       | 463       | 1.54%   |
| OpenMandriva 4.2   | 403       | 1.34%   |
| Arch Rolling       | 296       | 0.98%   |
| OpenMandriva 4.3   | 292       | 0.97%   |
| ROSA 12.1          | 275       | 0.91%   |
| Debian 12          | 243       | 0.81%   |
| KDE neon 20.04     | 199       | 0.66%   |
| Arch               | 175       | 0.58%   |
| Debian 10          | 174       | 0.58%   |
| ROSA 12            | 169       | 0.56%   |
| Manjaro            | 168       | 0.56%   |
| Kometa P10         | 165       | 0.55%   |
| Fedora 36          | 153       | 0.51%   |
| Fedora 37          | 148       | 0.49%   |
| Xubuntu 20.04      | 136       | 0.45%   |
| Linux Mint 20.3    | 135       | 0.45%   |
| Linux Mint 19.3    | 134       | 0.45%   |
| OpenMandriva 23.03 | 123       | 0.41%   |
| OpenMandriva 23.01 | 120       | 0.4%    |
| Kubuntu 20.04      | 119       | 0.4%    |
| Fedora 38          | 119       | 0.4%    |
| Fedora 35          | 113       | 0.38%   |
| ALT Linux 10.1     | 113       | 0.38%   |
| Linux Mint 18.3    | 112       | 0.37%   |
| Red OS 7.3.2       | 108       | 0.36%   |
| Linux Mint 20.1    | 108       | 0.36%   |
| Linux Mint 19.1    | 105       | 0.35%   |
| Red OS 7.3.1       | 100       | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 15128     | 56.75%  |
| Ubuntu        | 2310      | 8.67%   |
| Debian        | 1444      | 5.42%   |
| Linux Mint    | 1112      | 4.17%   |
| OpenMandriva  | 1029      | 3.86%   |
| Fedora        | 778       | 2.92%   |
| Manjaro       | 614       | 2.3%    |
| ALT Linux     | 552       | 2.07%   |
| Arch          | 454       | 1.7%    |
| Red OS        | 298       | 1.12%   |
| Endless       | 288       | 1.08%   |
| Kubuntu       | 278       | 1.04%   |
| Xubuntu       | 268       | 1.01%   |
| KDE neon      | 263       | 0.99%   |
| RED           | 168       | 0.63%   |
| Pop!_OS       | 161       | 0.6%    |
| Gentoo        | 136       | 0.51%   |
| openSUSE      | 107       | 0.4%    |
| Elementary    | 93        | 0.35%   |
| Kali          | 91        | 0.34%   |
| Ubuntu MATE   | 67        | 0.25%   |
| Lubuntu       | 66        | 0.25%   |
| CentOS        | 65        | 0.24%   |
| Clear Linux   | 63        | 0.24%   |
| Zorin         | 62        | 0.23%   |
| LMDE          | 61        | 0.23%   |
| ArcoLinux     | 54        | 0.2%    |
| Ubuntu Unity  | 52        | 0.2%    |
| RELS          | 44        | 0.17%   |
| Cyber Infra   | 42        | 0.16%   |
| Astra Linux   | 34        | 0.13%   |
| EndeavourOS   | 33        | 0.12%   |
| SteamOS       | 30        | 0.11%   |
| MX            | 24        | 0.09%   |
| Artix         | 23        | 0.09%   |
| Parrot        | 18        | 0.07%   |
| Ubuntu Budgie | 16        | 0.06%   |
| RELD          | 16        | 0.06%   |
| Void Linux    | 15        | 0.06%   |
| Calculate     | 15        | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 1502      | 4.64%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 1358      | 4.2%    |
| 4.15.0-desktop-45.1rosa-x86_64      | 1352      | 4.18%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1280      | 3.96%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 761       | 2.35%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 619       | 1.91%   |
| 5.10.0-7-amd64                      | 583       | 1.8%    |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 558       | 1.72%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 545       | 1.68%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 476       | 1.47%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 406       | 1.25%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 395       | 1.22%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 391       | 1.21%   |
| 5.10.14-desktop-1omv4002            | 388       | 1.2%    |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 377       | 1.17%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 369       | 1.14%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 363       | 1.12%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 355       | 1.1%    |
| 4.15.0-desktop-45.1rosa-i586        | 349       | 1.08%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 329       | 1.02%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 323       | 1%      |
| 5.4.32-generic-2rosa-x86_64         | 317       | 0.98%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 307       | 0.95%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 297       | 0.92%   |
| 5.4.83-generic-2rosa-x86_64         | 293       | 0.91%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 281       | 0.87%   |
| 5.16.7-desktop-1omv4003             | 268       | 0.83%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 251       | 0.78%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 251       | 0.78%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 240       | 0.74%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 220       | 0.68%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 204       | 0.63%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 192       | 0.59%   |
| 6.1.0-4-amd64                       | 172       | 0.53%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 167       | 0.52%   |
| 5.10.0-2-amd64                      | 149       | 0.46%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 143       | 0.44%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 143       | 0.44%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 138       | 0.43%   |
| 6.1.38-generic-1rosa2021.1-x86_64   | 134       | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 4000      | 12.75%  |
| 4.9.60   | 1751      | 5.58%   |
| 4.9.20   | 1642      | 5.23%   |
| 5.10.74  | 1551      | 4.94%   |
| 5.4.0    | 1353      | 4.31%   |
| 4.1.34   | 1057      | 3.37%   |
| 5.10.0   | 1054      | 3.36%   |
| 4.1.38   | 841       | 2.68%   |
| 5.15.0   | 797       | 2.54%   |
| 4.9.9    | 792       | 2.52%   |
| 4.9.124  | 765       | 2.44%   |
| 4.1.25   | 763       | 2.43%   |
| 4.9.76   | 494       | 1.57%   |
| 4.9.41   | 493       | 1.57%   |
| 4.9.155  | 482       | 1.54%   |
| 5.4.32   | 434       | 1.38%   |
| 6.1.20   | 429       | 1.37%   |
| 5.3.0    | 400       | 1.27%   |
| 5.10.14  | 392       | 1.25%   |
| 5.4.83   | 382       | 1.22%   |
| 5.8.0    | 376       | 1.2%    |
| 5.11.0   | 357       | 1.14%   |
| 5.10.118 | 336       | 1.07%   |
| 5.15.75  | 323       | 1.03%   |
| 5.13.0   | 313       | 1%      |
| 5.0.0    | 296       | 0.94%   |
| 6.1.0    | 284       | 0.91%   |
| 5.16.7   | 271       | 0.86%   |
| 5.19.0   | 263       | 0.84%   |
| 4.9.95   | 251       | 0.8%    |
| 5.15.79  | 244       | 0.78%   |
| 4.18.0   | 192       | 0.61%   |
| 4.9.111  | 187       | 0.6%    |
| 4.19.0   | 158       | 0.5%    |
| 6.1.38   | 150       | 0.48%   |
| 6.2.6    | 146       | 0.47%   |
| 4.13.0   | 145       | 0.46%   |
| 4.9.87   | 142       | 0.45%   |
| 5.10.71  | 139       | 0.44%   |
| 3.10.0   | 134       | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 6233      | 21.17%  |
| 5.10    | 4045      | 13.74%  |
| 4.15    | 4038      | 13.72%  |
| 4.1     | 2601      | 8.84%   |
| 5.4     | 2514      | 8.54%   |
| 5.15    | 2153      | 7.31%   |
| 6.1     | 1190      | 4.04%   |
| 5.11    | 515       | 1.75%   |
| 5.8     | 499       | 1.7%    |
| 5.3     | 496       | 1.68%   |
| 5.16    | 425       | 1.44%   |
| 5.13    | 412       | 1.4%    |
| 6.2     | 401       | 1.36%   |
| 5.19    | 376       | 1.28%   |
| 5.0     | 325       | 1.1%    |
| 6.0     | 276       | 0.94%   |
| 5.18    | 254       | 0.86%   |
| 4.19    | 248       | 0.84%   |
| 5.17    | 226       | 0.77%   |
| 4.18    | 218       | 0.74%   |
| 5.14    | 181       | 0.61%   |
| 4.13    | 175       | 0.59%   |
| 6.4     | 165       | 0.56%   |
| 5.6     | 157       | 0.53%   |
| 5.9     | 137       | 0.47%   |
| 3.10    | 137       | 0.47%   |
| 6.3     | 120       | 0.41%   |
| 4.4     | 109       | 0.37%   |
| 5.12    | 99        | 0.34%   |
| 5.7     | 93        | 0.32%   |
| 4.8     | 77        | 0.26%   |
| 4.16    | 76        | 0.26%   |
| 5.5     | 71        | 0.24%   |
| 4.10    | 59        | 0.2%    |
| 4.14    | 50        | 0.17%   |
| 3.14    | 43        | 0.15%   |
| 5.2     | 40        | 0.14%   |
| 4.12    | 30        | 0.1%    |
| 4.17    | 27        | 0.09%   |
| 4.11    | 24        | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 22683     | 86.72%  |
| i686        | 3375      | 12.9%   |
| aarch64     | 63        | 0.24%   |
| armv7l      | 18        | 0.07%   |
| e2k         | 5         | 0.02%   |
| armv6l      | 5         | 0.02%   |
| armv8l      | 3         | 0.01%   |
| ppc64       | 1         | 0.004%  |
| ppc         | 1         | 0.004%  |
| mips        | 1         | 0.004%  |
| loongarch64 | 1         | 0.004%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KDE4               | 9055      | 32.67%  |
| KDE5               | 7357      | 26.54%  |
| GNOME              | 4636      | 16.73%  |
| Unknown            | 2256      | 8.14%   |
| XFCE               | 996       | 3.59%   |
| LXQt               | 825       | 2.98%   |
| MATE               | 824       | 2.97%   |
| X-Cinnamon         | 525       | 1.89%   |
| Cinnamon           | 472       | 1.7%    |
| KDE                | 314       | 1.13%   |
| Pantheon           | 88        | 0.32%   |
| LXDE               | 60        | 0.22%   |
| i3                 | 55        | 0.2%    |
| Unity              | 52        | 0.19%   |
| Budgie             | 39        | 0.14%   |
| GNOME Flashback    | 26        | 0.09%   |
| Deepin             | 18        | 0.06%   |
| sway               | 16        | 0.06%   |
| fly                | 16        | 0.06%   |
| awesome            | 11        | 0.04%   |
| GNOME Classic      | 10        | 0.04%   |
| Openbox            | 9         | 0.03%   |
| bspwm              | 8         | 0.03%   |
| icewm              | 7         | 0.03%   |
| DWM                | 7         | 0.03%   |
| Hyprland           | 6         | 0.02%   |
| Trinity            | 5         | 0.02%   |
| xmonad             | 4         | 0.01%   |
| lightdm-xsession   | 4         | 0.01%   |
| fluxbox            | 4         | 0.01%   |
| X-Generic          | 1         | 0.004%  |
| steamos            | 1         | 0.004%  |
| qtile              | 1         | 0.004%  |
| pantheon-non-gnome | 1         | 0.004%  |
| none+i3            | 1         | 0.004%  |
| Lumina             | 1         | 0.004%  |
| Lubuntu            | 1         | 0.004%  |
| i3-with-shmlog     | 1         | 0.004%  |
| fvwm2              | 1         | 0.004%  |
| Enlightenment      | 1         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 20687     | 77.52%  |
| Wayland     | 4219      | 15.81%  |
| Unknown     | 1456      | 5.46%   |
| Tty         | 321       | 1.2%    |
| Web         | 1         | 0.004%  |
| Unspecified | 1         | 0.004%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 9117      | 33%     |
| SDDM    | 7456      | 26.99%  |
| Unknown | 4828      | 17.48%  |
| GDM     | 3256      | 11.79%  |
| LightDM | 1304      | 4.72%   |
| TDM     | 798       | 2.89%   |
| GDM3    | 737       | 2.67%   |
| MDM     | 43        | 0.16%   |
| XDM     | 28        | 0.1%    |
| SLiM    | 18        | 0.07%   |
| FLY-DM  | 14        | 0.05%   |
| LXDM    | 11        | 0.04%   |
| Ly      | 6         | 0.02%   |
| NODM    | 4         | 0.01%   |
| GREETD  | 4         | 0.01%   |
| WDM     | 1         | 0.004%  |
| LDM     | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 12415     | 46.07%  |
| ru_RU       | 11498     | 42.67%  |
| en_US       | 2586      | 9.6%    |
| C           | 200       | 0.74%   |
| en_GB       | 90        | 0.33%   |
| ru_RU.UTF_8 | 30        | 0.11%   |
| ru_UA       | 19        | 0.07%   |
| C.UTF8      | 15        | 0.06%   |
| POSIX       | 14        | 0.05%   |
| ru_RU.UTF8  | 10        | 0.04%   |
| zh_CN       | 7         | 0.03%   |
| de_DE       | 7         | 0.03%   |
| cv_RU       | 7         | 0.03%   |
| en_DK       | 6         | 0.02%   |
| en_AG       | 6         | 0.02%   |
| ba_RU       | 5         | 0.02%   |
| en_CA       | 4         | 0.01%   |
| uk_UA       | 3         | 0.01%   |
| tt_RU       | 3         | 0.01%   |
| fr_FR       | 3         | 0.01%   |
| es_ES       | 3         | 0.01%   |
| tr_TR       | 2         | 0.01%   |
| pt_BR       | 2         | 0.01%   |
| myv_RU      | 2         | 0.01%   |
| it_IT       | 2         | 0.01%   |
| ru_RU.utf-8 | 1         | 0.004%  |
| ja_JP       | 1         | 0.004%  |
| en_RU       | 1         | 0.004%  |
| en_NZ       | 1         | 0.004%  |
| en_IL       | 1         | 0.004%  |
| en_GB.utf-8 | 1         | 0.004%  |
| en_AU       | 1         | 0.004%  |
| en-US       | 1         | 0.004%  |
| ce_RU       | 1         | 0.004%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 16586     | 62.68%  |
| EFI  | 9875      | 37.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 15839     | 57.82%  |
| Unknown  | 7581      | 27.67%  |
| Overlay  | 1899      | 6.93%   |
| Btrfs    | 1484      | 5.42%   |
| Xfs      | 217       | 0.79%   |
| Tmpfs    | 88        | 0.32%   |
| Zfs      | 81        | 0.3%    |
| Ext3     | 68        | 0.25%   |
| F2fs     | 42        | 0.15%   |
| Ext2     | 41        | 0.15%   |
| Aufs     | 22        | 0.08%   |
| Reiserfs | 9         | 0.03%   |
| XXXXXXX  | 5         | 0.02%   |
| Rootfs   | 5         | 0.02%   |
| Jfs      | 5         | 0.02%   |
| SAMSUNG  | 3         | 0.01%   |
| XXXXX    | 2         | 0.01%   |
| Ufs      | 1         | 0.004%  |
| Exfat    | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 10978     | 40.08%  |
| GPT     | 9348      | 34.13%  |
| Unknown | 7062      | 25.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22937     | 85.68%  |
| Yes       | 3833      | 14.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 18287     | 67.72%  |
| Yes       | 8715      | 32.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 6596      | 25.49%  |
| Gigabyte Technology | 3069      | 11.86%  |
| Lenovo              | 2522      | 9.75%   |
| Hewlett-Packard     | 2092      | 8.09%   |
| Acer                | 1901      | 7.35%   |
| MSI                 | 1665      | 6.43%   |
| ASRock              | 1350      | 5.22%   |
| Dell                | 1000      | 3.86%   |
| Samsung Electronics | 672       | 2.6%    |
| Intel               | 491       | 1.9%    |
| Unknown             | 328       | 1.27%   |
| Toshiba             | 299       | 1.16%   |
| Sony                | 283       | 1.09%   |
| ECS                 | 275       | 1.06%   |
| HUAWEI              | 244       | 0.94%   |
| Supermicro          | 206       | 0.8%    |
| Packard Bell        | 187       | 0.72%   |
| Apple               | 158       | 0.61%   |
| Pegatron            | 150       | 0.58%   |
| Biostar             | 138       | 0.53%   |
| Foxconn             | 128       | 0.49%   |
| eMachines           | 125       | 0.48%   |
| Clevo               | 108       | 0.42%   |
| Aquarius            | 105       | 0.41%   |
| Timi                | 104       | 0.4%    |
| Huanan              | 92        | 0.36%   |
| Notebook            | 78        | 0.3%    |
| Digma               | 65        | 0.25%   |
| Fujitsu Siemens     | 59        | 0.23%   |
| Fujitsu             | 59        | 0.23%   |
| HONOR               | 56        | 0.22%   |
| Irbis               | 51        | 0.2%    |
| Quanta              | 43        | 0.17%   |
| ICL                 | 41        | 0.16%   |
| DNS                 | 40        | 0.15%   |
| 3Logic Group        | 39        | 0.15%   |
| Prestigio           | 38        | 0.15%   |
| DEPO Computers      | 38        | 0.15%   |
| Chuwi               | 35        | 0.14%   |
| AMI                 | 34        | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 424       | 1.64%   |
| ASUS All Series                  | 395       | 1.53%   |
| HP Pavilion g6                   | 126       | 0.49%   |
| HP Pavilion dv6                  | 82        | 0.32%   |
| HP Notebook                      | 82        | 0.32%   |
| HP Laptop 15-bw0xx               | 76        | 0.29%   |
| MSI MS-7996                      | 75        | 0.29%   |
| Gigabyte 970A-DS3P               | 72        | 0.28%   |
| MSI MS-7817                      | 70        | 0.27%   |
| ASUS M5A78L-M LX3                | 69        | 0.27%   |
| Acer Aspire V3-571G              | 63        | 0.24%   |
| ASUS H110M-R                     | 61        | 0.24%   |
| Supermicro Super Server          | 59        | 0.23%   |
| ASUS P8H61-M LX3 R2.0            | 59        | 0.23%   |
| ASUS S20 K29                     | 55        | 0.21%   |
| Lenovo G570 20079                | 54        | 0.21%   |
| Intel SKYBAY                     | 50        | 0.19%   |
| ASUS P5K                         | 50        | 0.19%   |
| Aquarius NS585                   | 50        | 0.19%   |
| ASUS M5A97 R2.0                  | 49        | 0.19%   |
| Lenovo B570e HuronRiver Platform | 47        | 0.18%   |
| ASRock G31M-S                    | 47        | 0.18%   |
| MSI MS-7529                      | 46        | 0.18%   |
| Lenovo B590 20206                | 46        | 0.18%   |
| Gigabyte H61M-S1                 | 46        | 0.18%   |
| Gigabyte G31M-ES2L               | 44        | 0.17%   |
| ASUS P5G41T-M LX2/GB             | 44        | 0.17%   |
| Gigabyte H61M-S2PV               | 43        | 0.17%   |
| ASUS P5KPL-AM                    | 43        | 0.17%   |
| HP Pavilion dv7                  | 42        | 0.16%   |
| MSI MS-7592                      | 41        | 0.16%   |
| ASUS PRIME A320M-K               | 41        | 0.16%   |
| Packard Bell EasyNote TE11HC     | 40        | 0.15%   |
| HP Pavilion 15                   | 40        | 0.15%   |
| ASRock N68C-S UCC                | 40        | 0.15%   |
| Gigabyte H81M-S2V                | 39        | 0.15%   |
| ASUS M5A78L-M/USB3               | 39        | 0.15%   |
| Lenovo B590 20208                | 38        | 0.15%   |
| ASUS M5A97 LE R2.0               | 38        | 0.15%   |
| Clevo NL41MU2                    | 37        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1290      | 4.99%   |
| Lenovo IdeaPad        | 661       | 2.55%   |
| HP Pavilion           | 532       | 2.06%   |
| Lenovo ThinkPad       | 506       | 1.96%   |
| ASUS PRIME            | 444       | 1.72%   |
| Dell Inspiron         | 442       | 1.71%   |
| Unknown               | 424       | 1.64%   |
| ASUS All              | 395       | 1.53%   |
| ASUS VivoBook         | 328       | 1.27%   |
| HP Laptop             | 306       | 1.18%   |
| Toshiba Satellite     | 278       | 1.07%   |
| HP ProBook            | 268       | 1.04%   |
| ASUS P8H61-M          | 193       | 0.75%   |
| ASUS M5A78L-M         | 180       | 0.7%    |
| Dell Latitude         | 175       | 0.68%   |
| HP Compaq             | 173       | 0.67%   |
| Acer Extensa          | 161       | 0.62%   |
| Packard Bell EasyNote | 156       | 0.6%    |
| ASUS ROG              | 133       | 0.51%   |
| Dell Vostro           | 129       | 0.5%    |
| ASUS P5KPL-AM         | 127       | 0.49%   |
| ASUS TUF              | 125       | 0.48%   |
| ASUS M5A97            | 117       | 0.45%   |
| ASUS P5G41T-M         | 110       | 0.43%   |
| ASUS P5K              | 102       | 0.39%   |
| HP EliteBook          | 100       | 0.39%   |
| ASUS P8Z77-V          | 90        | 0.35%   |
| Acer TravelMate       | 90        | 0.35%   |
| Lenovo B590           | 84        | 0.32%   |
| HP Notebook           | 83        | 0.32%   |
| Lenovo ThinkCentre    | 82        | 0.32%   |
| Lenovo G580           | 80        | 0.31%   |
| Lenovo ThinkBook      | 77        | 0.3%    |
| Gigabyte B450M        | 77        | 0.3%    |
| MSI MS-7996           | 75        | 0.29%   |
| Dell OptiPlex         | 75        | 0.29%   |
| ASUS P5Q              | 74        | 0.29%   |
| HP ENVY               | 73        | 0.28%   |
| Gigabyte 970A-DS3P    | 73        | 0.28%   |
| MSI MS-7817           | 70        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 3120      | 12.06%  |
| 2011    | 2632      | 10.17%  |
| 2010    | 2018      | 7.8%    |
| 2013    | 1805      | 6.98%   |
| 2018    | 1726      | 6.67%   |
| 2009    | 1715      | 6.63%   |
| 2019    | 1429      | 5.52%   |
| 2008    | 1409      | 5.45%   |
| 2020    | 1289      | 4.98%   |
| 2007    | 1215      | 4.7%    |
| 2017    | 1213      | 4.69%   |
| 2021    | 1206      | 4.66%   |
| 2014    | 1138      | 4.4%    |
| 2016    | 1104      | 4.27%   |
| 2015    | 1009      | 3.9%    |
| 2006    | 689       | 2.66%   |
| 2022    | 625       | 2.42%   |
| 2005    | 250       | 0.97%   |
| Unknown | 92        | 0.36%   |
| 2004    | 81        | 0.31%   |
| 2023    | 50        | 0.19%   |
| 2003    | 46        | 0.18%   |
| 2002    | 8         | 0.03%   |
| 2001    | 5         | 0.02%   |
| 2000    | 1         | 0.004%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 12358     | 47.76%  |
| Notebook       | 12336     | 47.68%  |
| All in one     | 350       | 1.35%   |
| Server         | 318       | 1.23%   |
| Mini pc        | 204       | 0.79%   |
| Convertible    | 124       | 0.48%   |
| Tablet         | 108       | 0.42%   |
| System on chip | 68        | 0.26%   |
| Phone          | 6         | 0.02%   |
| Stick pc       | 2         | 0.01%   |
| Firewall       | 1         | 0.004%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25211     | 97.14%  |
| Enabled  | 742       | 2.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25855     | 99.92%  |
| Yes  | 20        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 6963      | 26.03%  |
| 4.01-8.0        | 5737      | 21.45%  |
| 8.01-16.0       | 4732      | 17.69%  |
| 16.01-24.0      | 3121      | 11.67%  |
| 1.01-2.0        | 2593      | 9.69%   |
| 2.01-3.0        | 1473      | 5.51%   |
| 32.01-64.0      | 1037      | 3.88%   |
| 0.51-1.0        | 436       | 1.63%   |
| 64.01-256.0     | 324       | 1.21%   |
| 24.01-32.0      | 229       | 0.86%   |
| More than 256.0 | 59        | 0.22%   |
| 0.01-0.5        | 37        | 0.14%   |
| Unknown         | 7         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 11155     | 38.1%   |
| 0.51-1.0        | 8930      | 30.5%   |
| 2.01-3.0        | 4159      | 14.21%  |
| 4.01-8.0        | 1885      | 6.44%   |
| 3.01-4.0        | 1776      | 6.07%   |
| 0.01-0.5        | 646       | 2.21%   |
| 8.01-16.0       | 523       | 1.79%   |
| 16.01-24.0      | 81        | 0.28%   |
| Unknown         | 37        | 0.13%   |
| 32.01-64.0      | 33        | 0.11%   |
| 24.01-32.0      | 33        | 0.11%   |
| 64.01-256.0     | 14        | 0.05%   |
| More than 256.0 | 5         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 16932     | 62.61%  |
| 2       | 6366      | 23.54%  |
| 3       | 2079      | 7.69%   |
| 4       | 834       | 3.08%   |
| 5       | 362       | 1.34%   |
| 0       | 202       | 0.75%   |
| 6       | 117       | 0.43%   |
| 7       | 49        | 0.18%   |
| 8       | 40        | 0.15%   |
| 9       | 14        | 0.05%   |
| 11      | 10        | 0.04%   |
| 10      | 10        | 0.04%   |
| Unknown | 9         | 0.03%   |
| 28      | 3         | 0.01%   |
| 17      | 3         | 0.01%   |
| 16      | 2         | 0.01%   |
| 12      | 2         | 0.01%   |
| 209     | 1         | 0.004%  |
| 40      | 1         | 0.004%  |
| 27      | 1         | 0.004%  |
| 26      | 1         | 0.004%  |
| 25      | 1         | 0.004%  |
| 24      | 1         | 0.004%  |
| 21      | 1         | 0.004%  |
| 19      | 1         | 0.004%  |
| 18      | 1         | 0.004%  |
| 15      | 1         | 0.004%  |
| 13      | 1         | 0.004%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 14486     | 55%     |
| Yes       | 11850     | 45%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23742     | 91.65%  |
| No        | 2162      | 8.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15842     | 60.67%  |
| No        | 10268     | 39.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 15035     | 57.3%   |
| Yes       | 11202     | 42.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 25875     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 5366      | 19.36%  |
| St Petersburg    | 2239      | 8.08%   |
| Voronezh         | 1231      | 4.44%   |
| Novosibirsk      | 824       | 2.97%   |
| Pecherskoye      | 765       | 2.76%   |
| Krasnodar        | 716       | 2.58%   |
| Yekaterinburg    | 701       | 2.53%   |
| Nizhniy Novgorod | 530       | 1.91%   |
| Samara           | 515       | 1.86%   |
| Perm             | 458       | 1.65%   |
| Rostov-on-Don    | 451       | 1.63%   |
| Chelyabinsk      | 422       | 1.52%   |
| Krasnoyarsk      | 323       | 1.17%   |
| Kazan’         | 304       | 1.1%    |
| Saratov          | 299       | 1.08%   |
| Ufa              | 275       | 0.99%   |
| Omsk             | 266       | 0.96%   |
| Volgograd        | 244       | 0.88%   |
| Vladivostok      | 225       | 0.81%   |
| Tyumen           | 223       | 0.8%    |
| Khabarovsk       | 222       | 0.8%    |
| Barnaul          | 213       | 0.77%   |
| Irkutsk          | 207       | 0.75%   |
| Stavropol        | 202       | 0.73%   |
| Yaroslavl        | 166       | 0.6%    |
| Tomsk            | 160       | 0.58%   |
| Kaliningrad      | 160       | 0.58%   |
| Ulyanovsk        | 158       | 0.57%   |
| Tula             | 152       | 0.55%   |
| Kemerovo         | 152       | 0.55%   |
| Belgorod         | 151       | 0.54%   |
| Orenburg         | 144       | 0.52%   |
| Kirov            | 140       | 0.51%   |
| Ryazan           | 138       | 0.5%    |
| Bryansk          | 134       | 0.48%   |
| Novokuznetsk     | 129       | 0.47%   |
| Tolyatti         | 127       | 0.46%   |
| Izhevsk          | 127       | 0.46%   |
| Surgut           | 126       | 0.45%   |
| Penza            | 121       | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7768      | 12684  | 20.83%  |
| Seagate             | 7409      | 11430  | 19.86%  |
| Samsung Electronics | 3390      | 5012   | 9.09%   |
| Toshiba             | 2927      | 4152   | 7.85%   |
| Hitachi             | 2067      | 2842   | 5.54%   |
| Kingston            | 1928      | 2554   | 5.17%   |
| Unknown             | 880       | 1173   | 2.36%   |
| HGST                | 800       | 1203   | 2.14%   |
| SanDisk             | 787       | 1058   | 2.11%   |
| Intel               | 692       | 1071   | 1.86%   |
| A-DATA Technology   | 679       | 1008   | 1.82%   |
| China               | 605       | 822    | 1.62%   |
| Crucial             | 484       | 637    | 1.3%    |
| SK hynix            | 474       | 603    | 1.27%   |
| SPCC                | 459       | 606    | 1.23%   |
| Apacer              | 343       | 438    | 0.92%   |
| OCZ                 | 337       | 427    | 0.9%    |
| Plextor             | 294       | 427    | 0.79%   |
| Maxtor              | 286       | 362    | 0.77%   |
| Micron Technology   | 243       | 352    | 0.65%   |
| Smartbuy            | 231       | 296    | 0.62%   |
| Fujitsu             | 208       | 284    | 0.56%   |
| Transcend           | 196       | 245    | 0.53%   |
| AMD                 | 190       | 235    | 0.51%   |
| KingSpec            | 184       | 230    | 0.49%   |
| Patriot             | 183       | 232    | 0.49%   |
| Silicon Motion      | 169       | 209    | 0.45%   |
| Netac               | 166       | 284    | 0.45%   |
| HUAWEI              | 163       | 199    | 0.44%   |
| KIOXIA              | 129       | 157    | 0.35%   |
| GOODRAM             | 126       | 166    | 0.34%   |
| Phison              | 124       | 140    | 0.33%   |
| Corsair             | 116       | 164    | 0.31%   |
| Gigabyte Technology | 101       | 120    | 0.27%   |
| Unknown             | 100       | 110    | 0.27%   |
| JMicron Technology  | 85        | 90     | 0.23%   |
| KingDian            | 77        | 117    | 0.21%   |
| Apple               | 75        | 97     | 0.2%    |
| XrayDisk            | 71        | 93     | 0.19%   |
| Phison Electronics  | 66        | 80     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 417       | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 308       | 0.75%   |
| Seagate ST500LT012-1DG142 500GB    | 299       | 0.73%   |
| Toshiba MQ01ABF050 500GB           | 297       | 0.73%   |
| Toshiba DT01ACA050 500GB           | 296       | 0.72%   |
| Kingston SA400S37240G 240GB SSD    | 289       | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB     | 274       | 0.67%   |
| Kingston SA400S37120G 120GB SSD    | 267       | 0.65%   |
| Toshiba HDWD110 1TB                | 265       | 0.65%   |
| Seagate ST3500418AS 500GB          | 262       | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB           | 241       | 0.59%   |
| Seagate ST9500325AS 500GB          | 235       | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 223       | 0.55%   |
| Kingston SV300S37A120G 120GB SSD   | 223       | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB     | 215       | 0.53%   |
| Toshiba DT01ACA100 1TB             | 212       | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB     | 210       | 0.51%   |
| Samsung SSD 860 EVO 250GB          | 210       | 0.51%   |
| Seagate ST9320325AS 320GB          | 187       | 0.46%   |
| HGST HTS545050A7E680 500GB         | 181       | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 168       | 0.41%   |
| Toshiba MQ01ABD100 1TB             | 156       | 0.38%   |
| WDC WD5000AAKX-001CA0 500GB        | 142       | 0.35%   |
| Seagate ST3250410AS 250GB          | 140       | 0.34%   |
| Samsung SSD 860 EVO 500GB          | 138       | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB     | 137       | 0.34%   |
| Seagate ST380011A 80GB             | 133       | 0.33%   |
| Toshiba MQ04ABF100 1TB             | 129       | 0.32%   |
| Seagate ST380815AS 80GB            | 129       | 0.32%   |
| Seagate ST31000528AS 1TB           | 128       | 0.31%   |
| Seagate ST31000524AS 1TB           | 128       | 0.31%   |
| Hitachi HTS543232A7A384 320GB      | 124       | 0.3%    |
| Seagate ST500LT012-9WS142 500GB    | 123       | 0.3%    |
| Seagate ST3160815AS 160GB          | 122       | 0.3%    |
| HGST HTS545050A7E380 500GB         | 122       | 0.3%    |
| SPCC Solid State Disk 120GB        | 120       | 0.29%   |
| Hitachi HDS721050CLA362 500GB      | 120       | 0.29%   |
| Seagate ST9250315AS 250GB          | 119       | 0.29%   |
| HGST HTS721010A9E630 1TB           | 118       | 0.29%   |
| Crucial CT240BX500SSD1 240GB       | 118       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7377      | 11361  | 34.2%   |
| WDC                 | 6924      | 11058  | 32.1%   |
| Toshiba             | 2686      | 3793   | 12.45%  |
| Hitachi             | 2066      | 2841   | 9.58%   |
| Samsung Electronics | 1012      | 1406   | 4.69%   |
| HGST                | 800       | 1203   | 3.71%   |
| Maxtor              | 284       | 360    | 1.32%   |
| Fujitsu             | 206       | 282    | 0.95%   |
| Unknown             | 58        | 80     | 0.27%   |
| Apple               | 25        | 33     | 0.12%   |
| IBM/Hitachi         | 18        | 21     | 0.08%   |
| External            | 18        | 22     | 0.08%   |
| Hewlett-Packard     | 14        | 44     | 0.06%   |
| USB3.0              | 6         | 6      | 0.03%   |
| USB                 | 5         | 5      | 0.02%   |
| IBM                 | 5         | 5      | 0.02%   |
| PHD 3.0             | 4         | 4      | 0.02%   |
| Lenovo              | 4         | 35     | 0.02%   |
| HGST HTS            | 4         | 4      | 0.02%   |
| ASMT                | 4         | 15     | 0.02%   |
| WD MediaMax         | 3         | 4      | 0.01%   |
| Quantum             | 3         | 3      | 0.01%   |
| KESU                | 3         | 3      | 0.01%   |
| JMicron Technology  | 3         | 3      | 0.01%   |
| CLOVER              | 3         | 3      | 0.01%   |
| Unknown             | 3         | 3      | 0.01%   |
| Synology            | 2         | 3      | 0.01%   |
| SCST_BIO            | 2         | 6      | 0.01%   |
| QNAP                | 2         | 6      | 0.01%   |
| MARSHAL             | 2         | 2      | 0.01%   |
| LIO-ORG             | 2         | 2      | 0.01%   |
| ExcelStor           | 2         | 2      | 0.01%   |
| ASMT106x            | 2         | 3      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.005%  |
| VSTORAGE            | 1         | 1      | 0.005%  |
| USB 3.0             | 1         | 1      | 0.005%  |
| StoreJet            | 1         | 1      | 0.005%  |
| SILICONMOTION       | 1         | 1      | 0.005%  |
| Silicon             | 1         | 1      | 0.005%  |
| SAGE                | 1         | 1      | 0.005%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1631      | 2152   | 15.57%  |
| Samsung Electronics | 1348      | 1983   | 12.87%  |
| WDC                 | 791       | 1032   | 7.55%   |
| China               | 601       | 818    | 5.74%   |
| A-DATA Technology   | 565       | 834    | 5.39%   |
| SanDisk             | 483       | 678    | 4.61%   |
| Crucial             | 466       | 611    | 4.45%   |
| SPCC                | 435       | 576    | 4.15%   |
| Intel               | 360       | 602    | 3.44%   |
| OCZ                 | 336       | 426    | 3.21%   |
| Apacer              | 286       | 367    | 2.73%   |
| Plextor             | 276       | 385    | 2.63%   |
| Smartbuy            | 218       | 281    | 2.08%   |
| Transcend           | 183       | 224    | 1.75%   |
| KingSpec            | 183       | 229    | 1.75%   |
| AMD                 | 174       | 210    | 1.66%   |
| Patriot             | 171       | 219    | 1.63%   |
| Toshiba             | 158       | 215    | 1.51%   |
| Netac               | 127       | 234    | 1.21%   |
| GOODRAM             | 121       | 161    | 1.16%   |
| Corsair             | 108       | 152    | 1.03%   |
| Micron Technology   | 103       | 162    | 0.98%   |
| SK hynix            | 92        | 113    | 0.88%   |
| KingDian            | 76        | 116    | 0.73%   |
| Gigabyte Technology | 66        | 74     | 0.63%   |
| JMicron Technology  | 56        | 57     | 0.53%   |
| XrayDisk            | 54        | 72     | 0.52%   |
| Kingmax             | 47        | 87     | 0.45%   |
| Unknown             | 46        | 52     | 0.44%   |
| Foxline             | 44        | 53     | 0.42%   |
| Apple               | 40        | 47     | 0.38%   |
| LITEON              | 36        | 44     | 0.34%   |
| Hewlett-Packard     | 34        | 59     | 0.32%   |
| Qumo                | 29        | 38     | 0.28%   |
| LITEONIT            | 29        | 48     | 0.28%   |
| AXIOMTEK            | 29        | 31     | 0.28%   |
| Team                | 26        | 32     | 0.25%   |
| Londisk             | 26        | 30     | 0.25%   |
| KingFast            | 26        | 32     | 0.25%   |
| TO Exter            | 25        | 29     | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 18200     | 32645  | 55.59%  |
| SSD     | 9176      | 14331  | 28.03%  |
| NVMe    | 4067      | 5735   | 12.42%  |
| MMC     | 858       | 1167   | 2.62%   |
| Unknown | 437       | 708    | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22572     | 46332  | 79.62%  |
| NVMe | 4063      | 5723   | 14.33%  |
| MMC  | 858       | 1167   | 3.03%   |
| SAS  | 857       | 1364   | 3.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 18902     | 32270  | 68.23%  |
| 0.51-1.0        | 6793      | 11063  | 24.52%  |
| 1.01-2.0        | 1344      | 2305   | 4.85%   |
| 2.01-3.0        | 267       | 467    | 0.96%   |
| 3.01-4.0        | 237       | 440    | 0.86%   |
| 4.01-10.0       | 124       | 311    | 0.45%   |
| 10.01-20.0      | 28        | 109    | 0.1%    |
| More than 100.0 | 7         | 8      | 0.03%   |
| 0               | 2         | 2      | 0.01%   |
| 20.01-50.0      | 1         | 1      | 0.004%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 7793      | 27.14%  |
| 251-500        | 6152      | 21.43%  |
| 501-1000       | 3349      | 11.66%  |
| 1-20           | 3061      | 10.66%  |
| 51-100         | 2704      | 9.42%   |
| 21-50          | 1833      | 6.38%   |
| 1001-2000      | 1610      | 5.61%   |
| Unknown        | 1193      | 4.16%   |
| 2001-3000      | 519       | 1.81%   |
| More than 3000 | 497       | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15766     | 54.23%  |
| 21-50          | 3537      | 12.17%  |
| 101-250        | 2556      | 8.79%   |
| 51-100         | 2293      | 7.89%   |
| 251-500        | 1690      | 5.81%   |
| Unknown        | 1193      | 4.1%    |
| 501-1000       | 1105      | 3.8%    |
| 1001-2000      | 568       | 1.95%   |
| More than 3000 | 197       | 0.68%   |
| 2001-3000      | 164       | 0.56%   |
| 0              | 2         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 161       | 215    | 1.79%   |
| Seagate ST500DM002-1BD142 500GB    | 161       | 202    | 1.79%   |
| Seagate ST3500418AS 500GB          | 115       | 147    | 1.28%   |
| Seagate ST500LT012-9WS142 500GB    | 111       | 131    | 1.24%   |
| Seagate ST9320325AS 320GB          | 101       | 127    | 1.13%   |
| Seagate ST3250410AS 250GB          | 93        | 119    | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 87        | 107    | 0.97%   |
| Seagate ST9250315AS 250GB          | 84        | 103    | 0.94%   |
| Seagate ST500LT012-1DG142 500GB    | 84        | 102    | 0.94%   |
| HGST HTS545050A7E680 500GB         | 79        | 117    | 0.88%   |
| WDC WD5000AAKX-001CA0 500GB        | 70        | 88     | 0.78%   |
| Seagate ST3250310AS 250GB          | 68        | 113    | 0.76%   |
| Seagate ST320LT020-9YG142 320GB    | 65        | 93     | 0.72%   |
| Seagate ST3320613AS 320GB          | 62        | 83     | 0.69%   |
| Seagate ST1000DM003-1CH162 1TB     | 60        | 91     | 0.67%   |
| Seagate ST31000528AS 1TB           | 58        | 69     | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB     | 55        | 65     | 0.61%   |
| HGST HTS545050A7E380 500GB         | 55        | 87     | 0.61%   |
| Hitachi HTS543232A7A384 320GB      | 48        | 54     | 0.54%   |
| Hitachi HDS721050CLA362 500GB      | 48        | 57     | 0.54%   |
| Hitachi HTS545025B9A300 250GB      | 47        | 58     | 0.52%   |
| WDC WD5000AADS-00S9B0 500GB        | 46        | 53     | 0.51%   |
| Seagate ST380011A 80GB             | 45        | 48     | 0.5%    |
| Seagate ST31000524AS 1TB           | 45        | 58     | 0.5%    |
| Seagate ST250DM000-1BD141 250GB    | 45        | 60     | 0.5%    |
| Seagate ST3160815AS 160GB          | 44        | 55     | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB        | 42        | 47     | 0.47%   |
| Seagate ST320LT012-9WS14C 320GB    | 42        | 56     | 0.47%   |
| Kingston SV300S37A120G 120GB SSD   | 41        | 42     | 0.46%   |
| Seagate ST3250318AS 250GB          | 40        | 52     | 0.45%   |
| Hitachi HTS541612J9SA00 120GB      | 39        | 51     | 0.43%   |
| Hitachi HDS721010CLA332 1TB        | 39        | 46     | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 38        | 59     | 0.42%   |
| WDC WD10EARS-00Y5B1 1TB            | 38        | 62     | 0.42%   |
| Toshiba MQ01ABF050 500GB           | 38        | 52     | 0.42%   |
| Toshiba MQ01ABD050 500GB           | 38        | 45     | 0.42%   |
| Hitachi HTS547550A9E384 500GB      | 38        | 53     | 0.42%   |
| Hitachi HDS721616PLA380 160GB      | 38        | 52     | 0.42%   |
| Seagate ST380815AS 80GB            | 36        | 48     | 0.4%    |
| Seagate ST3160811AS 160GB          | 36        | 52     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2935      | 4066   | 34.27%  |
| WDC                 | 2119      | 2947   | 24.74%  |
| Hitachi             | 1009      | 1324   | 11.78%  |
| Toshiba             | 628       | 826    | 7.33%   |
| Samsung Electronics | 537       | 729    | 6.27%   |
| HGST                | 224       | 329    | 2.62%   |
| Maxtor              | 166       | 198    | 1.94%   |
| Kingston            | 153       | 175    | 1.79%   |
| OCZ                 | 72        | 90     | 0.84%   |
| SanDisk             | 65        | 79     | 0.76%   |
| Intel               | 63        | 90     | 0.74%   |
| A-DATA Technology   | 56        | 78     | 0.65%   |
| Fujitsu             | 55        | 72     | 0.64%   |
| SPCC                | 51        | 59     | 0.6%    |
| Corsair             | 37        | 52     | 0.43%   |
| China               | 32        | 40     | 0.37%   |
| SK hynix            | 30        | 40     | 0.35%   |
| KingSpec            | 29        | 33     | 0.34%   |
| Kingmax             | 27        | 49     | 0.32%   |
| Plextor             | 22        | 35     | 0.26%   |
| Crucial             | 21        | 34     | 0.25%   |
| AMD                 | 20        | 25     | 0.23%   |
| IBM/Hitachi         | 16        | 19     | 0.19%   |
| Netac               | 15        | 16     | 0.18%   |
| LITEON              | 14        | 16     | 0.16%   |
| Micron Technology   | 11        | 19     | 0.13%   |
| LITEONIT            | 10        | 16     | 0.12%   |
| Unknown             | 10        | 12     | 0.12%   |
| OCZ-VERTEX3         | 8         | 13     | 0.09%   |
| Transcend           | 7         | 7      | 0.08%   |
| Neo                 | 7         | 14     | 0.08%   |
| KingDian            | 7         | 11     | 0.08%   |
| Apple               | 6         | 7      | 0.07%   |
| Smartbuy            | 5         | 6      | 0.06%   |
| Apacer              | 5         | 5      | 0.06%   |
| XrayDisk            | 4         | 6      | 0.05%   |
| SSSTC               | 4         | 6      | 0.05%   |
| XPG                 | 3         | 7      | 0.04%   |
| Team                | 3         | 4      | 0.04%   |
| Silicon Motion      | 3         | 4      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2934      | 4063   | 38.69%  |
| WDC                 | 2056      | 2858   | 27.11%  |
| Hitachi             | 1009      | 1324   | 13.3%   |
| Toshiba             | 621       | 819    | 8.19%   |
| Samsung Electronics | 483       | 664    | 6.37%   |
| HGST                | 224       | 329    | 2.95%   |
| Maxtor              | 166       | 198    | 2.19%   |
| Fujitsu             | 55        | 72     | 0.73%   |
| IBM/Hitachi         | 16        | 19     | 0.21%   |
| IBM                 | 3         | 3      | 0.04%   |
| Hewlett-Packard     | 3         | 4      | 0.04%   |
| Quantum             | 2         | 2      | 0.03%   |
| MARSHAL             | 2         | 2      | 0.03%   |
| HGST HTS            | 2         | 2      | 0.03%   |
| ASMT                | 2         | 4      | 0.03%   |
| Apple               | 2         | 3      | 0.03%   |
| WD MediaMax         | 1         | 1      | 0.01%   |
| External            | 1         | 1      | 0.01%   |
| ExcelStor           | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6953      | 10370  | 87.74%  |
| SSD  | 915       | 1201   | 11.55%  |
| NVMe | 57        | 79     | 0.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB           | 8         | 10     | 2.84%   |
| Seagate ST31000524AS 1TB           | 7         | 9      | 2.48%   |
| Hitachi HDS721010DLE630 1TB        | 6         | 7      | 2.13%   |
| Seagate ST9500325AS 500GB          | 5         | 5      | 1.77%   |
| Seagate ST3500418AS 500GB          | 5         | 6      | 1.77%   |
| Seagate ST3500412AS 500GB          | 5         | 6      | 1.77%   |
| Samsung Electronics HM321HI 320GB  | 5         | 7      | 1.77%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 1.42%   |
| Seagate ST9320325AS 320GB          | 4         | 5      | 1.42%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 1.42%   |
| HGST HTS545050A7E680 500GB         | 4         | 4      | 1.42%   |
| HGST HTS545050A7E380 500GB         | 4         | 4      | 1.42%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 1.06%   |
| Toshiba MQ01ABD050 500GB           | 3         | 3      | 1.06%   |
| Toshiba MK6465GSX 640GB            | 3         | 3      | 1.06%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 1.06%   |
| Seagate ST3320613AS 320GB          | 3         | 4      | 1.06%   |
| Seagate ST31000333AS 1TB           | 3         | 3      | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.06%   |
| Samsung Electronics SP0411N 40GB   | 3         | 4      | 1.06%   |
| Maxtor 6Y080L0 82GB                | 3         | 3      | 1.06%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 3      | 1.06%   |
| Hitachi HDS721010CLA332 1TB        | 3         | 3      | 1.06%   |
| WDC WD5000AAKS-00V1A0 500GB        | 2         | 2      | 0.71%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 2      | 0.71%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 2      | 0.71%   |
| WDC WD15EARS-00MVWB0 1TB           | 2         | 4      | 0.71%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 0.71%   |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.71%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 0.71%   |
| Seagate ST500DM005 HD502HJ 500GB   | 2         | 3      | 0.71%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 2      | 0.71%   |
| Seagate ST500DM002-1BC142 500GB    | 2         | 2      | 0.71%   |
| Seagate ST3750528AS 752GB          | 2         | 2      | 0.71%   |
| Seagate ST3250318AS 250GB          | 2         | 2      | 0.71%   |
| Seagate ST32000542AS 2TB           | 2         | 4      | 0.71%   |
| Seagate ST3160318AS 160GB          | 2         | 2      | 0.71%   |
| Seagate ST250DM000-1BD141 250GB    | 2         | 2      | 0.71%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 0.71%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 103    | 30.71%  |
| WDC                 | 75        | 92     | 26.79%  |
| Samsung Electronics | 35        | 38     | 12.5%   |
| Hitachi             | 27        | 30     | 9.64%   |
| Toshiba             | 23        | 25     | 8.21%   |
| HGST                | 16        | 18     | 5.71%   |
| Maxtor              | 7         | 7      | 2.5%    |
| Transcend           | 1         | 1      | 0.36%   |
| OCZ                 | 1         | 1      | 0.36%   |
| Intel               | 1         | 1      | 0.36%   |
| IBM-ESXS            | 1         | 2      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |
| GOODRAM             | 1         | 1      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| Crucial             | 1         | 1      | 0.36%   |
| Corsair             | 1         | 1      | 0.36%   |
| Apple               | 1         | 2      | 0.36%   |
| A-DATA Technology   | 1         | 1      | 0.36%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 16852     | 32546  | 55.54%  |
| Malfunc  | 7699      | 11650  | 25.37%  |
| Detected | 5513      | 10063  | 18.17%  |
| Failed   | 276       | 326    | 0.91%   |
| Limited  | 1         | 1      | 0.003%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17767     | 57.93%  |
| AMD                              | 5566      | 18.15%  |
| Samsung Electronics              | 1201      | 3.92%   |
| Nvidia                           | 924       | 3.01%   |
| JMicron Technology               | 839       | 2.74%   |
| SanDisk                          | 511       | 1.67%   |
| Marvell Technology Group         | 455       | 1.48%   |
| ASMedia Technology               | 427       | 1.39%   |
| SK hynix                         | 365       | 1.19%   |
| Kingston Technology Company      | 342       | 1.12%   |
| Phison Electronics               | 326       | 1.06%   |
| Silicon Motion                   | 273       | 0.89%   |
| VIA Technologies                 | 229       | 0.75%   |
| Micron Technology                | 149       | 0.49%   |
| KIOXIA                           | 142       | 0.46%   |
| ADATA Technology                 | 130       | 0.42%   |
| Toshiba America Info Systems     | 121       | 0.39%   |
| Silicon Integrated Systems [SiS] | 116       | 0.38%   |
| Realtek Semiconductor            | 102       | 0.33%   |
| Union Memory (Shenzhen)          | 68        | 0.22%   |
| LSI Logic / Symbios Logic        | 63        | 0.21%   |
| Broadcom / LSI                   | 51        | 0.17%   |
| Solid State Storage Technology   | 50        | 0.16%   |
| INNOGRIT                         | 46        | 0.15%   |
| Silicon Image                    | 39        | 0.13%   |
| Adaptec                          | 38        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 37        | 0.12%   |
| Lite-On Technology               | 37        | 0.12%   |
| Shenzhen Longsys Electronics     | 35        | 0.11%   |
| Micron/Crucial Technology        | 32        | 0.1%    |
| Integrated Technology Express    | 31        | 0.1%    |
| Hewlett-Packard                  | 31        | 0.1%    |
| Netac Technology                 | 30        | 0.1%    |
| Yangtze Memory Technologies      | 10        | 0.03%   |
| Apple                            | 8         | 0.03%   |
| O2 Micro                         | 6         | 0.02%   |
| Lenovo                           | 6         | 0.02%   |
| ULi Electronics                  | 5         | 0.02%   |
| Seagate Technology               | 5         | 0.02%   |
| MCST                             | 5         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2917      | 7.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1491      | 3.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1443      | 3.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1207      | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1202      | 3.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1088      | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1028      | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 978       | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 826       | 2.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 752       | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 677       | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 661       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 620       | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 619       | 1.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 584       | 1.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 540       | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 526       | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 495       | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 494       | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 491       | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 471       | 1.22%   |
| Nvidia MCP61 SATA Controller                                                            | 407       | 1.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 406       | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 398       | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 398       | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 380       | 0.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 349       | 0.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 348       | 0.9%    |
| Samsung NVMe SSD Controller 980                                                         | 333       | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 322       | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 320       | 0.83%   |
| JMicron JMB368 IDE controller                                                           | 310       | 0.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 305       | 0.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 304       | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 297       | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 276       | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 272       | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 267       | 0.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 251       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 250       | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 18692     | 59.3%   |
| IDE  | 7668      | 24.33%  |
| NVMe | 4095      | 12.99%  |
| RAID | 953       | 3.02%   |
| SAS  | 86        | 0.27%   |
| SCSI | 25        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 18869     | 72.91%  |
| AMD          | 6902      | 26.67%  |
| ARM          | 74        | 0.29%   |
| CentaurHauls | 9         | 0.03%   |
| Qualcomm     | 6         | 0.02%   |
| Unknown      | 6         | 0.02%   |
| HiSilicon    | 4         | 0.02%   |
| PowerMac7,2  | 1         | 0.004%  |
| PowerBook5,6 | 1         | 0.004%  |
| MIPS         | 1         | 0.004%  |
| MBE8C-PC     | 1         | 0.004%  |
| Loongson     | 1         | 0.004%  |
| Elbrus-MCST  | 1         | 0.004%  |
| E8C/EATX     | 1         | 0.004%  |
| E8C-SWTX     | 1         | 0.004%  |
| E8C-mITX     | 1         | 0.004%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 171       | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 169       | 0.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 164       | 0.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 161       | 0.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 157       | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 155       | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 144       | 0.55%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 132       | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 132       | 0.51%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 126       | 0.48%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 126       | 0.48%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 122       | 0.47%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 119       | 0.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 117       | 0.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 117       | 0.45%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 117       | 0.45%   |
| AMD Ryzen 5 3600 6-Core Processor             | 117       | 0.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 116       | 0.45%   |
| Intel Pentium 4 CPU 3.00GHz                   | 113       | 0.43%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 112       | 0.43%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 111       | 0.43%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 111       | 0.43%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 109       | 0.42%   |
| AMD FX-6300 Six-Core Processor                | 109       | 0.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 107       | 0.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 106       | 0.41%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 106       | 0.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 104       | 0.4%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 104       | 0.4%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 98        | 0.38%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 95        | 0.36%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 95        | 0.36%   |
| AMD Athlon II X2 250 Processor                | 95        | 0.36%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 94        | 0.36%   |
| AMD FX-8350 Eight-Core Processor              | 94        | 0.36%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 91        | 0.35%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 89        | 0.34%   |
| AMD E-450 APU with Radeon HD Graphics         | 89        | 0.34%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 88        | 0.34%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 88        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4207      | 16.17%  |
| Intel Core i3           | 2969      | 11.41%  |
| Intel Core i7           | 1934      | 7.43%   |
| Intel Celeron           | 1781      | 6.85%   |
| Intel Pentium           | 1622      | 6.23%   |
| Intel Core 2 Duo        | 1432      | 5.5%    |
| AMD Ryzen 5             | 1146      | 4.4%    |
| Intel Atom              | 928       | 3.57%   |
| Other                   | 893       | 3.43%   |
| Intel Xeon              | 790       | 3.04%   |
| AMD FX                  | 645       | 2.48%   |
| Intel Pentium Dual-Core | 605       | 2.33%   |
| AMD Ryzen 7             | 533       | 2.05%   |
| AMD Athlon 64 X2        | 441       | 1.7%    |
| Intel Core 2 Quad       | 360       | 1.38%   |
| AMD Athlon II X2        | 332       | 1.28%   |
| AMD A6                  | 331       | 1.27%   |
| AMD Ryzen 3             | 327       | 1.26%   |
| AMD A8                  | 278       | 1.07%   |
| AMD A4                  | 271       | 1.04%   |
| AMD A10                 | 267       | 1.03%   |
| Intel Pentium 4         | 261       | 1%      |
| Intel Pentium Dual      | 244       | 0.94%   |
| Intel Core 2            | 237       | 0.91%   |
| AMD Phenom II X4        | 208       | 0.8%    |
| AMD E                   | 172       | 0.66%   |
| AMD Athlon II X4        | 155       | 0.6%    |
| Intel Genuine           | 147       | 0.57%   |
| AMD E1                  | 129       | 0.5%    |
| AMD Athlon              | 127       | 0.49%   |
| AMD E2                  | 122       | 0.47%   |
| AMD Athlon II X3        | 121       | 0.47%   |
| Intel Pentium D         | 109       | 0.42%   |
| Intel Pentium Gold      | 105       | 0.4%    |
| AMD Ryzen 9             | 105       | 0.4%    |
| AMD Phenom              | 102       | 0.39%   |
| Intel Pentium Silver    | 99        | 0.38%   |
| AMD Athlon 64           | 94        | 0.36%   |
| AMD Phenom II X6        | 85        | 0.33%   |
| Intel Celeron M         | 79        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 12786     | 48.64%  |
| 4       | 7341      | 27.93%  |
| 6       | 1832      | 6.97%   |
| 1       | 1382      | 5.26%   |
| Unknown | 1107      | 4.21%   |
| 8       | 943       | 3.59%   |
| 3       | 346       | 1.32%   |
| 12      | 202       | 0.77%   |
| 10      | 87        | 0.33%   |
| 16      | 81        | 0.31%   |
| 24      | 49        | 0.19%   |
| 14      | 38        | 0.14%   |
| 28      | 23        | 0.09%   |
| 20      | 19        | 0.07%   |
| 32      | 18        | 0.07%   |
| 18      | 6         | 0.02%   |
| 96      | 4         | 0.02%   |
| 44      | 4         | 0.02%   |
| 40      | 4         | 0.02%   |
| 48      | 3         | 0.01%   |
| 36      | 3         | 0.01%   |
| 56      | 2         | 0.01%   |
| 192     | 1         | 0.004%  |
| 128     | 1         | 0.004%  |
| 80      | 1         | 0.004%  |
| 72      | 1         | 0.004%  |
| 64      | 1         | 0.004%  |
| 22      | 1         | 0.004%  |
| 15      | 1         | 0.004%  |
| 5       | 1         | 0.004%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 25556     | 98.7%   |
| 2       | 286       | 1.1%    |
| Unknown | 39        | 0.15%   |
| 4       | 8         | 0.03%   |
| 3       | 2         | 0.01%   |
| 8       | 1         | 0.004%  |
| 0       | 1         | 0.004%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 12672     | 48.24%  |
| 1       | 12483     | 47.52%  |
| Unknown | 1107      | 4.21%   |
| 8       | 2         | 0.01%   |
| 6       | 2         | 0.01%   |
| 4       | 1         | 0.004%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25080     | 96.8%   |
| 32-bit         | 571       | 2.2%    |
| Unknown        | 243       | 0.94%   |
| 64-bit         | 16        | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3048      | 11.46%  |
| 0x206a7    | 2321      | 8.73%   |
| 0x306a9    | 1967      | 7.4%    |
| 0x1067a    | 1551      | 5.83%   |
| 0x306c3    | 1132      | 4.26%   |
| 0x010000c8 | 642       | 2.41%   |
| 0x6fd      | 626       | 2.35%   |
| 0x20655    | 581       | 2.19%   |
| 0x906ea    | 547       | 2.06%   |
| 0x506e3    | 485       | 1.82%   |
| 0x10676    | 439       | 1.65%   |
| 0x906e9    | 414       | 1.56%   |
| 0x06001119 | 405       | 1.52%   |
| 0x106ca    | 377       | 1.42%   |
| 0x806ec    | 349       | 1.31%   |
| 0x30678    | 345       | 1.3%    |
| 0x40651    | 326       | 1.23%   |
| 0x806ea    | 319       | 1.2%    |
| 0x08108109 | 305       | 1.15%   |
| 0x6fb      | 287       | 1.08%   |
| 0x806c1    | 277       | 1.04%   |
| 0x406c4    | 266       | 1%      |
| 0x806e9    | 262       | 0.99%   |
| 0x406e3    | 259       | 0.97%   |
| 0xa0653    | 236       | 0.89%   |
| 0x06000852 | 234       | 0.88%   |
| 0x20652    | 225       | 0.85%   |
| 0x03000027 | 216       | 0.81%   |
| 0x306d4    | 195       | 0.73%   |
| 0x05000119 | 190       | 0.71%   |
| 0x0a50000c | 185       | 0.7%    |
| 0x0800820d | 182       | 0.68%   |
| 0x08701021 | 181       | 0.68%   |
| 0x0600084f | 171       | 0.64%   |
| 0x6f6      | 163       | 0.61%   |
| 0x506c9    | 163       | 0.61%   |
| 0x07030105 | 161       | 0.61%   |
| 0x906eb    | 157       | 0.59%   |
| 0x106e5    | 157       | 0.59%   |
| 0x06006705 | 155       | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 2563      | 9.85%   |
| KabyLake         | 2532      | 9.73%   |
| IvyBridge        | 2202      | 8.46%   |
| Penryn           | 2046      | 7.86%   |
| Haswell          | 1691      | 6.5%    |
| Core             | 1476      | 5.67%   |
| K10              | 1263      | 4.85%   |
| Piledriver       | 950       | 3.65%   |
| Westmere         | 910       | 3.5%    |
| Skylake          | 904       | 3.47%   |
| Silvermont       | 853       | 3.28%   |
| Zen+             | 690       | 2.65%   |
| Unknown          | 680       | 2.61%   |
| K8 Hammer        | 669       | 2.57%   |
| Bonnell          | 649       | 2.49%   |
| Zen 2            | 590       | 2.27%   |
| NetBurst         | 488       | 1.88%   |
| CometLake        | 443       | 1.7%    |
| Zen              | 429       | 1.65%   |
| Zen 3            | 406       | 1.56%   |
| TigerLake        | 361       | 1.39%   |
| Excavator        | 359       | 1.38%   |
| Bobcat           | 296       | 1.14%   |
| Broadwell        | 292       | 1.12%   |
| Goldmont plus    | 280       | 1.08%   |
| K10 Llano        | 245       | 0.94%   |
| Nehalem          | 226       | 0.87%   |
| Icelake          | 215       | 0.83%   |
| Puma             | 210       | 0.81%   |
| Goldmont         | 201       | 0.77%   |
| P6               | 193       | 0.74%   |
| Alderlake Hybrid | 171       | 0.66%   |
| Bulldozer        | 145       | 0.56%   |
| Steamroller      | 130       | 0.5%    |
| Jaguar           | 123       | 0.47%   |
| K8 & K10 hybrid  | 71        | 0.27%   |
| Tremont          | 57        | 0.22%   |
| K6               | 11        | 0.04%   |
| Gracemont        | 1         | 0.004%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 12258     | 40.6%   |
| Nvidia                                       | 9916      | 32.85%  |
| AMD                                          | 7604      | 25.19%  |
| ASPEED Technology                            | 163       | 0.54%   |
| Matrox Electronics Systems                   | 157       | 0.52%   |
| Silicon Integrated Systems [SiS]             | 36        | 0.12%   |
| VIA Technologies                             | 27        | 0.09%   |
| ATI Technologies                             | 10        | 0.03%   |
| Huawei Technologies                          | 8         | 0.03%   |
| Zhaoxin                                      | 3         | 0.01%   |
| S3 Graphics                                  | 3         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.01%   |
| Silicon Motion                               | 2         | 0.01%   |
| Loongson Technology                          | 1         | 0.003%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1699      | 5.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1163      | 3.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 464       | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 433       | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 416       | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 413       | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 401       | 1.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 364       | 1.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 364       | 1.14%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 361       | 1.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 337       | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 328       | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 326       | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 309       | 0.97%   |
| AMD Renoir                                                                               | 286       | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 282       | 0.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 281       | 0.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 280       | 0.88%   |
| Intel UHD Graphics 620                                                                   | 274       | 0.86%   |
| Intel HD Graphics 620                                                                    | 273       | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 265       | 0.83%   |
| Nvidia GT218 [GeForce 210]                                                               | 262       | 0.82%   |
| Intel HD Graphics 630                                                                    | 250       | 0.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 250       | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 246       | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 246       | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 246       | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 244       | 0.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 244       | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 233       | 0.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 232       | 0.73%   |
| Intel HD Graphics 530                                                                    | 226       | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 226       | 0.71%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 223       | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 218       | 0.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 216       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 202       | 0.63%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 196       | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 195       | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 185       | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Intel                     | 8404      | 32.07%  |
| 1 x Nvidia                    | 6624      | 25.27%  |
| 1 x AMD                       | 5812      | 22.18%  |
| Intel + Nvidia                | 2990      | 11.41%  |
| 2 x AMD                       | 904       | 3.45%   |
| Intel + AMD                   | 651       | 2.48%   |
| AMD + Nvidia                  | 251       | 0.96%   |
| 1 x Matrox                    | 146       | 0.56%   |
| 1 x ASPEED                    | 143       | 0.55%   |
| Other                         | 101       | 0.39%   |
| 2 x Nvidia                    | 36        | 0.14%   |
| 1 x SiS                       | 36        | 0.14%   |
| 1 x VIA                       | 27        | 0.1%    |
| 2 x Intel                     | 19        | 0.07%   |
| Nvidia + Matrox               | 11        | 0.04%   |
| Nvidia + ASPEED               | 10        | 0.04%   |
| 1 x Huawei Technologies       | 8         | 0.03%   |
| AMD + ASPEED                  | 7         | 0.03%   |
| 3 x AMD                       | 4         | 0.02%   |
| 3 x Nvidia                    | 3         | 0.01%   |
| 1 x Zhaoxin                   | 2         | 0.01%   |
| 1 x XGI                       | 2         | 0.01%   |
| 1 x Silicon Motion            | 2         | 0.01%   |
| 1 x S3 Graphics               | 2         | 0.01%   |
| Intel + 2 x Nvidia            | 2         | 0.01%   |
| Intel + 2 x AMD               | 2         | 0.01%   |
| 3 x Nvidia + 1 x ASPEED       | 1         | 0.004%  |
| 2 x Nvidia + 1 x ASPEED       | 1         | 0.004%  |
| 2 x AMD + 1 x Nvidia          | 1         | 0.004%  |
| Nvidia + Zhaoxin              | 1         | 0.004%  |
| 1 x Loongson Technology       | 1         | 0.004%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.004%  |
| Intel + ASPEED                | 1         | 0.004%  |
| Intel + AMD + 4 x Nvidia      | 1         | 0.004%  |
| AMD + 2 x Nvidia              | 1         | 0.004%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 20895     | 77.95%  |
| Proprietary | 3670      | 13.69%  |
| Unknown     | 2242      | 8.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9178      | 33.76%  |
| 1.01-2.0   | 6093      | 22.41%  |
| 0.01-0.5   | 5531      | 20.35%  |
| 0.51-1.0   | 3468      | 12.76%  |
| 3.01-4.0   | 1769      | 6.51%   |
| 7.01-8.0   | 497       | 1.83%   |
| 5.01-6.0   | 314       | 1.16%   |
| 2.01-3.0   | 189       | 0.7%    |
| 8.01-16.0  | 124       | 0.46%   |
| 16.01-24.0 | 14        | 0.05%   |
| 4.01-5.0   | 6         | 0.02%   |
| 24.01-32.0 | 1         | 0.004%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4550      | 18.09%  |
| AU Optronics            | 2648      | 10.53%  |
| LG Display              | 1909      | 7.59%   |
| Goldstar                | 1796      | 7.14%   |
| BOE                     | 1601      | 6.36%   |
| Chimei Innolux          | 1518      | 6.03%   |
| Acer                    | 1438      | 5.72%   |
| BenQ                    | 1122      | 4.46%   |
| Philips                 | 896       | 3.56%   |
| Chi Mei Optoelectronics | 838       | 3.33%   |
| Dell                    | 681       | 2.71%   |
| AOC                     | 644       | 2.56%   |
| ViewSonic               | 628       | 2.5%    |
| Ancor Communications    | 438       | 1.74%   |
| Hewlett-Packard         | 432       | 1.72%   |
| Lenovo                  | 341       | 1.36%   |
| NEC Computers           | 302       | 1.2%    |
| LG Philips              | 231       | 0.92%   |
| HannStar                | 205       | 0.81%   |
| Iiyama                  | 199       | 0.79%   |
| Sony                    | 188       | 0.75%   |
| PANDA                   | 172       | 0.68%   |
| Apple                   | 143       | 0.57%   |
| InfoVision              | 127       | 0.5%    |
| Sharp                   | 119       | 0.47%   |
| CPT                     | 117       | 0.47%   |
| ASUSTek Computer        | 109       | 0.43%   |
| Unknown                 | 94        | 0.37%   |
| LG Electronics          | 66        | 0.26%   |
| Envision Peripherals    | 65        | 0.26%   |
| Plain Tree Systems      | 60        | 0.24%   |
| Toshiba                 | 56        | 0.22%   |
| Packard Bell            | 54        | 0.21%   |
| HHT                     | 49        | 0.19%   |
| Mi                      | 46        | 0.18%   |
| MSI                     | 42        | 0.17%   |
| CSO                     | 40        | 0.16%   |
| HUAWEI                  | 38        | 0.15%   |
| TMX                     | 37        | 0.15%   |
| ___                     | 35        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 234       | 0.91%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 208       | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 180       | 0.7%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 160       | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 157       | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 110       | 0.43%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 106       | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 103       | 0.4%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 95        | 0.37%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 95        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 94        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 89        | 0.35%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 88        | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 87        | 0.34%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 79        | 0.31%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 77        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 75        | 0.29%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 75        | 0.29%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 74        | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 74        | 0.29%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                        | 73        | 0.28%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch     | 71        | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 71        | 0.28%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 69        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 68        | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 65        | 0.25%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 65        | 0.25%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 65        | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 65        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 63        | 0.24%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 62        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 61        | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 61        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 58        | 0.23%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 57        | 0.22%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 57        | 0.22%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 54        | 0.21%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 54        | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 54        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 52        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 9404      | 38.24%  |
| 1366x768 (WXGA)    | 5510      | 22.41%  |
| 1280x1024 (SXGA)   | 2467      | 10.03%  |
| 1600x900 (HD+)     | 1231      | 5.01%   |
| 1280x800 (WXGA)    | 807       | 3.28%   |
| 1440x900 (WXGA+)   | 778       | 3.16%   |
| 1680x1050 (WSXGA+) | 750       | 3.05%   |
| 3840x2160 (4K)     | 658       | 2.68%   |
| 2560x1440 (QHD)    | 625       | 2.54%   |
| 1024x600           | 392       | 1.59%   |
| 1920x1200 (WUXGA)  | 373       | 1.52%   |
| 1360x768           | 221       | 0.9%    |
| 1024x768 (XGA)     | 206       | 0.84%   |
| 2560x1080          | 144       | 0.59%   |
| Unknown            | 107       | 0.44%   |
| 1600x1200          | 103       | 0.42%   |
| 2560x1600          | 91        | 0.37%   |
| 3440x1440          | 87        | 0.35%   |
| 2160x1440          | 70        | 0.28%   |
| 1280x720 (HD)      | 58        | 0.24%   |
| 1920x540           | 41        | 0.17%   |
| 2880x1800          | 40        | 0.16%   |
| 2288x1287          | 38        | 0.15%   |
| 1400x1050          | 37        | 0.15%   |
| 800x1280           | 31        | 0.13%   |
| 3840x1080          | 31        | 0.13%   |
| 3200x2000          | 19        | 0.08%   |
| 1152x864           | 16        | 0.07%   |
| 2048x1536          | 14        | 0.06%   |
| 1680x945           | 14        | 0.06%   |
| 1280x960           | 14        | 0.06%   |
| 2520x1680          | 13        | 0.05%   |
| 3000x2000          | 12        | 0.05%   |
| 2048x1152          | 11        | 0.04%   |
| 4480x1440          | 10        | 0.04%   |
| 3840x2400          | 10        | 0.04%   |
| 1920x1440          | 8         | 0.03%   |
| 3200x1800 (QHD+)   | 7         | 0.03%   |
| 2880x1620          | 7         | 0.03%   |
| 2240x1400          | 7         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7383      | 29.3%   |
| 17      | 2268      | 9%      |
| 21      | 2136      | 8.48%   |
| 23      | 1882      | 7.47%   |
| 19      | 1758      | 6.98%   |
| 24      | 1540      | 6.11%   |
| 13      | 1124      | 4.46%   |
| 14      | 1075      | 4.27%   |
| 27      | 1024      | 4.06%   |
| 18      | 742       | 2.94%   |
| 20      | 606       | 2.4%    |
| Unknown | 570       | 2.26%   |
| 22      | 440       | 1.75%   |
| 10      | 409       | 1.62%   |
| 11      | 285       | 1.13%   |
| 12      | 252       | 1%      |
| 31      | 243       | 0.96%   |
| 34      | 190       | 0.75%   |
| 16      | 180       | 0.71%   |
| 40      | 147       | 0.58%   |
| 54      | 117       | 0.46%   |
| 32      | 113       | 0.45%   |
| 72      | 109       | 0.43%   |
| 26      | 79        | 0.31%   |
| 52      | 66        | 0.26%   |
| 25      | 50        | 0.2%    |
| 84      | 48        | 0.19%   |
| 48      | 33        | 0.13%   |
| 46      | 33        | 0.13%   |
| 42      | 33        | 0.13%   |
| 28      | 27        | 0.11%   |
| 142     | 26        | 0.1%    |
| 7       | 25        | 0.1%    |
| 8       | 23        | 0.09%   |
| 43      | 20        | 0.08%   |
| 65      | 15        | 0.06%   |
| 33      | 15        | 0.06%   |
| 29      | 15        | 0.06%   |
| 37      | 11        | 0.04%   |
| 50      | 9         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 10039     | 40.28%  |
| 401-500        | 4456      | 17.88%  |
| 501-600        | 4309      | 17.29%  |
| 351-400        | 2515      | 10.09%  |
| 201-300        | 1586      | 6.36%   |
| Unknown        | 570       | 2.29%   |
| 601-700        | 344       | 1.38%   |
| 701-800        | 325       | 1.3%    |
| 1001-1500      | 303       | 1.22%   |
| 1501-2000      | 164       | 0.66%   |
| 801-900        | 122       | 0.49%   |
| 901-1000       | 106       | 0.43%   |
| More than 2000 | 32        | 0.13%   |
| 1-100          | 30        | 0.12%   |
| 101-200        | 23        | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 17136     | 71.73%  |
| 16/10   | 2822      | 11.81%  |
| 5/4     | 2338      | 9.79%   |
| 4/3     | 564       | 2.36%   |
| Unknown | 409       | 1.71%   |
| 21/9    | 257       | 1.08%   |
| 3/2     | 241       | 1.01%   |
| 6/5     | 49        | 0.21%   |
| 1.00    | 26        | 0.11%   |
| 0.67    | 25        | 0.1%    |
| 32/9    | 11        | 0.05%   |
| 3.73    | 2         | 0.01%   |
| 2.00    | 2         | 0.01%   |
| 0.62    | 2         | 0.01%   |
| 0.45    | 2         | 0.01%   |
| 3.40    | 1         | 0.004%  |
| 1.96    | 1         | 0.004%  |
| 0.80    | 1         | 0.004%  |
| 0.56    | 1         | 0.004%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7285      | 29.1%   |
| 201-250        | 5066      | 20.24%  |
| 151-200        | 2946      | 11.77%  |
| 141-150        | 1761      | 7.03%   |
| 81-90          | 1676      | 6.69%   |
| 301-350        | 1097      | 4.38%   |
| 121-130        | 893       | 3.57%   |
| 351-500        | 583       | 2.33%   |
| Unknown        | 570       | 2.28%   |
| 71-80          | 522       | 2.09%   |
| More than 1000 | 457       | 1.83%   |
| 251-300        | 438       | 1.75%   |
| 41-50          | 412       | 1.65%   |
| 51-60          | 286       | 1.14%   |
| 501-1000       | 273       | 1.09%   |
| 131-140        | 220       | 0.88%   |
| 61-70          | 204       | 0.81%   |
| 111-120        | 195       | 0.78%   |
| 91-100         | 98        | 0.39%   |
| 1-40           | 53        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 10487     | 42.87%  |
| 101-120       | 7892      | 32.26%  |
| 121-160       | 4172      | 17.05%  |
| 161-240       | 661       | 2.7%    |
| Unknown       | 570       | 2.33%   |
| 1-50          | 515       | 2.11%   |
| More than 240 | 168       | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 22245     | 84.28%  |
| 2     | 2123      | 8.04%   |
| 0     | 1896      | 7.18%   |
| 3     | 127       | 0.48%   |
| 4     | 4         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 16564     | 43.32%  |
| Qualcomm Atheros                  | 6470      | 16.92%  |
| Intel                             | 6287      | 16.44%  |
| Broadcom                          | 2125      | 5.56%   |
| Nvidia                            | 755       | 1.97%   |
| Marvell Technology Group          | 719       | 1.88%   |
| Ralink                            | 572       | 1.5%    |
| Broadcom Limited                  | 556       | 1.45%   |
| Huawei Technologies               | 498       | 1.3%    |
| Ralink Technology                 | 497       | 1.3%    |
| TP-Link                           | 342       | 0.89%   |
| MediaTek                          | 334       | 0.87%   |
| VIA Technologies                  | 195       | 0.51%   |
| Xiaomi                            | 181       | 0.47%   |
| D-Link                            | 167       | 0.44%   |
| D-Link System                     | 159       | 0.42%   |
| ASUSTek Computer                  | 143       | 0.37%   |
| Qualcomm Atheros Communications   | 127       | 0.33%   |
| JMicron Technology                | 126       | 0.33%   |
| Attansic Technology               | 112       | 0.29%   |
| ZTE WCDMA Technologies MSM        | 108       | 0.28%   |
| Samsung Electronics               | 99        | 0.26%   |
| Silicon Integrated Systems [SiS]  | 79        | 0.21%   |
| Qualcomm                          | 66        | 0.17%   |
| Mellanox Technologies             | 58        | 0.15%   |
| ASIX Electronics                  | 57        | 0.15%   |
| Sundance Technology Inc / IC Plus | 37        | 0.1%    |
| Gemtek                            | 35        | 0.09%   |
| 3Com                              | 33        | 0.09%   |
| Sierra Wireless                   | 30        | 0.08%   |
| Microsoft                         | 30        | 0.08%   |
| IBM                               | 27        | 0.07%   |
| Hewlett-Packard                   | 26        | 0.07%   |
| Ericsson Business Mobile Networks | 25        | 0.07%   |
| Lenovo                            | 24        | 0.06%   |
| Vimtron Electronics               | 23        | 0.06%   |
| OPPO Electronics                  | 23        | 0.06%   |
| NetGear                           | 23        | 0.06%   |
| HTC (High Tech Computer)          | 23        | 0.06%   |
| Mercucys                          | 22        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 12150     | 28.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2166      | 5.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1490      | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 908       | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 653       | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 582       | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 546       | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 539       | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 489       | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 441       | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 439       | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 378       | 0.88%   |
| Nvidia MCP61 Ethernet                                                   | 362       | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 356       | 0.83%   |
| Intel Wi-Fi 6 AX200                                                     | 340       | 0.79%   |
| Ralink MT7601U Wireless Adapter                                         | 313       | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 312       | 0.73%   |
| Intel Wi-Fi 6 AX201                                                     | 288       | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 281       | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 259       | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 257       | 0.6%    |
| Intel Wireless 8265 / 8275                                              | 253       | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 250       | 0.58%   |
| Intel Wireless 7265                                                     | 249       | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 245       | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                    | 242       | 0.56%   |
| Huawei Modem/Networkcard                                                | 238       | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 231       | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 224       | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                       | 224       | 0.52%   |
| Intel Wireless 3165                                                     | 224       | 0.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 219       | 0.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 216       | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 211       | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 205       | 0.48%   |
| Intel I211 Gigabit Network Connection                                   | 202       | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 202       | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 199       | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 198       | 0.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 194       | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 4713      | 28.74%  |
| Intel                             | 4443      | 27.09%  |
| Realtek Semiconductor             | 3145      | 19.18%  |
| Broadcom                          | 1458      | 8.89%   |
| Ralink                            | 572       | 3.49%   |
| Ralink Technology                 | 497       | 3.03%   |
| TP-Link                           | 300       | 1.83%   |
| Broadcom Limited                  | 284       | 1.73%   |
| MediaTek                          | 247       | 1.51%   |
| D-Link                            | 145       | 0.88%   |
| ASUSTek Computer                  | 132       | 0.8%    |
| Qualcomm Atheros Communications   | 127       | 0.77%   |
| D-Link System                     | 70        | 0.43%   |
| Sierra Wireless                   | 30        | 0.18%   |
| Microsoft                         | 30        | 0.18%   |
| Qualcomm                          | 26        | 0.16%   |
| NetGear                           | 22        | 0.13%   |
| Mercucys                          | 22        | 0.13%   |
| IMC Networks                      | 16        | 0.1%    |
| ZyXEL Communications              | 15        | 0.09%   |
| Tenda                             | 13        | 0.08%   |
| Fibocom                           | 12        | 0.07%   |
| Xiaomi                            | 11        | 0.07%   |
| Dell                              | 10        | 0.06%   |
| Micro Star International          | 8         | 0.05%   |
| Edimax Technology                 | 6         | 0.04%   |
| Marvell Technology Group          | 5         | 0.03%   |
| Ericsson Business Mobile Networks | 5         | 0.03%   |
| ZyDAS                             | 3         | 0.02%   |
| VIA Technologies                  | 3         | 0.02%   |
| Texas Instruments                 | 3         | 0.02%   |
| Linksys                           | 3         | 0.02%   |
| Hewlett-Packard                   | 3         | 0.02%   |
| Wacom                             | 2         | 0.01%   |
| TRENDnet                          | 2         | 0.01%   |
| Fujitsu Siemens Computers         | 2         | 0.01%   |
| ASUSTek Computer (wrong ID)       | 2         | 0.01%   |
| Z-Com                             | 1         | 0.01%   |
| Wilocity                          | 1         | 0.01%   |
| Quectel Wireless Solutions        | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1490      | 9.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 908       | 5.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 653       | 3.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 582       | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 539       | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 441       | 2.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 439       | 2.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 378       | 2.29%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 356       | 2.15%   |
| Intel Wi-Fi 6 AX200                                                     | 340       | 2.06%   |
| Ralink MT7601U Wireless Adapter                                         | 313       | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 312       | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 288       | 1.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 281       | 1.7%    |
| Intel Wireless 8265 / 8275                                              | 253       | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 250       | 1.51%   |
| Intel Wireless 7265                                                     | 249       | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 224       | 1.35%   |
| Intel Wireless 3165                                                     | 224       | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 219       | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 202       | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 199       | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 194       | 1.17%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 193       | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 193       | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 159       | 0.96%   |
| Intel WiFi Link 5100                                                    | 157       | 0.95%   |
| Intel Wireless 7260                                                     | 149       | 0.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 145       | 0.88%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 142       | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 134       | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 128       | 0.77%   |
| Intel Centrino Wireless-N 130                                           | 128       | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 126       | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 125       | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 122       | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 119       | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 113       | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 105       | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                         | 104       | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 15363     | 60.69%  |
| Intel                                  | 2877      | 11.37%  |
| Qualcomm Atheros                       | 2563      | 10.12%  |
| Broadcom                               | 866       | 3.42%   |
| Nvidia                                 | 754       | 2.98%   |
| Marvell Technology Group               | 714       | 2.82%   |
| Broadcom Limited                       | 282       | 1.11%   |
| VIA Technologies                       | 190       | 0.75%   |
| Xiaomi                                 | 170       | 0.67%   |
| Huawei Technologies                    | 168       | 0.66%   |
| JMicron Technology                     | 126       | 0.5%    |
| Attansic Technology                    | 112       | 0.44%   |
| ZTE WCDMA Technologies MSM             | 103       | 0.41%   |
| Samsung Electronics                    | 99        | 0.39%   |
| D-Link System                          | 90        | 0.36%   |
| MediaTek                               | 84        | 0.33%   |
| Silicon Integrated Systems [SiS]       | 78        | 0.31%   |
| ASIX Electronics                       | 57        | 0.23%   |
| TP-Link                                | 43        | 0.17%   |
| Mellanox Technologies                  | 43        | 0.17%   |
| Qualcomm                               | 40        | 0.16%   |
| Sundance Technology Inc / IC Plus      | 37        | 0.15%   |
| Gemtek                                 | 34        | 0.13%   |
| 3Com                                   | 33        | 0.13%   |
| IBM                                    | 27        | 0.11%   |
| Lenovo                                 | 24        | 0.09%   |
| Vimtron Electronics                    | 23        | 0.09%   |
| OPPO Electronics                       | 23        | 0.09%   |
| HTC (High Tech Computer)               | 23        | 0.09%   |
| D-Link                                 | 22        | 0.09%   |
| Sony Ericsson Mobile Communications AB | 15        | 0.06%   |
| Aquantia                               | 15        | 0.06%   |
| Spreadtrum Communications              | 14        | 0.06%   |
| HMD Global                             | 14        | 0.06%   |
| T & A Mobile Phones                    | 12        | 0.05%   |
| GCT Semiconductor                      | 12        | 0.05%   |
| ASUSTek Computer                       | 12        | 0.05%   |
| ICS Advent                             | 11        | 0.04%   |
| Apple                                  | 11        | 0.04%   |
| Microchip Technology                   | 10        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12150     | 47.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2166      | 8.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 546       | 2.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 489       | 1.9%    |
| Nvidia MCP61 Ethernet                                             | 362       | 1.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 259       | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 257       | 1%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 245       | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 242       | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 231       | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 224       | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 216       | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 211       | 0.82%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 205       | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 202       | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 198       | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 191       | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 178       | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 136       | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 135       | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 132       | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 131       | 0.51%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 129       | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 122       | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 122       | 0.47%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 112       | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 111       | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 106       | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 103       | 0.4%    |
| Intel Ethernet Controller I225-V                                  | 98        | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 97        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 96        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 95        | 0.37%   |
| Intel 82574L Gigabit Network Connection                           | 94        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 91        | 0.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 89        | 0.35%   |
| Huawei MLA-L11                                                    | 89        | 0.35%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 85        | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 85        | 0.33%   |
| Nvidia MCP77 Ethernet                                             | 85        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23698     | 59.09%  |
| WiFi     | 15837     | 39.49%  |
| Modem    | 522       | 1.3%    |
| Unknown  | 50        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 13804     | 52.96%  |
| WiFi     | 12253     | 47.01%  |
| Modem    | 5         | 0.02%   |
| Unknown  | 3         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12827     | 49.34%  |
| 1     | 12232     | 47.05%  |
| 0     | 526       | 2.02%   |
| 3     | 231       | 0.89%   |
| 4     | 109       | 0.42%   |
| 6     | 38        | 0.15%   |
| 8     | 13        | 0.05%   |
| 5     | 5         | 0.02%   |
| 7     | 4         | 0.02%   |
| 12    | 3         | 0.01%   |
| 10    | 3         | 0.01%   |
| 11    | 2         | 0.01%   |
| 33    | 1         | 0.004%  |
| 20    | 1         | 0.004%  |
| 14    | 1         | 0.004%  |
| 13    | 1         | 0.004%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25476     | 98.02%  |
| Yes  | 515       | 1.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3239      | 28.57%  |
| Realtek Semiconductor           | 1366      | 12.05%  |
| Qualcomm Atheros Communications | 1304      | 11.5%   |
| Cambridge Silicon Radio         | 903       | 7.96%   |
| IMC Networks                    | 806       | 7.11%   |
| Broadcom                        | 720       | 6.35%   |
| Lite-On Technology              | 665       | 5.86%   |
| Foxconn / Hon Hai               | 576       | 5.08%   |
| ASUSTek Computer                | 344       | 3.03%   |
| Ralink                          | 199       | 1.76%   |
| Apple                           | 158       | 1.39%   |
| Toshiba                         | 155       | 1.37%   |
| Foxconn International           | 155       | 1.37%   |
| Realtek                         | 150       | 1.32%   |
| Hewlett-Packard                 | 130       | 1.15%   |
| Dell                            | 113       | 1%      |
| Alps Electric                   | 65        | 0.57%   |
| MediaTek                        | 57        | 0.5%    |
| Ralink Technology               | 38        | 0.34%   |
| Integrated System Solution      | 31        | 0.27%   |
| Opticis                         | 28        | 0.25%   |
| Chicony Electronics             | 23        | 0.2%    |
| TP-Link                         | 21        | 0.19%   |
| Micro Star International        | 15        | 0.13%   |
| USI                             | 11        | 0.1%    |
| ISSC                            | 10        | 0.09%   |
| Conwise Technology              | 9         | 0.08%   |
| Askey Computer                  | 7         | 0.06%   |
| Taiyo Yuden                     | 5         | 0.04%   |
| Roper                           | 5         | 0.04%   |
| Qcom                            | 5         | 0.04%   |
| HTC (High Tech Computer)        | 5         | 0.04%   |
| Logitech                        | 4         | 0.04%   |
| D-Link System                   | 4         | 0.04%   |
| Marvell Semiconductor           | 3         | 0.03%   |
| Actions                         | 3         | 0.03%   |
| Samsung Electronics             | 2         | 0.02%   |
| TRENDnet                        | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1039      | 9.15%   |
| Realtek Bluetooth Radio                                                             | 910       | 8.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 903       | 7.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 598       | 5.27%   |
| Intel AX201 Bluetooth                                                               | 539       | 4.75%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 409       | 3.6%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 388       | 3.42%   |
| Intel AX200 Bluetooth                                                               | 336       | 2.96%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 324       | 2.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 265       | 2.34%   |
| Intel Bluetooth Device                                                              | 257       | 2.26%   |
| IMC Networks Bluetooth Radio                                                        | 253       | 2.23%   |
| Ralink RT3290 Bluetooth                                                             | 199       | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 194       | 1.71%   |
| IMC Networks Bluetooth Device                                                       | 187       | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 168       | 1.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 167       | 1.47%   |
| Lite-On Bluetooth Device                                                            | 163       | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 157       | 1.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 153       | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 153       | 1.35%   |
| Realtek 802.11ac WLAN Adapter                                                       | 142       | 1.25%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 140       | 1.23%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 107       | 0.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 107       | 0.94%   |
| Broadcom BCM2045 Bluetooth                                                          | 100       | 0.88%   |
| Intel AX210 Bluetooth                                                               | 87        | 0.77%   |
| IMC Networks Wireless_Device                                                        | 79        | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 78        | 0.69%   |
| Qualcomm Atheros Bluetooth                                                          | 74        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 73        | 0.64%   |
| Apple Bluetooth Host Controller                                                     | 73        | 0.64%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 71        | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 66        | 0.58%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 64        | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 63        | 0.56%   |
| Broadcom HP Portable Valentine                                                      | 62        | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 59        | 0.52%   |
| Toshiba Integrated Bluetooth HCI                                                    | 58        | 0.51%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 58        | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 17717     | 50.92%  |
| AMD                                  | 7981      | 22.94%  |
| Nvidia                               | 6635      | 19.07%  |
| C-Media Electronics                  | 623       | 1.79%   |
| Creative Labs                        | 326       | 0.94%   |
| VIA Technologies                     | 136       | 0.39%   |
| Creative Technology                  | 116       | 0.33%   |
| Silicon Integrated Systems [SiS]     | 114       | 0.33%   |
| Logitech                             | 108       | 0.31%   |
| JMTek                                | 98        | 0.28%   |
| Texas Instruments                    | 68        | 0.2%    |
| Generalplus Technology               | 68        | 0.2%    |
| ASUSTek Computer                     | 38        | 0.11%   |
| Realtek Semiconductor                | 29        | 0.08%   |
| Plantronics                          | 29        | 0.08%   |
| Lenovo                               | 27        | 0.08%   |
| Kingston Technology                  | 27        | 0.08%   |
| GN Netcom                            | 23        | 0.07%   |
| Razer USA                            | 21        | 0.06%   |
| Yamaha                               | 20        | 0.06%   |
| Sony                                 | 18        | 0.05%   |
| Focusrite-Novation                   | 18        | 0.05%   |
| A4Tech                               | 18        | 0.05%   |
| Samson Technologies                  | 17        | 0.05%   |
| SteelSeries ApS                      | 15        | 0.04%   |
| KTMicro                              | 15        | 0.04%   |
| Micro Star International             | 13        | 0.04%   |
| M-Audio                              | 13        | 0.04%   |
| XMOS                                 | 12        | 0.03%   |
| Pixart Imaging                       | 12        | 0.03%   |
| Thesycon Systemsoftware & Consulting | 10        | 0.03%   |
| Sennheiser Communications            | 10        | 0.03%   |
| Nordic Semiconductor ASA             | 10        | 0.03%   |
| Ensoniq                              | 10        | 0.03%   |
| Conexant Systems                     | 10        | 0.03%   |
| Microsoft                            | 9         | 0.03%   |
| BEHRINGER International              | 9         | 0.03%   |
| SAVITECH                             | 8         | 0.02%   |
| GYROCOM C&C                          | 8         | 0.02%   |
| FIFINE Microphones                   | 8         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2279      | 5.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2239      | 5.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2197      | 5.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2048      | 5.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1455      | 3.59%   |
| AMD FCH Azalia Controller                                                                         | 1228      | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1084      | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 981       | 2.42%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 924       | 2.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 924       | 2.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 829       | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 686       | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 681       | 1.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 680       | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 627       | 1.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 594       | 1.46%   |
| Nvidia High Definition Audio Controller                                                           | 591       | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 546       | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 539       | 1.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 512       | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 504       | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 470       | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 431       | 1.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 411       | 1.01%   |
| Nvidia MCP61 High Definition Audio                                                                | 393       | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 391       | 0.96%   |
| Intel 8 Series HD Audio Controller                                                                | 366       | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 365       | 0.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 362       | 0.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 361       | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 358       | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 354       | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 338       | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 322       | 0.79%   |
| AMD Trinity HDMI Audio Controller                                                                 | 314       | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 312       | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 287       | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 282       | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 279       | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 272       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 6371      | 24.89%  |
| Samsung Electronics          | 3963      | 15.48%  |
| Kingston                     | 3851      | 15.05%  |
| SK hynix                     | 3053      | 11.93%  |
| Crucial                      | 1371      | 5.36%   |
| Micron Technology            | 1363      | 5.33%   |
| Corsair                      | 581       | 2.27%   |
| Elpida                       | 533       | 2.08%   |
| AMD                          | 496       | 1.94%   |
| A-DATA Technology            | 483       | 1.89%   |
| Nanya Technology             | 476       | 1.86%   |
| Patriot                      | 442       | 1.73%   |
| Ramaxel Technology           | 418       | 1.63%   |
| Unknown (ABCD)               | 153       | 0.6%    |
| GOODRAM                      | 141       | 0.55%   |
| Goldkey                      | 135       | 0.53%   |
| ASint Technology             | 131       | 0.51%   |
| Apacer                       | 118       | 0.46%   |
| Foxline                      | 113       | 0.44%   |
| G.Skill                      | 102       | 0.4%    |
| Unknown                      | 102       | 0.4%    |
| Qumo                         | 82        | 0.32%   |
| 48spaces                     | 82        | 0.32%   |
| Transcend                    | 80        | 0.31%   |
| Kingmax                      | 77        | 0.3%    |
| Kllisre                      | 66        | 0.26%   |
| Silicon Power                | 65        | 0.25%   |
| SHARETRONIC                  | 56        | 0.22%   |
| Unifosa                      | 55        | 0.21%   |
| Qimonda                      | 41        | 0.16%   |
| ACPI Digital                 | 36        | 0.14%   |
| KETECH                       | 31        | 0.12%   |
| Atermiter                    | 31        | 0.12%   |
| GeIL                         | 30        | 0.12%   |
| Hikvision                    | 27        | 0.11%   |
| Team                         | 24        | 0.09%   |
| Toshiba                      | 21        | 0.08%   |
| Ramos Technology             | 19        | 0.07%   |
| Patriot Memory (PDP Systems) | 18        | 0.07%   |
| Hewlett-Packard              | 15        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 291       | 1.01%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 271       | 0.94%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 264       | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 231       | 0.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 224       | 0.78%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 214       | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 206       | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                      | 187       | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 168       | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 166       | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 147       | 0.51%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 142       | 0.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 138       | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 137       | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 137       | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 133       | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 128       | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 122       | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 122       | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 117       | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 116       | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 113       | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 113       | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 113       | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 108       | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 106       | 0.37%   |
| Unknown                                                          | 102       | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 101       | 0.35%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 98        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 97        | 0.34%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 96        | 0.33%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 95        | 0.33%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 94        | 0.33%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 93        | 0.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 89        | 0.31%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 86        | 0.3%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 86        | 0.3%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 85        | 0.3%    |
| Unknown RAM Module 512MB DIMM SDRAM                              | 83        | 0.29%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 83        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 9371      | 41.82%  |
| DDR4         | 5775      | 25.77%  |
| DDR2         | 2430      | 10.84%  |
| Unknown      | 2145      | 9.57%   |
| SDRAM        | 1525      | 6.81%   |
| DDR          | 426       | 1.9%    |
| LPDDR4       | 393       | 1.75%   |
| DRAM         | 123       | 0.55%   |
| LPDDR3       | 111       | 0.5%    |
| DDR5         | 67        | 0.3%    |
| LPDDR5       | 37        | 0.17%   |
| DDR2 FB-DIMM | 2         | 0.01%   |
| SRAM         | 1         | 0.004%  |
| EEPROM       | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 11031     | 49.93%  |
| SODIMM       | 10464     | 47.37%  |
| Row Of Chips | 542       | 2.45%   |
| Chip         | 29        | 0.13%   |
| FB-DIMM      | 16        | 0.07%   |
| Unknown      | 8         | 0.04%   |
| RIMM         | 1         | 0.005%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 8192      | 31.91%  |
| 2048    | 6586      | 25.65%  |
| 8192    | 5839      | 22.74%  |
| 1024    | 2758      | 10.74%  |
| 16384   | 1243      | 4.84%   |
| 512     | 556       | 2.17%   |
| 32768   | 333       | 1.3%    |
| 256     | 104       | 0.41%   |
| 65536   | 29        | 0.11%   |
| 1536    | 10        | 0.04%   |
| 12288   | 5         | 0.02%   |
| 32      | 5         | 0.02%   |
| Unknown | 5         | 0.02%   |
| 128     | 2         | 0.01%   |
| 16      | 2         | 0.01%   |
| 258496  | 1         | 0.004%  |
| 129408  | 1         | 0.004%  |
| 1       | 1         | 0.004%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 5476      | 22.27%  |
| 1333    | 2821      | 11.47%  |
| 2667    | 1924      | 7.82%   |
| Unknown | 1652      | 6.72%   |
| 3200    | 1618      | 6.58%   |
| 800     | 1558      | 6.34%   |
| 667     | 1410      | 5.73%   |
| 1334    | 1391      | 5.66%   |
| 2400    | 1271      | 5.17%   |
| 2133    | 722       | 2.94%   |
| 1066    | 333       | 1.35%   |
| 1067    | 327       | 1.33%   |
| 1867    | 313       | 1.27%   |
| 400     | 307       | 1.25%   |
| 533     | 291       | 1.18%   |
| 4199    | 288       | 1.17%   |
| 1866    | 260       | 1.06%   |
| 3600    | 250       | 1.02%   |
| 3266    | 230       | 0.94%   |
| 333     | 183       | 0.74%   |
| 2933    | 178       | 0.72%   |
| 2666    | 139       | 0.57%   |
| 3400    | 131       | 0.53%   |
| 2048    | 126       | 0.51%   |
| 1800    | 104       | 0.42%   |
| 3466    | 74        | 0.3%    |
| 3000    | 67        | 0.27%   |
| 975     | 66        | 0.27%   |
| 266     | 62        | 0.25%   |
| 2800    | 60        | 0.24%   |
| 4267    | 57        | 0.23%   |
| 3733    | 54        | 0.22%   |
| 4800    | 49        | 0.2%    |
| 3333    | 43        | 0.17%   |
| 2866    | 43        | 0.17%   |
| 6400    | 41        | 0.17%   |
| 1648    | 36        | 0.15%   |
| 1639    | 33        | 0.13%   |
| 66      | 33        | 0.13%   |
| 2134    | 30        | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 368       | 28.95%  |
| Canon                           | 266       | 20.93%  |
| Samsung Electronics             | 210       | 16.52%  |
| Seiko Epson                     | 114       | 8.97%   |
| Brother Industries              | 91        | 7.16%   |
| Xerox                           | 48        | 3.78%   |
| Pantum                          | 40        | 3.15%   |
| Panasonic (Matsushita)          | 37        | 2.91%   |
| Kyocera                         | 25        | 1.97%   |
| Ricoh                           | 22        | 1.73%   |
| QinHeng Electronics             | 13        | 1.02%   |
| Prolific Technology             | 7         | 0.55%   |
| NXP Semiconductors              | 3         | 0.24%   |
| Lexmark International           | 3         | 0.24%   |
| Xiaomi                          | 2         | 0.16%   |
| TSC Auto ID Technology          | 2         | 0.16%   |
| STMicroelectronics              | 2         | 0.16%   |
| Konica Minolta                  | 2         | 0.16%   |
| Datamax-O'Neil                  | 2         | 0.16%   |
| Custom Engineering SPA          | 2         | 0.16%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.16%   |
| Apple                           | 2         | 0.16%   |
| Sharp                           | 1         | 0.08%   |
| Samsung Info. Systems America   | 1         | 0.08%   |
| Oki Data                        | 1         | 0.08%   |
| NCR                             | 1         | 0.08%   |
| KODAK                           | 1         | 0.08%   |
| iDPRT                           | 1         | 0.08%   |
| GODEX INTERNATIONAL             | 1         | 0.08%   |
| Fuji Xerox                      | 1         | 0.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1020                      | 39        | 3.05%   |
| Samsung SCX-4200 series               | 34        | 2.66%   |
| HP LaserJet P1102                     | 33        | 2.58%   |
| HP LaserJet 1018                      | 31        | 2.42%   |
| Canon LBP2900                         | 30        | 2.35%   |
| Panasonic (Matsushita) KX-MB1500RU    | 24        | 1.88%   |
| Samsung SCX-3400 Series               | 22        | 1.72%   |
| HP LaserJet 1010                      | 21        | 1.64%   |
| HP LaserJet P1005                     | 20        | 1.56%   |
| Samsung SCX-3200 Series               | 19        | 1.49%   |
| Seiko Epson Printer                   | 17        | 1.33%   |
| Canon MF4010 series                   | 16        | 1.25%   |
| Canon MF3010                          | 16        | 1.25%   |
| Canon MF4410                          | 15        | 1.17%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 14        | 1.09%   |
| Samsung M2070 Series                  | 14        | 1.09%   |
| Pantum P2200 series                   | 14        | 1.09%   |
| HP LaserJet 1320                      | 14        | 1.09%   |
| HP LaserJet 1200                      | 14        | 1.09%   |
| Brother HL-1110 series                | 14        | 1.09%   |
| QinHeng CH340S                        | 13        | 1.02%   |
| Samsung ML-1640 Series Laser Printer  | 12        | 0.94%   |
| Samsung ML-1210 Printer               | 12        | 0.94%   |
| HP DeskJet 2130 series                | 12        | 0.94%   |
| Canon PIXMA MG2500 Series             | 12        | 0.94%   |
| Canon LBP3010/LBP3018/LBP3050         | 12        | 0.94%   |
| Seiko Epson L210 Series               | 11        | 0.86%   |
| Samsung M2020 Series                  | 11        | 0.86%   |
| HP LaserJet 1022                      | 11        | 0.86%   |
| Canon LBP6000                         | 11        | 0.86%   |
| Samsung ML-2010P Mono Laser Printer   | 10        | 0.78%   |
| Pantum M6500 series                   | 10        | 0.78%   |
| HP LaserJet 1300                      | 10        | 0.78%   |
| Canon LBP810                          | 10        | 0.78%   |
| Canon LaserShot LBP-1120 Printer      | 10        | 0.78%   |
| Brother HL-2030 Laser Printer         | 10        | 0.78%   |
| Samsung SCX-4100 Scanner              | 9         | 0.7%    |
| Canon LBP6020                         | 9         | 0.7%    |
| Xerox WorkCentre 3119 Series          | 8         | 0.63%   |
| Xerox Phaser 3140 and 3155            | 8         | 0.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 118       | 36.31%  |
| Seiko Epson                 | 83        | 25.54%  |
| Hewlett-Packard             | 58        | 17.85%  |
| Mustek Systems              | 33        | 10.15%  |
| Acer Peripherals (now BenQ) | 13        | 4%      |
| Ultima Electronics          | 12        | 3.69%   |
| KYE Systems (Mouse Systems) | 5         | 1.54%   |
| Avision                     | 2         | 0.62%   |
| Canon Electronics           | 1         | 0.31%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                                                      | 20        | 6.13%   |
| Canon CanoScan LIDE 25                                                                | 20        | 6.13%   |
| Canon CanoScan LiDE 110                                                               | 20        | 6.13%   |
| Canon CanoScan LiDE 120                                                               | 18        | 5.52%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 13        | 3.99%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 11        | 3.37%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11        | 3.37%   |
| Canon CanoScan LiDE 210                                                               | 11        | 3.37%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 10        | 3.07%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 10        | 3.07%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 3.07%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 9         | 2.76%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 2.15%   |
| Mustek Systems SNAPSCAN e22                                                           | 7         | 2.15%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 6         | 1.84%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6         | 1.84%   |
| Canon CanoScan LiDE 60                                                                | 6         | 1.84%   |
| Canon CanoScan LiDE 220                                                               | 6         | 1.84%   |
| Canon CanoScan LiDE 100                                                               | 6         | 1.84%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4         | 1.23%   |
| HP ScanJet 3800c                                                                      | 4         | 1.23%   |
| Canon CanoScan LiDE 70                                                                | 4         | 1.23%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4         | 1.23%   |
| Seiko Epson Perfection 660                                                            | 3         | 0.92%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 3         | 0.92%   |
| HP ScanJet 3970c                                                                      | 3         | 0.92%   |
| HP ScanJet 3770                                                                       | 3         | 0.92%   |
| HP Scanjet 200                                                                        | 3         | 0.92%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3         | 0.92%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3         | 0.92%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 3         | 0.92%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 2         | 0.61%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2         | 0.61%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2         | 0.61%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2         | 0.61%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 2         | 0.61%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 2         | 0.61%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 2         | 0.61%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 0.61%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 2         | 0.61%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2886      | 20.91%  |
| IMC Networks                           | 1368      | 9.91%   |
| Logitech                               | 869       | 6.3%    |
| Realtek Semiconductor                  | 822       | 5.96%   |
| Bison Electronics                      | 783       | 5.67%   |
| Microdia                               | 767       | 5.56%   |
| Suyin                                  | 670       | 4.86%   |
| Z-Star Microelectronics                | 584       | 4.23%   |
| Sunplus Innovation Technology          | 560       | 4.06%   |
| Quanta                                 | 500       | 3.62%   |
| Silicon Motion                         | 426       | 3.09%   |
| Cheng Uei Precision Industry (Foxlink) | 419       | 3.04%   |
| Alcor Micro                            | 395       | 2.86%   |
| Syntek                                 | 364       | 2.64%   |
| Acer                                   | 293       | 2.12%   |
| Apple                                  | 175       | 1.27%   |
| Lite-On Technology                     | 135       | 0.98%   |
| Microsoft                              | 130       | 0.94%   |
| Ricoh                                  | 126       | 0.91%   |
| Luxvisions Innotech Limited            | 115       | 0.83%   |
| ALi                                    | 107       | 0.78%   |
| KYE Systems (Mouse Systems)            | 100       | 0.72%   |
| DigiTech                               | 85        | 0.62%   |
| GEMBIRD                                | 83        | 0.6%    |
| Arkmicro Technologies                  | 76        | 0.55%   |
| Aveo Technology                        | 64        | 0.46%   |
| Samsung Electronics                    | 61        | 0.44%   |
| Pixart Imaging                         | 59        | 0.43%   |
| SunplusIT                              | 57        | 0.41%   |
| Sonix Technology                       | 55        | 0.4%    |
| Cubeternet                             | 55        | 0.4%    |
| Creative Technology                    | 47        | 0.34%   |
| Lenovo                                 | 42        | 0.3%    |
| Primax Electronics                     | 34        | 0.25%   |
| icSpring                               | 31        | 0.22%   |
| Genesys Logic                          | 27        | 0.2%    |
| Importek                               | 24        | 0.17%   |
| A4Tech                                 | 24        | 0.17%   |
| Y Media                                | 23        | 0.17%   |
| Sunplus Technology                     | 20        | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Logitech Webcam C270                     | 310       | 2.24%   |
| Chicony HD WebCam                        | 286       | 2.07%   |
| Chicony Integrated Camera                | 282       | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 255       | 1.84%   |
| Chicony Lenovo EasyCamera                | 226       | 1.63%   |
| IMC Networks USB2.0 HD UVC WebCam        | 217       | 1.57%   |
| Bison Lenovo Integrated Webcam           | 191       | 1.38%   |
| Z-Star Venus USB2.0 Camera               | 177       | 1.28%   |
| Sunplus HD WebCam                        | 173       | 1.25%   |
| Microdia Integrated_Webcam_HD            | 163       | 1.18%   |
| IMC Networks Integrated Camera           | 156       | 1.13%   |
| Chicony USB2.0 HD UVC WebCam             | 144       | 1.04%   |
| IMC Networks UVC VGA Webcam              | 142       | 1.03%   |
| Chicony USB 2.0 Camera                   | 133       | 0.96%   |
| Bison BisonCam, NB Pro                   | 127       | 0.92%   |
| Realtek Integrated_Webcam_HD             | 125       | 0.9%    |
| Bison Integrated Camera                  | 121       | 0.87%   |
| Syntek Integrated Camera                 | 119       | 0.86%   |
| Microdia Camera                          | 118       | 0.85%   |
| Z-Star Vega USB 2.0 Camera.              | 117       | 0.85%   |
| Chicony HP Webcam                        | 113       | 0.82%   |
| Chicony VGA Webcam                       | 109       | 0.79%   |
| Alcor Micro USB 2.0 PC cam               | 106       | 0.77%   |
| IMC Networks HD Camera                   | 103       | 0.74%   |
| Realtek Lenovo EasyCamera                | 99        | 0.72%   |
| Realtek USB Camera                       | 97        | 0.7%    |
| Quanta VGA WebCam                        | 97        | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam            | 93        | 0.67%   |
| Alcor Micro Asus Integrated Webcam       | 88        | 0.64%   |
| Silicon Motion WebCam SC-0311139N        | 85        | 0.61%   |
| Z-Star Vimicro USB Camera (Altair)       | 81        | 0.59%   |
| Sunplus Integrated_Webcam_HD             | 81        | 0.59%   |
| Syntek Lenovo EasyCamera                 | 80        | 0.58%   |
| IMC Networks Integrated Webcam           | 80        | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 79        | 0.57%   |
| Chicony HP TrueVision HD                 | 78        | 0.56%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 78        | 0.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 77        | 0.56%   |
| DigiTech USB 2.0 PC Camera               | 77        | 0.56%   |
| Acer Lenovo EasyCamera                   | 75        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 456       | 30.3%   |
| Shenzhen Goodix Technology         | 299       | 19.87%  |
| Synaptics                          | 230       | 15.28%  |
| AuthenTec                          | 138       | 9.17%   |
| Upek                               | 111       | 7.38%   |
| Elan Microelectronics              | 104       | 6.91%   |
| LighTuning Technology              | 100       | 6.64%   |
| STMicroelectronics                 | 37        | 2.46%   |
| Realtek USB2.0 Finger Print Bridge | 14        | 0.93%   |
| Focal-systems.Corp                 | 12        | 0.8%    |
| Microsoft                          | 2         | 0.13%   |
| Samsung Electronics                | 1         | 0.07%   |
| GDMicroelectronics                 | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 242       | 16.08%  |
| Validity Sensors Fingerprint scanner                                       | 103       | 6.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 93        | 6.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 89        | 5.91%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 76        | 5.05%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 68        | 4.52%   |
| Elan ELAN:Fingerprint                                                      | 55        | 3.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 49        | 3.26%   |
| LighTuning Fingerprint Reader                                              | 45        | 2.99%   |
| AuthenTec AES1600                                                          | 42        | 2.79%   |
| STMicroelectronics Fingerprint Reader                                      | 37        | 2.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 34        | 2.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 34        | 2.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 33        | 2.19%   |
| Elan ELAN:ARM-M4                                                           | 31        | 2.06%   |
| Validity Sensors VFS491                                                    | 28        | 1.86%   |
| AuthenTec AES2810                                                          | 28        | 1.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 26        | 1.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 1.73%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 23        | 1.53%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 22        | 1.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 20        | 1.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 1.33%   |
| Synaptics Fingerprint reader [HP G6]                                       | 19        | 1.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 1.26%   |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 1.2%    |
| Synaptics  WBDI                                                            | 17        | 1.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 1.13%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 1.06%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 14        | 0.93%   |
| Elan WBF Fingerprint Sensor                                                | 14        | 0.93%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.8%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 12        | 0.8%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 12        | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 0.73%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 0.66%   |
| Synaptics UWP WBDI Device                                                  | 10        | 0.66%   |
| Synaptics UWP WBDI                                                         | 10        | 0.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 107       | 32.42%  |
| Broadcom                   | 89        | 26.97%  |
| Upek                       | 26        | 7.88%   |
| O2 Micro                   | 21        | 6.36%   |
| Aktiv                      | 18        | 5.45%   |
| Lenovo                     | 16        | 4.85%   |
| Aladdin Knowledge Systems  | 15        | 4.55%   |
| Aladdin R.D.               | 11        | 3.33%   |
| Yubico.com                 | 7         | 2.12%   |
| Advanced Card Systems      | 7         | 2.12%   |
| Gemalto (was Gemplus)      | 5         | 1.52%   |
| Athena Smartcard Solutions | 4         | 1.21%   |
| OmniKey                    | 1         | 0.3%    |
| NXP Semiconductors         | 1         | 0.3%    |
| Microchip Technology       | 1         | 0.3%    |
| Castles Technology         | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 102       | 30.91%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 10.3%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 7.88%   |
| Broadcom 58200                                                               | 20        | 6.06%   |
| Broadcom 5880                                                                | 19        | 5.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.45%   |
| Aktiv Rutoken lite                                                           | 18        | 5.45%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 4.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 4.85%   |
| Aladdin Knowledge Systems Token JC                                           | 15        | 4.55%   |
| Aladdin R.D. JaCarta                                                         | 9         | 2.73%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 7         | 2.12%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.21%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.21%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.91%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.91%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.61%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.61%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 2         | 0.61%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.3%    |
| NXP Semiconductors PN7462au CCID                                             | 1         | 0.3%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.3%    |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.3%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.3%    |
| Aladdin R.D. Smart card reader JCR721                                        | 1         | 0.3%    |
| Aladdin R.D. JaCarta LT                                                      | 1         | 0.3%    |
| Advanced Card Systems Token USB 64K                                          | 1         | 0.3%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.3%    |
| Advanced Card Systems ACR3901U                                               | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 19660     | 73.6%   |
| 1     | 5723      | 21.42%  |
| 2     | 1000      | 3.74%   |
| 3     | 205       | 0.77%   |
| 4     | 89        | 0.33%   |
| 5     | 19        | 0.07%   |
| 6     | 13        | 0.05%   |
| 7     | 3         | 0.01%   |
| 9     | 1         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3638      | 44.94%  |
| Fingerprint reader       | 1498      | 18.5%   |
| Net/wireless             | 744       | 9.19%   |
| Communication controller | 410       | 5.06%   |
| Multimedia controller    | 376       | 4.64%   |
| Bluetooth                | 286       | 3.53%   |
| Chipcard                 | 279       | 3.45%   |
| Unassigned class         | 242       | 2.99%   |
| Camera                   | 181       | 2.24%   |
| Sound                    | 92        | 1.14%   |
| Storage                  | 72        | 0.89%   |
| Flash memory             | 65        | 0.8%    |
| Net/ethernet             | 49        | 0.61%   |
| Network                  | 31        | 0.38%   |
| Modem                    | 30        | 0.37%   |
| Card reader              | 29        | 0.36%   |
| Dvb card                 | 22        | 0.27%   |
| Storage/raid             | 17        | 0.21%   |
| Storage/ide              | 10        | 0.12%   |
| Firewire controller      | 9         | 0.11%   |
| Storage/ata              | 7         | 0.09%   |
| Tv card                  | 5         | 0.06%   |
| Unclassified device      | 2         | 0.02%   |
| Wireless                 | 1         | 0.01%   |
| Video                    | 1         | 0.01%   |

