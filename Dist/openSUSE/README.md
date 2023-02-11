openSUSE - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

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

Total: 2589

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | Desktop     | [175a0fcf9a](https://linux-hardware.org/?probe=175a0fcf9a) | Jan 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0e7acce8d](https://linux-hardware.org/?probe=e0e7acce8d) | Jan 31, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [1746dfe4b1](https://linux-hardware.org/?probe=1746dfe4b1) | Jan 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9b0891d54d](https://linux-hardware.org/?probe=9b0891d54d) | Jan 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b61ed06b1e](https://linux-hardware.org/?probe=b61ed06b1e) | Jan 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [de8c055a8a](https://linux-hardware.org/?probe=de8c055a8a) | Jan 29, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [4a33511e43](https://linux-hardware.org/?probe=4a33511e43) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [de71656929](https://linux-hardware.org/?probe=de71656929) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | Notebook    | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| Intel         | X99                         | Desktop     | [1fbd6cf5bd](https://linux-hardware.org/?probe=1fbd6cf5bd) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [cf662e2730](https://linux-hardware.org/?probe=cf662e2730) | Jan 25, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [c2ff1b1e23](https://linux-hardware.org/?probe=c2ff1b1e23) | Jan 25, 2023 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [7b9b00eccb](https://linux-hardware.org/?probe=7b9b00eccb) | Jan 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [723d6a91bb](https://linux-hardware.org/?probe=723d6a91bb) | Jan 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5abd524783](https://linux-hardware.org/?probe=5abd524783) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [4da9f87ebb](https://linux-hardware.org/?probe=4da9f87ebb) | Jan 23, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [62e1cc77f9](https://linux-hardware.org/?probe=62e1cc77f9) | Jan 23, 2023 |
| HP            | 8399                        | Desktop     | [db427c8bc9](https://linux-hardware.org/?probe=db427c8bc9) | Jan 22, 2023 |
| HP            | 8399                        | Desktop     | [cdf9d12bb4](https://linux-hardware.org/?probe=cdf9d12bb4) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | Notebook    | [282161cc92](https://linux-hardware.org/?probe=282161cc92) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | Notebook    | [8d235b1b8d](https://linux-hardware.org/?probe=8d235b1b8d) | Jan 22, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Dell          | Latitude 9420               | Notebook    | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Fujitsu       | LIFEBOOK P1630              | Notebook    | [5ee218deb4](https://linux-hardware.org/?probe=5ee218deb4) | Jan 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [f6b68c1767](https://linux-hardware.org/?probe=f6b68c1767) | Jan 19, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [1f56f8cb21](https://linux-hardware.org/?probe=1f56f8cb21) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [28a15ffc38](https://linux-hardware.org/?probe=28a15ffc38) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [004b2669ef](https://linux-hardware.org/?probe=004b2669ef) | Jan 18, 2023 |
| Fujitsu       | LIFEBOOK P1630              | Notebook    | [5a9662e39b](https://linux-hardware.org/?probe=5a9662e39b) | Jan 17, 2023 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [de3dde0785](https://linux-hardware.org/?probe=de3dde0785) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17fd020689](https://linux-hardware.org/?probe=17fd020689) | Jan 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9b874af8a4](https://linux-hardware.org/?probe=9b874af8a4) | Jan 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ae33b4bb24](https://linux-hardware.org/?probe=ae33b4bb24) | Jan 16, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [aae8dcf220](https://linux-hardware.org/?probe=aae8dcf220) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [64bb2953ec](https://linux-hardware.org/?probe=64bb2953ec) | Jan 15, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6309c0f057](https://linux-hardware.org/?probe=6309c0f057) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
| MSI           | P67A-C45                    | Desktop     | [625a573f22](https://linux-hardware.org/?probe=625a573f22) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| Dell          | Latitude 5414               | Notebook    | [bc4fdb0971](https://linux-hardware.org/?probe=bc4fdb0971) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [64a9cc7b90](https://linux-hardware.org/?probe=64a9cc7b90) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [6b20e87c33](https://linux-hardware.org/?probe=6b20e87c33) | Jan 13, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [e8bf140d81](https://linux-hardware.org/?probe=e8bf140d81) | Jan 12, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Convertible | [f3bf17dba0](https://linux-hardware.org/?probe=f3bf17dba0) | Jan 11, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [9fd56e9b73](https://linux-hardware.org/?probe=9fd56e9b73) | Jan 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2f2f7a3a60](https://linux-hardware.org/?probe=2f2f7a3a60) | Jan 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [bff59f1d42](https://linux-hardware.org/?probe=bff59f1d42) | Jan 08, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [a4b5bc192d](https://linux-hardware.org/?probe=a4b5bc192d) | Jan 06, 2023 |
| Dell          | 081VG9 A05                  | Server      | [23031aa11a](https://linux-hardware.org/?probe=23031aa11a) | Jan 06, 2023 |
| Dell          | G7 7790                     | Notebook    | [ffaafd92cf](https://linux-hardware.org/?probe=ffaafd92cf) | Jan 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [6b475a50fc](https://linux-hardware.org/?probe=6b475a50fc) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [e11b38ed14](https://linux-hardware.org/?probe=e11b38ed14) | Jan 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a502c849f](https://linux-hardware.org/?probe=8a502c849f) | Jan 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [138a853640](https://linux-hardware.org/?probe=138a853640) | Jan 02, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [704cc86124](https://linux-hardware.org/?probe=704cc86124) | Jan 01, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [092aa8fe44](https://linux-hardware.org/?probe=092aa8fe44) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2508c5972e](https://linux-hardware.org/?probe=2508c5972e) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [133d8a7f70](https://linux-hardware.org/?probe=133d8a7f70) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | Notebook    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c7a7749a95](https://linux-hardware.org/?probe=c7a7749a95) | Dec 30, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [0053ddb3c9](https://linux-hardware.org/?probe=0053ddb3c9) | Dec 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [458727c26e](https://linux-hardware.org/?probe=458727c26e) | Dec 30, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [250104c525](https://linux-hardware.org/?probe=250104c525) | Dec 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0447771b4f](https://linux-hardware.org/?probe=0447771b4f) | Dec 29, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [23fe358945](https://linux-hardware.org/?probe=23fe358945) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [a8b80cb4f6](https://linux-hardware.org/?probe=a8b80cb4f6) | Dec 28, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b073c04bea](https://linux-hardware.org/?probe=b073c04bea) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [442fcdba27](https://linux-hardware.org/?probe=442fcdba27) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4ad973e635](https://linux-hardware.org/?probe=4ad973e635) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [7e46b9fd5b](https://linux-hardware.org/?probe=7e46b9fd5b) | Dec 26, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dde339b7c9](https://linux-hardware.org/?probe=dde339b7c9) | Dec 26, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [7b965d8da8](https://linux-hardware.org/?probe=7b965d8da8) | Dec 25, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [410ac6980a](https://linux-hardware.org/?probe=410ac6980a) | Dec 25, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [cc51ba5d49](https://linux-hardware.org/?probe=cc51ba5d49) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [660e3a6511](https://linux-hardware.org/?probe=660e3a6511) | Dec 24, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [a640541ee0](https://linux-hardware.org/?probe=a640541ee0) | Dec 24, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [83203eef25](https://linux-hardware.org/?probe=83203eef25) | Dec 24, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | Notebook    | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [ab0eabbb89](https://linux-hardware.org/?probe=ab0eabbb89) | Dec 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Samsung       | 750QUA                      | Convertible | [19db82224d](https://linux-hardware.org/?probe=19db82224d) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [9dca0f7674](https://linux-hardware.org/?probe=9dca0f7674) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [13e778509f](https://linux-hardware.org/?probe=13e778509f) | Dec 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [b4f32be15b](https://linux-hardware.org/?probe=b4f32be15b) | Dec 22, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3dae14f00f](https://linux-hardware.org/?probe=3dae14f00f) | Dec 22, 2022 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [70695e9f3b](https://linux-hardware.org/?probe=70695e9f3b) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Dell          | 0K071D A01                  | Desktop     | [49612bc7d4](https://linux-hardware.org/?probe=49612bc7d4) | Dec 21, 2022 |
| Dell          | 0K071D A01                  | Desktop     | [94204a7d2c](https://linux-hardware.org/?probe=94204a7d2c) | Dec 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [ce5835b58d](https://linux-hardware.org/?probe=ce5835b58d) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [79cf1b618f](https://linux-hardware.org/?probe=79cf1b618f) | Dec 20, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [da35f3ec23](https://linux-hardware.org/?probe=da35f3ec23) | Dec 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [2a2f618c62](https://linux-hardware.org/?probe=2a2f618c62) | Dec 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [533bf9eafc](https://linux-hardware.org/?probe=533bf9eafc) | Dec 19, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1212530d94](https://linux-hardware.org/?probe=1212530d94) | Dec 18, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [c0b006673c](https://linux-hardware.org/?probe=c0b006673c) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [19e8973a92](https://linux-hardware.org/?probe=19e8973a92) | Dec 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [83e177278e](https://linux-hardware.org/?probe=83e177278e) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [adc5196d64](https://linux-hardware.org/?probe=adc5196d64) | Dec 17, 2022 |
| Lenovo        | 1S20UDCT01WWPF1ARBNP 29U... | Notebook    | [b5e9681592](https://linux-hardware.org/?probe=b5e9681592) | Dec 17, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [05519b281d](https://linux-hardware.org/?probe=05519b281d) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [64bdae140b](https://linux-hardware.org/?probe=64bdae140b) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0fe564693b](https://linux-hardware.org/?probe=0fe564693b) | Dec 16, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [e2a4ba00cd](https://linux-hardware.org/?probe=e2a4ba00cd) | Dec 16, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [e7334e3ced](https://linux-hardware.org/?probe=e7334e3ced) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f5a317963c](https://linux-hardware.org/?probe=f5a317963c) | Dec 15, 2022 |
| Dell          | Precision 7760              | Notebook    | [cbe51e9db3](https://linux-hardware.org/?probe=cbe51e9db3) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8df2e8b58c](https://linux-hardware.org/?probe=8df2e8b58c) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f18b9184ca](https://linux-hardware.org/?probe=f18b9184ca) | Dec 15, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [77fcf302d4](https://linux-hardware.org/?probe=77fcf302d4) | Dec 14, 2022 |
| Irbis         | NB264                       | Notebook    | [d137aad605](https://linux-hardware.org/?probe=d137aad605) | Dec 14, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2ba2a16d](https://linux-hardware.org/?probe=1e2ba2a16d) | Dec 14, 2022 |
| Samsung       | 750QUA                      | Convertible | [6c39114e7d](https://linux-hardware.org/?probe=6c39114e7d) | Dec 14, 2022 |
| ASUSTek       | Zenbook UP6502ZA_UP6502Z... | Convertible | [85c2b907d7](https://linux-hardware.org/?probe=85c2b907d7) | Dec 14, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9369afea1b](https://linux-hardware.org/?probe=9369afea1b) | Dec 14, 2022 |
| ASRock        | 4X4-R1000                   | Desktop     | [f6b7e164dc](https://linux-hardware.org/?probe=f6b7e164dc) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ004EU... | Notebook    | [8d04dfe3a5](https://linux-hardware.org/?probe=8d04dfe3a5) | Dec 12, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [780eecc5e8](https://linux-hardware.org/?probe=780eecc5e8) | Dec 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [aea1c7da95](https://linux-hardware.org/?probe=aea1c7da95) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b1ac2fbabe](https://linux-hardware.org/?probe=b1ac2fbabe) | Dec 09, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [62212b2baa](https://linux-hardware.org/?probe=62212b2baa) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [4acc1d38e8](https://linux-hardware.org/?probe=4acc1d38e8) | Dec 08, 2022 |
| MSI           | P67A-C45                    | Desktop     | [44c8da681d](https://linux-hardware.org/?probe=44c8da681d) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [a8aa92bfed](https://linux-hardware.org/?probe=a8aa92bfed) | Dec 07, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [7a2d061568](https://linux-hardware.org/?probe=7a2d061568) | Dec 06, 2022 |
| MSI           | B85-G41 PC Mate             | Desktop     | [a54611689d](https://linux-hardware.org/?probe=a54611689d) | Dec 06, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [6fc850bb3e](https://linux-hardware.org/?probe=6fc850bb3e) | Dec 06, 2022 |
| HUAWEI        | HUAWEIPGU-WBY0              | Soc         | [b4f452d2d8](https://linux-hardware.org/?probe=b4f452d2d8) | Dec 06, 2022 |
| MSI           | MS-B1711                    | Desktop     | [1fbaa02605](https://linux-hardware.org/?probe=1fbaa02605) | Dec 05, 2022 |
| Dell          | Latitude E5400              | Notebook    | [ab5b64fe8a](https://linux-hardware.org/?probe=ab5b64fe8a) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [5827ea2fa5](https://linux-hardware.org/?probe=5827ea2fa5) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7f8dcdb666](https://linux-hardware.org/?probe=7f8dcdb666) | Dec 05, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [930b8d0ff2](https://linux-hardware.org/?probe=930b8d0ff2) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f2a555fb1b](https://linux-hardware.org/?probe=f2a555fb1b) | Dec 04, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [8fc8a7552b](https://linux-hardware.org/?probe=8fc8a7552b) | Dec 04, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [5326fede0a](https://linux-hardware.org/?probe=5326fede0a) | Dec 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| HP            | 2B52                        | Desktop     | [e2e8bdd4f6](https://linux-hardware.org/?probe=e2e8bdd4f6) | Dec 03, 2022 |
| TYAN Compu... | S8026GM2NRE-HOV-B           | Server      | [d2813c6963](https://linux-hardware.org/?probe=d2813c6963) | Dec 03, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8d4e2bdcb9](https://linux-hardware.org/?probe=8d4e2bdcb9) | Dec 03, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [e46ba957f0](https://linux-hardware.org/?probe=e46ba957f0) | Dec 02, 2022 |
| ASUSTek       | A8N-E                       | Desktop     | [a1020380dd](https://linux-hardware.org/?probe=a1020380dd) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [87b13a5112](https://linux-hardware.org/?probe=87b13a5112) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [82c0eb6155](https://linux-hardware.org/?probe=82c0eb6155) | Dec 02, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ee17f7d657](https://linux-hardware.org/?probe=ee17f7d657) | Dec 02, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a4ed7efef9](https://linux-hardware.org/?probe=a4ed7efef9) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5eebfea632](https://linux-hardware.org/?probe=5eebfea632) | Dec 01, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [961f58c143](https://linux-hardware.org/?probe=961f58c143) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0461e6b5d2](https://linux-hardware.org/?probe=0461e6b5d2) | Dec 01, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [4951da34da](https://linux-hardware.org/?probe=4951da34da) | Nov 30, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [a41d7dbfb1](https://linux-hardware.org/?probe=a41d7dbfb1) | Nov 29, 2022 |
| VA_IP3        | GMLR_V1                     | Mini pc     | [ac6676f125](https://linux-hardware.org/?probe=ac6676f125) | Nov 29, 2022 |
| Supermicro    | X8DTG-D                     | Server      | [9e977b651e](https://linux-hardware.org/?probe=9e977b651e) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [944ade9560](https://linux-hardware.org/?probe=944ade9560) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [cc1637d7e2](https://linux-hardware.org/?probe=cc1637d7e2) | Nov 27, 2022 |
| Lenovo        | ThinkPad X260 20F6005HUS    | Notebook    | [6418eda1a9](https://linux-hardware.org/?probe=6418eda1a9) | Nov 27, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [a034af6b70](https://linux-hardware.org/?probe=a034af6b70) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [ed2e9cfb4f](https://linux-hardware.org/?probe=ed2e9cfb4f) | Nov 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| HP            | 212B                        | Desktop     | [3ac96bbb45](https://linux-hardware.org/?probe=3ac96bbb45) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| Dell          | Latitude 5401               | Notebook    | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Timi          | TM1612                      | Notebook    | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [be2c23e33c](https://linux-hardware.org/?probe=be2c23e33c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [8b8ac358e4](https://linux-hardware.org/?probe=8b8ac358e4) | Nov 21, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [2890235d49](https://linux-hardware.org/?probe=2890235d49) | Nov 21, 2022 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [d9a74ee60a](https://linux-hardware.org/?probe=d9a74ee60a) | Nov 20, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [4f3c7d5501](https://linux-hardware.org/?probe=4f3c7d5501) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [05c9ad6f4a](https://linux-hardware.org/?probe=05c9ad6f4a) | Nov 19, 2022 |
| Dell          | Latitude 5414               | Notebook    | [a408bec327](https://linux-hardware.org/?probe=a408bec327) | Nov 18, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| HP            | 8055                        | Desktop     | [4195a9765a](https://linux-hardware.org/?probe=4195a9765a) | Nov 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [b678f31b24](https://linux-hardware.org/?probe=b678f31b24) | Nov 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [371368cfe7](https://linux-hardware.org/?probe=371368cfe7) | Nov 16, 2022 |
| HP            | Compaq 6830s                | Notebook    | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | Notebook    | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [3b6d611387](https://linux-hardware.org/?probe=3b6d611387) | Nov 14, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [3eb034e033](https://linux-hardware.org/?probe=3eb034e033) | Nov 13, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [18b42b8ead](https://linux-hardware.org/?probe=18b42b8ead) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b2dbd8f602](https://linux-hardware.org/?probe=b2dbd8f602) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59a0a26e78](https://linux-hardware.org/?probe=59a0a26e78) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59d3c93814](https://linux-hardware.org/?probe=59d3c93814) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dc0e46c7b3](https://linux-hardware.org/?probe=dc0e46c7b3) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [75f7a51f9e](https://linux-hardware.org/?probe=75f7a51f9e) | Nov 12, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Lenovo        | ThinkPad T530 2394D56       | Notebook    | [3d44b768e5](https://linux-hardware.org/?probe=3d44b768e5) | Nov 12, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [4e0b0368b8](https://linux-hardware.org/?probe=4e0b0368b8) | Nov 12, 2022 |
| Samsung       | 730QDA                      | Convertible | [a7a2ca6941](https://linux-hardware.org/?probe=a7a2ca6941) | Nov 12, 2022 |
| Toshiba       | IS 1422+                    | Notebook    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [13286af46e](https://linux-hardware.org/?probe=13286af46e) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| HP            | ZBook 17                    | Notebook    | [e866fa1319](https://linux-hardware.org/?probe=e866fa1319) | Nov 09, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [776a9bc0b6](https://linux-hardware.org/?probe=776a9bc0b6) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [be071c7456](https://linux-hardware.org/?probe=be071c7456) | Nov 08, 2022 |
| HP            | ZBook 17                    | Notebook    | [af26e94623](https://linux-hardware.org/?probe=af26e94623) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e13f29fc81](https://linux-hardware.org/?probe=e13f29fc81) | Nov 07, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [912bfcc57e](https://linux-hardware.org/?probe=912bfcc57e) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [0f119b6000](https://linux-hardware.org/?probe=0f119b6000) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [e872fcb5f7](https://linux-hardware.org/?probe=e872fcb5f7) | Nov 06, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b5470f4f19](https://linux-hardware.org/?probe=b5470f4f19) | Nov 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [ec3bc58f50](https://linux-hardware.org/?probe=ec3bc58f50) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c177c82021](https://linux-hardware.org/?probe=c177c82021) | Nov 05, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [99e32a37ff](https://linux-hardware.org/?probe=99e32a37ff) | Nov 04, 2022 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [2d2c00b163](https://linux-hardware.org/?probe=2d2c00b163) | Nov 04, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [011d776675](https://linux-hardware.org/?probe=011d776675) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7255a61579](https://linux-hardware.org/?probe=7255a61579) | Nov 03, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b3613b84ad](https://linux-hardware.org/?probe=b3613b84ad) | Nov 02, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [40cedc7d2c](https://linux-hardware.org/?probe=40cedc7d2c) | Nov 02, 2022 |
| HP            | 829B                        | All in one  | [23122cba32](https://linux-hardware.org/?probe=23122cba32) | Nov 01, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0131299a9e](https://linux-hardware.org/?probe=0131299a9e) | Nov 01, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | Notebook    | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [453d856b8d](https://linux-hardware.org/?probe=453d856b8d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| Dell          | Latitude E6430              | Notebook    | [cb4eb1f556](https://linux-hardware.org/?probe=cb4eb1f556) | Oct 28, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Radxa         | Zero                        | Soc         | [e35d41a9a6](https://linux-hardware.org/?probe=e35d41a9a6) | Oct 27, 2022 |
| Dell          | Latitude 9420               | Notebook    | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| MSI           | X58 Pro                     | Desktop     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5fa9b60268](https://linux-hardware.org/?probe=5fa9b60268) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [3a60ac01f4](https://linux-hardware.org/?probe=3a60ac01f4) | Oct 23, 2022 |
| MSI           | X58 Pro                     | Desktop     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [fbc271b648](https://linux-hardware.org/?probe=fbc271b648) | Oct 22, 2022 |
| Lenovo        | 3111 NOK                    | Desktop     | [185e1ca963](https://linux-hardware.org/?probe=185e1ca963) | Oct 21, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [4c699ac628](https://linux-hardware.org/?probe=4c699ac628) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| HP            | ZBook 17                    | Notebook    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| Sony          | VPCEL3S1R                   | Notebook    | [5c37559c2d](https://linux-hardware.org/?probe=5c37559c2d) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [a078a2f2ae](https://linux-hardware.org/?probe=a078a2f2ae) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [e4769fb9e0](https://linux-hardware.org/?probe=e4769fb9e0) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [76bb60e5ee](https://linux-hardware.org/?probe=76bb60e5ee) | Oct 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [79c4c3b21f](https://linux-hardware.org/?probe=79c4c3b21f) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [b11fa8e1dd](https://linux-hardware.org/?probe=b11fa8e1dd) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI           | Prestige 14 A11SCS          | Notebook    | [e552920463](https://linux-hardware.org/?probe=e552920463) | Oct 13, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61eb97192e](https://linux-hardware.org/?probe=61eb97192e) | Oct 12, 2022 |
| Toshiba       | Satellite P55t-A            | Notebook    | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| Lenovo        | ThinkPad T430 2347DS3       | Notebook    | [970542656e](https://linux-hardware.org/?probe=970542656e) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| Gateway       | NV54 Series                 | Notebook    | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7d71e688f4](https://linux-hardware.org/?probe=7d71e688f4) | Oct 08, 2022 |
| ASUSTek       | F3Sv                        | Notebook    | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [b8f7c25d91](https://linux-hardware.org/?probe=b8f7c25d91) | Oct 07, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [9ef16d569e](https://linux-hardware.org/?probe=9ef16d569e) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Acer          | S50-54                      | Notebook    | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| Dell          | Latitude 3340               | Notebook    | [100b89b0a9](https://linux-hardware.org/?probe=100b89b0a9) | Oct 04, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [daec61299a](https://linux-hardware.org/?probe=daec61299a) | Oct 03, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Acer          | S50-54                      | Notebook    | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [9121550ca1](https://linux-hardware.org/?probe=9121550ca1) | Oct 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6e3b616977](https://linux-hardware.org/?probe=6e3b616977) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bf657c61f5](https://linux-hardware.org/?probe=bf657c61f5) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c82f3311d](https://linux-hardware.org/?probe=2c82f3311d) | Sep 28, 2022 |
| Dell          | Latitude E5250              | Notebook    | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [911a73323d](https://linux-hardware.org/?probe=911a73323d) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd63352b24](https://linux-hardware.org/?probe=fd63352b24) | Sep 24, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| Timi          | A35S                        | Notebook    | [a57a688f31](https://linux-hardware.org/?probe=a57a688f31) | Sep 21, 2022 |
| Dell          | Latitude 7400               | Notebook    | [466bd310ef](https://linux-hardware.org/?probe=466bd310ef) | Sep 21, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ed6f75ec9f](https://linux-hardware.org/?probe=ed6f75ec9f) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [167d69530f](https://linux-hardware.org/?probe=167d69530f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d3b972d870](https://linux-hardware.org/?probe=d3b972d870) | Sep 19, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [959330d9c1](https://linux-hardware.org/?probe=959330d9c1) | Sep 19, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [2daced0309](https://linux-hardware.org/?probe=2daced0309) | Sep 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [42f1c1aee1](https://linux-hardware.org/?probe=42f1c1aee1) | Sep 17, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c0e411a96d](https://linux-hardware.org/?probe=c0e411a96d) | Sep 13, 2022 |
| MSI           | X58 Pro                     | Desktop     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6d70631176](https://linux-hardware.org/?probe=6d70631176) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [921b9580f4](https://linux-hardware.org/?probe=921b9580f4) | Sep 09, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| MSI           | P67A-C45                    | Desktop     | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [068c169aa0](https://linux-hardware.org/?probe=068c169aa0) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [312e65fd07](https://linux-hardware.org/?probe=312e65fd07) | Sep 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8c4261ac4f](https://linux-hardware.org/?probe=8c4261ac4f) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ede97805ec](https://linux-hardware.org/?probe=ede97805ec) | Sep 02, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e5ae0e72ca](https://linux-hardware.org/?probe=e5ae0e72ca) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2615743a16](https://linux-hardware.org/?probe=2615743a16) | Sep 02, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| HP            | ZBook 17                    | Notebook    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| Google        | Eldrid                      | Notebook    | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [0a454665e0](https://linux-hardware.org/?probe=0a454665e0) | Aug 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| HP            | 802F                        | Desktop     | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP            | 802F                        | Desktop     | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [57727c2af7](https://linux-hardware.org/?probe=57727c2af7) | Aug 23, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [a9f2cced08](https://linux-hardware.org/?probe=a9f2cced08) | Aug 22, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [9590ddbb06](https://linux-hardware.org/?probe=9590ddbb06) | Aug 22, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c956ba84ed](https://linux-hardware.org/?probe=c956ba84ed) | Aug 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [68fa656563](https://linux-hardware.org/?probe=68fa656563) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [20a816d976](https://linux-hardware.org/?probe=20a816d976) | Aug 21, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [b0579e2127](https://linux-hardware.org/?probe=b0579e2127) | Aug 19, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [8620d444d4](https://linux-hardware.org/?probe=8620d444d4) | Aug 19, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5893f7215e](https://linux-hardware.org/?probe=5893f7215e) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [1ef086a230](https://linux-hardware.org/?probe=1ef086a230) | Aug 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [fd64b105a4](https://linux-hardware.org/?probe=fd64b105a4) | Aug 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [73f2db9159](https://linux-hardware.org/?probe=73f2db9159) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [36a169c447](https://linux-hardware.org/?probe=36a169c447) | Aug 11, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [42f35776a6](https://linux-hardware.org/?probe=42f35776a6) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0aada24b1e](https://linux-hardware.org/?probe=0aada24b1e) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [37f87e94fc](https://linux-hardware.org/?probe=37f87e94fc) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [904bd1db44](https://linux-hardware.org/?probe=904bd1db44) | Aug 06, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e2f0ef440](https://linux-hardware.org/?probe=2e2f0ef440) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [80007c0939](https://linux-hardware.org/?probe=80007c0939) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [abe955b96f](https://linux-hardware.org/?probe=abe955b96f) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [8ffda4cfe7](https://linux-hardware.org/?probe=8ffda4cfe7) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [24fa962b0b](https://linux-hardware.org/?probe=24fa962b0b) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [af32973765](https://linux-hardware.org/?probe=af32973765) | Jul 26, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [7f2dde6f76](https://linux-hardware.org/?probe=7f2dde6f76) | Jul 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b874a0aa8e](https://linux-hardware.org/?probe=b874a0aa8e) | Jul 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| HP            | 8715                        | Mini pc     | [75c873bb8e](https://linux-hardware.org/?probe=75c873bb8e) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Biostar       | B450MH                      | Desktop     | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | Desktop     | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [5a6d4e8ba4](https://linux-hardware.org/?probe=5a6d4e8ba4) | Jul 21, 2022 |
| HP            | 158B                        | Desktop     | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b128b9e7a](https://linux-hardware.org/?probe=7b128b9e7a) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [03d7fde009](https://linux-hardware.org/?probe=03d7fde009) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge 0328A11       | Notebook    | [4305889043](https://linux-hardware.org/?probe=4305889043) | Jul 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [084f1e11d2](https://linux-hardware.org/?probe=084f1e11d2) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [b6d23c8307](https://linux-hardware.org/?probe=b6d23c8307) | Jul 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| HP            | 829E                        | Mini pc     | [27c2c68afb](https://linux-hardware.org/?probe=27c2c68afb) | Jul 13, 2022 |
| Jumper        | EZbook                      | Notebook    | [2515427610](https://linux-hardware.org/?probe=2515427610) | Jul 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ef6695e9f9](https://linux-hardware.org/?probe=ef6695e9f9) | Jul 12, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [fdae528732](https://linux-hardware.org/?probe=fdae528732) | Jul 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ddd990405d](https://linux-hardware.org/?probe=ddd990405d) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| ASUSTek       | P5Q3                        | Desktop     | [5fb3e2b502](https://linux-hardware.org/?probe=5fb3e2b502) | Jul 10, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c29a7cd884](https://linux-hardware.org/?probe=c29a7cd884) | Jul 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42cc0cf38e](https://linux-hardware.org/?probe=42cc0cf38e) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [1e39d0bba8](https://linux-hardware.org/?probe=1e39d0bba8) | Jul 06, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [2311c99a80](https://linux-hardware.org/?probe=2311c99a80) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [6512ee623f](https://linux-hardware.org/?probe=6512ee623f) | Jul 05, 2022 |
| Multilaser    | PC150                       | Notebook    | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6cbbc0b707](https://linux-hardware.org/?probe=6cbbc0b707) | Jul 03, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [80fbf3aee4](https://linux-hardware.org/?probe=80fbf3aee4) | Jul 02, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [153a698b74](https://linux-hardware.org/?probe=153a698b74) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [97dfd06a92](https://linux-hardware.org/?probe=97dfd06a92) | Jul 01, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [e46c1314b2](https://linux-hardware.org/?probe=e46c1314b2) | Jul 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [bec2a7697f](https://linux-hardware.org/?probe=bec2a7697f) | Jun 30, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [bde570c9f5](https://linux-hardware.org/?probe=bde570c9f5) | Jun 30, 2022 |
| HP            | ENVY TS 17                  | Notebook    | [7b5d021513](https://linux-hardware.org/?probe=7b5d021513) | Jun 29, 2022 |
| Framework     | Laptop                      | Notebook    | [d4cd42f3af](https://linux-hardware.org/?probe=d4cd42f3af) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a9ddf668c4](https://linux-hardware.org/?probe=a9ddf668c4) | Jun 28, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [2fac0d5ea2](https://linux-hardware.org/?probe=2fac0d5ea2) | Jun 28, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [2818c11c12](https://linux-hardware.org/?probe=2818c11c12) | Jun 28, 2022 |
| Dell          | 0J3C2F A03                  | Desktop     | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [e272328867](https://linux-hardware.org/?probe=e272328867) | Jun 26, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8d5e06f168](https://linux-hardware.org/?probe=8d5e06f168) | Jun 26, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [9a39e5ea0d](https://linux-hardware.org/?probe=9a39e5ea0d) | Jun 26, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [78a37e2d4c](https://linux-hardware.org/?probe=78a37e2d4c) | Jun 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f1b7197958](https://linux-hardware.org/?probe=f1b7197958) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [a00111330b](https://linux-hardware.org/?probe=a00111330b) | Jun 24, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [c3c9ce7e40](https://linux-hardware.org/?probe=c3c9ce7e40) | Jun 23, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [1d719d4b2d](https://linux-hardware.org/?probe=1d719d4b2d) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [9a2d492e07](https://linux-hardware.org/?probe=9a2d492e07) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f51215fa91](https://linux-hardware.org/?probe=f51215fa91) | Jun 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc0719c813](https://linux-hardware.org/?probe=cc0719c813) | Jun 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [52276b3971](https://linux-hardware.org/?probe=52276b3971) | Jun 16, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [74770880f9](https://linux-hardware.org/?probe=74770880f9) | Jun 15, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [f14133e69e](https://linux-hardware.org/?probe=f14133e69e) | Jun 14, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [1908660d1a](https://linux-hardware.org/?probe=1908660d1a) | Jun 13, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bde09cf3b5](https://linux-hardware.org/?probe=bde09cf3b5) | Jun 13, 2022 |
| MSI           | Raider GE76 12UH            | Notebook    | [c29e79e22d](https://linux-hardware.org/?probe=c29e79e22d) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | Notebook    | [02e4c63249](https://linux-hardware.org/?probe=02e4c63249) | Jun 12, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a1069bbb9d](https://linux-hardware.org/?probe=a1069bbb9d) | Jun 12, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | 2129                        | Desktop     | [1e716f8086](https://linux-hardware.org/?probe=1e716f8086) | Jun 12, 2022 |
| HP            | 2129                        | Desktop     | [ad6f94da2e](https://linux-hardware.org/?probe=ad6f94da2e) | Jun 11, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bca7de0216](https://linux-hardware.org/?probe=bca7de0216) | Jun 11, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| HP            | 87C3                        | Desktop     | [1383f85e70](https://linux-hardware.org/?probe=1383f85e70) | Jun 09, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [06e496124a](https://linux-hardware.org/?probe=06e496124a) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [fd421da52b](https://linux-hardware.org/?probe=fd421da52b) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [0970e891ee](https://linux-hardware.org/?probe=0970e891ee) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [3b33a1b625](https://linux-hardware.org/?probe=3b33a1b625) | Jun 07, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [325cde32e5](https://linux-hardware.org/?probe=325cde32e5) | Jun 06, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [6abee365c1](https://linux-hardware.org/?probe=6abee365c1) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f496dbb19](https://linux-hardware.org/?probe=8f496dbb19) | Jun 06, 2022 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [5a7eff8826](https://linux-hardware.org/?probe=5a7eff8826) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [fab0ffc01e](https://linux-hardware.org/?probe=fab0ffc01e) | Jun 03, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [c50bbae3e1](https://linux-hardware.org/?probe=c50bbae3e1) | Jun 02, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [9b84f171eb](https://linux-hardware.org/?probe=9b84f171eb) | Jun 01, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [11882c80d6](https://linux-hardware.org/?probe=11882c80d6) | May 30, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7fe5175e37](https://linux-hardware.org/?probe=7fe5175e37) | May 30, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| Dell          | Latitude 7320               | Notebook    | [63c6f252ab](https://linux-hardware.org/?probe=63c6f252ab) | May 30, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [7167a72758](https://linux-hardware.org/?probe=7167a72758) | May 30, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [91508b9375](https://linux-hardware.org/?probe=91508b9375) | May 29, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [e2e854cde1](https://linux-hardware.org/?probe=e2e854cde1) | May 28, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b9f38d3572](https://linux-hardware.org/?probe=b9f38d3572) | May 28, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [640f9226a1](https://linux-hardware.org/?probe=640f9226a1) | May 26, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8dcce6eadb](https://linux-hardware.org/?probe=8dcce6eadb) | May 24, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [401023c3b3](https://linux-hardware.org/?probe=401023c3b3) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0fe6809527](https://linux-hardware.org/?probe=0fe6809527) | May 20, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [54f43d3430](https://linux-hardware.org/?probe=54f43d3430) | May 20, 2022 |
| HP            | 8591                        | Desktop     | [60c5d4f8ca](https://linux-hardware.org/?probe=60c5d4f8ca) | May 19, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [2864dc6f0a](https://linux-hardware.org/?probe=2864dc6f0a) | May 19, 2022 |
| HP            | 2820h                       | Desktop     | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [c32e65738e](https://linux-hardware.org/?probe=c32e65738e) | May 18, 2022 |
| HP            | 8591                        | Desktop     | [fd05ae27e7](https://linux-hardware.org/?probe=fd05ae27e7) | May 18, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1575ec23a](https://linux-hardware.org/?probe=d1575ec23a) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | 81B7 1001                   | All in one  | [d99babe70f](https://linux-hardware.org/?probe=d99babe70f) | May 15, 2022 |
| Dell          | 03V7GF A00                  | Desktop     | [1be2673e23](https://linux-hardware.org/?probe=1be2673e23) | May 14, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e01bfd360d](https://linux-hardware.org/?probe=e01bfd360d) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [07e54c3c41](https://linux-hardware.org/?probe=07e54c3c41) | May 12, 2022 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [2e8f888ca3](https://linux-hardware.org/?probe=2e8f888ca3) | May 11, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | Notebook    | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Positivo      | DA18HV1 POSITIVO            | Desktop     | [9d5e3583e2](https://linux-hardware.org/?probe=9d5e3583e2) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Dell          | 0XNJ2Y A00                  | Desktop     | [52e1e36724](https://linux-hardware.org/?probe=52e1e36724) | May 11, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [2591f59c80](https://linux-hardware.org/?probe=2591f59c80) | May 11, 2022 |
| EVGA          | 132-YW-E178-FTW 1           | Desktop     | [f9b1fe2224](https://linux-hardware.org/?probe=f9b1fe2224) | May 10, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [2091818d85](https://linux-hardware.org/?probe=2091818d85) | May 10, 2022 |
| Sony          | VPCF23S1E                   | Notebook    | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [b1d92dcb4e](https://linux-hardware.org/?probe=b1d92dcb4e) | May 10, 2022 |
| HP            | Notebook                    | Notebook    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [d2b0694da5](https://linux-hardware.org/?probe=d2b0694da5) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | Notebook    | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| Lenovo        | ThinkPad E555 20DH000WGE    | Notebook    | [75920152df](https://linux-hardware.org/?probe=75920152df) | May 10, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [feafca0464](https://linux-hardware.org/?probe=feafca0464) | May 10, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fe92976577](https://linux-hardware.org/?probe=fe92976577) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [730c246f44](https://linux-hardware.org/?probe=730c246f44) | May 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [99078d316d](https://linux-hardware.org/?probe=99078d316d) | May 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f60ba0abd7](https://linux-hardware.org/?probe=f60ba0abd7) | May 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9a7b248f26](https://linux-hardware.org/?probe=9a7b248f26) | May 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bf8ea76f0a](https://linux-hardware.org/?probe=bf8ea76f0a) | May 10, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| Clevo         | W55xEU                      | Notebook    | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [a3c1257116](https://linux-hardware.org/?probe=a3c1257116) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [8caf6e2b66](https://linux-hardware.org/?probe=8caf6e2b66) | May 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [fdc78a778b](https://linux-hardware.org/?probe=fdc78a778b) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4242d236c5](https://linux-hardware.org/?probe=4242d236c5) | May 09, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [cc42e8d5e5](https://linux-hardware.org/?probe=cc42e8d5e5) | May 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| ASRock        | A88M-G                      | Desktop     | [d67df6ff7d](https://linux-hardware.org/?probe=d67df6ff7d) | May 09, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [b438c97dca](https://linux-hardware.org/?probe=b438c97dca) | May 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [cc53668d3f](https://linux-hardware.org/?probe=cc53668d3f) | May 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [bdfe0722a7](https://linux-hardware.org/?probe=bdfe0722a7) | May 09, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [27b384c114](https://linux-hardware.org/?probe=27b384c114) | May 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d427368abd](https://linux-hardware.org/?probe=d427368abd) | May 08, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [899a0e8999](https://linux-hardware.org/?probe=899a0e8999) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | Notebook    | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [10eb959775](https://linux-hardware.org/?probe=10eb959775) | Apr 30, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [89def966af](https://linux-hardware.org/?probe=89def966af) | Apr 30, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [9b128bc47e](https://linux-hardware.org/?probe=9b128bc47e) | Apr 30, 2022 |
| PCWare        | IPX4105G Pro                | Desktop     | [073d789fc4](https://linux-hardware.org/?probe=073d789fc4) | Apr 29, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0b88a7422d](https://linux-hardware.org/?probe=0b88a7422d) | Apr 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c07e06f794](https://linux-hardware.org/?probe=c07e06f794) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [127862c3f7](https://linux-hardware.org/?probe=127862c3f7) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [e2461ef9a7](https://linux-hardware.org/?probe=e2461ef9a7) | Apr 27, 2022 |
| Acer          | Aspire 3810TZ               | Notebook    | [cba19ea352](https://linux-hardware.org/?probe=cba19ea352) | Apr 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [593ee8ccf3](https://linux-hardware.org/?probe=593ee8ccf3) | Apr 27, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [5850b85224](https://linux-hardware.org/?probe=5850b85224) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [26727e92e4](https://linux-hardware.org/?probe=26727e92e4) | Apr 22, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [29a508398a](https://linux-hardware.org/?probe=29a508398a) | Apr 22, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4f27720e96](https://linux-hardware.org/?probe=4f27720e96) | Apr 21, 2022 |
| Acer          | Extensa 2519                | Notebook    | [ae1a90a282](https://linux-hardware.org/?probe=ae1a90a282) | Apr 21, 2022 |
| HP            | Notebook                    | Notebook    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | Notebook    | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4151908bf](https://linux-hardware.org/?probe=f4151908bf) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [90486ad164](https://linux-hardware.org/?probe=90486ad164) | Apr 15, 2022 |
| HP            | 17E2                        | Mini pc     | [a7bb99026f](https://linux-hardware.org/?probe=a7bb99026f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [80572def69](https://linux-hardware.org/?probe=80572def69) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [191880e24b](https://linux-hardware.org/?probe=191880e24b) | Apr 14, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8619f35452](https://linux-hardware.org/?probe=8619f35452) | Apr 13, 2022 |
| Dell          | Precision 5530              | Notebook    | [3c4cc67cc4](https://linux-hardware.org/?probe=3c4cc67cc4) | Apr 13, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [3775d7e528](https://linux-hardware.org/?probe=3775d7e528) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [8645c57fcc](https://linux-hardware.org/?probe=8645c57fcc) | Apr 09, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [00d95f7a3a](https://linux-hardware.org/?probe=00d95f7a3a) | Apr 09, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [7e54067e6a](https://linux-hardware.org/?probe=7e54067e6a) | Apr 08, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [c40867ec67](https://linux-hardware.org/?probe=c40867ec67) | Apr 08, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [9a2939bd71](https://linux-hardware.org/?probe=9a2939bd71) | Apr 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [ff290845fe](https://linux-hardware.org/?probe=ff290845fe) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | Notebook    | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| HP            | 0A9Ch                       | Desktop     | [5a415a150f](https://linux-hardware.org/?probe=5a415a150f) | Apr 05, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [c1419a6f3c](https://linux-hardware.org/?probe=c1419a6f3c) | Apr 03, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | Desktop     | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ff7f2845b0](https://linux-hardware.org/?probe=ff7f2845b0) | Apr 01, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6eb9c66f7d](https://linux-hardware.org/?probe=6eb9c66f7d) | Mar 31, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [787cb334c2](https://linux-hardware.org/?probe=787cb334c2) | Mar 28, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8392d5c3fe](https://linux-hardware.org/?probe=8392d5c3fe) | Mar 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [5c424251c8](https://linux-hardware.org/?probe=5c424251c8) | Mar 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b9aec6129a](https://linux-hardware.org/?probe=b9aec6129a) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3429bc98ac](https://linux-hardware.org/?probe=3429bc98ac) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e862658aa](https://linux-hardware.org/?probe=9e862658aa) | Mar 22, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b632c4a0c5](https://linux-hardware.org/?probe=b632c4a0c5) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [73734bbce5](https://linux-hardware.org/?probe=73734bbce5) | Mar 19, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [651e0fb5eb](https://linux-hardware.org/?probe=651e0fb5eb) | Mar 16, 2022 |
| ASRock        | Z370 Gaming K6              | Desktop     | [90bedd5ff6](https://linux-hardware.org/?probe=90bedd5ff6) | Mar 14, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [2e45a56117](https://linux-hardware.org/?probe=2e45a56117) | Mar 14, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [704438d05e](https://linux-hardware.org/?probe=704438d05e) | Mar 13, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [571547ee1d](https://linux-hardware.org/?probe=571547ee1d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [7ce09d403d](https://linux-hardware.org/?probe=7ce09d403d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [ec1783840e](https://linux-hardware.org/?probe=ec1783840e) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [31b0bbe97f](https://linux-hardware.org/?probe=31b0bbe97f) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [ef67eef250](https://linux-hardware.org/?probe=ef67eef250) | Mar 13, 2022 |
| Microsoft     | Surface Book                | Tablet      | [00d499f50c](https://linux-hardware.org/?probe=00d499f50c) | Mar 13, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [8ec8e7be46](https://linux-hardware.org/?probe=8ec8e7be46) | Mar 12, 2022 |
| ASRock        | H61M-S1 PLUS                | Desktop     | [56c15fcbf6](https://linux-hardware.org/?probe=56c15fcbf6) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [2e7a87521b](https://linux-hardware.org/?probe=2e7a87521b) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [a610ee6ad5](https://linux-hardware.org/?probe=a610ee6ad5) | Mar 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [cbff798f89](https://linux-hardware.org/?probe=cbff798f89) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [02e748e3ac](https://linux-hardware.org/?probe=02e748e3ac) | Mar 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c9b7431269](https://linux-hardware.org/?probe=c9b7431269) | Mar 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f118a17b6e](https://linux-hardware.org/?probe=f118a17b6e) | Mar 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [d549055064](https://linux-hardware.org/?probe=d549055064) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | 2129                        | Desktop     | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [37d07ec6df](https://linux-hardware.org/?probe=37d07ec6df) | Mar 02, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [dc25902f7e](https://linux-hardware.org/?probe=dc25902f7e) | Feb 28, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f4a068f57c](https://linux-hardware.org/?probe=f4a068f57c) | Feb 27, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e3931f1fb](https://linux-hardware.org/?probe=2e3931f1fb) | Feb 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [f904e185fb](https://linux-hardware.org/?probe=f904e185fb) | Feb 25, 2022 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [f8f8968f19](https://linux-hardware.org/?probe=f8f8968f19) | Feb 22, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cd61ef5a5d](https://linux-hardware.org/?probe=cd61ef5a5d) | Feb 20, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [100666467c](https://linux-hardware.org/?probe=100666467c) | Feb 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [450f779085](https://linux-hardware.org/?probe=450f779085) | Feb 20, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [686b1350c9](https://linux-hardware.org/?probe=686b1350c9) | Feb 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [24ec19a092](https://linux-hardware.org/?probe=24ec19a092) | Feb 17, 2022 |
| MSI           | CX600                       | Notebook    | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Teclast       | F5                          | Convertible | [ab28d730e6](https://linux-hardware.org/?probe=ab28d730e6) | Feb 15, 2022 |
| MSI           | A55M-P33                    | Desktop     | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [47ff2c9673](https://linux-hardware.org/?probe=47ff2c9673) | Feb 15, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [787eacd33c](https://linux-hardware.org/?probe=787eacd33c) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [91d1953478](https://linux-hardware.org/?probe=91d1953478) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [119cc6c1b1](https://linux-hardware.org/?probe=119cc6c1b1) | Feb 13, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [33abf3e568](https://linux-hardware.org/?probe=33abf3e568) | Feb 11, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [8c571a917d](https://linux-hardware.org/?probe=8c571a917d) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c2729fb959](https://linux-hardware.org/?probe=c2729fb959) | Feb 10, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [34a6010fb2](https://linux-hardware.org/?probe=34a6010fb2) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [e995276798](https://linux-hardware.org/?probe=e995276798) | Feb 07, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [1b0a32e129](https://linux-hardware.org/?probe=1b0a32e129) | Feb 06, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | 2B4B                        | Desktop     | [4205ceb454](https://linux-hardware.org/?probe=4205ceb454) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [af71ad30ed](https://linux-hardware.org/?probe=af71ad30ed) | Jan 30, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [373b062fd0](https://linux-hardware.org/?probe=373b062fd0) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [9cc991a921](https://linux-hardware.org/?probe=9cc991a921) | Jan 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [533df9d207](https://linux-hardware.org/?probe=533df9d207) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [093d240f55](https://linux-hardware.org/?probe=093d240f55) | Jan 28, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [50b28ab929](https://linux-hardware.org/?probe=50b28ab929) | Jan 26, 2022 |
| MSI           | Pulse GL66 11UDK            | Notebook    | [06d5ba6ef3](https://linux-hardware.org/?probe=06d5ba6ef3) | Jan 26, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [cf7b776431](https://linux-hardware.org/?probe=cf7b776431) | Jan 24, 2022 |
| Getac         | V200-G2                     | Notebook    | [6d9b456d5f](https://linux-hardware.org/?probe=6d9b456d5f) | Jan 24, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c07dc3a8ee](https://linux-hardware.org/?probe=c07dc3a8ee) | Jan 24, 2022 |
| ASUSTek       | SABERTOOTH 55i              | Desktop     | [5c67654acf](https://linux-hardware.org/?probe=5c67654acf) | Jan 23, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [170a3c500e](https://linux-hardware.org/?probe=170a3c500e) | Jan 21, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [a8eefb04f1](https://linux-hardware.org/?probe=a8eefb04f1) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d195d57aa4](https://linux-hardware.org/?probe=d195d57aa4) | Jan 21, 2022 |
| Sony          | VPCYB15AB                   | Notebook    | [1d7c8aa76a](https://linux-hardware.org/?probe=1d7c8aa76a) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a30f5fabcd](https://linux-hardware.org/?probe=a30f5fabcd) | Jan 18, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [f55512e3bc](https://linux-hardware.org/?probe=f55512e3bc) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| MSI           | P67A-C45                    | Desktop     | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [99d2f2253d](https://linux-hardware.org/?probe=99d2f2253d) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [2000988c8b](https://linux-hardware.org/?probe=2000988c8b) | Jan 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [30b86e16bf](https://linux-hardware.org/?probe=30b86e16bf) | Jan 10, 2022 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [af7d37f35c](https://linux-hardware.org/?probe=af7d37f35c) | Jan 10, 2022 |
| HP            | 2B29                        | Desktop     | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| Dell          | Latitude XT2                | Notebook    | [65adc4cb22](https://linux-hardware.org/?probe=65adc4cb22) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [85fc03c636](https://linux-hardware.org/?probe=85fc03c636) | Jan 08, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [5d8b5e0c8e](https://linux-hardware.org/?probe=5d8b5e0c8e) | Jan 07, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [4a33da1bc1](https://linux-hardware.org/?probe=4a33da1bc1) | Jan 06, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [39b60e131a](https://linux-hardware.org/?probe=39b60e131a) | Jan 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [c7bf784225](https://linux-hardware.org/?probe=c7bf784225) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [896b348390](https://linux-hardware.org/?probe=896b348390) | Jan 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bfd3b013ad](https://linux-hardware.org/?probe=bfd3b013ad) | Jan 02, 2022 |
| MSI           | C847IS-P33                  | Desktop     | [1ea085e13d](https://linux-hardware.org/?probe=1ea085e13d) | Jan 02, 2022 |
| Toshiba       | AS 1301                     | Notebook    | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [6a29278e3f](https://linux-hardware.org/?probe=6a29278e3f) | Dec 31, 2021 |
| Dell          | 0RY007                      | Desktop     | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b29f429221](https://linux-hardware.org/?probe=b29f429221) | Dec 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [86da0c348f](https://linux-hardware.org/?probe=86da0c348f) | Dec 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [c152f8c702](https://linux-hardware.org/?probe=c152f8c702) | Dec 27, 2021 |
| Dell          | Studio 1737                 | Notebook    | [6b5362714f](https://linux-hardware.org/?probe=6b5362714f) | Dec 27, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [5f62a9d831](https://linux-hardware.org/?probe=5f62a9d831) | Dec 26, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81f1473127](https://linux-hardware.org/?probe=81f1473127) | Dec 26, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [e62e9c50d0](https://linux-hardware.org/?probe=e62e9c50d0) | Dec 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a1b975a4e1](https://linux-hardware.org/?probe=a1b975a4e1) | Dec 26, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [f74478e98e](https://linux-hardware.org/?probe=f74478e98e) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [491f8d7813](https://linux-hardware.org/?probe=491f8d7813) | Dec 21, 2021 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [b2108dd133](https://linux-hardware.org/?probe=b2108dd133) | Dec 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f86ef0f23](https://linux-hardware.org/?probe=1f86ef0f23) | Dec 19, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| MSI           | A55M-P33                    | Desktop     | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bb01b911cd](https://linux-hardware.org/?probe=bb01b911cd) | Dec 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| Google        | Pantheon                    | Notebook    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [8f1556eb30](https://linux-hardware.org/?probe=8f1556eb30) | Dec 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [b5a9d168a5](https://linux-hardware.org/?probe=b5a9d168a5) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [0fca0b679f](https://linux-hardware.org/?probe=0fca0b679f) | Dec 16, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [452044c67e](https://linux-hardware.org/?probe=452044c67e) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [4dc9e683af](https://linux-hardware.org/?probe=4dc9e683af) | Dec 15, 2021 |
| Biostar       | X370GT5                     | Desktop     | [40849a76de](https://linux-hardware.org/?probe=40849a76de) | Dec 14, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [3ad9c4f3dc](https://linux-hardware.org/?probe=3ad9c4f3dc) | Dec 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [696d4a24cd](https://linux-hardware.org/?probe=696d4a24cd) | Dec 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3d396a7f28](https://linux-hardware.org/?probe=3d396a7f28) | Dec 13, 2021 |
| HP            | Elite Dragonfly             | Convertible | [d25e8dec93](https://linux-hardware.org/?probe=d25e8dec93) | Dec 13, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [68bef1611d](https://linux-hardware.org/?probe=68bef1611d) | Dec 13, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 1101      | 63.17%  |
| openSUSE Leap-15.2           | 211       | 12.11%  |
| openSUSE Leap-15.3           | 132       | 7.57%   |
| openSUSE Leap-15.1           | 123       | 7.06%   |
| openSUSE Leap-15.4           | 86        | 4.93%   |
| openSUSE Leap-15.0           | 48        | 2.75%   |
| openSUSE Microos-XXXXXXXX    | 23        | 1.32%   |
| openSUSE 13.2                | 5         | 0.29%   |
| openSUSE Leap-42.2           | 3         | 0.17%   |
| openSUSE                     | 3         | 0.17%   |
| openSUSE Leap-42.3           | 2         | 0.11%   |
| openSUSE Leap-15.5           | 2         | 0.11%   |
| openSUSE 42.3                | 2         | 0.11%   |
| openSUSE Leap-42.1           | 1         | 0.06%   |
| openSUSE 13.1                | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 1689      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.4-1-default             | 49        | 2.42%   |
| 4.12.14-lp151.28.44-default  | 43        | 2.13%   |
| 6.0.8-1-default              | 35        | 1.73%   |
| 5.6.0-1-default              | 31        | 1.53%   |
| 6.0.12-1-default             | 25        | 1.24%   |
| 5.19.2-1-default             | 24        | 1.19%   |
| 5.14.21-150400.22-default    | 24        | 1.19%   |
| 6.0.10-1-default             | 23        | 1.14%   |
| 4.18.15-1-default            | 23        | 1.14%   |
| 5.3.18-lp152.63-default      | 22        | 1.09%   |
| 5.16.11-1-default            | 20        | 0.99%   |
| 5.14.14-1-default            | 20        | 0.99%   |
| 5.6.2-1-default              | 19        | 0.94%   |
| 5.17.9-1-default             | 19        | 0.94%   |
| 5.17.1-1-default             | 19        | 0.94%   |
| 5.3.18-lp152.57-default      | 18        | 0.89%   |
| 5.3.18-59.37-default         | 18        | 0.89%   |
| 5.11.6-1-default             | 18        | 0.89%   |
| 5.8.4-1-default              | 17        | 0.84%   |
| 5.3.18-lp152.41-default      | 17        | 0.84%   |
| 5.19.8-1-default             | 17        | 0.84%   |
| 5.18.6-1-default             | 17        | 0.84%   |
| 5.10.7-1-default             | 17        | 0.84%   |
| 5.3.18-lp152.36-default      | 16        | 0.79%   |
| 5.14.21-150400.24.21-default | 16        | 0.79%   |
| 6.0.3-1-default              | 15        | 0.74%   |
| 5.10.16-1-default            | 15        | 0.74%   |
| 5.6.12-1-default             | 14        | 0.69%   |
| 5.3.18-lp152.50-default      | 14        | 0.69%   |
| 5.13.8-1-default             | 14        | 0.69%   |
| 4.12.14-lp151.28.48-default  | 14        | 0.69%   |
| 6.1.1-1-default              | 13        | 0.64%   |
| 5.3.18-59.27-default         | 13        | 0.64%   |
| 5.3.18-59.19-default         | 13        | 0.64%   |
| 5.14.6-1-default             | 13        | 0.64%   |
| 6.1.3-1-default              | 12        | 0.59%   |
| 5.8.10-1-default             | 12        | 0.59%   |
| 5.3.18-lp152.66-default      | 12        | 0.59%   |
| 5.15.12-1-default            | 12        | 0.59%   |
| 5.14.21-150400.24.18-default | 12        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 312       | 15.98%  |
| 4.12.14 | 158       | 8.09%   |
| 5.14.21 | 85        | 4.35%   |
| 5.17.4  | 49        | 2.51%   |
| 6.0.8   | 35        | 1.79%   |
| 5.6.0   | 33        | 1.69%   |
| 5.14.14 | 30        | 1.54%   |
| 6.0.12  | 26        | 1.33%   |
| 6.0.10  | 24        | 1.23%   |
| 5.19.2  | 24        | 1.23%   |
| 4.18.15 | 23        | 1.18%   |
| 5.6.2   | 21        | 1.08%   |
| 5.17.1  | 20        | 1.02%   |
| 5.16.11 | 20        | 1.02%   |
| 5.17.9  | 19        | 0.97%   |
| 5.12.4  | 19        | 0.97%   |
| 5.11.6  | 19        | 0.97%   |
| 5.8.4   | 18        | 0.92%   |
| 5.14.6  | 18        | 0.92%   |
| 5.10.7  | 18        | 0.92%   |
| 5.19.8  | 17        | 0.87%   |
| 5.18.6  | 17        | 0.87%   |
| 6.0.3   | 16        | 0.82%   |
| 5.12.9  | 15        | 0.77%   |
| 5.12.0  | 15        | 0.77%   |
| 5.10.16 | 15        | 0.77%   |
| 5.9.1   | 14        | 0.72%   |
| 5.6.12  | 14        | 0.72%   |
| 5.18.9  | 14        | 0.72%   |
| 5.13.8  | 14        | 0.72%   |
| 6.1.1   | 13        | 0.67%   |
| 6.1.0   | 13        | 0.67%   |
| 6.1.3   | 12        | 0.61%   |
| 5.8.10  | 12        | 0.61%   |
| 5.8.0   | 12        | 0.61%   |
| 5.16.0  | 12        | 0.61%   |
| 5.15.12 | 12        | 0.61%   |
| 6.1.4   | 11        | 0.56%   |
| 6.0.7   | 11        | 0.56%   |
| 6.0.6   | 11        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 333       | 17.49%  |
| 5.14    | 172       | 9.03%   |
| 4.12    | 158       | 8.3%    |
| 6.0     | 142       | 7.46%   |
| 5.17    | 113       | 5.93%   |
| 5.6     | 82        | 4.31%   |
| 5.16    | 77        | 4.04%   |
| 6.1     | 76        | 3.99%   |
| 5.18    | 76        | 3.99%   |
| 5.12    | 72        | 3.78%   |
| 5.8     | 70        | 3.68%   |
| 5.10    | 68        | 3.57%   |
| 5.19    | 67        | 3.52%   |
| 5.11    | 59        | 3.1%    |
| 5.15    | 58        | 3.05%   |
| 5.13    | 49        | 2.57%   |
| 5.9     | 40        | 2.1%    |
| 5.7     | 36        | 1.89%   |
| 5.5     | 33        | 1.73%   |
| 4.18    | 27        | 1.42%   |
| 5.4     | 21        | 1.1%    |
| 5.0     | 14        | 0.74%   |
| 5.2     | 13        | 0.68%   |
| 4.17    | 11        | 0.58%   |
| 4.4     | 9         | 0.47%   |
| 5.1     | 5         | 0.26%   |
| 4.20    | 5         | 0.26%   |
| 4.3     | 4         | 0.21%   |
| 3.16    | 4         | 0.21%   |
| 4.19    | 3         | 0.16%   |
| 6.2     | 2         | 0.11%   |
| 4.16    | 2         | 0.11%   |
| 4.7     | 1         | 0.05%   |
| 4.1     | 1         | 0.05%   |
| 3.12    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1669      | 98.76%  |
| i686    | 14        | 0.83%   |
| aarch64 | 7         | 0.41%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 917       | 52.37%  |
| GNOME         | 293       | 16.73%  |
| KDE           | 212       | 12.11%  |
| Unknown       | 137       | 7.82%   |
| XFCE          | 91        | 5.2%    |
| MATE          | 20        | 1.14%   |
| X-Cinnamon    | 17        | 0.97%   |
| Cinnamon      | 11        | 0.63%   |
| KDE4          | 9         | 0.51%   |
| LXQt          | 8         | 0.46%   |
| ICEWM         | 5         | 0.29%   |
| Budgie        | 5         | 0.29%   |
| LXDE          | 4         | 0.23%   |
| Deepin        | 3         | 0.17%   |
| WindowMaker   | 2         | 0.11%   |
| sway          | 2         | 0.11%   |
| Pantheon      | 2         | 0.11%   |
| i3            | 2         | 0.11%   |
| GNOME Classic | 2         | 0.11%   |
| awesome       | 2         | 0.11%   |
| Trinity       | 1         | 0.06%   |
| plasma5       | 1         | 0.06%   |
| openbox       | 1         | 0.06%   |
| Herbstluftwm  | 1         | 0.06%   |
| fvwm2         | 1         | 0.06%   |
| default       | 1         | 0.06%   |
| custom        | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1392      | 80%     |
| Wayland     | 276       | 15.86%  |
| Unknown     | 39        | 2.24%   |
| Tty         | 31        | 1.78%   |
| Unspecified | 2         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 662       | 38.18%  |
| LightDM | 567       | 32.7%   |
| SDDM    | 388       | 22.38%  |
| XDM     | 108       | 6.23%   |
| GDM     | 9         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 591       | 33.91%  |
| de_DE   | 205       | 11.76%  |
| Unknown | 179       | 10.27%  |
| POSIX   | 170       | 9.75%   |
| en_GB   | 116       | 6.66%   |
| pt_BR   | 76        | 4.36%   |
| ru_RU   | 68        | 3.9%    |
| es_ES   | 50        | 2.87%   |
| fr_FR   | 40        | 2.29%   |
| it_IT   | 38        | 2.18%   |
| pl_PL   | 25        | 1.43%   |
| nl_NL   | 19        | 1.09%   |
| pt_PT   | 18        | 1.03%   |
| zh_CN   | 11        | 0.63%   |
| cs_CZ   | 10        | 0.57%   |
| hu_HU   | 8         | 0.46%   |
| fi_FI   | 8         | 0.46%   |
| sv_SE   | 6         | 0.34%   |
| es_MX   | 6         | 0.34%   |
| es_AR   | 6         | 0.34%   |
| C       | 6         | 0.34%   |
| en_IN   | 5         | 0.29%   |
| en_DE   | 5         | 0.29%   |
| tr_TR   | 4         | 0.23%   |
| nn_NO   | 4         | 0.23%   |
| nl_BE   | 4         | 0.23%   |
| nb_NO   | 4         | 0.23%   |
| en_IE   | 4         | 0.23%   |
| en_AU   | 4         | 0.23%   |
| hr_HR   | 3         | 0.17%   |
| en_FI   | 3         | 0.17%   |
| en_CH   | 3         | 0.17%   |
| cv_RU   | 3         | 0.17%   |
| bg_BG   | 3         | 0.17%   |
| sk_SK   | 2         | 0.11%   |
| ru_UA   | 2         | 0.11%   |
| ko_KR   | 2         | 0.11%   |
| ja_JP   | 2         | 0.11%   |
| en_PH   | 2         | 0.11%   |
| en_NL   | 2         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1108      | 64.91%  |
| BIOS | 599       | 35.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Btrfs    | 1171      | 68.52%  |
| Ext4     | 380       | 22.24%  |
| Xfs      | 73        | 4.27%   |
| Unknown  | 61        | 3.57%   |
| Overlay  | 17        | 0.99%   |
| Tmpfs    | 2         | 0.12%   |
| Ext3     | 2         | 0.12%   |
| Reiserfs | 1         | 0.06%   |
| F2fs     | 1         | 0.06%   |
| Ext2     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 963       | 55.96%  |
| Unknown | 595       | 34.57%  |
| MBR     | 163       | 9.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1438      | 83.36%  |
| Yes       | 287       | 16.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1230      | 71.64%  |
| Yes       | 487       | 28.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 274       | 16.22%  |
| Lenovo                  | 259       | 15.33%  |
| Hewlett-Packard         | 243       | 14.39%  |
| Dell                    | 206       | 12.2%   |
| Gigabyte Technology     | 140       | 8.29%   |
| MSI                     | 122       | 7.22%   |
| ASRock                  | 81        | 4.8%    |
| Acer                    | 70        | 4.14%   |
| Apple                   | 38        | 2.25%   |
| Fujitsu                 | 21        | 1.24%   |
| Toshiba                 | 19        | 1.12%   |
| TUXEDO                  | 16        | 0.95%   |
| HUAWEI                  | 15        | 0.89%   |
| Intel                   | 14        | 0.83%   |
| Sony                    | 12        | 0.71%   |
| Samsung Electronics     | 12        | 0.71%   |
| Supermicro              | 9         | 0.53%   |
| Biostar                 | 9         | 0.53%   |
| Medion                  | 8         | 0.47%   |
| Fujitsu Siemens         | 7         | 0.41%   |
| Pegatron                | 6         | 0.36%   |
| Notebook                | 5         | 0.3%    |
| Foxconn                 | 5         | 0.3%    |
| Alienware               | 5         | 0.3%    |
| Unknown                 | 5         | 0.3%    |
| Raspberry Pi Foundation | 4         | 0.24%   |
| Positivo                | 4         | 0.24%   |
| Timi                    | 3         | 0.18%   |
| Razer                   | 3         | 0.18%   |
| Microsoft               | 3         | 0.18%   |
| LG Electronics          | 3         | 0.18%   |
| Google                  | 3         | 0.18%   |
| Clevo                   | 3         | 0.18%   |
| BESSTAR Tech            | 3         | 0.18%   |
| Avell High Performance  | 3         | 0.18%   |
| TYAN Computer           | 2         | 0.12%   |
| SLIMBOOK                | 2         | 0.12%   |
| Shuttle                 | 2         | 0.12%   |
| Semp Toshiba            | 2         | 0.12%   |
| Schenker                | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 21        | 1.24%   |
| Unknown                              | 10        | 0.59%   |
| Dell OptiPlex 9020                   | 8         | 0.47%   |
| MSI MS-7B86                          | 7         | 0.41%   |
| HP Notebook                          | 7         | 0.41%   |
| MSI MS-7B89                          | 6         | 0.36%   |
| Dell Precision 5530                  | 6         | 0.36%   |
| ASRock B450M Pro4                    | 6         | 0.36%   |
| MSI MS-7C37                          | 5         | 0.3%    |
| HP Pavilion dv7                      | 5         | 0.3%    |
| HP Pavilion dv6                      | 5         | 0.3%    |
| Gigabyte B450M DS3H                  | 5         | 0.3%    |
| Gigabyte B450 AORUS M                | 5         | 0.3%    |
| Gigabyte 970A-DS3P                   | 5         | 0.3%    |
| Dell Latitude 7490                   | 5         | 0.3%    |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.3%    |
| Apple MacBookPro9,2                  | 5         | 0.3%    |
| MSI MS-7C02                          | 4         | 0.24%   |
| MSI MS-7B79                          | 4         | 0.24%   |
| MSI MS-7A34                          | 4         | 0.24%   |
| HP Pavilion g6                       | 4         | 0.24%   |
| HP Laptop 17-ca0xxx                  | 4         | 0.24%   |
| Gigabyte X570 AORUS MASTER           | 4         | 0.24%   |
| Dell XPS 15 9560                     | 4         | 0.24%   |
| ASUS PRIME A320M-K                   | 4         | 0.24%   |
| ASUS M5A78L-M/USB3                   | 4         | 0.24%   |
| ASUS CROSSHAIR V FORMULA-Z           | 4         | 0.24%   |
| ASRock X570 Steel Legend             | 4         | 0.24%   |
| TUXEDO Pulse 15 Gen1                 | 3         | 0.18%   |
| MSI MS-7C91                          | 3         | 0.18%   |
| MSI MS-7A38                          | 3         | 0.18%   |
| MSI MS-7A33                          | 3         | 0.18%   |
| Lenovo ThinkBook 14 G3 ACL 21A2      | 3         | 0.18%   |
| Lenovo IdeaPad Y700-15ISK 80NV       | 3         | 0.18%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 3         | 0.18%   |
| HP Z840 Workstation                  | 3         | 0.18%   |
| HP Z620 Workstation                  | 3         | 0.18%   |
| HP ProLiant MicroServer              | 3         | 0.18%   |
| HP Laptop 15-bs0xx                   | 3         | 0.18%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 140       | 8.29%   |
| Dell Inspiron      | 49        | 2.9%    |
| Dell Latitude      | 47        | 2.78%   |
| Lenovo IdeaPad     | 41        | 2.43%   |
| Acer Aspire        | 41        | 2.43%   |
| HP Pavilion        | 39        | 2.31%   |
| HP EliteBook       | 36        | 2.13%   |
| ASUS PRIME         | 35        | 2.07%   |
| ASUS ROG           | 31        | 1.84%   |
| Dell OptiPlex      | 28        | 1.66%   |
| ASUS TUF           | 28        | 1.66%   |
| Dell XPS           | 26        | 1.54%   |
| Dell Precision     | 22        | 1.3%    |
| ASUS All           | 21        | 1.24%   |
| Lenovo Yoga        | 20        | 1.18%   |
| HP Laptop          | 20        | 1.18%   |
| HP ProBook         | 19        | 1.12%   |
| Toshiba Satellite  | 18        | 1.07%   |
| ASUS VivoBook      | 18        | 1.07%   |
| HP ZBook           | 17        | 1.01%   |
| HP ENVY            | 17        | 1.01%   |
| Lenovo ThinkCentre | 14        | 0.83%   |
| HP Compaq          | 13        | 0.77%   |
| Gigabyte X570      | 12        | 0.71%   |
| Dell PowerEdge     | 12        | 0.71%   |
| Fujitsu LIFEBOOK   | 11        | 0.65%   |
| Gigabyte B550      | 10        | 0.59%   |
| ASUS Zenbook       | 10        | 0.59%   |
| Unknown            | 10        | 0.59%   |
| HP OMEN            | 9         | 0.53%   |
| ASUS M5A78L-M      | 9         | 0.53%   |
| Gigabyte B450      | 8         | 0.47%   |
| Dell Vostro        | 8         | 0.47%   |
| ASRock B450M       | 8         | 0.47%   |
| Acer Swift         | 8         | 0.47%   |
| MSI MS-7B86        | 7         | 0.41%   |
| HP Notebook        | 7         | 0.41%   |
| Gigabyte B450M     | 7         | 0.41%   |
| ASRock X570        | 7         | 0.41%   |
| MSI MS-7B89        | 6         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 195       | 11.55%  |
| 2018 | 186       | 11.01%  |
| 2019 | 184       | 10.89%  |
| 2017 | 142       | 8.41%   |
| 2021 | 139       | 8.23%   |
| 2013 | 125       | 7.4%    |
| 2012 | 120       | 7.1%    |
| 2015 | 104       | 6.16%   |
| 2011 | 91        | 5.39%   |
| 2014 | 83        | 4.91%   |
| 2016 | 82        | 4.85%   |
| 2010 | 68        | 4.03%   |
| 2009 | 50        | 2.96%   |
| 2008 | 43        | 2.55%   |
| 2022 | 41        | 2.43%   |
| 2007 | 20        | 1.18%   |
| 2006 | 8         | 0.47%   |
| 2005 | 5         | 0.3%    |
| 2004 | 2         | 0.12%   |
| 2000 | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 851       | 50.38%  |
| Desktop        | 698       | 41.33%  |
| Convertible    | 61        | 3.61%   |
| Mini pc        | 25        | 1.48%   |
| Server         | 23        | 1.36%   |
| All in one     | 18        | 1.07%   |
| System on chip | 6         | 0.36%   |
| Tablet         | 6         | 0.36%   |
| Firewall       | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1468      | 85.7%   |
| Enabled  | 245       | 14.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1684      | 99.7%   |
| Yes  | 5         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 436       | 25.51%  |
| 4.01-8.0        | 368       | 21.53%  |
| 8.01-16.0       | 336       | 19.66%  |
| 32.01-64.0      | 252       | 14.75%  |
| 3.01-4.0        | 153       | 8.95%   |
| 64.01-256.0     | 72        | 4.21%   |
| 24.01-32.0      | 40        | 2.34%   |
| 1.01-2.0        | 23        | 1.35%   |
| 2.01-3.0        | 11        | 0.64%   |
| Unknown         | 10        | 0.59%   |
| 0.51-1.0        | 6         | 0.35%   |
| More than 256.0 | 1         | 0.06%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 468       | 25.35%  |
| 4.01-8.0   | 443       | 24%     |
| 1.01-2.0   | 405       | 21.94%  |
| 3.01-4.0   | 305       | 16.52%  |
| 8.01-16.0  | 116       | 6.28%   |
| 0.51-1.0   | 64        | 3.47%   |
| 16.01-24.0 | 15        | 0.81%   |
| 0.01-0.5   | 13        | 0.7%    |
| Unknown    | 10        | 0.54%   |
| 24.01-32.0 | 6         | 0.33%   |
| 32.01-64.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 843       | 48.64%  |
| 2       | 476       | 27.47%  |
| 3       | 189       | 10.91%  |
| 4       | 103       | 5.94%   |
| 5       | 55        | 3.17%   |
| 6       | 34        | 1.96%   |
| 7       | 19        | 1.1%    |
| 8       | 3         | 0.17%   |
| 0       | 3         | 0.17%   |
| 13      | 2         | 0.12%   |
| 10      | 2         | 0.12%   |
| 35      | 1         | 0.06%   |
| 16      | 1         | 0.06%   |
| 9       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1079      | 63.43%  |
| Yes       | 622       | 36.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1489      | 88.05%  |
| No        | 202       | 11.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1246      | 73.51%  |
| No        | 449       | 26.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1060      | 61.99%  |
| No        | 650       | 38.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 307       | 18.11%  |
| Germany     | 298       | 17.58%  |
| Brazil      | 105       | 6.19%   |
| Russia      | 85        | 5.01%   |
| Italy       | 65        | 3.83%   |
| France      | 64        | 3.78%   |
| UK          | 59        | 3.48%   |
| Netherlands | 55        | 3.24%   |
| Spain       | 42        | 2.48%   |
| Switzerland | 39        | 2.3%    |
| Canada      | 37        | 2.18%   |
| Poland      | 36        | 2.12%   |
| Sweden      | 27        | 1.59%   |
| India       | 27        | 1.59%   |
| Belgium     | 24        | 1.42%   |
| Austria     | 24        | 1.42%   |
| Mexico      | 23        | 1.36%   |
| Czechia     | 22        | 1.3%    |
| China       | 22        | 1.3%    |
| Australia   | 21        | 1.24%   |
| Hungary     | 18        | 1.06%   |
| Finland     | 17        | 1%      |
| Portugal    | 16        | 0.94%   |
| Norway      | 16        | 0.94%   |
| Ukraine     | 15        | 0.88%   |
| Turkey      | 12        | 0.71%   |
| Romania     | 12        | 0.71%   |
| Greece      | 12        | 0.71%   |
| Serbia      | 11        | 0.65%   |
| Bulgaria    | 11        | 0.65%   |
| Argentina   | 10        | 0.59%   |
| Chile       | 8         | 0.47%   |
| Belarus     | 8         | 0.47%   |
| Thailand    | 7         | 0.41%   |
| Peru        | 7         | 0.41%   |
| Japan       | 7         | 0.41%   |
| Croatia     | 7         | 0.41%   |
| Luxembourg  | 6         | 0.35%   |
| Israel      | 6         | 0.35%   |
| Indonesia   | 6         | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 24        | 1.34%   |
| Moscow            | 23        | 1.29%   |
| Vienna            | 15        | 0.84%   |
| Sao Paulo         | 15        | 0.84%   |
| Rio de Janeiro    | 13        | 0.73%   |
| Paris             | 13        | 0.73%   |
| Munich            | 13        | 0.73%   |
| Zurich            | 11        | 0.62%   |
| St Petersburg     | 11        | 0.62%   |
| Prague            | 11        | 0.62%   |
| Milan             | 11        | 0.62%   |
| Littleton         | 11        | 0.62%   |
| Amsterdam         | 11        | 0.62%   |
| Frankfurt am Main | 10        | 0.56%   |
| Budapest          | 10        | 0.56%   |
| Neuchatel         | 9         | 0.5%    |
| Warsaw            | 8         | 0.45%   |
| Rome              | 8         | 0.45%   |
| Riverton          | 8         | 0.45%   |
| Madrid            | 8         | 0.45%   |
| Los Angeles       | 8         | 0.45%   |
| Hamburg           | 8         | 0.45%   |
| Sydney            | 7         | 0.39%   |
| Sofia             | 7         | 0.39%   |
| Montreal          | 7         | 0.39%   |
| Gothenburg        | 7         | 0.39%   |
| Bengaluru         | 7         | 0.39%   |
| Belgrade          | 7         | 0.39%   |
| Athens            | 7         | 0.39%   |
| Schrobenhausen    | 6         | 0.34%   |
| Houston           | 6         | 0.34%   |
| Halle             | 6         | 0.34%   |
| The Hague         | 5         | 0.28%   |
| Santiago          | 5         | 0.28%   |
| San Jose          | 5         | 0.28%   |
| Minsk             | 5         | 0.28%   |
| Miami             | 5         | 0.28%   |
| Mexico City       | 5         | 0.28%   |
| Lisbon            | 5         | 0.28%   |
| Leipzig           | 5         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 559       | 855    | 19.84%  |
| WDC                         | 423       | 707    | 15.02%  |
| Seagate                     | 412       | 743    | 14.63%  |
| Toshiba                     | 178       | 230    | 6.32%   |
| Kingston                    | 154       | 199    | 5.47%   |
| SanDisk                     | 143       | 179    | 5.08%   |
| Crucial                     | 118       | 158    | 4.19%   |
| Intel                       | 81        | 100    | 2.88%   |
| SK hynix                    | 75        | 102    | 2.66%   |
| Unknown                     | 64        | 95     | 2.27%   |
| Hitachi                     | 54        | 65     | 1.92%   |
| HGST                        | 50        | 70     | 1.77%   |
| A-DATA Technology           | 35        | 47     | 1.24%   |
| Micron Technology           | 33        | 42     | 1.17%   |
| PNY                         | 23        | 31     | 0.82%   |
| Phison                      | 23        | 31     | 0.82%   |
| KIOXIA                      | 19        | 20     | 0.67%   |
| Silicon Motion              | 18        | 19     | 0.64%   |
| Intenso                     | 17        | 23     | 0.6%    |
| Apple                       | 16        | 19     | 0.57%   |
| SPCC                        | 15        | 19     | 0.53%   |
| China                       | 15        | 17     | 0.53%   |
| Phison Electronics          | 13        | 19     | 0.46%   |
| Transcend                   | 12        | 13     | 0.43%   |
| LITEON                      | 12        | 13     | 0.43%   |
| Hewlett-Packard             | 12        | 17     | 0.43%   |
| Fujitsu                     | 12        | 15     | 0.43%   |
| Corsair                     | 11        | 12     | 0.39%   |
| Kingston Technology Company | 10        | 10     | 0.35%   |
| OCZ                         | 8         | 13     | 0.28%   |
| Micron/Crucial Technology   | 8         | 14     | 0.28%   |
| Maxtor                      | 8         | 8      | 0.28%   |
| JMicron Technology          | 8         | 8      | 0.28%   |
| GOODRAM                     | 8         | 8      | 0.28%   |
| XPG                         | 7         | 9      | 0.25%   |
| Team                        | 7         | 7      | 0.25%   |
| Patriot                     | 7         | 7      | 0.25%   |
| LITEONIT                    | 6         | 6      | 0.21%   |
| SABRENT                     | 5         | 6      | 0.18%   |
| Plextor                     | 5         | 6      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 44        | 1.37%   |
| Samsung SSD 850 EVO 250GB                           | 32        | 1%      |
| Samsung SSD 860 EVO 1TB                             | 28        | 0.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 25        | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB                      | 23        | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 23        | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB                      | 20        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 20        | 0.62%   |
| Kingston SA400S37240G 240GB SSD                     | 19        | 0.59%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 18        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 18        | 0.56%   |
| Samsung SSD 850 EVO 500GB                           | 18        | 0.56%   |
| Kingston SA400S37480G 480GB SSD                     | 17        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 16        | 0.5%    |
| Unknown SD/MMC/MS PRO 2GB                           | 15        | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB                      | 15        | 0.47%   |
| Samsung SSD 970 EVO 500GB                           | 15        | 0.47%   |
| Kingston SA400S37120G 120GB SSD                     | 15        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                      | 14        | 0.44%   |
| Samsung SSD 860 QVO 1TB                             | 14        | 0.44%   |
| Samsung SSD 860 EVO 250GB                           | 14        | 0.44%   |
| Samsung SSD 840 EVO 250GB                           | 14        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 14        | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 14        | 0.44%   |
| Toshiba MQ04ABF100 1TB                              | 13        | 0.4%    |
| Seagate ST500DM002-1BD142 500GB                     | 13        | 0.4%    |
| Seagate ST3500418AS 500GB                           | 13        | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB                      | 13        | 0.4%    |
| Samsung SSD 850 PRO 256GB                           | 13        | 0.4%    |
| Samsung NVMe SSD Drive 500GB                        | 13        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 12        | 0.37%   |
| Toshiba MQ01ABD100 1TB                              | 12        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 12        | 0.37%   |
| Seagate Expansion 240GB                             | 12        | 0.37%   |
| Samsung NVMe SSD Drive 512GB                        | 12        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                    | 12        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 11        | 0.34%   |
| Toshiba DT01ACA200 2TB                              | 10        | 0.31%   |
| Seagate Expansion Desk 6TB                          | 10        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 406       | 725    | 36.68%  |
| WDC                 | 336       | 561    | 30.35%  |
| Toshiba             | 128       | 169    | 11.56%  |
| Samsung Electronics | 61        | 91     | 5.51%   |
| Hitachi             | 54        | 65     | 4.88%   |
| HGST                | 50        | 70     | 4.52%   |
| Unknown             | 16        | 17     | 1.45%   |
| Fujitsu             | 12        | 15     | 1.08%   |
| Maxtor              | 7         | 7      | 0.63%   |
| Apple               | 6         | 8      | 0.54%   |
| SABRENT             | 5         | 6      | 0.45%   |
| Hewlett-Packard     | 5         | 8      | 0.45%   |
| ASMT                | 3         | 4      | 0.27%   |
| WD MediaMax         | 2         | 2      | 0.18%   |
| Pioneer             | 2         | 7      | 0.18%   |
| JMicron Technology  | 2         | 2      | 0.18%   |
| Intenso             | 2         | 7      | 0.18%   |
| USB3.0              | 1         | 1      | 0.09%   |
| USB                 | 1         | 1      | 0.09%   |
| UD0401              | 1         | 1      | 0.09%   |
| Synology            | 1         | 1      | 0.09%   |
| MaxDigital          | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 2      | 0.09%   |
| IBM-207x            | 1         | 8      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |
| DELLBOSS            | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 289       | 418    | 29.31%  |
| Kingston            | 114       | 148    | 11.56%  |
| Crucial             | 106       | 141    | 10.75%  |
| SanDisk             | 97        | 117    | 9.84%   |
| WDC                 | 67        | 83     | 6.8%    |
| A-DATA Technology   | 25        | 32     | 2.54%   |
| Intel               | 24        | 31     | 2.43%   |
| Toshiba             | 18        | 22     | 1.83%   |
| SK hynix            | 18        | 29     | 1.83%   |
| PNY                 | 18        | 22     | 1.83%   |
| Micron Technology   | 16        | 24     | 1.62%   |
| China               | 15        | 17     | 1.52%   |
| Intenso             | 13        | 13     | 1.32%   |
| LITEON              | 12        | 13     | 1.22%   |
| SPCC                | 10        | 14     | 1.01%   |
| Transcend           | 9         | 10     | 0.91%   |
| OCZ                 | 8         | 13     | 0.81%   |
| Apple               | 8         | 9      | 0.81%   |
| Patriot             | 7         | 7      | 0.71%   |
| GOODRAM             | 7         | 7      | 0.71%   |
| Corsair             | 7         | 7      | 0.71%   |
| Team                | 6         | 6      | 0.61%   |
| Seagate             | 6         | 7      | 0.61%   |
| LITEONIT            | 6         | 6      | 0.61%   |
| Plextor             | 4         | 5      | 0.41%   |
| Mushkin             | 4         | 6      | 0.41%   |
| KingSpec            | 4         | 9      | 0.41%   |
| JMicron Technology  | 4         | 4      | 0.41%   |
| Hewlett-Packard     | 4         | 6      | 0.41%   |
| TO Exter            | 3         | 3      | 0.3%    |
| Biostar             | 3         | 5      | 0.3%    |
| Apacer              | 3         | 6      | 0.3%    |
| Smartbuy            | 2         | 4      | 0.2%    |
| Smart               | 2         | 2      | 0.2%    |
| Netac               | 2         | 2      | 0.2%    |
| MyDigitalSSD        | 2         | 2      | 0.2%    |
| Gigabyte Technology | 2         | 4      | 0.2%    |
| GALAX               | 2         | 2      | 0.2%    |
| Fanxiang            | 2         | 3      | 0.2%    |
| Advantech           | 2         | 2      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 879       | 1782   | 35.59%  |
| SSD     | 841       | 1299   | 34.05%  |
| NVMe    | 678       | 959    | 27.45%  |
| MMC     | 47        | 68     | 1.9%    |
| Unknown | 25        | 35     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1277      | 2960   | 60.55%  |
| NVMe | 678       | 958    | 32.15%  |
| SAS  | 107       | 157    | 5.07%   |
| MMC  | 47        | 68     | 2.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 943       | 1544   | 50.35%  |
| 0.51-1.0   | 554       | 889    | 29.58%  |
| 1.01-2.0   | 201       | 352    | 10.73%  |
| 3.01-4.0   | 63        | 102    | 3.36%   |
| 2.01-3.0   | 60        | 86     | 3.2%    |
| 4.01-10.0  | 47        | 98     | 2.51%   |
| 10.01-20.0 | 5         | 10     | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 519       | 29.46%  |
| 1001-2000      | 381       | 21.62%  |
| 501-1000       | 256       | 14.53%  |
| 2001-3000      | 234       | 13.28%  |
| 251-500        | 170       | 9.65%   |
| 101-250        | 104       | 5.9%    |
| Unknown        | 41        | 2.33%   |
| 51-100         | 28        | 1.59%   |
| 1-20           | 16        | 0.91%   |
| 21-50          | 13        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 353       | 19.23%  |
| 251-500        | 324       | 17.65%  |
| 501-1000       | 264       | 14.38%  |
| 51-100         | 255       | 13.89%  |
| 1001-2000      | 226       | 12.31%  |
| More than 3000 | 109       | 5.94%   |
| 1-20           | 104       | 5.66%   |
| 2001-3000      | 85        | 4.63%   |
| 21-50          | 75        | 4.08%   |
| Unknown        | 41        | 2.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6         | 8      | 2.44%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 2.03%   |
| Samsung Electronics SSD 840 EVO 120GB | 4         | 5      | 1.63%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.63%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 3      | 1.22%   |
| Seagate ST2000DM001-1CH164 2TB        | 3         | 4      | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 1.22%   |
| Seagate ST1000DM003-1SB102 1TB        | 3         | 3      | 1.22%   |
| Samsung Electronics HD501LJ 500GB     | 3         | 4      | 1.22%   |
| WDC WD6400AAKS-22A7B2 640GB           | 2         | 2      | 0.81%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2         | 3      | 0.81%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 2      | 0.81%   |
| WDC WD10JFCX-68N6GN0 1TB              | 2         | 3      | 0.81%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.81%   |
| Toshiba MK5055GSX 500GB               | 2         | 4      | 0.81%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.81%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.81%   |
| Seagate ST31000528AS 1TB              | 2         | 5      | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 0.81%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 0.81%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 2         | 2      | 0.81%   |
| Samsung Electronics HN-M500MBB 500GB  | 2         | 2      | 0.81%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 0.81%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 3      | 0.81%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3      | 0.81%   |
| Kingston SMS200S3240G 240GB SSD       | 2         | 2      | 0.81%   |
| Kingston SHFS37A120G 120GB SSD        | 2         | 2      | 0.81%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.81%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 0.81%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.81%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 0.81%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 0.41%   |
| XPG GAMMIX S41 512GB                  | 1         | 1      | 0.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.41%   |
| WDC WD800AAJS-75M0A0 80GB             | 1         | 1      | 0.41%   |
| WDC WD7500AAKS-00RBA0 752GB           | 1         | 1      | 0.41%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 0.41%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 0.41%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.41%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 80     | 26.78%  |
| WDC                 | 41        | 48     | 17.15%  |
| Samsung Electronics | 31        | 38     | 12.97%  |
| Toshiba             | 23        | 33     | 9.62%   |
| Hitachi             | 11        | 12     | 4.6%    |
| Kingston            | 10        | 14     | 4.18%   |
| Crucial             | 8         | 9      | 3.35%   |
| HGST                | 7         | 7      | 2.93%   |
| SanDisk             | 6         | 6      | 2.51%   |
| Intel               | 6         | 7      | 2.51%   |
| Maxtor              | 4         | 4      | 1.67%   |
| SK hynix            | 2         | 2      | 0.84%   |
| Patriot             | 2         | 2      | 0.84%   |
| OCZ                 | 2         | 2      | 0.84%   |
| LITEONIT            | 2         | 2      | 0.84%   |
| Fujitsu             | 2         | 3      | 0.84%   |
| Corsair             | 2         | 2      | 0.84%   |
| XrayDisk            | 1         | 1      | 0.42%   |
| XPG                 | 1         | 1      | 0.42%   |
| WD MediaMax         | 1         | 1      | 0.42%   |
| Transcend           | 1         | 1      | 0.42%   |
| SuperTalent         | 1         | 1      | 0.42%   |
| SSSTC               | 1         | 1      | 0.42%   |
| SPCC                | 1         | 1      | 0.42%   |
| Phison              | 1         | 1      | 0.42%   |
| Micron Technology   | 1         | 1      | 0.42%   |
| LEQIXIANG           | 1         | 1      | 0.42%   |
| KingFast            | 1         | 1      | 0.42%   |
| Intenso             | 1         | 1      | 0.42%   |
| Hewlett-Packard     | 1         | 1      | 0.42%   |
| GOODRAM             | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |
| A-DATA Technology   | 1         | 2      | 0.42%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 80     | 37.65%  |
| WDC                 | 40        | 47     | 23.53%  |
| Toshiba             | 22        | 32     | 12.94%  |
| Samsung Electronics | 17        | 23     | 10%     |
| Hitachi             | 11        | 12     | 6.47%   |
| HGST                | 7         | 7      | 4.12%   |
| Maxtor              | 4         | 4      | 2.35%   |
| Fujitsu             | 2         | 3      | 1.18%   |
| WD MediaMax         | 1         | 1      | 0.59%   |
| Hewlett-Packard     | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 153       | 211    | 69.55%  |
| SSD  | 56        | 66     | 25.45%  |
| NVMe | 11        | 11     | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1         | 3      | 33.33%  |
| Hitachi HDS721025CLA382 250GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 3      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1037      | 2203   | 53.84%  |
| Detected | 673       | 1647   | 34.94%  |
| Malfunc  | 213       | 288    | 11.06%  |
| Failed   | 3         | 5      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1018      | 43.63%  |
| AMD                              | 461       | 19.76%  |
| Samsung Electronics              | 254       | 10.89%  |
| SanDisk                          | 96        | 4.11%   |
| SK hynix                         | 57        | 2.44%   |
| Kingston Technology Company      | 54        | 2.31%   |
| ASMedia Technology               | 54        | 2.31%   |
| Phison Electronics               | 47        | 2.01%   |
| Toshiba America Info Systems     | 37        | 1.59%   |
| Marvell Technology Group         | 29        | 1.24%   |
| JMicron Technology               | 24        | 1.03%   |
| Silicon Motion                   | 23        | 0.99%   |
| Nvidia                           | 23        | 0.99%   |
| Micron/Crucial Technology        | 20        | 0.86%   |
| Micron Technology                | 18        | 0.77%   |
| KIOXIA                           | 17        | 0.73%   |
| LSI Logic / Symbios Logic        | 15        | 0.64%   |
| ADATA Technology                 | 14        | 0.6%    |
| Broadcom / LSI                   | 11        | 0.47%   |
| Realtek Semiconductor            | 9         | 0.39%   |
| Solid State Storage Technology   | 6         | 0.26%   |
| Union Memory (Shenzhen)          | 5         | 0.21%   |
| Silicon Image                    | 5         | 0.21%   |
| VIA Technologies                 | 4         | 0.17%   |
| Seagate Technology               | 4         | 0.17%   |
| Adaptec                          | 4         | 0.17%   |
| Shenzhen Longsys Electronics     | 3         | 0.13%   |
| Lite-On Technology               | 3         | 0.13%   |
| Lenovo                           | 3         | 0.13%   |
| Yangtze Memory Technologies      | 2         | 0.09%   |
| Promise Technology               | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.09%   |
| Apple                            | 2         | 0.09%   |
| Tekram Technology                | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Huawei Technologies              | 1         | 0.04%   |
| Hewlett-Packard                  | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| ATTO Technology                  | 1         | 0.04%   |
| 3ware                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 313       | 11.66%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 149       | 5.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 91        | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 85        | 3.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 76        | 2.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 65        | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 57        | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 53        | 1.97%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 50        | 1.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 46        | 1.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 45        | 1.68%   |
| Intel Volume Management Device NVMe RAID Controller                            | 41        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 41        | 1.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 39        | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 38        | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 36        | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 33        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 32        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 32        | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 32        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 32        | 1.19%   |
| Samsung NVMe SSD Controller 980                                                | 31        | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 30        | 1.12%   |
| Phison E12 NVMe Controller                                                     | 29        | 1.08%   |
| Intel SSD 660P Series                                                          | 29        | 1.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 27        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 27        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 26        | 0.97%   |
| AMD 300 Series Chipset SATA Controller                                         | 26        | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 23        | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 22        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 22        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 21        | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21        | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                        | 19        | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 19        | 0.71%   |
| Micron Non-Volatile memory controller                                          | 18        | 0.67%   |
| Intel SATA Controller [RAID mode]                                              | 18        | 0.67%   |
| Kingston Company A2000 NVMe SSD                                                | 16        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1307      | 56.26%  |
| NVMe | 671       | 28.89%  |
| IDE  | 180       | 7.75%   |
| RAID | 142       | 6.11%   |
| SAS  | 12        | 0.52%   |
| SCSI | 11        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 1126      | 66.67%  |
| AMD       | 556       | 32.92%  |
| ARM       | 6         | 0.36%   |
| HISILICON | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 1.42%   |
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor           | 17        | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 0.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.95%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 16        | 0.95%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 16        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 14        | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 0.77%   |
| AMD FX-8350 Eight-Core Processor              | 13        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 11        | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 0.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 11        | 0.65%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 11        | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 10        | 0.59%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.53%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 9         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 0.53%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 8         | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 8         | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 8         | 0.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 366       | 21.64%  |
| Intel Core i5           | 336       | 19.87%  |
| AMD Ryzen 5             | 157       | 9.28%   |
| AMD Ryzen 7             | 122       | 7.21%   |
| Other                   | 114       | 6.74%   |
| Intel Core i3           | 82        | 4.85%   |
| Intel Xeon              | 61        | 3.61%   |
| Intel Core 2 Duo        | 48        | 2.84%   |
| AMD Ryzen 9             | 45        | 2.66%   |
| AMD FX                  | 40        | 2.37%   |
| Intel Celeron           | 35        | 2.07%   |
| Intel Pentium           | 23        | 1.36%   |
| AMD Ryzen 3             | 21        | 1.24%   |
| AMD Ryzen 7 PRO         | 18        | 1.06%   |
| Intel Core i9           | 16        | 0.95%   |
| AMD A8                  | 16        | 0.95%   |
| AMD Phenom II X4        | 14        | 0.83%   |
| AMD A10                 | 13        | 0.77%   |
| Intel Pentium Dual-Core | 12        | 0.71%   |
| Intel Atom              | 12        | 0.71%   |
| AMD Athlon              | 10        | 0.59%   |
| AMD A6                  | 10        | 0.59%   |
| Intel Core 2 Quad       | 9         | 0.53%   |
| AMD Ryzen 5 PRO         | 9         | 0.53%   |
| Intel Pentium Silver    | 8         | 0.47%   |
| AMD Phenom II X6        | 8         | 0.47%   |
| AMD Athlon II X2        | 7         | 0.41%   |
| AMD A4                  | 7         | 0.41%   |
| Intel Core 2            | 5         | 0.3%    |
| AMD Ryzen Threadripper  | 5         | 0.3%    |
| AMD Opteron             | 5         | 0.3%    |
| AMD E2                  | 5         | 0.3%    |
| Intel Genuine           | 3         | 0.18%   |
| AMD EPYC                | 3         | 0.18%   |
| AMD E                   | 3         | 0.18%   |
| Intel Pentium Dual      | 2         | 0.12%   |
| Intel Pentium 4         | 2         | 0.12%   |
| Intel Core m3           | 2         | 0.12%   |
| Intel Core M            | 2         | 0.12%   |
| AMD Turion II Neo       | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 623       | 36.8%   |
| 2       | 529       | 31.25%  |
| 6       | 219       | 12.94%  |
| 8       | 185       | 10.93%  |
| 12      | 39        | 2.3%    |
| 1       | 24        | 1.42%   |
| 16      | 23        | 1.36%   |
| 3       | 14        | 0.83%   |
| 10      | 11        | 0.65%   |
| 24      | 5         | 0.3%    |
| 32      | 4         | 0.24%   |
| 14      | 4         | 0.24%   |
| Unknown | 4         | 0.24%   |
| 40      | 3         | 0.18%   |
| 20      | 2         | 0.12%   |
| 64      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 44      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1655      | 97.93%  |
| 2       | 28        | 1.66%   |
| 4       | 4         | 0.24%   |
| Unknown | 3         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1267      | 74.84%  |
| 1       | 421       | 24.87%  |
| Unknown | 4         | 0.24%   |
| 8       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1631      | 96.22%  |
| Unknown        | 55        | 3.24%   |
| 32-bit         | 7         | 0.41%   |
| 64-bit         | 2         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 9.63%   |
| 0x306c3    | 97        | 5.63%   |
| 0x306a9    | 89        | 5.16%   |
| 0x206a7    | 89        | 5.16%   |
| 0x806c1    | 56        | 3.25%   |
| 0x906ea    | 55        | 3.19%   |
| 0x506e3    | 55        | 3.19%   |
| 0x406e3    | 47        | 2.73%   |
| 0x806ec    | 45        | 2.61%   |
| 0x08701021 | 44        | 2.55%   |
| 0x906e9    | 40        | 2.32%   |
| 0x806ea    | 40        | 2.32%   |
| 0x0800820d | 38        | 2.2%    |
| 0x806e9    | 37        | 2.15%   |
| 0x0a50000c | 36        | 2.09%   |
| 0x1067a    | 35        | 2.03%   |
| 0x40651    | 34        | 1.97%   |
| 0x306d4    | 31        | 1.8%    |
| 0x06000852 | 30        | 1.74%   |
| 0x08600106 | 29        | 1.68%   |
| 0x08108109 | 29        | 1.68%   |
| 0x20655    | 21        | 1.22%   |
| 0x010000c8 | 21        | 1.22%   |
| 0x08001138 | 19        | 1.1%    |
| 0x08701013 | 17        | 0.99%   |
| 0x08600104 | 17        | 0.99%   |
| 0x0a201009 | 16        | 0.93%   |
| 0x08108102 | 16        | 0.93%   |
| 0x06001119 | 16        | 0.93%   |
| 0x08608103 | 15        | 0.87%   |
| 0x806eb    | 14        | 0.81%   |
| 0x706e5    | 12        | 0.7%    |
| 0x706a8    | 12        | 0.7%    |
| 0x706a1    | 12        | 0.7%    |
| 0x0810100b | 12        | 0.7%    |
| 0x08001137 | 12        | 0.7%    |
| 0x906ed    | 11        | 0.64%   |
| 0x6fd      | 11        | 0.64%   |
| 0x306f2    | 11        | 0.64%   |
| 0x06006705 | 11        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 274       | 16.19%  |
| Haswell          | 161       | 9.52%   |
| Zen 2            | 126       | 7.45%   |
| Skylake          | 117       | 6.91%   |
| IvyBridge        | 107       | 6.32%   |
| SandyBridge      | 97        | 5.73%   |
| Zen+             | 92        | 5.44%   |
| Zen 3            | 82        | 4.85%   |
| Zen              | 65        | 3.84%   |
| TigerLake        | 56        | 3.31%   |
| Penryn           | 55        | 3.25%   |
| Piledriver       | 50        | 2.96%   |
| K10              | 42        | 2.48%   |
| Broadwell        | 36        | 2.13%   |
| Unknown          | 36        | 2.13%   |
| Westmere         | 35        | 2.07%   |
| Icelake          | 32        | 1.89%   |
| CometLake        | 30        | 1.77%   |
| Core             | 29        | 1.71%   |
| Goldmont plus    | 24        | 1.42%   |
| Alderlake Hybrid | 23        | 1.36%   |
| Nehalem          | 20        | 1.18%   |
| Excavator        | 19        | 1.12%   |
| Silvermont       | 11        | 0.65%   |
| Steamroller      | 9         | 0.53%   |
| Bulldozer        | 9         | 0.53%   |
| Bobcat           | 8         | 0.47%   |
| Puma             | 7         | 0.41%   |
| Jaguar           | 7         | 0.41%   |
| Bonnell          | 7         | 0.41%   |
| K8 Hammer        | 6         | 0.35%   |
| K10 Llano        | 6         | 0.35%   |
| Goldmont         | 5         | 0.3%    |
| P6               | 3         | 0.18%   |
| K8 & K10 hybrid  | 3         | 0.18%   |
| NetBurst         | 2         | 0.12%   |
| Tremont          | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 840       | 42.23%  |
| AMD                        | 570       | 28.66%  |
| Nvidia                     | 558       | 28.05%  |
| Matrox Electronics Systems | 14        | 0.7%    |
| ASPEED Technology          | 4         | 0.2%    |
| S3 Graphics                | 2         | 0.1%    |
| VIA Technologies           | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 64        | 3.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 60        | 2.92%   |
| AMD Renoir                                                                  | 59        | 2.87%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 56        | 2.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 53        | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 49        | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 47        | 2.29%   |
| Intel UHD Graphics 620                                                      | 42        | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 42        | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 41        | 1.99%   |
| Intel HD Graphics 620                                                       | 40        | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 39        | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 39        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 35        | 1.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 35        | 1.7%    |
| Intel HD Graphics 530                                                       | 34        | 1.65%   |
| Intel HD Graphics 630                                                       | 32        | 1.56%   |
| Intel HD Graphics 5500                                                      | 25        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 23        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22        | 1.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 22        | 1.07%   |
| Intel Core Processor Integrated Graphics Controller                         | 21        | 1.02%   |
| AMD Lucienne                                                                | 20        | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 16        | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 16        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 15        | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 15        | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                              | 14        | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 14        | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13        | 0.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 13        | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 13        | 0.63%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 13        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 12        | 0.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 11        | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 10        | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 10        | 0.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 10        | 0.49%   |
| Nvidia GK208B [GeForce GT 730]                                              | 10        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 573       | 33.79%  |
| 1 x AMD            | 465       | 27.42%  |
| 1 x Nvidia         | 304       | 17.92%  |
| Intel + Nvidia     | 208       | 12.26%  |
| Intel + AMD        | 37        | 2.18%   |
| 2 x AMD            | 34        | 2%      |
| AMD + Nvidia       | 34        | 2%      |
| 1 x Matrox         | 11        | 0.65%   |
| Other              | 8         | 0.47%   |
| 2 x Nvidia         | 7         | 0.41%   |
| 2 x Intel          | 4         | 0.24%   |
| Nvidia + ASPEED    | 3         | 0.18%   |
| 1 x S3 Graphics    | 2         | 0.12%   |
| Nvidia + Matrox    | 2         | 0.12%   |
| 1 x VIA            | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |
| 1 x ASPEED         | 1         | 0.06%   |
| AMD + Matrox       | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1358      | 79.42%  |
| Proprietary | 318       | 18.6%   |
| Unknown     | 34        | 1.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 797       | 46.18%  |
| 1.01-2.0   | 218       | 12.63%  |
| 0.01-0.5   | 211       | 12.22%  |
| 3.01-4.0   | 145       | 8.4%    |
| 0.51-1.0   | 127       | 7.36%   |
| 7.01-8.0   | 123       | 7.13%   |
| 5.01-6.0   | 48        | 2.78%   |
| 8.01-16.0  | 36        | 2.09%   |
| 2.01-3.0   | 14        | 0.81%   |
| 16.01-24.0 | 6         | 0.35%   |
| 4.01-5.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 240       | 12.18%  |
| AU Optronics            | 212       | 10.76%  |
| LG Display              | 153       | 7.76%   |
| Chimei Innolux          | 151       | 7.66%   |
| Dell                    | 149       | 7.56%   |
| BOE                     | 148       | 7.51%   |
| Goldstar                | 123       | 6.24%   |
| Hewlett-Packard         | 82        | 4.16%   |
| Acer                    | 69        | 3.5%    |
| Ancor Communications    | 66        | 3.35%   |
| BenQ                    | 62        | 3.15%   |
| AOC                     | 50        | 2.54%   |
| Philips                 | 41        | 2.08%   |
| Lenovo                  | 41        | 2.08%   |
| Sharp                   | 35        | 1.78%   |
| Apple                   | 31        | 1.57%   |
| Iiyama                  | 20        | 1.01%   |
| ASUSTek Computer        | 20        | 1.01%   |
| InfoVision              | 19        | 0.96%   |
| ViewSonic               | 18        | 0.91%   |
| PANDA                   | 17        | 0.86%   |
| Fujitsu Siemens         | 15        | 0.76%   |
| Chi Mei Optoelectronics | 14        | 0.71%   |
| Unknown                 | 13        | 0.66%   |
| LG Electronics          | 11        | 0.56%   |
| Eizo                    | 11        | 0.56%   |
| Vizio                   | 8         | 0.41%   |
| Sony                    | 8         | 0.41%   |
| Sceptre Tech            | 7         | 0.36%   |
| NEC Computers           | 7         | 0.36%   |
| LG Philips              | 7         | 0.36%   |
| Panasonic               | 6         | 0.3%    |
| Pixio                   | 5         | 0.25%   |
| MSI                     | 5         | 0.25%   |
| CSO                     | 5         | 0.25%   |
| Toshiba                 | 4         | 0.2%    |
| TMX                     | 4         | 0.2%    |
| Medion                  | 4         | 0.2%    |
| HannStar                | 4         | 0.2%    |
| CPT                     | 4         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 10        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 9         | 0.43%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                  | 9         | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 9         | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.39%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 7         | 0.34%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 7         | 0.34%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 7         | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 6         | 0.29%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 6         | 0.29%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 6         | 0.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6         | 0.29%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 380x300mm 19.1-inch          | 6         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 6         | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 6         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 6         | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 5         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 5         | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch              | 5         | 0.24%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 5         | 0.24%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                     | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 5         | 0.24%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch       | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 5         | 0.24%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 4         | 0.19%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 4         | 0.19%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch    | 4         | 0.19%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 4         | 0.19%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                     | 4         | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 4         | 0.19%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 4         | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 4         | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 0.19%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch         | 4         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 918       | 48.57%  |
| 1366x768 (WXGA)    | 222       | 11.75%  |
| 2560x1440 (QHD)    | 136       | 7.2%    |
| 3840x2160 (4K)     | 118       | 6.24%   |
| 1600x900 (HD+)     | 68        | 3.6%    |
| 1920x1200 (WUXGA)  | 54        | 2.86%   |
| 1680x1050 (WSXGA+) | 53        | 2.8%    |
| 1280x1024 (SXGA)   | 51        | 2.7%    |
| 1440x900 (WXGA+)   | 35        | 1.85%   |
| 1280x800 (WXGA)    | 33        | 1.75%   |
| 2560x1080          | 30        | 1.59%   |
| Unknown            | 25        | 1.32%   |
| 3440x1440          | 24        | 1.27%   |
| 3840x1080          | 15        | 0.79%   |
| 1024x768 (XGA)     | 14        | 0.74%   |
| 2560x1600          | 11        | 0.58%   |
| 2880x1800          | 8         | 0.42%   |
| 1360x768           | 7         | 0.37%   |
| 3200x1800 (QHD+)   | 6         | 0.32%   |
| 2160x1440          | 5         | 0.26%   |
| 1920x540           | 5         | 0.26%   |
| 3840x1200          | 4         | 0.21%   |
| 1024x600           | 4         | 0.21%   |
| 3840x2400          | 3         | 0.16%   |
| 1600x1200          | 3         | 0.16%   |
| 1280x720 (HD)      | 3         | 0.16%   |
| 3840x1600          | 2         | 0.11%   |
| 3456x2160          | 2         | 0.11%   |
| 2048x1536          | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 1280x960           | 2         | 0.11%   |
| 8960x2160          | 1         | 0.05%   |
| 800x1280           | 1         | 0.05%   |
| 7680x1440          | 1         | 0.05%   |
| 7280x2160          | 1         | 0.05%   |
| 6520x1440          | 1         | 0.05%   |
| 640x480            | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5520x1080          | 1         | 0.05%   |
| 4480x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 448       | 22.71%  |
| 27      | 211       | 10.69%  |
| 24      | 162       | 8.21%   |
| 14      | 158       | 8.01%   |
| 13      | 146       | 7.4%    |
| 21      | 133       | 6.74%   |
| 23      | 119       | 6.03%   |
| 17      | 102       | 5.17%   |
| Unknown | 77        | 3.9%    |
| 19      | 50        | 2.53%   |
| 31      | 48        | 2.43%   |
| 12      | 42        | 2.13%   |
| 34      | 39        | 1.98%   |
| 22      | 35        | 1.77%   |
| 18      | 31        | 1.57%   |
| 20      | 23        | 1.17%   |
| 32      | 19        | 0.96%   |
| 11      | 13        | 0.66%   |
| 84      | 12        | 0.61%   |
| 26      | 12        | 0.61%   |
| 25      | 12        | 0.61%   |
| 72      | 9         | 0.46%   |
| 29      | 9         | 0.46%   |
| 16      | 9         | 0.46%   |
| 54      | 8         | 0.41%   |
| 40      | 6         | 0.3%    |
| 37      | 4         | 0.2%    |
| 28      | 4         | 0.2%    |
| 10      | 4         | 0.2%    |
| 74      | 3         | 0.15%   |
| 52      | 3         | 0.15%   |
| 49      | 3         | 0.15%   |
| 42      | 3         | 0.15%   |
| 60      | 2         | 0.1%    |
| 48      | 2         | 0.1%    |
| 35      | 2         | 0.1%    |
| 33      | 2         | 0.1%    |
| 142     | 1         | 0.05%   |
| 69      | 1         | 0.05%   |
| 47      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 674       | 34.9%   |
| 501-600        | 459       | 23.77%  |
| 401-500        | 237       | 12.27%  |
| 201-300        | 138       | 7.15%   |
| 351-400        | 135       | 6.99%   |
| 601-700        | 87        | 4.51%   |
| Unknown        | 77        | 3.99%   |
| 701-800        | 59        | 3.06%   |
| 1501-2000      | 25        | 1.29%   |
| 1001-1500      | 21        | 1.09%   |
| 801-900        | 13        | 0.67%   |
| 901-1000       | 3         | 0.16%   |
| 101-200        | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1339      | 76.34%  |
| 16/10   | 200       | 11.4%   |
| Unknown | 63        | 3.59%   |
| 21/9    | 45        | 2.57%   |
| 5/4     | 42        | 2.39%   |
| 4/3     | 31        | 1.77%   |
| 3/2     | 17        | 0.97%   |
| 6/5     | 6         | 0.34%   |
| 32/9    | 4         | 0.23%   |
| 2.65    | 4         | 0.23%   |
| 3.20    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 449       | 22.99%  |
| 201-250        | 348       | 17.82%  |
| 81-90          | 241       | 12.34%  |
| 301-350        | 217       | 11.11%  |
| 351-500        | 116       | 5.94%   |
| 151-200        | 113       | 5.79%   |
| 251-300        | 77        | 3.94%   |
| 121-130        | 77        | 3.94%   |
| Unknown        | 77        | 3.94%   |
| 71-80          | 66        | 3.38%   |
| More than 1000 | 42        | 2.15%   |
| 61-70          | 37        | 1.89%   |
| 141-150        | 36        | 1.84%   |
| 501-1000       | 18        | 0.92%   |
| 51-60          | 13        | 0.67%   |
| 131-140        | 11        | 0.56%   |
| 41-50          | 5         | 0.26%   |
| 91-100         | 5         | 0.26%   |
| 111-120        | 4         | 0.2%    |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 646       | 34.18%  |
| 121-160       | 524       | 27.72%  |
| 101-120       | 445       | 23.54%  |
| 161-240       | 121       | 6.4%    |
| Unknown       | 77        | 4.07%   |
| More than 240 | 46        | 2.43%   |
| 1-50          | 31        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1300      | 75.1%   |
| 2     | 344       | 19.87%  |
| 0     | 47        | 2.72%   |
| 3     | 37        | 2.14%   |
| 4     | 3         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 930       | 36.7%   |
| Intel                                  | 893       | 35.24%  |
| Qualcomm Atheros                       | 223       | 8.8%    |
| Broadcom                               | 132       | 5.21%   |
| MediaTek                               | 39        | 1.54%   |
| Ralink Technology                      | 27        | 1.07%   |
| TP-Link                                | 24        | 0.95%   |
| Broadcom Limited                       | 24        | 0.95%   |
| Ralink                                 | 21        | 0.83%   |
| ASIX Electronics                       | 20        | 0.79%   |
| Nvidia                                 | 19        | 0.75%   |
| Marvell Technology Group               | 18        | 0.71%   |
| Sierra Wireless                        | 10        | 0.39%   |
| NetGear                                | 8         | 0.32%   |
| Lenovo                                 | 8         | 0.32%   |
| DisplayLink                            | 8         | 0.32%   |
| Samsung Electronics                    | 7         | 0.28%   |
| Dell                                   | 7         | 0.28%   |
| Edimax Technology                      | 6         | 0.24%   |
| D-Link                                 | 6         | 0.24%   |
| Aquantia                               | 6         | 0.24%   |
| Microsoft                              | 5         | 0.2%    |
| Hewlett-Packard                        | 5         | 0.2%    |
| Ericsson Business Mobile Networks      | 5         | 0.2%    |
| Qualcomm Atheros Communications        | 4         | 0.16%   |
| D-Link System                          | 4         | 0.16%   |
| Cypress Semiconductor                  | 4         | 0.16%   |
| Motorola PCS                           | 3         | 0.12%   |
| Microchip Technology                   | 3         | 0.12%   |
| Linksys                                | 3         | 0.12%   |
| ICS Advent                             | 3         | 0.12%   |
| Huawei Technologies                    | 3         | 0.12%   |
| AVM                                    | 3         | 0.12%   |
| ASUSTek Computer                       | 3         | 0.12%   |
| Xiaomi                                 | 2         | 0.08%   |
| VIA Technologies                       | 2         | 0.08%   |
| Texas Instruments                      | 2         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.08%   |
| NetXen Incorporated                    | 2         | 0.08%   |
| Mellanox Technologies                  | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 680       | 22.48%  |
| Intel Wi-Fi 6 AX200                                               | 122       | 4.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 70        | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 65        | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 57        | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 57        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 48        | 1.59%   |
| Intel Wireless 8260                                               | 46        | 1.52%   |
| Intel Wireless 7260                                               | 44        | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 43        | 1.42%   |
| Intel Wi-Fi 6 AX201                                               | 43        | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 35        | 1.16%   |
| Intel Wireless-AC 9260                                            | 35        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 33        | 1.09%   |
| Intel Wireless 7265                                               | 32        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27        | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 24        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 22        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 21        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 20        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 17        | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.53%   |
| Intel Wireless 3160                                               | 15        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 668       | 51.07%  |
| Realtek Semiconductor           | 205       | 15.67%  |
| Qualcomm Atheros                | 171       | 13.07%  |
| Broadcom                        | 86        | 6.57%   |
| MediaTek                        | 34        | 2.6%    |
| Ralink Technology               | 27        | 2.06%   |
| Ralink                          | 21        | 1.61%   |
| TP-Link                         | 16        | 1.22%   |
| Broadcom Limited                | 15        | 1.15%   |
| Sierra Wireless                 | 10        | 0.76%   |
| NetGear                         | 8         | 0.61%   |
| Edimax Technology               | 6         | 0.46%   |
| D-Link                          | 6         | 0.46%   |
| Qualcomm Atheros Communications | 4         | 0.31%   |
| Microsoft                       | 4         | 0.31%   |
| Dell                            | 4         | 0.31%   |
| Linksys                         | 3         | 0.23%   |
| AVM                             | 3         | 0.23%   |
| ASUSTek Computer                | 3         | 0.23%   |
| Marvell Technology Group        | 2         | 0.15%   |
| D-Link System                   | 2         | 0.15%   |
| Belkin Components               | 2         | 0.15%   |
| ZyXEL Communications            | 1         | 0.08%   |
| Xiaomi                          | 1         | 0.08%   |
| Realtek                         | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Intersil                        | 1         | 0.08%   |
| IMC Networks                    | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| BUFFALO                         | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 122       | 9.24%   |
| Intel Wireless 8265 / 8275                                     | 57        | 4.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 48        | 3.64%   |
| Intel Wireless 8260                                            | 46        | 3.48%   |
| Intel Wireless 7260                                            | 44        | 3.33%   |
| Intel Wi-Fi 6 AX201                                            | 43        | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.65%   |
| Intel Wireless-AC 9260                                         | 35        | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 34        | 2.58%   |
| Intel Wireless 7265                                            | 32        | 2.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 27        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 24        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 21        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 20        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 1.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.29%   |
| Intel Wireless 3160                                            | 15        | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.06%   |
| Intel Centrino Ultimate-N 6300                                 | 14        | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 13        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 0.98%   |
| Intel Wireless 3165                                            | 12        | 0.91%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                | 11        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 9         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 852       | 52.14%  |
| Intel                                  | 501       | 30.66%  |
| Qualcomm Atheros                       | 69        | 4.22%   |
| Broadcom                               | 64        | 3.92%   |
| ASIX Electronics                       | 20        | 1.22%   |
| Nvidia                                 | 19        | 1.16%   |
| Marvell Technology Group               | 16        | 0.98%   |
| Broadcom Limited                       | 9         | 0.55%   |
| TP-Link                                | 8         | 0.49%   |
| Lenovo                                 | 8         | 0.49%   |
| DisplayLink                            | 8         | 0.49%   |
| Samsung Electronics                    | 7         | 0.43%   |
| Aquantia                               | 6         | 0.37%   |
| MediaTek                               | 5         | 0.31%   |
| Cypress Semiconductor                  | 4         | 0.24%   |
| Motorola PCS                           | 3         | 0.18%   |
| ICS Advent                             | 3         | 0.18%   |
| Huawei Technologies                    | 3         | 0.18%   |
| VIA Technologies                       | 2         | 0.12%   |
| NetXen Incorporated                    | 2         | 0.12%   |
| JMicron Technology                     | 2         | 0.12%   |
| HMD Global                             | 2         | 0.12%   |
| Dell                                   | 2         | 0.12%   |
| D-Link System                          | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.06%   |
| Xiaomi                                 | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Solarflare Communications              | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| MosChip Semiconductor                  | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Microchip Technology                   | 1         | 0.06%   |
| IBM                                    | 1         | 0.06%   |
| Hewlett-Packard                        | 1         | 0.06%   |
| Google                                 | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| Emulex                                 | 1         | 0.06%   |
| Chelsio Communications                 | 1         | 0.06%   |
| ADMtek                                 | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 680       | 40.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 70        | 4.18%   |
| Intel I211 Gigabit Network Connection                             | 65        | 3.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 57        | 3.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 43        | 2.57%   |
| Intel Ethernet Connection (2) I219-V                              | 33        | 1.97%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 1.31%   |
| Intel Ethernet Connection I217-V                                  | 19        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.08%   |
| Intel I210 Gigabit Network Connection                             | 17        | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 17        | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 13        | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 8         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.42%   |
| Intel Ethernet Connection (11) I219-V                             | 7         | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.36%   |
| Intel Ethernet Connection (2) I218-LM                             | 6         | 0.36%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.36%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 6         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1487      | 53.9%   |
| WiFi     | 1243      | 45.05%  |
| Modem    | 19        | 0.69%   |
| Unknown  | 10        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 921       | 50.88%  |
| Ethernet | 888       | 49.06%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 920       | 54.31%  |
| 1     | 670       | 39.55%  |
| 3     | 63        | 3.72%   |
| 0     | 19        | 1.12%   |
| 4     | 16        | 0.94%   |
| 5     | 4         | 0.24%   |
| 8     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1421      | 82.28%  |
| Yes  | 306       | 17.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 544       | 50.75%  |
| Realtek Semiconductor           | 100       | 9.33%   |
| Cambridge Silicon Radio         | 83        | 7.74%   |
| Qualcomm Atheros Communications | 71        | 6.62%   |
| Broadcom                        | 49        | 4.57%   |
| Lite-On Technology              | 40        | 3.73%   |
| IMC Networks                    | 38        | 3.54%   |
| Apple                           | 38        | 3.54%   |
| Foxconn / Hon Hai               | 27        | 2.52%   |
| ASUSTek Computer                | 19        | 1.77%   |
| Hewlett-Packard                 | 9         | 0.84%   |
| Dell                            | 9         | 0.84%   |
| Realtek                         | 8         | 0.75%   |
| MediaTek                        | 6         | 0.56%   |
| Toshiba                         | 5         | 0.47%   |
| Unknown                         | 3         | 0.28%   |
| Belkin Components               | 3         | 0.28%   |
| TP-Link                         | 2         | 0.19%   |
| Taiyo Yuden                     | 2         | 0.19%   |
| Ralink                          | 2         | 0.19%   |
| Marvell Semiconductor           | 2         | 0.19%   |
| HTC (High Tech Computer)        | 2         | 0.19%   |
| Foxconn International           | 2         | 0.19%   |
| USI                             | 1         | 0.09%   |
| SIN                             | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| Mobile Action Technology        | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 184       | 17.12%  |
| Intel AX200 Bluetooth                                                               | 115       | 10.7%   |
| Intel Bluetooth Device                                                              | 93        | 8.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 83        | 7.72%   |
| Realtek Bluetooth Radio                                                             | 62        | 5.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 58        | 5.4%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 36        | 3.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 34        | 3.16%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 27        | 2.51%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 25        | 2.33%   |
| Lite-On Bluetooth Device                                                            | 20        | 1.86%   |
| Apple Bluetooth Host Controller                                                     | 19        | 1.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 17        | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 1.58%   |
| Intel AX210 Bluetooth                                                               | 17        | 1.58%   |
| IMC Networks Bluetooth Radio                                                        | 14        | 1.3%    |
| IMC Networks Wireless_Device                                                        | 11        | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.02%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 0.93%   |
| IMC Networks Bluetooth Device                                                       | 9         | 0.84%   |
| Realtek Bluetooth Radio                                                             | 8         | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 8         | 0.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 8         | 0.74%   |
| Lite-On Wireless_Device                                                             | 7         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.56%   |
| MediaTek Wireless_Device                                                            | 6         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.47%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 0.47%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 5         | 0.47%   |
| ASUS ASUS USB-BT500                                                                 | 5         | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 5         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.37%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 0.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.37%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.37%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 4         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 1072      | 44.8%   |
| AMD                         | 628       | 26.24%  |
| Nvidia                      | 359       | 15%     |
| C-Media Electronics         | 45        | 1.88%   |
| Logitech                    | 25        | 1.04%   |
| Creative Labs               | 25        | 1.04%   |
| Texas Instruments           | 18        | 0.75%   |
| Realtek Semiconductor       | 14        | 0.59%   |
| Creative Technology         | 11        | 0.46%   |
| Kingston Technology         | 10        | 0.42%   |
| JMTek                       | 10        | 0.42%   |
| Generalplus Technology      | 9         | 0.38%   |
| Razer USA                   | 8         | 0.33%   |
| Lenovo                      | 8         | 0.33%   |
| GN Netcom                   | 8         | 0.33%   |
| M-Audio                     | 7         | 0.29%   |
| Sennheiser Communications   | 6         | 0.25%   |
| Plantronics                 | 6         | 0.25%   |
| Focusrite-Novation          | 6         | 0.25%   |
| Corsair                     | 6         | 0.25%   |
| ASUSTek Computer            | 6         | 0.25%   |
| Yamaha                      | 5         | 0.21%   |
| SteelSeries ApS             | 5         | 0.21%   |
| RODE Microphones            | 5         | 0.21%   |
| Hewlett-Packard             | 5         | 0.21%   |
| BEHRINGER International     | 5         | 0.21%   |
| Samson Technologies         | 4         | 0.17%   |
| FiiO Electronics Technology | 4         | 0.17%   |
| VIA Technologies            | 3         | 0.13%   |
| SAVITECH                    | 3         | 0.13%   |
| Dell                        | 3         | 0.13%   |
| Apple                       | 3         | 0.13%   |
| ZOOM                        | 2         | 0.08%   |
| Microsoft                   | 2         | 0.08%   |
| Huawei Technologies         | 2         | 0.08%   |
| Fry's Electronics           | 2         | 0.08%   |
| ESS Technology              | 2         | 0.08%   |
| Conexant Systems            | 2         | 0.08%   |
| Blue Microphones            | 2         | 0.08%   |
| BlackWeb                    | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 198       | 6.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 137       | 4.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 116       | 3.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 100       | 3.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 95        | 3.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 92        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 86        | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 81        | 2.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 79        | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 69        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 65        | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 65        | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 61        | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 61        | 2.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 56        | 1.89%   |
| AMD FCH Azalia Controller                                                  | 45        | 1.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 40        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 39        | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                      | 38        | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 33        | 1.12%   |
| Intel Broadwell-U Audio Controller                                         | 32        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 31        | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 31        | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 30        | 1.01%   |
| AMD Navi 10 HDMI Audio                                                     | 30        | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 26        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 25        | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 25        | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 24        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 23        | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 23        | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 22        | 0.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 21        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 20        | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 19        | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 0.64%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 305       | 22.36%  |
| SK hynix                                | 216       | 15.84%  |
| Kingston                                | 172       | 12.61%  |
| Micron Technology                       | 140       | 10.26%  |
| Unknown                                 | 111       | 8.14%   |
| Crucial                                 | 93        | 6.82%   |
| Corsair                                 | 85        | 6.23%   |
| G.Skill                                 | 73        | 5.35%   |
| A-DATA Technology                       | 19        | 1.39%   |
| Ramaxel Technology                      | 18        | 1.32%   |
| Elpida                                  | 16        | 1.17%   |
| Patriot                                 | 15        | 1.1%    |
| Unknown (ABCD)                          | 11        | 0.81%   |
| Team                                    | 10        | 0.73%   |
| Nanya Technology                        | 10        | 0.73%   |
| Smart                                   | 9         | 0.66%   |
| Transcend                               | 6         | 0.44%   |
| Avant                                   | 6         | 0.44%   |
| Unknown                                 | 5         | 0.37%   |
| GOODRAM                                 | 4         | 0.29%   |
| AMD                                     | 4         | 0.29%   |
| Teikon                                  | 2         | 0.15%   |
| Lexar                                   | 2         | 0.15%   |
| Exceleram                               | 2         | 0.15%   |
| ChangXin Memory                         | 2         | 0.15%   |
| ASint Technology                        | 2         | 0.15%   |
| Unknown (0x02BA)                        | 1         | 0.07%   |
| Unknown (07FB)                          | 1         | 0.07%   |
| Unknown (000004B30000)                  | 1         | 0.07%   |
| Unifosa                                 | 1         | 0.07%   |
| Toshiba                                 | 1         | 0.07%   |
| TakeMS                                  | 1         | 0.07%   |
| Super Talent                            | 1         | 0.07%   |
| Smart Modular                           | 1         | 0.07%   |
| Smart Brazil                            | 1         | 0.07%   |
| Silicon Power Computer & Communications | 1         | 0.07%   |
| Silicon Power                           | 1         | 0.07%   |
| SanDisk                                 | 1         | 0.07%   |
| Qimonda                                 | 1         | 0.07%   |
| Princeton                               | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 16        | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1.03%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 9         | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.48%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 7         | 0.48%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 7         | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.41%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.41%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 6         | 0.41%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 6         | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 5         | 0.34%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.34%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.34%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 607       | 52.24%  |
| DDR3    | 361       | 31.07%  |
| LPDDR4  | 44        | 3.79%   |
| DDR2    | 41        | 3.53%   |
| Unknown | 37        | 3.18%   |
| LPDDR3  | 31        | 2.67%   |
| SDRAM   | 20        | 1.72%   |
| LPDDR5  | 8         | 0.69%   |
| DDR     | 7         | 0.6%    |
| DDR5    | 4         | 0.34%   |
| DRAM    | 2         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 616       | 52.83%  |
| DIMM         | 456       | 39.11%  |
| Row Of Chips | 79        | 6.78%   |
| Chip         | 11        | 0.94%   |
| RIMM         | 2         | 0.17%   |
| FB-DIMM      | 2         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 521       | 40.99%  |
| 4096  | 351       | 27.62%  |
| 16384 | 198       | 15.58%  |
| 2048  | 119       | 9.36%   |
| 32768 | 46        | 3.62%   |
| 1024  | 33        | 2.6%    |
| 512   | 2         | 0.16%   |
| 128   | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 237       | 18.71%  |
| 3200    | 193       | 15.23%  |
| 2667    | 191       | 15.07%  |
| 2400    | 97        | 7.66%   |
| 1333    | 93        | 7.34%   |
| 2133    | 83        | 6.55%   |
| 3600    | 43        | 3.39%   |
| 1334    | 36        | 2.84%   |
| 1867    | 25        | 1.97%   |
| 800     | 24        | 1.89%   |
| 667     | 22        | 1.74%   |
| 4267    | 17        | 1.34%   |
| 3266    | 16        | 1.26%   |
| 3466    | 13        | 1.03%   |
| Unknown | 13        | 1.03%   |
| 3400    | 12        | 0.95%   |
| 1067    | 12        | 0.95%   |
| 1066    | 12        | 0.95%   |
| 3800    | 10        | 0.79%   |
| 2666    | 10        | 0.79%   |
| 1866    | 8         | 0.63%   |
| 8400    | 7         | 0.55%   |
| 6400    | 7         | 0.55%   |
| 4266    | 7         | 0.55%   |
| 3000    | 7         | 0.55%   |
| 2933    | 7         | 0.55%   |
| 2800    | 6         | 0.47%   |
| 2048    | 6         | 0.47%   |
| 975     | 5         | 0.39%   |
| 4199    | 4         | 0.32%   |
| 3866    | 4         | 0.32%   |
| 3733    | 4         | 0.32%   |
| 3666    | 4         | 0.32%   |
| 533     | 4         | 0.32%   |
| 4800    | 3         | 0.24%   |
| 333     | 3         | 0.24%   |
| 3334    | 2         | 0.16%   |
| 3151    | 2         | 0.16%   |
| 3007    | 2         | 0.16%   |
| 1800    | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 43.4%   |
| Samsung Electronics | 8         | 15.09%  |
| Brother Industries  | 7         | 13.21%  |
| Seiko Epson         | 6         | 11.32%  |
| Canon               | 5         | 9.43%   |
| Prolific Technology | 2         | 3.77%   |
| Pantum              | 1         | 1.89%   |
| Kyocera             | 1         | 1.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                      | 2         | 3.7%    |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 3.7%    |
| Prolific PL2305 Parallel Port                   | 2         | 3.7%    |
| HP Officejet 4500 G510g-m                       | 2         | 3.7%    |
| HP Color LaserJet CP1215                        | 2         | 3.7%    |
| Seiko Epson XP-243 245 247 Series               | 1         | 1.85%   |
| Seiko Epson XP-230 Series                       | 1         | 1.85%   |
| Seiko Epson L3160 Series                        | 1         | 1.85%   |
| Seiko Epson L1300 Series                        | 1         | 1.85%   |
| Seiko Epson ET-3840 Series                      | 1         | 1.85%   |
| Samsung SCX-4200 series                         | 1         | 1.85%   |
| Samsung SCX-3400 Series                         | 1         | 1.85%   |
| Samsung ML-191x/ML-252x Laser Printer           | 1         | 1.85%   |
| Samsung ML-1865                                 | 1         | 1.85%   |
| Samsung M267x 287x Series                       | 1         | 1.85%   |
| Samsung M2020 Series                            | 1         | 1.85%   |
| Pantum P2500W-series                            | 1         | 1.85%   |
| Kyocera FS-1030D printer                        | 1         | 1.85%   |
| HP Smart Tank Plus 550 series                   | 1         | 1.85%   |
| HP Smart Install                                | 1         | 1.85%   |
| HP OfficeJet 5200 series                        | 1         | 1.85%   |
| HP Officejet 4620 series                        | 1         | 1.85%   |
| HP LaserJet Professional P 1102w                | 1         | 1.85%   |
| HP LaserJet P1102                               | 1         | 1.85%   |
| HP LaserJet CM1415fn                            | 1         | 1.85%   |
| HP LaserJet 1320                                | 1         | 1.85%   |
| HP LaserJet 1020                                | 1         | 1.85%   |
| HP LaserJet 1018                                | 1         | 1.85%   |
| HP ENVY 4520 series                             | 1         | 1.85%   |
| HP ENVY 4500 series                             | 1         | 1.85%   |
| HP Deskjet Ink Advant K209a-z                   | 1         | 1.85%   |
| HP DeskJet 6940 series                          | 1         | 1.85%   |
| HP DeskJet 5940                                 | 1         | 1.85%   |
| HP DeskJet 3830 series                          | 1         | 1.85%   |
| HP DeskJet 3630 series                          | 1         | 1.85%   |
| HP DeskJet 2700 series                          | 1         | 1.85%   |
| HP DeskJet 2600 series                          | 1         | 1.85%   |
| Canon TR8500 series                             | 1         | 1.85%   |
| Canon TR7500 series                             | 1         | 1.85%   |
| Canon LiDE 400                                  | 1         | 1.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 46.67%  |
| Seiko Epson     | 3         | 20%     |
| Hewlett-Packard | 2         | 13.33%  |
| AGFA-Gevaert NV | 2         | 13.33%  |
| Mustek Systems  | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                             | 3         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20                  | 2         | 13.33%  |
| Seiko Epson Scanner                                 | 1         | 6.67%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1         | 6.67%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 6.67%   |
| Mustek Systems ScanExpress A3 USB                   | 1         | 6.67%   |
| HP ScanJet 5300c/5370c                              | 1         | 6.67%   |
| HP ScanJet 3970c                                    | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                       | 1         | 6.67%   |
| Canon CanoScan LiDE 110                             | 1         | 6.67%   |
| AGFA-Gevaert NV SnapScan e20                        | 1         | 6.67%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                  | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 235       | 23.48%  |
| IMC Networks                           | 99        | 9.89%   |
| Microdia                               | 89        | 8.89%   |
| Logitech                               | 87        | 8.69%   |
| Acer                                   | 76        | 7.59%   |
| Realtek Semiconductor                  | 73        | 7.29%   |
| Sunplus Innovation Technology          | 54        | 5.39%   |
| Quanta                                 | 52        | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 3.3%    |
| Apple                                  | 27        | 2.7%    |
| Lite-On Technology                     | 23        | 2.3%    |
| Luxvisions Innotech Limited            | 20        | 2%      |
| Syntek                                 | 19        | 1.9%    |
| Suyin                                  | 17        | 1.7%    |
| Microsoft                              | 10        | 1%      |
| Silicon Motion                         | 9         | 0.9%    |
| Lenovo                                 | 6         | 0.6%    |
| Samsung Electronics                    | 5         | 0.5%    |
| Alcor Micro                            | 5         | 0.5%    |
| Ricoh                                  | 4         | 0.4%    |
| Generalplus Technology                 | 4         | 0.4%    |
| Z-Star Microelectronics                | 3         | 0.3%    |
| SunplusIT                              | 3         | 0.3%    |
| Sonix Technology                       | 3         | 0.3%    |
| Primax Electronics                     | 3         | 0.3%    |
| Hewlett-Packard                        | 3         | 0.3%    |
| Y Media                                | 2         | 0.2%    |
| Unknown                                | 2         | 0.2%    |
| Trust                                  | 2         | 0.2%    |
| Tobii Technology AB                    | 2         | 0.2%    |
| LG Electronics                         | 2         | 0.2%    |
| Cubeternet                             | 2         | 0.2%    |
| Creative Technology                    | 2         | 0.2%    |
| Arkmicro Technologies                  | 2         | 0.2%    |
| ARC International                      | 2         | 0.2%    |
| 2M UVC CAMERA                          | 2         | 0.2%    |
| Unknown (3730304231393931415053)       | 1         | 0.1%    |
| Sweex                                  | 1         | 0.1%    |
| Philips (or NXP)                       | 1         | 0.1%    |
| Oculus VR                              | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 58        | 5.74%   |
| IMC Networks Integrated Camera                      | 39        | 3.86%   |
| Microdia Integrated_Webcam_HD                       | 36        | 3.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 28        | 2.77%   |
| Chicony HD Webcam                                   | 27        | 2.67%   |
| Realtek Integrated_Webcam_HD                        | 26        | 2.57%   |
| Logitech Webcam C270                                | 26        | 2.57%   |
| Acer Integrated Camera                              | 24        | 2.37%   |
| Sunplus Integrated_Webcam_HD                        | 17        | 1.68%   |
| Chicony HP HD Camera                                | 16        | 1.58%   |
| Microdia USB 2.0 Camera                             | 12        | 1.19%   |
| Apple Built-in iSight                               | 12        | 1.19%   |
| Quanta HP HD Camera                                 | 11        | 1.09%   |
| Logitech HD Pro Webcam C920                         | 10        | 0.99%   |
| Syntek Integrated Camera                            | 9         | 0.89%   |
| Realtek Integrated Webcam HD                        | 9         | 0.89%   |
| Lite-On Integrated Camera                           | 9         | 0.89%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 0.89%   |
| Chicony HP HD Webcam                                | 9         | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 8         | 0.79%   |
| Chicony USB2.0 Camera                               | 8         | 0.79%   |
| Acer HD Webcam                                      | 8         | 0.79%   |
| Acer BisonCam, NB Pro                               | 8         | 0.79%   |
| Quanta HD User Facing                               | 7         | 0.69%   |
| Microdia Integrated Webcam                          | 7         | 0.69%   |
| Chicony HD User Facing                              | 7         | 0.69%   |
| Apple FaceTime HD Camera                            | 7         | 0.69%   |
| Realtek USB Camera                                  | 6         | 0.59%   |
| Quanta VGA WebCam                                   | 6         | 0.59%   |
| Luxvisions Innotech Limited HP HD Camera            | 6         | 0.59%   |
| Logitech HD Webcam C615                             | 6         | 0.59%   |
| Logitech C922 Pro Stream Webcam                     | 6         | 0.59%   |
| Chicony USB 2.0 Camera                              | 6         | 0.59%   |
| Chicony HP Truevision HD                            | 6         | 0.59%   |
| Acer EasyCamera                                     | 6         | 0.59%   |
| Samsung Galaxy A5 (MTP)                             | 5         | 0.49%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.49%   |
| Microdia Sonix USB 2.0 Camera                       | 5         | 0.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.49%   |
| Logitech Webcam C310                                | 5         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 83        | 38.43%  |
| Synaptics                  | 77        | 35.65%  |
| Shenzhen Goodix Technology | 27        | 12.5%   |
| Upek                       | 9         | 4.17%   |
| AuthenTec                  | 9         | 4.17%   |
| Elan Microelectronics      | 7         | 3.24%   |
| LighTuning Technology      | 2         | 0.93%   |
| STMicroelectronics         | 1         | 0.46%   |
| Samsung Electronics        | 1         | 0.46%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 26        | 12.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 10.65%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 10.19%  |
| Shenzhen Goodix  Fingerprint Device                                        | 17        | 7.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 5.09%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 4.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 3.24%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 2.78%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.31%   |
| Validity Sensors VFS491                                                    | 4         | 1.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.85%   |
| Synaptics  WBDI                                                            | 4         | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.85%   |
| Synaptics WBDI Device                                                      | 3         | 1.39%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.39%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.93%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.93%   |
| Elan ELAN:Fingerprint                                                      | 2         | 0.93%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.93%   |
| AuthenTec AES1600                                                          | 2         | 0.93%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.46%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.46%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.46%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.46%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.46%   |
| Samsung Fingerprint Device                                                 | 1         | 0.46%   |
| AuthenTec AES2810                                                          | 1         | 0.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 34        | 39.08%  |
| Broadcom                   | 31        | 35.63%  |
| Gemalto (was Gemplus)      | 6         | 6.9%    |
| Upek                       | 4         | 4.6%    |
| O2 Micro                   | 3         | 3.45%   |
| Hewlett-Packard            | 3         | 3.45%   |
| Lenovo                     | 2         | 2.3%    |
| Yubico.com                 | 1         | 1.15%   |
| Watchdata                  | 1         | 1.15%   |
| Clay Logic                 | 1         | 1.15%   |
| Athena Smartcard Solutions | 1         | 1.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 32        | 36.78%  |
| Broadcom 5880                                                                | 12        | 13.79%  |
| Broadcom 58200                                                               | 8         | 9.2%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 8.05%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 5.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.6%    |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.6%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.45%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 3         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.3%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.15%   |
| Watchdata USB Key                                                            | 1         | 1.15%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 1.15%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.15%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.15%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.15%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1209      | 69.28%  |
| 1     | 419       | 24.01%  |
| 2     | 97        | 5.56%   |
| 3     | 16        | 0.92%   |
| 4     | 3         | 0.17%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 215       | 33.49%  |
| Graphics card            | 128       | 19.94%  |
| Chipcard                 | 77        | 11.99%  |
| Net/wireless             | 69        | 10.75%  |
| Multimedia controller    | 33        | 5.14%   |
| Sound                    | 27        | 4.21%   |
| Camera                   | 21        | 3.27%   |
| Unassigned class         | 18        | 2.8%    |
| Communication controller | 16        | 2.49%   |
| Card reader              | 9         | 1.4%    |
| Storage                  | 8         | 1.25%   |
| Bluetooth                | 6         | 0.93%   |
| Network                  | 5         | 0.78%   |
| Net/ethernet             | 4         | 0.62%   |
| Firewire controller      | 3         | 0.47%   |
| Storage/raid             | 1         | 0.16%   |
| Modem                    | 1         | 0.16%   |
| Flash memory             | 1         | 0.16%   |

